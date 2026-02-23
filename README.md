# 🧮 mbase-cli - Easy Multi-Code Base Conversion

[![Download mbase-cli](https://img.shields.io/badge/Download-mbase--cli-blue?style=for-the-badge)](https://github.com/aoitge/mbase-cli/releases)

---

## 📘 What is mbase-cli?

mbase-cli is a simple app that helps you convert data between many different base encoding systems. Think of base encoding as a way to change your data into letters and numbers that computers and people can easily read and share.

This tool supports over 30 types of base codes, including popular ones like Base16, Base32, Base64, and others such as Base58 and Bech32. You do not need to install multiple programs or plugins. The whole app runs as a single file on your computer.

You can use mbase-cli to:
- Convert text or files from one base encoding to another.
- Decode encoded data back into its original form.
- Try new base systems not usually found in standard tools.

All you need is a computer and this single program file.

---

## 💻 Who Can Use It?

This app is designed for anyone who needs to work with base encoding without dealing with complex software. You do not need to know how to program or use command-line tools deeply. Basic computer skills are enough.

Typical users include:
- People curious about data encoding.
- Developers testing base conversion.
- Users trying to decode mysterious codes.
- Students learning data formats.

---

## 🖥️ System Requirements

To run mbase-cli you need a computer with:
- Windows 7 or newer, macOS 10.12 or newer, or a Linux distribution.
- At least 100 MB of free space.
- No special hardware needed.

The app is a standalone program and does not require internet after download.

---

## 🚀 Getting Started

Getting the program and running it is simple. You just need to download the right version for your system and open it.

### Step 1: Visit the Download Page

Click the big blue button at the top or go to:
[https://github.com/aoitge/mbase-cli/releases](https://github.com/aoitge/mbase-cli/releases)

### Step 2: Choose Your Version

On the release page:
- Pick the file that matches your computer system. For example, if you use Windows, look for a file ending with `.exe`. For macOS, a `.dmg` or `.zip` might be available.
- Downloads are organized by version. Select the latest stable release for best results.

### Step 3: Download and Save

Click the file link to download it. Save it somewhere easy to find, like your Desktop or Downloads folder.

### Step 4: Run the Program

- Windows: Double-click the `.exe` file.
- macOS: Open the `.dmg` or unzip the file and double-click the app.
- Linux: The file might be executable. If not, right-click, select Properties, and allow execution. Then double-click or run via terminal.

The program will open in a window, or in some cases, in a command line interface.

---

## 🚦 How to Use mbase-cli

mbase-cli works mainly through commands you type. However, it has clear instructions shown when you open it or ask for help.

Here’s a simple way to convert text:

1. Open mbase-cli.
2. Type the command to encode or decode.
3. Enter your data.
4. See the result instantly.

### Quick Example: Convert Text to Base64

1. Open mbase-cli.
2. Type: `mbase-cli encode base64`
3. When asked, type the text you want to convert.
4. Press Enter.
5. You will see your text changed to Base64 code.

### Decoding Example: Convert Base64 back to Text

1. Run: `mbase-cli decode base64`
2. Enter the Base64 code to decode.
3. You get your original text back.

---

## 🔧 Command Overview

Here are some commands you can use:

- `encode [base]` — converts text or file to the base format.
- `decode [base]` — converts data from the base format back.
- `convert [from-base] [to-base]` — switches data between two base types.

Replace `[base]` with the type you want, such as `base16`, `base32`, `base64`, `base58`, `bech32`, and many more.

Example:
```
mbase-cli convert base58 base64
```

---

## 📝 Inputs and Outputs

mbase-cli accepts both typed text and file inputs.

- For text, type or paste it directly when prompted.
- For files, add a file name after the command:
  ```
  mbase-cli encode base64 filename.txt
  ```
The program will read the file, convert it, and show the output.

You can also save output to a file by adding `-o outputfile.txt` at the end.

---

## ⚙️ Settings and Options

You can set options like line length and character sets depending on your needs.

- Use `--line-length` to break output lines into specific sizes.
- Use `--help` to get details for each command.

For example:
```
mbase-cli encode base64 --line-length 76
```
This splits the output into lines no longer than 76 characters.

---

## 📂 Supported Base Formats

mbase-cli supports many base encoding standards, including:

- Base16 (Hexadecimal)
- Base32
- Base36
- Base45
- Base58
- Base62
- Base64
- Base65536
- Base85
- Base91
- Bech32
- Proquint
- Quoted-Printable
- UUEncode

This wide range makes it useful for most encoding needs.

---

## ❓ Troubleshooting

If mbase-cli does not open or work as expected:

- Make sure you downloaded the correct file for your OS.
- Check that you have permission to run files from your download location.
- Try opening the program from a terminal or command prompt for error messages.
- Restart your computer if the program isn’t launching.
- Visit the GitHub page for updates or bug reports.

---

## 📥 Download & Install

Click the button below or visit the release page to get started:

[Download mbase-cli releases](https://github.com/aoitge/mbase-cli/releases)

On that page, pick the file matching your operating system. Download and save it. Then open and run as described above.

---

## 📖 Additional Help

mbase-cli includes help commands:

```
mbase-cli --help
mbase-cli encode --help
mbase-cli decode --help
```

These commands show all available options and example uses.

---

## 🛠️ Developer Info

mbase-cli is built with Rust and distributed as a lightweight, standalone binary. It does not require additional plugins or installation steps. The app is open source and hosted on GitHub.

Topics related include base encoding, multibase systems, CLI applications, and data formats.

---

## 📞 Getting Support

If you have issues or questions:

- Check the GitHub issues page for common problems.
- Look at the README and documentation on GitHub.
- Open a new issue if your problem is not listed.

---

This guide helps you download, install, and use mbase-cli to convert between many base encoding types quickly and easily.