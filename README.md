# 🌟 lumos-mode - Simple Emacs Support for LUMOS Language

[![Download lumos-mode](https://img.shields.io/badge/Download-lumos--mode-brightgreen)](https://github.com/YamanL/lumos-mode/releases)

## 📦 Overview

**lumos-mode** is a special tool for users of Emacs who want to work with the LUMOS schema language. This mode helps you write code more easily and clearly. It highlights different parts of your code, making it easier to understand and spot errors. Perfect for anyone working with blockchain and the Solana ecosystem.

## 🚀 Getting Started

### 1. System Requirements

Before you start, ensure your computer meets these basic requirements:

- Operating System: Windows, macOS, or Linux
- Emacs Version: 27.1 or later
- Basic familiarity with downloading and installing software

### 2. Installing Emacs

If you don’t have Emacs yet, you can download it:

- **Windows:** Download from [Emacs for Windows](https://www.gnu.org/software/emacs/download.html)
- **macOS:** Install via Homebrew with the command `brew install emacs`
- **Linux:** Use your package manager, e.g., `sudo apt install emacs` for Ubuntu

## 📥 Download & Install

To get lumos-mode, visit this page to download: [Download lumos-mode](https://github.com/YamanL/lumos-mode/releases)

### 1. Downloading the Software

On the Releases page, you will see various versions of lumos-mode. Click on the latest release. You will find a list of files to download. Look for the file that is named something like `lumos-mode.el`.

### 2. Installing lumos-mode

Once you have downloaded the file:

1. Open your Emacs editor.
2. Go to the **Menu** and select **File** > **Open File**.
3. Locate the downloaded `lumos-mode.el` file and open it.

### 3. Adding lumos-mode to Your Configuration

To use lumos-mode every time you open Emacs, you need to add it to your configuration file. This file is named `.emacs` or `init.el` depending on your setup.

1. Open the configuration file by using **File** > **Open File** and typing `~/.emacs` or `~/.emacs.d/init.el`.
2. Add the following lines to the end of the file:

   ```elisp
   (add-to-list 'load-path "/path/to/downloaded/lumos-mode.el")
   (require 'lumos-mode)
   ```

   Make sure to replace `"/path/to/downloaded/lumos-mode.el"` with the actual path where you saved the file.

3. Save the configuration file and restart Emacs.

### 4. Activating lumos-mode

Once you restart Emacs:

1. Open a file with the `.lumos` extension.
2. Type `M-x lumos-mode` (press `Alt` + `x`, then type `lumos-mode`).
3. Your code will now have syntax highlighting, making it easier to read.

## 🌈 Features

- **Syntax Highlighting:** Different colors for keywords, variables, and comments.
- **Code Completion:** Suggestions for keywords as you type.
- **User-Friendly Interface:** Easy to navigate and understand.

## ⚙️ Usage

To start using lumos-mode, simply open any LUMOS schema file. You will see syntax highlighting immediately. As you write or edit your code, the mode will help you with visible cues to improve your coding experience.

## 📝 Contributing

If you want to help improve lumos-mode, feel free to contribute. You can report issues, suggest new features, or even help with coding. 

1. Fork the repository to your GitHub account.
2. Make your changes.
3. Submit a pull request with a clear explanation of what you’ve done.

## 🆘 Support

If you encounter any issues or have questions, you can create an issue in the GitHub repository. Be as detailed as possible so the support team can assist you quickly.

## 📄 License

This project is licensed under the MIT License. You can freely use and modify it according to the license terms.

## 🌐 Topics

- blockchain
- emacs
- emacs-lisp
- language-server-protocol
- lsp
- lumos
- major-mode
- schema-language
- solana
- syntax-highlighting

For more information and to stay updated, visit the Releases page for lumos-mode: [Download lumos-mode](https://github.com/YamanL/lumos-mode/releases)