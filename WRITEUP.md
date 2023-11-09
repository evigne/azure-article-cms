# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
- _Choose the appropriate solution (VM or App Service) for deploying the app_
- _Justify your choice_

### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._

I prefer utilizing App Services for this application due to its lightweight nature. This eliminates the need for investing in a Virtual Machine (VM), and we also avoid the necessity of controlling the operating system for this lightweight application. In my workplace, we previously deployed applications using VMs, including a separate VM for the MySQL server, and it proved challenging to manage.
