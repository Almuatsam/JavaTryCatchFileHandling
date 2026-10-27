# Java Try-Catch and File Handling

## Description

This project demonstrates how to copy the contents of a text file using Java's `BufferedReader` and `BufferedWriter`, with exception handling using `try-catch`.

## Features

- Reads text from `input.txt` using `BufferedReader`.
- Copies the content to `output.txt` using `BufferedWriter`.
- Uses try-with-resources to close files automatically.
- Handles file and input/output errors using `IOException`.
- Displays a success message when copying completes.
- Displays an error message if copying fails.

## Project Files

- `FileCopy.java` — Java program that copies the file.
- `input.txt` — Source text file.
- `output.txt` — Destination file created by the program.
- `.gitignore` — Excludes compiled Java class files.

## Requirements

- Java Development Kit (JDK)
- PowerShell or another terminal

## How to Run

1. Open a terminal in the project folder.
2. Compile the program.

   ```bash
   javac FileCopy.java
   ```

3. Run the program.

   ```bash
   java FileCopy
   ```

## Expected Output

On success:

```text
File copied successfully.
```

If the source file is missing, the program displays an error message.

## Concepts Practiced

- File handling in Java
- `BufferedReader` and `BufferedWriter`
- Try-with-resources
- Exception handling with `IOException`
- Reading and writing text files