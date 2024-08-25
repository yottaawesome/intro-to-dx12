# Introduction to 3D Game Programming with DirectX 12 source code

## Introduction

This is an unofficial fork of the [sample code repo]((https://github.com/d3dcoder/d3d12book)) for [Frank D. Luna's](http://www.d3dcoder.net/default.htm) excellent book [Introduction to 3D Game Programming with DirectX 12](http://www.d3dcoder.net/d3d12.htm). No representation is made that the source code belongs to me, it's simply reproduced here for convenience (so you don't need to dig up the physical media of the book) and remains the copyright of Frank D. Luna.

## Building

You'll need Visual Studio 2022 with the _Desktop development with C++_ and _Game development with C++_ Visual Studio workloads. Once you've satisfied these requirements, you should be able to open any of the included SLN files, build, and run the sample apps. Obviously, you also need to have a GPU that supports DirectX 12 for the samples to work correctly.

## Changes

All projects have been updated to use Visual Studio 2022 and retargeted to the latest Windows SDK. For convenience, an additional solution file AllProjects.sln has been added that includes all the projects.

## Considerations

If you're a novice looking to learn game development, this book and repo is probably not the best place to start, and you might be better off looking at resources for building games in Unreal Engine or Unity. This repo is mainly useful for professional and amateur game engine and graphics programmers wanting to learn how to work with DirectX 12. Needless to say, building a 3D game or rendering engine is _a lot of hard work_, and this book really only touches on the DX12 rendering aspect of such an engine, without touching on things like design, sound, gameplay, etc, so don't expect to master game development purely using this resource. 

## Additional resources

### General
* [Official book site](http://d3dcoder.net/default.htm)
* [Microsoft's DirectX Developer Blog](https://devblogs.microsoft.com/directx/)
* [Ryosuke's Learning DirectX 12 in 2023](https://whoisryosuke.com/blog/2023/learning-directx-12-in-2023/)

### Guides and tutorials
* [MSDN's Direct3D 12 Programming Guide](https://docs.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide)
* [Jeremiah van Oosten's DirectX 12 tutorial](https://github.com/jpvanoosten/LearningDirectX12/tree/v0.0.1)
* [Braynzar Soft's DirectX 12 tutorials](https://www.braynzarsoft.net/viewtutorial/q16390-04-directx-12-braynzar-soft-tutorials)

### Samples
* [GPUOpen-LibrariesAndSDK's D3D12 sample](https://github.com/GPUOpen-LibrariesAndSDKs/HelloD3D12)
* [Microsoft's DirectX graphics samples](https://github.com/microsoft/DirectX-Graphics-Samples)
* [Microsoft's XBox ATG samples](https://github.com/microsoft/Xbox-ATG-Samples) and [GDK samples](https://github.com/microsoft/Xbox-GDK-Samples/)

### Related technologies

* [Microsoft's DirectXTK12](https://github.com/Microsoft/DirectXTK12) and [Chuck Walbourn's samples](https://github.com/walbourn/directxtk-samples)
