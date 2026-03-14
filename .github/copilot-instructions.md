# Copilot Workspace Instructions

## Must do before coding
- [ ] Run `dotnet build SocOps/SocOps.csproj`
- [ ] Run `dotnet test` (if tests exist)
- [ ] Run analyzer/lint in your editor

## Quick start
1. Install .NET 10 SDK.
2. From repo root run: `dotnet run --project SocOps/SocOps.csproj`
3. Open `http://localhost:5166`.

## Quick commands
- `dotnet build SocOps/SocOps.csproj`
- `dotnet run --project SocOps/SocOps.csproj`

## Project at a glance
- Blazor WASM app in `SocOps/`
- UI components in `SocOps/Components`
- Game logic in `SocOps/Services`
- Data in `SocOps/Data`

## Troubleshooting
- `dotnet clean SocOps/SocOps.csproj` then run again.
- If port in use: `dotnet run --project SocOps/SocOps.csproj --urls "http://localhost:5000"`.
