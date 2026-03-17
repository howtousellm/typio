<div align="center">

# Typio

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

![Platform](https://img.shields.io/badge/platform-macOS-111827?logo=apple&logoColor=white)
![Input Method](https://img.shields.io/badge/type-English%20IME-2563eb)
![Local First](https://img.shields.io/badge/architecture-local--first-059669)
[![Sponsor](https://img.shields.io/badge/sponsor-Support%20Typio-ea580c?logo=githubsponsors&logoColor=white)](https://www.shuqihere.top/archive/projects/typio)

</div>

Typio is an English IME for non-native speakers on macOS.

It is designed for people who write in English daily but still lose flow on spelling, word choice, or constant input method switching.

Typio is especially useful for Korean, Japanese, and Chinese users who want an English-first typing experience instead of full Chinese IME behavior.

Everything is local-first: no cloud dependency, no sign-in flow, and no extra distractions. You type, Typio suggests practical candidates, and you keep writing.

Typio means the end of typo.

## Why Typio

- ✍️ **Stay in flow**: keep typing while candidates update in place.
- 🧠 **Practical suggestions**: focused on high-frequency English usage.
- 🧩 **Flexible panel styles**: horizontal, grid (multi-row), and vertical layouts.
- 🔒 **Private by default**: all input processing stays local.

## Screenshots

<div align="center">
  <video src="resources/images/readme/demo.mov" controls="controls" muted="muted" autoplay="autoplay" width="66.666%"></video>
</div>

<br/>

<table>
	<tr>
		<td align="center"><strong>Input Source Menu</strong></td>
		<td align="center"><strong>Language Mode Switch</strong></td>
	</tr>
	<tr>
		<td align="center"><img src="resources/images/readme/typio-menu-entry.png" alt="Typio input source menu" height="240" /></td>
		<td align="center"><img src="resources/images/readme/typio-language-toggle.png" alt="Typio language toggle" height="240" /></td>
	</tr>
	<tr>
		<td align="center"><strong>Multi-row Candidate Panel</strong></td>
		<td align="center"><strong>Settings: Panel Style</strong></td>
	</tr>
	<tr>
		<td align="center"><img src="resources/images/readme/typio-candidate-grid.png" alt="Typio candidate grid" height="240" /></td>
		<td align="center"><img src="resources/images/readme/typio-settings-panel-style.png" alt="Typio settings panel style" height="240" /></td>
	</tr>
</table>

## Install

For end users, download and run `typio-<version>.pkg`, then enable Typio in System Settings → Keyboard → Input Sources.

<div align="center">
  <img src="resources/images/readme/install-guide-1.png" alt="Allow applications from App Store & Known Developers" height="300" />
      
  <img src="resources/images/readme/install-guide-2.png" alt="Open typio-1.0.pkg anyway" height="300" />
</div>

In most cases, logout is not required. If Typio does not appear immediately, remove and add the source once. If it still does not show, log out and log back in.

## Build and Package

Use `sh scripts/build.sh` to build the app, `sh scripts/build-and-install.sh` for local developer install, and `sh scripts/package-pkg.sh` to generate the installer package at `dist/typio-<version>.pkg`.

If you need installer signing, set `INSTALLER_SIGN_IDENTITY` before packaging.

## Support Typio

Typio is built for the community. If you find it helpful, please consider supporting its development on my [personal blog](https://www.shuqihere.top/archive/projects/typio).

## About

Project home: https://github.com/howtoexitvim/Typio
