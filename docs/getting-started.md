---

api_name:
- Microsoft.Office.DocumentFormat.OpenXML.Packaging
api_type:
- schema
ms.assetid: 7b729dda-bbb6-437e-93d6-7bfe7b8183fa
title: Getting started with the Open XML SDK 2.5 for Office
ms.suite: office

ms.author: o365devx
author: o365devx
ms.topic: conceptual
ms.date: 11/01/2017
ms.localizationpriority: high
---

# Getting started with the Open XML SDK 2.5 for Office

The Open XML SDK 2.5 for Office simplifies the task of manipulating Open XML packages and the underlying Open XML schema elements within a package. The classes in the Open XML SDK 2.5 encapsulate many common tasks that developers perform on Open XML packages, so that you can perform complex operations with just a few lines of code.

[!include[Add-ins note](./includes/addinsnote.md)]

## Using the Classes in the Open XML SDK

Using the classes in the Open XML SDK 2.5 is simple. When you have installed the Open XML SDK 2.5, open your existing project or application in Visual Studio, or create a new project or application. Then, in your project or application, add references to the following components.

- **DocumentFormat.OpenXml**
- **WindowsBase**

### To add a reference in a Microsoft Visual Studio 2008 project

1. In Solution Explorer, right-click **References** and then click **Add Reference**. If the **References** node is not visible, click **Project** and then click **Show All Files**.
2. In the **Add Reference** dialog box, click **.NET**.
3. In the Component Name column, select the components (scroll if you need to), and then click **OK**.

> [!TIP]
> To select more than one component, hold down the **Ctrl** key and click each component.

The added components are displayed in the References section in Solution Explorer.
