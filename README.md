## Steps to start and develop a Haskell project

 ```
 stack new baseball simple
 cd baseball
 git init
 git add .
 git commit -m "Initial commit"
 add .gitignore
 edit cabbal file
 //Editign a src/Main.hs file 
 stack setup (in case no ghc has been installed)
 ```
### Loop (writing and refactoring)
 ```
 stack build
 stack exec baseball
 stack ghci ( it will load executable and library)
 stack build
 stack exec baseball
 ```
### Loop
```
 Adding tests
 edit cabal file
 stack test 
 Or (stack ghci baseball:tests)

 stack ghci
 writing/refactoring
 :reload in the REPL
```
