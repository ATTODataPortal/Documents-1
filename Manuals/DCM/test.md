<span id="_Toc64318195" class="anchor"></span>**How to upload (BEXIS2
2.14)**

Authors: Cornelia Fürstenau, Franziska Zander

Contact BExIS Team: <bexis@listserv.uni-jena.de>

Contact BExIS Data Curator: bexis-datacurator@uni-jena.de

# Table of content

[**How to upload (BEXIS2 2.14)** 1](#_Toc64318195)

[1. Overview 2](#overview)

[2. Create a dataset with tabular data)
2](#create-a-dataset-with-tabular-data)

[2.1 Create dataset 2](#create-dataset)

[2.2 Metadata 3](#metadata)

[2.3 Data structure 4](#data-structure)

[2.4 Upload data 6](#upload-data)

[2.5 Add data record links (optional)
7](#add-data-record-links-optional)

[2.6 Add attachments (optional) 8](#add-attachments-optional)

[3. Create a new dataset (with/without a file)
9](#create-a-new-dataset-withwithout-a-file)

[3.1Create dataset 9](#create-dataset-1)

[3.2. Metadata 9](#metadata-1)

[3.3. Upload data 10](#upload-data-1)

[3.4. Add data record links and attachments (optional)
10](#add-data-record-links-and-attachments-optional)

## Overview

Under *Upload* are tools to create datasets. The basic functions are
(Figure 1):

-   Create Dataset

-   Create Publication (see separate How to)

-   Upload Data

-   Push Big Files

<img src=".\media_md\media\image1.png" style="width:6.3in;height:1.15625in" />

Figure 1: Functions of the upload menu.

## Create a dataset with tabular data

Creating a new dataset with tabular data includes the following steps:

1.  Create a new dataset

2.  Fill out the metadata

3.  Define data structure

4.  Upload primary data

5.  Add links to other datasets and publications (optional)

6.  Add attachments (optional)

### Create dataset

Create a new dataset by selecting *Create Dataset* in the *Upload* menu
and follow those steps (Figure 2):

1.  *Dataset:*

    1.  to create a blank dataset, choose *New Datase*t -\> next step 2a

    2.  to use an existing dataset as template, select this dataset from
        the list -\> next step 2a or 2b

2.  *Data Structure:*

    1.  define the data structure; chose *Tabular data (new)*; to reuse
        an existing data structure, select *Existing tabular data
        structure* and select a data structure from the list-\> next
        step 3

    2.  use the data structure of the chosen data record (1b), choose
        another existing data structure, or create a new one by choosing
        *Tabular data (new)* -\> next step 4

3.  *Metadata Structure*:

> use the metadata schema called *BE -MetaSchema* -\> next step 4

1.  *Next-button*:

> press the button and fill in the metadata

<img src=".\media_md\media\image2.png" style="width:6.3in;height:2.15625in" />

Figure 2: First steps of creating a new dataset.

### Metadata

Provide detailed metadata to give all essential information about the
data. The metadata is structured in sections. Switch directly to a
section via the metadata tabs (e.g., *General* and *Contact – Figure 3
(1)*).

Note, grey boxes mark automatically filled fields like *Id, Version,
Metadata creation date*. Table 1 explains the use of the buttons in the
metadata.

**Please use the autocomplete functions for the *project name, metadata
creator, data creator, data collector, and contact person!***

Table 1: Buttons in the metadata schema.

| Button                                                                                                                                                                                                         | Description                                                                                                         |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| <img src=".\media_md\media\image3.png" style="width:0.20991in;height:0.19792in" />                                                                                                       | \(1\) info-button offers help when filling out the metadata fields; the info-button on the top shows all help texts |
| \*                                                                                                                                                                                                             | \(2\) mandatory fields                                                                                              |
| <img src=".\media_md\media\image4.png" style="width:0.17708in;height:0.16169in" /><img src=".\media_md\media\image5.png" style="width:0.11875in;height:0.125in" /> | \(3\) opens or closes subsections (topics)                                                                          |
|                                                                                                                                                                                                                | \(4\) the button adds or deletes an additional field                                                                |
| <img src=".\media_md\media\image8.png" style="width:0.40625in;height:0.18281in" alt="Up Down" />                                                                                         | \(5\) use to reorders a list                                                                                        |
| <img src=".\media_md\media\image9.png" style="width:0.23036in;height:0.1875in" />                                                                                                        | \(6\) ome subsections are closed by default (e.g., Coordinates-WGS84); ticking the check box opens subsection       |

<img src=".\media_md\media\image10.png" style="width:6.3in;height:3.1875in" />

Figure 3: Metadata schema

At the end of the metadata schema, there are two buttons - *validate* or
*save*. The validation checks if all mandatory fields are filled and
comply with the metadata standard. Errors and missing content will be
marked in red (Figure 6). Clicking the save button also validates the
dataset, and a warning will pop up if the data is incomplete.
Nevertheless, the metadata can be saved and completed later.

<img src=".\media_md\media\image11.png" style="width:6.3in;height:2.48958in" />

Figure 4: Validation of metadata schema.

### Data structure

The next step is to adjust the data structure to the primary data. Use
the link provided under the tab *Data Structure* of the dataset (Figure
5).

<img src=".\media_md\media\image12.png" style="width:6.3in;height:1.71875in" />Figure
5: Link to edit the data structure.

The data structure describes the variables of the primary data. Choose a
variable template from the predefined list for each variable of the
primary data. There are two filter options to find the templates (Figure
6):

1.  Search: enter search term, e.g., length, mass

2.  Filter: select datatype, unit, or dimension

Add the variable template to the data structure using *arrow button*
(3). Make sure the variable templates are in the same order as the
variables in the data.

<img src=".\media_md\media\image13.png" style="width:6.3in;height:1.90625in" />

In the next step, customize each variable template. Table 2 explains the
fields and the buttons in the variable template (see also Figure 7).

Table 2:Variable Template

<table>
<thead>
<tr class="header">
<th>Fields/buttons</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ol type="1">
<li><blockquote>
<p>Name</p>
</blockquote></li>
</ol></td>
<td>change the variable name; it has to be the identical name as used in the primary data</td>
</tr>
<tr class="even">
<td><ol start="2" type="1">
<li><blockquote>
<p>Unit</p>
</blockquote></li>
</ol></td>
<td>select the appropriate unit</td>
</tr>
<tr class="odd">
<td><ol start="3" type="1">
<li><blockquote>
<p><em>Optional</em> (checkbox)</p>
</blockquote></li>
</ol></td>
<td>allows empty cells in the data (not preferred!)</td>
</tr>
<tr class="even">
<td><ol start="4" type="1">
<li><blockquote>
<p><img src=".p\media_md\media\image14.png" style="width:0.10435in;height:0.13565in" /></p>
</blockquote></li>
</ol></td>
<td>shows the whole template</td>
</tr>
<tr class="odd">
<td><ol start="5" type="1">
<li><blockquote>
<p><em>Description</em></p>
</blockquote></li>
</ol></td>
<td>add a variable description</td>
</tr>
<tr class="even">
<td><ol start="6" type="1">
<li><blockquote>
<p><em>Missing value</em></p>
</blockquote></li>
</ol></td>
<td><p>there is one predefined missing value</p>
<p><em>-Placeholder:</em> per default <em>na</em>, but can be customized</p>
<p><em>-Description:</em> add a description</p></td>
</tr>
<tr class="odd">
<td><ol start="7" type="1">
<li><blockquote>
<p>Trash bin<img src=".\media_md\media\image15.png" style="width:0.14074in;height:0.16522in" /></p>
</blockquote></li>
</ol></td>
<td>use to delete a variable template</td>
</tr>
</tbody>
</table>

If you cannot find an appropriate variable template or a specific unit
is missing, please contact the BExIS team!

Finally, save the data
structure<img src=".\media_md\media\image16.png" style="width:2.85208in;height:1.04028in" />
and go back to your dataset (use the browser back button).

<img src=".\media_md\media\image17.png" style="width:6.3in;height:2.70833in" />

Figure 7: Edit a variable template.

### Upload data

To start the upload process, use the *upload button* in your dataset's
primary data tab (Figure 8). This link will direct you to the data
upload wizard.

<img src=".\media_md\media\image18.png" style="width:6.3in;height:1.79167in" />

Figure 8: Start data upload.

Now follow the upload wizard (Figure 9):

1.  Select file:

    -   Choose the file from your local computer. The wizard supports
        file formats of Microsoft Excel or text (UTF-8) (\*.xlsm,
        \*.xlsx, \*.txt, \*.csv, \*.tsv). After selecting the file,
        click the *Next button*.

2.  Get file information (excel files):

    -   The first datasheet of the selected file is displayed. If you
        wish to upload data from a different worksheet use the *Change
        Worksheet button*. Please be aware that you can only upload data
        from one sheet at a time.

    -   Note: The representation of the data in the upload wizard might
        differ from Microsoft Excel or similar programs. Nevertheless,
        the data will be uploaded correctly.

    -   Provide the information which cells contain the header
        (variables). Select the row or one part of a row containing the
        variable names and click the *Header button*.

    -   Mark the data section by selecting multiple rows and clicking
        the *Data button*. The selected area will be highlighted in
        blue. Please make sure that the data area contains as many
        columns as the header. You can use the *Expand Selection button*
        to expand the already selected data area to the last row of the
        file.

    -   If mistakes occur, use the *Reset* button to remove all markings
        and start over.

    -   Click the *Next Button* to proceed to the next step.

3.  Specify dataset

    -   Skip this step if you used the upload button in the dataset's
        primary data tab.

4.  Validation

    -   Click the *Validate Button*. This step checks if the data
        structure and the primary data match.

    -   Validation failed: View the error message and adapt the data
        structure or your uploaded data. You can open the data structure
        in a second tab, change it and validate it again. If you need
        help: send a mail with the error message and the dataset id to
        the BExIS-Team. If the data file is not too big, please also
        attach it.

    -   Validation successful: click *Next Button*

5.  Summary:

    -   The wizard provides a summary of the uploaded data

    -   Click the *Finish button* to complete the import

    -   Depending on the size of your uploaded data you will be directly
        forwarded to your dataset and you can view your data. Otherwise,
        you will be informed via mail once the import is completed.
        During that time your dataset is not accessible.

6.  Visual check:

    -   Please check your uploaded data under the *Primary Data* tab. In
        case something looks strange please contact the BExIS Team.

<img src=".\media_md\media\image19.png" style="width:6.3in;height:2.36458in" />

Figure 9: First page of upload wizard.

### Add data record links (optional)

Under the tab *Links* of the dataset (Figure 10), you can add
linked/related datasets and publications. Links always refer to a
specific version of a dataset. To insert links, click on *Create link*

<img src=".\media_md\media\image20.png" style="width:6.3in;height:2.77083in" />

Figure 10: Create a link.

Provide the following information while creating a link:

1.  *Type*: dataset or publication

2.  *Title:* select a data record from the list. Tip: start to type in
    the title, and the system will narrow down the results.

3.  *Version:* choose an appropriate version of the data record

4.  *Reference Type:* select a reference type. These indicated the
    relation to the other dataset (Table 2).

Table 3: Reference types.

| Link type              | description                                                                                                      |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| Collection             | linked dataset is part of a collection (e.g., header data and species data)                                      |
| Link                   | unspecific link to a dataset or publication                                                                      |
| Is supplement to       | linked dataset is used in the current publication (only to link publication and dataset)                         |
| Is supplemented by     | linked publication uses the current dataset (only to link dataset and publication)                               |
| Is new version of      | linked dataset is a newer version of the current dataset                                                         |
| Is previous version of | linked dataset is an older version of the current dataset                                                        |
| Is continued by        | indicates that the current dataset is continued by the linked dataset (e.g., for time series)                    |
| Is derived from        | linked dataset is a source upon which the current dataset is based                                               |
| Is source of           | the original dataset is the source of the linked dataset                                                         |
| Compiles               | linked dataset (e.g., synthesis datasets) is the result of a compile or creation event using the current dataset |
| Is compiled by         | linked dataset is used to compile or create the current dataset (e.g., synthesis datasets)                       |

### Add attachments (optional)

Additional files (e.g., files documenting primary data collection and
creation like images, documents, and protocols) may be added to the
datasets. Use the *Select Button* to upload one or more files. Please
provide a short description of your selected file(s).

## Create a new dataset (with/without a file)

Creating a new data set for unstructured data (documents, images,
GIS-files) or data stored in an external repository includes the
following steps:

1.  Create a new dataset

2.  Fill out the metadata

3.  Upload file(s) (optional)

4.  Add links to other datasets and publications (optional)

5.  Add attachments (optional)

### 3.1 Create dataset

To set up a new dataset, select *Create Dataset* in the *Upload* menu
(Figure 1) and follow those steps:

1.  *Dataset:*

    1.  to create a blank dataset, choose *New Datase*t -\> next step 2a

    2.  to use an existing dataset as template, select this dataset from
        the list -\> next step 2b

2.  *Data Structure:*

    1.  define the data structure; select *Existing file data structure*
        and chose a data type from the list-\> next step 3

    2.  use the data structure of the chosen dataset (1b), choose
        another existing data type -\> next step 4

3.  *Metadata Structure*:

> use the metadata schema called *BE -MetaSchema* -\> next step 4

1.  *Next-button*:

> press the button and fill in the metadata

###  Metadata

Read Chapter 2.2 for instructions.

###  Upload data

To start the upload process, use the upload button in your dataset's
primary data tab (Figure 11). This link will direct you to the data
upload wizard.

<img src=".\media_md\media\image18.png" style="width:6.3in;height:1.79167in" />

Figure 11: Start data upload.

Now follow these steps of the upload wizard:

1.  Select file:

    -   Choose the file from your local computer. After selecting the
        file, click the *Next button*.

2.  Specify dataset

    -   Skip this step if you used the upload button in the dataset's
        primary data tab. The dataset is already selected. Press the
        *Next Button.*

3.  Summary:

    -   The wizard provides a summary of the uploaded data

    -   Click finish button

    1.  ### Add data record links and attachments (optional)

Read Chapter 1.5 and 1.6 for instructions.

