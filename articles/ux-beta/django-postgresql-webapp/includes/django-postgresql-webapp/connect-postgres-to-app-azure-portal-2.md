---
author: jess-johnson-msft
ms.author: jejohn
ms.topic: include
ms.date: 01/25/2022
ms.service: app-service
ms.role: developer
ms.devlang: python
ms.azure.devx-azure-tooling: ['azure-portal']
ms.custom: devx-track-python
---

**Step 2.** Create application settings

Use the **New application setting** button to create settings for each of the following values (which are expected by the djangoapp sample):

* *DBHOST* &rarr; The URL of the database server from the previous section; that is, the `<server-name>.postgres.database.azure.com`. <br /> Example: `msdocs-django-postgres-webapp-db`
* *DBNAME* &rarr;  Enter `pollsdb`; The name of the application database.
* *DBUSER* &rarr; The administrator user name used when you provisioned the database.
* *DBPASS* &rarr; The administrator **secure password** you created earlier.

<br />

Select **Save** and then **Continue** to apply the settings.
