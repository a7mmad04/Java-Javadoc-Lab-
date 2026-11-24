# Java Javadoc Lab – SortExample

## Contents
- `SortExample.java`: formatted Java source code with Javadoc comments.
- `docOutput/`: generated HTML Javadoc documentation.

## Requirements
- JDK installed (the `java`, `javac`, and `javadoc` commands available in the terminal).

## Compile and run
Open a terminal in this folder and run:

```bash
javac SortExample.java
java SortExample
```

Expected output:

```text
[3, 6, 10, 12, 13, 24, 70, 90]
[1, 2, 3, 5, 6]
Is array2 sorted? true
```

## Generate Javadoc from the command line
Run:

```bash
javadoc -d docOutput *.java
```

Then open `docOutput/index.html` in a web browser.

## Generate Javadoc in NetBeans
1. Open the project and open `SortExample.java` under Source Packages.
2. Choose **Run → Generate Javadoc**.
3. Inspect the generated HTML documentation.
4. To auto-format code in NetBeans, use **Alt + Shift + F** or **Source → Format**.

## Submit through GitHub
1. Create a new GitHub repository (for example, `Java-Javadoc-Lab`).
2. Add `SortExample.java`, `README.md`, and the generated `docOutput` folder.
3. Commit and push the files.
4. Submit the repository URL to your instructor.

> Author: Ahmad Osama Alsharawneh.
