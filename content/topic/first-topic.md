+++
title = "Hotfixes"
date = 2018-11-27
draft = "false"
tags = ["Hotfixes"]
categories = []
+++

## Exploring
### Where does it fit in?
A hotfix is the minimum software required to provide a solution for a specific problem experienced by one or more customers. These can also include any relevant dependencies.

SYSPRO provides hotfixes as a way of deploying software updates during the release of **SYSPRO 8**.

Types of hotfixes available include:

* Mandatory Hotfix
* Optional Hotfix
* Diagnostic Hotfix
* Restricted Hotfix
* Withdrawn Hotfix

Hotfixes are available from the SYSPRO Installer application.

## Starting
### Restrictions and Limits
Hotfixes are only displayed when running the SYSPRO Installer application on the server to which the SYSPRO 8 Server component has been installed.

## Types of Hotfixes
### Mandatory Hotfix
Occasionally, a Mandatory Hotfix is made available. This could be because of one of the following:

A serious error that we believe most customers will want corrected.
An architectural change to improve areas such as: security, performance, scalability, reliability, or the introduction of new foundation for several other hotfixes.

##### Who is notified?
Anyone who is using the current release of the software. Notification is via email.

If you install the software and previously-published Mandatory Hotfixes exist for that release, then they are automatically applied at the time of the install, without notification.

##### Who can install the hotfix?
All customers who are using the current release of the software and have not yet installed the mandatory hotfix.

##### Can the hotfix be uninstalled?
No, you cannot uninstall a mandatory hotfix.

### Optional Hotfix
Most hotfixes are optional. An **Optional Hotfix** is targeted at a specific customer who has reported a bug and a specific hotfix exists to resolve the issue.

Other customers can also elect to install an **Optional Hotfix** if they believe that the issue is relevant to them.

##### Who is notified?
The customer who reported the bug is notified when the **Optional Hotfix** to resolve this is available. Notification is via email.

##### Who can install the hotfix?
The customer who raised the bug is notified about the hotfix availability. However, all customers may use the SYSPRO Installer app to select and install the hotfix, if deemed relevant.

##### Can the hotfix be uninstalled?
Yes, if required you can uninstall an Optional Hotfix

### Diagnostic Hotfix
Occasionally, the development team may produce a Diagnostic Hotfix. These are aimed at specific customers to provide additional diagnostic output and/or other diagnostic features.

A Diagnostic Hotfix is only intended to be used for a limited period of time (while diagnosing any problems) and is typically uninstalled once the diagnostic phase has completed. Often this is followed by an Optional Hotfix/Mandatory Hotfix to resolve the identified issue(s).

###### Who is notified?
No notifications are sent as the development and/or support team will contact the customer directly.

###### Who can install the hotfix?
Only the customer who has a problem requiring a Diagnostic Hotfix.

###### Can the hotfix be uninstalled?
Yes, upon completion of the diagnostic phase, the hotfix should be uninstalled.

### Restricted Hotfix
Occasionally, the development team may issue a Restricted Hotfix that only a specific customer can install.

This could be of a very customer-specific nature, or may be a high-risk change where close customer support is required during hotfix implementation.

###### Who is notified?
The specific customer is notified. Notification is via email.

###### Who can install the hotfix?
Only the specific customer who requires the Restricted Hotfix.

###### Can the hotfix be uninstalled?
Yes, if required, you can uninstall a Restricted Hotfix.

### Withdrawn Hotfix
Occasionally, a published hotfix may contain an error, in which case the hotfix will be flagged as withdrawn.

##### Who is notified?
All customers who have previously installed the Withdrawn Hotfix.

##### Who can uninstall the hotfix?
Only customers who had installed the Withdrawn Hotfix.

##### Can the hotfix be uninstalled?
The hotfix should be uninstalled.

If required, a replacement hotfix is published and the list of customers who were notified about the Withdrawn Hotfix are notified about the replacement hotfix.