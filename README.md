# CLI To-Do Application in Go

A command-line interface to-do application developed in the Go programming language


---
| #   | Title         | Completed | Created at                    | Completed at                  |
| --- | ------------- | --------- | ----------------------------- | ----------------------------- |
| 0   | Go for a run  | ❌         | Mon, 10 Feb 2025 21:41:29 IST |                               |
| 1   | Buy groceries | ✅         | Mon, 10 Feb 2025 21:42:01 IST | Mon, 10 Feb 2025 21:42:33 IST |
| 2   | Read a book   | ❌         | Mon, 10 Feb 2025 21:42:17 IST |                               |

---


### Get started:
```sh
go mod tidy
```
```sh
go build ./
```

### Usage:
```
-add string
      Add a new todo. Specify title
-del int
      Delete a todo by index (default -1)
-edit string
      Edit a todo by index & specify a new title. id:New Title.
-list
      List all todos
-toggle int
      Toggle a todo by index (default -1)
```