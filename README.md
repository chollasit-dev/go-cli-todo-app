# Todo CLI App

A simple command-line TODO application written in Go and powered by [**Cobra**](https://github.com/spf13/cobra/blob/main/site/content/user_guide.md) library.

## Features

### Basic CRUD Operations

|              Function              | Status |
| :--------------------------------: | :----: |
|           Create a task            |   🚧    |
| List all ongoing and overdue tasks |   🚧    |
|        Mark completed tasks        |   🚧    |
|          Modifying a task          |   🚧    |
|          Deleting a task           |   🚧    |

### Sorted, Filter, and Formatted Display

Currently, the application only supported displaying all ongoing and overdue tasks while the completed are automatically hidden.

All tasks will be shown in the tabular format sorted from most recent to the oldest.

In the future, the application will support the following features:

- [ ] Show tasks filtered only (non-combined) by
  - [ ] Status: done, ongoing, overdue
  - [ ] Priority: high, medium, low
  - [ ] Time: today, this week, this month, this year

- [ ] Show tasks sorted by
  - [ ] Priority: high, medium, low
  - [ ] Time: ascending / descending

### Settings

- [ ] Support configuring via the CLI app or directly modify the TOML file `cli-todo-app.toml` at `$HOME/.config`.

### Additional TODOs

- [ ] Tailored suggestions when **unknown command** happens.
- [ ] Opt-in telemetry of log files.
