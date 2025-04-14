# General instructions
- Only solve requested task
- I dont want reasoning unless I ask for it

# Code Standards
- Use LINQ & expressive syntax
- Use C# 10+ features
- Follow clean architecture principles
- Follow naming conventions:
  - Use PascalCase for classes, methods, public members
  - Use camelCase for local variables, private fields
  - Use UPPERCASE for constants
  - Prefix interfaces with 'I'
  - Only use '_' for ignore syntax, never for naming

# Quality Requirements
- Unit tests required for new features
- 80% test coverage minimum
- All tests MUST pass
- Global exception handling
- Input validation at boundaries

# .NET Guidelines
- Use C# 10+ features
- Prefer DateTimeOffset/NodaTime, No use of DateTime
- Use file-scoped namespaces
- Use Autofac for DI
- Use FluentValidation
- Async/await for I/O operations
- Optimize LINQ (avoid N+1)
- Use xUnit and FakeItEasy for mocks (nuget package) for .Net tests