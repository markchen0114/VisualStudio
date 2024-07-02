# Tools > NuGet Package Manager > Package Manager Console

# Install CLI
- Install-Package NuGet.CommandLine
# Create nuspec file
- nuget spec [project name]
# Create nupkg file
- nuget pack [project name]
# Push nupkg file
- nuget push [YourPackage.nupkg] -Source [NuGet Server] -Api-Key [ApiKey]
