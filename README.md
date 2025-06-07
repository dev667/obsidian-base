---
tags:
  - vaulthealth
---

# README

About this vault.

This is a base setup to get started with Obsidian. It integrates well into a wide range of workflows, optimizes and prettifies the experience.

You got a [[ROOT|Homepage]] to layout important things and a [[TODO]] list.

The vault is configured to sort pasted attachments, your daily and digital notes automatically. Keep your vault organised and clean!

It also uses the Iconic and File Color extension to change the icons and colors of your notes in the side pane. See the [[TODO]] note or the [[Dataview Examples|Overview Notes]] for example.

> [!Tip]
> The most important thing in this repository might be the `.obsidian` directory with all configurations I made!



# How to apply

0. Install `Obsidian` (if not already installed)

1. Clone this repository

```bash
git clone https://github.com/dev667/obsidian-base.git
```

2. Open Obsidian, create a new Vault and enable `community plugins`

3. Drop the content of the cloned repository into your vault (with File Manager of your choice)

>[!]Note
>Do not forget the hidden directiory `.obsidian`. It contains the configuration and settings I made.



# How to use

Shortcuts:

ctl + arrowleft: opens left side pane
ctl + arrowright: opens right side pane

alt + n: new daily note

ctl + o: open a file from Quick Switcher
ctl + p: open command palette

ctl + ,; open settings
esc: close an opened window





# Settings and Plugins

## Basic Extensions


Improve built in tools:

- Settings Search
- Auto Link Title
- Advanced Canvas
- Advanced Slides
- Advanced Tables
- Code Styler
- Outliner
- Admonitions
- Natural Language Dates: easily create dates @Today
- PDF++
- Image Toolkit

- Quick Switcher++
- Omnisearch


Prettify the explorer:

- File Explorer Note Count
- Iconic: add icons to the explorer
- File Color: colorize the explorer


Ease of use:

- Easy Typing (Word like syntax formatting)
- ~~Highlightr, cMenu~~ -> Editing Toolbar
- Image in editor: Shows images in source mode


## Automation and Organisation

- Auto Note Mover
- Custom Attachment Location
- Folder Links


## Keep Your Vault Clean and Steady

- Find orphaned files and broken links!!
- Linter
- Random Note (Core Plugin: Alt + R) -> Rediscover your notes
- Hider: Hide things from the GUI of Obsidian
- Homepage


## Smarter Plugins

- Templater
- Periodic Notes
- Data View
- Meta bind (for buttons):

```meta-bind-button
label: This is a button
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: command
    command: workspace:export-pdf

```


## Homepage

- Homepage
- Banners
- Multi-Column Markdown

Rice up your homepage with `Dataview`, `Tracker` and columns.

### Tracker Example:

``` tracker
searchType: tag
searchTarget: daily
folder: /
startDate:
endDate:
bar:
    title: "Bar Chart"
    xAxisLabel: Date
    yAxisLabel: Value
```


## Math

- LaTeX Suit
- Extended MathJax
- Completr


## Writing

- Automatic Table Of Contents
- Zotero Integration
- Pretty BibTex


## Additional

- Privacy Glasses (blur out content)
- Style settings (good for styling??)
- Charts (when you need to create charts in markdown)
- Export To Anki


For task management:

- Kanban
- Tasks
