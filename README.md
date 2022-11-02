# C#	

### C# vs .NET

**C# is a programming language.**

**.NET is a framework for building applications on Windows.** It consist of two components

- CLR (Common Language Runtime)
- Class Library

### CLR

When you compile an application, C# compiler compiles your code to IL (Intermediate Language) code. IL code is platform agnostics, which makes it possible to a take a C# program on a different computer with different hardware architecture and operating system and run it. For this to happen, we need CLR. When you run a C# application, CLR compiles the IL code into the native machine code for the computer on which it is running. This process is called Just-in-time Compilation (JIT).

**The compilation of IL code to native machine code at runtime is JIT Compilation.**

### Architecture of .NET Application

When we build an application with C# , application consist of building blocks called classes.

Class is container containing data and functions. As the number of classes in an application grows we need a way to organize these classes. That's where we use a namespace. So a namespace is a container for a related classes.

We need a different way of partitioning an application and that where we use an assembly. Assembly is a container for related name spaces. Assembly , physically its a file on the disk which can either be an executable or Dynamically linked library. **Assembly is a single unit of deployment of .NET applications.**



58410-17700

