# Hello World Program

This project is only intended to test if the current machine can
run [Java](https://en.wikipedia.org/wiki/Java_(programming_language)) program without errors. <br>
This project uses **IntelliJ Build System** to build the project, which is not that important for the purpose of this
project.

## Dependencies

1. [JDK](https://www.oracle.com/java/technologies/downloads/)

#### Optional Dependencies

1. IDE: [IntelliJ](https://www.jetbrains.com/idea/)

## Usage without any IDE

```bash
# For Linux based systems
# Compile the code
javac src/Main.java -d out/production/HelloWorld

# run the code
java -classpath out/production/HelloWorld Main
```

```
:: For Windows based systems

:: Compile the code
javac src\Main.java -d out\production\HelloWorld

:: Run the code
java -classpath out\production\HelloWorld Main
```

## Usage with [IntelliJ](https://www.jetbrains.com/idea/) IDE

IntelliJ is IDE developed by Jetbrains exclusively to code in Java. It is freely available as Community Edition and as
paid version as well, which you can use for free for educational
purposes [Get Started](https://www.jetbrains.com/community/education/#students)

1. Open project with [IntelliJ](https://www.jetbrains.com/idea/)
2. Choose **Main** configuration from the toolbar
3. Click ▶ on toolbar which looks like this ![toolbar](readme_assets/toolbar.png)

<p align="center">
    <img src="readme_assets/demo.gif" alt="animated" />
</p>

## Contributing

Although, there is little to no scope for contributing, pull requests are welcome. For major changes, please open an
issue first to discuss what you would like to change.

## License

[MIT](LICENSE.txt)
