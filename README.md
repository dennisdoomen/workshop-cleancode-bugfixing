# Prerequisites
* Visual Studio 2019 (16.8 or later), [Jetbrains Rider](https://www.jetbrains.com/rider/) (2020.3 or later) or Visual Studio Code with the [C# Extension](https://code.visualstudio.com/docs/languages/dotnet).
* .NET 5.0.101 SDK or later (can be downloaded [here](https://dotnet.microsoft.com/download/dotnet/5.0))

# Instructions
Fix a bug in `StringAssertions` that seems to think `encyclopædia` == `encyclopaedia`.
See https://docs.microsoft.com/en-us/dotnet/api/system.string.equals?view=netframework-4.8#System_String_Equals_System_String_System_StringComparison_

# Hint
Start with adding a new test to`StringAssertions` to reproduce the bug.
