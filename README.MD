
# Note App 📝

## Introduction:

👋 Welcome to the Simple Note App! This Node.js project offers a straightforward solution for managing your notes via the command line. Its core functionalities include adding, removing, listing, and reading notes. Designed for simplicity and efficiency, it's a perfect starting point for understanding basic Node.js development and command-line interaction. Dive in and streamline your note-taking process with ease! 🚀

## Simple Note App

This is a simple command-line note-taking application built using Node.js. It allows users to add, remove, list, and read notes.

## Installation

Ensure you have Node.js installed on your system.

Clone the repository using the following command:

```bash
git clone https://github.com/iamNithiiN/noteApp.git
```

You can install the required dependencies using npm:

```bash
npm install yarg chalk
```
or simply run `npm install` on your command line. 

## Usage Instructions

The application supports the following commands:

- `add`: Add a new note.
  - Options:
    - `--title`: Title of the note (required).
    - `--body`: Body/content of the note (required).
  - Example:
    ```
    node app.js add --title="Title of the Note" --body="Content of the Note"
    ```

- `remove`: Remove an existing note.
  - Options:
    - `--title`: Title of the note to be removed (required).
  - Example:
    ```
    node app.js remove --title="Title of the Note"
    ```

- `list`: List all existing notes.
  - Example:
    ```
    node app.js list
    ```

- `read`: Read a specific note.
  - Options:
    - `--title`: Title of the note to be read (required).
  - Example:
    ```
    node app.js read --title="Title of the Note"
    ```
## Example Usage

### Add a new note
> node app.js add --title="Title of the Note" --body="Content of the Note"

### Remove a note
> node app.js remove --title="Title of the Note"

### List all notes
> node app.js list

### Read a specific note
> node app.js read --title="Title of the Note"


## Code Explanation

- `app.js`: Main entry point of the application, where commands are defined using yargs.
- `notes.js`: Contains the implementation of note-related functionalities.
- External Dependencies: 
  - `chalk`: For colorful console output.
  - `yargs`: For command-line argument parsing.

## Conclusion

Feel free to explore the application and utilize its features to manage your notes efficiently!



