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

- Settings Search
- Auto Link Title
- File Explorer Note Count
- Iconic
- File Color
- Code Styler
- Image Toolkit
- PDF++
- Natural Language Dates
- Outliner
- Easy Typing
- Quick Switcher++
- Advanced Canvas
- Advanced Slides
- Highlightr
- CMenu


## Automation and organisation

- Auto Note Mover
- Custom Attachment Location
- Folder Links


## Smart plugins

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


## Keep your vault clean
- Find orphaned files and broken links
- Linter
- Smart Random Note
- Hider
- Homepage
- Banners

## Math
- LaTeX Suit
- Extended MathJax
- Completr



## Charts in your vault

Tracker

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



Charts
```chart
type: bar
labels: [1, 2, 3, 4, 5]
series:
  - title: Berlin
    data: [4, 17, 6, 20, 13]
tension: 0.24
width: 90%
labelColors: true
fill: true
beginAtZero: false
bestFit: false
bestFitTitle: undefined
bestFitNumber: 0
```
