---
tags:
  - vaulthealth
---
About this vault.

This is a base setup to get started with Obsidian. It integrates well into a wide range of workflows, optimizes and prettifies the experience.

You got a [[ROOT|Homepage]] to layout important things and a [[TODO]] list.

The vault is configured to sort pasted attachments, your daily and digital notes automatically. Keep your vault organised and clean!

It also uses the Iconic extension to change the icons of your notes. See the [[TODO]] note or the [[Dataview Examples|Overview Notes]] for example.

> [!Tip]
> The most important thing in this repository might be the `.obsidian` directory with all configurations I made!



# Settings and plugins

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
- Natural Language Dates (create dates)
- PDF++
- Image Toolkit

- Quick Switcher++
- Omnisearch


Prettify the explorer:

- File Explorer Note Count
- Iconic (iconize the explorer)
- File Color (colorize the explorer)


Ease of use:

- Easy Typing
- ~~Highlightr~~ -> Editing Toolbar
- Image in editor: Shows images in source mode


## Automation and organisation

- Auto Note Mover
- Custom Attachment Location
- Folder Links


## Smarter plugins

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


## Keep your vault clean and steady

- Find orphaned files and broken links
- Linter
- Smart Random Note
- Hider
- Homepage

## Math

- LaTeX Suit
- Extended MathJax
- Completr

## Writing

- Automatic Table Of Contents
- Zotero Integration
- Pretty BibTex

## Homepage

- Homepage
- Banners
- Multi-Column Markdown

Rice up your homepage with `Dataview`, `Tracker` and columns.

### Tracker example:

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


## Additional

- Privacy Glasses (blur out content)
- Style settings (good for styling??)
- Charts (when you need to create charts in markdown)


For task management:

- Kanban
- Tasks