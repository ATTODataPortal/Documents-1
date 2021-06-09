# How to upload

#

Authors: Cornelia Fürstenau, Franziska Zander

Contact BExIS Team: <bexis@listserv.uni-jena.de>

Contact BExIS Data Curator: <bexis-datacurator@uni-jena.de>

## Table of content

[1. Overview](#1-overview)

[2. Create a dataset with tabular data2](#2-create-a-dataset-with-tabular-data)

- [2.1 Create dataset](#21-create-dataset)
- [2.2 Metadata](#22-metadata)
- [2.3 Data structure](#23-data-structure)
- [2.4 Upload data](#24-upload-data)
- [2.5 Add data links (optional)](#25-add-data-links-optional)
- [2.6 Add attachments (optional)](#26-add-attachments-optional)

[3. Create a new dataset (with/without a file)](#3-create-a-new-dataset-withwithout-a-file)

- [3.1 Create dataset](#31-create-dataset)
- [3.2 Metadata](#32-metadata)
- [3.3 Upload data](#33-upload-data)
- [3.4 Add data links and attachments (optional)](#34-add-data-links-and-attachments-optional)

[4. Update a dataset](#4-update-a-dataset)

- [4.1 Metadata](#41-metadata)
- [4.2 Primary data](#42-primary-data)
- [4.3 Links and Attachments](#43-links-and-attachments)

## 1 Overview

Under *Upload* you find tools to create datasets. The basic functions are
(Figure 1):

-   Create Dataset ([Chapter 2](#2-create-a-dataset-with-tabular-data) and [Chapter 3](#3-create-a-new-dataset-withwithout-a-file))
-   Create Publication (see separate How to)
-   Update Data ([Chapter 4](#4-update-a-dataset))
-   Push Big Files (coming soon)

<img src=".\images_upload\image1.png" style="width:6.3in;height:1.13861in" />

Figure 1: Functions of the upload menu.

## 2 Create a dataset with tabular data

Creating a new dataset with tabular data includes the following steps:

1.  [Create a new dataset](#21-create-dataset)
2.  [Fill out the metadata](#22-metadata)
3.  [Define data structure](#23-data-structure)
4.  [Upload primary data](#24-upload-data)
5.  [Add links to other datasets and publications (optional)](#25-add-data-links-optional)
6.  [Add attachments (optional)](#26-add-attachments-optional)

### 2.1 Create dataset

Create a new dataset by selecting *Create Dataset* from the *Upload* menu (Figure 2)
and following these steps :

1.  Dataset:
    1.  To create a blank dataset, choose *New Datase*t -\> next step 2i
    2.  To use an existing dataset as template, select this dataset from the list -\> next step 2i or 2ii

2.  Data Structure:
    1.  Define the data structure; choose *Tabular data (new)*; to reuse
        an existing data structure, select *Existing tabular data
        structure* and select a data structure from the list-\> next
        step 3i
    2.  Use the data structure of the chosen data record (1i), choose
        another existing data structure, or create a new one by
        choosing *Tabular data (new)* -\> next step 4i

3.  Metadata Structure:
    1.  Use the metadata schema called *Biodiversity Exploratories Metadata
        Schema 3.0* -\> next step 4i

4.  Next-button:
    1.  Press the button and fill in the metadata

<img src=".\images_upload\image2.png" style="width:6.3in;height:2.17822in" />

Figure 2: First steps of creating a new dataset.

### 2.2 Metadata

Provide detailed metadata to give all essential information about the data. The metadata is structured in sections. Switch directly to a section via the metadata tabs (e.g., *General* and *Contact –* Figure 3).

Note, grey boxes mark automatically filled fields like *Id, Version, Metadata creation date*. [Table 1](#t1) explains the use of the buttons in the metadata.

Please use the autocomplete functions for the *project name, metadata creator, data creator, data collector,* and *contact person*!

[Table 1](#t1): Buttons in the metadata schema.

| Button    | Description   |
|-----------------------------------------------------------------------------------|---------------|
| <img src=".\images_upload\image3.png" style="width:0.20002in;height:0.20002in" /> | \(1\) info-button offers help when filling out the metadata fields; the info-button on the top shows all help texts |
| \*    | \(2\) mandatory fields|
| <img src=".\images_upload\image4.png" style="width:0.32003in;height:0.20002in" /> | \(3\) opens or closes subsections (topics)|
| <img src=".\images_upload\image5.png" style="width:0.38003in;height:0.19335in" /> | \(4\) the button adds or deletes an additional field|
| <img src=".\images_upload\image6.png" style="width:0.38003in;height:0.20002in" /> | \(5\) use to reorders a list|
| <img src=".\images_upload\image7.png" style="width:0.23036in;height:0.1875in" />  | \(6\) subsections are closed by default (e.g., Coordinates-WGS84); ticking the check box opens subsection|

<img src=".\images_upload\image8.png" style="width:6.3in;height:3.1875in" />

Figure 3: Metadata schema

At the end of the metadata schema, there are two buttons - *validate* or *save*. The validation checks if all mandatory fields are filled and comply with the metadata standard. Errors and missing content will be marked in red (Figure 4). Clicking the save button also validates the dataset, and a warning will pop up if the data is incomplete. Nevertheless, the metadata can be saved and completed later.

<img src=".\images_upload\image9.png" style="width:6.3in;height:2.48958in" />

Figure 4: Validation of metadata schema.

### 2.3 Data structure

The next step is to adjust the data structure to the primary data. Use the link provided under the tab *Data Structure* of the dataset (Figure 5).

<img src=".\images_upload\image10.png" style="width:6.3in;height:1.71875in" />

Figure 5: Link to edit the data structure.

The data structure describes the variables of the primary data. Choose a variable template from the predefined list for each variable of the primary data. There are two filter options to find the templates (Figure 6):

1.  Search: enter search term, e.g., length, mass
2.  Filter: select datatype, unit, or dimension

Add the variable template to the data structure using *arrow button* (3). Make sure the variable templates are in the same order as the variables in the data.

<img src=".\images_upload\image11.png" style="width:6.3in;height:1.90625in" />

Figure 6: Options to search for a variable template.

In the next step, customize each variable template. Table 2 explains the fields and the buttons in the variable template (see also Figure 7).

Table 2: Variable Template.
| Fields/buttons           | Description                                                                           |
|--------------------------|---------------------------------------------------------------------------------------|
| 1. Name                     | change the variable name; it has to be the identical name as used in the primary data |
| 2. Unit                     | select the appropriate unit                                                           |
| 3. Optional (checkbox)      | allows empty cells in the data (not preferred!)                                       |
| 4. <img src=".\images_upload\image12.png" style="width:0.14931in;height:0.19931in" />               |  shows the whole template                                                                                     |
| 5. Description              | add a variable description                                                            |
| 6. Missing value            | there is one predefined missing value </p>- *Placeholder*: per default *na*, but can be customized <p>- *Description*:add a description</p></td>                                              |
| 7. Trash bin                | use to delete a variable template                                                     |

If you cannot find an appropriate variable template or a specific unit is missing, please contact the BExIS team!

Finally, save the data structure and go back to your dataset (use the browser back button).

<img src=".\images_upload\image14.png" style="width:6.3in;height:2.70833in" />

Figure 7: Edit a variable template.

### 2.4 Upload data

To start the upload process, use the *Upload button* in your dataset's primary data tab (Figure 8). This link will direct you to the data upload wizard.

<img src=".\images_upload\image15.png" style="width:6.3in;height:1.79167in" />

Figure 8: Start data upload.

Now follow the upload wizard (Figure 9):

1.  Select file:
    -   Choose the file from your local computer. The wizard supports file formats of Microsoft Excel or text (UTF-8)   (\*.xlsm, \*.xlsx, \*.txt, \*.csv, \*.tsv). After selecting the file, click the *Next button*.

2.  Get file information (excel files):
    -   The first datasheet of the selected file is displayed. If you wish to upload data from a different worksheet use the *Change Worksheet button*. Please be aware that you can only upload data from one sheet at a time.
    -   Note: The representation of the data in the upload wizard might differ from Microsoft Excel or similar programs. Nevertheless, the data will be uploaded correctly.
    -   Provide the information which cells contain the header (variables). Select the row or one part of a row containing the variable names and click the *Header button*.
    -   Mark the data section by selecting multiple rows and clicking the *Data button*. The selected area will be highlighted in blue. Please make sure that the data                      area contains as many columns as the header. You can use the *Expand Selection button* to expand the already selected data area to the last row of the file.
    -   If mistakes occur, use the *Reset button* to remove all markings and start over.
    -   Click the *Next button* to proceed to the next step.

3.  Specify dataset:
    -   Skip this step if you used the upload button in the dataset's primary data tab.

4.  Validation:
    -   Click the *Validate button*. This step checks if the data structure and the primary data match.
    -   Validation failed: View the error message and adapt the datastructure or your uploaded data. You can open the data structure
        in a second tab, change it and validate it again. If you need help: send a mail with the error message and the dataset id to
        the BExIS-Team. If the data file is not too big, please also attach it.
    -   Validation successful: click *Next button*.

5.  Summary:
    -   The wizard provides a summary of the uploaded data.
    -   Click the *Finish button* to complete the import.
    -   Depending on the size of your uploaded data you will be directly forwarded to your dataset and you can view your data. Otherwise,
        you will be informed via mail once the import is completed. During that time your dataset is not accessible.

6.  Visual check:
    -   Please check your uploaded data under the *Primary Data tab*. In case something looks strange please contact the BExIS Team.

<img src=".\images_upload\image16.png" style="width:6.3in;height:2.36458in" />

Figure 9: First page of upload wizard.

### 2.5 Add data links (optional)

Under the tab *Links* of the dataset (Figure 10), you can add linked/related datasets and publications. Links always refer to a specific version of a dataset. To insert links, click on *Create link*

<img src=".\images_upload\image17.png" style="width:6.3in;height:2.77083in" />

Figure 10: Create a link.

Provide the following information while creating a link:

1.  *Type*: dataset or publication
2.  *Title:* select a dataset or publication from the list. Tip: start to type in the title and the system will narrow down the results.
3.  *Version:* choose an appropriate version of the data record
4.  *Reference Type:* select a reference type (Table 3).

Table 3: Reference types.

| Link type              | Description  |  
|------------------------|-----------------------------------------------------------------------------|
| Collection             | linked dataset is part of a collection (e.g., header data and species data)|
| Link                   | unspecific link to a dataset or publication|
| Is supplement to       | linked dataset is used in the current publication|
| Is supplemented by     | linked publication uses the current dataset|
| Is new version of      | linked dataset is a newer version of the current dataset|
| Is previous version of | linked dataset is an older version of the current dataset|
| Is continued by        | indicates that the current dataset is continued by the linked dataset (e.g., for time series)|
| Is derived from        | linked dataset is a source upon which the current dataset is based|
| Is source of           | the original dataset is the source of the linked dataset|
| Compiles               | linked dataset (e.g., synthesis datasets) is the result of a compile or creation event using the current dataset|
| Is compiled by         | linked dataset is used to compile or create the current dataset (e.g., synthesis datasets)|

### 2.6 Add attachments (optional)

Additional files (e.g., files documenting primary data collection and creation like images, documents, and protocols) may be added to the datasets. Use the *Select button* to upload one or more files. Please provide a short description of your selected file(s).

## 3 Create a new dataset (with/without a file)

Creating a new data set for unstructured data (documents, images, GIS-files) or data stored in an external repository includes the following steps:

1.  [Create a new dataset](#31-create-dataset)
2.  [Fill out the metadata](#32-metadata)
3.  [Upload file(s) (optional)](#33-upload-data)
4.  [Add links to other datasets and publications (optional)](#34-add-data-links-and-attachments-(optional))
5.  [Add attachments (optional)](#34-add-data-links-and-attachments-(optional))

### 3.1 Create dataset

To set up a new dataset, select *Create Dataset* in the *Upload* menu and follow those steps:

1.  Dataset:
    1.  To create a blank dataset, choose *New Datase*t -\> next step 2i
    2.  To use an existing dataset as template, select this dataset from the list -\> next step 2ii

2.  Data Structure:
    1.  Define the data structure; select *Existing file data structure* and choose a data type from the list-\> next step 3i
    2.  Use the data structure of the chosen dataset (1ii), choose another existing data type -\> next step 4i

3.  Metadata Structure:
    1.  Use the metadata schema called *Biodiversity Exploratories MetadataSchema 3.0* -\> next step 4i

4.  Next-button:
    1.  Press the button and fill in the metadata

### 3.2 Metadata

See [Chapter 2.2](#22-metadata) for instructions.

<span id="_3.3__Upload" class="anchor"></span>

### 3.3 Upload data

To start the upload process, use the upload button in your dataset's primary data tab (Figure 11). This link will direct you to the data
upload wizard.

<img src=".\images_upload\image15.png" style="width:6.3in;height:1.79167in" />

Figure 11: Start data upload.

Now follow these steps of the upload wizard:

1.  Select file:
    -   Choose the file from your local computer. After selecting the file, click the *Next button*.

2.  Specify dataset
    -   Skip this step if you used the *Upload button* in the dataset's primary data tab. The dataset is already selected. Press the *Next button.*

3.  Summary:
    -   The wizard provides a summary of the uploaded data.
    -   Click finish button.

### 3.4 Add data links and attachments (optional)

See [Chapter 2.5](#25-add-data-links-optional) and [Chapter2.6](#26-add-attachments-optional) for instructions.

# 4. Update a dataset

The metadata creator, data creator, and project leader are allowed to edit the following parts of their dataset:

- metadata
- primary data
- links
- attachments

The data structure itself can not be changed once the dataset contains primary data. But you are still able to edit the description of the variables.

To start this process open the dataset. To find the dataset use the menu *Search* or *My Data*.

## 4.1 Metadata

Open your dataset. To edit the metadata click on the *Edit button* on top of your metadata.

## 4.2 Primary data

To update your primary data go to the *Primary Data tab* of your dataset.

There are two options to update your data:
- Update: adds only new data; a unique key (one or more variables) has to be provided
- Append: this adds all data of the uploaded file to the datasets. Note: make sure that you don't upload already existing data!

To start the upload process, use the *Update or Append button* in your dataset's *Primary Data tab*. This link will direct you to the data upload wizard.

<img src=".\images_upload\image18.png" >

Figure 12: Update or Append button.

Follow the upload wizard. The steps are shorty explained. A more detailed explanation is provided in [Chapter 2.4](#24-upload-data).

1. Select file:
    - Choose the file from your local computer and click the *Next button*.

2. Get file information (excel files):
    - Select the header of the data and click the *Header button.*
    - Select the data section of your table and click the *Data button.*
    - If mistakes occur, use the *Reset* button to remove all markings and start over.
    - Click the *Next button* to proceed to the next step.

<img src=".\images_upload\image19.png" />

Figure 13: Define header and data.

3. Specify dataset:
    -  Skip this step if you used the upload button in the dataset's primary data tab.

4. Choose update method:
    - 4a - Update:
        - Define a unique key. Therefore choose one or more variables.
        - Click the *Check button.* You get a message whether the key variables are unique or not.
        - Click the *Next button* to proceed to the next step.

    - 4b - Append:
        - By choosing to append data no further information is required.

<img src=".\images_upload\image20.png" />

Figure 14: Update and append workflow.

5. Validation

    - Click the *Validate button*. This step checks if data structure and primary data match.
    - Validation failed: view the error message and adapt the data structure or your uploaded data.
    - Validation successful: click *Next button*

6. Summary:

    - The wizard provides a summary of the uploaded data
    - Click the *Finish button* to complete the import
    - Depending on the size of your uploaded data you will be directly forwarded to your dataset. Otherwise, you will be informed via mail once the import is   
      completed. During that time your dataset is not accessible.

7. Visual check:

    - Please check your uploaded data under the *Primary Data* tab. In case something looks strange please contact the BExIS Team.

## 4.3 Links and Attachments

Open your dataset. In the *Links tab* you can create new links via the *Create link button* and or delete already existing links.

Under the *Attachments tab* you can upload new attachments and delete old ones.
