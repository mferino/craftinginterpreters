# Crafting Interpreters

## LOX (Java based interpreter - PART 1)

### File Structure

/java/com/craftinginterpreters/lox

### How To Run

To compile (depending on if you need tools run or not): navigate to the java directory

```sh
javac -d . com/craftinginterpreters/lox/*.java
javac -d . com/craftinginterpreters/tool/*.java
```

To run interpreter in interactive mode: navigate to the java directory

```sh
java com.craftinginterpreters.lox.Lox
```

To run a source file:

```sh
java com.craftinginterpreters.lox.Lox <path to source file>
```

To build AST file 
```sh
java com.craftinginterpreters.tool.GenerateAst <path to output dir>
```
