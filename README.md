<h1 align="center">
  <img src="./src/assets/image/logo.png" alt="Clash" width="128" />
  <br>
  Continuation of <a href="https://github.com/zzzgydi/clash-verge">Clash Verge</a>
  <br>
</h1>

<h3 align="center">
A Clash Meta GUI based on <a href="https://github.com/tauri-apps/tauri">Tauri</a>.
</h3>

## Install

Click on the corresponding link below to download the installation package. Supports Windows (x64/x86), Linux (x64/arm64) and macOS 10.15+ (intel/apple).

[[Windows x64](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/Clash.Verge_1.5.0_x64-setup.exe)]
[[Windows x86](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/Clash.Verge_1.5.0_x86-setup.exe)]
[[Windows arm64](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/Clash.Verge_1.5.0_arm64-setup.exe)]

[[macOS intel](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/Clash.Verge_1.5.0_x64.dmg)]
[[macOS apple](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/Clash.Verge_1.5.0_aarch64.dmg)]

[[Linux x64 AppImage](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/clash-verge_1.5.0_amd64.AppImage)]
[[Linux x64 deb](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/clash-verge_1.5.0_amd64.deb)]
[[Linux x86 AppImage](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/clash-verge_1.5.0_i386.AppImage)]
[[Linux x86 deb](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/clash-verge_1.5.0_i386.deb)]
[[Linux arm64 deb](https://github.com/i-panel/clash-verge-rev/releases/download/v1.5.0/clash-verge_1.5.0_arm64.deb)]

Or you can build it yourself. Supports Windows, Linux and macOS 10.15+

Notes: If you could not start the app on Windows, please check that you have [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section) installed.

## Features

- Since the clash core has been removed. The project no longer maintains the clash core, but only the Clash Meta core.
- Profiles management and enhancement (by yaml and Javascript). [Doc](https://clash-verge-rev.github.io)
- Simple UI and supports custom theme color.
- Built-in support [Clash.Meta(mihomo)](https://github.com/MetaCubeX/mihomo) core.
- System proxy setting and guard.

#### TG Group: [@clash_verge_rev](https://t.me/clash_verge_rev)

## Preview

![preview](./docs/preview.gif)

### FAQ

#### 1. **macOS** "Clash Verge" is damaged and can't be opened

open the terminal and run `sudo xattr -r -d com.apple.quarantine /Applications/Clash\ Verge.app`

## Development

See [CONTRIBUTING.md](./CONTRIBUTING.md) for more details.

To run the development server, execute the following commands after all prerequisites for **Tauri** are installed:

```shell
pnpm i
pnpm run check
pnpm dev
```

## Todos

> This keng is a little big...

## Disclaimer

This is a learning project for Rust practice.

## Contributions

Issue and PR welcome!

## Acknowledgement

Clash Verge rev was based on or inspired by these projects and so on:

- [zzzgydi/clash-verge](https://github.com/zzzgydi/clash-verge): A Clash GUI based on tauri. Supports Windows, macOS and Linux.
- [tauri-apps/tauri](https://github.com/tauri-apps/tauri): Build smaller, faster, and more secure desktop applications with a web frontend.
- [Dreamacro/clash](https://github.com/Dreamacro/clash): A rule-based tunnel in Go.
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo): A rule-based tunnel in Go.
- [Fndroid/clash_for_windows_pkg](https://github.com/Fndroid/clash_for_windows_pkg): A Windows/macOS GUI based on Clash.
- [vitejs/vite](https://github.com/vitejs/vite): Next generation frontend tooling. It's fast!

## License

GPL-3.0 License. See [License here](./LICENSE) for details.
