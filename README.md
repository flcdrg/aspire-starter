# aspire-starter

Implementation of the .NET Aspire starter template

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
