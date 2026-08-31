# Learn C# API Development

Interactive, self-paced course repository for learning API development with **C#** and **ASP.NET Core** from beginner to advanced.

## How to use this repository

1. Start with **Level 01** and move forward in order.
2. In each lesson, complete sections top to bottom:
   - Goal
   - Working code
   - Run commands
   - Example request/response
   - Common mistakes
   - Practice task
   - Complete solution
3. Use `docs/COURSE_OUTLINE.md` to track lesson order.
4. Use `src/` for runnable project scaffolds and `tests/` for test scaffolds.
5. Use `docs/templates/LESSON_TEMPLATE.md` when adding new lessons.
6. Start with filled examples in:
   - `docs/lessons/level-01-csharp-basics/01-variables.md`
   - `docs/lessons/level-03-first-aspnet-core-api/04-run-the-app.md`

## Quick start (latest stable .NET)

```bash
dotnet --version
dotnet restore src/LearnCSharpApiDevelopment.sln
dotnet build src/LearnCSharpApiDevelopment.sln
dotnet test tests/LearnCSharpApiDevelopment.Api.Tests/LearnCSharpApiDevelopment.Api.Tests.csproj
```

## Repository structure

```text
docs/
  COURSE_OUTLINE.md
  templates/
    LESSON_TEMPLATE.md
  lessons/
    level-01-csharp-basics/
    level-02-api-fundamentals/
    ...
    level-12-deployment/
src/
  LearnCSharpApiDevelopment.sln
  LearnCSharpApiDevelopment.Api/
tests/
  LearnCSharpApiDevelopment.Api.Tests/
```

## Notes

- Lesson files are scaffolded for progressive expansion.
- Code projects are starter scaffolds intended for lesson-by-lesson updates.
