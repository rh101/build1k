# 1kiss (1k)

A cross-platform one step build powershell script with auto setup general dependent tools.  
Your programing life will relex if you're using 1k!
  
[![Release](https://img.shields.io/github/v/release/simdsoft/1kiss?include_prereleases&label=release)](../../releases/latest)
[![build](https://github.com/simdsoft/1kiss/actions/workflows/build.yml/badge.svg)](https://github.com/simdsoft/1kiss/actions/workflows/build.yml)
[![dist](https://github.com/simdsoft/1kiss/actions/workflows/dist.yml/badge.svg)](https://github.com/simdsoft/1kiss/actions/workflows/dist.yml)
[![Downloads](https://img.shields.io/github/downloads/simdsoft/1kiss/total.svg?label=downloads&colorB=orange)](../../releases/latest)

## opensources
- [![zlib](https://img.shields.io/badge/zlib-green.svg)](https://github.com/madler/zlib)
- [![openssl](https://img.shields.io/badge/openssl-green.svg)](https://github.com/openssl/openssl)
- [![jpeg-turbo](https://img.shields.io/badge/jpeg%2d%2dturbo-green.svg)](https://github.com/libjpeg-turbo/libjpeg-turbo)
- [![curl](https://img.shields.io/badge/curl-green.svg)](https://github.com/curl/curl/releases)
- [![luajit](https://img.shields.io/badge/luajit-green.svg)](https://github.com/LuaJIT/LuaJIT)
- [![angle](https://img.shields.io/badge/angle-green.svg)](https://github.com/google/angle) - Windows Only
- [![c-ares](https://img.shields.io/badge/c--ares-green.svg)](https://github.com/c-ares/c-ares)

## Notes

- *Since v81, use xcframework for apple platforms*

## Build Targets:

- osx: 
  - arm64 (M1+)
  - x86_64
- linux: x86_64
- ios:
  - arm64
  - arm64 simulator
  - x86_64 simulator
- tvos:
  - arm64
  - arm64 simulator
  - x86_64 simulator
- android
  - armv7
  - arm64
  - x86 (DEPRECATED)
  - x86_64
- win32 (Windows Desktop Apps)
  - x86 (DEPRECATED)
  - x86_64
- winrt/winuwp (Windows Universal Apps)
  - x86_64
  - arm64

## refers

- cppwinrt: Since axmol-2.1-`LTS`: migrate from `C++/CX` to [`cppwinrt`](https://learn.microsoft.com/en-us/windows/uwp/cpp-and-winrt-apis/move-to-winrt-from-wrl) for breaking c++ standard limition, benefits to use c++20 on all target platforms.
- chrome releases: https://chromiumdash.appspot.com/fetch_releases?channel=Stable&platform=Windows&num=1
