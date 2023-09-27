Tutorial: Create a .NET class library using Visual Studio
![Csharp](https://github.com/NicoleKelsey/WebsiteREADME/assets/127091448/648c721c-49e4-4d9b-809a-2aa98c23391e)


## Description

### In this tutorial, you create a simple class library that contains a single string-handling method.

### A class library defines types and methods that are called by an application. If the library targets .NET Standard 2.0, it can be called by any .NET implementation (including .NET Framework) that supports .NET Standard 2.0. If the library targets .NET 7, it can be called by any application that targets .NET 7. This tutorial shows how to target .NET 7.

### When you create a class library, you can distribute it as a NuGet package or as a component bundled with the application that uses it.

## Create a class library project

### 1.Add a new .NET class library project named "StringLibrary" to the solution.

### Right-click on the solution in Solution Explorer and select Add > New Project.

### 2.On the Add a new project page, enter library in the search box. Choose C# or Visual Basic from the Language list, and then choose All platforms from the Platform list. Choose the Class Library template, and then choose Next.

### On the Configure your new project page, enter StringLibrary in the Project name box, and then choose Next.

### 3.On the Additional information page, select .NET 7 (Standard-term support), and then choose Create.

### Check to make sure that the library targets the correct version of .NET. Right-click on the library project in Solution Explorer, and then select Properties. The Target Framework text box shows that the project targets .NET 7.0.

### If you're using Visual Basic, clear the text in the Root namespace text box.

![pic2](https://github.com/NicoleKelsey/WebsiteREADME/assets/127091448/b6a88b2a-6cd8-459b-893f-4c3836b3ff4a)

### 4.For each project, Visual Basic automatically creates a namespace that corresponds to the project name. In this tutorial, you define a top-level namespace by using the namespace keyword in the code file.

### Replace the code in the code window for Class1.cs or Class1.vb with the following code, and save the file. If the language you want to use isn't shown, change the language selector at the top of the page.
