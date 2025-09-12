# Input to Json

The **Input to Json** project, converts command-line arguments into a structured **JSON** object.

> **Note:** Automatically includes the current year.

## Directory Structure

```text
└── InputToJson
    ├── InputToJson.sln
    └── src
        ├── App
        │   ├── App.fsproj
        │   ├── Program.fs
        └── Library
            ├── Library.fs
            └── Library.fsproj
```

## How to use

1. Download or clone the repository.
2. Use the command `dotnet run` in the `src/App` directory followed by any argument.
