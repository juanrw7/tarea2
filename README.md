# Theory of Computation Assignment 2 - Barendregt Numerals 

> **Course:** SI1001 Theory of Computation  
> **Instructor:** Sergio Ramírez Rico  
> **Deadline:** April 24

## Authors
| Name | Email |
|------|-------|
| Juan Manuel Ramirez | jmramirezw@eafit.edu.co |
| Samuel Serna| sserna@eafit.edu.co |


---

## Environment

| Component | Version / Details |
|-----------|------------------|
| **OS** | Windows 10 / 11 + WSL 2 (Ubuntu 22.04.4 LTS) |
| **Lambda Shell** | `0.9.9.1` (compiled from source) |
| **GHC / Haskell Platform** | ` 9.12.2` (only for building Lambda Shell) |

> ℹ️ If you need to install Lambda Shell from scratch, follow the PDF linked in the assignment:  
> <https://asr.github.io/courses/programs-installations-tips-and-tricks.pdf>

> ℹ️ You can also follow the instructions in the shared YouTube video:  
> <https://www.youtube.com/watch?v=jRxm5sm1ChI>


---

## Launching the project
Make sure the versions of the program match.

Two ways to launch this project.

### To launch the project only using the ".lambda file"

1. Launch Lambda Shell in your console.
```bash
$ lambdaShell
```
*Lambda Shell should launch and give you the version.

2. Load the Lambda file.
```bash
load barendregt-numerals.lambda
```
Or use the relative path if the file is in another directory.
```bash
load "../src/barendregt-numerals.lambda"
```

3. Evaluate the examples.

For example:
```bash
predTwo
```

### To launch the project using a command file like "test.ls"

This option pre-feeds all the necessary commands to Lambda Shell, made for "automated test runs".
```bash
$ lambdaShell < tests.ls
```
Note you still need the ".lambda file and its correct relative path in the command file"

---

## References

* [Programs and Tools: Installations, Tips and Tricks](https://asr.github.io/courses/programs-installations-tips-and-tricks.pdf)
* [Instalacion WSL y LambdaShell (Video)](https://www.youtube.com/watch?v=jRxm5sm1ChI)
* [GHCup First Steps](https://www.haskell.org/ghcup/steps/)
* [Lambda Shell GitHub Repository](https://github.com/robdockins/lambda-shell)
* Built in manual in Lambda Shell ":help"
