---
oneliner: Thin C# P/Invoke wrapper for Box2D v3 physics, this fork using Godot Vector types instead of System.Numerics
tags: [box2d, physics, pinvoke, wrapper, dotnet, csharp, godot, native-interop, rigid-body, game-physics]
stack: [C#, .NET, Box2D]
generated: 2026-09-06
commit: c23012d
placeholder: true
---
Box2dNet exposes virtually the entire Box2D v3 C API as static C# methods with the original identifiers, prioritizing a minimal, allocation-free surface over an idiomatic .NET API. It ships prebuilt native DLLs, a codegen tool (Box2dNetGen) that regenerates the wrapper from the Box2D source, .NET Task Parallel Library integration for Box2D's multithreaded solver, and helper types (NativeHandle, AsSpan properties) for dealing with IntPtr plumbing. This is a working, actively maintained fork of the upstream Box2dNet project, retargeted to use Godot's Vector types instead of System.Numerics.
