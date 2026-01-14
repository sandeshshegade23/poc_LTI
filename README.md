Add-Migration InitialCreate
Update-Database

dotnet ef migrations add RenameAndAddColumn
dotnet ef database update
