# Framing Script


### Install


* `Y:\Island_Library\Scripting\Addins\Framer.exe` - Installs the **Framer** Add-In for Revit


### Run the Script

  To run the script all you need to do is click the **Framer** icon under your Add-Ins tab.

### Execute Framer

* Once the **Framer** script is running you will be prompted to select a framer option:

* Framing options include preset frames and user saved framing configurations.

* Once a frame option has been selected you will be prompted to select assemblies to apply the framing to.


# Select Multiple Families Script


### Install

* `Y:\Island_Library\Scripting\Addins\Select_Multiple_Families.exe` - Installs the **Select Multiple Families** Add-In for Revit

### Run the Script

  To run the script all you need to do is click the **Select Multiple Families** icon under your Add-Ins tab.

### Execute Select Multiple Families

**Select Multiple Families**, as the name implies, allows you to select multiple instances of multiple families.

* After running the script, select elements with the family and type you'd like to select across the entire project. Once executed the script will add these elements to your selection so you can isolate, delete, or manage them however you need.


# Element Tag Script


### Install

* `Y:\Island_Library\Scripting\Addins\Element_Tag.exe` - Installs the **Element Tag** Add-In for Revit

### Run the Script

  To run the script all you need to do is click the **Element Tag** icon under your Add-Ins tab.

### Execute Element Tag
**Element Tag** speeds up the process of tagging elements within fabrication tickets by separating them into families, types, and lengths to generate unique IDs and then apply those IDs as tags in the view.

* Once inside the view you'd like elements tagged in, run the **Element Tag** script. The script will then parse through the elements inside of the view based on family category and assign IDs and generate tags within the view.


# Parameter Transfer Script


### Install

* `Y:\Island_Library\Scripting\Addins\Parameter_Transfer.exe` - Installs the **Parameter Transfer** Add-In for Revit

### Run the Script

  To run the script all you need to do is click the **Parameter Transfer** icon under your Add-Ins tab.

### Execute Parameter Transfer
**Parameter Transfer** allows for the transfer of parameters across families and types without changing the underlying family or parameters outside of those expressly specified.

* Once the **Parameter Transfer** script is running you can select source and transfer elements along with the parameters to pull from and push to.

* Additionally you can select assemblies to propagate your selection to, for every transfer element in your selection the script will check the selected assemblies for all other instances of that element and apply the same parameter transfer to those elements.

* After selecting all of the source and transfer elements and parameters you can then run the add-in to apply the transfer.


# Framing Script


### Install


* `Y:\Island_Library\Scripting\Addins\Framer.exe` - Installs the **Framer** Add-In for Revit


### Run the Script

  To run the script all you need to do is click the **Framer** icon under your Add-Ins tab.

### Execute Framer

* Once the **Framer** script is running you will be prompted to select a framer option:

* Framing options include preset frames and user saved framing configurations.

* Once a frame option has been selected you will be prompted to select assemblies to apply the framing to.


# Sheet Duplicator Script


### Install

* `Y:\Island_Library\Scripting\Addins\Sheet_Duplicator.exe` - Installs the **Sheet Duplicator** Add-In for Revit

### Run the Script

  To run the script all you need to do is click the **Sheet Duplicator** icon under your Add-Ins tab.

### Execute Sheet Duplicator
The **Sheet Duplicator** provides several useful functions, primarily the **Sheet Duplicator** can be used to duplicate sheet templates, copy legends to many sheets, generate schedules for many sheets, all while maintaining consistent formatting across the generated sheets.

* Once the **Sheet Duplicator** script is running you will be prompted to select between generating duplicate sheets within an existing assembly, duplicating sheets to other assemblies, or copying legends/schedules to other assembly sheets.

* When duplicating sheets to the same assembly or to other assemblies the **Sheet Duplicator** will provide you with many options to best format the duplicated sheets.
    * Sheet Duplication Options:
        * Reference Sheet | The template sheet that will be used for sheet duplication.
        * Title Block | The title block to be used on the duplicated sheets.
        * Sheet Number | Prefix __ Suffix to be given to each duplicated sheet number.
        * Sheet Name | Prefix __ Suffix to be given to each duplicated sheet name.
        * With Views | Set whether or not to include views on duplicated sheets.
        * Copy Elements Outside of Views | Set whether or not to include elements not inside of views placed on the sheet being duplicated.
        * Duplicate |
        * With Detailing |
        * View Name | Prefix __ Suffix to be given to each duplicated sheet view.
        * Title | Prefix __ Suffix to be given to each duplicated sheet title.
        * Copy Legend | *(None/Instance/Duplicate)* Instance: Use the existing legend on duplicated sheets. Duplicate: Create a new legend to use on duplicated sheets.
        * Copy Schedules | *(None/Instance/Duplicate)* Instance: Use the existing schedules on duplicated sheets. Duplicate: Create a new schedules to use on duplicated sheets.

# Panel Tracker Script


### Install

* `Y:\Island_Library\Scripting\Addins\Panel_Tracker.exe` - Installs the **Panel Tracker** Add-In for Revit

### Run the Script

  To run the script all you need to do is click the **Panel Tracker** icon under your Add-Ins tab.

### Execute Panel Tracker

**Panel Tracker** synchronizes a designated Revit model to Sharepoint and BIM 360 information to produce a visual tracker within Revit that is accessible through BIM 360

* Running the script will initiate a project setup process, the script needs the panel tracker Sharepoint link, the BIM 360 Docs folder location for storage, as well as locaton information for the parameters that the script will use to update the model.

* The Revit model must be formatted so that the view template shows the appropriate model information within the BIM 360 Docs viewer and should include material settings for the script to apply to the project panels.
