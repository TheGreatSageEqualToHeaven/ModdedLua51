# Modded Lua51

Lua 5.1 with added functionality

# Syntax

- Removed ambiguous syntax error.
- Added LuaJIT suffixes.
- Added octal and binary numbers.
- Added continue statement.
- Added number separators.
- Added FiveM hash strings.
- Added bitwise operators.
- Added integer division.
- Added compound operators.
- Added local variable attributes. (Not run-time) 

# Bytecode Changes

[Bitwise operations and integer division had opcodes added between `OP_POW` and `OP_UNM`](https://github.com/TheGreatSageEqualToHeaven/ModdedLua51/blob/main/Compiler/LuaCompiler-O/lopcodes.h#L177-L183)
