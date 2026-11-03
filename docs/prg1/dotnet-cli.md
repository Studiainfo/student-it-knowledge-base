# Ściąga: .NET CLI

| Polecenie | Przykład | Opis |
|---|---|---|
| `dotnet --version` | `dotnet --version` | Sprawdza zainstalowaną wersję .NET SDK. |
| `dotnet --list-sdks` | `dotnet --list-sdks` | Wyświetla wszystkie dostępne wersje SDK. |
| `dotnet new list` | `dotnet new list` | Wyświetla dostępne szablony projektów. |
| `dotnet new console` | `dotnet new console` | Tworzy aplikację konsolową w bieżącym katalogu. |
| `dotnet new console -n` | `dotnet new console -n MyApp` | Tworzy aplikację konsolową w katalogu `MyApp`. |
| `dotnet restore` | `dotnet restore` | Pobiera zależności wymagane przez projekt. |
| `dotnet build` | `dotnet build` | Kompiluje projekt i pokazuje komunikaty o błędach. |
| `dotnet run` | `dotnet run --project MyApp` | Buduje i uruchamia wskazany projekt. |
| `dotnet clean` | `dotnet clean` | Usuwa pliki wygenerowane podczas kompilacji. |

## Przykładowa sesja

```bash
dotnet --version
dotnet new console -n MyApp
dotnet restore
dotnet build
dotnet run --project MyApp
dotnet clean
```