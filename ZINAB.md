# Zinab

*Zinab Is Not A Backronym*

Zinab is an interpreted,
statically typed programming
language.

## Types

All types have move semantics: they are copied on assignment.

### Integer types

| Name | Description
|------|-------------
| I8   | 8-bit integer.
| I16  | 16-bit integer.
| I32  | 32-bit integer.
| I64  | 64-bit integer.
| U8   | Unsigned 8-bit integer.
| U16  | Unsigned 16-bit integer.
| U32  | Unsigned 32-bit integer.
| Bool | Boolean value stored as an 
         8-bit integer.

### Floating point

| Name | Description
|------|-------------
| F32  | 32-bit floating point.
| F64  | 64-bit floating point.

### Other

| Name | Description
|------|-------------
| Unit | A zero-size type with only one value: 
         ().

### Traits

| Name | Description
|------|-------------
| Value | An empty trait.

### AST Types

| Name | Description
|------|-------------
| Block | Contains a variable amount of 
          expressions.
| Expression | A trait type that can be evaluates to an Owned<Value>.
| Value | An empty trait.