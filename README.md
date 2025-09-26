# Input to Json

The **Input to Json** project, converts application arguments into a **JSON** object.

> **Note:** The JSON object includes the current year.

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
