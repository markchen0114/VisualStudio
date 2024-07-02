# Tools > NuGet Package Manager > Package Manager Console

# Install CLI
- Install-Package NuGet.CommandLine
# Create nuspec file
- nuget spec [Package ID]
# Create nupkg file
- nuget pack [Package ID]
# Push nupkg file
- nuget push [YourPackage.nupkg] -Source [NuGet Server] -Api-Key [ApiKey]
