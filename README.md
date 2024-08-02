# Enhanced.AssemblyMarkers

This package contains a source generator that creates a C# marker classes for assembly.

## Features

- [x] Generates a public marker class in `Projects` namespace.
- [x] Generates an internal shortcut class `This`.

## Installation

```bash
dotnet add package Enhanced.AssemblyMarkers
```

## Usage

```csharp
var thisAssembly = This.Assembly;
```

```csharp
var domainAssembly = Projects.MyNamespace_Domain.Assembly;
```
