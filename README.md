# SonghayCore.Newtonsoft

## core reusable, opinionated Newtonsoft concerns for my C# projects

**NuGet package 📦:** [`SonghayCore.Newtonsoft`](https://www.nuget.org/packages/SonghayCore.Newtonsoft/)

This repo is intended to sit next to `SonghayCore` [[GitHub](https://github.com/BryanWilhite/SonghayCore)], providing Core support for Newtonsoft-based routines.

### `Songhay.Extensions`

The Songhay System uses imperative C# code with a view to make it more functional in an effort to control complexity and enhance maintainability.

The preference for [extension methods](https://github.com/BryanWilhite/SonghayCore/tree/master/SonghayCore/Extensions) encourages stateless, reusable routines (many of them are “pure” functions).

Notable extensions:

- [`JObjectExtensions`](https://github.com/BryanWilhite/SonghayCore.Newtonsoft/blob/main/SonghayCore.Newtonsoft/Extensions/JObjectExtensions.cs) — defines conventions around the `Newtonsoft.Json.Linq.JObject` from [James Newton King](https://github.com/JamesNK).

@[BryanWilhite](https://twitter.com/BryanWilhite)
