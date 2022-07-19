How I did it using Jira Automation.

![Jira Automation recipe](https://user-images.githubusercontent.com/954865/179820311-0ba24a78-ac5d-401d-b994-0f751b2adc0c.png)

Detailed screenshots that require configuration:

Clone epic and set assignee to `User who triggered the event`.
![Clone issue (epic)](https://user-images.githubusercontent.com/954865/179820387-b3d0f0c9-3db3-4852-b884-482b07e72fee.png)

Create variable using `{{createdIssue}}`.
![Create variable](https://user-images.githubusercontent.com/954865/179820506-9087d050-35d6-4b8d-8116-dff70849e377.png)

Add an epic link to cloned child issues and set assignee to `User who triggered the event`.
![Clone issue (child issues)](https://user-images.githubusercontent.com/954865/179820540-820bb29d-3db8-415e-8e81-03792b6856b6.png)
