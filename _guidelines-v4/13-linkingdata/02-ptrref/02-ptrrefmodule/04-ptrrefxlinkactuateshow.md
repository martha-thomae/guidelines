---
sectionid: ptrRefXlinkActuateShow
title: "Determine the link element's behaviour"
version: "v4"
---

The **@xlink:actuate** and **@xlink:show** attributes are used in conjunction to determine the link's behavior.
 
 The **@xlink:actuate** attribute defines whether the resolution of a link occurs automatically or must be requested by the user.

The following values are allowed for the **@xlink:actuate** attribute:

{:.gloss}
**'onLoad'**: load the target resource(s) immediately

{:.gloss}
**'onRequest'**: load the target resource(s) upon user request, e.g., after a mouse click

{:.gloss}
**'none'**: do not permit loading of the target resource(s); no other markup is provided to determine appropriate behavior

{:.gloss}
**'other'**: behavior other than permitted by the other values of this attribute; application should look for other markup to determine appropriate behavior


The value "none" may be used to indicate that the link is un-traversable and no other markup is provided to determine appropriate behavior; it may or may not render the link invisible to the user. When the value of **@xlink:actuate** is "other", an application must base a determination of appropriate behavior on factors other than the value of **@xlink:actuate**.

The **@xlink:show** attribute defines how a remote resource is to be rendered. The following values are permitted:

{:.gloss}
**'new'**: target of the link appears in a new window

{:.gloss}
**'replace'**: target of the link replaces the current resource in the same window

{:.gloss}
**'embed'**: the content of the target appears at the point of the link

{:.gloss}
**'none'**: do not permit traversal to the target resource(s); no other markup is provided to determine appropriate behavior

{:.gloss}
**'other'**: behavior other than permitted by the other values of this attribute; application should look for other markup to determine appropriate behavior


The value "none" may be used to indicate a link that is not displayed or is not displayable and no other markup is provided to determine appropriate behavior. When the value of **@xlink:show** is "other", an application must base a determination of appropriate behavior on factors other than the value of **@xlink:show**.

The following example illustrates a pointer that results in the automatic creation of a new window with the content of the target loaded in it:

{% include mei example="ptrRef/ptrRef-sample343.txt" valid="" %}
