# MINI USER GUIDE - PANDOC

## 1. Introduction
Pandoc is a universal document converter that allows you to convert files between formats such as Markdown, Word, PDF, and HTML.  
This guide covers the basic installation package and usage.

---

## 2. Installation

### Windows
- Download the installer from [Pandoc release page](https://github.com/jgm/pandoc/releases)  
- Run the `.msi` installer and follow the prompts  
- Open **Command Prompt** or **PowerShell**  
- Verify installation by running:

```pandoc -v ```

It should show the Pandoc version number if installed correctly.

### macOS
- Open Terminal

- If you have Homebrew, run:

```brew install pandoc ```

If you don’t have Homebrew, download the .pkg file from Pandoc’s website and install it.

- Verify your installation:
```pandoc -v```

### Linux (Ubuntu/Debian)
- Open Terminal
- Update your package list:

```sudo apt update```

- Install Pandoc:

```sudo apt install pandoc```

- Verify installation:

```pandoc -v```

## 3. Basic Usage
- Convert Markdown to Word:

```pandoc input.md -o output.docx```

- Convert Markdown to PDF:

```pandoc input.md -o output.pdf```

- Convert Word to Markdown:

```pandoc input.docx -o output.md```

- Convert PDF to Markdown:

```pandoc input.pdf -o output.md```

## 4. Common Options
- -o : specify output file

- --standalone : create a full standalone document

- --toc : add table of contents

## 5. Example Workflow
Write documentation in myproject.md

- Convert to Word:

```pandoc myproject.md -o output.docx```

- Convert to PDF:

```pandoc myproject.md -o output.pdf```

6. Resources

- [Pandoc official site](https://pandoc.org)
- [Pandoc user guide](https://pandoc.org/MANUAL.html)

