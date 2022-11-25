# ModdedLua51

Lua 5.1 with added functionality

# Syntax

<div>Removed ambiguous syntax error.<\div>
Added LuaJIT suffixes.
Added octal and binary numbers.
Added continue statement.
Added number separators.
Added FiveM hash strings.
Added bitwise operators.
Added integer division.
Added compound operators.
Added local variable attributes. (Not compile-time!) 

# Bytecode Changes

[Bitwise operations and integer division had opcodes added between `OP_POW` and `OP_UNM`](https://github.com/TheGreatSageEqualToHeaven/ModdedLua51/blob/main/Compiler/LuaCompiler-O/lopcodes.h#L177-L183)
