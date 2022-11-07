This is the smallest TypeScript program which validates a coherent error. Use this for whatever purpose you need.

```
file.ts:1:7 - error TS2322: Type 'number' is not assignable to type 'string'.

1 const a: string = 0;
        ~

Found 1 error in file.ts:1
> tsc --extendedDiagnostics

Files:                          2
Lines of Library:               0
Lines of Definitions:           8
Lines of TypeScript:            2
Lines of JavaScript:            0
Lines of JSON:                  0
Lines of Other:                 0
Identifiers:                   10
Symbols:                       17
Types:                         75
Instantiations:                 0
Memory used:               23525K
Assignability cache size:       0
Identity cache size:            0
Subtype cache size:             0
Strict subtype cache size:      0
I/O Read time:              0.00s
Parse time:                 0.00s
Program time:               0.00s
Bind time:                  0.00s
Check time:                 0.01s
printTime time:             0.00s
Emit time:                  0.00s
Total time:                 0.01s
```