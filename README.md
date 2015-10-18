Visual Studio Toolsets
======================

This fork of Gavin Pugh's [vs-android](https://github.com/gavinpugh/vs-android) with inspirations taken from [vs-tool](https://github.com/juj/vs-tool) provides a collection of scripts and utilities to support integrated development with external compiler and linker toolchains under Microsoft Visual Studio 2013 or higher. It is released under the terms and conditions of the [zlib license](LICENSE.txt).

## Features

  * Seamlessly integrates external toolchains into Visual Studio.
  * Adds toolsets as new solution platforms and thus can be added to existing solutions.
  * Adapts the project properties dialogs to show the parameters specific to each toolchain.

## Installation

  1. Navigate to the following directory:
  
    For VS2013: `C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\V120\Platforms`   
    For VS2015: `C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\V140\Platforms`

  2. Copy all folders from this repository to that location.
