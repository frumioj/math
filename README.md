# Racket 'math' package source

This repository forms part of the github.com/racket collection of repositories. Code in this repository may be modified by:

1. Checkout github.com/racket, which contains only the minimal code needed to build a version of the language, its REPL, and tools.
2. Fork this repository (github.com/math) to your own github account if you wish to make changes and submit them for review or inclusion in Racket.
3. In your local copy of Racket, you may type 'make' to build the code, resulting in a sub-directory also called racket, containing a 'bin' folder that has your newly-built executables for racket, raco et al.
4. Create a directory called "extra-pkgs" (or any other name you choose) and cd to that directory. 
5. Use the raco you built in (3.) (perhaps by adding racket/bin to your PATH via export PATH=~/src/racket/racket/bin:$PATH) to clone the package from github:
    raco pkg update --clone math
6. cd <your-local-copy-of-package>
7. Do the git fu to add your fork of the repository
    git remote rename origin upstream
    git remote add origin <your-fork>
8. Make your changes, rebuild Racket, and test (rinse & repeat as needed)
9. Commit your changes to your fork, and submit PR (if desired)
    
