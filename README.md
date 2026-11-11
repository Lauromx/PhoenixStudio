<p align="center">
  <img src="logo.png" alt="Phoenix Studio" width="160">
</p>

<h1 align="center">Phoenix Studio</h1>

<p align="center"><b>Visual designer and code editor for AutoIt.</b><br>
Draw your windows, write only the logic, get a clean <code>.au3</code>.</p>

<p align="center"><a href="README.es.md">Leer en español</a></p>

---

![Phoenix Studio main window](capturas/ventana-principal.png)

## What it is

Phoenix Studio is a native Windows application (no .NET, no runtime to install) where you **design the windows of an AutoIt program by dragging controls**, and it generates the AutoIt source for you. The generated code is plain, readable AutoIt: you can keep editing it by hand, and the designer keeps your event functions safe.

## Highlights

- **Visual form designer.** Drag, resize, align, snap to the grid and to guides, set the Tab order by clicking, copy and paste formatting, undo and redo, zoom.
- **Rich control palette.** Labels, inputs, buttons, checkboxes, radios, lists, combos, groups, tabs, list views and tree views (with groups, alternating rows, numeric and date sorting), menus and popup menus, tool bars, status bars, rich edit, date pickers, sliders, IP address, data-bound controls and more.
- **Properties inspector** with ready-made editors for lists, columns, menus, images, tree nodes, SQL and INI keys.
- **Events.** Pick an event, and a function with the right name is added to your code. The IDE only adds functions, it never deletes yours.
- **Code editor.** Syntax highlighting, autocompletion, a code library, find / replace / find in files, rename in code, comment and uncomment, a variables panel, and live error checking with **Au3Check**.
- **Run and compile.** Run with one key, stop, check, and compile to an `.exe` (32 or 64 bit) from project options such as icon, version and output folder.
- **Multi-window projects** (`.afp`) with a program file, plus a set of ready-to-use window templates.
- **Import existing AutoIt scripts** and keep working on them visually.
- **Data.** SQLite-backed controls and a grid that shows real records at design time, and report support.
- **Built-in AI assistant** (bring your own provider and key).
- **Interface in 9 languages:** Spanish, English, German, French, Italian, Polish, Portuguese, Russian and Chinese.

## Screenshots

| Tool palette and project structure | Edit menu |
|---|---|
| ![Tool palette](capturas/caja-de-herramientas.png) | ![Edit menu](capturas/menu-editar.png) |

## Requirements

- Windows 10 or 11, 64 bit.
- [AutoIt v3](https://www.autoitscript.com/site/autoit/downloads/) installed, to run, check and compile the programs you create. Phoenix Studio does not include AutoIt.

## Install

1. Download the latest `.zip` from the **Releases** page.
2. Check the SHA-256 shown in the release notes (see below).
3. Unzip it anywhere and run `ps.exe`. There is no installer and nothing is written outside its own folder and your user profile.

Check the download:

```powershell
Get-FileHash .\PhoenixStudio-vX.Y.zip -Algorithm SHA256
```

The value must match the one in the release notes.

> Windows SmartScreen or your antivirus may warn about a program that is not code-signed. If you downloaded it from this page and the hash matches, you can safely choose *More info > Run anyway*.

## Support the project

Phoenix Studio is free to use. If it saves you time and you want to help it keep growing, you can donate here (it is optional and never shown inside the program unless you open *Help > Donate*):

**https://paypal.me/laudrupmx**

## License and responsible use

Phoenix Studio is distributed **free of charge and without any warranty or liability**: the author is not responsible for what anyone does or may do with the program. It is a tool for writing scripting programs for Windows in a correct, ethical and good-faith way. It must not be used to create or spread viruses, malware, ransomware, worms or any hacking tool or attack of any kind, and the author does not support that in any form. Anyone may redistribute Phoenix Studio as long as it is **unmodified** (no reverse engineering or modification of any kind). **The programs you create with it belong to you**: you can distribute them freely, with no credit to Phoenix Studio and no payment to it, even if you sell them. Full terms in [LICENSE.txt](LICENSE.txt).

## Notes

- The source code is not published.
- **AutoIt is the creator of the language and of everything that makes the programs run.** Phoenix Studio is only an interface that makes it easier to create AutoIt scripts. AutoIt has its own rules and licenses, and they must be respected when using Phoenix Studio; Phoenix Studio complies with them.
- "AutoIt" is a trademark of its owners. Phoenix Studio is an independent tool and is not affiliated with or endorsed by the AutoIt project.
