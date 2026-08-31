# level-01-csharp-basics Lesson 01: Variables

## 1) Goal
- Create and print simple C# variables.

## 2) Complete working code
```csharp
// Program.cs
// This lesson uses top-level statements for simplicity.
string learnerName = "Alex"; // string stores text
int completedLessons = 1;      // int stores whole numbers
bool isLearningApi = true;     // bool stores true/false

Console.WriteLine($"Learner: {learnerName}");
Console.WriteLine($"Completed lessons: {completedLessons}");
Console.WriteLine($"Learning API development: {isLearningApi}");
```

## 3) Comments explaining important lines
- `string`, `int`, and `bool` are beginner-friendly core data types.
- `$"..."` is string interpolation to print variable values clearly.

## 4) Commands to run the code
```bash
dotnet new console -n L01Variables --framework net10.0
cd L01Variables
# Replace Program.cs with the code above
dotnet run
```

## 5) Example API request
```http
# Not an API lesson yet. No HTTP request for this lesson.
```

## 6) Expected API response
```json
{
  "note": "No API response. This is a C# basics lesson."
}
```

## 7) Common mistakes
- Forgetting `;` at the end of statements.
- Using quotes with `int` values (`int x = "1";` is invalid).

## 8) Small practice task
- Add a `double progressPercent = 5.5;` variable and print it.

## 9) Complete task solution
```csharp
string learnerName = "Alex";
int completedLessons = 1;
bool isLearningApi = true;
double progressPercent = 5.5;

Console.WriteLine($"Learner: {learnerName}");
Console.WriteLine($"Completed lessons: {completedLessons}");
Console.WriteLine($"Learning API development: {isLearningApi}");
Console.WriteLine($"Progress: {progressPercent}%");
```
