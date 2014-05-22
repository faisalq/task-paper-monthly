# TaskPaper Month Generator

**[matthewmcvickar.github.io/taskpaper-month-generator](http://matthewmcvickar.github.io/taskpaper-month-generator)**

Given a list of tasks, generates a list of days and tasks for a specified month that can be pasted into TaskPaper for a monthly schedule.

For use with [Taskpaper Tiles](https://github.com/matthewmcvickar/taskpapertiles), my [TaskPaper](http://www.hogbaysoftware.com/products/taskpaper)-based productivity framework.


## Instructions

Go to the **[TaskPaper Month Generator](http://matthewmcvickar.github.io/taskpaper-month-generator)**.

To add tasks to a day, enter the day number, start a new line, and list each new task on a new line, like you would in TaskPaper. Start a new line and press `Tab` to start an indented note. Colons after day names are not required, but can be used. Same goes for dashes in front of tasks.

### Example

```
1
to-do item

14
another task
  notes

29
task
yet another task
  notes and details
  another note
```

The generated TaskPaper month will be updated as you type. Hit the **Copy** button to copy it to your clipboard, then paste it into a Taskpaper document.

To generate an empty month, click the **Empty** button above the editor.


## Nifty Features

- The `Tab` key works in the editor, to allow for notes.
- Generates a link to generate the next month at the end of the list.
- Quick copy-to-clipboard button.
- Utilizes local storage so that your list of monthly tasks is retained between visits.


## Planned Features

- A syntax for tasks that happen on the last day of the month.
- A syntax for tasks that happen on the same day every week.


## Credits

- [jQuery Throttle/Debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/)
- [ZeroClipboard](http://zeroclipboard.org/)
- [Foundation Icons](http://zurb.com/playground/foundation-icon-fonts-3)
- [Erik Meyer's Reset](http://meyerweb.com/eric/tools/css/reset/)
- [jQuery](http://jquery.com/) • [SASS](http://sass-lang.com/)
- [SublimeText](http://www.sublimetext.com/) • [CodeKit](https://incident57.com/codekit/) • [Chrome Developer Tools](https://developer.chrome.com/devtools)


## Thanks

- [Justin Falcone](http://justinfalcone.com)
- [Cody Robbins](http://twitter.com/codyrobbins)
