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

**Step 3.** On the **Create Web App** page, fill out the form as follows.

* *Resource Group* &rarr; Select *Create new* and use a name of **msdocs-django-postgres-webapp-rg**.
* *Name* &rarr; **msdocs-django-postgres-webapp** This name must be unique across Azure.
* *Runtime stack* &rarr; **Python 3.9**
* *Region* &rarr; Any Azure region near you.
* *App Service Plan* &rarr; Select **Create new** under *Linux Plan* and use a name of **msdocs-django-postgres-webapp-plan**.
* *App Service Plan* &rarr; Select **Change size** under *Sku and size setting* to select a different App Service plan.
