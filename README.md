# Tauri + Angular

This template should help get you started developing with Tauri and Angular.


# Prerequisites
Installing
The first step is to install [Rust](https://www.rust-lang.org/) and system dependencies. Keep in mind that this setup is only needed for developing Tauri apps. Your end-users are not required to do any of this.

Setting Up Windows
1. Microsoft Visual Studio C++ Build Tools
You will need to install Microsoft Visual Studio C++ build tools. The easiest way is to install Build Tools for Visual Studio 2022. When asked which workloads to install, ensure "C++ build tools" and the Windows 10 SDK are selected.
Microsoft Visual Studio Installer

2. WebView2
Tauri heavily depends on WebView2 to render web content on Windows, therefore you must have WebView2 installed. The easiest way is to download and run the Evergreen Bootstrapper from Microsoft's website.
The bootstrapper script will try to determine the correct architecture and version for your system. Still, if you run into issues (especially with Windows on ARM) you can select the correct standalone installer.

3. Rust
Lastly, go to https://www.rust-lang.org/tools/install to install rustup (the Rust installer). Note that you have to restart your terminal, and in some cases, Windows itself, for the changes to take effect.

Alternatively, you could use winget to install rustup using the following command in PowerShell:



## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) + [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template).
