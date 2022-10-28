Visual Studio Toolsets
======================

A collection of scripts and utilities to support integrated development with external compiler and linker toolchains under Microsoft Visual Studio 2013 and 2015.

Uses [vs-android.Build.CPPTasks.Android.dll](Platforms/Emscripten/vs-android.Build.CPPTasks.Android.dll) from [vs-android](https://github.com/gavinpugh/vs-android).

The remaining files are released under the terms and conditions of the [BSD 2-clause license](LICENSE.txt).

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
  
    For Visual Studio 2017: %PROGRAMFILES(X86)%\Microsoft Visual Studio\2017\Community\Common7\IDE\VC\VCTargets
    For Visual Studio 2019: %PROGRAMFILES(X86)%\Microsoft Visual Studio\2019\Community\MSBuild\Microsoft\VC\v160
    For Visual Studio 2022: %PROGRAMFILES%\Microsoft Visual Studio\2022\Community\MSBuild\Microsoft\VC\v170
