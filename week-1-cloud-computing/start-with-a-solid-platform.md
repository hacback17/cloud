# Module 2 - Start With a Solid Platform

## Four ways to interact with GCP.

![](../.gitbook/assets/image%20%2814%29.png)

GCP Console:

* Using this web based console, you can manage your GCP projects and resources.
* Serves as a centralized console for all project data
* Execute common tasks using simple mouse clicks.
* The resources you create are done in the context of a specific project: Manage and create projects
* Access developer tools:
  * Cloud Source Repositories - Git repos for collaborative development
  * Cloud SDK - a set of tools to automate your workflow
  * Cloud Shell - Shell within the GCP Console

##  Understanding Projects

Every GCP service you use is associated with a project:

* Enable services and APIs
* Enable billing
* Adding and removing collaborators: Manage permissions and credentials
* Track resources and quota usage.
* Using resource manager, manage your projects programmatically in GCP - Rest API.

Each project is a separate account. And, each resource belongs to exactly one.

Projects can have different owners and users they are billed separately and managed separately.

Projects have three identifying attributes:

1. Project ID
   * Globally unique
   * Assigned by GCP but editable during creation only
2. Project Name
   * Need not be unique
   * Chosen by you
   * Mutable/Editable
   * You can't reuse the project name of a deleted project.
3. Project Number
   * Globally unique
   * Assigned by GCP
   * Immutable

![Creating a project](../.gitbook/assets/image%20%289%29.png)

##  Billing in GCP

* Billing in GCP is set up at the project level. When you define a GCP project, you link a billing account to it where you set up a payment option.
* A billing account is linked to zero or more projects.
* Projects that you don't link to any billing account can only use free GCP services.
* Accounts are charged automatically, invoiced monthly, or invoiced at the threshold limit.
* You can separate project billings by setting up billing sub accounts. Some GCP customers that re-sell GCP services use sub accounts for each of their own clients.

### How to keep your billing under control

1. Budgets and alerts
   1. You can define budget at the **billing account level** or the **project level**.
   2. To be notified when budget approach the limit, you can use an alert.
   3. You can also set up a web hook that can control automation based on billing alerts, for example, you can set up a script to shutdown resources when a billing alert occurs.
   4. 
2. Billing export
   1. Billing exports allow you to store detailed billing information for external analysis.
3. Reports

   1. visual tool in the console to monitor expenditure 

4. Quotas
   1. Helpful limits to prevent over-consumsuption of resources because of  an error or a malicious attack.
   2. They apply at the level of GCP project.
   3. Two types of quotas:
      1. **Rate quotas** reset after a specific time. For example, GKE API: 1,000 requests per 100 seconds
      2. **Allocation quotas** governs number of allocation resources have in your projects. For example, 5 networks per project
   4. Many quotas are changeable by calling the Google support. You can also use the console to request a quota change.

![](../.gitbook/assets/image%20%2822%29.png)

![](../.gitbook/assets/image%20%2821%29.png)

