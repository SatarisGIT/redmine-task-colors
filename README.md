# redmine-color-tasks

Redmine color tasks is a custom style file thats adds colours to redmine tasks in any view.
Thats add __status__ colours on table-row backgrounds, and __priorities__ lights in right side of task row

## Default settings

### Status
| Status  | Color | Style |
| ------------- | ------------- | ------------- |
| New           | red   | .status-1  |
| In progress   | blue  | .status-2  |
| Resolved      | green | .status-3  |
| Feedback      | red   | .status-4  |
| Closed        | black | .status-5  |
| Rejected      | black | .status-6  |

### Priority
| Status  | Color | Style |
| ------------- | ------------- | ------------- |
| Low          | Content  | .priority-1  |
| Normal       | Content  | .priority-2  |
| High         | Content  | .priority-3  |
| Urgent       | Content  | .priority-4  |
| Immediate    | Content  | .priority-5  |

![redmine-color-tasks-screenshot](https://github.com/SatarisGIT/redmine-task-colors/blob/master/redmine-task-colors.png?raw=true)

## Installation

  - Move to your current redmine location > current theme folder > __stylesheets__
  -- example **gitmike** style on ubuntu: (/usr/share/redmine/public/themes/__redmine-theme-gitmike__/stylesheets)
  - Drag and drop `color-task.css` file to __stylesheets__ folder
  - Open `application.css` in __stylesheets__ folder, and add line bellow on top of file

```css
@import url(../stylesheets/color-task.css);
```

## Todos

 - Better hover effects with colours
 - Better description
 - Some animations

License
----
MIT