-- sqlite editor

https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite

-- operator ??= (if null assign default value) 

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/null-coalescing-operator

-- run test help
dotnet test -h 

-- run test list available test
dotnet test -l

-- run test 
cd boilerplate/netcore/tests/Conduit.IntegrationTests

dotnet test -t (list available)
dotnet test (all)
dotnet test --filter CreateTests