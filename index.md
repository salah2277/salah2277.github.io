---
layout: "default"
title: "🚀 steve - Control Apps Quickly and Easily"
description: "🚀 Automate Mac applications using the Accessibility API with this CLI tool for seamless testing and AI control."
---
# 🚀 steve - Control Apps Quickly and Easily

<img src="steve-logo.webp" alt="steve" width="400">

## 🔗 Download Now

[![Download steve](https://img.shields.io/badge/Download%20steve-latest-brightgreen)](https://github.com/mikker/steve/releases/latest)

## 📥 Download & Install

To get started with steve, visit this page to download the latest version: [Releases Page](https://github.com/mikker/steve/releases/latest).

You can also install using Homebrew if you have it on your Mac. Open your terminal and run these commands:

```
brew tap mikker/tap
brew install steve
```

## 🚀 Getting Started

Once you have installed steve, you can start using it right away. This tool helps you control Mac applications using the Accessibility API. It is perfect for automated testing and managing applications through scripts.

### 💻 System Requirements

- Operating System: macOS 10.14 or later 
- A working installation of Homebrew if you choose to use it

## 📜 Usage Instructions

All commands output structured text to the console. For exceptions like screenshots, steve outputs a PNG file unless you specify an output file with `-o` or `--output`.

You can get the results in JSON format by adding `--format json` or using `-j`. Errors will display in the terminal, and any failed command returns a non-zero exit code.

### 🛠️ Examples

#### Text Output

When you run commands in text mode, the output looks something like this:

```
- Extensions
  frame: x=837 y=157 w=885 h=814
```

#### JSON Output

When using JSON format, it will appear like this:

```
{"ok":true,"data":...}
{"ok":false,"error":"message"}
```

## 🎮 Application Control Commands

Here are some of the basic commands to drive applications:

- **List Applications**: To see all the applications on your Mac, run:
  ```
  steve apps
  ```
  
- **Focus on an Application**: You can bring an application into focus by name or process ID:
  ```
  steve focus "AppName"
  steve focus --pid 1234
  steve focus --bundle "com.example.app"
  ```

- **Launch an Application**: To open an application, use:
  ```
  steve launch "com.example.app" --wait
  ```

## 🔍 Key Features

- **Accessibility**: Directly interacts with Mac applications.
- **Automation**: Great for automated testing setups.
- **Control**: Provides commands to launch, focus, and manage applications.
- **Output Flexibility**: Returns outputs in both plain text and JSON formats for easy parsing.

### 👩‍💻 Additional Information

The commands return structured data, making it easier for users to integrate with other programs or scripts. If you need help with a specific command, you can type:

```
steve --help
```

This will provide you with a list of all available commands and options.

## 📞 Support

If you encounter issues or have questions, feel free to raise them in our [Issues Page](https://github.com/mikker/steve/issues). We are here to help you!

## 🗒️ Changelog

Stay tuned for updates! You can follow the changelog in the [Releases Page](https://github.com/mikker/steve/releases/latest) to know what’s new in each version.

By following these steps, you will be able to install and run steve effectively. Enjoy leveraging the power of Mac applications through the Accessibility API!