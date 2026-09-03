# .NET Foundry

A hub for small, self-contained .NET and C# projects covering programming fundamentals, APIs, web development, architecture, tooling, cloud and practical engineering.

> Every project is independently runnable and intentionally focused.

## Project structure

```text
DotNetFoundry/
├── index.html
├── style.css
├── script.js
├── Ideas.md
├── projects/
│   ├── _template/
│   │   ├── DotNetFoundry.ProjectName.sln
│   │   ├── README.md
│   │   └── src/
│   │       └── DotNetFoundry.ProjectName/
│   │           ├── DotNetFoundry.ProjectName.csproj
│   │           └── Program.cs
│   └── ...
└── README.md
```

The hub automatically discovers project folders under `projects/`. `Ideas.md` is the backlog and source of truth for the collection.

## Add a project

1. Copy `projects/_template/` to a new folder.
2. Rename the solution, project, and namespaces as appropriate.
3. Implement the project described in `Ideas.md`.
4. Run `dotnet run` from the project directory.
5. Push the folder to GitHub.

## Project rules

- One project = one folder.
- .NET 10 is the baseline LTS platform.
- Prefer the .NET and Microsoft first-party libraries.
- Add external dependencies only when the project genuinely requires them.
- Keep every project independently runnable.
- Keep source code free of comments.
- Deployment is manual.
- No GitHub Actions or workflows are required.
