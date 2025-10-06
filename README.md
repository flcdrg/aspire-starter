# .NET Aspire Starter example

Implementation of the .NET Aspire starter template with the following options:

- .NET 10
- Using .slnx file
- Redis cache
- xUnit.NET tests (using [Microsoft.Testing.Platform](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test?WT.mc_id=DOP-MVP-5001655#microsofttestingplatform-mtp-mode-of-dotnet-test))
- GitHub Actions [workflow with test results](.github/workflows/dotnet.yml)
- Dependabot

## Created with

```bash
aspire new aspire-starter --use-redis-cache --test-framework xunit.net --xunit-version mtf --output .
```

Then migrate to .slnx file

```bash
dotnet sln migrate
```

Upgrade to .NET 10

```bash
dotnet tool install -g upgrade-assistant

upgrade-assistant upgrade
```
