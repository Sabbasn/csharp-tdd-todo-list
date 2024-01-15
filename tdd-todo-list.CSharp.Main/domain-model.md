﻿# ToDo List - Domain Model

```
I want to add tasks to my todo list.
I want to see all the tasks in my todo list.
I want to change the status of a task between incomplete and complete.
I want to be able to get only the complete tasks.
I want to be able to get only the incomplete tasks.
I want to search for a task and receive a message that says it wasn't found if it doesn't exist.
I want to remove tasks from my list.
I want to see all the tasks in my list ordered alphabetically in ascending order.
I want to see all the tasks in my list ordered alphabetically in descending order.
```
<table>
	<thead>
		<td>Class</td>
		<td>Methods</td>
		<td>Scenario</td>
		<td>Output</td>
	</thead>
	<tbody>
		<td><code>ToDoList</code></td>
		<td><code>Add(Task task)</code></td>
		<td>Add a task to my todo list</td>
		<td>void</td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>View(Enum OrderAlphabetical ascending)</code></td>
		<td>View all tasks in the ToDoList ordered alphabetically, 
		ascending or descending</td>
		<td>void</td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>GetCompleteTasks()</code></td>
		<td>Gets all the complete tasks</td>
		<td>List&ltTask></td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>GetIncompleteTasks()</code></td>
		<td>Gets all the incomplete tasks</td>
		<td>List&ltTask></td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>Search(string id)</code></td>
		<td>Search for a task with a given Guid</td>
		<td>Task</td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>Search(string id)</code></td>
		<td>Return null if none are found</td>
		<td>null</td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>Remove(string id)</code></td>
		<td>Remove a task from the ToDoList by id</td>
		<td>void</td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>Remove(int index)</code></td>
		<td>Remove a task from the ToDoList by index</td>
		<td>void</td>
	</tbody>
	<tbody>
		<td><code>ToDoTask</code></td>
		<td><code>Status</code></td>
		<td>Change the status of a task</td>
		<td>void</td>
	</tbody>
	<tbody>
		<td></td>
		<td><code>Status</code></td>
		<td>Get the status of a task</td>
		<td>Enum.Status</td>
	</tbody>
</table>