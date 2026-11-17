<!-- SPDX-FileCopyrightText: 2026 Progmasoft <support@progmasoft.com> -->
<!-- SPDX-License-Identifier: MIT -->

# Ariane.NET

Ariane.NET brings the diagnostics of [Ariane](https://github.com/Progmasoft/ariane) to .NET: reports drawn over the
source code they are about, with labels, notes and helps, by the Rust library Ariadne behind Ariane's C API.

It is for the languages of .NET 8 and later, such as C#, F# and Visual Basic. Its package is `Progmasoft.Ariane.NET`
on NuGet, and its types are in the namespaces `Progmasoft.Ariane.*`:

```bash
dotnet add package Progmasoft.Ariane.NET
```

No code is written yet; the first version of Ariane.NET follows the first release of Ariane.

## The Ariane family

| Repository | For |
| --- | --- |
| [Progmasoft/ariane](https://github.com/Progmasoft/ariane), Ariane | C, through its C API |
| [Progmasoft/arianex](https://github.com/Progmasoft/arianex), Arianex | C++17 |
| [Progmasoft/jariane](https://github.com/Progmasoft/jariane), JAriane | Java 21+ and the JVM 21+ languages with Java interop |
| [Progmasoft/arianekt](https://github.com/Progmasoft/arianekt), ArianeKt | Kotlin/JVM 25+ |
| [Progmasoft/ariane.net](https://github.com/Progmasoft/ariane.net), Ariane.NET | the .NET 8+ languages |
| [Progmasoft/hariane](https://github.com/Progmasoft/hariane), Hariane | Haskell, GHC 9.6+ |

## License

[MIT](LICENSE.txt). Progmasoft's own code is also covered by the [Progmasoft Patent Grant 1.1](PATENTS.md).
Participation follows the [Code of Conduct](CODE_OF_CONDUCT.md).
