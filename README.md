# hello-zig

I'm just playing around with Zig here to get a feel for it and understand 
what it's about. 

I work mainly with Rust recently, so that'll be my biggest point of comparison.


## Things I like

- Nice to have a C/C++ compatible package manager!
- Easy zipping of tuples with for loop iterators is nice
- Install, LSP, everything works well out of the box.
- Defer for cleaning up when exiting a block seems nice

## Things I don't like 

- Why do I have to specify a file when I'm running tests
- I miss immutable vars by default already
- Auto imports where art though
- Test output, spits out a backtrace from the test framework first ("TestUnexpectedResult") 
    and then the actual test statement.
- Why snake case variables and camel case functions? This plus the string literal 
    for test case names is an eyesore.
- Can't have named unused variables. 

