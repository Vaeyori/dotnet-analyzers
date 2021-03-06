# .Net Analyzers

This projects goal is to have a single NuGet package that has a dependency on other .Net analyzer NuGet packages that are designed at improving coding standards, quality assurance and security.

## Analytics

![GitHub](https://img.shields.io/github/license/vaeyori/dotnet-analyzers?label=License)
![GitHub last commit](https://img.shields.io/github/last-commit/vaeyori/dotnet-analyzers?label=Latest%20Commit)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/vaeyori/dotnet-analyzers?label=Version&sort=semver)
![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/vaeyori/dotnet-analyzers?label=Dependencies)

## Usage

### Installation

Install via Package Manager

    Install-Package Vaeyori.Analyzers


### Included Analyzers

| Package Name | Summary |
|--|--|
| ClrHeapAllocationAnalyzer | A collection of heap allocation diagnostic analyzers that detect explicit and many implicit allocations |
| InclusivenessAnalyzer | A collection of analyzers used to detect inappropriate naming conventions within code to bring about inclusive behavior |
| Meziantou.Analyzer | A collection of analyzers to enforce good practices in terms of design, usage, security, performance and style |
| Microsoft.CodeAnalysis.NetAnalyzers | Primary analyzers for .Net 5+ |
| Microsoft.EntityFrameworkCore.Analyzers | Analyzers for Entity Framework Core library |
| Microsoft.VisualStudio.Threading.Analyzers | Static code analyzer to detect common mistakes or potential issues regarding threading and async coding |
| Nullable.Extended.Analyzer | A collection of analyzers used to detect unjustified usage of null-forgiving operators |
| Philips.CodeAnalysis.DuplicateCodeAnalyzer | A set of analyzers that help detect duplicate code |
| Philips.CodeAnalysis.MaintainabilityAnalyzers | A set of analyzers that help the maintainability of code bases |
| Philips.CodeAnalysis.MoqAnalyzers | A set of analyzers that help fix frequent issues with writing Moq tests |
| Puma.Security.Rules | A set of security analyzers that help identify OWASP Top 10, SANS/CWE Top 25, and other common insecure coding patterns |
| ReflectionAnalyzers | A collection of analyzers used to detect performance and improper usage of System.Reflection |
| Roslynator.Analyzers | A collection of 200+ analyzers for C#, powered by Roslyn |
| Roslynator.CodeAnalysis.Analyzers | A collection of analyzers for the Roslyn API |
| Roslynator.Formatting.Analyzers | A collection of analyzers to help with formatting of code |
| SecurityCodeScan.VS2019 | A collection of analyzers that help detect SQL Injection, Cross-Site Scripting, Cross-Site Request Forgery, XML eXternal Entity Injection and more |
| SonarAnalyzer.CSharp | Roslyn analyzers that spot Bugs, Vulnerabilities and Code Smells in your code |
| StyleCop.Analyzers | A collection of StyleCop rules as analyzers to enforce during build |
| xunit.analyzers | Helps developers find and fix frequent issues when writing tests and xUnit.Net extensibility code |

## Contribute

Contributions are always welcome! Please read the [contribution guidelines](/contributing.md) first.

## License

[MIT](https://choosealicense.com/licenses/mit/)
