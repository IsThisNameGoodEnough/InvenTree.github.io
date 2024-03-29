---
title: Part Detail
---

Each part has a comprehensive detail view which provides information about the particular part.

{% include img.html url="part/part_overview.png" description="Part details" %}

A Part is defined in the system by the following parameters:

## Part Definition Fields

**Name** - The Part name is a simple (unique) test label

**Description** - Longer form text field describing the Part

**Internal Part Number (IPN)** - A special code which can be used to link a part to a numbering system. The IPN field is not required, but may be useful where a part numbering system has been defined.

**Revision** - An optional revision code denoting the particular version for the part. Used when there are multiple revisions of the same master part object.

**Category** - The Part category is used to group or arrange parts, as per the particular requirements of the user. Categories are arranged in a 'tree' where each category may have multiple child categories.

**URL** - An external URL field is provided to link to an external page. This could be useful the part has extra documentation located on an external server.

**Units** - Units of measure (UoM) for this Part. The default is 'pcs'

## Part Options

A Part can provide different functionality based on the following options.

**Virtual** - A *Virtual* part is one which does not physically exist but should still be tracked in the system. This could be a process step,  machine time, software license, etc.

**Assembly** - If a part is designated as an *Assembly* it can be created (or built) from other component parts. As an example, a circuit board assembly is made using multiple electronic components, which are tracked in the system. An *Assembly* Part has a Bill of Materials (BOM) which lists all the required sub-components.

**Component** - If a part is designated as a *Component* it can be used as a sub-component of an *Assembly*.

**Purchaseable** - If a part is designated as *Purchaseable* it can be purchased from external suppliers. Setting this flag allows parts to be added to purchase orders.
