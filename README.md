<div align="center">

# Everforest · Prism

**A quiet grove holds the morning; moss and stone keep the evening. Let each thought find a softer shade of green.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-a7c080?labelColor=2d353b)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-a7c080?labelColor=2d353b)
[![License: MIT](https://img.shields.io/badge/license-MIT-a7c080?labelColor=2d353b)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-everforest-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-everforest-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-everforest-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Everforest's warm, green-toned light and dark medium palettes meet in one theme, with softened forest surfaces and restrained natural accents.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![Everforest · Prism in Tine dark mode](docs/everforest-dark.png)

### Light mode

![Everforest · Prism in Tine light mode](docs/everforest-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-everforest-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#FDF6E3` | `#2D353B` |
| Sidebar | `#F4F0D9` | `#232A2E` |
| Body | `#5C6A72` | `#D3C6AA` |
| Heading | `#5C6A72` | `#D3C6AA` |
| Accent | `#8DA101` | `#A7C080` |
| Links | `#286983` | `#7FBBB3` |
| Tags | `#5D7410` | `#A7C080` |
| Mark background | `#FAEDCD` | `#4D4C43` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Everforest Light / Dark Medium](https://github.com/sainnhe/everforest) at `85a86eb62409e3ec88713bff3d1b9d7374e112e4`, under MIT; see [LICENSE](LICENSE). Both modes follow the official Everforest Light and Dark palettes at the default medium contrast, which are available in the Codex theme family. Tine surface roles are mapped independently; the documented light text and tag adjustments support contrast on the package's declared surfaces.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-everforest-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.

