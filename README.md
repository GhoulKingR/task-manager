# Task manager
Project URL: https://roadmap.sh/projects/task-tracker

## Running the project
To run the project on your machine follow these steps:
1. Clone the repository into your machine:
```bash
https://github.com/GhoulKingR/task-manager.git
```
2. make the `task-cli` tool executable:
```bash
chmod +x task-cli
```
3. Run the `task-cli`:
```bash
./task-cli
```

## Actions you can perform

### Add a new task
Here's an example of adding a new task to the tracker:

```bash
task-cli add "Buy groceries"
# Output: Task added successfully (ID: 1)
```

### Updatng a task
Say you have a task at id 3, to change the text of the task, you can run this command:
```bash
task-cli update 3 "Buy groceries and cook dinner"
```

### Deleting a task
To delete a task at ID 1, run this command:
```bash
task-cli delete 1
```

### Marking as done or in progress
To mark a task as either done or in progress run any of these commands
```bash
task-cli mark-in-progress 1
task-cli mark-done 1
```

### Listing all tasks
To list all the tasks in the list, run this command
```bash
task-cli list
```

You can also filter the list by their status using any of these commands
```bash
task-cli list done
task-cli list todo
task-cli list in-progress
```