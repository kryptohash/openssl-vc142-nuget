# openssl-vc141-nuget
OpenSSL library nuget package for Visual Studio 2019 C++ (msvc142) Project.

## Nuget Gallery
- [NuGet Gallery | openssl-vc142 1.1.1](https://www.nuget.org/packages/openssl-vc142)

## Usage
Run the following command in the Package Manager Console on Visual Studio 2019.
```
PM> Install-Package openssl-vc142
```

## How to package (for Package Owner)
Run the commands below on the Developer Command Prompt for VS 2019.
```
build-win32.bat

cd packaging\nuget
package.bat
```
