**English** | [Português](README.pt-BR.md)

# Contact Book in C

A terminal application to add, list, edit, remove and search contacts, with data saved to a file. I built it to practice structs, file handling and code organization in C, with no external libraries, only stdio, stdlib and string from the standard library.

## Features

- Add a contact
- List saved contacts
- Edit an existing contact
- Remove a contact
- Search for a contact
- Persistent storage in a file (read and write with fopen/fread/fwrite)

## Tech stack

- C
- Standard library (stdio, stdlib, string)
- Structs to model contacts
- File handling for data persistence

## How to run

```
gcc agenda.cpp -o agenda
./agenda
```

## Project structure

```
c-agenda-system/
├── agenda.cpp
└── README.md
```

## Author

Daniel Augusto Silva
