Visual Studio Toolsets
======================

A collection of scripts and utilities to support integrated development with external compiler and linker toolchains under Microsoft Visual Studio 2013 or higher.

It is released under the terms and conditions of the [zlib license](LICENSE.txt). Uses [vs-android.Build.CPPTasks.Android.dll](Emscripten/vs-android.Build.CPPTasks.Android.dll) from [vs-android](https://github.com/gavinpugh/vs-android).

## Features

  * Seamlessly integrates external toolchains into Visual Studio.
  * Adds toolsets as new solution platforms and thus can be added to existing solutions.
  * Adapts the project properties dialogs to show the parameters specific to each toolchain.

The following toolsets are available:

  * **Clang** (platform toolset)
  * **Emscripten** (platform)
  * **GLSL** (build customization)

## Installation

  Copy all folders from this repository to the following location:
  
    For VS2013: "C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\V120" 
    For VS2015: "C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\V140"
