# **Add User Tasks:**

## Requires different states for progress levels:
   * [x] ex. "unfinished", "in-progress" and "finished"
   * [x] could be done by a cyclical function? (display x at count y etc)
   * [ ] use a checkbox and store the state of the box in the DB
         * store the index of {priorities} instead i.e priorities[2] == "Medium-Priority"
   * [ ] Tasks will contain a {id, name, state, priority, deadline, notification_time, and subtasks}.

## Tasks should have subtasks:
   * [ ] This should allow a user to add a task to a prexisting task
   * [ ] All subtasks should be stored on the database
	   * [ ] Will be related to tasks in a one(task) to many(subtasks)
   * [ ] All will contain {id, name, state}

## Should be able to assign priority to tasks:
   * [x] incl. "no priority", "low priority", "medium priority", "high priority".
	   * [ ] task priority should be stored in the DB with the task

## A task should have a deadline and a notification:
   * [ ] Should allow the user to enter a deadline date
   * [ ] Should allow the user to enter a notification time 
		* [ ] (e.g. 1 day/week/month before the deadline)
   * [ ] both the notification and deadline will be stored under task in the database (task.deadline, task.notification_time)


 
