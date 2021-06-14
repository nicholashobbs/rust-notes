# rust-notes

## Language Constructs

### Data Structures

struct S {}
enum E {}
static X: T = T();
const X: T = T();	
let mut x: T;	
S { x: y }	
E::C { x: y }	
s.x	

### References & Pointers
&S - shared reference 
&s	 - shared borrow
ref s	 - bind by reference
*r - dereference
/a - lifetime parameter

### Functions & Behavior
trait
impl
fn
const
async
fn() -> S
|| closure
move
return 
unsafe

### Control Flow
while
loop
for x in iter
if x else 
label 
break
continue await
reuturn

### Organizing Code
mod - module
use 
pub use
extern crate

### Type Aliases and Casts
type T = S
SElf
self
S as T

### Macros & Attributes
m!()
#attr 
#![attr

### Pattern Matching
match
let S(x) = get();
if let
while let
E::A => {} match arm


### Generics & Constraints
S<T>
S<T: R>
  
### Strings & Chars
### Documentation
### Miscellaneous

## Behind the Scenes

### The Abstract Machine
### Memory & Lifetimes
### Language Sugar
### Types, Traits, Generics

### Data Layout

### Basic Types
### Custom Types
### References & Pointers
### Closures
### Standard Library Types
 
## Standard Library

### One-Liners
### Thread Safety
### Dynamically / Zero Sized Types
### Iterators
### Number Conversions
### String Conversions
### String Output

## Tooling

### Project Anatomy
### Cargo
### Cross Compilation
### Tooling Directives

## Coding Guides

### Idiomatic Rust
### Async-Await 101
### Closures in APIs
### Unsafe, Unsound, Undefined
### API Stability

## Misc

### Links & Services
### Printing & PDF
