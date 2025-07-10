# osu!tools

### !!! These tools were made by the osu!lazer team. We at Tuyosu only forked them to work with our APIs. !!!
### For anyone that doesn't care about Tuyosu, the original repo is [here](https://github.com/ppy/osu-tools).

[![Build status](https://github.com/ppy/osu-tools/actions/workflows/ci.yml/badge.svg?branch=master&event=push)](https://github.com/ppy/osu-tools/actions/workflows/ci.yml)
[![CodeFactor](https://www.codefactor.io/repository/github/ppy/osu-tools/badge)](https://www.codefactor.io/repository/github/ppy/osu-tools) 
[![dev chat](https://discordapp.com/api/guilds/188630481301012481/widget.png?style=shield)](https://discord.gg/ppy)

Tools for [osu!](https://osu.ppy.sh).

# Current Versions

This is part of a group of projects which are used in live deployments where the deployed version is critical to producing correct results. The `master` branch tracks ongoing developments. If looking to use the correct version for matching live values, please [consult this wiki page](https://github.com/ppy/osu-infrastructure/wiki/Star-Rating-and-Performance-Points) for the latest information.

# Requirements

- A desktop platform with the [.NET 8.0 SDK](https://dotnet.microsoft.com/download) installed.
- When working with the codebase, we recommend using an IDE with intelligent code completion and syntax highlighting, such as the latest version of [Visual Studio](https://visualstudio.microsoft.com/vs/), [JetBrains Rider](https://www.jetbrains.com/rider/) or [Visual Studio Code](https://code.visualstudio.com/) with the [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) and [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) plugin installed.
- These instructions assume you have the the [CLI git client](https://git-scm.com/) installed, but any other GUI client such as GitKraken will suffice.

# Getting Started

## I just want to run it
- Clone the repository (`git clone --recursive https://github.com/Tuyosu/osu-tools`)
- Navigate to each tool's directory (i.e. `cd PerformanceCalculator`) and follow the instructions listed in the tool's README.
    - [PerformanceCalculator](https://github.com/ppy/osu-tools/blob/master/PerformanceCalculator/README.md) - A tool for calculating the difficulty of beatmaps and the performance of replays.
    - [PerformanceCalculatorGUI](https://github.com/ppy/osu-tools/blob/master/PerformanceCalculatorGUI/README.md) - A GUI tool for calculating the difficulty of beatmaps, changes in profile scores and leaderboards.

### Code analysis

Before committing your code, please run a code formatter. This can be achieved by running `dotnet format` in the command line, or using the `Format code` command in your IDE.

We have adopted some cross-platform, compiler integrated analyzers. They can provide warnings when you are editing, building inside IDE or from command line, as-if they are provided by the compiler itself.

JetBrains ReSharper InspectCode is also used for wider rule sets. You can run it from PowerShell with `.\InspectCode.ps1`. Alternatively, you can install ReSharper or use Rider to get inline support in your IDE of choice.

# Contributing

When it comes to contributing to the project, the two main things you can do to help out are reporting issues and submitting pull requests. You might want to refer to the [contributing guidelines](https://github.com/ppy/osu/blob/master/CONTRIBUTING.md) in the main osu! repository to understand how to help in the most effective way possible.

We love to reward quality contributions. If you have made a large contribution, or are a regular contributor, you are welcome to [submit an expense via opencollective](https://opencollective.com/ppy/expenses/new). If you have any questions, feel free to [reach out to peppy](mailto:pe@ppy.sh) before doing so.

# Licence

*osu!*'s code, framework, and tools are licensed under the [MIT licence](https://opensource.org/licenses/MIT). Please see [the licence file](LICENCE) for more information. [tl;dr](https://tldrlegal.com/license/mit-license) you can do whatever you want as long as you include the original copyright and license notice in any copy of the software/source.

Please note that this *does not cover* the usage of the "osu!" or "ppy" branding in any software, resources, advertising or promotion, as this is protected by trademark law.

Please also note that game resources are covered by a separate licence. Please see the [ppy/osu-resources](https://github.com/ppy/osu-resources) repository for clarifications.
