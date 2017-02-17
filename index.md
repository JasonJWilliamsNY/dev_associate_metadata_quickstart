```eval_rst
|CyVerse logo|

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
```

# Associate metadata to a file in the DE

## Goal

This Quick Start will show you how to add metadata to a single file or folder in the Discovery Environment using your own attributes or a pre-built template.

## Prerequisites


### Downloads, access, and services

*In order to complete this tutorial you will need access to the following services/software*

* **CyVerse account** - You will need a CyVerse account to complete this
  exercise [Register](https://user.cyverse.org/)

### Platform(s)

*We will use the following CyVerse platform(s):*

* [Discovery Environment](https://de.iplantcollaborative.org) ([Manual](https://pods.iplantcollaborative.org/wiki/display/DEmanual/Table+of+Contents))

### Input and example data

*In order to complete this tutorial you will need to have the following inputs prepared*

You need to have at least one file or folder in your home folder in CyVerse and be able to access it from the Discovery Environment.

---

## Get Started

First we will add a single piece of metadata called an AVU, then we will add several standard pieces of metadata using a template, to see how templates can include AVUs that are already entered. 

```eval_rst
.. Note::
	* A single piece of metadata, or an AVU, is made up of attributes, values, and units. An attribute is a changeable property or characteristic of the file or folder you have selected that can be set to a value. For example, length is an attribute of a file, while 7 is its value, and cms is the unit.  The metadata you enter stays with the file when you share the file or folder with others.
	* Just like editing any file or folder, you must either have write or own permission to it in order to add, edit, or delete its metadata. You can view, copy, or save the metadata for any file or folder that has been shared with you, regardless of permission level. Another form of metadata that is just for your use is the ability to add tags to a file or folder in the DE.
```

**Add a single AVU to a file or folder**

1. Open the DE then open the Data window and search for the file or folder you own and to which you want to add or edit metadata.

2. Click the metadata icon to the right of the file or folder name (or click the checkbox next to the item, click the Metadata menu, and then click Edit/View Metadata).

3. To add metadata to the data item:
* Click Add (green plus sign)
* Double-click in the New Attribute field and enter "Title" as the attribute for the data item.
* Tab to the New Value field and enter "The Haunting" as the value.
* Tab to the Unit field and delete the default text as there is no unit for this attribute.

```eval_rst
.. Hint::
    For the next section of the quickstart to work properly, you must enter "Title" with a capital T as the attribute.
```

4. Click Save to save the AVU.

**Add a metadata template to the same file or folder**

1. Using the same file or folder from above, click the metadata icon to the right of the file or folder name (or click the checkbox next to the item, click the Metadata menu, and then click Edit/View Metadata).

2. In the User Metadata window, click Select Template, select the "Dublin Core", and click OK. 

3. The template window opens, and you will see a list of AVUs. The first AVU is Title, and you will see the value you entered for Title already filled in.

4. Double click on some additional AVUs to enter some additional values.

5. When done, click OK. The template's metadata attributes are added to the User Metadata dialog.

### Summary

You now know the basics of adding metadata to objects (files and folders) in the CyVerse Data Store, using tools available in the Discovery Environment.

**Next Steps:**

---
## More help/additional information

To learn more about working with metadata in the DE, including copying metadata from one object to another and adding metadata to multiple objects at once, see [Using metadata in the DE](https://wiki.cyverse.org/wiki/display/DEmanual/Using+Metadata+in+the+DE).

**Search for an answer:** [CyVerse Learning Center](http://www.cyverse.org/learning-center) or [Wiki](https://wiki.cyverse.org/wiki/dashboard.action)
**Post your question to the user forum:** [Ask CyVerse](http://ask.iplantcollaborative.org/questions/)

### Fix or improve this tutorial 

**Fix this tutorial on GitHub:** [GitHub](Link_to_gh_readme)
**Send a note to support:** [Tutorials@CyVerse.org](mailto:Tutorials@CyVerse.org)
