# Aviv Yamin's Final Project

## What did I built
I've built a Kanban website that allows you to store your task by their status.

### Page Structure

There are 3 `section` elements. One for to-do tasks, one for in-progress tasks, and one for done tasks.

Each `section` contains:

- [ ] a `ul` element with the appropriate class - `to-do-tasks`/`in-progress-tasks`/`done-tasks`
- [ ] an `input` element with an appropriate id - `add-to-do-task`/`add-in-progress-task`/`add-done-task`
- [ ] a `button` element with an appropriate id - `submit-add-to-do`/`submit-add-in-progress`/`submit-add-done`
- [ ] Each `ul` should contain task elements, which are `li` elements with the `task` class.

In addition the page contains:

- [ ] a heading with a `page-title` id
- [ ] a global input with the `search` id

### Interaction

- [ ] When the user clicks on one of the add-task buttons, a new task will be added to the respective list. The task content will be taken from the respective input field.
- [ ] Trying to submit empty tasks will cause an alert.
- [ ] Double clicking a task element will enable editing its text. When the task element loses focus (`blur` event) the change will be saved.
- [ ] Hovering over a task element and pressing `alt + 1-3` will move the task to the appropriate list (`1`: todo, `2`: in-progress, `3`: done).
- [ ] The search input filters tasks case-**in**sensitively, so that only tasks that match the search string are displayed. The filter is reapplied every time the user changes the content of the search input (on **every keystroke**).

### Storage

- [ ] The data of all the tasks is saved to `localStorage` following any changes made to the data. The data is saved under a storage key named `tasks`. 

- [ ] API integration:

  - [ ] There are save and load buttons that sync the current tasks to the API.
  - [ ] If the data loaded from the API is different from the local data, it will replace the local data with the API data. It will update both the `localStorage` and the DOM.

