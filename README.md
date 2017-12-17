# libsndfile.NET

This is [libsndfile](https://github.com/erikd/libsndfile) for .NET :)

[![NuGet](https://img.shields.io/badge/nuget-v1.0.0-blue.svg)](https://www.nuget.org/packages/libsndfile.NET/1.0.0)

## Features
- libsndfile API fully implemented
- supports all additional formats, i.e. FLAC, Ogg/Vorbis (binaries built using [vcpkg](https://github.com/Microsoft/vcpkg))
- friendly interface with patterns familiar to .NET coders
- works for AnyCPU, x86, x64

## Requirements
 - [Microsoft Visual C++ Redistributable for Visual Studio 2017](https://www.visualstudio.com/downloads/) (for the native libraries)

## Notes
 - basic functionality has been tested and works, e.g. reading and writing of audio
 - specialized features like reading special tags needs more testing
 - currently the only documentation is the [official one](http://www.mega-nerd.com/libsndfile/api.html)
 
