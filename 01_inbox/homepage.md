
This is an example homepage!

> [!NOTE] Some notable hotkey shortcuts to mention:
> - `cmd + n` = creates a new untitled note
> - `cmd + t` = (use in a new note or experiment to apply a protocol) - open templates
> - `cmd + f` = find on page
> - `cmd + shift + f` = open 'Omnisearch'
> - All hotkeys can be found under `settings -> hotkeys`

> [!INFO] FYI
> 1. All notes can be toggled between editing view (with live preview) and reading view. 
> ![[Screenshot 2025-03-29 at 5.26.00 PM.png|200]] 
> 2. To interface with a page in split view, click on the respective window. 
> - ![[Pasted image 20250329205639.png|400]]

# Notebook Dashboards 

## [[Protocols Dashboard]]

## [[Project 1 Dashboard]]

## [[Project 2 Dashboard]]

# Recent Experiments

## in-progress

```dataview
TABLE date_created, status, results
FROM #experiment 
WHERE status = "in-progress" AND file.name !="experiment"
SORT DESC
LIMIT 5
```

## complete

```dataview
TABLE date_created, status, results
FROM #experiment 
WHERE status = "complete" AND file.name !="experiment"
SORT DESC
LIMIT 5
```

## Future Experiments

- enter "someday" into the progress YAML to populate this table...
```dataview
TABLE date_created, status, results
FROM #experiment 
WHERE status = "someday" AND file.name !="experiment"
SORT DESC
LIMIT 5
```

# Outstanding Tasks 

Everyone has a different way they organize tasks. If you so choose to integrate all of a part of your task management into this lab notebook, I have setup a basic example of how that could look. 

Below is an example use case of the [tasks](https://publish.obsidian.md/tasks/Introduction) plugin to coalesce tasks delimited by a `- [ ] ` . Using a tasks code block, we can view all tasks in one place and query by varying attributes of an individual tasks. A full walkthrough of how to use this plugin can be found here: [Introduction - Tasks User Guide - Obsidian Publish](https://publish.obsidian.md/tasks/Introduction)

- [ ] Here is an example task in this note 📅 2025-03-29 🛫 2025-03-29 

> [!NOTE] All Tasks
> ```tasks
> ```


