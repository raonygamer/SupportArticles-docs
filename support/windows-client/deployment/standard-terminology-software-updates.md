---
title: Description of the standard terminology
description: This article describes the standard terminology that Microsoft uses to describe software updates.
ms.data: 09/08/2020
author: delhan
ms.author: Deland-Han
manager: dscontentpm
audience: itpro
ms.topic: troubleshooting
ms.prod: windows-client
localization_priority: medium
ms.reviewer: kaushika
ms.prod-support-area-path: Servicing
ms.technology: Deployment
---
# Description of the standard terminology that is used to describe Microsoft software updates

This article describes the standard terminology that defines the software updates for the Windows Update and Microsoft Update services.

_Original product version:_ &nbsp; Windows 10 - all editions  
_Original KB number:_ &nbsp; 824684

## Critical update

A widely released fix for a specific problem that addresses a critical, non-security-related bug.

## Definition update

A widely released and frequent software update that contains additions to a product's definition database. Definition databases are often used to detect objects that have specific attributes, such as malicious code, phishing websites, or junk mail.

## Driver

Software that controls the input and output of a device.

## Feature pack

New product functionality that is first distributed outside the context of a product release and that is typically included in the next full product release.

## Security update

A widely released fix for a product-specific, security-related vulnerability. Security vulnerabilities are rated by their severity. The severity rating is indicated in the Microsoft security bulletin as critical, important, moderate, or low.

### Additional information

Microsoft security updates are available for customers to download and are accompanied by two documents: a security bulletin and a Microsoft Knowledge Base article. For more information about the format of Microsoft Knowledge Base articles for Microsoft security updates, see [Description of the format of Microsoft Knowledge Base articles for Microsoft Security Updates](https://support.microsoft.com/help/824689).

## Service pack

A tested, cumulative set of all hotfixes, security updates, critical updates, and updates. Additionally, service packs may contain additional fixes for problems that are found internally since the release of the product. Service packs my also contain a limited number of customer-requested design changes or features.

## Tool

A utility or feature that helps complete a task or set of tasks.

## Update

A widely released fix for a specific problem. An update addresses a noncritical, non-security-related bug.

## Update rollup

A tested, cumulative set of hotfixes, security updates, critical updates, and updates that are packaged together for easy deployment. A rollup generally targets a specific area, such as security, or a component of a product, such as Internet Information Services (IIS).

## Security-only update

An update that collects all the new security updates for a given month and for a given product, addressing security-related vulnerabilities and distributed through Windows Server Update Services (WSUS), System Center Configuration Manager and Microsoft Update Catalog. Security vulnerabilities are rated by their severity. The severity rating is indicated in the Microsoft security bulletin as critical, important, moderate, or low. This Security-only update would be displayed under the title Security Only Quality Update when you download or install the update and will be classified as an *Important* update.

## Monthly Rollup

A tested, cumulative set of updates. They include both security and reliability updates that are packaged together and distributed over Windows Update, WSUS, System Center Configuration Manager and Microsoft Update Catalog for easy deployment. The Monthly Rollup is product-specific, addresses both new security issues and nonsecurity issues in a single update and will proactively include updates that were released in the past. Security vulnerabilities are rated by their severity. The severity rating is indicated in the Microsoft security bulletin as critical, important, moderate, or low. This Monthly Rollup would be displayed under the title Security Monthly Quality Rollup when you download or install. This Monthly Rollup will be classified as an *Important* update on Windows Update and will automatically download and install if your Windows Update settings are configured to automatically download and install Important updates.

## Preview of Monthly Rollup

A tested, cumulative set of new updates that are packaged together and distributed over Windows Update, WSUS, System Center Configuration Manager and Microsoft Update Catalog ahead of the release of the next Monthly Rollup for customers to proactively download, test, and provide feedback. The Preview of Monthly Rollup is product-specific and addresses new non-security updates, and includes fixes from the latest Monthly Rollup. This Preview of Monthly Rollup would be displayed under the title Preview of Monthly Quality Rollup when you download or install and will be classified as an "Optional" update.

## Servicing Stack Updates (SSU)

The servicing stack is the code that installs other operating system updates. Additionally, it contains the component-based servicing stack (CBS), which is a key underlying component for several elements of Windows deployment, such as DISM, SFC, changing Windows features or roles, and repairing components. The CBS is a small component that typically does not have updates released every month.

For more information, see [Servicing stack updates](/windows/deployment/update/servicing-stack-updates).