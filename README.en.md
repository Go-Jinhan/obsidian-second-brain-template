![Loose notes connected to an open notebook, with books and a pencil nearby](assets/second-brain-banner.png)

# Obsidian Second Brain Template

[한국어](README.md) · **English**

We read books, save useful articles, and jot down ideas. But when it is time to do something with them, those notes can be surprisingly hard to use. We search for something we already saved, or open a long note and wonder what mattered in it. I wanted **a collection of notes I could actually return to and use**.

Tiago Forte’s *Building a Second Brain* was the starting point. *CODE* gave me a way to move from collecting information to using it; *PARA* gave me a way to organize material around the work it supports. I added the *Zettelkasten* practice of writing ideas in my own words and connecting them. Command Space’s *CMDS* materials informed the library-like organization of Resources. Kim Ik-han’s Korean book *거인의 노트* also contributed the idea of revisiting records and developing the thinking in them.

This vault brings those approaches together in Obsidian. A passing thought can become material for a project, and what that project teaches you can support the next one. I removed my personal records from the structure I use and added guides and examples. I hope it gives you a useful place to start—and something you can make your own.

## Start with one note

Suppose you finish reading and wonder, “Why can I understand this while reading it, but struggle to explain it later?” Put that question in *Capture*. When you find a useful article, save its source and what you understood. Add a short summary at the top of the note. That is *Distill*: a way to see what matters before reading the full note again. The summary stays with the material it describes.

To try an answer, create a project: “Experiment with reading notes for four weeks.” **Bring the relevant material from Capture, Resources, and earlier projects into this project’s folder.** Read it, compare it, and improve it while doing the work. If several projects need the same reference, you can keep it in its original location and link to it.

When the experiment ends, return reusable methods and templates to *Resources*. Keep the project’s progress and results in *Archives*. If you have developed an idea that applies beyond this experiment, explain it in your own words in a *Permanent Note*. Your next project can begin with material you have already worked on.

There is a short example trail inside the vault: [a passing thought](<10. Capture/11. Zettelkasten-FleetingNotes/Example - Leave a Next Action.en.md>), [a reference note](<10. Capture/12. Zettelkasten-ReferenceNotes/Example - The Hemingway Bridge.en.md>), [a project](<20. Organize/21. 📦Projects/📦P-Example Reading Experiment/📦P-Example Reading Experiment.en.md>), and [a permanent note](<30. Express/31. Zettelkasten-PermanentNotes/Example - A Next Action Makes Restarting Easier.en.md>). These are fictional examples written to show how the pieces fit together.

## Finding your way around

```text
10. Capture
    11. Zettelkasten-FleetingNotes    Passing thoughts and questions
    12. Zettelkasten-ReferenceNotes   Sources and your understanding of them

20. Organize
    21. 📦Projects                   Work you intend to finish and its materials
    22. Areas                       Ongoing responsibilities and interests
    23. Resources                   Subject-based material to use again
    24. Archives                    Completed or inactive records

30. Express
    31. Zettelkasten-PermanentNotes  Ideas explained and connected in your own words
```

The four steps of *CODE* do not need four separate folders. *Distill* lives at the top of individual notes. *Express* also happens when you write, make something, or solve a problem inside a project.

Notes whose names begin with `_` explain their folder: what belongs there and how it connects to the rest of the vault. All folder and file names are in English. Korean guides have an English companion ending in `.en.md`, with a language link at the top.

## Open it in Obsidian

1. Select **Code → Download ZIP** in this repository and extract the download.
2. In Obsidian, choose **Open folder as vault** and select the extracted folder.
3. Read [Getting Started](<10. Capture/_Getting-Started.en.md>) and write one thing you want to remember today.

You can read the guides and examples and write notes without any extra plugins. To create notes from the included templates, continue with the setup below. One inbox and one project are enough to begin with.

## Create notes from templates

Install and enable **Templater** and **Periodic Notes** under **Settings → Community plugins**. The plugins themselves are not bundled with this vault.

Set Templater’s **Template folder location** to the following folder. It is included in the supplied settings, but check it after installing the plugin.

```text
20. Organize/23. Resources/📖1000. Reference/📚1090. Settings/📚1091. Templates
```

Run **Templater: Create new note from template** from the command palette and choose **TPL - Basic Note.en**. Select *Idea*, *Reference*, *Book*, or *Project*. The template creates the note’s contents and moves it to the appropriate folder. Templates without `.en` retain the Korean prompts.

A project opens with *Twyla Tharp First Memo*, *Project Progress*, and *The Hemingway Bridge*. Use them to record why you are starting, what you have done and learned, and where to pick up next time. The [Projects guide](<20. Organize/21. 📦Projects/_Projects.en.md>) also explains how to gather materials and redistribute them when the work is finished.

For a permanent note, create a note in `30. Express/31. Zettelkasten-PermanentNotes`, then use **Templater: Insert template** to insert **TPL - Permanent Note.en**.

### Daily, weekly, and monthly notes

Periodic notes live under this folder:

```text
20. Organize/23. Resources/📖1000. Reference/📚1010. Periodic Notes
```

In Periodic Notes, check these settings and select the English templates from the Templates folder above:

- **Daily**: the `1011. Daily` subfolder, format `YYYY-MM-DD (ddd)`, **TPL - Daily Note.en**
- **Weekly**: the `1012. Weekly` subfolder, format `GGGG-[W]WW`, **TPL - Weekly Note.en**
- **Monthly**: the `1013. Monthly` subfolder, format `YYYY-MM`, **TPL - Monthly Note.en**

The supplied settings select the Korean versions; change the three template selections to use English. Each folder is a subfolder of the full Periodic Notes path above. Weekly titles use ISO week numbers, such as `2026-W45`.

Automatic template execution on file creation is disabled. If a note created by Periodic Notes still contains `<%` code, run **Templater: Replace templates in the active file** once. Use daily notes for experiences, weekly notes for patterns and adjustments, and monthly notes for direction. The [Periodic Notes guide](<20. Organize/23. Resources/📖1000. Reference/📚1010. Periodic Notes/_Periodic-Notes.en.md>) explains the practice behind them.

## Make the structure yours

Resources includes example shelves for faith, work and business, economics, personal development, humanities, and other subjects. I adapted the classification and navigation approach I found in *CMDS* materials to my own interests. Keep the subjects you need and rename the rest. The numbers help you find things; they are not a ranking or a reading order.

If you move Books, Periodic Notes, Templates, or Attachments, also update the paths in templates and plugin settings. The [Resources guide](<20. Organize/23. Resources/_Resources.en.md>) explains how folders and links work together.

For the reasoning behind the structure and its references, read the [Design guide](<10. Capture/_Second-Brain-Design.en.md>). Adjust things as you use them. If you can return to a note, understand it, and put it to work, it is doing its job.

---

This is a review version ahead of public release. A license covering use, modification, and redistribution has not yet been selected.
