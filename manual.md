Authors
* Ulf Kroehne
* Carolin Hahnel

Acknowledgements
* Sylvia Krueger
* Florian Remmers
* Corinna Dziudzia
* Gabriele Gissler
* Britta Upsing

Contents

[How to use this manual iv](#_Toc380472884)

[Part I: IB at a Glance 1](#ib-at-a-glance)

[I.1 Introduction 1](#introduction)

[I.1.1 Why an Item Authoring Tool? 1](#_Toc380472887)

[I.1.2 Benefits using an Item Authoring Tool 1](#benefits-using-an-item-authoring-tool)

[I.1.3 Test Deployment and Navigation 2](#_Toc380472889)

[I.1.4 Glossary 3](#_Toc380472890)

[I.2 Real Life Examples 4](#_Toc380472891)

[I.2.1 Click Responses 5](#_Toc380472892)

[I.2.2 Text entries 8](#text-entries)

[I.2.3 Advance Response Formats 9](#advance-response-formats)

[I.2.4 Multi-Page Questionnaires 11](#multi-page-questionnaires)

[I.3 Contact, Support, and Technical Details 12](#_Toc380472896)

[I.3.1 Technical Information for Delivery 12](#_Toc380472897)

[I.3.2 Terms of License 12](#_Toc380472898)

[Part II: User Guide 13](#_Toc380472899)

[II.1 Installation 13](#_Toc380472900)

[II.1.1 System Requirements 13](#system-requirements)

[II.1.2 Setup Wizard 13](#setup-wizard)

[II.1.3 Manual Installation (X-Copy Deployment) 14](#_Toc380472903)

[II.1.4 Deinstallation 15](#_Toc380472904)

[II.1.5 Migrating Projects 16](#_Toc380472905)

[II.2 First Start of the IB 16](#_Toc380472906)

[II.2.1 Start an Instance 17](#_Toc380472907)

[II.2.2 Open, Preview, Save and Close Projects 17](#_Toc380472908)

[II.2.3 Graphical User Interface 21](#_Toc380472909)

[II.3 Generate Items with the IB 30](#_Toc380472910)

[II.3.1 Basics of IB Item Design 30](#_Toc380472911)

[II.3.2 Use of Additional Syntax 35](#_Toc380472912)

[II.3.3 Resources 36](#_Toc380472913)

[II.3.4 Design a Page 38](#_Toc380472914)

[II.3.5 Use Multiple Pages 46](#_Toc380472915)

[II.3.6 Templates 50](#_Toc380472916)

[II.3.7 General Remarks on the Item-Design-Workflow 55](#_Toc380472917)

[II.4 Scoring 56](#_Toc380472918)

[II.4.1 The Task Editor 56](#_Toc380472919)

[II.4.2 Scoring an Item 57](#_Toc380472920)

[II.4.3 Conditional Literals and Conditional Operators 63](#conditional-literals-and-conditional-operators)

[II.4.4 Examples 65](#_Toc380472922)

[II.4.5 Checking Scoring Implementation 69](#_Toc380472923)

[II.5 Finite State Machines (FSM) 70](#_Toc380472924)

[II.5.1 Variables 70](#_Toc380472925)

[II.5.2 Events 77](#_Toc380472926)

[II.5.3 States 78](#_Toc380472927)

[II.5.4 Rules 81](#_Toc380472928)

[II.5.5 Graphical FSM Editor 85](#_Toc380472929)

[II.5.6 Examples 86](#_Toc380472930)

[II.6 Advanced Functions 93](#_Toc380472931)

[II.6.1 Commands 93](#_Toc380472932)

[II.6.2 Regular Expressions 94](#_Toc380472933)

[II.6.3 Dynamic Text in HTMLTextFields 98](#_Toc380472934)

[II.6.4 Conditional Linking and Task Initializing 100](#_Toc380472935)

[II.6.5 Item Translation (OLT) 109](#_Toc380472936)

[Part III: Cookbook 110](#_Toc380472937)

[III.1 Project Structure 110](#_Toc380472938)

[III.1.1 Simple Pages 110](#simple-pages)

[III.1.2 Navigation between Pages and Page Selection 113](#navigation-between-pages-and-page-selection)

[III.1.3 X-Pages 120](#_Toc380472941)

[III.1.4 Web Browser and Web Child Pages 125](#_Toc380472942)

[III.1.5 Tabfolder Page 129](#tabfolder-page)

[III.1.6 Taskbar Page 130](#_Toc380472944)

[III.1.7 Dialogs and Modal Dialogs 131](#_Toc380472945)

[III.2 Use Specific Response Elements 134](#_Toc380472946)

[III.2.1 CheckBox 134](#checkbox)

[III.2.2 Radio Buttons 135](#radio-buttons-1)

[III.2.3 Input Fields 136](#_Toc380472949)

[III.2.4 Combo Box and Lists 137](#_Toc380472950)

[III.2.5 Menu 143](#menu)

[III.2.6 Image Map 146](#_Toc380472952)

[III.2.7 Highlighting 154](#_Toc380472953)

[III.3 Using Dynamic Functions 159](#_Toc380472954)

[III.3.1 Value Displays 159](#value-displays)

[Part IV: Things you might need to know … 160](#_Toc380472956)

[IV.1 Things of Suboptimal Usability 160](#things-of-suboptimal-usability)

[IV.2 Things You Might Not Expect to Work but Actually Do 161](#things-you-might-not-expect-to-work-but-actually-do)

[IV.3 Things That Do Not Work 162](#things-that-do-not-work)

[List of Figures 163](#list-of-figures)

[References 167](#references)

<span id="_Ref361425403" class="anchor"><span id="_Ref352174845" class="anchor"></span></span>

The present manual seeks to help test and item authors to understand the general concept of the software *CBA ItemBuilder* (IB), i.e., which components, functionalities and features are included, and how to use them.

The different parts of this manual:

The first part introduces the IB as a tool for item authoring (Part I: IB at a Glance). The second part gives a detailed description about how to use the specific features of the IB (Part II: User Guide). This is followed by a third part, which guides through the building process necessary to create items with specific properties step-by-step (Part III: Cookbook). Finally, the last part points out possible drawbacks or difficulties regarding the usability of the IB (Part IV: Things you might need to know …).

As a supplement, the IB manual includes a digital folder with a variety of IB projects (*IB\_manual\_examples*). The examples (zip-files) in this folder can be opened with the IB (see II.2.2.2). They serve as construction examples to understand certain features or sub-steps easier.

Furthermore, some of the manual’s screenshots will refer to these examples. Figure 1 provides an example for such a reference. In the upper right corner of figure 1 the name of the used zip-file is given (see the red circle in the screenshot). If you want to follow the instructions step-by-step, you can open the corresponding IB project within the IB environment (see II.2.2.2 for how to open an IB project).

|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref367891080" class="anchor"><span id="_Ref367891076" class="anchor"><span id="_Toc380472962" class="anchor"></span></span></span>Figure 1. Illustration of Correspondence to ZIP-File Examples in the IB Manual |

However, this manual can only give an introduction to general functions and work processes in the IB. As the IB is constantly improved and its functionalities can be used in manifold ways, this manual claims no totality. Your opinions as IB users, however, matter and we are always pleased to receive any suggestions, especially for the ‘Cookbook’ part. You can find our contact information in section I.3.

IB at a Glance
==============

This part gives a brief overview about what the *CBA ItemBuilder* (IB) actually is and how it can be used. Chapter 1 seeks to outline why an item authoring tool such as the IB is needed and in which settings it can be used. Regarding the field of application, computer based test delivery and navigation are addressed, too. Subsequently, the chapter closes with an exemplification of the used technical terms. Chapter 2 presents some examples of real computer based items which have been created with the IB. The examples are classified by different formats of response and also provide an idea of item arrangement and embedding. The last chapter of part I contains details on contact, offered support as well as technical information and the terms of license.

Introduction
------------

### <span id="_Ref366827236" class="anchor"><span id="_Toc380472887" class="anchor"></span></span>Why an Item Authoring Tool?

Computer based and technology based assessment is gaining importance in fields of research that investigate human education, experience and behavior. Methods of technology based assessment provide many advantages for testing in general and measuring competencies in particular (cf. Bugbee, 1996; Clariana & Wallace, 2002; Mason Patry & Bernstein, 2001). On the way to a computer based test, however, a first obstacle often lies in the development and technical implementation of a single item. The *CBA ItemBuilder* provides an easy solution: It is an authoring tool for computer based assessment that enables test authors to design different item types with a graphical editor.

The unique feature of the IB is its suitability for persons with no or hardly any programming experiences. Therefore, it is possible that researchers with no specific IT background can create and implement complex items on their own within a fairly short time. The IB itself provides a graphical designer that looks very much like a WYSIWYG editor with a toolbox window that can be used to add elements to the design view of the item. Item authors can use this graphical editor to design one or several items by creating pages with images, texts or videos, implementing special features for test takers like timers or feedback loops, and defining rules for automatic scoring.

The available features of the IB are permanently extended and updated. This manual describes version 05-00-00 of the IB and many of the features available in this version. For further information about the different versions of the IB see chapter II.1.5. Note that some of the screenshots might show older versions of the IB.

### Benefits using an Item Authoring Tool 

The need of computerized items for technology based assessment is equivalent to asking for a specific computer program which shows the item stimulus and linked questions on a computer screen, to show the additional input elements with their specific behavior and to gather all log, process and result data. Implementing computer programs or web pages would usually require technical efforts, i.e., programming. However, if each item for technology based assessment would be a separate computer program or web page, the developed programs would be very similar to each other from a technical point of view. To avoid this redundancy, the IB was developed as a graphical editor to define a variety of different items. For these items the IB adopts the role of the programmer.

When an item author saves his or her creation, the IB stores a zip-file in which it automatically generates the needed program code necessary for the item defined at the design time (*Code Generation*). The generated code, the item definition as well as all included resources bundled in a zip-file then provides the basis for technical displaying and presenting the item to test takers at run-time and gathering different kinds of log, process and result data (see Figure 2).

### <span id="_Toc377756430" class="anchor"><span id="_Toc377809302" class="anchor"><span id="_Toc380472889" class="anchor"></span></span></span>Test Deployment and Navigation

Computer based assessment can be implemented with different test deployment strategies, which are described in the following.

*Notebook*. Software for offline test delivery, i.e., for item sequencing, data storage, account management and response logging, is installed on notebooks. Offline delivery with notebooks provides the highest operational safety, because the software for offline test delivery can be installed on the target systems (notebooks) with administrative privileges. Hence, test authors are able to define specific actions which the test takers are allowed to do in the offline test delivery system. In this way test authors can also guard the content of their items. Notebook delivery, though, can cause logistic challenges, especially regarding storage and transport.

*Online*. A more comfortable deployment option is online delivery, i.e., browser based testing. For online delivery, a) a central web server has to be set up with an appropriate software for online test delivery which provides items and item resources, functionalities for data storage and item sequencing as well as b) an application server is necessary for running interactive parts of the items (such as finite state machines, see section II.5). Online test deployment is based on standard web technologies (HTML5) with standard protocols (http, https) and the necessary browser requirements (e.g., JavaScript) are low. To support a larger number of concurrent users, however, using one server might not be sufficient. In this case, a so-called server farm or a cloud solution has to be considered. No specific software is expected on the client side because standard web browsers are used to render items developed with the IB. In principle, all devices connected to the internet can be used, but often this has to be restricted to devices offering certain features like a minimum of screen size, a special browser version, etc. Test security is also more difficult to maintain in an online assessment setting, because the software within the browser runs with restricted access to system resources.

*USB flash drive*. Delivery by USB flash drives combines some advantages of notebook and online delivery. It concedes the test author to define exactly possible actions within the test, but it is also very flexible in bringing the test to the test taker. A compatible hardware, though, is presumed at the place of test administration, e.g., in classroom settings within schools.

#### Integration in Delivery Systems

The IB is a flexible item authoring tool, capable for various item types and formats. However, the developed items cannot be used for CBA without an additional software for “test deployment”, i.e., to administer tests composed by multiple items or units, additional software that controls access to the test or the items, the navigation between items and the storage of data is necessary.

A web browser is used for platform independent presentation of items developed with the IB and a portable version of the Firefox browser is used in the current version for previewing items (see II.2.2.3 for preview function), but using other browsers at run-time is possible as well.

A simple delivery system, the *Execution Environment*, is bundled with the IB. Other delivery systems that can be used with the IB are the *TAO* system[1] as well as, with the help of a *TBA Tools*, an implementation of the JavaScript API which can be used to include the generated code for items in browser-based environments.

Note that items created with the IB also can be integrated in other existing software packages and web applications (see section I.3.1 for more information about the technical documentation). Hence, items created with the IB are “delivery-independent” (I.1.1) und the items can be used under different test deployment scenarios. Each of the deployment scenarios contains different advantages and disadvantages. The particular scenario used for test deployment of a specific test has to be selected individually for each research project.

| ![](images/media/image3.png)                                                                                                                                    |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref380391150" class="anchor"><span id="_Toc380472963" class="anchor"></span></span>Figure 2. Idea of code generation and item presentation in the IB |

#### Navigation Method 

Navigation addresses questions about how to move *between* or *within* IB items. Inside, each IB item has to provide the necessary user interface components (e.g., Buttons, Links) to allow task-completion as well as navigation between pages.

Test authors can also decide how test takers can navigate between IB items. This navigation is usually implemented with the help of the chosen delivery platform. Options referring to forward, backward, or hidden navigation might be available and have to be chosen by the test author.

### <span id="_Toc377756432" class="anchor"><span id="_Toc377809304" class="anchor"><span id="_Toc380472890" class="anchor"></span></span></span>Glossary

A computer based test usually consists of one or several items. We name the elements which require the test taker to give a response as the “answer” of the item. An item usually consists of a stimulus, i.e., the material that the test taker is supposed to work with before accomplishing the task (e.g., texts or charts), and a task that the test taker is supposed to accomplish (e.g., an instruction or a question). We use the term “unit” for stimuli that are aligned to multiple items. More terms are described shortly in Table 1.

<span id="_Ref367885217" class="anchor"></span>Table 1: Terminology

| Term                        | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Container                   | Elements that can hold other elements are called “containers”. Elements that belong to a common container might share properties (see 0 for a description).                                                                                                                                                                                                                                                                                                                    |
| Elements                    | Each container can hold one or multiple elements. Elements can be part of the presentation layer (e.g., texts or images), elements can represent response options (e.g., RadioButtons), and elements can be containers which can hold several related (child-)elements (e.g., RadioButtonsGroups).                                                                                                                                                                             |
| Finite State Machines (FSM) | Finite state machines allow to modify the visual presentation or behavior of items in a very flexible way (see II.5), according to states of “machines”, i.e., distinct values of variables. Many of the advanced functions of the IB can be constructed by using one or multiple finite state machines, such as “Drag and Drop” (**Fehler! Verweisquelle konnte nicht gefunden werden.**).                                                                                    |
| Item                        | An element of a test corresponding to an exercise with either one or more related questions.                                                                                                                                                                                                                                                                                                                                                                                   |
| Navigation                  | The term “navigation” is used to describe how test takers can move between different pages, items and units. Response elements (e.g. Buttons) can be used to trigger navigation (see II.3.5), either with the help of commands or links.                                                                                                                                                                                                                                       |
| Page                        | Each project consists of one or more pages. Pages can contain containers and elements, e.g., presentation elements (such as texts, images) and response elements (such as inputfields, check boxes, buttons or hyperlinks; see II.3).                                                                                                                                                                                                                                          |
| Page Type                   | Each page is of a particular type, and several page types are available in the IB. The elements and containers which can be used to create a page depent on the page type. I.e., pages of different types have to be used to implement specific parts of a computer based item. The type of a page, e.g., *WebBrowserPages*, *TaskBarPages*, *Dialog* and *Modal Dialog* (see II.3.1.1) is defined when the page is created and it is impossible to change the type of a page. |
| Palette                     | The palette is the “toolkit” of the item authoring system, containing all elements and containers that can be added to a page of a particular type (see II.2.3.5).                                                                                                                                                                                                                                                                                                             |
| Project File                | Test authors build and edit “project files” within the IB. A project file can contain either a single item, several units, or even a complete test. The decision about how many separate files are used to computerize a particular test material is up to the test author. Howerver, very large files with many items in single IB project are not suggested, because the size of the zip-files might become too large.                                                       
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                               For the sake of simplicity, projects described in this manual contain only a single item, unless otherwise stated. Note that the name of the project and the saved zip-file are identic (see II.2.2.7).                                                                                                                                                                                                                                                                         |
| Properties                  | The term properties refers to the specific design and features of a selected element (see II.2.3.6). Properties are listed and can be changed in the *Properties View*.                                                                                                                                                                                                                                                                                                        |
| Ressources                  | Resources include all elements that have been uploaded in the IB for creating items, e.g., pictures, audio and video files (see II.3.3).                                                                                                                                                                                                                                                                                                                                       |
| TAO                         | The TAO framework is an open-source project which provides a very general and open architecture for computer-assisted test development and delivery.                                                                                                                                                                                                                                                                                                                           |
| Template                    | Pages can be saved as templates for re-using a created page inside and outside of a project file, i.e., in the same or other projects several times (see II.3.6).                                                                                                                                                                                                                                                                                                              |
| Scoring                     | Scoring refers to the automatized assessment of the test taker’s response (see II.4). Test authors can precisely define scoring patterns for each possible response. Scoring patterns are organized within tasks.                                                                                                                                                                                                                                                              |
| Task                        | IB tasks are selfcontained item-packages defined by test authors. They have two functions: IB tasks interconnect IB items with the delivery system as so called *entry points* (see II.4.1) and they also include rules for automatic scoring (see II.4.2).                                                                                                                                                                                                                    |

<span id="_Ref366833487" class="anchor"></span>

<span id="_Ref377120370" class="anchor"><span id="_Toc380472891" class="anchor"></span></span>Real Life Examples
----------------------------------------------------------------------------------------------------------------

The purpose of an assessment is usually to measure certain skills or competencies of test takers (e.g., reading, problem solving). With the IB it is possible to create test scenarios that allow measuring competencies in different areas or domains. Therefore, the IB supports a wide range of item formats and characteristics for computer based test items. From static to dynamic, from simple to complex, using only text or multimedia, with a linear or a hyper textual structure – many different item types can be created.

To name just a few, item formats (sorted by increasing difficulty) might be

simple multiple choice questions with each question on a separate page,

assessment in unit structure with a text stimulus followed by multiple aligned questions,

simulated browser and hypertext for the assessment of digital reading competence ,

behavior and simulation-based assessment of ICT-literacy ,

assessment of Problem Solving (PS), dynamic PS, and collaborative PS , and

assessment embedded in simulated, complex computer environments.

Answers and responses from computerized test items can be collected by different response formats. Some of them are comparable with response modes in paper based assessments; others make use of specific interactions that are only possible in computer based assessments. The IB supports a variety of response formats out-of-the-box. Additional response formats can be realized using the advanced functions of the IB (e.g., finite state machines).

The number of response formats supported by an item authoring tool determines the range of item types that can be created with this particular software. The following examples in this section should illustrate typical response formats available with the IB. Although not exhaustive, the list should give a first impression of possible response formats and item types.

### <span id="_Toc377756435" class="anchor"><span id="_Toc377809307" class="anchor"><span id="_Toc380472892" class="anchor"></span></span></span>Click Responses 

Click responses represent a rather simple type of response formats given in computer based testing. Items that contain click responses can be solved only by using a mouse or, in case of touchpads, by pointing on the touchscreen. Click responses are mainly used in tasks that require a selection out of several alternatives or marking of a specific area, for instance, in a chart.

#### Check Boxes 

Check boxes can be used when test takers have to select several elements from a given assortment. The selection itself serves as response. Check boxes are activated by clicking on the corresponding field or, if available, on the text near to the field[2] (Figure 3). It is possible to deselect each check box.

| ![](images/media/image4.png)                                                                                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361423368" class="anchor"><span id="_Toc380472964" class="anchor"></span></span>Figure 3. Example of Selection/Identification Implemented with Check Boxes in the IB (from Scalise, 2006, Figure 2) |

#### Radio Buttons

Compared to check boxes, radio buttons are also used for selecting an element of a given group. In contrast, radio buttons only allow one selection at a time (Figure 4). The circle (i.e., the radio button) itself can be clicked to give the answer as well as the text or image next to the radio button.

| ![](images/media/image5.png)                                                                                                                                                                       | ![](images/media/image6.png) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|
| <span id="_Ref367899211" class="anchor"><span id="_Toc380472965" class="anchor"></span></span>Figure 4. Examples of Multiple Choice with Radio Buttons (from Scalise, 2006, Figure 2 and Figure 4) |

In the IB radio buttons are assigned to groups (so called radio-button-groups) to bundle radio buttons that belong together to one item. Within each radio-button-group only one element can be selected. Note that once a radio button of a group is selected, it is usually impossible to deselect it (see **Fehler! Verweisquelle konnte nicht gefunden werden.**).

With multiple radio-button-groups several single-choice items can be implemented in one project or at one page, respectively. Multiple radio button groups or check boxes arranged in rows or columns (known as complex multiple choice, CMC) can be created in this way (see Figure 5 for an example).

| ![](images/media/image7.png)                                                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref367899362" class="anchor"><span id="_Toc380472966" class="anchor"></span></span>Figure 5. Example of Rearrangement Implemented with RadioButtons in the IB (from Scalise, 2006, Figure 12) |

<span id="_Ref367980293" class="anchor"></span>

#### Image Maps

| ImageMapExample.zip | Preview                                                                                                           |
|-----------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image8.png)                                                                                                            |
| <span id="_Toc380472967" class="anchor"></span>Figure 6. Example of an Item Using Image Maps to Provide Clickable Areas in a Coordinate |

#### Combo Boxes

| ![](images/media/image10.png)                                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref367899944" class="anchor"><span id="_Toc380472968" class="anchor"></span></span>Figure 7. Example of Substitution / Correction with Combo Box (from Scalise, 2006, Figure 14) |

### Text entries 

#### Single Line Input Fields

| ![](images/media/image11.png)                                                                                                                                                              |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref367900212" class="anchor"><span id="_Toc380472969" class="anchor"></span></span>Figure 8. Example of Completion with Single Line Input Field (from Scalise, 2006, Figure 19) |

| ![](images/media/image12.png)                                                                                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361504570" class="anchor"><span id="_Ref361504566" class="anchor"><span id="_Toc380472970" class="anchor"></span></span></span>Figure 9. Example of Completion with Single Line Input Field (from Scalise, 2006, Figure 18) |

#### Input Fields

| ![](images/media/image13.png)                                                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref367900256" class="anchor"><span id="_Toc380472971" class="anchor"></span></span>Figure 10. Example of Construction with Input Field (from Scalise, 2006, Figure 25) |

### Advance Response Formats

#### Using navigation elements as response format

|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| <span id="_Ref367900354" class="anchor"><span id="_Toc380472972" class="anchor"></span></span>Figure 11. Example of Construction with Buttons (from Goldhammer et al., 2012, released item) |

#### Using processing steps as response format

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| <span id="_Ref367900678" class="anchor"><span id="_Toc380472973" class="anchor"></span></span>Figure 12. Example of Construction with Menu Entries (from Goldhammer et al., 2012, released item) |

#### Drag and Drop

| Waage.zip | Preview                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image18.png)                                                                                                            |
| <span id="_Ref367900501" class="anchor"><span id="_Toc380472974" class="anchor"></span></span>Figure 13. Example of a Drag and Drop item |

#### Highlighting

| ![](images/media/image20.gif)                                                                                                                                                                               | ![](images/media/image21.png) |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <span id="_Ref367900584" class="anchor"><span id="_Toc380472975" class="anchor"></span></span>Figure 14. Example of Construction with Highlightable Text (from NCES, 2013, released OECD PIAAC sample item) |

### Multi-Page Questionnaires

| PQExample.zip | Design View & Preview                                                                                                    |
|------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image22.png)                                                                                                            |
| <span id="_Ref367900721" class="anchor"><span id="_Toc380472976" class="anchor"></span></span>Figure 15. Example Page of a Questionnaire |

<span id="_Ref367956324" class="anchor"><span id="_Ref368463893" class="anchor"><span id="_Ref369774537" class="anchor"><span id="_Toc380472896" class="anchor"></span></span></span></span>Contact, Support, and Technical Details
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you want to use the IB for building up items for your own research or assessments, please consider the terms of license (see I.3.2). To obtain a copy of the IB send a request to <tba-info@dipf.de>.

### <span id="_Toc377809315" class="anchor"><span id="_Ref370719113" class="anchor"><span id="_Toc380472897" class="anchor"></span></span></span>Technical Information for Delivery 

The technical requirements for the delivery of IB items are described in detail in the document “CBA-AdminManual.pdf“, which can be requested from TBA.

### <span id="_Ref374549538" class="anchor"><span id="_Toc380472898" class="anchor"></span></span>Terms of License

The license is included in the installer.

<span id="_Ref367891496" class="anchor"><span id="_Toc380472899" class="anchor"></span></span>User Guide
========================================================================================================

In this second part, general information about working with the *CBA ItemBuilder* (IB) is provided. Chapter II.1 is about technical requirements for the use and installation of the IB and describes how to deal with different versions. In chapter II.2 the general user interfaces, important views and different settings of the IB are introduced. Chapter II.3 explains basic features for designing items with the IB. Chapter II.4 is about the implementation of item scoring, i.e., about how to define a final score for different possible responses. A detailed introduction of the so-called Finite State Machine (FSM), used to develop innovative, interactive item types, is given in chapter II.6.

<span id="_Toc377735683" class="anchor"><span id="_Toc377756445" class="anchor"><span id="_Toc377809319" class="anchor"><span id="_Ref377809648" class="anchor"><span id="_Toc380472900" class="anchor"></span></span></span></span></span>Installation
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### System Requirements

Before you start the installation of the IB make sure that your computer fulfills the following system requirements:

-   Operating system: Windows XP, Windows Vista, Windows 7, Windows 8 or Windows 8.1

-   CPU: Pentium D or higher, 2.6 GHz or higher (Pentium 4 or higher, 2 GHz or higher for XP)

-   RAM: At least 1 GB main memory

-   HDD: More than 750 MB free disk space

### Setup Wizard

To install the IB, start the “IB-{Version}-Setup.exe”. Make sure that you run this setup as ‘Administrator’. After verifying the installer, the following wizard is shown:

| Step 1   | ![](images/media/image24.png) | Step 2   | ![](images/media/image25.png) |
|----------|-------------------------------|----------|-------------------------------|
| Step 3   | ![](images/media/image26.png) | Step 4   | ![](images/media/image27.png) |
| Step 5   | ![](images/media/image28.png) | Step 6   | ![](images/media/image29.png) |

| <span id="_Toc380472977" class="anchor"></span>Figure 16. Setup wizard for the IB |
|-----------------------------------------------------------------------------------|

Please read the license agreement (step 2) and accept by selecting “I Agree”.

Note that the destination folder selected in step 3, must not contain white spaces (e.g., “C:\\my work related programs\\”) and the overall length of the path (i.e., the depth in your computers directory tree) should be small. By default, the setup wizard suggests the directory “C:\\CBAIB\\{Version-Number}\\” which should work on most systems. Do not modify this directory unless it is necessary.

In step 4, optional features can be selected: The “Demo Projects” contain technical examples, used to test each new version of the IB, and the “Manual (PDF)” includes a PDF version of this manual as well as the examples, described in this document. After selecting or de-selecting the optional components, press the “Install” - button to start the installation. The actual installation in step 5 might take several seconds.

Note that multiple versions of the IB can be installed simultaneously on your computer.

### <span id="_Ref367985731" class="anchor"><span id="_Toc380472903" class="anchor"></span></span>Manual Installation (X-Copy Deployment)

The TBA group (see I.3) might also provide a zip-file as download containing the IB program and a user’s license (“allFeatures.cbalicense”). For installation of the IB just unzip the zip-archive with suitable software (e.g., 7zip). Afterwards the IB can be started by (double-) clicking on “cba-itembuilder.exe”.

|----------------------------------------------------------------------------------------------------------------------|
| <span id="_Toc380472978" class="anchor"></span>Figure 17. Start the IB by (double-)clicking on „cba-itembuilder.exe“ |

> **Important Note 1:** *Directory depth* – To avoid any processing problems make sure to choose a rather low directory depth for installation.
>
> **Good:** C:\\IB\\
>
> **Bad:** C:\\Users\\User.Domain.etc.\\Desktop\\MyCurrentProjects\\CBA\_ItemBuilder\_DIPF\\etc.
>
> **Important Note 2:** *Licensing –* Without a license the IB will just provide a grey surface without menu entries (e.g., file) when starting the program. In case of failing, copy your license in the unzipped IB archive. Otherwise, please contact the IB support (I.3).
>
> **Important Note 3:** To use the IB Scoring-Viewer function (see II.4.5) you might have to add a line in the configuration file “cba-itembuilder.ini”. If the viewer does not work, you have to type in “-DAllowScoreDebugging=true” in a separate line by using any text editor program.
>
> **Tip:** We recommend creating a shortcut on the desktop of „cba-itembuilder.exe“. It is easy to implement by right-clicking on „cba-itembuilder.exe“, selecting “Send to” and “Desktop (create shortcut)” (Figure 18).

| ![](images/media/image31.png)![](images/media/image31.png)                                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref367955507" class="anchor"><span id="_Ref367955476" class="anchor"><span id="_Toc380472979" class="anchor"></span></span></span>Figure 18. How to create a Shortcut on the Desktop |

### <span id="_Ref366826895" class="anchor"><span id="_Toc380472904" class="anchor"></span></span>Deinstallation

A deinstallation of a previous version of the IB is (technically) not necessary. Multiple version of the IB can be used in parallel on the computer. However, if you have used the install wizard, the IB can be uninstalled by using the “uninstall.exe” from the selected installation directory. Otherwise, just delete the IB folder.

| Step 1   | ![](images/media/image32.png) | Step 2   | ![](images/media/image33.png) |
|----------|-------------------------------|----------|-------------------------------|

| <span id="_Toc380472980" class="anchor"></span>Figure 19. Uninstall IB |
|------------------------------------------------------------------------|

### <span id="_Toc377756451" class="anchor"><span id="_Toc377809325" class="anchor"><span id="_Toc377756452" class="anchor"><span id="_Toc377809326" class="anchor"><span id="_Toc377756453" class="anchor"><span id="_Toc377809327" class="anchor"><span id="_Toc377756454" class="anchor"><span id="_Toc377809328" class="anchor"><span id="_Ref366823782" class="anchor"><span id="_Ref373391323" class="anchor"><span id="_Ref377130528" class="anchor"><span id="_Toc380472905" class="anchor"></span></span></span></span></span></span></span></span></span></span></span></span>Migrating Projects

#### Compatibility between different IB versions

Note that you can open all projects saved with a certain version of the IB in a higher version of the tool – but it is not possible the other way around: A project that was saved in a certain version of the IB cannot be opened with a lower release version anymore.

For migrating an IB project to a higher version the project just has to be saved (“generate and save”) within the higher version environment.

#### Current Version

The current version can be checked in the menu “Help” with the menu entry “About” (see Figure 20).

| ![](images/media/image34.png)                                                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361569167" class="anchor"><span id="_Toc380472981" class="anchor"></span></span>Figure 20. About Dialog of the IB |

<span id="_Toc380472906" class="anchor"><span id="_Ref377809736" class="anchor"></span></span>First Start of the IB
-------------------------------------------------------------------------------------------------------------------

This section describes start elements within the IB. First, how to start the IB environment (see II.2.1), second, how to create, open, save or close a project (see II.2.2). In section II.2.3 the graphical user interface of the IB is introduced in detail.

### <span id="_Toc377756457" class="anchor"><span id="_Toc377809331" class="anchor"><span id="_Ref367976634" class="anchor"><span id="_Toc380472907" class="anchor"></span></span></span></span>Start an Instance 

For starting the IB double-click on the file “cba-itembuilder.exe” within the installation directory (see II.1.3) or on the respective desktop icon. It is important that only one instance of the IB can be opened at the same time.

| ![](images/media/image35.png)                                                                                                  |
|--------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361243031" class="anchor"><span id="_Toc380472982" class="anchor"></span></span>Figure 21. Main Window of the IB |

The main window of the IB (see Figure 21) consists of at least two areas: On the left side the “Project View” is located, in the middle-right part of the screen the edition can be done in the designer view.

### <span id="_Toc377756459" class="anchor"><span id="_Toc377809333" class="anchor"><span id="_Ref367976645" class="anchor"><span id="_Toc380472908" class="anchor"></span></span></span></span>Open, Preview, Save and Close Projects

#### <span id="_Ref361241872" class="anchor"><span id="_Ref361569413" class="anchor"></span></span>Create a New Project

You can create a new project by either choosing *New Project* from the file menu entry or by clicking on the ‘brown-box-icon’ from the quick access toolbar. After selecting *New Project* you are asked to enter the project’s name (Figure 22).

> **Important Note:** The name of a project must neither contain white spaces and special characters nor start with a number. The project’s name is identical to its file name (see II.2.2.7).

#### Open a Project

To open an existing project you can choose *Open project* from the file menu or click the ‘blue-folder-icon’ from the quick access toolbar (Figure 22).

> **Important Note 1**: You can open only one project at the same time.
>
> **Important Note 2:** Depending on the project’s size opening can take a few seconds.

| A                                                                                                                                                                                     |     | B   |     |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|-----|-----|
| <span id="_Ref367894183" class="anchor"><span id="_Toc380472983" class="anchor"></span></span>Figure 22. Menu Entries and Icons for Creating a New Project or Opening an Existing One |

#### Preview a Project

In the designer view the different components of pages can be added and arranged. However, the designer view does not show how the page will look like at runtime. To see a preview of a page, a specific task or the complete project you can use the preview functionality.

There are different ways to preview the complete project. You can either use the menu button “Preview project” (see the icon in the part A of Figure 23), use the entry in the menu “Project” of the menu bar (see part B of Figure 23), use the context menu available by right-clicking on the project’s name in the “Project View” (see part C of Figure 23), or open the preview of a single page by right-clicking on the page’s name in the “Project View” (see part D of Figure 23).

The options A-C will open a dialog in which the scope for the preview can be selected (see **Fehler! Verweisquelle konnte nicht gefunden werden.**). If tasks had been defined in the project (see section II.4.1), a task can be selected to be previewed. Otherwise, the whole project can be previewed starting with the first page of the project. Finally, each page can be previewed separately by choosing “Page”. This is equivalent to option D in Figure 23).

| A                                                                                                                                    | ![](images/media/image38.png) | B   | ![](images/media/image39.png) |
|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|-----|-------------------------------|
| C                                                                                                                                    | ![](images/media/image40.png) | D   | ![](images/media/image41.png) |
| <span id="_Ref361246766" class="anchor"><span id="_Toc380472984" class="anchor"></span></span>Figure 23. Preview a Project or a Page |

| ![](images/media/image42.png)                                           |
|-------------------------------------------------------------------------|
| <span id="_Toc380472985" class="anchor"></span>Figure 24. Preview Scope |

The preview automatically starts the portable firefox, which is included as browser in the IB installation, and shows the selected task, page or project.

> **Important Note 1**: Close the preview before switching back the IB: Once the preview is requested the IB will generate the necessary code to show a preview of the task, item or page in the browser. The generated code will be outdated as soon as you change anything in the underlying project file. To avoid any confusion, use only one preview at a time and always close the preview before switching back to your project.
>
> **Important Note 2**: Check the specified item size: The preview is always generated for the item size specified in the global preferences (see section II.2.2.4). If the item is not previewed as expected and, for instance, scroll bars are appearing although there is enough space to display the whole item make sure that you specified the correct item size in the preferences of the IB.
>
> **Important Note 3**: It can sometimes happen that the preview just displays a white window. In that case it helps to close IB and re-open it.

#### <span id="_Ref361329299" class="anchor"><span id="_Ref361584074" class="anchor"></span></span>Item Display Size for Preview

IB items are designed according to a fixed item size. Therefore, before you preview an item, you have to define the size available for this item. The item size can be configured in the dialog “Preferences”, which can be found in the menu “Utilities” under the menu entry “Open preferences”. To change the item size, select the element “CBA Item Size” on the left and adjust height and width of the item in pixels (Figure 25).

| ![](images/media/image43.png)                                                                                          |
|------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368399000" class="anchor"><span id="_Toc380472986" class="anchor"></span></span>Figure 25. CBA Item Size |

> **Important Note 1**: The item size is different from the effective size of an item. The item size is defined in the dialog “Preferences” (see Figure 25); the effective item size results from the size of the frame (see II.3.1.2), added to a page as the root container. Both sizes are not perfectly in line with each other, because the item is located at the coordinates (X=1, Y=1) in the display area. Therefore, if you want to use the full item size without scrollbars, the size of the frame should be two pixels smaller than the item size defined in the preferences.
>
> **Important Note 2:** The arrangement of height and width input fields in the dialog *preferences* might be unfamiliar. If the size of your item is not correctly presented in the preview, check the arrangement of your height and width parameter inputs at first.

#### Save a Project

You can save projects by opening the menu item “Project” in the menu bar or by using the ‘blue-arrow-icons’. If a project is saved (or if the option “Save As” is selected) for the first time, a directory on your computer must be specified where the project file should be stored. The name of the ZIP-file represents the project name that was used when the project was created.

To save changes in an existing project you should usually use “Generate and Save”, either from the menu bar or from the menu buttons. “Generate and Save” differs from “Save” and “Save As” in the following way: “Generate and Save” generates the code necessary to run (see I.1.1) or preview (see II.2.2.3) the item while “Save” and “Save as” only stores all information relevant for a later code generation in the project file. However, instead of generating new code the code used for the last preview of the project is included in the project file, meaning that none of the changes you made after the last preview of the project will be available when using the item (as saved) in a test.

> **Important Note 1**: To be on the safe side, please make sure to always use “Generate and Save” when you want to save your changes.
>
> **Important Note 2:** Do not save your IB project within the IB path structure where you have installed it. Otherwise, problems can occur in item implementation.

#### Close a Project

To close an opened project you can choose *Close project* from the file menu or click the ‘x-icon’ from the quick access toolbar (see Figure 26).

|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref373390635" class="anchor"><span id="_Toc380472987" class="anchor"></span></span>Figure 26. Menu Entry and Icon for Closing an Opened Project |

#### Renaming an Existing Project

If you want to rename a project you need to open it in the IB and use the “Save as” option to save it under a different name.

> **Very Important Note:** Do not rename your project by just changing the name of the ZIP-file on your computer without opening it in the IB. If you rename a project file in the file explorer, the project will be destroyed and cannot be used any longer with the IB.
>
> **Explanation:** The IB saves projects as ZIP-files. The files contain the item specification, settings, resources (e.g., graphics) and templates used by the project. By using “Save as” and choosing a different name, the IB renames the project as well as all corresponding files and resources within the ZIP-archive. Just renaming the ZIP-file is therefore incomplete.

#### Global Properties / Project Settings 

Various project settings (see the build-in help of the IB for a description**Fehler! Verweisquelle konnte nicht gefunden werden.**) are editable in the global properties dialog. To open the global settings dialog right click on the project name in the project view and select the entry “Global Properties” from the context menu. The dialog “Project Settings” opens (Figure 27). Note that changes in the global properties are specific for each project.

| ![](images/media/image45.png)                                                                                                    |
|----------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368406033" class="anchor"><span id="_Toc380472988" class="anchor"></span></span>Figure 27. Global project settings |

### <span id="_Toc377756461" class="anchor"><span id="_Toc377809335" class="anchor"><span id="_Ref367976662" class="anchor"><span id="_Ref361329220" class="anchor"><span id="_Toc380472909" class="anchor"></span></span></span></span></span>Graphical User Interface 

In the following the elements and functions of the IB graphical user interface (GUI) are explained. A general overview of the main window (II.2.3.1) is followed by details on the menu bar (II.2.3.2). The sections guide through to the IB User Interface from left to right, starting at the Project View (II.2.3.3), to the Drawing Area (II.2.3.4), the Palette (II.2.3.5) to the Properties View (II.2.3.6). Finally, the function and settings of IB rulers and grids are explained (II.2.3.7).

#### Overview of the main window

The main window of the IB consists of three areas:

On the left side the Project View is located. The Project View provides an overview of the pages within the project. Use the Project View to open, save, rename etc. of your project.

Editing pages is done in the middle of the screen. You can open more than one page for editing. In case you have opened more than one page you can select a single page by clicking on the tabs above.

The Palette and the Properties View are located on the right side. The Palette holds tools like TextFields and Buttons. You can use these elements to design your pages. The Properties Views lists the properties of a selected element.

The IB also provides other views, e.g. Component View, Value Maps Editor and Task Editor that are described in separate sections in more detail (see specification in Figure 28).

| ![](images/media/image46.png)                                                                                                                                                                     |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368303695" class="anchor"><span id="_Toc354128273" class="anchor"><span id="_Toc380472989" class="anchor"></span></span></span>Figure 28. Central Elements of the IB User Interface |

#### <span id="_Ref368303371" class="anchor"><span id="_Ref369871202" class="anchor"></span></span>Menu Bar and Menu Buttons

The menu bar in the upper left of the IB interface contains all general functions. The menu buttons below provides shortcuts for frequently used functions from the menu bar (Figure 29).

| ![](images/media/image47.png)                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369848193" class="anchor"><span id="_Toc380472990" class="anchor"></span></span>Figure 29. Menu Bar and Menu Buttons |

<span id="_Ref368463785" class="anchor"></span>In the following, Table 2 gives an overview about the entries in the menu bar,

Table 3 lists the menu buttons and describes their function.

<span id="_Ref373390699" class="anchor"></span>Table 2: Entries of the Menu Bar

| **Menu bar entry** | **Description**                                                                                                                                                                                                 |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| File               |                                                                                                                                                                                                                 |
|                    | Creating, opening, saving, and closing a project (see II.2.2).                                                                                                                                                  |
|                    | Ends the IB.                                                                                                                                                                                                    |
|                    |                                                                                                                                                                                                                 |
|                    | Undo cancels the former step. Redo cancels Undo.                                                                                                                                                                |
|                    | Does not work yet. In some cases the duplicate-function might work (see II.2.3.4).                                                                                                                              |
|                    | Only works for text copied externally from the IB.                                                                                                                                                              |
|                    | Selects all design elements. If a container is already selected, the container itself and included elements are selected (see II.3.1.5).                                                                        |
|                    | Appears only when a design element is selected (see II.3.1.5).                                                                                                                                                  |
|                    |                                                                                                                                                                                                                 |
|                    | Previews a project (see II.2.2.3).                                                                                                                                                                              |
|                    | Uses template function for generating pages (see II.3.6).                                                                                                                                                       |
|                    | Uses OLT functions for item translation (see II.6.5).                                                                                                                                                           |
|                    | Opens editors for viewing and editing text entries, e.g., names, texts, user defined IDs.                                                                                                                       |
|                    | Opens several editors (see Resources: II.3.3, Tasks: II.4.1, Value Maps: 0, or FSM: II.5).                                                                                                                      |
|                    |                                                                                                                                                                                                                 |
|                    | Opens the Template Browser (see II.3.6).                                                                                                                                                                        |
|                    |                                                                                                                                                                                                                 |
|                    | Opens the XLIFF Editor for item translation (see II.6.5).                                                                                                                                                       |
|                    | Opens preference settings for item translation (see II.6.5), item display size (see II.2.2.4) and rulers/grid settings (see II.2.3.7). Note that changes in the preferences remain until you change them again. |
|                    |                                                                                                                                                                                                                 |
|                    | Opens internal help files of the IB.                                                                                                                                                                            |
|                    | Opens the IB Reference.                                                                                                                                                                                         |
|                    | Doesnot work yet. Please contact the TBA group for an update (see I.3).                                                                                                                                         |

<span id="_Ref370716726" class="anchor"></span>

Table 3: Menu Buttons

| **Menu Buttons**              | **Description**                    |
|-------------------------------|------------------------------------|
| ![](images/media/image48.png) | Create new page from page template |
| ![](images/media/image49.png) | New project                        |
| ![](images/media/image50.png) | Open project                       |
| ![](images/media/image51.png) | Save project                       |
| ![](images/media/image52.png) | Save project as                    |
| ![](images/media/image53.png) | Generate and save project          |
| ![](images/media/image54.png) | Preview project                    |
| ![](images/media/image55.png) | Open XLIFF editor                  |
| ![](images/media/image56.png) | Close project                      |
| ![](images/media/image57.png) | Browse resources                   |
| ![](images/media/image58.png) | Browse Tasks                       |
| ![](images/media/image59.png) | Browse Value Maps                  |
| ![](images/media/image60.png) | Edit State Machine                 |
| ![](images/media/image61.png) | Edit State Chart                   |

#### <span id="_Ref368303379" class="anchor"><span id="_Ref368465632" class="anchor"><span id="_Ref361590333" class="anchor"></span></span></span>Project View

One of the most important parts of the graphical user interface is the Project View. It lists all pages in a project. The root element of the Project View is the project name. Child nodes in the list correspond to pages in the project.

From the Project View you can access two important context menues. If you right-click on the root element (i.e., on the project name), the context menu for the project is opened (see Figure 30). When right-clicking on a child element (i.e., a page) you open the context menu for this page (see Figure 31).

| ![](images/media/image62.png)                                                                                                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361590979" class="anchor"><span id="_Toc380472991" class="anchor"></span></span>Figure 30. Context Menu for the Current Project |

The first context menu entries add new pages of several types. Besides previewing the whole project you can also open the settings for global properties (see II.2.2.8) and global icons (see II.3.3.3), or several other editors (see Tasks: II.4.1, Value Maps: 0, or FSM: II.5) from project’s context menu.

| ![](images/media/image64.png)                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361591164" class="anchor"><span id="_Toc380472992" class="anchor"></span></span>Figure 31. Context Menu for a Selected Page |

To edit a page select “Open page” from its context menu. Alternatively, you can also double-click on a page as a shortcut to open its editor in the Drawing Area. The page context menu also contains “saving” and “previewing a single page” (see II.2.2). “Save page as template” and “Export page” are two functions for using a certain page as a template (see II.3.6). Last but not least, you can also rename or delete a page. Note that the page’s editor has to be closed for these two functions.

#### <span id="_Ref368303386" class="anchor"><span id="_Ref368463944" class="anchor"></span></span>The Drawing Area 

The Drawing Area provides space for editing pages in the middle of the screen. Switch between multiple editors (Figure 32) by selecting a tab. The Drawing Area is also used for other syntax editors (e.g., see Resources Browser: II.3.6, Hit and Miss Syntax: II.4.2, FSM: II.5, or syntax editor for Task Initialization: II.6.3)

| ![](images/media/image65.png)                                                                                                                         |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368470537" class="anchor"><span id="_Toc380472993" class="anchor"></span></span>Figure 32. Multiple Page Editors above the Drawing Area |

When you draw elements in page editors you can open their context menues by right-clicking on them (Figure 33). Menu entries vary depending on the selected element. The most important entries of this context menu are:

*Show Properties View*: Opens Properties View of the element.

*Link* \<another element\>: Links the element with another one (e.g., with pages for navigation, see II.3.5.3; with an images for design, see II.3.4.5; with events for FSM, see II.5.2)

*Add* \<element\>: Creates an element within a container (e.g., for ComboBoxes, Lists, Menus, Trees)

*Configure \<element\>*: Defines settings for a specific element (e.g., for Tables).

*Set* \<attributes\>: Defines attributes of selected elements.

*Edit – Duplicate*: Duplicates the selected element. Not always available.

*Delete from Model*: Deletes the selected element. You can also use Delete on PC keyboard.

|-----------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368470571" class="anchor"><span id="_Toc380472994" class="anchor"></span></span>Figure 33. Context Menu of Elements |

#### The Palette 

The Palette contains all design elements of the IB. To select an element you just have to click on the Palette entry (the chosen label will be highlighted) and then draw a rectangle in the drawing area.

Note that the elements in the palette follow a simple structure: In the first part all elements are listed, followed by anchors in the second part and containers in the third part.

You can hide and open the Palette by using the white triangle-button top-right in the drawing area and Palette, respectively (see Figure 34).

| ![](images/media/image67.png)                                                                                                       | ![](images/media/image68.png) |
|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <span id="_Ref368407645" class="anchor"><span id="_Toc380472995" class="anchor"></span></span>Figure 34. Show (or Hide) the Palette |

The palette can be customized. For this reason open the Palette’s context menu by right-clicking on the Palette list (not on the word “Palette”). Select the entry...

…“Layout”, to edit the display of the Palette elements.

…“Use Large Icons”, to augment the size of the Palette icons.

…“Customize…”, to adjust the name, description and visibility of each Palette element.

…“Settings...”, to adjust font, layout and closing settings.

#### <span id="_Ref368303403" class="anchor"><span id="_Ref368459725" class="anchor"></span></span>Property View

The Properties Views lists all attributes of a selected element. Open the properties by selecting the entry “Show Properties View” of an element’s context menu as shown in Figure 35.

> **Important Note:** It might occur that the Properties View displays nothing even if an element of the Drawing Area has been selected. In this case, close and re-open the Drawing Area.

| ![](images/media/image69.png)                                                                                                        |
|--------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361591653" class="anchor"><span id="_Toc380472996" class="anchor"></span></span>Figure 35. Opening the Properties View |

<span id="_Ref368464172" class="anchor"></span>You can edit the properties by clicking in the “Value Column” of a certain attribute. Some attributes require text input (part A of Figure 36), selecting an entry from a combo box (part B of Figure 36), or opening a text editor (part C of Figure 36).

| | A   |     | B   |     | C   |     |                                                                                       
 |-----|-----|-----|-----|-----|-----|                                                                                        |
|-----------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref372707493" class="anchor"><span id="_Toc380472997" class="anchor"></span></span>Figure 36. Editing Properties |

The Properties View can also be adjusted. The setting’s shortcuts are located at the upper right of the Properties View (Figure 37). Table 4 provides an overview about settings of the Properties View.

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368472170" class="anchor"><span id="_Ref368472167" class="anchor"><span id="_Toc380472998" class="anchor"></span></span></span>Figure 37. Settings for Properties View |

<span id="_Ref368473986" class="anchor"><span id="_Ref368473975" class="anchor"></span></span>Table 4: Suggested Settings for the IB Properties View

| **Setting**           | **Description**                                                                                                                   |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Show Categories       | Classifies the Properties by topic or arranges them in alphabetic order.                                                          |
|                       | Not in use. All properties always are shown.                                                                                      |
| Restore Default Value | Restores default, if properties were changed.                                                                                     |
|                       | Pins the Properties View of the current selected element.                                                                         |
| View Menu             | Contains width adjustment for Property and Value column (“Columns...”) and opens another Properties View (“New Properties View”). |

#### Settings for the Graphical User Interface

If you use the IB for the first time, you may set the grid and ruler feature. Rulers and grids are useful for aligning design elements, later you are probably working with location parameters (see II.2.3.6). First, a project has to be open (see II.2.2.1). Make sure the “Properties” window is visible (see II.2.3.3). If not, right click on the empty background of a page (outside the Frame) and select “Show Properties View”. We suggest adjusting the settings in the tab “Rulers & Grid” in the “Properties View” (see Figure 38 as given in Table 5). The IB will save these settings.

| ![](images/media/image74.png)                                                                                                                    |
|--------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361242452" class="anchor"><span id="_Toc380472999" class="anchor"></span></span>Figure 38. “Rulers & Grid” for the IB drawing area |

<span id="_Ref361242423" class="anchor"><span id="_Ref369777782" class="anchor"><span id="_Toc354128251" class="anchor"></span></span></span>Table 5: Suggested settings for the Drawing Area

| **Setting**      | **Description**                                                                |
|------------------|--------------------------------------------------------------------------------|
| Show Ruler       | If activated, rulers are displayed at the lateral edges of the drawing area.   |
|                  | If activated, a grid is placed over the drawing area.                          |
| Grid in Front    | If activated, the grid is placed over all design elements in the drawing area. |
|                  | Select the ruler’s unit out of inches, centimeters, and pixels.                |
| Grid Spacing: 10 | Defines the size of the grid.                                                  |
|                  | Defines the grid line color and style (solid, dashed, dotted, etc.).           |
|                  | Aligns elements to the grid (see left part A of Figure 39).                    |
| Snap to Shape    | Aligns elements to the other elements (see right part B of Figure 39).         |
| Restore Defaults | Sets all parameters back to default.                                           |

Figure 39 illustrates the “Rulers & Grid” settings “Snap to grid” and “Snap to Shape” (see Table 5).

| | A   |     | B   |     |                                                                                                                   
 |-----|-----|-----|-----|                                                                                                                    |
|---------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref372707679" class="anchor"><span id="_Toc380473000" class="anchor"></span></span>Figure 39. “Snap to Grid” and “Snap to Shape” |

Furthermore, in the tab “CBA Rulers and Grid” of the “Preferences” (select “Utilities” from the menu and open preferences) you can define if your rulers and grid setting should be applied for a single page or for all pages (Figure 40).

| ![](images/media/image77.png)                                                                                                                                            |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref368397474" class="anchor"><span id="_Toc380473001" class="anchor"></span></span>Figure 40. Preference Settings for “Rulers & Grid” for the IB Drawing Area |

<span id="_Ref372704212" class="anchor"><span id="_Toc380472910" class="anchor"><span id="_Ref377809775" class="anchor"></span></span></span>Generate Items with the IB
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

The following section describes how to use the IB for designing computerized items. The first part summarizes the basics by introducing Pages, Frames and Panels (II.3.1). Although the IB is primarily a graphical tool, some features require the use of syntax. An overview of these features and some advices on name printing are given in II.3.2. Because the IB is a tool for item building, it is not quite right to prepare single design elements, e.g., images or videos. Instead, the Resource Browser (II.3.3) can be used for importing and managing several external images, audio, and video files. Other (few) design features of the IB are described in II.3.4. Furthermore, the IB provides features for managing multiple pages and connecting them for navigation (II.3.5). For facilitating the work with the IB, features and functions of templates with which pages can be duplicated are introduced (II.3.6), and in the end some general remarks on item authoring workflow are given (II.3.7).

> **Tips for the beginning 1:** Do not miss to adjust the item size when you open and preview items developed by others (see Section II.2.2.4 for details).
>
> **Tips for the beginning 2:** Read the section “Things you might need to know …” for the current version of the IB.

### <span id="_Ref369859591" class="anchor"><span id="_Toc380472911" class="anchor"></span></span>Basics of IB Item Design

This section deals with the basics of how to use the IB for designing functional and appealing items. The section starts with a short overview about different page types (II.3.1.1). After choosing a certain page format a Frame and a Panel have to be prepared before you can actually design elements of an IB item. Functions and features of Frames and Panels are presented in section II.3.1.2. A more precise introduction regarding the necessity of Frames and Panels, or the so called ‘container principle’, follows in section 0. The component view helps to keep an overview over all containers and elements. Finally, some remarks are given on an additional design bar that appears when you design a page (II.3.1.5).

#### Pages

After you created a new project the next step to an IB item is to create pages. Pages contain all elements that shall be visible and available to the test takers. Therefore, they are essential for the layout of an IB item.

The IB knows several page types which are more or less suitable for specific item formats. Some pages make use of so called “Child Pages” that means pages can also be presented within other pages.

Table 6 gives a first overview about the different page types in the IB. Note that not all elements can be placed on pages of every type (see III.1 for details).

<span id="_Ref369856987" class="anchor"><span id="_Ref372707912" class="anchor"></span></span>Table 6: Short Description and Prototypical Layout of Different Page Types

| **Page**        | **Description**                                                                                                                                                                                                                                                                                              | **Prototypical Layout** |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| Simple Page     | This is the basic page type. It can be used to implement independent pages, combined by links or FSM, or implement dialogs or modal dialogs.                                                                                                                                                                 |                         |
|                 | Additional extra pages can be combined with all other page types. They remain visible during navigation between different pages and can be used, for instance, to implement a common instruction part for items with multiple pages.                                                                         |                         |
|                 | One page is used as the common frame for multiple (Web-) pages, rendered in a child area. They can be used, for instance, for simulated Browser environments.                                                                                                                                                |                         |
| Tab Folder Page | Tab Folder Pages simulate multi-tasking systems with multiple applications. The single applications are closable.                                                                                                                                                                                            |                         |
| Task Bar Page   | This page type is used to simulate multi-tasking systems with multiple applications running in parallel.                                                                                                                                                                                                     |                         |
| Micro DYN Page  | Micro DYN Pages refer to a special item format. In the model part a linear equation structure can be defined to connect several exogeneous and endogeneous variables. Test takers can explore this structure by interacting with a defined item scenario. Their progress is reported in the history section. |                         |

Note that different pages have different properties. Table 7 provides the most important information on navigation between different page types (first and second column), connection to child pages (third and fourth column), and visibility of the page (fifth column). For more details on implementation see III.1.

<span id="_Ref370131709" class="anchor"></span>Table 7: Connection and Navigation Features between different Page Types

| **Feature**     | **Can link to Simple Page** | **Can be linked from Simple Page** | **Can be connected with Child Page** | **Childs have to be ...**   | **Remains visible during navigation** |
|-----------------|-----------------------------|------------------------------------|--------------------------------------|-----------------------------|---------------------------------------|
| Simple Page     | x                           | x                                  |                                      |                             |                                       |
|                 |                             |                                    |                                      |                             | x                                     |
| Web Child Page  | x                           |                                    |                                      |                             |                                       |
|                 |                             | x                                  | x                                    | Web Child Pages             | only for navigation between childs    |
| Tab Folder Page | x                           | x                                  | x                                    | Simple Pages                | only for navigation between childs    |
| Task Bar Page   |                             | x                                  | x                                    | Simple or Web Browser Pages | only for navigation between childs    |
| Micro DYN Page  | x                           | x                                  |                                      |                             |                                       |

#### Frames and Panels

Each page has to consist of a frame (see green area in the *Drawing Area* of Figure 41) that can contain one or multiple panels (see yellow area in the drawing area of Figure 41). Frames are the basis for panels which in turn serve as basis for other design elements (see next section 0). The frame size of an IB item defines the size of its panel(s). If the panel size fits into the frame area, no scrollbars are shown in the preview. If the panel size is larger than the effective frame area size, scrollbars are displayed automatically (cf. II.2.2.4). To create a new page and add a Frame and a Panel to the page, follow the detailed instruction in the cookbook part of this manual (see III.1.1.1).

<span id="_Ref369862230" class="anchor"></span>Table 8: Names of Frame, Panel and Child Area Types of different Pages

| **Page**        | **Name of Frame Element** | **Name of Panel Element** | **Name of Child Area Element** |
|-----------------|---------------------------|---------------------------|--------------------------------|
| Simple Page     | Frame                     | Panel                     | -                              |
|                 | Frame                     | Panel                     | -                              |
| Web Child Page  | WebChildFrame             | Panel                     | -                              |
|                 | WebBrowserFrame           | WebBrowserToolbar         | WebChildArea                   |
| Tab Folder Page | TabFolderFrame            | TabFolderGroup            | ChildArea                      |
| Task Bar Page   | TaskbarFrame              | TaskBarGroup              | ChildArea                      |
| Micro DYN Page  | MicroDynFrame             | -                         | -                              |

|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361570144" class="anchor"><span id="_Toc380473002" class="anchor"></span></span>Figure 41. Frame and Panel in the Drawing Area of the IB |

> **Important Note:** MicroDYN Pages are excluded from creating a Panel. In this case, you create a Frame, right-click the new Frame and select “Configure MicroDyn Frame” from the context menu. A dialog opens with layout options to choose from.

#### Container vs. Elements

The IB works according to the ‘container principle’: All design elements are placed in a hierarchy to order them according to their properties and affilitation.

The frame is the most general container. It is necessary for each page to contain the panel (Figure 42). A Frame can also contain multiple panel elements. You can image the frame as a desk on which to put some sheets of paper, e.g., the panels, for item drawing.

Additional elements (Containers or Elements) can be added to a panel. However, each container only accepts specific elements as child. For instance, frames do not accept frames as child elements. When adding elements to the “Drawing Area”, elements can only be added to a container fitting to the element selected (Figure 43). Note that elements can also be new containers for elements lower in hierarchy. Finally, different page types accept only specific containers (see for instance II.3.1.2).

Note also that the location of an element (i.e., its coordinates in the properties) depends on the container. The coordinates of an element in the upper left edge of its container are always (0,0).

> **Example:** Frames contain one panel at least and panels need a frame as container, respectively.
>
> RadioButtons must be drawn in a RadioButtonGroup.
>
> CheckBoxes can be directly put inside a Panel.

| ![](images/media/image80.png)                                                                                                                      |
|----------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369869272" class="anchor"><span id="_Toc380473003" class="anchor"></span></span>Figure 42. Hierarchical Structure of Frame and Panel |

| ![](images/media/image80.png)                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369869386" class="anchor"><span id="_Toc380473004" class="anchor"></span></span>Figure 43. Additional Elements and Containers on a Panel |

#### <span id="_Ref368303555" class="anchor"><span id="_Ref374026790" class="anchor"></span></span>Component View 

The Component View offers an overview about all containers and elements in one IB project. It is available through the second tab in the “Project View” (Figure 44) and lists all elements of a selected page. Elements in lower hierarchy are indented. Following the element’s name the location coordinates are given in brackets.

| FrameAndPanel.zip | Resource Browser                                                                                                                                         |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image81.png)                                                                                                                                                |
| <span id="_Ref369870141" class="anchor"><span id="_Toc380473005" class="anchor"></span></span>Figure 44. Hierarchical List of Pages Elements in the Component View of the IB |

#### <span id="_Ref368463875" class="anchor"><span id="_Ref372706658" class="anchor"></span></span>Additional Remarks

When opening a page an extended menu bar appears for editing properties of design elements. Figure 45 shows the most important functions of this extended menu bar. Especially note the zoom function with which you can zoom in or out the drawing area in order to enlarge or limit your view of the elements within the drawing area.

| ![](images/media/image82.png)                                                                                                                   |
|-------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369871356" class="anchor"><span id="_Toc380473006" class="anchor"></span></span>Figure 45. Additional Menu Bar for Editing a Page |

> **Important Note:** There are several ways to adjust the layout properties of elements. You can use the above mentioned additional menu bar, the appearing menu entry “Diagram” (see II.2.3.2), the context menu of the element (by right-clicking the element), or the appearance tab in the element’s properties (see II.2.3.6).

### <span id="_Ref369859595" class="anchor"><span id="_Ref370138067" class="anchor"><span id="_Toc380472912" class="anchor"></span></span></span>Use of Additional Syntax 

Although the IB is primarily a graphical tool, some advanced features require the use of a very simple syntax. Syntax is comparable to natural language grammar. It defines how to “speak” to the IB to make clear what to do.

#### Overview of Syntax Types

Types of IB syntax are geared to common principles for all areas of application. But dependent of the intended use they slightly differ in their exact structure. Therefore, a detailed instruction is given in each corresponding section. The scope of application includes:

Scoring (for definition of “correct” and “false” responses to a task, see II.4)

Finite State Machines (for connecting states, variables and events, see II.5)

Conditional Links (for defining the circumstances in which certain linking occurs, see II.3.5.4)

Task Initialization (for starting a task under certain conditions, see II.6.3)

> **Important Note 1:** Conditional Links and Task Initialization share the same syntax principles. See II.6.3 for explanation on syntax.
>
> **Important Note 2:** You can make comments in your syntax by setting two slashes initially (i.e. // My Comment). This rule applies for the remaining syntax line and can be used in e<span id="_Ref361417177" class="anchor"></span>ach editor for syntax writing.

#### Rules for Names and IDs

Names and IDs for various elements should be defined using the following rules:

only letters, digits and the underscores “\_” are allowed

the name must start with a letter (i.e., it is not allowed to use a digit or underscore as the first character)

the syntax is case sensitive (i.e., you have to pay attention to upper and lower case)

The restrictions can be expressed as regular expression (see II.6.2.2).

#### User-Defined IDs

User defined IDs are essential for implementing automatic scoring (see II.4) and detailed logging of data. Especially for the latter case, user defined IDs facilitate the interpretability of logged result and process data. User defined IDs are specified for each element in the properties view (Figure 46).

> **Important Note:** The IB itself also generates IDs for each element that was used when no user defined ID is determinated. The problems with IB generated IDs are that (1) they change each time you click “generate and save”, and (2) they look awful and are not intuitive for logging process data. We strongly recommend the usage of user defined IDs for each element (and a comprehensive documentation of the user defined IDs).

| CheckBoxExample.zip | Edit View                                                                                                       |
|---------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image83.png)                                                                                                         |
| <span id="_Ref368299312" class="anchor"><span id="_Toc380473007" class="anchor"></span></span>Figure 46. Example for User Defined IDs |

Since version 04.15.00 an editor is available for editing all user defined IDs from the main menu (see II.2.3.2). The editor lists all elements together with the assigned user defined ID. If no user defined IDs are assigned, the editor is empty (Figure 47, left). You have to tickmark the check box “Show empty fields” to view all elements that have not been assigned yet (Figure 47, middle). Double-click on an element entry to edit its user defined ID (Figure 47, right).

| ![](images/media/image84.png)                                                                                                        | ![](images/media/image85.png) | ![](images/media/image86.png) |
|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|-------------------------------|
| <span id="_Ref369867055" class="anchor"><span id="_Toc380473008" class="anchor"></span></span>Figure 47. Editor for User Defined IDs |

### <span id="_Ref367883366" class="anchor"><span id="_Ref369859601" class="anchor"><span id="_Toc380472913" class="anchor"></span></span></span>Resources

To create a visually appealing IB projects you should use the resources function of the IB. The IB does not provide many possibilities of designing elements but it allows uploading and using images, audio and video material. To use such files in the IB they have to be included in the project at first. All resources added to a project are saved within the project file.

#### Ressource Browser 

Resources can be managed with the build-in “Resource Browser”, which provides the following two options: A) Add a resource to the project file and B) delete a selected resource from the project file. The “Resource Browser” can be opened using either the entry “Browse Resources” of the “Project” menu or the following icon of the menu bar: ![](images/media/image87.png) . The “Resource Browser” will open in a new tab in the “Drawing Area” (see Figure 48).

<span id="_Ref361485991" class="anchor"></span>Table 9: File Formats of Media Resources in the IB

| **File Format** | **Extension ** | **Type**                        | **Comment**                       |
|-----------------|----------------|---------------------------------|-----------------------------------|
| GIF             | \*.gif         | Graphics Interchange Format     | bitmap image format               |
|                 | \*.png         | Portable Network Graphics       | raster graphics file format       |
| JPG             | \*.jpg         | Joint Photographic Expert Group | digital compression and coding    |
| Bitmap          | \*.bmp         |                                 | raster graphics image file Format |
| MP3             | \*.mp3         |                                 | encoding format for digital audio |
|                 | \*.flv         | Flash Video                     | container file format             |
| MP4             | \*.mp4         |                                 |                                   |
| WebM            | \*.webm        |                                 |                                   |
| Ogv             | \*.ogv         |                                 |                                   |

You can use the file formats listed in Table 9 for images, video or audio files that you want to use in an IB project. For audio- and video resources the built-in preview might start a “Save as”-dialog as soon as the corresponding entry is selected in the list of “Available resources”. To avoid this check the option “Skip Preview” (see Figure 48).

| ItemDesignExample.zip | Resource Browser                                                                                                            |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image88.png)                                                                                                                       |
| <span id="_Ref361486237" class="anchor"><span id="_Toc380473009" class="anchor"></span></span>Figure 48. The Resource Browser implemented in the IB |

> **Tip 1:** Delete unused resources to reduce the file size of a project. Many and large resources will slow down the processing of an IB project.
>
> **Tip 2:** Existing resources can be updated without re-assigning them to elements by deleting the resource with the resource browser and adding a resource with the identical name. Note however that “Generate and save” (see II.2.2.5) will be necessary to apply the update.
>
> **Tip 3:** An easier, but precarious way to “upload” resource material is to put your files directly into the project’s resource folder. Open the folder where you saved your IB project and double-click the zip-file. If you used the resource browser before, the folder “resources” is available. Copy all your images, audio, and video file in this folder and they will be available in your project. But be careful not to break down the project file.

#### Preparation of Resources

Before you upload resources in your project, you should prepare them to a suitable form. Images, for instance, should be prepared by image processing software. They should be, for instance, resized to the size you want to display them in your project. Indeed, the IB allows resizing an element such as an image field. But note that the linked resource is not rescaled, too. Thus, you should prepare your resources carefully before you use them in IB projects.

#### Global icons

For Web Browser Pages you can set global icons in the “Project Icon Settings”. First, you need to upload images you want to use (e.g. Back button, Home button). Then, you have to right-click the project’s name to select “Global icons” from the context menu. A Setting Dialog opens. Now you can chose an image for the icons by clicking on the presented combo boxes (Figure 49).

|------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369876718" class="anchor"><span id="_Toc380473010" class="anchor"></span></span>Figure 49. Project Icon Editor |

### <span id="_Toc377756467" class="anchor"><span id="_Toc377809341" class="anchor"><span id="_Ref367884197" class="anchor"><span id="_Toc380472914" class="anchor"><span id="_Ref369859605" class="anchor"></span></span></span></span></span>Design a Page 

For designing pages the IB provides specific design elements to display text on a page (II.3.4.1 and 0), and to show lines and rectangles (II.3.4.3). To dye a specific area within a page with a specific color, “Panels” can be used (see the gray “Panel” in Figure 50). To realize a more exciting design of pages images are used, either as elemente within a panel (ImageField, see II.3.4.4), or to format other elements (e.g., images used as background, see II.3.4.5). For interactive items Buttons can be used and designed to fit into the item layout (see II.3.4.6). Finally, the MediaPlayer for video and audio files is part of the layout of “Simple Pages” (see II.3.4.7).

| ItemDesignExample.zip | Edit View & Preview                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image90.png)                                                                                                                        |
| ![](images/media/image91.png)                                                                                                                        |
| <span id="_Ref361575307" class="anchor"><span id="_Toc380473011" class="anchor"></span></span>Figure 50. Examples of Basic Design Elements in the IB |

#### Text Fields

The IB provides a series of different text fields that serves slightly different functions: the Simple TextField, the HTMLTextField, and the TextField (see Figure 50).

The simplest text field you can select from the Palette is the SimpleTextField. It is a “light” version of a text field with less design options. You can configure the text by double-clicking the text field or by selecting “Edit text” in its context menu.

Note that SimpleTextFields can also serve as text input fields (see III.2.3), texts on web child pages (URL text, page description and tab text; see III.1.4), and result texts for compution with calculation engines (see **Fehler! Verweisquelle konnte nicht gefunden werden.**) (Figure 51). To assign a SimpleTextField to a specific function right-click the text field and select “Configure Input Source” from the Context menu.

| ![](images/media/image92.png)                                                                                                                        |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369881877" class="anchor"><span id="_Toc380473012" class="anchor"></span></span>Figure 51. Different Input Sources of SimpleTextFields |

The HTMLTextField provides more design options for texts. Double-click the HMTLTextField to edit text (see Figure 52). The HTML-Text editor opens that provides the following functions:

-   copy, cut and paste

-   font family, font size, font color

-   bold, italic, underlined and alignment (left-aligned, centred, right-aligned, and justified)

-   link (and unlink) text or text parts to other pages

-   listing text lines by numbering or using bullet points

-   tab stopps for paragraphs

-   superscript and subscript

-   rotate text

-   by tickmarking the check box “Selectable” the whole text field can be selected at runtime (see **Fehler! Verweisquelle konnte nicht gefunden werden.**)

After editing close the HMTL-Text editor by clicking the “Save and Close” button. The text appears now in the text field.

> **Important Note:** It can be problematic to have two blanks between words justified. Justify is represented in the editor as left aligned, it will only have an effect at runtime.
>
> The tool bar will show an empty font name and an empty font size if the selected text contains different fonts or sizes.

| ![](images/media/image93.png)                                                                                                 |
|-------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369884960" class="anchor"><span id="_Toc380473013" class="anchor"></span></span>Figure 52. HTMLTextField editor |

The TextField is similar to the HTMLTextField (see Figure 53). In contrast, it uses rich text field specifics with which highlightable text blocks can be defined at runtime. Therefore, the check box “Highlightable” has to be tickmarked. If you mark text or text parts now, you can add them as text blocks needed to score highlightable text (see III.2.7). Images can also be added in text fields. The text editor is closed by the “Save and Close” button.

| ![](images/media/image94.png)                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref370121460" class="anchor"><span id="_Toc380473014" class="anchor"></span></span>Figure 53. Text Editor for Rich Text |

> **Important Note:** It is preferable to use HTMLTextFields instead of rich TextFields which can cause problems in item presentation.

#### Links

Text, specifically used to link pages can be added to a panel as Link element (see Figure 50). The “Text” for the link as well as the “Mouse Over Text” can be defined in the core section of the link elements properties. Font family, font size, background color and border color are defined in the “Appearance”-section of the element’s properties. Links that have been already visited during the test administrations can be defined to be displayed in a different color (“Visited link color”). Note that general layout settings for links are defined in the global properties of a project (see II.2.2.8).

To specify the link target, you need to right-click the link element and select “Link Page” (see II.3.5.3 for details).

#### Lines & Rectangles

Simple lines and rectangles can be also added as design elements in the “Drawing Area” (see Figure 50). To use them select the entries Rectangle, LineHorizontal or LineVertical from the Palette and draw a rectangle in the “Drawing Area”.

Note that panels can be used to define backgrounds and Rectangles can be used to define borders (i.e., the background property of Rectangles and the border property of panels are ignored in the current version of the IB).

#### Image Fields 

Images are very important to generate items with a convincing layout. To include images in the item design, the ImageField element is available (see Figure 50 for an example). Before images can be used as design element of pages, the image file must be added to the project using the “Ressource Browser” (see II.3.3.1).

To use an image as a design element, add a so-called ImageField to the “Drawing Area” and specify the exact position (X- and Y-coordinates relative to the container). Once the ImageField is added right-click the element and select the entry “Link Image” of the context menu and select the image in the “Select Image” dialog (see Figure 54).

| ![](images/media/image95.png)                                                                                       |
|---------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361577786" class="anchor"><span id="_Toc380473015" class="anchor"></span></span>Figure 54. Link Image |

Note that the size of the ImageField is automatically adjusted to the size of the image (see 0).

#### <span id="_Ref361574926" class="anchor"><span id="_Ref368471079" class="anchor"></span></span>Images to Design Elements

In addition to displaying pictures with an ImageField, bitmap images can also be used to design other elements, such as the background of panels as images in TextFields, in Buttons, in Tables and for RadioButtons (see Figure 55).

To connect an image with an element, you need to right-click the element and select the entry “Link Image” of the context menu. Then, select the image in the “Select Image” dialog (see Figure 54). Note that you need to prepare the size of the image (see 0).

| ImageExamples.zip| Edit View and Preview                                                                                                                |
|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image96.png)                                                                                                                           |
| ![](images/media/image97.png)                                                                                                                           |
| <span id="_Ref361577987" class="anchor"><span id="_Toc380473016" class="anchor"></span></span>Figure 55. Examples for the Use of Images to Design Pages |

#### <span id="_Ref361578235" class="anchor"><span id="_Ref372374851" class="anchor"></span></span>Buttons and Toggle Buttons

Buttons can be added easily. The size of the button can either be set in the properties menu. The IB supports three kinds of buttons, summarized with their important properties in the following:

-   *Standard button “Text”* – This is the standard button you receive by using Button from the Palette. Properties: text, mouse-over text and background color (see first row, first column in Figure 57)

-   *Standard button “Image”* – Standard buttons “image” are specified as in the left part of Figure 56. Properties: image, mouse-over text and background color (see second row, first column in Figure 57)

-   *Image button* – Image buttons need images to be activated or de-activated. Further properties: pressed, mouse-over image and mouse-over as specified in the right part of Figure 56 (see third row, first column in Figure 57).

For all kinds of button, the same Button element is added to the “Drawing Area”. However, no image is linked to a standard button “Text”. A standard button “Image” has one linked image and the type “Standard button” is selected in the “Link image” dialog (see Figure 56). Finally, an image button is configured by selecting this type in the “Link image” dialog and by specifying different images for the possible states of a button:

-   Activated: (default) appearance when activated

-   Deactivated: appearance when de-activated

-   Pressed: appearance when pressed

-   Mouse-Over: appearance when hovering about an activated button

| ![](images/media/image98.png)                                                                                                  | ![](images/media/image99.png) |
|--------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| <span id="_Ref361582079" class="anchor"><span id="_Toc380473017" class="anchor"></span></span>Figure 56. Link Image to Buttons |

The distinction between standard buttons (“Text” or “Image”) and image buttons is also relevant with respect to the flexibility with which buttons can be used. Image buttons can be used, in contrast to standard buttons, as image maps (see III.2.6) and on Web browser pages (see III.1.4).

Buttons provide a property “Is Toggle” in the section “Misc”, which allows to define a button as a so-called “toggle button”. A toggle button has, similar to RadioButtons, two states, namely toggled and un-toggled. Buttons and image buttons can be configured as toggle buttons by setting the property “Is Toggle” to true. By default, i.e., when the property “Is Toggle” is not specified, the buttons are in non-toggle mode. The first click on a toggle button switches the button into the pressed position (toggled) until a second click releases the button to its initial state (un-toggled). The following examples, Figure 57, show the visual state of toggle buttons (second and third column) for a standard button “Text” (first row), a standard button “Image” (second row), and for an image button (third row). Note that the assigned images for standard buttons “Image” and image buttons are not shown in the design view of the IB, but are displayed at runtime (see preview II.2.2.3).

Furthermore, buttons can be used as links. For this, you need to specify the link target for a Button, right-click the link element and select “Link Page” (see II.3.5.2 for details). Besides linking to different pages within a project, buttons can also be associated with commands (see II.6.1) or with events when selected or de-selected (see II.5.2). Note that buttons can also be assigned to spinner elements (see **Fehler! Verweisquelle konnte nicht gefunden werden.**).

| ButtonExample.zip | Preview                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image100.png)                                                                                                                                            |
| <span id="_Ref361582905" class="anchor"><span id="_Toc380473018" class="anchor"></span></span>Figure 57. Standard Button (Text), Standard Button (Image) and Image Button |

#### Multimedia Player

The IB can also play multimedia files. For this, you just need to add “Audio” or “Video” from the palette and draw a rectangle that serves as area for audio or video playbacks (Figure 59, left side). Files can be linked by right-clicking the rectangle and select “Link Audio” or “Link Video” from the context menu. Now, the preview shows the files (Figure 59, right side). Note that you might deselect the Audio or Video element at first to receive the context menu with the linking option. Video files are embedded according to their screen size (see 0).

Audio and Video elements have some standard controls which can be adjusted in the properties. Audio elements contain play, pause, stop, and volume. Video elements contain play, pause, video duration, volume, and full screen option. You have the option to hide the controls, too. Alternatively, audio and video controls can be implemented by FSM what allows for more constraints in using the controls (see **Fehler! Verweisquelle konnte nicht gefunden werden.**).

| Video.zip | Edit View and Preview                                                                       |
|---------------------------------------------------------------------------------------------------------|
| ![](images/media/image101.png)                                                                          |
| <span id="_Toc380473019" class="anchor"></span>Figure 58. Implementing a video player within an IB item |

Note that it is also possible to include a media player in a stimulus for showing short films. The element MediaPlayer has to be selected from the Palette. A media player area is created in the editor by drawing a rectangular area in the editor (see **Fehler! Verweisquelle konnte nicht gefunden werden.**).

### <span id="_Ref367882642" class="anchor"><span id="_Toc380472915" class="anchor"><span id="_Ref369859610" class="anchor"></span></span></span>Use Multiple Pages 

The following section is about the connection of multiple pages and the possibilities of navigation between them. It starts with listing some scenarios in which specific linking is needed (II.3.5.1). In II.3.5.2 is shown how multiple pages can be sorted. Section II.3.5.3 introduces how to implement links between pages which is extended in section II.3.5.4 to linking under certain conditions.

#### Scenarios for Multiple Pages

To create complex, innovative items, the IB provides the functionality to implement items a) with multiple pages of different types and b) different options of connecting these pages for navigation. Multiple pages can be linked in sequential, hierarchical or hypertextual (cross-linked) order. For this purpose Item authors have to pre-decide how single pages should be connected to each other. Table 10 shows some selected scenarios.

<span id="_Ref370122540" class="anchor"></span>Table 10: Short Description and Examples for Flow Drafts of different Navigation Scenarios

| **Scenario** | **Description**                                                                                                                 | **Flow Draft**                 |
|--------------|---------------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| Units        | For implementing a unit structure, for instance, a stimulus page is linked with several item pages referring to the stimulus.   | ![](images/media/image103.png) |
|              | A tree structure is in particular applicable for simulating a web browser environment with continuative web texts.              | ![](images/media/image104.png) |
|              | User actions or events can also lead, for instance, to feedback pages. Implementing conditional links is here the first choice. |                                |

#### <span id="_Ref369880331" class="anchor"><span id="_Ref361578543" class="anchor"></span></span>Sorting of Pages in the Project View

Multiple pages can be ordered in the project view (see buttons in Figure 59).

| ![](images/media/image106.png)                                                                                                                |
|-----------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361590137" class="anchor"><span id="_Toc380473020" class="anchor"></span></span>Figure 59. Sorting of Pages in the Project View |

#### Link between Pages

To navigate between different pages within one IB project, Item authors need to implement links between the pages. Links can be embedded in many different basic input elements, i.e., TextFields, Buttons, ImageFields, Menus (see Figure 60).

| PageSelectionExample.zip | Edit View                                                                                                                       |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image107.png)                                                                                                                             |
| <span id="_Ref361640601" class="anchor"><span id="_Toc380473021" class="anchor"></span></span>Figure 60. Links can be Assigned to Different Input Elements |

Through links the current page can be changed because of an user interaction, i.e., when the test taker activates a link or an input element associated with a link (see Figure 61). For this, an element on the source page, i.e., the page from where to link, has to be right-clicked. Then, you need to select “Link page” from the context menu and the link editor opens. On the left side of the link editor the target page can be selected from the list below “Select page”. On the right side of the editor the color of the link, unvisited and visited, can be adjusted. The two buttons, “Edit Condition” and “Drop Condition”, add and remove conditions under which linking occurs (see next section II.3.5.4 for details).

> **Important Note:** You can unlink a connection just by clicking on the blue highlighted target page again. The blue highlight vanishes.

| ![](images/media/image108.png)![](images/media/image109.png)![](images/media/image110.png)                                 |
|----------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref370134569" class="anchor"><span id="_Toc380473022" class="anchor"></span></span>Figure 61. How to Link Pages |

Last but not least, pages can be also assigned to states in the FSM, and the current page is changed along with transition between states (see II.5.3.3).

#### <span id="_Ref361640413" class="anchor"><span id="_Ref370135537" class="anchor"></span></span>Conditional Links

Conditional links are links with an extended link mechanism. With it, link targets can be assigned statistically or dynamically with conditions incorporating other input elements, e.g., a button. According to the defined rule the link switches to a certain page at runtime (see Figure 62).

| ![](images/media/image111.png)                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref370137280" class="anchor"><span id="_Toc380473023" class="anchor"></span></span>Figure 62. Principle of Conditional Linking |

Conditional linking requires a basic form of syntax (see II.3.2 for an overview or II.6.4 for details on syntax). Conditions and their corresponding target pages are defined by syntax. If not defined, the default link applies. In the syntax, a single rule consists of three parts:

**{ TargetPage : Condition | Initialization }**

The *TargetPage* is the page to which to be linked, if the condition is fulfilled. It is always separated by a colon “:” from its corresponding condition. *Conditions* can be single active response elements (e.g., clicking a check box) or more complex attributes or expressions.

Simple conditional links only need a target page and a defined condition. Another optional part to extend the conditional link is to initialize tasks or events (e.g., start a scoring mechanism or activate a timer). To implement an *initialization* the condition has to be separated by a vertical bar “|” at first. Then, initialization parameters are set. See II.6.4 for more details on initialization.

The *curly brackets* always have to be set because they close the definition of a conditional link rule. Therefore, multiple conditional links to different pages can be defined within only one syntax editor. For more details on the syntax structure see II.6.4.

> **Important Note 1:** If multiple conditions in a conditional link are fulfilled, the first target page defined in the syntax editor is linked.
>
> **Important Note 2:** TargetPages have to linkable (see Table 7 in section II.3.1.1). Therefore, WebChildPages, for instance, cannot be TargetPages.

In the following example test takers have to decide which of eight alternatives fits a given pattern (see Figure 63). If they select the correct answer, test takers should receive the “correct”-feedback. If not, they should be lead to a “false”-feedback. The source page contains the item. Two target pages contain the feedback.

| ConditionalLinkExample.zip | Edit View                                                                                            |
|-----------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image112.png)                                                                                                    |
| <span id="_Ref370137273" class="anchor"><span id="_Toc380473024" class="anchor"></span></span>Figure 63. Conditional Link Example |

The link is implemented in the button. After a test taker clicked on the button, the condition is checked whether the correct answer was selected or not. For the definition of the conditional link, the default link has to be selected at first (Figure 64, left side). In the example, the “wrong”-feedback was selected as default page because every condition leads to the “wrong”-feedback, except in case of a correct answer. For defining the rule for conditional linking you need to open the syntax editor by clicking the button “Edit Condition”. After the condition has been inserted and saved (Figure 64, right side), the conditional link works.

| ![](images/media/image113.png)                                                                                                                                                         | ![](images/media/image114.png) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| <span id="_Ref370137039" class="anchor"><span id="_Toc380473025" class="anchor"></span></span>Figure 64. Default Link (left) and Condition (right) for the ConditionalLiniking Example |

### <span id="_Toc377756470" class="anchor"><span id="_Toc377809344" class="anchor"><span id="_Ref367883555" class="anchor"><span id="_Toc380472916" class="anchor"></span></span></span></span>Templates

Especially when creating very similar types of items, templates simplify working with the IB. The goal of templates is to avoid repetitive activities by creating identical pages. Defined parts or whole pages can therefore serve as templates. Pages just have to be saved as templates (see 0). Several templates are organized within the “Template Browser” (see II.3.6.2). Note that page creation proceeds slightly different when using templates (see II.3.6.3). Additionally pages can also be exported and imported which supports using templates with different IB versions and on different computers (see II.3.6.4).

> **Important Note 1**: All page types can be used as templates.
>
> **Important Note 2:** Templates do not copy User Defined IDs. Exporting and importing function do.

#### Save Page as Template

If you want to re-use a page as a template, you have to close all editors in the drawing area at first. Then, right-click the page you want to save. The context menu opens. Select “Save page as template” (Figure 65) to use your page as template.

|------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369778688" class="anchor"><span id="_Toc380473026" class="anchor"></span></span>Figure 65. Saving a page as template |

<span id="_Ref369779262" class="anchor"></span>Enter the name of your template (regard the advices from 0) and confirm with OK. A dialog informs you about the saving process (see Figure 66).

| ![](images/media/image116.png)                                                                                                              |
|---------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369796620" class="anchor"><span id="_Toc380473027" class="anchor"></span></span>Figure 66. Message of Correct Template Saving |

#### Template Browser

Templates are not stored within the project file but within the workspace of the local IB instance. That means, saved templates are only available within one IB version on one computer. To move templates from computer to computer or share templates between IB instances use the import and export function (see II.3.6.4).

The Template Browser gives an overview about all available templates (Figure 67). You can open the Template Browser with the menu entry “Browse templates” in the menu bar section “Templates” (see 0).

The window “Available templates” contains the names of all available templates within the IB. Click on the name of a template to select it. Now, a preview of the template appears in the window “Template Preview” and the buttons “Delete template” and “Export template...” are activated. Note, large templates slow down the processing time and might not be presented in the preview window. If you click the check box “Skip preview”, the preview of the template is passed. With the buttons “Import template...” and “Export template...” you can use the import and export function (see II.3.6.4). Use the “Delete template” button to remove a template from the Template Browser.

| ![](images/media/image117.png)                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369780006" class="anchor"><span id="_Toc380473028" class="anchor"></span></span>Figure 67. Template Browser in the IB |

#### Create Page from Template

For using a template to create a new page you have to select “New page from template” from the menu bar entry “Project” or click on the double-sheet icon (Figure 68).

|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| <span id="_Ref369803744" class="anchor"><span id="_Toc380473029" class="anchor"></span></span>Figure 68. Menu Bar Entry and Icon for Creating a Page from a Template |

The template browser opens with an additional line for the page name. Enter a page name (regarding the advices from 0) and select one of the available templates. Note, you have to tickmark the check box “Create as X-Page” on the upper right side if you want your new page to be an X-page. Click on the button “Create page”. Now you added a new page to your project that is identical to the chosen template.

|------------------------------------------------------------------------------------------------|
| <span id="_Toc380473030" class="anchor"></span>Figure 69. Create a New Page from Page Template |

#### Export and Import of Pages

The template browser can be used to export and import single pages instead of saving templates that are stored within the IB instance. When exporting a page the IB locally saves the page as zip-files, so you can store, copy or send these templates to other computers.

For exporting a page you have to close all editors at first. Rigth-click on the page you want to export and select “Export page” from the context menu, or use the “Export template...” button from the template browser (Figure 70).

|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| <span id="_Ref369801157" class="anchor"><span id="_Toc380473031" class="anchor"></span></span>Figure 70. Exporting Pages from Context Menu (left) or from Template Browser (right) |

Enter a name for theexported page (regarding the advices from 0) and confirm with “OK”. A dialog informs you about the saving process (see Figure 71).

| ![](images/media/image123.png)                                                                                                              |
|---------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref369801328" class="anchor"><span id="_Toc380473032" class="anchor"></span></span>Figure 71. Message of Correct Exporting Pages |

For importing templates you have to select “Import page” from the menu bar entry “Project" (Figure 72, left). Select and open the zip-file you want to import. The page with the corresponding name is directly imported in your project without using the template browser.

If you use the “Import templates...” button from the template browser (Figure 72, right), the page is imported as a template. Select the template from the template list, enter a page name (regarding the advices from 0) and confirm with the button “Create page”.

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| <span id="_Ref369802005" class="anchor"><span id="_Toc380473033" class="anchor"></span></span>Figure 72. Importing Pages from Menu Bar (left) or from Template Browser (right) |

> **Important Note 1**: It is not possible to import a page with an already existing page name.
>
> **Important Note 2:** You can also import whole IB projects. Therefore, all existing pages within the project serve as templates.
>
> **Important Note 3:** The import function also imports User defined IDs. Be careful when (renaming and) importing a page into one project repeatedly, because this may result in User Defined IDs wich are no loner unique.

### <span id="_Ref369859619" class="anchor"><span id="_Toc380472917" class="anchor"></span></span>General Remarks on the Item-Design-Workflow

Despite the undo and duplicate function building an item with the IB by not knowing beforehand how it shall look like and work can be very frustrating. Therefore, we strongly recommend making a rough sketch of the item you want to build (Figure 73 by using (A) paper-and-pencil and (B) painting software before starting working with the IB.

| | ![](images/media/image126.png) |     |                                                                                                   
 |--------------------------------|-----|                                                                                                    |
|--------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref372709906" class="anchor"><span id="_Toc380473034" class="anchor"></span></span>Figure 73. Developing a General Item Concept |

The following points shall also help to consider crucial aspects in planning your item concept:

1.  Define a general screen layout for your test before the development of single items (see II.2.2.4).

2.  Define a general structure of the test for clarifying possibilities of between-item navigation and feedback (see II.3.5).

3.  Define the content of the item and prepare needed materials (see II.3.3).

4.  Plan the layout and display of each item. If necessary, consider position and size of multiple pages (types).

5.  Plan the structure of each single item and consider dependencies, e.g., links, events.

6.  Think of what kind of item you want to create. Use appropriate response elements (see III.2).

7.  Think of what kind of response data you want to achieve. Define appropriate scoring rules (see II.4).

<span id="_Ref367883568" class="anchor"></span>

<span id="_Ref370130660" class="anchor"><span id="_Toc380472918" class="anchor"></span></span>Scoring
-----------------------------------------------------------------------------------------------------

Through automatic scoring the results of a single exercise or a test are determined, while the test is still running. Hence, automatic scoring provides many important advantages: Besides an immediate access to collected results and standardized scoring procedures it also allows for possible adaptive, branched, or multi-stage testing. The implementation of scoring is done inside the IB by defining an IB Task. Therefore, scoring is independent from final deployment options and can be tested during the process of item development.

IB Tasks fulfill two functions:

1.  They serve as *entry points* to the item. In order to include IB items in the final test delivery an access to the item is needed. Entry points are “portals” to IB projects. You do not have to define an entry point separately: IB Tasks automatically serve as entry points.

2.  IB Tasks are also the basis for the *implementation of automatic scoring* what is the subject of the following section.

The first part is about how to open and use the Task Editor for defining a task (see II.4.1). In the second part, basic principles of IB scoring implementation are introduced (see II.4.2). Section 3 provides lists of specific “scoring commands”. Exemplarly, two scoring implementations are illustrated in the fourth part (see II.4.4). Part five concludes with how to check the implemented scoring (see II.4.5).

When implementing automatic scoring, in general, we recommend the following four construction steps:

Prepare the scoring implementation, i.e., define and assign explicit IDs (see II.3.2.3).

Define a Task (see II.4.1).

Define hit and miss conditions (see II.4.2.1).

Test your scoring implementation (see II.4.5).

### <span id="_Toc377756474" class="anchor"><span id="_Toc377809348" class="anchor"><span id="_Ref368464056" class="anchor"><span id="_Ref368467759" class="anchor"><span id="_Ref368478870" class="anchor"><span id="_Ref369776192" class="anchor"><span id="_Ref370206363" class="anchor"><span id="_Ref370208091" class="anchor"><span id="_Ref370208491" class="anchor"><span id="_Toc380472919" class="anchor"></span></span></span></span></span></span></span></span></span></span>The Task Editor

For opening the Task Editor you can select *Browse Tasks* from the file menu or click the notebook-icon from the menu button toolbar (see Figure 74).

|-------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref373390876" class="anchor"><span id="_Toc380473035" class="anchor"></span></span>Figure 74. Icon for Opening the Task Editor |

When you first open the task editor, only the buttons “New” and “Layout settings” are available. The other buttons will be clickable when a task is already generated. Table 11 gives an overview about the buttons and their functions in the task editor.

<span id="_Ref368313394" class="anchor"></span>Table 11: Buttons of the Task Editor

| **Button(s)**      | **Description**                                                                                                                                                                                               |
|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| New                | Creates a new Task.                                                                                                                                                                                           |
| Delete             | Deletes an existing Task.                                                                                                                                                                                     |
| Open               | Opens an editor for Task initializations (see II.6.3).                                                                                                                                                        |
| Add Hit / Add Miss | Defines hits and misses. These buttons are needed for the definition of automatic scoring rules (see Scoring an Item II.4.2).                                                                                 |
| Preview            | Another option for previewing the constructed item (see II.2.2.3). It previews your project for a certain task.                                                                                               |
| Layout settings    | In the task browser you can also define presentation settings of a permanent visible page (so called X-Page, see III.1.3). Note, you have to activate these settings if you like to preview your used X-Page. |

When creating a new task you have to make some entries (see Figure 75):

Name your task at first. Task names are restricted to letters, digits and underscores, and must start with a letter (see II.3.2). The task name also serves as identification.

“MinHits” represents the minimum number of required hits to get an Item Score result (see next section II.4.2). The default value for MinHits is “1”. MinHits always have to be positive integers.

“Start page” shows which page will be presented when the task begins. Click on it and the table cell turns into a combo box including all eligible pages.

“Start X-Page” is an optional setting. If you have created X-Pages (see II.3.1.1 and III.1.3) assign them to a certain task. One X-Page can also be assigned to multiple tasks.

If all necessary entries are made correctly, a green tickmark between “MinHits” and “Start Page” appears after saving (see Figure 75).

| ![](images/media/image129.png)                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref373390940" class="anchor"><span id="_Ref373390911" class="anchor"><span id="_Toc380473036" class="anchor"></span></span></span>Figure 75. Entries for Definition of an IB Task |

> **Important Note:** You can define multiple tasks. But note, IB tasks are selfcontained. Means, multiple tasks can only run one by one, a task has to be completed at first, before the next can be started. Thus, the scoring of the first task is finsihed if the second is initiated. Repeated use of pages as start-pages for several tasks is possible.

### <span id="_Ref368315465" class="anchor"><span id="_Ref370139304" class="anchor"><span id="_Toc380472920" class="anchor"></span></span></span>Scoring an Item

An IB “Item Score” is defined as the evaluated result of a test taker‘s answer to an item. The item-author is responsible to define what this item exactly is (e.g., a single score or a bundle of specific user interactions). IB projects can contain more than one IB Task and, therefore, more than one Item Score (see II.4.1).

An IB Item Score includes a dichotomous result (“true” vs. “false”) and a so-called Credit Weight and Credit Class. The values of these three parameters depend on the definition of “Hits” and “Misses”. For the definition of conditions for hits and misses a simple syntax is needed which basics are described in II.4.2.2.

Besides the test taker’s result on the task’s question, Item Scores also contain further information about test taker’s performance on the IB Task. This further information is listed in Table 12. Item Score indicators are available in the resulting log-files after delivery, but can be also presented during item processing within one IB project (see II.6.3). Note, the Item Score elements in Table 12 and their corresponding total values are the same when only one IB Task is implemented within a project.

<span id="_Ref370206547" class="anchor"></span>Table 12: Overview about Other Elements of ItemScore

| **Item Score elements** | **Description**                                                                                                                                                       |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| reactionTime            | Time in seconds between Task-start and the first user interaction.                                                                                                    |
| reactionTimeTotal       | Cumulated time in seconds between Task-start and the first user interaction, when returning to a Task. This means that the previous time is restored by the snapshot. |
| execTime                | Time in seconds between Task-start and Task-end.                                                                                                                      |
| execTimeTotal           | Cumulated time in seconds between Task-start and Task-end of the same Task, when returning to a Task. This means that the previous time is restored by the snapshot.  |
| nbInteractions          | Number of user interactions between Task-start and Task-end.                                                                                                          |
| nbInteractionsTotal     | Cumulated number of user interactions between Task-start and Task-end, when returning to a Task. This means that the previous time is restored by the snapshot.       |

> **Important Note:** Timings are measured on the server application side (i.e., at runtime), not in the browser. In a delivery by notebooks, tablets or USB flash drive differences between real action time and action time at runtime can be ignored. Online delivery, though, might provide problems. Network latency and bandwidth of the used connection by test takers can bias time records.<span id="_Ref370212236" class="anchor"></span>

#### Hits and Misses

The Item Score consists of Hits and Misses (see Figure 76). A “Hit” is defined as correct answer to an IB Task or a part of an IB Task, respectively. A “Miss” is an incorrect answer. Note, it is up to the item-author to define what a correct or an incorrect answer is.

| ![](images/media/image130.png)                                                                                                         |
|----------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref373390964" class="anchor"><span id="_Toc380473037" class="anchor"></span></span>Figure 76. Composition of the Item Score |

> **Important Note 1**: Item Scores can contain more than one hit and more than one miss. Therefore, a more differentiated scoring is possible (e.g., partial credit scoring), although Item Score Result is a dichotomous variable.
>
> **Important Note 2:** Hits and misses also can contain multiple conditions to be fulfilled. The more conditions are included in their definition, the more complex the syntax will be (see II.4.2.2). To keep it simple, instead of defining multiple conditions within one hit or miss, you can also create more than one hit or miss, respectively.

**Defining Hits and Misses.** Hits and misses are created by clicking the button “Add Hit” or “Add Miss” (see II.4.1). Enter the name, weight and class of the hit or miss. To open the condition editor for hits and misses, respectively, click on the “Open”-button. (The used syntax for condition writing is explained in more detail in the next section II.4.2.2.) The “Delete”-button removes defined hits or misses. Note, the “Delete”-button removes your hits and misses without warning you again.

> **Important Note:** The name of a hit or miss is its identifier and, therefore, has to be unique in the project. Weights and Classes can double.

| ![](images/media/image131.png)![](images/media/image132.png)                                                                                         |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref373391009" class="anchor"><span id="_Toc380473038" class="anchor"></span></span>Figure 77. Defining Hits and Misses in the Task Editor |

**Item Score Result.** To be scorable an IB Task needs at least one implemented hit. Note, you can define the minimal needed hit number by the “MinHits” option in IB Task implementation (see II.4.1). If test takers (1) do not reach the required minimal hit number or (2) receive at least one miss, the result of the Item Score turns “false”. Likewise, if test takers (1) reach the required minimal hit number and (2) avoid receiving misses, the result of the item score turns to “true”.

> **Important Note:** A “false” Item Score Result does not necessarily indicate not reached Hit-conditions. The Item Score Result is also “false” when any performed user-interaction is not regarded by implemented scoring rules. That means, if you do not define anything, the Item Score Result always turns “false”. To avoid such “scoring gaps” you should check your scoring implementation (see II.4.5).

**Weights and Classes.** Weights are quantitative scores attributed to the hit or miss by the item-author. The default of Weights is “1”. Classes are qualitative labels of the hit or miss (e.g., “success”, “Code 1”, “0”). Note that class entries are not restricted to the IB naming rules (see 0). Numbers, spaces or mutated vowels can be used. Hit and miss conditions must not be connected to the same class.

Besides hits and misses, item scores also own weights and wlasses. The terminology between these elements is slightly different: Item scores possess a “Credit Weight” and a “Credit Class”; hits and misses have weights and classes. The weight and class of an item score do not need to be defined because they receive their information from the defined hits and misses.

Rules for attributing values and labels to credit weight and credit class of an item score:

-   If the item score result is “true”, credit weight and credit class are drawn from the received hits. If the item score result is “false”, they are drawn from the received misses.

-   The weight and the class of the received hit or miss with the highest weight is chosen as credit weight and credit class, respectively.

-   If the weights of multiple received hits or misses are equal, the attributes from the first defined hit or miss in the task browser is used (see Figure 77).

**Hit List and Miss List.** Additional to the final credit class and credit weight lists about receiving certain hits and misses are also returned to the test author. These hit and miss lists (means names, weights and classes of all received hits and misses), include the total number of received hits or misses as well as the total sum of their corresponding weights, too.

| ![](images/media/image133.png)                                                                                         |
|------------------------------------------------------------------------------------------------------------------------|
| <span id="_Toc380473039" class="anchor"></span>Figure 78. Elements of an IB Item Score (Scoring Viewer in the Preview) |

#### Basics of the Scoring Syntax

The syntax rules described in this section applies for the definition of hit and miss conditions for scoring purposes. Hit and miss conditions are logical expressions that consist of conditional literals and conditional operators.

Conditional literals are the objects of scoring rules. They usually are the identifier (i.e., user-defined IDs) of logical objects (e.g., IDs of RadioButtons), selection objects (e.g. IDs of ImageAreas), input objects (e.g. IDs of InputFields), or other IB elements (e.g. names of pages or events). Conditional literals can also summarize multiple identifiers as a set (see for an overview Table 15).

Conditional operators define what should be done with the conditional literals. They include simple conditions as well as comparisons.

-   Simple conditions involve a conditional literal combined with an operator

-   Comparisons confront two expressions. They are always surrounded by squared brackets to indicate unique propositions. Expressions can be compared against numbers (of integer type) or strings.

In Figure 79 an example for scoring syntax of a simple condition is illustrated. Note that conditional operators turn into purple if they are inserted correctly. All operators are listed in the IB Manual. The conditional literals, however, are black. The literals are named by the test author. They can either be defined in the properties of an element (see II.3.2.3), or in a Finite State Machine (see II.5), or by just naming elements (e.g. names of pages, trees or tree nodes).

| ![](images/media/image134.png)                                                                                                                         |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref371430832" class="anchor"><span id="_Toc380473040" class="anchor"></span></span>Figure 79. Example for Scoring Syntax (Simple Condition) |

> **Important Note:** Some scoring conditions can be very easy. In case of logical objects (e.g., user-defined IDs for check boxes) the literal serves also as an operator (see Figure 80). Thus, only the user-defined ID needs to be denoted in the syntax. If a test taker activates the element (in the following example it is a checkbox), he or she receives the defined hit or miss. But, usually literals and operators have to be combined to form a condition.

| ![](images/media/image135.png)                                                                                                                                                        |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref371430741" class="anchor"><span id="_Toc380473041" class="anchor"></span></span>Figure 80. Example for a Simple Logical Object that also Serves as Conditional Operator |

Table 13 contains the “Conditional Operators for Comparisons”. The operators are bold.

<span id="_Ref370231563" class="anchor"></span>Table 13: Conditional Operators of Comparisons

| **Conditional Operator**                   | **Description**                                                                                                                                                                                                |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **[** Expression **==** Expression **]**   
                                             
 **[** Expression **\<\>** Expression **]**  | Binary Operators for standard comparison of text and integer values. If the reference expression is a number, an integer comparison is done. If the reference expression is a string, string matching is done. |
| **[** Expression **\<** Expression **]**   
                                             
 **[** Expression **\>** Expression **]**    
                                             
 **[** Expression **\<=** Expression **]**   
                                             
 **[** Expression **\>=** Expression **]**   | Binary Operators for standard comparison of integer values. The reference expression has to be a number. Otherwise “false” is returned.                                                                        |

Figure 81 illustrates an example for a comparison. According to this piece of syntax a miss is given when a test taker skips an item, i.e., if the number of interactions with the project equals zero. Note, usually the second expression is an integer number or a character string (see II.6.2).

| ![](images/media/image136.png)                                                                                                    |
|-----------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref371430640" class="anchor"><span id="_Toc380473042" class="anchor"></span></span>Figure 81. Example for a Comparison |

> **Important Note 1**: You can use the shortcut “Ctrl/Strg + Space” in the syntax editor to get a list of all available conditional literals and conditional operators.
>
> **Important Note 2**: Two slashes set a comment in the syntax, e.g. // my comment.
>
> **Important Note 3**: The IB checks the syntax. If the syntax is syntactically incorrect, a red x-symbol appears on the left side of the editor and wrong statements are underlined in red. With a mouseover on the x-symbol an error message in a yellow box appears. Unfortunenately, the error message usually is not very comprehensive.

|----------------------------------------------------------------------------------------------|
| <span id="_Toc380473043" class="anchor"></span>Figure 82. Error Message for Incorrect Syntax |

Furthermore, several conditions can be combined or negated. Table 14 contains the corresponding operators. The presented conditional operators are bold.

<span id="_Ref370230358" class="anchor"></span>Table 14: Conditional Operators Affecting Complete Conditions

| **Conditional Operator**                  | **Description**                                                                                |
|-------------------------------------------|------------------------------------------------------------------------------------------------|
| **(** Condition1 **AND** Condition2 **)** | Logical “and”, i.e., a hit or miss is given when both Condition1 and Condition2 are fulfilled. |
| **(** Condition1 **OR** Condition2 **)**  | Logical “or”, .e., a hit or miss is given when Condition1 and/or Condition2 are fulfilled.     |
| **NOT** Condition                         | Logical negation of the Condition.                                                             |

> **Important Note:** Brackets are used for unique propositions of binary operators. If you want to score multiple conditions, you have to consider the bracketing, e.g., for three conditions:
>
> **( (** Condition1 **AND** Condition2 **)** **AND** Condition3 **)**

<span id="_Ref370212226" class="anchor"><span id="_Ref370231251" class="anchor"></span></span>

### Conditional Literals and Conditional Operators

Several conditional operators that can be used in the scoring syntax are listed and described in this section. The first part, 0, provides an overview of conditional literals for scoring an IB Task. The names of the conditional literals are used in the tables of the following parts, too. The following parts list common conditional operators (II.4.3.2) as well as operators for scoring FSM elements (II.4.3.3). The conditional operators are bold. Tables are separated by operators yielding simple conditions and operators that are used as expressions in comparisons.

> **Note 1:** An extension of operators for the scoring implementation of the MicroDYN model can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.
>
> **Note 2:** An extension of operators for the scoring implementation of the IB tree structures can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.

#### Conditional Literals

<span id="_Ref370228726" class="anchor"></span>Table 15: Conditional Literals for Scoring Implementation

| **Conditional Literal** | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ColPattern              | String (see RegExpr in this table) that refers to a certain column of a Tree node (see NodeIdPattern in this table).                                                                                                                                                                                                                                                                                                                                                                                                                   |
| EndoVariable            | User-defined ID of an EndogenousVariable in a MicroDYN model.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Event                   | Name of an event that serves as an identifier in FSM.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ExoVariable             | User-defined ID of an ExogenousVariable in a MicroDYN model.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| FSMVariable             | Name of a variable that serves as an identifier in FSM.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| InputObject             | User-defined ID of InputFields, SingleLineInputFields and TableCells.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Integer                 | Numbers of the integer type.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| LogicalObject           | User-defined ID of radio buttons, check boxes, combo boxes or list items.                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| NodeIdPattern           | String (see RegExpr in this table) that refers to a certain Tree node. The string usually starts with the Tree-ID. Underlines indicate a new node on another hierarchy-level. Positions of hierarchy-lower nodes are indicated by hyphens. Note that the position counter starts at 0. For instance, the string “t\_tn1\_tn11-0” refers to a document that lies at the first position in folder “tn11” that in turn lies in folder “tn1” in the Tree “t”. Note that you can shorten strings by using regular expressions (see II.6.2). |
| Page                    | Name of a page that serves as identifier.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| RegExpr                 | Strings. Note that strings must be double-quoted (see II.6.2). See section II.6.2 for advices on regular expressions.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| SelectionObject         | User-defined IDs of                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
                           highlightable TextsBlocks (in TextFields),                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
                           ImageAreas in ImageFields,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
                           editable HTMLTextFields in Panels or ImagesMaps,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
                           InputObjects,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
                           EndoVariable and ExoVariable.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| SetOfSelections         
                          
 > SetOfTextFields        
                          
 > SetOfEvents            
                          
 > SetOfStates            
                          
 > SetOfValues            
                          
 > SetOfNodeIdPatterns    
                          
 > SetOfEndoVariables     
                          
 > SetOfExoVariables      | Sets of Selections are combined SelectionObjects, e.g. *complete (*ComboBox1, ComboBox2, ComboBox3*)*. Sets of Selections can be specific for TextFields, FSM Events, FSM States, integer values, IDs of Tree-Node-Paths, EndogenousVariable, and ExogenousVariable.                                                                                                                                                                                                                                                                   |
| State                   | Name of a state that serves as identifier in FSM.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| TextField               | User-defined ID of TextFields, HMTLTextFields, and SimpleTextFields.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| TreeId                  | User-defined ID of a Tree.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

#### General Conditional Operators

Table 16: Overview about General Simple Conditions

| **Conditional Operator**                          | **Description**                                                                                                                                                                                                                                                            |
|---------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| LogicalObject                                     | Simple condition which only uses the user-defined ID of radio buttons, check boxes, combo boxes or list items as Conditional Operator.                                                                                                                                     |
| **bookmarked(** Page **)**                        | Evaluates “true” if the named page (only WebChildPages) is currently bookmarked (see III.1.4).                                                                                                                                                                             |
| **complete(** SetOfSelections **)**               | Evaluates “true” if all selections in SetOfSelections are completely selected.                                                                                                                                                                                             |
| **current\_page(** Page **)**                     | Evaluates “true” if the named page (only SimplePages or WebChildPages) corresponds to the currently displayed page.                                                                                                                                                        |
| **highlighted(** SetOfTextFields **)**            | Evaluates “true” if text lines are highlighted in at least one of the text fields.                                                                                                                                                                                         |
| **matches(** InputObject, RegExpr, Selector **)** | Evaluates “true” if test taker’s input (InputObject) matches a preliminary defined regular expression (RegExpr). “Selector” is an optional argument. It is available for the application of specific formulas (in TableCells) or HTML text formatings (in HTMLTextFields). |
| **partial(**SetOfSelections**)**                  | Evaluates “true” if all selections in SetOfSelections are partly selected.                                                                                                                                                                                                 |

Table 17: Overview about General Expressions

| **Conditional Operator**  | **Description**                                                                                                                                                                                                                                                                                                                                           |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Integer                   | Numbers of the integer type.                                                                                                                                                                                                                                                                                                                              |
| RegExpr                   | Strings. Note that strings must be double quoted (see II.6.2).                                                                                                                                                                                                                                                                                            |
| **user\_interactions() ** | Returns the number of user interactions within the current task. Its counter is reset to 0 at the beginning of each task. The number of user interactions can be used to differentiate “incorrect” from “missed” responses, i.e., if the number of user interactions is 0 or very low, then the test person has probably not tried to solve the exercise. |

#### FSM-specific Conditional Operators

Table 18: Overview about FSM-specific Simple Conditions

| **Conditional Operator**                                             | **Description**                                                                                                           |
|----------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| **is\_last\_state(**SetOfStates**)**                                 | Evaluates “true” if the last visited state at the task’s end corresponds to one state out of the selection.               |
| **raised\_all\_events(**SetOfEvents**)**                             | Evaluates “true” if all events of a given set have been raised during the current task.                                   |
| **raised\_all\_events\_in\_state(**State, SetOfEvents**)**           | Evaluates “true” if all events of a given set have been raised in a given state during the current task.                  |
| **variable\_in(**FSMVariable, SetOfValues**)**                       | Evaluates “true” if one variable-value of a given set corresponds to the value of a specified variable.                   |
| **visited\_all\_states(**SetOfStates**)**                            | Evaluates “true” if all states of a given set have been visited during the current task.                                  |
| **visited\_all\_values\_of\_variable(**FSMVariable, SetOfValues**)** | Evaluates “true” if all variable-values of a given set have been covered for a specific variable during the current task. |

Table 19: Overview about FSM-specific Expressions

| **Conditional Operator**                                            | **Description**                                                                                                |
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **raised\_ events() **                                              | Returns the number of raised events within the current task.                                                   |
| **raised\_nb\_events(**SetOfEvents**)**                             | Returns the number of events raised out of a selection of events within the current task.                      |
| **raised\_nb\_events\_in\_state(** State, SetOfEvents**)**          | Returns the number of events raised out of a selection of events within a given state during the current task. |
| **visited\_nb\_states(**SetOfStates**)**                            | Returns the number of states visited out of a selection of states within the current task.                     |
| **visited\_nb\_values\_of\_variable(**FSMVariable, SetOfValues**)** | Returns the number of covered variable-values out of a specific variable within the current task.              |

### <span id="_Ref368312553" class="anchor"><span id="_Toc380472922" class="anchor"><span id="_Ref367955916" class="anchor"></span></span></span>Examples

In the following, two examples of scoring implementation are illustrated. The first example will be very detailed in how to define a task and implement the scoring rules for a simple click response item. The latter example demonstrates scoring text inputs.

#### Example 1: Scoring a Check Box Item

In Figure 83 you can see the first item example in the IB design view. The task is to select all animals written in the check boxes on the right side of the item. To complete the task correctly, test takers have to select both check boxes “Janguar” and “Panda”. If not, they fail.

The first step is to score this item to assign user-defined IDs to each CheckBox (Figure 83). These IDs serve as identifiers for the check boxes and as conditional literals in the scoring syntax.

| ExampleCheckboxScoring.zip | Edit View                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image138.png)                                                                                                                                       |
| <span id="_Ref368322158" class="anchor"><span id="_Toc380473044" class="anchor"></span></span>Figure 83. Scoring Example Checkbox (Design View and User-Defined IDs) |

After determining the IDs, it is necessary to create a new task and to adjust the properties of the task (Name, MinHits, Start Page) as presented in Figure 84.

| ExampleCheckboxScoring.zip | Edit View                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image139.png)                                                                                                                      |
| <span id="_Ref368323079" class="anchor"><span id="_Toc380473045" class="anchor"></span></span>Figure 84. Scoring Example Checkbox (Task definition) |

Then, the more complex part follows: To decide whether test takers correctly answered the task or failed we have to define hit and miss conditions. For this, conditional expressions have to be inserted in the syntax editors of the hits and misses (Figure 86). In our example test takers should receive a hit for a correct item response, and a miss for an incorrect response. They should also receive a miss, if they skip the item without doing anything.

Let us start with the hit condition. Use the button “Add Hit” in the task editor to create a new hit (see Figure 87). Enter a name, a weight and a class as hit properties and open the hit syntax editor by clicking the “Open” button in the hit section of the task editor. A hit should be given when test takers selected both “Jaguar” and “Panda”. Thus, enter the corresponding user-defined IDs and connect them with an AND-operator. Do not forget the brackets (upper part of Figure 86).

|----------------------------------------------------------------------------------|
| <span id="_Toc380473046" class="anchor"></span>Figure 85. Adding Hits and Misses |

For defining the wrong-answer-miss use the button “Add Miss” to create a new miss. Define name, weight and class, and then open the miss syntax editor. Here, a wrong answer is indicated by not selecting both animals as described in the hit condition. Therefore, you can re-use the hit syntax and put it in front of it the not-operator (middle part of Figure 86).

Add another miss to the miss conditions. Define the miss properties and open the miss syntax editor. Skipping the item should be indicated by zero interactions with the item. Thus, use the operator *user\_interactions()* and set it at 0. Use also squared brackets to group the operator and the value (lower part of Figure 86).

**Last but not least:** Save the item, and see the green tickmarks indicating a successful scoring implementation, in case everything was defined correctly.

| ExampleCheckboxScoring.zip | Scoring Editor                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Hit                                                                                                                                                             |
| Miss 1                                                                                                                                                          |
| Miss 2                                                                                                                                                          |
| <span id="_Ref368323481" class="anchor"><span id="_Toc380473047" class="anchor"></span></span>Figure 86. Scoring Example Checkbox (Hit and two Miss Conditions) |

#### Example 2: Scoring a Text Response Item

A more complex syntax for hits and misses is required for the scoring of text input fields. To complete the task in Figure 87 correctly, test takers have to type in *hello world* in the grey-colored box on the right of the item. If not, they fail. The scoring steps basically equal the ones described in the former example: (1) Assign user-defined ID, (2) create a task, and (3) define hit and miss conditions.

For scoring simple text input we use the matches-operator for string matching. In regard of slightly differing answers (i.e., “Hello World” or “hello world”) we also add some regular expressions (see II.6.2).

The following list contains possible expressions for hits and misses:

hit condition: matches(inputtext,"\\\\s\*[Hh]ello [Ww]orld\\\\s\*")

miss condition 1: not matches(inputtext,"\\\\s\*[Hh]ello [Ww]orld\\\\s\*")

miss condition 2: [user\_interactions() == 0]

| ExampleTextScoring.zip | Edit View                                                                                                                                     |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image144.png)                                                                                                                                         |
| <span id="_Ref368327749" class="anchor"><span id="_Toc380473048" class="anchor"></span></span>Figure 87. Scoring Example Text Input (Design View and User-Defined IDs) |

### <span id="_Toc377756479" class="anchor"><span id="_Toc377809353" class="anchor"><span id="_Ref368307310" class="anchor"><span id="_Toc380472923" class="anchor"></span></span></span></span>Checking Scoring Implementation 

The IB provides the possibility to verify your scoring implementation. To use the IB scoring viewer option, preview a specific IB task you want to check. Then press **Ctrl/Strg + S** during the preview. The dialog “Scoring Viewer for Task [*TaskName*]” will appear. In the upper part of this dialog current general results are presented listing the overall score result, credit class, credit weight, execution time, reaction time, and number of interactions (for explanation see II.4.2). According to the hit and miss definitions in the task editor (left part of Figure 88), the lower part shows what hits and misses are fulfilled the moment the Scoring Viewer was opened (right part of Figure 88). Close the Scoring Viewer by pressing the white x in the upper right of the dialog box. You can (re-)open the Scoring Viewer in the preview whenever you want.

|                                                                                                                                      |     |     | ExampleCheckboxScoring.zip | Task Editor & Preview |
|--------------------------------------------------------------------------------------------------------------------------------------|-----|-----|----------------------------------------------------|
| A                                                                                                                                    |     | B   | ![](images/media/image146.png)                     |
| <span id="_Ref368301917" class="anchor"><span id="_Toc380473049" class="anchor"></span></span>Figure 88. Using the IB Scoring Viewer |

> **Important Note:** If the IB Scoring-Viewer does not work, check the configuration file “cba-itembuilder.ini” (see II.1.3).

<span id="_Ref361445509" class="anchor"><span id="_Toc380472924" class="anchor"></span></span>Finite State Machines (FSM)
-------------------------------------------------------------------------------------------------------------------------

Finite State Machines (FSM) allow varying the representation or behavior of certain elements by test takers or timed events in a very flexible way. With them IB items can be created to be more interactive. When implementing a FSM you need to know that they are composed of the four following parts: A) *Variables*, B) *Events*, C) *States* and D) *Rules* describing the transition between states. The specific combination of these four parts constitutes the FSM.

The FSM mechanism is complex and probably reveals completely not before it is tried in practice. However, FSM is a powerful tool to extend the functionalities in your items and it is worth to be engaged with. To illustrate the working principles of a FSM, imagine a UNO card game or any other card game with the possibility to play a “Reverse”-Card that switches the directions of playing from clockwise to counterclockwise, and vice versa. The *Variable* defines which player is in turn. It changes when the next player is in turn. In this case the change to the next player is an *Event*. Another *Event* in this example is that one player plays a reverse-card that changes the playing direction. The two playing directions, “clockwise” and “counterclockwise”, can be described by two *States* that reflect the current situation in the game and, thus, influences which player could be next. The *Rules* combine all *Variables*, *Events* and *States* to a common whole and state how they are related to each other. For instance, the *Rules* define that without playing a reverse-card (*Event*) the playing direction (*State*) cannot be changed, or that in counterclockwise direction (*State*) player 2 cannot follow player 1 (*Variable*), and so on.

Note that FSM’s are extremely versatile and, of course, not restricted to the use in the illustrated card game example.

In the following defining, combining and using *Variables* (see II.5.1), *Events* (see II.5.2), *States* (see II.5.3) and *Rules* (see II.5.4) is described in more detail. Some comments are also given about the graphical FSM editor (see II.5.5). In the end of this chapter two examples illustrate more complex Finite State Machines (see II.5.6). For further examples also check the Cookbook part on FSM (III.3).

> **Important Note 1:** *Scoring FSM*: The general scoring mechanism can be reused for evaluating the results of a task. Additional operators are provided (see section II.4.3.3).
>
> **Important Note 2:** *Simple FSM*: Some kinds of Finite State Machines can be used in simpler implementation forms. They can be used as palette elements (e.g., Slider, see **Fehler! Verweisquelle konnte nicht gefunden werden.**; Spinner, see **Fehler! Verweisquelle konnte nicht gefunden werden.**; Timer, see **Fehler! Verweisquelle konnte nicht gefunden werden.**) or element properties (e.g., Drag-and-Drop, see **Fehler! Verweisquelle konnte nicht gefunden werden.**). Of course, these mechanisms can be re-built or supplemented by using a “normal” FSM.
>
> **Important Note 3:** *FSM Task Initialization*: The FSM is automatically initialized when starting a task. In the task initialisation the values of timer events and assigned pages of start and end states can be modified. After the Finite State Machine has ended, however, no events are processed any more (see section II.6.4).

### <span id="_Ref370748608" class="anchor"><span id="_Toc380472925" class="anchor"></span></span>Variables

Variables are placeholders for numeric values used in the FSM of IB projects. They are identified by a specified name and defined on the project level, meaning that variables are valid across different pages within a project.

In the following, variables are introduced in more detail beginning with their definition (see II.5.1.1). Specific values of variables can be defined by naming them, too (see II.5.1.2). Section II.5.1.3 shows how variables can be linked to specific input elements to let the test taker actively change the variable’s value. Note that changes in variable values initiated by the FSM are the topic of a later section (see II.5.4). Variables can be also combined, for instance, with texts, images, audio- or video-files that are mapped to values (or value ranges) with the help of so-called “Value Maps”. Functioning and implementation of these combinations are explained in section II.5.1.4. In the end, possibilities of how to display variable values to the test taker are summarized in section II.5.1.5.

#### Definition of Variables

Variables are defined graphically in the “State Machine” by adding entries to the “Resource Set” (see Figure 89) using the context menu (right-click on “Machine”, select the category “New Child” and the entry “Variable”). Each variable has to have a unique name. Note that variable names are case sensitive. It is not allowed to use white spaces in variable names and a variable name must not start with a number (see 0 for general remarks on IDs in the IB). For keeping track we recommend to start the name by “V\_” indicating a FSM variable.

> **Important Note:** Note that in order to apply changes in the definition of variables (as well as states, events and rules; see below) the project has to be saved. Until the project is saved variables cannot be assigned to, for instance, VariableValueDisplays (see II.5.1.5) with the “Link Variables” method (i.e., in the dialog boxes “Set State Machine Variables”).

#### Named Variable Values

All variables have to consist of integers (i.e., only numbers and no decimals are allowed as variable values). However, in order to make the State Machine definition (see II.5.4) more readable, named variable values (i.e., labels for specific values of variables) can be defined by adding child nodes to variables in the “Resource Set” part of the “State Machine”. Add a child node by right-clicking the variable, and select the category “New Child” and the entry “Named Value”.

| ![](images/media/image147.png)                                                                                                                                               |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361346702" class="anchor"><span id="_Ref361347611" class="anchor"><span id="_Toc380473050" class="anchor"></span></span></span>Figure 89. Name Variable Values |

For each child of a variable in the “Resource Set” a name and a corresponding value can be defined as property (see, for instance, the named variable values V1 equals 865 and V2 equals 3123 in Figure 89).

####  Input Elements Associated with Variables

The IB provides different input elements which can be found on the palette. They are directly linked to variables of the FSM (see Table 20) that means the value entered with the help of the input element is directly used to change the value of a variable.

<span id="_Ref361348012" class="anchor"></span>Table 20: Input Elements Associate with Variables

| **Input Element** | **Description**                       |
|-------------------|---------------------------------------|
| ValueInput        | Text input for integer values.        |
|                   | Slider in a specified range.          |
| SpinnerValueInput | Button-based input of integer values. |
|                   |                                       |

Figure 90 shows applications of input elements. Note that you can see each input element on the left side in the figure and a number reflecting the current value of the corresponding variable on the right. The numbers on the right side are implemented by so called NumberValueDisplays which are described in more detail later (see II.5.1.5).

| ValueInputExample.zip | Preview                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image148.png)                                                                                                                                |
| <span id="_Ref371521383" class="anchor"><span id="_Toc380473051" class="anchor"></span></span>Figure 90. Example for Input Elements Associated with Variables |

A ValueInput (first row in Figure 90) allows entering any integer number by test takers. Once the number is entered, it is automatically assigned to the linked variable (i.e., the entered text value is transformed to an integer number and assigned to the corresponding variable even if the ValueInput has not yet lost the focus).

A ScaleVariableInput (second application in Figure 90) is a movable slider that can be moved to change the value of an associated variable. Sliders are configured to be horizontal or vertical and the resolution can be configured with the “increment” (i.e., the smallest unit between two slide control positions), and a “page increment” (i.e., the distance between two dashes on the scale), see Figure 91. Note that these characteristics have to be set in the ScaleVariableInput’s properties.

| ScaleVariableInputConfigurationExample.zip | Preview                                                                                                             |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image149.png)                                                                                                                                   |
| <span id="_Ref371521843" class="anchor"><span id="_Toc380473052" class="anchor"></span></span>Figure 91. Different Settings for the ScaleVariableInput - Element |

> **Tip:** Note that the range of a ScaleVariableInput is defined based on a ValueMap described in the next paragraph.

A SpinnerValueInput (third application in Figure 90) is a read-only inputfield used to show the current value of a variable as well as small up-and-down buttons which can be used to increase and decrease the variable.

Note that you always need to assign the variable to a specific input element. Right-click the input element and select “Link Variable” from the context menu (part A of Figure 92). Then select the variable you want to connect with the input element from the appearing dialog (part B of Figure 92).

|                                                                                                                             | ![](images/media/image151.png) |
|-----------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| <span id="_Ref371519693" class="anchor"><span id="_Toc380473053" class="anchor"></span></span>Figure 92. Linking a Variable |

<span id="_Ref361349997" class="anchor"></span>

#### Mapping Values to Texts or Multimedia Resources

In this section, the structure and the implementation of a value map are explained. Note that the next section (II.5.1.5) shows how value mapped resources are displayed in IB items.

Variables can be attributed to specific resources (texts, images, icons, audio- or video-files). This attribution is organized in so called *Value Maps*. A value map is used for the assignment of a specific resource to a certain number. If the value map itself is assigned to a FSM variable as well as to a specific display format, the resource-number assignment makes sure that the presentation of the resource changes according to the numeric changes in the corresponding FSM variable.

To implement or edit value maps, the value map table can be opened by using either the entry “Browse Value Maps” of the “Project” menu or the following icon of the menu bar: ![](images/media/image152.png). In Figure 93 the value maps editor is shown. To create a new value map click the button “Add” and name value maps regarding the naming rules (see 0). With the “Edit” button you can rename your value maps. The “Delete” button deletes a selected value map. Rearrange and sort multiple value maps by the “Up” and “Down” buttons.

| A                                                                                                                               | ![](images/media/image153.png) | B   | ![](images/media/image154.png) |
|---------------------------------------------------------------------------------------------------------------------------------|--------------------------------|-----|--------------------------------|
| <span id="_Ref373325816" class="anchor"><span id="_Toc380473054" class="anchor"></span></span>Figure 93. Example for Value Maps |

The lower part of the value maps editor, the “Value Maps Details”, lists the assignments of numbers or number intervals (“Guard”) to text-, image-, icon-, audio-, and video-resources. Note that multiple resources can be assigned to one value. Subject to the display format (see next section II.5.1.5) a specific resource is presented.

To create a new value map entry click the button “Add” below the detail list. A dialog opens asking for the value and the resource to be connected (see Figure 94). Text displays have to be written in the text line of this dialog. For adding images, icons, audio- o rvideo-files browse the available resources (see section II.3.3) and select one of the corresponding types. To assign a value to the selected resources click the “...” button behind the guard line.

| ![](images/media/image155.png)                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref373326435" class="anchor"><span id="_Toc380473055" class="anchor"></span></span>Figure 94. Edit a Value Map Entry in the IB |

The dialog “Value map entry” opens (see Figure 95). Select one of the provided entries “Default”, “Single Value”, or “Interval”. In case of “Default” an asterisk (\*) appears indicating the standard resource to be displayed if the connected FSM variable has not changed yet. In case of “Single Value” and “Interval” you have to add intger numbers behind the value entries. Note that integer ranges must not overlap. Otherwise resources cannot be asigned clearly.

| ![](images/media/image156.png)                                                                                                                                 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361349689" class="anchor"><span id="_Toc380473056" class="anchor"></span></span>Figure 95. Edit the Numeric Value of a Value Map Entry in the IB |

#### Displaying Values of Variables

The IB provides a specifc so called “Value Display” for each resource. Value displays are palette elements which show the FSM variable values and the corresponding resources, respectively.

From the palette “NumberValueDisplays”, "TextValueDisplays”, “ImageValueDisplays”, “IconValueDisplays”, “AudioValueDisplays”, and “VideoValueDisplays” can be choosen. According to the FSM variable value, the resource in the corresponding value map entry is presented. The example in Figure 96 shows the presentation of value displays in form of numbers, texts, and images. The left picture illustrates what resources are shown when the variable value is 1. The center one shows the representation of 2, and the third the representation of 3.

| ValueDisplayExample.zip | Preview                                                                                                                                                            |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image157.png)                                                                                                                                                               |
| <span id="_Ref373330053" class="anchor"><span id="_Ref368310851" class="anchor"><span id="_Toc380473057" class="anchor"></span></span></span>Figure 96. Example for Different Value Displays |

Note that you have to link a value display to a specific variable and a value map at first. This is necessary to clearly assign resources to specific FSM variables and value displays. Only numbers just need to be linked to variables because variables itself contain numeric values (part A in Figure 96).

To link a value display to a FSM variable right-click the value display to open its context menu. Select “Link Variable” and select the variable to be connected. Note that you have to define variables in the FSM editor at first, before you can link them.

To link a value display to a value map right-click the value display to open its context menu. Select “Link Value Map” and select the value map to be connected (part B in Figure 96). Note that you have to define at least the name of the value map at first before you can link it.

| ValueDisplayExample.zip | Preview                                                                  |
|----------------------------------------------------------------------------------------------------|
| A                                                                                                  |
| <span id="_Toc380473058" class="anchor"></span>Figure 97. Linking Variables and Linking Value Maps |

> **Important Note:** You can assign only one value map to multiple Value Display, but not vice versa (i.e., one value displays to be served by multiple value maps).

### <span id="_Toc377756483" class="anchor"><span id="_Toc377809357" class="anchor"><span id="_Ref361579203" class="anchor"><span id="_Ref361579208" class="anchor"><span id="_Toc380472926" class="anchor"></span></span></span></span></span>Events

The finite state machine of an IB project can be activated thtough user actions or in pre-specified time intervals. The terminology “Event” is used to label specific handlers, which can be used in the finite state machine. Events are defined in the FSM syntax. Input elements (e.g., RadioButtons, CheckBoxes) can be linked to defined events. Furthermore, timed events can be defined that are automatically triggered as long as the project is running.

#### Definition of Events

Events are defined in the window “State Machine Rules” of an FSM. The general structure of the syntax in the window “State Machine Rules” is as follows:

| **Events:** EventA, EventB 10,                                                          
                                                                                          
 EventC;                                                                                  | Keyword “**Events:**” followed by a comma-separated list of event names. The list must end with a ‘;’, but multiple lines are possible. |
|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **Rules:** ST\_Start -\> ST\_Page{true}                                                 
                                                                                          
 [...]                                                                                    | Keyword “**Rules:**” followed by different rules for the transition between states (see II.5.4)                                         |
| // Comment!                                                                             | Comments can be included in the syntax file. A comment line must start with ‘//’                                                        |
| <span id="_Toc380473059" class="anchor"></span>Figure 98. Syntax for the FSM Definition |

Event names are restricted to letters, digits and underscores, and have to start with a letter (see 0). For keeping track we recommend to start the name by “EV\_” indicating a FSM event. Note that the keyword “Events:” and “Rules:” are both necessary and each is only allowed once.

| EventExample.zip | Edit View                                                 |
|------------------------------------------------------------------------------|
| ![](images/media/image162.png)                                               |
| <span id="_Toc380473060" class="anchor"></span>Figure 99. Example for Events |

Once you entered an Eevent’s name in the “Event:” part of the “State Machine Rules”, you have defined this certain event. From now on the defined event is available in the “Set Raised Event” menu (left part of Figure 100) to connect it with any design element by right-clicking the element (right part of Figure 100). If the connected element is activated, the corresponding event is raised. For instance, in Figure 100 a click on the “RadioButton A” will raise the event “EV\_RadioButtonEvent”.

| EventExample.zip | Edit View                                                                                                    |
|---------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image163.png)                                                                                                  |
| <span id="_Ref371336066" class="anchor"><span id="_Toc380473061" class="anchor"></span></span>Figure 100. Setting Raised Events |

Events can be raised by a wide variety of IB elements (standard and image buttons, check boxes, radio buttons, combo box items, menu items, [single line]input fields, value displays as well as clicking image areas, images and image maps).

> **Important Note 1:** If buttons and image areas show a “toogle behavior”, they can be assigned to two different events optionally (one for pressing down and one for up).
>
> **Important Note 2:** Only buttons, combo box items as well as menu items can raise events and link to certain pages at the same time. If doing so, they raise the event at first and then switch to the linked page.

#### Definition of Timed Events

Events defined have to be triggered by linking them to input elements in an IB project as described in the previous section. By adding an integer number (as seconds) behind the definition of an event, timed events are defined, which are triggered automatically repeatedly after the specified number of seconds. For instance, ”**Events:** TimeEvent 10;” denotes that the Event “TimeEvent” is raised after ten seconds.

Note that the time interval specified in the syntax of an FSM might be updated by the task initialization (see II.6.4.1).

### <span id="_Toc377756485" class="anchor"><span id="_Toc377809359" class="anchor"><span id="_Ref370748619" class="anchor"><span id="_Toc380472927" class="anchor"></span></span></span></span>States

FSM states refer to present conditions while an IB item is running. Therefore, they can provide unique configurations of item settings or functionings that characterize one specific state. The charactistic of the states in the introductory example (the UNO card game), for instance, is their processing direction (clockwise vs. counterclockwise) that had consequences for variable changes.

States are organized in the State Machine editor. The hierarchical structure of the states is expressed by using a tree structure. This graphical editor is provided for the definition of states (see Figure 101):

| StateExample.zip | State Machine                                                                                                            |
|---------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image165.png)                                                                                                              |
| <span id="_Ref361443786" class="anchor"><span id="_Toc380473062" class="anchor"></span></span>Figure 101. Graphical Editor to Define States |

#### Definition of States 

To define states open “Edit State Machine” by using either the menu entry or the menu bar icon. Open the tree structure in the State Machine-editor. Right-click on the entry “Machine” and select “New Child” and “State” from the opening context menu. A new state with no name set appears (left part of Figure 102). Right-click on the new state and select “Configure State”. In the opening dialog you have to name the state and define its type at least (right part of Figure 102).

State are represented by a unique name, i.e., an identifier which is used only once in a project. For naming the state follow the rules described in section 0. For keeping track we recommend to start the name by “ST\_” indicating a FSM state.

States also have attributes, i.e., state types. They can be of the type “start”, “normal”, or “end”. Normal states are regular states. Start and end states indicate the beginning and the end of a FSM processing. Note that exactly one state must be defined as a “start” state, so that the FSM can be initiated. End states are rather optional, a FSM does not necessarily to be ended.

| ![](images/media/image166.png)                                                                                            | ![](images/media/image167.png) |
|---------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| <span id="_Ref373337703" class="anchor"><span id="_Toc380473063" class="anchor"></span></span>Figure 102. Defining States |

#### Nesting of States 

Typically, only one FSM can be processed at a time. However, to allow the use of “multiple” FSMs, states can have also child states that can be only called when their ‘parent’ state is actively processed. That means, states can be nested hierarchically (it is like a state machine within a state machine). Note that the parent state is also called composite state because it is decomposed into its children.

You can nest states in two different ways. Usually, child states are dependent to their parent and, therefore, can only be processed when the parent is running. However, if states should work independently, you need to define so called “regions” that are working independently of each other and can therefore be processed in parallel. You need regions when you create an IB project that, for instance, contains a calculator while a timer is running at the same time.

To define child states or regions, right-click the state that serves as the parent (see left part of Figure 103). Select “New Child” from the opening context menu and decide if you want to create a child (“State”) or a region (“Region”).

> **Important Note:** States of lower level hierarchy as well as regions have to contain at least one start state and one normal state to be initiated (see right part of Figure 103). If a child mechanism or region should be closed at item runtime, it should also contain an end state.

The name of the region itself is not needed for defining rules in State Machine Rules (see next section II.5.4). Note that regions can be synchronized by raising events, e.g., by adding the FSM operator *raise()* to the State Machine Rules.

| NavigateWithStatesInRegions.zip | State Machine                                                                            |
|----------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                            |
| <span id="_Ref373333789" class="anchor"><span id="_Toc380473064" class="anchor"></span></span>Figure 103. Defining Regions |

#### Assignment of Pages to States

Normal and end states can be also assigned to pages. If a state is changed into another, the test taker is lead to a new page which is connected with the state to change into. To assign pages to states open the State Machine editor and right-click the state you want to asign (left part of Figure 104). Select “Configure State” from its context menu and type in the page’s name you want to assign to that state in the corresponding input line (right part of Figure 104). Confirm with OK. If a state is called (as defined by State Machine Rules) the user-interface changes to the corresponding page without any additional linking implementation.

|                                                                                                                                         | ![](images/media/image171.png) |
|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| <span id="_Ref373332256" class="anchor"><span id="_Toc380473065" class="anchor"></span></span>Figure 104. Assigning Pages to FSM States |

### <span id="_Toc377756487" class="anchor"><span id="_Toc377809361" class="anchor"><span id="_Ref370748624" class="anchor"><span id="_Ref371441167" class="anchor"><span id="_Ref371442318" class="anchor"><span id="_Ref371442331" class="anchor"><span id="_Toc380472928" class="anchor"></span></span></span></span></span></span></span>Rules

In the following, the structure of FSM rules is explained. The section starts with the description of state transitions (see II.5.4.1). Conditions that have to be fulfilled to trigger a state transition, are treated in the second section (see II.5.4.2). At the end, actions that can happen due to state transition are listed (see II.5.4.3).

The processing rules of a FSM are defined in the *State Machine Rules* editor which also opens when you select *Edit State Machine* by either the menu entry or menu bar icon. In this part, variables, events and states are brought together and related to each other.

The FSM syntax in the *State* *Machine* Rules is structured in two sections (see Figure 105):

-   *Event Definition:* FSM syntax always starts with the Event Definition. This section is initialized by “Events:”. Event Definition lists all available FSM events. Differents events are separated by “,”. The section closes by “;” (see section II.5.2).

-   *Rules Definition:* In the second syntax part so called transition rules between states plus conditions are defined that trigger the state transition as well as consequences of the state condition. The rules section is always initiated by “Rules:”. An explicite closing is not necessary.

| FSMexample.zip | State Machine Diagram                                                                                           |
|----------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image172.png)                                                                                                   |
| <span id="_Ref373400871" class="anchor"><span id="_Toc380473066" class="anchor"></span></span>Figure 105. Example for FSM Syntax |

#### Transitions 

States in FSMs are changed via so-called transitions, i.e., fixed pre-defined rules. A transition is always specified as a pair of a) a source state and b) a target state. Note that a “start state” can never be used as target and that an “end state” can never be used as source. However, given “normal states” source and target states can refer to the same state as well as to different.

The syntax differentiates between several types of transition:

Table 21: Types of Transition

| **Type**            | **Syntax Form**                                                   |
|---------------------|-------------------------------------------------------------------|
| Start Transition    | START\_STATE -\> NORMAL\_STATE {EVENT:CONDITION|ACTION }          |
| External Transition | NORMAL\_STATE =\> NORMAL\_OR\_END\_STATE {EVENT:CONDITION|ACTION} |
| Internal Transition | NORMAL\_STATE internal {EVENT:CONDITION|ACTION}                   |
| Entry Actions       | NORMAL\_STATE entry {ACTION}                                      |
| Exit Actions        | NORMAL\_STATE exit {ACTION}                                       |

Note that START\_STATE refers to the name of the start state in a FSM, NORMAL\_STATE refers to the name of any normal state and NORMAL\_OR\_END\_STATE refers to the name of any state of the type “normal” or “end”.

The syntax differences between several transition types are obvious: An initial transition from a start into a normal state requires a simple arrow (“-\>”) whereas a regular (external) transition requires a double-arrow (“=\>”). Internal transitions, however, work only with the command “internal”. “Entry” and “Exit” denote specific actions that should be executed when a specific state is entered or left, respectively. Note that “Internal Transitions” do not trigger entry or exit actions.

State transitions can be specified by events, conditions and actions that are described in curly bracket behind a transition. Events, conditions and actions are optional parameters, i.e., brackets can also be empty when nothing has to be done explicitely.

Events and conditions specify when a state transition is actually executed. A new state is reached when a specific event (under certain conditions) occurs. Multiple events just have to be separated by “,”. An asterisk “\*”, however, represents all events. Conditions, in contrast, are logical expressions based on comparisons of variable values. In FSM, they are true by default. Note that for the usage of multiple conditions connecting operators and bracketing is needed. For more information on events and conditions see section II.5.2 as well as section II.5.4.2.

Actions are executed when a state transition occurs, i.e., if the corresponding condition ia evaluated as true. Like multiple events, multiple actions just have to be separated by “,”. Actions attached to state transition are described in section II.5.4.3 in more detail.

#### Conditions

Conditions are logical expressions based on comparisons of numeric values. FSM actions (see II.5.4.3) are executed if the condition is evaluated as true. Note that, in contrast to Scoring or Conditional Linking or Task Initializing, conditions in FSM are true by default. That means, actions are executed every time a state transition occurs if no explicit condition is set. For the definition of conditions in FSMs the following operators and connectors are available.

Table 22: Conditions in FSM Rules

| **Condition **                            | **Description**                                                                                                                                                                                                                                              |
|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **(** Condition1 **AND** Condition2 **)** | Logical “and”, i.e., defined state actions are processed when both Condition1 and Condition2 are fulfilled.                                                                                                                                                  |
| **(** Condition1 **OR** Condition2 **)**  | Logical “or”, i.e., defined state actions are processed when Condition1 and / or Condition2 are fulfilled.                                                                                                                                                   |
| **NOT** Condition                         | Logical negation of the Condition.                                                                                                                                                                                                                           |
| **isCurrentTask(** TaskID **)**           | Request of the currently executed IB Task. Condition gets true if the named task (“TaskID”) corresponds to the currently executed task.                                                                                                                      |
| **[** Comparison **]**                    | Comparisons contrast two expressions and compare them with each other. Usually, a number value or a character string is compared to a reference value (or reference character string). Note that all comparisions need to be surrounded by squared brackets. |

Table 23 summarizes available forms of comparisons for FSM conditions. Note that expressions in FSMs are numeric values.

<span id="_Ref373404286" class="anchor"></span>Table 23: Forms of Comparisons in FSM Rules

| **Conditional Operator**                   | **Description**                                                                                   |
|--------------------------------------------|---------------------------------------------------------------------------------------------------|
| **[** Expression **==** Expression **]**   
                                             
 **[** Expression **\<\>** Expression **]**  | Operators for standard comparison of integer values. The reference expression has to be a number. |
| **[** Expression **\<** Expression **]**   
                                             
 **[** Expression **\>** Expression **]**    
                                             
 **[** Expression **\<=** Expression **]**   
                                             
 **[** Expression **\>=** Expression **]**   | Operators for standard comparison of integer values. The reference expression has to be a number. |

In FSMs expressions refer to numeric values. In the following table, values are listed which serve as expressions in FSMs:

Table 24: Expressions in FSM Rules

| **Operator**                 | **Description**                                                                                                                                                                                                                                      |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Integer                      | Number of integer type.                                                                                                                                                                                                                              |
| Variable                     
                               
 Variable.NamedValue           | Returns the current value of a variable as expression. Note that if you have pre-defined named values, they can be called directly. In this case you set the variable’s names as well as the name of the named value separated by “.” as expression. |
| **ifthenelse(** Condition,   
                               
 ThenExpr, ElseExpr **)**      | The ifthenelse-syntax implements a functional operator which returns the result of the integer expression “ThenExpr”, if “Condition” evaluates to true, otherwise the result of the integer expression “ElseExpr”.                                   |
| Expression **+** Expression  
                               
 Expression **-** Expression   
                               
 Expression **\*** Expression  
                               
 Expression **/** Expression   
                               
 Expression **%** Expression   | Standard arithmetic operators: addition (+), subtraction (-), multiplication (\*), integer division (/), and modulus (%).                                                                                                                            |

> **Note:** An extension of operators to calculation engine settings can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.

#### <span id="_Ref373401446" class="anchor"><span id="_Ref373404460" class="anchor"></span></span>Actions Attached to Transitions

Actions can be initiated when a state is transferred into another. They can modify variable values, change the user interface, raise events or interact directly with elements of the item (e.g., the video-player).

The following predefined actions are available:

<span id="_Ref361445910" class="anchor"></span>Table 25: Actions Available in the FSM

| Operator                                                     | Description                                                                                                                                                                              |
|--------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| raise( Event )                                               | Raises the given event after a current event has been processed completely.                                                                                                              |
| reset( Variables )                                           | Sets the list of variables in “Variables” (identifiers) to value 0. Multiple variables can be separated by “,”. The operator also applies for exogenous MicroDYN variables.              |
| set( Variable, Value )                                       | Sets the variable value of “Variable” (identifier) to the expression “Value”. The operator also applies for exogenous MicroDYN variables.                                                |
| setActive( UserDefineID )                                    
 >                                                             
 > unsetActive(UserDefineID)                                   | Activates/Inactivates a/an ...                                                                                                                                                           
                                                                                                                                                                                                                                                          
                                                                standard or image button (Button, i.e., toggled or untoggled),                                                                                                                            
                                                                                                                                                                                                                                                          
                                                                radio button (RadioButton, i.e., selected or unselected within the corresponding RadioButtonGroup),                                                                                       
                                                                                                                                                                                                                                                          
                                                                combo box items (i.e., selected or unselected from the corresponding ComboBox),                                                                                                           
                                                                                                                                                                                                                                                          
                                                                check box (CheckBox, i.e., tickmarked or not) or                                                                                                                                          
                                                                                                                                                                                                                                                          
                                                                image area (ImageField, i.e., highlighted or not, if not in “multiselect mode”).                                                                                                          
                                                                                                                                                                                                                                                          
                                                                Note that connected events are not raised implicitly by activation or deactivation.                                                                                                       |
| setFrozen(UserDefineID)                                      
 >                                                             
 > unsetFrozen(UserDefineID)                                   | Makes a scale value input (ScaleValueInput, see II.5.1.3) or a button (see II.3.4.6) usable or not for test takers.                                                                      |
| setHidden (UserDefineID)                                     
 >                                                             
 > unsetHidden (UserDefineID)                                  | Makes a TaskBarButton (see III.1.6) or MicroDYN History Panel or MicroDYN Model Panel (see **Fehler! Verweisquelle konnte nicht gefunden werden.**) visible or not for test takers.      |
| setMediaPlayer (UserDefineID of a MediaPlayer, Operation )   | Controls the settings of a specific media player (user defined ID). The following operations are available:                                                                              
                                                                >                                                                                                                                                                                         
                                                                > *mp\_start* = starts the media player execution at the beginning or continues when paused                                                                                               
                                                                >                                                                                                                                                                                         
                                                                > *mp\_stop* = stops the media player execution and rewinds to the beginning                                                                                                              
                                                                                                                                                                                                                                                          
                                                                *mp\_pause* = pauses the media player execution (without rewinding)                                                                                                                       |
| setMediaPlayerVolume ( MediaPlayer, Integer )                | Controls the volume of a specific media player (user defined ID). The Volume corresponds to an integer value from 0 (mute) to 10 (maximal volume).                                       |
| setValueDisplayMode ( ValueDisplay, Mode )                   | Sets the “Drag and Drop-Mode” of a specified value display (user defined ID). The value display components can be numbers, texts, images, or icons. The following modes are available:   
                                                                >                                                                                                                                                                                         
                                                                > *dd\_none* = the component does not allow dragging or dropping                                                                                                                          
                                                                >                                                                                                                                                                                         
                                                                > *dd\_drag* = the component only allows dragging                                                                                                                                         
                                                                >                                                                                                                                                                                         
                                                                > *dd\_drop* = the component only allows dropping                                                                                                                                         
                                                                                                                                                                                                                                                          
                                                                *dd\_dragdrop* = the component allows both dragging and dropping                                                                                                                          |
|                                                              |                                                                                                                                                                                          |

> **Note 1:** FSMs can be also used for between-item navigation. See section II.6.1.4 for control commands.
>
> **Note 2:** An extension of operators for the implementation of web browser simulation can be found in section III.1.4.
>
> **Note 3:** An extension of operators for the implementation of MicroDYN model can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.
>
> **Note 4:** An extension of operators for the implementation of IB tree structures can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.
>
> **Note 5:** An extension of operators to calculation engine settings can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.

### <span id="_Ref373225119" class="anchor"><span id="_Toc380472929" class="anchor"></span></span>Graphical FSM Editor

<span id="_Ref370748630" class="anchor"></span>In addition to the State Machine, the IB also provides an editor to visualize states and their transitions. The visualization is formed by a state chart diagram which is made of simple nodes, start nodes, end state nodes, composite state nodes, and submachine reference state nodes as well as transitions. Drawing a transition opens a little comment text field where events or variable change can be drafted.

The editor can be opened by using the menu entry o the menu bar icon *Edit State Chart*. Note that this additional editor only supports an overview about the structure in a FSM. FSM’s cannot be implemented by this editor and the graphical illustration does not synchronize with changes in state machine rules.

The example described in section II.5.6.1, for instance, can be visualized by Figure 106.

| FSMexample.zip | State Machine Diagram                                                                                                                                                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image173.png)                                                                                                                                                           |
| <span id="_Ref373307947" class="anchor"><span id="_Toc380473067" class="anchor"></span></span>Figure 106. StateMachine Diagram for Visualizing States and State Transitions Within a FSM |

### <span id="_Ref373391582" class="anchor"><span id="_Toc380472930" class="anchor"></span></span>Examples

The following two examples illustrate the implementation and the usage of Finite State Machines. The first example shows how visual feedback for the test taker solving a certain task can be implemented. The second example demonstrates how navigation between pages can be defined and restricted by using a FSM. For how to define variables, events, states and rules in particular you should see the previous sections. For other examples also check the Cookbook part on FSM (III.3).

#### Example 1: Implementing Visual Feedback

In this example a visual feedback should be created signaling the test taker that he or she still has to answer a certain question or not. Furthermore, the test taker should receive the feedback over all pages he or she can visit.

For implementation, first of all an area, where the feedback shall be presented, is drawn on every page. As we use images as feedback signs, ImageValueDisplays are used to present the feedback. The ImageValueDisplays are drawn on a text page (see part A of Figure 107) and on a question page (see part B of Figure 107).

| FSMexample.zip | Edit View                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| A                                                                                                                                                        |
| <span id="_Ref371340838" class="anchor"><span id="_Toc380473068" class="anchor"></span></span>Figure 107. Edit View of Two Pages with ImageValueDisplays |

In a next step a Value Map containing all possible feedback images has to be prepared (part A of Figure 108). Note that in this case you have to upload images in the ressource browser (see II.3.3). In a Value Map each used image is assigned to a specific value (see II.5.1.4).

After preparing a Value Map the needed states and variables should be defined in the “State Machine”-Editor (part B of Figure 108). For feedback implementation at least a start state (“Start”) as well as two states, i.e., task is still incomplete (“ST\_incomplete”) or already complete (“ST\_complete”), and one variable (“V\_Done”) have to be defined. Note that you now need to connect the ImageValueDisplays to the variable “V\_Done” as well as to the Value Map “M\_Done” to make sure that images in the ImageValueDisplays refer to images from the Value Maps according to the variable number.

| FSMexample.zip | Edit View                                                                                                                                                                              |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A                                                                                                                                                                                                       |
| B                                                                                                                                                                                                       |
| C                                                                                                                                                                                                       |
| <span id="_Ref371341345" class="anchor"><span id="_Toc380473069" class="anchor"></span></span>Figure 108. Value Map (A), State Machine (B) and State Maching Rules (C) for Implementing Visual Feedback |

To relate states and variable to each other open the “State Machine Rules” (part C of Figure 108). By using the FSM syntax you can define the event “EV\_Click” which triggers the state change from “ST\_incomplete” to “ST\_complete”. The state change, in turn, initiates the integer switch in the variable “V\_Done” to “1”. As the last step you also have to adjust each radion button to raise the event “EV\_Click”.

When each part is implemented correctly, the item works as follows: When you preview the item for the first time, the visual feedback reports that the task is unsolved (part A of Figure 109). If you switch between pages but do not solve the task, the feedback remains (part B of Figure 109). When you process the task by clicking a radio button, the visual feedback shifts its display to task completion (part C of Figure 109). The feedback now remains over all pages (part D of Figure 109).

| FSMexample.zip | Preview                                                                                                                                          |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A                                                                                                                                                                 |
| C                                                                                                                                                                 |
| <span id="_Ref371329733" class="anchor"><span id="_Toc380473070" class="anchor"></span></span>Figure 109. Preview of Different Pages during the Item Presentation |

#### Example 2: Implementing and Restricting Navigation

In this example the FSM is used to implement navigation and restrict the navigation options to certain time circumstances. At the beginning we have a reading page with a “Go to Task Page” button (part A of Figure 110), a task page with a “Go To Reading Page” button (part B of Figure 110) as well as two modal dialogs serving (part C and D of Figure 110) for different timeouts available.

Both the reading page and the task page contain two NumberValueDisplays for a separate timer indication, the time spent on the reading rage (Reading Time) and a total task timer representing the time left for processing the whole task (Total Time). The reading timer should only run when the reading page is displayed. When the timer runs out, the reading page should not be available anymore (part C of Figure 110). The “Go to Reading Page” button, then, needs to be linked to the corresponding modal dialog reporting the restriction. When the total timer runs out, task processing (as well as reading) should end by displaying a timeout page (part D of Figure 110).

| NavRestriction\_simple.zip | Preview                                                                                                                                                 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A                                                                                                                                                                                    |
| C                                                                                                                                                                                    |
| <span id="_Ref371348736" class="anchor"><span id="_Toc380473071" class="anchor"></span></span>Figure 110. Edit View of Used Pages. Pages in Part A and B Contain NumberValueDisplays |

For implementing the navigation between single pages as well as the timer conditions, nested states need to be used. In the example we implemented a start state and four normal states that are assigned to each page. Some of these normal states, in turn, possess a separate start state and one normal state. States and also other variables needed for the timer counting have to be defined in the “State Machine” editor (part A of Figure 111).

In the “State Machine Rules” (part B of Figure 111) two events for navigation and one for “timer ticking” are defined. The navigation events need to be raised by clicking the “Go to Task Page” button on the reading page and the “Go To Reading Page” button on the task page. The “timer ticking” event is used in the syntax definition of the FSM.

The FSM Rules part starts with the transition from the overall start state in the first state which is associated with the reading page. In the following each nested state needs a syntax line to be initiated from its start state to its running state (each line with a single arrow “-\>”). The running states of the nested states, then, need a transition rule to each other state that can be called (each line with a double arrow “=\>”). Behind the state transitions, events and conditions are denoted in curly bracket that should be triggered when this state is changed. Note that the timer variables are only changed by the “timer ticking” event when a running state is transited to itself, except for the reading time-timer which pauses one the task page. Note also that you have to connect the NumberValueDisplays with either variable “V\_TimeReading” or variable “V\_TotalTime” to display the timer number counting down.

| FSMexample.zip | Edit View                                                                                                                                                                                      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A                                                                                                                                                                                                               |
| B                                                                                                                                                                                                               |
| <span id="_Ref371349066" class="anchor"><span id="_Toc380473072" class="anchor"></span></span>Figure 111. State Machine (A) and State Maching Rules (B) for Implementing Navigation and Navigation Restrictions |

When each part is implemented correctly, the item works as follows: The test taker starts at the reading page where the two timers count down from 10 seconds and 30 seconds, respectively (see part A of Figure 112). As long as both timer run, test takers can switch between reading page and task page any time. Note that the reading time-timer only counts down when test takers visit the reading page. The total time-timer, however, continues (see part B of Figure 112). When the reading time is over, test takers are automatically led to the task page. If they try to get back to the reading page, a modal dialog opens reporting that test takers are not allowed to go back (see part C of Figure 112). Then the total time-timer runs out, another modal dialog opens reporting that time is over and the task processing is ending (see part D of Figure 112).

| NavRestriction\_simple.zip | Preview                                                                                                                                                  |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A                                                                                                                                                                                     |
| C                                                                                                                                                                                     |
| <span id="_Ref371411784" class="anchor"><span id="_Toc380473073" class="anchor"></span></span>Figure 112. Preview of Different Pages and Timer Settings during the Items Presentation |

<span id="_Ref368477301" class="anchor"><span id="_Toc380472931" class="anchor"></span></span>Advanced Functions
----------------------------------------------------------------------------------------------------------------

The IB provides a wide variety of other features. To highlight just a few the following sections give a short introduction about commands (see II.6.1), usage of regular expressions (see II.6.2), dynamic texts (see II.6.3), conditional linking and task initializing (see II.6.4) as well as the OLT editor for easy item translation (see II.6.5).

### <span id="_Toc377756492" class="anchor"><span id="_Toc377809366" class="anchor"><span id="_Ref361579156" class="anchor"><span id="_Toc380472932" class="anchor"></span></span></span></span>Commands

Commands extend the functionality of buttons and menu items. They are usually assigned to buttons and menu items, but some of them can also be called from the FSM (see II.6.1.4). In regular elements command setting is empty. To implement a command you have two options: First, right-click the button or menu items you want to extend to open its context menu (part A in Figure 113). Select “Set Command” and the dialog “Set Runtime Command”opens (part B in Figure 113). Select a command and confirm with OK. The command is then set. Second, you can also assign a command via the button’s properties. Go to the properties entry “Command” in “Component Interaction” and select any command you need.

| A                                                                                                                            |     | B   | ![](images/media/image194.png) |
|------------------------------------------------------------------------------------------------------------------------------|-----|-----|--------------------------------|
|                                                                                                                              |     | C   |                                |
| <span id="_Ref373221722" class="anchor"><span id="_Toc380473074" class="anchor"></span></span>Figure 113. Assigning Commands |

> **Important Note:** If you set commands through the properties, note that the commands “BACK”, “FORWARD”, “HOME”, “BOOKMARK” and “SEARCH” are out-dated and do not serve a useful purpose anymore. Presently, these commands are directly available as independent buttons. Note that you can implement a back, forward, home, and bookmark button only within web browser pages (see III.1.4). Buttons containing the search command, however, need to be implemented within a SearchGroup that can be placed on a simple page (see **Fehler! Verweisquelle konnte nicht gefunden werden.**).

#### Clipboard Commands

The commands cut, copy and paste refer to an internal IB clipboard. Therefore, it is possible to cut, copy, and paste text segments within an IB project. For using these commands input fields are needed from which text segments could be marked for cutting and copying, and in which text could be pasted, respectively. For cookbook examples about how to use the clipboard see **Fehler! Verweisquelle konnte nicht gefunden werden.**.

#### The Close Command

The close-command is especially needed when dealing with the dialogs or modal dialogs in IB items. If a button is assigned to this command, it closes an open dialog.

Note that you necessarily need to implement a close-command if you restrict your dialog to be not closable in its frame properties. For implementation see the cookbook examples about how to use the close command for dialogs (see section III.1.7).

#### The Next-Task, Cancel-Task and Back-Task Commands

If the items are developed for the navigation mode “in-item navigation” (see **Fehler! Verweisquelle konnte nicht gefunden werden.**), three specific commands are provided which can be assigned to the user interface (i.e., to buttons) or the FSM. As indicated by their names these commands execute the termination of the current task and start – if provided – another task.

Note that you cannot evaluate the functioning of these commands in the preview because you cannot preview multiple tasks with the IB simultaneously. For an implementation check you have to integrate your IB tasks in a delivery platform.

#### Calling Commands from the FSM

The aforementioned commands for controlling task execution can also be called by FSMs. This is especially useful, when multiple circumstances shall trigger task processing. The available operators are listed in Table 26.

<span id="_Ref377755852" class="anchor"></span>Table 26: Task Control Commands for Usage in FSMs

| **Operator**                     | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **back\_task()**                 | Terminates the current task and calculates the (intermediate) scoring result and then goes back to the previous task, if one is available. The previous task is defined by the test sequence, i.e., by the task order in the choosen test delivery platform. If the selected task had been already visited in the test session, states within that task are restored in the states the moment the task was left.                                                                                                                                                                                                      |
| **cancel\_task()**               | Terminates the current task and calculates the (intermediate) scoring result.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **next\_task( TaskID, TestID )** | Terminates the current task and calculates the scoring result and then goes on to the next task if one is available. The next task is defined by the test sequence, i.e., by the task order in the choosen test delivery platform. TaskID and TestID are optional arguments referring to the next task and to the next test to go to, if one is available. Note that task name is defined within an IB project whereas test name is defined within the test delivery platform. The task ID always has to be specified if the test ID is not omitted. If the test ID is omitted, the task belongs to the current test. |

### <span id="_Ref368327461" class="anchor"><span id="_Toc380472933" class="anchor"><span id="_Ref373141997" class="anchor"></span></span></span>Regular Expressions 

A regular expression is a sequence of characters (i.e., so called strings) that form a certain pattern of letters, numbers, and additional characters, respectively. Within the IB regular expressions are used for restricting input options in input text fields as well as for matching a test author defined reference expression against test taker’s text response.

Regular expressions in the IB are based on unicode (Unicode, 2000-2012). If they are used for scoring, conditional linking or for definitions in any other syntax-editor based description, regular expressions need to be double-quoted.

The first section in the following introduces some special character sequences you probably use more often than working with regular expressions (see II.6.2.1). The second part (see II.6.2.2) shows how regular expression can be formulated for applying naming rules for IB IDs and identifier. The third and fourth section highlights the specific usage of regular expressions for scoring test taker’s text input (see II.6.2.3) and selection behavior within trees (see 0).

#### Use of Regular Expressions to Restrict Valid Characters for Input Elements

The valid input of multi-line InputFields, SingleLineInputFields and SearchInputFields can be restricted by regular expressions. Means, test takers can only use a character set defined by test authors when typing. Regular expressions are used to define valid input patterns for an input field at design time. Incorrect input is ignored at runtime without any system feedback. Incorrect input is logged after a test taker responded. Table 27 provides an overview about most important character combinations:

<span id="_Ref373144441" class="anchor"></span>Table 27: Examples for Regular Expressions Used in IB Projects to Restrict Input Characters

| Regular Expression | Description                                                                                          |
|--------------------|------------------------------------------------------------------------------------------------------|
| [A-Z0-9 ]\*        | Only upper case letters, blanks and digits are allowed.                                              |
| [^a-z]\*           | All characters except lower case letters are allowed.                                                |
| [0-9]\*            | Only digits are allowed.                                                                             |
| \\\\s\*            | Line break.                                                                                          |
| xx|yy              | Separator for a group of multiple eligible expressions (here: xx and yy). Either xx or yy can occur. |
| (xx)               | Grouping multiple expressions.                                                                       |
| .\*                | Set the preliminary or later string part free (for scoring purpose, see II.6.2.3).                   |
| \\\\               | One backslash in regular expressions.                                                                |
| ^                  | Logical beginning of line.                                                                           |
| $                  | Logical end of line.                                                                                 |
| ^$                 | Empty line.                                                                                          |
|                    |

To implement restrictions of valid characters in one of the mentioned input elements a regular expression can be added to the property “Input Validation Pattern” (in the section “Misc”, see Figure 114).

| InputValidationInputFieldExample.zip| Edit View                                                                                                                                                                        |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image196.png)                                                                                                                                                                                         |
| <span id="_Ref361415478" class="anchor"><span id="_Ref361415475" class="anchor"><span id="_Toc380473075" class="anchor"></span></span></span>Figure 114. Regular Expression in the Property “Input Validation Pattern” |

#### <span id="_Ref361417150" class="anchor"><span id="_Ref373143128" class="anchor"></span></span>Rule for Valid Names and Identifiers in the IB

To make you more familiar with writing regular expressions we give you a short example of how the rules for IDs and names in the IB can be written as regular expression (see section 0). They can be formulated as well as regular expression:

([A-Za-z][A-Za-z\_0-9]\*)

According to the introduction of regular expressions given above this means:

-   Only uppercase and lowercase characters are allowed as first characters: [A-Za-z].

-   A name or ID must have a length of at least one character.

-   No whitespace is allowed in names or IDs.

-   Digits and underscores are allowed after the first position in addition to uppercase and lowercase characters: [A-Za-z\_0-9]\*

#### Use Regular Expressions for Text Scoring

For scoring purposes test taker’s text input needs to be compared to a reference given by the test author. Simple string matching, however, restricts scoring to matches letter by letter. Thus, regular expression can be used to extend scoring possibilities. In the example in Figure 115, for instance, the string “simple input” should be scored as correct example. In dependence of specific additions in regular expressions several text features should be also regarded. Part A of Figure 115 shows the syntax and output for a simple one-by-one string matching. Part B to D illustrate extensions regarding to line breaks (\\\\s\*), alternative notations (|), or other characters occurring before the string to be scored (.\*). Note that you can also score empty lines like in part E, Figure 115.

<span id="_Ref373143219" class="anchor"></span>

|     | ScoringRegular Expressions.zip| Scoring Syntax, Preview and Scoring Viewer                                                            |
|-----|---------------------------------------------------------------------------------------------------------------------------------------|
| A   | ![](images/media/image197.png)                                                                                                        |
|     |                                                                                                                                       |
| B   | ![](images/media/image200.png)                                                                                                        |
|     |                                                                                                                                       |
| C   | ![](images/media/image203.png)                                                                                                        |
|     |                                                                                                                                       |
| D   | ![](images/media/image206.png)                                                                                                        |
|     |                                                                                                                                       |
| E   | ![](images/media/image209.png)                                                                                                        |
|     |                                                                                                                                       |
|     | <span id="_Ref373153179" class="anchor"><span id="_Toc380473076" class="anchor"></span></span>Figure 115. Scoring Regular Expressions |

### <span id="_Ref370206530" class="anchor"><span id="_Toc380472934" class="anchor"><span id="_Ref368300543" class="anchor"><span id="_Ref368304544" class="anchor"><span id="_Ref368311382" class="anchor"></span></span></span></span></span>Dynamic Text in HTMLTextFields

HTMLTextFields may contain special syntax to display dynamic text, i.e., parameters which are replaced with values of the FSM or values of the current scoring. The parameters are evaluated at runtime (as a string value) and replaced in the HTMLTextField. You can use this mechanism, for instance, for giving feedback to your test takers at runtime.

For implementation of dynamic text you just have to construct an HTMLTextField and write down a specific syntax command indicating the parameter which should be displayed. The syntax has the following form:

${ParameterName}

The $-sign and the curly brackets initiate the parameter request. The ParameterName is a chain of the requested indicators and their identifiers (i.e., names) separated by “.”. Incorrect ParameterNames are replaced by empty strings. Parameters are updated each time the HTMLTextField is refreshed. The qualified parameters that are available are listed in Table 28:

<span id="_Ref361418268" class="anchor"></span>Table 28: Qualified Parameters for Dynamic Text in HTMLTextFields

| **Qualified Parameter**          | **Description**                                                                                                                                                                          |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ItemScore.*TaskName*.*ScoreType* | Result of item score for the specified task (see Figure 116). TaskName is the name of your defined task. ScoreType might be (see II.4.2 for the exact description of parameter outcome): 
                                                                                                                                                                                                                              
                                    result                                                                                                                                                                                    
                                                                                                                                                                                                                              
                                    credit\_class                                                                                                                                                                             
                                                                                                                                                                                                                              
                                    credit\_weight                                                                                                                                                                            
                                                                                                                                                                                                                              
                                    reactionTime                                                                                                                                                                              
                                                                                                                                                                                                                              
                                    reactionTimeTotal                                                                                                                                                                         
                                                                                                                                                                                                                              
                                    execTime                                                                                                                                                                                  
                                                                                                                                                                                                                              
                                    execTimeTotal nb\_hits                                                                                                                                                                    
                                                                                                                                                                                                                              
                                    nbInteractions                                                                                                                                                                            
                                                                                                                                                                                                                              
                                    nbInteractionsTotal                                                                                                                                                                       
                                                                                                                                                                                                                              
                                    hit\_weight                                                                                                                                                                               
                                                                                                                                                                                                                              
                                    nb\_misses                                                                                                                                                                                
                                                                                                                                                                                                                              
                                    miss\_weight                                                                                                                                                                              |
| FSMVariable.*FSMVariableName*    | Displays the value of a FSM variable converted to a string (see Figure 117).                                                                                                             |

| Dynamic\_text.zip | Edit View and Preview                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image212.png)                                                                                                                        |
| <span id="_Ref371959675" class="anchor"><span id="_Toc380473077" class="anchor"></span></span>Figure 116. Example for Requesting ItemScore Parameters |

> **Important Note:** If the parameters of the item score are requested and the name of the task is not defined in the task browser then the requested parameter is replaced by “-1”.

| DynamicTextExampleSimple.zip | Edit View and Preview                                                                                                    |
|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image214.png)                                                                                                                          |
| <span id="_Ref371959666" class="anchor"><span id="_Toc380473078" class="anchor"></span></span>Figure 117. Example for Requesting FSM Variable Parameter |

### <span id="_Toc377756496" class="anchor"><span id="_Toc377809370" class="anchor"><span id="_Ref372015762" class="anchor"><span id="_Ref373142010" class="anchor"><span id="_Toc380472935" class="anchor"></span></span></span></span></span>Conditional Linking and Task Initializing 

Conditional linking has already been introduced shortly in section II.3.5.4. However, in this chapter advanced principles of implementation and the using of syntax for determining and describing conditions are given. Because they share the same syntax rules, conditional linking and task initializing are presented here together. Their definitions also have a lot in common with scoring and FSM rule principles, but the rule structure is unique.

Although they are based on the same underlying mechanism, conditional linking and task initializing serve different purposes. Conditional linking is used for guiding the test taker within the IB project to different pages according to a certain event, e.g., leading him or her to a “right”-feedback page when the test taker correctly solves an item. Task initialization, in contrast, is used for setting or restricting specific options at the beginning of a certain task. For instance, a video should play automatically when the test taker starts the task, or specific buttons are hidden and have to be uncovered by test taker’s actions.

The rules in the syntax specify relations between pages in IB projects, conditions and – if defined – involved initializations. According to the syntax, one rule for conditional linking or task initializing consists of three parts:

{ Page : Condition | Initialization }

This syntax structure is basically the same for conditional linking and task initializing. Note that a rule is always surrounded by curly brackets. However, the meaning of the first argument “Page” significantly differs: In conditional linking the page refers to the target page to which to link. In task lnitializing the page refers to the page a test taker currently encounters. For definition the page’s name has to be inserted in the *Page*-argument.

After setting up a page the definition of condition(s) follows separated by a colon-sign “:”. Conditions are Boolean expressions. This means, when their truthfulness is evaluated, conditions turn “true” (condition is fulfilled) or “false” (condition is not fulfilled).

Another optional extension of the syntax structure is to initialize certain events (e.g., starting a scoring mechanism or activating a timer). To implement an initialization the condition has to be separated by a vertical bar “|” at first. Then, initialization parameters are set. To sum up, one rule says that if a condition related to a specific page evaluates to true, a given initializations is executed.

> **Important Note:** “Task Initialization” is not the same as “Initialization”. Task initialization concerns the definition of initial settings when an IB Task is started. Initialization is an element of the syntax rules that can be applied to define conditional links and task initializations.

In the following it is described how and where to define a conditional link and a task initialization, respectively (see section II.6.4.1). The second section focuses on writing conditions (see section II.6.4.2). In the subsequent parts writing initializations regarding the user-interface for test takers (see section II.6.4.3), functioning of a FSM (see section 0), or processing of a MicroDYN model (see section **Fehler! Verweisquelle konnte nicht gefunden werden.**) are described.

#### <span id="_Ref372548668" class="anchor"><span id="_Ref361445458" class="anchor"></span></span>Defining Conditional Links and Task Initializing

Defining rules for conditional links (1) and task initializations (2) has to be done in different ways. Therefore, the item-author has to decide at first whether a conditional linking between pages is needed (1) or a specific task should start with certain requirements for test takers (2). Let us start with the definition of a conditional link.

For defining a conditional links you need to link an element for navigation at first (see section II.3.5.3). In the example in Figure 118, a button (“cond\_button”) should link from Page1 to Page2. Marking the check box item (“check”), though, should lead to Page3. To define this conditional link the “regular link” has to be set at first. To implement the condition open the syntax editor for conditional linking by clicking the button “Edit condition” in the link dialog (left part of Figure 118). Now, you can define the conditional link by setting the target page (“Page3”) and the condition (“check”) in curly brackets (see section II.3.5.4).

A target page combined with a condition represents the minimal form of a conditional link. Additionally, initialization parameters could be added (right part of Figure 118). Initialization parameters can set several functions active (or inactive), when the conditional link is in use. For instance, in the example in Figure 118 the check box item is simultaneously de-selected while the conditional link is activated (“unsetActive(check)”). Means, when test takers go to Page3, the check box gets de-selected. If test takers go back to the initial page, the check box does not possess a tickmark anymore.

| Link\_And\_Init1.zip | Edit View and Syntax Editor                                                                                              |
|-------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                 |
| <span id="_Ref372038358" class="anchor"><span id="_Toc380473079" class="anchor"></span></span>Figure 118. Syntax Editor for Conditional Linking |

> **Important Note:** Note that all involved elements for condition definition need an identifier (i.e. their name or user-defined ID).

For defining a task initialization, another syntax editor has to be used. You get access to this editor via the task browser. Select a defined task in the task browser to which you want to add initialization parameters. The buttons on the right side are activated. Click on the button “Open” to open the syntax editor for conditional link (left part in Figure 119). Note that conditional link is always paired with a specific IB Task.

The example in Figure 119 is similar to the example in Figure 118, except it contains an additional IB Task with a conditional link in the project, caused by the conditional link in Figure 119 (right part), when Page1 is displayed to the test taker (the condition is “true”), the check box “check” is selected. Means, test takers encounter this page with an already tickmarked check box in a certain task (“Task01”).

| Link\_And\_Init2.zip | Edit View and Syntax Editor                                                                                            |
|-----------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                               |
| <span id="_Ref372549325" class="anchor"><span id="_Toc380473080" class="anchor"></span></span>Figure 119. Syntax Editor for Task Initializing |

> **Important Note 1:** Note that you can “recycle” IB projects by defining multiple IB Tasks with different task initialization parameters within one project. Therefore, test takers can encounter the same project by solving different tasks and with, if necessary, different restrictions in the item’s user interface.
>
> **Important Note 2:** Multiple IB Tasks cannot be previewed simultaneously or in form of a test, respectively. For having a preview, a test delivery plattform is needed. Accordingly, commands like “Next\_Task” (see II.6.1) will not work in the IB preview. The IB is just a tool for item authoring.

Of course, you can also define multiple linking and initialization rules at once. In the example in Figure 120, the response to the check box item (tickmarked vs. not tickmarked) lead to different pages and also switches the activation status of the check box simultaneously. Note that you have to frame each additional link and initialization rule by curly brackets. Multiple lining also works for defining task initializations.

| Link\_And\_Init3.zip | Syntax Editor                                                                                                                           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image220.png)                                                                                                                                 |
| <span id="_Ref372041226" class="anchor"><span id="_Toc380473081" class="anchor"></span></span>Figure 120. Multiple Syntax Lines for Multiple Conditional Links |

Furthermore, you can also define multiple conditions and multiple initializations within one rule. In the example in Figure 121, a button (“cond\_button”) only leads to page 3 when the first check box item (“check”) is selected, but not the second one (“check2”). By fulfilling this condition all check boxes get de-selected, too. Note that multiple conditions have to be combined by connecting operators (“and” as well as “or”, for details on this operators and the needed brackets see Table 14 in section II.4.2.2). Combining multiple initializations, however, only needs a separation by space. Defining multiple conditions and multiple initializations also works for task initialization.

| Link\_And\_Init4.zip | Syntax Editor                                                                                                                                     |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image221.png)                                                                                                                                           |
| <span id="_Ref372042386" class="anchor"><span id="_Toc380473082" class="anchor"></span></span>Figure 121. Definition of Multiple Conditions and Multiple Initializations |

> <span id="_Ref372548673" class="anchor"></span>**Note 1:** An extension of operators for conditional linking and task initialization in web browser simulations can be found in section III.1.4.
>
> **Note 2:** An extension of operators for conditional linking and task initialization in MicroDYN model can be found in section **Fehler! Verweisquelle konnte nicht gefunden werden.**.

#### Writing Conditions for Conditional Linking and Initializing Tasks

Conditions are logical expressions that evaluate either to true or false. They can be written as simple condition as well as comparison. Table 29 shows all commands that can be applied as condition in a rule for conditional linking and task initialization.

<span id="_Ref372715957" class="anchor"></span>Table 29: Conditions for Conditional Linking and Task Initializing

| Condition                       | Description                                                                                                                                                                                                                                                                                                                                                                                                 |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| true                            | Condition is fulfilled (per se).                                                                                                                                                                                                                                                                                                                                                                            |
| false                           | Condition is not fulfilled (per se).                                                                                                                                                                                                                                                                                                                                                                        |
| LogicalValue                    | User-defined ID of radio buttons, check boxes, combo boxes or list items. Condition gets true when the defined element is selected.                                                                                                                                                                                                                                                                         |
| isCurrentTask( TaskID )         | Request of the currently executed IB task. Condition gets true if the named task (“TaskID”) corresponds to the currently executed task.                                                                                                                                                                                                                                                                     |
| matches( InputObject, RegExpr ) | Request of test taker’s input in an input field. Command can be applied to InputFields, SingleLineInputFields or HTMLTextFields. Condition gets true if the character string in the named input field (“InputObject”) corresponds to a reference character string defined by test author (“RegExpr”). Note “RegExpr” has to be double-quoted. Furthermore, in HTML text format settings are not considered. |
| ( Condition1 AND Condition2 )   | Logical “and”, i.e., a conditional linking ortask initialization is set when both Condition1 and Condition2 are fulfilled.                                                                                                                                                                                                                                                                                  |
| ( Condition1 OR Condition2 )    | Logical “or”, i.e., a conditional linking or task initialization is set when both Condition1 and Condition2 are fulfilled.                                                                                                                                                                                                                                                                                  |
| NOT Condition                   | Logical negation of the condition.                                                                                                                                                                                                                                                                                                                                                                          |
| [ Comparison ]                  | Comparisons contrast two expressions and compare them with each other. Usually, a number value or a character string is compared to a reference value (or reference character string). Note that all comparisions need to be surrounded by squared brackets.                                                                                                                                                |

In the example, for instance, the *matches()* operator is used. The implemented conditional link always leads from Page1 to Page2, except a test taker writes NEXT inside the given input field. In this case he or she gets to Page3.

| Link\_And\_Init5.zip | Syntax Editor and Preview                                                                                            |
|---------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image222.png)                                                                                                              |
| <span id="_Toc380473083" class="anchor"></span>Figure 122. Example for Using Regular Expression (Character Strings) for Defining Conditions |

Comparisons consist of one expression configured by test takers (e.g., number values or character strings) that is compared to a test author defined reference expression. Table 30 contains all operators that can be used for comparing two expressions for conditional linking and task initialization:

<span id="_Ref377756378" class="anchor"></span>Table 30: Forms of Comparisons for Conditional Linking and Task Initializing

| **Conditional Operator**                   | **Description**                                                                                                                                                                                                |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **[** Expression **==** Expression **]**   
                                             
 **[** Expression **\<\>** Expression **]**  | Binary Operators for standard comparison of text and integer values. If the reference expression is a number, an integer comparison is done. If the reference expression is a string, string matching is done. |
| **[** Expression **\<** Expression **]**   
                                             
 **[** Expression **\>** Expression **]**    
                                             
 **[** Expression **\<=** Expression **]**   
                                             
 **[** Expression **\>=** Expression **]**   | Binary Operators for standard comparison of integer values. The reference expression has to be a number. Otherwise “false” is returned.                                                                        |

Table 31 contains all operators that can serve as expression:

<span id="_Ref372718724" class="anchor"></span>Table 31: Expressions for Comparisons in Conditional Linking and Task Initializing

| **Conditional Operator**               | **Description**                                                                                                                                                                                                                                                                                                                                              |
|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **getItemScore (** TaskID, XPath **)** | Requests current parts of test takers received ItemScore (see section II.4.2). The command contains two arguments. The name of a certain task has to be inserted as “TaskID”. “XPath”, however, needs a double-quoted string specifying the requested ItemScore part. In the following, possible specifications in double-quotes and their calls are listed: 
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “result” = overall result (“1” the results evaluates to “true”, otherwise “0”)                                                                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “nb\_hits” = received number of hits                                                                                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “hit\_weight” = received total weight of hits                                                                                                                                                                                                                                                                                                               
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “nb\_misses” = received number of misses                                                                                                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “miss\_weight” = received total weight of misses                                                                                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “credit\_class” = received credit class                                                                                                                                                                                                                                                                                                                     
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “credit\_weight” = received credit weight                                                                                                                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “nbInteractions” = number of user interactions within one task                                                                                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “nbInteractionsTotal” = cumulated number of user interactions on a task (if the user leaves a task ahead of time and returns to it later)                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “reactionTime” = time until first user interaction in seconds                                                                                                                                                                                                                                                                                               
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “reactionTimeTotal” = cumulated time until first user interaction in seconds (if the user leaves a task ahead of time and returns to it later)                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “execTime” = processing time in seconds of one task                                                                                                                                                                                                                                                                                                         
                                                                                                                                                                                                                                                                                                                                                                                                        
                                          > “execTimeTotal” = cumulated processing time of one task (if the user leaves a task ahead of time and returns to it later)                                                                                                                                                                                                                                   |
| **Integer**                            | Is a number of integer typ                                                                                                                                                                                                                                                                                                                                   |
| **String**                             | Is a double-quoted regular expression (see II.6.2)                                                                                                                                                                                                                                                                                                           |
| **TextField**                          | User-defined ID of a text field                                                                                                                                                                                                                                                                                                                              |

To illustrate the use of comparisons in conditional linking and task initialization see the example in Figure 123. A task is additionally implemented that states the selection of the check box “check” as a hit. The button “Link now!” leads from Page1 to Page2. To navigate from Page1 to Page3 the test taker has to solve the task (i.e., receive a hit). If a test taker selects the check box, the ItemScore results turn into “1” (or “true” as return by the Scoring Viewer) and the condition evaluates to true leading the test taker to Page3.

#### Initialization Configuration Regarding the User Interface 

The following parts list operators for the optional initialization parameter in conditional linking and task initialization rules. Note that initializing parameters set up specific options, if the condition that is connected to them evaluates to true.

| Link\_And\_Init6.zip | Conditional Link Syntax Editor, Hit Syntax Editor, Task Browser, Preview and Scoring Viewer                                     |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image225.png)                                                                                                                         |
| ![](images/media/image227.png)                                                                                                                         |
| ![](images/media/image228.png)                                                                                                                         |
| <span id="_Ref372718896" class="anchor"><span id="_Toc380473084" class="anchor"></span></span>Figure 123. Example for Using a Comparision as Condition |

The following table defines the objects and their attributes which can be initialized. The listed commands refer to general options and restrictions, respectively, regarding changes in the user-interface displayed to test takers:

Table 32: Operators for Initialization in Conditional Linking and Task Initializing

| **Conditional Operator**                                        | **Description**                                                                                                                                                                                                                                                                                                                                                                                            |
|-----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **initMediaPlayer (** MediaPlayer, MediaPlayerParams **)**      | Operator starts the “MediaPlayer” (user-defined ID) at the beginning of a new task. The following parameters can be set:                                                                                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > *automaticStart* =\> true or false                                                                                                                                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > default is false; starts the media player automatically when the corresponding page is displayed, but stops when it is left.                                                                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > *hideControls* =\> true or false                                                                                                                                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > default is false; all controls are hidden if true. The media player is completely invisible when audio resources are played. For video resources only the video area is visible.                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > *maxPlay* =\> number of integer typ                                                                                                                                                                                                                                                                                                                                                                       
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > default 0, means unlimited number of times the media player resource can be played. Note that a resource is counted as “played”, if it reaches the end, or if it is stopped explicitly.                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > *noPause* =\> true or false                                                                                                                                                                                                                                                                                                                                                                               
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > default is false; pause control cannot be activated if true. It is not possible to modify the position of the audio or video resource, the progress bar is set to non-interactive.                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > *noPlay* =\> true or false                                                                                                                                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > default is false; play control cannot be activated if true. Note that this makes only sense, when automaticStart is set to true.                                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > *noStop* =\> true or false                                                                                                                                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > default is false; stop control cannot be activated if true, i.e., the audio or video resource is rendered up to the end while the embedding page is displayed.                                                                                                                                                                                                                                            |
| **setActive(** ID **) **                                        
                                                                  
 **unsetActive(** ID **)**                                        | Operator activates/inactivates …                                                                                                                                                                                                                                                                                                                                                                           
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > taskbar buttons (“TaskBarButton”),                                                                                                                                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > standard or image buttons (“Button”, means is toogled),                                                                                                                                                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > radio buttons (“RadioButton”),                                                                                                                                                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > check boxes (“CheckBox”),                                                                                                                                                                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > combo box items (ComboBoxItem) or                                                                                                                                                                                                                                                                                                                                                                         
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   > image areas (“ImageArea”).                                                                                                                                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
                                                                   ID refers to the user-defined IDs of elements. Neither setActive() nor unsetActive() raise any connected events implicitely.                                                                                                                                                                                                                                                                                |
| **setFrozen(** ID **)**                                         
                                                                  
 **unsetFrozen(** ID **)**                                        | Operator sets “ScaleValueInput” and buttons to “frozen” or “unfrozen”, i.e., when frozen the element cannot be modified by test takers. ID refers to the user-defined ID of the corresponding element.                                                                                                                                                                                                     |
| **setHidden(** ID **)**                                         
                                                                  
 **unsetHidden(** ID **)**                                        | Operator makes a taskbar button, a timer or a MicroDYN HistoryChart invisible or visible. ID refers to the user-defined ID of the corresponding element. The initialization within a conditional link is only allowed from a page associated to the current taskbar, i.e., TaskBarButton.                                                                                                                  |
| **setHighlightable(** ID **)** **unsetHighlightable(** ID **)** | Operator makes rich text fields highlightable or not at runtime. ID refers to the user-defined ID of the corresponding element.                                                                                                                                                                                                                                                                            |
| **setMultiselect (** ID **) **                                  
                                                                  
 **unsetMultiselect (** ID **)**                                  | Operator makes images, image maps, HTML text fields, or MicroDYN variables multiple selectable or unselectable at runtime. Note that you necessarily have to set these elements and the underlying panel or MicroDYN model panel to be selectable in the properties at first (see **Fehler! Verweisquelle konnte nicht gefunden werden.**). ID refers to the user-defined ID of the corresponding element. |
| **setSelectable (** ID **)**                                    
                                                                  
 **unsetSelectable(** ID **)**                                    | Operator makes images, image maps, HTML text fields, or tables selectable or unselectable at runtime. Note that you necessarily have to set these elements and the underlying panel to be selectable in the properties at first (see **Fehler! Verweisquelle konnte nicht gefunden werden.**). ID refers to the user-defined ID of the corresponding element.                                              |

In the example in Figure 124, two IB tasks are implemented within one project. With the help of the initializing parameter in the task initialization rule the two tasks start differently, although using the same start page. Task01 (row A in Figure 124) does not contain specific initial parameter settings. In Task02 (row B in Figure 124), however, the button “cond\_button” is set to be frozen. Therefore, the test taker cannot use the button when Task02 has to be proceeded.

|                                                                                                                                                                             | Link\_And\_Init7.zip | Syntax Editor and Preview |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| A                                                                                                                                                                           | ![](images/media/image231.png)                   |
| B                                                                                                                                                                           | ![](images/media/image233.png)                   |
| <span id="_Ref372735733" class="anchor"><span id="_Toc380473085" class="anchor"></span></span>Figure 124. Example for Using Initialization to Setting Up the User-Interface |

<span id="_Ref372548687" class="anchor"><span id="_Ref372010482" class="anchor"></span></span>

#### Initialization Configuration regarding FSM 

The following table defines the objects and their attributes which can be initialized. The listed commands refer to options and restrictions regarding the functioning of a finite state machine (FSM):

<span id="_Ref361445009" class="anchor"></span>Table 33: Operators for the Configuration of the FSM from Conditional Linking or Task Initializing

| **Qualified Parameter**                      | **Description**                                                                                                       |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **setFSMEvent(** Event, TimerValue **)**     | Sets the timer attribute of the specified Event to TimerValue (a positive integer).                                   |
| **setFSMState(** State, Page **)**           | Sets the page attribute of the start or end state “State” to “Page”, the name of a page in the project.               |
| **initFSM(** Event1, Event2, …, EventN **)** | Initializes the finite state machine by processing the events Event1, Event2, ..., Event N (N\>0) in the given order. |

### <span id="_Ref368464010" class="anchor"><span id="_Ref373391407" class="anchor"><span id="_Ref373391431" class="anchor"><span id="_Ref373391440" class="anchor"><span id="_Ref373391633" class="anchor"><span id="_Toc380472936" class="anchor"></span></span></span></span></span></span>Item Translation (OLT)

<span id="_Ref367891512" class="anchor"></span>The OLT is an item translation tool to support the translation of software and electronic documents. The translation editor of OLT has been adapted and extended originally for a better support of the PISA workflow. With the import and export of XLIFF-files items can be translated into different languages without further constructing efforts:

![](images/media/image235.png)

<span id="_Ref370128360" class="anchor"><span id="_Toc380472937" class="anchor"></span></span>Cookbook 
=======================================================================================================

In this third part of the manual (the “Cookbook”), you will find different hands-on instructions for implementing certain features as well as several IB example projects illustrating specific options and settings. Single instructions focus on how to build a specific feature or to implement a specific functionality, and should help you to get an easy start with the IB. Note that the main focus is on implementation. For information on basic principles or functioning of elements see the User’s Guide part before (see Part II: User Guide).

This part is organized as follows: You will find some recipes dealing with different features of specific page types as well as with the navigation between pages in the fist section III.1. The second section will focus on specific response elements and on examples of how to use them to let test takers solve certain tasks (see III.2). The third section will be about the usage of different FSM-related features (see III.3) and the fourth section will deal with multimedia elements (see **Fehler! Verweisquelle konnte nicht gefunden werden.**).

Note that there are usually multiple ways to implement a specific functionality and that the recipes in this “Cookbook” will present mainly just one possible way to achieve a specific task with a list of steps. Moreover, this collection of ‘How-to’s’ is by no means complete. However, we continuously add additional recepies to make this manual more and more helpful.

<span id="_Toc377809374" class="anchor"><span id="_Ref367886252" class="anchor"><span id="_Toc380472938" class="anchor"></span></span></span>Project Structure
--------------------------------------------------------------------------------------------------------------------------------------------------------------

### Simple Pages

#### Create a Simple Page with Frame and Panel

| **Task:** Create and design a new simple page. |
|------------------------------------------------|
| **Steps:**                                     |
|                                                |
|                                                |

| SimpleFrameAndPanelExample.zip| Edit View and Preview                              |
|------------------------------------------------------------------------------------|
| ![](images/media/image236.png)                                                     |
| <span id="_Toc380473086" class="anchor"></span>Figure 125. Example of a SimplePage |

#### Create Instructions for Test takers

**Task:** Create instructions for test takers on a new page to welcome them to your test and to explain the tasks that will follow.

**Instructions: **

• Start with a simple page prepared with a frame and a panel (see III.1.1.1).

• Add a HTML text field to the page and adjust the size to fit the panel by selecting HTMLTextField from the Palette and draw a rectangle within the panel.

> *Alternatively, you can also use TextField or SingleLineTextField from the palette to create a regular text field and a simple text field, respectively. The following steps are the same. See section II.3.4.1 to get more information about different text fields.*

• A text input field appears immediately in the drawn rectangle. You can use it to directly write your text in the text field. But as long as it is active, you cannot edit your text. Click anywhere outside the HTML text field (e.g., on the panel) to deselect it. Now, you can double-click the HTML text field to open the “HTML Text Editor”.

• Insert your welcome-text for the instruction page.

• Close the “HTML Text Editor” by “Save and Close” button.

| WelcomePageExample.zip| Edit View and Preview                                        |
|--------------------------------------------------------------------------------------|
| ![](images/media/image238.png)                                                       |
| <span id="_Toc380473087" class="anchor"></span>Figure 126. Example of a Welcome-Page |

#### Guiding Test takers by Buttons

| **Task:** Create a button to give test takers the possibility to “navigate” through the item.                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Instructions: **                                                                                                                                                                        |
| Start with a simple page prepared with a frame and a panel (see III.1.1.1).                                                                                                               
                                                                                                                                                                                            
 Add a button to the page by selecting Button from the palette and draw a rectangle within the panel.                                                                                       
                                                                                                                                                                                            
 Now, you can use the button’s properties and its context menu to add design features (e.g., text, colors, and images) and other functions (e.g., linking to other pages, raising events).  |

| SimpleButton.zip| Edit View, Properties View and Preview                                                                                     |
|----------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image240.png)                                                                                                               |
| <span id="_Toc380473088" class="anchor"></span>Figure 127. Example of a Button with Text and Additional Mouse Over Text to Guide Test takers |

<span id="_Ref372384331" class="anchor"></span>

#### Designing Items with Images

| **Task**: Designing items by using images.                                                                                           |
|--------------------------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                                    |
| Start with a simple page prepared with a frame and a panel (see III.1.1.1).                                                          
 >                                                                                                                                     
 > Open the resource browser by clicking either “Browse resources” from the menu or the icon. Upload all the images your want to use.  
 >                                                                                                                                     
 > Add an image field to the page by selecting ImageField from the palette and draw a rectangle within the panel.                      
 >                                                                                                                                     
 > Right-click the image field and select “Link Image” from its context menu.                                                          
 >                                                                                                                                     
 > A new dialog appears and lists all resources uploaded in the resource browser.                                                      
 >                                                                                                                                     
 > Select the image you want to be displayed and confirm with OK.                                                                      
 >                                                                                                                                     
 > If you want to deselect an image, just click on the image name again.                                                               |

| ImageExamples.zip| Resource Browser, Edit View and Preview                                |
|-------------------------------------------------------------------------------------------|
| ![](images/media/image243.png)                                                            |
| <span id="_Toc380473089" class="anchor"></span>Figure 128. Example of IB Item with Images |

### Navigation between Pages and Page Selection

#### Gallery: Different Elements Used to Link between Pages 

This Gallery section shows you applications of elements that can be used for navigation. The IB provides a variety of elements you can use for getting from one page (or display) to another. You can implement links in buttons, textual elements, images, or listing elements (i.e., combo boxes, lists, menus):

| PageSelectionexample.zip| Edit View and Preview                                                                                                                                                                                        |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image246.png)                                                                                                                                                                                                         |
| <span id="_Toc380473090" class="anchor"></span>Figure 129. Examples for Navigation Implementation by Buttons. Note that the project example always contains two elements (Buttons, Images, Hyperlink, etc.) linked to different pages. |

Note that the implementation of a link slightly differs regarding the kind of element that contains the link. The standard procedure is to right-click an element and to select *Link Page* from its context menu. This works for buttons as well as for images:

| NavigationWithImagesExample.zip| Edit View and Preview                                            |
|---------------------------------------------------------------------------------------------------|
|                                                                                                   |
| <span id="_Toc380473091" class="anchor"></span>Figure 130. Navigate with Images from Page to Page |

For more complex text fields, for instance, the link has to be implemented within the text editor:

| TextFieldNavigation.zip| Edit view and Preview                                                |
|-----------------------------------------------------------------------------------------------|
| ![](images/media/image251.png)                                                                |
| <span id="_Toc380473092" class="anchor"></span>Figure 131. Linking to Different Pages by Text |

In case of listing elements, such as combo boxes and menus, the Component View (see section II.3.1.4) is needed to set links to other pages:

| NavigateWithComboBoxExample.zip| Edit view and Preview                                                                                                 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                        |
| <span id="_Ref374027189" class="anchor"><span id="_Toc380473093" class="anchor"></span></span>Figure 132. Navigate with a Combo Box to Different Pages |

| MenuBarExample.zip| Edit View/Preview                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                           |
| <span id="_Ref374027201" class="anchor"><span id="_Toc380473094" class="anchor"></span></span>Figure 133. Navigate with a Menu Entries to Different Pages |

<span id="_Ref373140767" class="anchor"></span>

#### Navigation by Using Buttons and Images

| **Task:** Navigate with buttons from page to page. |
|----------------------------------------------------|
| **Instructions:**                                  |
|                                                    |
|                                                    |
|                                                    |

#### Navigation by Using Text or Text Passages

| **Task:** Navigate with a text, text passages, or hyperlinks to another page. |
|-------------------------------------------------------------------------------|
| **Instructions:**                                                             |
|                                                                               |
|                                                                               |

|     | Create two simple pages (“page”, “target”) at least prepared with frame and panel (see III.1.1.1).               
                                                                                                                         
       Open the first page “page” and add a regular text field.                                                          
                                                                                                                         
       Open the Rich Text Editor by double clicking and type in some text.                                               
                                                                                                                         
       Select the text or single text passages with the mouse in the Rich Text Editor.                                   
                                                                                                                         
       Click to the button ![](images/media/image261.png) and choose “target”-page from the page-list. Confirm with OK.  
                                                                                                                         
       **IB** **Examples:** PageSelectionexample.zip | TextFieldNavigation.zip                                           |
|-----|------------------------------------------------------------------------------------------------------------------|

#### Navigation by Using Entries from a Selection

| **Task:** Navigate with a combo box, list, or menu entry, respectively. |
|-------------------------------------------------------------------------|
| **Instructions:**                                                       |
|                                                                         |
|                                                                         |
|                                                                         |

<span id="_Ref368314025" class="anchor"></span>

#### Gallery: Conditional Links 

This Gallery section shows how you can extent the linking feature by restricting it to certain conditions to be fulfilled as well as to different events. This is especially useful, for instance, when you want to give immediate feedback to your test takers performance.

An extension of the usual linking method (i.e., navigation by attributing a page to a certain element via *Link Page*) is to set conditional links (see III.1.2.6). First, a default link which applies when no condition is fulfilled has to be set. Conditions and linked pages then have to be defined. For definition links need to be written in a syntax editor for conditional linking. In Cookbook-section III.1.2.6 as well as in the example in Figure 134, you can see how conditional linking is defined for the selection of a specific radio button:

| ItemLevelFeedbackPageConditionalLink.zip| Edit View, Conditional Link Syntax and Preview                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image262.png)                                                                                                                                        |
| ![](images/media/image265.png)                                                                                                                                        |
| <span id="_Ref374027625" class="anchor"><span id="_Toc380473095" class="anchor"></span></span>Figure 134. Linking to Different Pages by Previously Defined Conditions |

Another method to navigate between pages is to link via state changes in FSMs (see Cookbook-section III.1.2.7 as well as III.1.2.8). The link mechanism is similar to conditional linking. The binding to state changes, however, allows for parallel changes in the user-interface as well as for more interactivity with the test taker. For implementing navigation via FSMs states it just has to be assigned to certain pages. The test taker, then, navigates by state transition (see II.5.3.3):

| NavigateWithStates.zip| State Machine, State Machine Rules and Preview                                                                       |
|----------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image268.png)                                                                                                               |
| ![](images/media/image270.png)                                                                                                               |
| <span id="_Ref374027877" class="anchor"><span id="_Toc380473096" class="anchor"></span></span>Figure 135. Example for Navigation with States |

Navigation via state transition is especially useful for implementing a timer function. For doing so, a timed event is needed (see 0). When the time runs out, however, state transition can lead the test taker to a time-out page:

| SimpleTimerExample.zip| Edit View, State Machine, State Machine Rules and Preview                                                                |
|--------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                  |
| ![](images/media/image274.png)                                                                                                                   |
| ![](images/media/image275.png)                                                                                                                   |
| <span id="_Ref374027887" class="anchor"><span id="_Toc380473097" class="anchor"></span></span>Figure 136. Example for Navigation by Timed Events |

The implementation of the illustrated features is described in the following sections.

#### <span id="_Ref374027729" class="anchor"><span id="_Ref372540421" class="anchor"></span></span>Link to Pages According to a Response 

| **Task:** Create an item level feedback page by implementing a conditional link (see Figure 134).                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                                                                             |
| Create three simple pages (“Page”, “True”, “False”) at least prepared with Frame and Panel (see III.1.1.1).                                                                   
                                                                                                                                                                                
 Add a RadioButtonGroup with radio button “A1” and radio button “A2” (user-define ID’s must be defined!). Note that the use of other click response elements is also possible.  
                                                                                                                                                                                
 Add a button “Go” with an user-defined ID and right-click on it to open its context menu. Select on *Link Page*.                                                               
                                                                                                                                                                                
 First, select the page “False” as default page in window “Select page”.                                                                                                        
                                                                                                                                                                                
 Second, click on “Edit Condition” and type in the condition (“A1”) that leads to the “True” page, e.g.,                                                                        
                                                                                                                                                                                
 **IB** **Examples:** ItemLevelFeedbackPageConditionalLink.zip                                                                                                                  |

#### Link to Pages While Changing an Item’s State

| **Task:** Create an item level feedback page by assigning pages to different states (see Figure 135).                                                                                                                                                                        |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                                                                                                                                                                            |
| Create two simple pages (“First”, “Second”) at least prepared with Frame and Panel (see III.1.1.1).                                                                                                                                                                          
                                                                                                                                                                                                                                                                               
 Add a click response element, e.g., a button.                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                                                               
 Open the FSM Editor by clicking on *Project* on the menu entry or menu bar icon, choose *Edit State Machine* and go to the *State Machine Rules*.                                                                                                                             
                                                                                                                                                                                                                                                                               
 Add one click-**event** for each page change (“EV\_GoToFirst”, “EV\_GoToSecond”) in the syntax’ event part (see II.5.2).                                                                                                                                                      
                                                                                                                                                                                                                                                                               
 Open the button’s context menu by right-clicking each button. Select “Link Select Event” and connect each button to a corresponding event (button of “First” page with “EV\_GoToSecond” and button of “Second” page with “EV\_GoToFirst”, respectively).                      
                                                                                                                                                                                                                                                                               
 Go to the *State Machine* editor and add three **states**: one start-state (“Start”) and two normal-states (“ST\_First”, “ST\_Second”) (see II.5.3).                                                                                                                          
                                                                                                                                                                                                                                                                               
 Connect the normal states to the corresponding pages (i.e., “ST\_First” to “First”, “ST\_Second” to “Second”) by right-clicking the states. Select “Configure State” from their context menu and type in the name of the page to be connected in the section “Page to open”.  
                                                                                                                                                                                                                                                                               
 Go to the *State Machine Rules* and add rules for initiating the FSM ( **Start -\> ST\_First{true}** ) and changing between the normal states ( **ST\_First =\> ST\_Second{EV\_GoToSecond}** as well as **ST\_Second =\> ST\_First{EV\_GoToFirst}** ).                        
                                                                                                                                                                                                                                                                               
 Your FSM works after you saved the file by “Generate and Save”.                                                                                                                                                                                                               
                                                                                                                                                                                                                                                                               
 **IB** **Examples:** NavigateWithStates.zip | NavigateWithStatesInRegions.zip                                                                                                                                                                                                 |

#### Close an Item when the Time is Over 

| **Task:** Change current page when the time is over (see Figure 136).                                                                                                                                                                                                              |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                                                                                                                                                                                  |
| Create two simple pages (“PageRunning”, “PageOut”) at least prepared with frame and panel (see III.1.1.1).                                                                                                                                                                         
                                                                                                                                                                                                                                                                                     
 Add a NumberValueDisplay from the Palette to the Panel.                                                                                                                                                                                                                             
                                                                                                                                                                                                                                                                                     
 Open the FSM Editor by clicking on *Edit State Machine*.                                                                                                                                                                                                                            
                                                                                                                                                                                                                                                                                     
 Add three **states**: one start-state (“Start”) and two normal-states (“TimerRuns”, “TimeOut”) (see II.5.3).                                                                                                                                                                        
                                                                                                                                                                                                                                                                                     
 > Connect the normal states to the corresponding pages (i.e., “TimerRuns” to “PageRunning”, “Timeout” to “PageOut”) by right-clicking the states. Select “Configure State” from their context menu and type in the name of the page to be connected in the section “Page to open”.  
                                                                                                                                                                                                                                                                                     
 Add one **variable** (“SecondsLeft”) (see II.5.1).                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                                                     
 Go to the *State Machine Rules*.                                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                                                                     
 Add one time-**event** (“TimerTick 1”) in the syntax’ event part (see II.5.2).                                                                                                                                                                                                      
                                                                                                                                                                                                                                                                                     
 Add the **rules** between States, Variables and Events (see II.5.4).                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                                     
 > Start with the transition from the start-state “Start” to the first normal-state “TimerRuns”. When the times starts (i.e., the condition is true), the variable “SecondsLeft” should be set to the initial time.                                                                  
 >                                                                                                                                                                                                                                                                                   
 > Every time the time-event “TickTimer” occurs (i.e., every second left) and the variable “SecondsLeft” is greater than 1, the state “TimerRuns” should convert to itself. In doing so, the variable “SecondsLeft” should be reduced by 1.                                          
 >                                                                                                                                                                                                                                                                                   
 > When the time-event “TickTimer” occurs, but the variable “SecondsLeft” is 1 or less, the state “TimerRuns” should convert to the second state “TimeOut” which automatically leads the test taker to the page “PageOut”.                                                           
                                                                                                                                                                                                                                                                                     
 Right-click on the NumberValueDisplay in the panel and select “Link Variable” from its context menu. Select the variable “SecondsLeft” and confirm with OK.                                                                                                                         
                                                                                                                                                                                                                                                                                     
 Your FSM works after you saved by “Generate and Save”.                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                                     
 **IB** **Examples:** SimpleTimerExample.zip                                                                                                                                                                                                                                         |

### <span id="_Ref373391492" class="anchor"><span id="_Ref373391525" class="anchor"><span id="_Toc380472941" class="anchor"></span></span></span>X-Pages 

#### Add a Remaining Page Part 

| **Task:** Navigate by the help of a combo box, list, or menu entry, respectively. |
|-----------------------------------------------------------------------------------|
| **Instructions:**                                                                 |
| *Create a X-Page*                                                                 |
| *Design a X-Page*                                                                 |
| *Connecting a X-Page*                                                             |

> **Important Note 1**: The size of the X-Page frame is added to other pages’ frame size. Example: A 60x60px X-Page and a 60x60px SimplePage result in a total size of 120x60px in horizontal setting.
>
> **Important Note 2**: Navigation elements in X-Pages will only link to other X-Pages.
>
> **Important Note 3**: X-Pages will be only previewed in combination with their task.<span id="_Ref364848212" class="anchor"></span>

#### Permanent Instruction during Item Processing

| **Task:** Navigate between pages while a general instruction remains constantly.                                  |
|-------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                 |
| Create two simple pages (“First”, “Second”) and one X-Page prepared with frame and panel (see III.1.1.1).         
                                                                                                                    
 Create a button on each simple page and link them among themselves.                                                
                                                                                                                    
 Open the Task Editor and create a new task (see II.4.1). Select “First” as Start Page and X-Page as Start X-Page.  
                                                                                                                    
 The X-Page works after you saved your file by “Generate and Save”.                                                 |

**IB Examples:**

| XPageNavigation.zip| Preview                                                                        |
|-----------------------------------------------------------------------------------------------------|
| ![](images/media/image278.png)                                                                      |
| <span id="_Toc380473098" class="anchor"></span>Figure 137. An X-Page Remains During Item Processing |

#### Change the Instruction during Item Processing

| **Task:** Navigate between different instruction parts.                                                                 |
|-------------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                       |
| Create one simple page and two X-Pages (“X1”, “X2) prepared with frame and panel (see III.1.1.1).                       
                                                                                                                          
 Create a button on each X-Page and link them.                                                                            
                                                                                                                          
 Open the Task Editor and create a new task (see II.4.1). Select the simple page as Start Page and “X1” as Start X-Page.  
                                                                                                                          
 The X-Pages work after you saved by “Generate and Save”.                                                                 |

**IB Examples:**

| XPageNavigationXPagetoXPage.zip| Preview                                                           |
|----------------------------------------------------------------------------------------------------|
| ![](images/media/image280.png)                                                                     |
| <span id="_Toc380473099" class="anchor"></span>Figure 138. Changing X-Pages During Item Processing |

#### Gallery: Different X-Pages and Underlying Layout Settings

You can add some more features to your X-Pages, e.g., the alignment of the X-Page or adding a slider. The following gallery part introduces several X-Page settings and shortly describes their functions. Call up the X-Page settings for a specific IB Task from the Task Browser clicking the button “Layout settings”. The setting dialog opens:

| XPageExample.zip| Task Browser                                                                             |
|------------------------------------------------------------------------------------------------------------|
| ![](images/media/image282.png)![](images/media/image283.png)                                               |
| <span id="_Toc380473100" class="anchor"></span>Figure 139. Tasks Definition and Layout Settings for X-Page |

In Table 34 you find an overview explaining layout setting properties of X-Pages. In the given IB Examples below several layout settings are varied.

<span id="_Ref368478580" class="anchor"></span>Table 34: Layout Settings for the IB X-Page (Task Editor View)

| **Setting**             | **Description**                                                                                                        |
|-------------------------|------------------------------------------------------------------------------------------------------------------------|
| X-Page layout type      | Shows on which side the x-Page is displayed.                                                                           |
|                         | Defines the minimum display width of the x-Page (probably depending on the size of the x-page display of scroll bars). |
| Slider width            | Defined distance between x width of a slider-page and other pages.                                                     |
|                         | Colour of Slider (if selected).                                                                                        |
| CheckBox „Allow resize“ | Checkmark allows scrollbars if (defined otherwise by the slider) the pages are scaled.                                 |

**
**

**IB** **Examples:**

| XPageExample.zip| X-Page Settings and Preview                                                            |
|----------------------------------------------------------------------------------------------------------|
| ![](images/media/image284.png)                                                                           |
| <span id="_Toc380473101" class="anchor"></span>Figure 140. Example of an X-Page with no Special Settings |
| XPageExampleRight.zip| X-Page Settings and Preview                                                       |
| ![](images/media/image286.png)                                                                           |
| <span id="_Toc380473102" class="anchor"></span>Figure 141. Example with a Right-Aligned X-Page           |

| XPageExampleSlider.zip| X-Page Settings and Preview                                           |
|-----------------------------------------------------------------------------------------------|
| ![](images/media/image288.png)                                                                |
| <span id="_Toc380473103" class="anchor"></span>Figure 142. Example of an X-Page with a Slider |

### <span id="_Ref368468255" class="anchor"><span id="_Toc380472942" class="anchor"></span></span>Web Browser and Web Child Pages

The simple web browser consists of the navigation area and the child area that shows the selected web pages at runtime. The web browser page is the container for both areas. In the navigation area you can add some of the well known navigation controls of a common web browser.

Every button listed in the palette window provides a special functionality at runtime:

**Back button and Forward button:** The order in which pages were called at runtime is memorized by the item. Using these buttons the user can navigate backward and forward through the web pages called so far.

**Home button:** The page linked to the button at design time will be displayed at runtime when the user clicks the button.

**Bookmark button:** The current page can be bookmarked at runtime. Clicking on the button will offer the feature ‘Add bookmark’ and ‘Manage bookmark …’. Select ‘Add bookmark’ to add the current pages URL to the list of bookmarks. The selection of ‘Manage bookmarks…’ will produce a dialog which lists the bookmarks already added and offers the possibility to delete one or more entries.

**URL Input field:** This is not really a input field, you cannot enter a URL here to load the entered page. The URL string of the current web child (if specified) will be displayed here

A context menu is presented when the option “Show browser context menu” is selected.

Note that the following texts are defined in the general project settings (see section II.2.2.8)

Context Menu Back

Context Menu Forward

Context Menu Home

#### Simulate a Web Browser and a Web Page

| **Task:** Simulate a Web environment.                                                                                                                                                        |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Instructions:**                                                                                                                                                                            |
| *Create a X-Page*                                                                                                                                                                            |
| *Create a web browser Page *                                                                                                                                                                 |
| *Design web browser*                                                                                                                                                                         |
| *New Task*                                                                                                                                                                                   |
| *Create a Simple Page*                                                                                                                                                                       
                                                                                                                                                                                               
 *Child1*                                                                                                                                                                                      |
|                                                                                                                                                                                              |
| *Create a Simple Page Child2*                                                                                                                                                                |
| *Create a Simple Page*                                                                                                                                                                       
                                                                                                                                                                                               
 *Child3*                                                                                                                                                                                      |
| *Linking between the Pages*                                                                                                                                                                  |
| BrowserExampleSimple.zip|Edit View, Preview and Settings                                                                                                                                     |
| ![](images/media/image290.png)                                                                                                                                                               |
| ![](images/media/image292.png)                                                                                                                                                               |
| <span id="_Ref374348608" class="anchor"><span id="_Ref374348602" class="anchor"><span id="_Toc380473104" class="anchor"></span></span></span>Figure 143. Example for a Webbrowser Simulation |

#### Gallery: Global Icons Settings

To open the global settings dialog right click on the project name in the project view and select the entry “Global Icons” from the context menu.

| BrowserGlobalIconExample.zip|Edit View, Preview and Settings                                     |
|--------------------------------------------------------------------------------------------------|
| ![](images/media/image294.png)                                                                   |
| ![](images/media/image296.png)                                                                   |
| <span id="_Toc380473105" class="anchor"></span>*Figure 144. Example for a Webbrowser Simulation* |

### Tabfolder Page

#### Simulate a Browser with Multiple Tabs

**Task:** Create a TabfolderPage with different tabs to close.

**Instruction: **

-   Create a Project.

-   Add a new tabfolder page and type in “tabfolder” as tabfolder page name.

-   Create three simple pages: simple1, simple2 and simple3.

-   Double-click on tabfolder page.

-   Create a TabfolderFrame.

-   Create a TabfolderGroup.

-   Create three TabButtons within the TabfolderGroup.

-   Rename the TabButtons 1, 2 and 3.

-   Right-click on each TabButton and Show Properties View and change Misc closable from false to true.

-   Double-click on each of the three simple pages and add one frame and panel on the same position. Change the backgroundcolor of the panel.

> **IB Example:** TabfolderExample.zip

| TabfolderExample.zip| Edit View and Preview                                                           |
|-------------------------------------------------------------------------------------------------------|
| ![](images/media/image297.png)                                                                        |
| ![](images/media/image298.png)                                                                        |
| <span id="_Toc380473106" class="anchor"></span>Figure 145. Edit View and Preview TabfolderExample.zip |

### <span id="_Ref373774697" class="anchor"><span id="_Toc380472944" class="anchor"></span></span>Taskbar Page

#### Simulate a Desktop

The TaskbarGroup is a special container for TaskBar Buttons. It must be placed on the top, bottom, left or right side of the frame.The TaskbarButton is a button with a special behaviour at runtime to activate the corresponding child page. The child page is linked to the button at design time.

The Taskbar StartButton is a special kind of TaskbarButton with a particular behaviour at runtime to display the empty desktop.

**Task:** Create TaskbarButtons on a TaskbarPage.

**Instruction:**

-   Create a new Project TaskbarExample

-   Add a new taskbar page and name it Taskbar.

-   Create three simple pages and name it Desktop, Page1 and Page2.

-   Double-click on the Taskbar page.

-   Create a TaskbarFrame.

-   Create a TaskbarGroup on the buttom of the Taskbar.

-   Create a TaskbarStartButton and name it Start.

-   Create a TaskbarButton and name it Page1.

-   Create a TaskbarButton and name it Page2.

-   Left-click on Start Button. Right-click on Start Button. Link Page to Desktop.

-   Right-click on Start Button. Show Properties View. Click on Misc Is Activated and choose true.

-   Left-click on Page1 Button. Right-click on Page1. LinkPage to Page1.

-   Left-click on Page2 Button. Right-click on Page2. LinkPage to Page2.

-   Double-click on the Desktop page.

-   Create a Frame and a Panel.

-   Create an HTML TextField on the Panel. Double-click on this HTML TextField and write Desktop. Save and close.

-   Create a Button on the Panel and name it Page 2. Change the colour of the Button.

-   Right-click on Button Page 2. Set Command to Empty. Link Page to Page 1.

-   Double-click on Page1. Create a Frame and a Panel.

-   Create a Button on the Panel and name it Page 1. Change the colour of the Button.

-   Right-click on Button Page 1. Set Command to Empty. Link Page to Desktop.

-   Double-click on Page2. Create a Frame and a Panel.

-   Create a HTML TextField on the Panel.

-   Double-click on the HTML TextField and write Page 2 in the TextField. Save and close.

> **IB Example:** TaskbarExample.zip

| TaskBarExample.zip| Edit View                                                 |
|-------------------------------------------------------------------------------|
| ![](images/media/image300.png)                                                |
| ![](images/media/image302.png)                                                |
| <span id="_Toc380473107" class="anchor"></span>Figure 146. TaskbarExample.zip |

### <span id="_Ref361585148" class="anchor"><span id="_Toc380472945" class="anchor"></span></span>Dialogs and Modal Dialogs

| ![](images/media/image304.png)                                                                              |
|-------------------------------------------------------------------------------------------------------------|
| <span id="_Toc380473108" class="anchor"></span>Figure 147. Defining Dialogs in the Property View of a Frame |

| SimpleDialogExample.zip| Preview                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](images/media/image305.png)                                                                                                                  |
| <span id="_Ref361424226" class="anchor"><span id="_Toc380473109" class="anchor"></span></span>Figure 148. Example for Dialog and a Modal Dialog |

#### Specific Properties for Dialogs

Although dialogs are specified as frames on simple pages, the following four properties are specific for frames used as dialogs:

1.  *Modal*: Dialogs are shown as modal dialogs if the property “Modal” is specified as true.

2.  *Transparency*: Dialogs and modal dialogs are rendered (semi-)transparent, when a number different from 0 (= non transparent) and smaller than or equal 100 (= invisible) is specified in the frames property “Transperency” (see **Fehler! Verweisquelle konnte nicht gefunden werden.** for an example of a dialog with 50.0 % transparency).

3.  *Text:* The “Text” property of the frame defining a dialog or a modal dialog is displayed as title text.

4.  *Closable*: If the property “Closable” is set to “true”, dialogs can be closed with the small “X” in the upper right corner of the dialog window (i.e., an optional close icon on the top right corner).

Select the frame defining the dialog and edit the properties to change the described characteristics of dialogs in the Property View (see, e.g., Figure 149).

| ![](images/media/image307.png)                                                                                                             |
|--------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="_Ref361585416" class="anchor"><span id="_Toc380473110" class="anchor"></span></span>Figure 149. Specify a Dialog as Not Closable |
| TransparentDialogExample.zip| Preview                                                                                                      |

<span id="_Ref368477639" class="anchor"><span id="_Toc380472946" class="anchor"></span></span>Use Specific Response Elements
----------------------------------------------------------------------------------------------------------------------------

### CheckBox

#### Generate a Simple Checkbox Item 

**Example**: Creating a multiple-choice selection which can be chosen from several alternatives.

**Instructions:**

-   Create a new Project **CheckBoxExampleSimple**

-   Add a New Simple Page **MultipleChoice**

-   Add a Frame and Panel

-   Add an HTML TextField and type in **Choose all relevant options!**

-   Select CheckBox and draw a rectangle on the panel.

-   Then right-click and open the properties:

-   Repeat until you create three check boxes.

-   2. Check Box:

-   3. Check Box:

-   Select Browse Tasks and create a new task

-   Name the Task Checkbox, define MinHits=1 and select as Start PageMultipleChoice

| CheckboxExample.zip| Edit View                                                                                |
|---------------------------------------------------------------------------------------------------------------|
| ![](images/media/image308.png)                                                                                |
| <span id="_Toc380473111" class="anchor"></span>Figure 150. Edit View for the Simple Checkbox Item             |
| CheckBoxExampleSimple.zip| Edit View and Preview                                                              |
| ![](images/media/image309.PNG)                                                                                |
| <span id="_Toc380473112" class="anchor"></span>Figure 151. Edit View and Preview for the Simple Checkbox Item |

### Radio Buttons

#### Create a SimpleRadioButton Item

**Example**: Creating a multiple-choice selection can be chosen from the only one alternative.

**Instructions:**

-   Select the RadioButtonGroup as a container for related radio buttons from the palette and draw a rectangle on the panel.

-   Select RadioButton from the palette and draw a rectangle into the RadioButtonGroup.

-   Coordinates of the radio buttons refer to the RadioButtonGroup.

-   If X = 0, Y = 0, then there is the radio button in the upper left corner of the RadioButtonGroup.

> **Important Notes:** Regardless of the RadioButtonGroup you created earlier, you can create other RadioButtonGroups by clicking on RadioButtons. As RadioButton options texts and images can be used.

| RadioButtonExample.zip| Edit View                                                               |
|-------------------------------------------------------------------------------------------------|
| ![](images/media/image311.png)                                                                  |
| <span id="_Toc380473113" class="anchor"></span>Figure 152. Edit View for the RadioButtonExample |
| RadioButtonExample.zip| Preview                                                                 |
| ![](images/media/image312.png)                                                                  |
| <span id="_Toc380473114" class="anchor"></span>Figure 153. Preview for the RadioButtonExample   
                                                                                                  
 | ImageExample.zip| Preview                                                                |     
 |------------------------------------------------------------------------------------------|     
 | ![](images/media/image313.png)                                                           |     
 | <span id="_Toc380473115" class="anchor"></span>Figure 154. Preview for the ImageExamples |     |

### <span id="_Ref372706096" class="anchor"><span id="_Ref372706411" class="anchor"><span id="_Ref372708822" class="anchor"><span id="_Toc380472949" class="anchor"></span></span></span></span>Input Fields

#### Create an Item with a SingleLineInputField and a InputField

Note that SimpleTextFields can also serve as text input fields (see III.2.3), texts on web child pages (URL text, page description and tab text; (see III.1.4), and result text for compution with calculation engines (see **Fehler! Verweisquelle konnte nicht gefunden werden.**), (Figure 51).

**Example**: Creating an Item with a SingleLineInputField and a InputField

**Instructions:**

-   Create a new Project

-   Add a Frame and a Panel

-   Add a Textfield and name it SingleLineInputField

-   Add a SingleLineInputField

-   Add another Textfield and name it Multiline Text

-   Add an InputField

**IB Examples:** InputFieldExample.zip

| InputFieldExample.zip| Edit View                                                               |
|------------------------------------------------------------------------------------------------|
| ![](images/media/image314.png)                                                                 |
| <span id="_Toc380473116" class="anchor"></span>Figure 155. Edit View for the InputFieldExample |

The InputField is similar to the text box. You can create a box and enter text if needed. In case the typed in text does not fit in the input field a vertical scrollbar will appear automatically in most browsers. Note that in Firefox an input field must have a minimum of 36 px in height for the vertical scrollbar to appear.

The SingleLineInputField works exactly the same way except for not having a box but a line where you can enter a text. The attribute of the SingleLineInputField can be set to read only. This function is useful when creating a web browser and you don not want the browsers address bar to be editable. To do so open the SingleLineInputField’s properties view and set the value of the property “read only” to “true”.

#### Context Menus for Text and Input Fields

A context menu is shown when the option “Show edit context menu” is enabled. Note that the following texts are defined in the general project settings (see section II.2.2.8)

Context Menu Cut

Context Menu Copy

Context Menu Paste

### <span id="_Ref372283977" class="anchor"><span id="_Toc380472950" class="anchor"></span></span>Combo Box and Lists 

A combo box is a mix of a drop-down menu and a textbox which enables the user to choose from a list of several items (e.g., commands/links to other pages or images). Adding a ComboBox to a page is very similar as adding a Menubar with Menus. To create a ComboBox select the ComboBox-Object from the palette and drag and draw a ComboBox on the panel. A name can be set directly after by typing it in the appearing TextField or afterwards by using the Properties View. Thereafter open the Component Subtree Tab and click on the panel, so the ComboBox appears in the Component Subtree Tab. To add (a) ComboBoxItem(s) right-click the ComboBox and select “Add Combo Box Item” from the popup box. A dialog box will show up in which a name for the ComboBoxItem has to be entered. This operation can be repeated for all MenuItems which should be added to a Menu.

To link the ComboBoxItems to Images or other Pages, right-click the concerning ComboBoxItem in the Component Tree Tab and select “Link Image” or ”Link Page” from the popup box.

The grafic shows the Component Subtree Tab with a list of all available objects (ComboBox and ComboBoxItems):

![](images/media/image315.png)

#### Create a Simple ComboBox Item

**Example**: Creating a simple ComboBox

**Instructions:**

-   Create a new Project ComboBoxSimple

-   Start with a simple Page name it Selection

-   Frame and Panel

-   Add a Combo Box on the panel

-   Right-click show properties and edit Font, Fontsize, Height, Width

-   Defined User Id=ComboBox

-   *Right-click on the* ComboBox *entry in the component view to add items to the* ComboBox*. *

-   It is also possible to add items with a Right-click to your ComboBox on the panel

-   Select Add Combo Box Item

-   Text = Choose one page to navigate to

-   User Defined Id = navigate

-   Select Add Combo Box Item

-   Text = Item 1, User Defined Id = Item\_1

-   Select Add Combo Box Item

-   Text = Item 2, User Defined Id = Item\_2

-   Select Add Combo Box Item

-   Text = Item 3, User Defined Id = Item\_3

**IB Examples:** ComboBoxExample.zip

| ComboBoxExample.zip| Edit View                                                               |
|----------------------------------------------------------------------------------------------|
| ![](images/media/image316.png)![](images/media/image317.png)                                 |
| <span id="_Toc380473117" class="anchor"></span>Figure 156. Edit View for the ComboBoxExample |

| ComboBoxExample.zip| Preview                                                               |
|--------------------------------------------------------------------------------------------|
| ![](images/media/image318.png)                                                             |
| <span id="_Toc380473118" class="anchor"></span>Figure 157. Preview for the ComboBoxExample |

| ComboBoxSimple.zip| Preview                                                               |
|-------------------------------------------------------------------------------------------|
| ![](images/media/image320.PNG)                                                            |
| <span id="_Toc380473119" class="anchor"></span>Figure 158. Preview for the ComboBoxSimple |

#### Create a simple List Item

**Example**: Creating a simple List Item

**Instructions:**

-   Create a new Project ListSimple

-   Start with a simple Page name it Selection

-   Frame and Panel

-   Add a List on the panel

-   Right-click show properties and edit Font, Fontsize, Height, Width

-   Defined User Id=List

-   *Right-click on the* List *entry in the component view to add items to the* List

-   It is also possible to add items with a Right-click to your List on the panel

-   Select Add List Item

-   Text = Choose one page to navigate to

-   User Defined Id = navigate

-   Select Add List Item

-   Text = Item 1, User Defined Id = Item\_1

-   Select Add List Item

-   Text = Item 2, User Defined Id = Item\_2

-   Select Add List Item

-   Text = Item 3, User Defined Id = Item\_3

**IB Example:** ListBoxExample.zip

| ListBoxExample.zip| Edit View                                                                 |
|-----------------------------------------------------------------------------------------------|
| ![](images/media/image322.png)![](images/media/image323.png)                                  |
| <span id="_Toc380473120" class="anchor"></span>Figure 159. Edit View for the ListBoxExample   |
| ListSimple.zip| Preview                                                                       |
| ![](images/media/image324.png)                                                                |
| <span id="_Toc380473121" class="anchor"></span>Figure 160. Preview for the ListSimple Example |

#### Gallery: Differences and similarities between ComboBox Item and ListBox Item

| ComboBox                       | List                           |
|--------------------------------|--------------------------------|
| ![](images/media/image325.png) | ![](images/media/image326.png) |
| ![](images/media/image327.png) | ![](images/media/image328.png) |
| ![](images/media/image329.png) | ![](images/media/image330.png) |
| ![](images/media/image331.PNG) | ![](images/media/image332.png) |

| <span id="_Toc380473122" class="anchor"></span>Figure 161. Comparison between ComboBox and List |
|-------------------------------------------------------------------------------------------------|

### Menu

**Example:** Create a Menubar

**Instructions: **

-   Start with a Frame and Panel

-   Add a Menubar on the Panel

-   Add Menu on the Menubar

-   Name the Menu File

-   Right-click on the Menu

-   Add Menu Item

-   Add the Text, User Defined Id and Mouse Over Text

-   Add second Menubar on the Panel

-   Add Menu on the second Menubar

-   Name the Menu Edit

-   Right-click on the Menu

-   Add Menu Item

-   Add the Text, User Defined Id and Mouse Over Text

-   Add third Menubar on the Panel

-   Add Menu on the third Menubar

-   Name the Menu About

-   Right-click on the Menu

-   Add Menu Item

-   Add the Text, User Defined Id and Mouse Over Text

A Menu includes a list of one or more MenuItems (e.g., commands/links to other pages or images) which can be selected by the user. Before one or several menus with its MenuItems can be added to a page, a MenuBar has to be created first, in which the menu(s) will be placed afterwards. This is done by selecting the menubar-object and placing a MenuBar in an existing panel by drag and drop. Afterwards (a) Menu(s) can be placed inside the MenuBar also by drag and drop. Therefore the menu-object has to be selected from the palette. A name can be assigned to the menu directly by typing it in the appearing TextField. This can also be done later on in the Properties View by editing the value for the property “Text” under the Core rider.

The image shows a MenuBar with two Menus:

![](images/media/image333.png)

To add (a) MenuItem(s) to the menu(s) you first have to change from the Project View to the Component Subtree Tab by clicking on it. This can be found left to the Project View Tab. Thereafter left-click the Panel and the Menubar will appear under the Component Subtree Tab. To add (a) MenuItem(s) open the Subtree by clicking on the “+” symbol left to the name of the MenuBar. A list with all related menus will appear. Right-click on the relevant menu and select “Add Menu Item” from the appearing pop up menu. A dialog box will show up in which a name for the MenuItem has to be entered. This operation can be repeated for all MenuItems which should be added to a Menu.

MenuItems can be linked to images or pages by selecting a relevant MenuItem from the subtree. From the popup box which appears after right-clicking the MenuItem “Link Image” or “Link Page” can be selected. A MenuItem can be deleted by clicking on “Delete Menu Item” which can also be found in the same pop up box.

The image shows the Component Subtree Tab with a list of all available objects (MenuBar and Menus with MenuItems):

![](images/media/image334.png)

### <span id="_Ref372709364" class="anchor"><span id="_Toc380472952" class="anchor"></span></span>Image Map

The ImageMap element is a type of container for ImageFields and the ImageTextFields. It allows merging an image and text fields into a single image. Use it if you want to insert a picture. In contrast to the Image Field it is possible to change the size of a picture. Here it is also possible to add other elements, for example, an Image Text Field. First, open a panel, then click right, choose “link image”. Inside the image map several parts can be made clickable: first click on the Image Area, then place it on the panel, then place an “Anchor Point” inside the image area. Points will be visible that are draggable, if you click on the line and drag it, new points will appear: if you click in the image area you can choose the background color, for example.

To create an ImageArea within an image map select the „AnchorPoint”-Tool and click into the area of the image map where you want to place the ImageArea:

![](images/media/image335.jpeg)

You will see an AnchorPoint in form of a “little square”. First, deselect the square by clicking somewhere inside the panel.

![](images/media/image336.jpeg)

Afterwards point the mouse over the angle of the square on which you would like to align the ImageArea. Two opposed arrows will appear. Click on one of the arrows. A dashed square will show up. Then move the pressed mouse somewhere outside the dashed square until it disappears and then the same direction back until the dashed square reappears. Now drop the mouse. The ImageArea will appear. You can change its shape and size by clicking and dragging each of its corners.

![](images/media/image337.jpeg)

To get a more precise shape you can add additional corners to the ImageArea. Place the mouse pointer over the area of one of the ImageArea’s angles to which you want to add a corner. A little “+”-symbol will show up. Drag and drop to the direction, where you want to place the additional corner and drop the mouse.

Corners can be moved to a new position by drag and drop. Corners that you do not need anymore can be removed by aligning them with two other corner points.

If you want to move the whole ImageArea, just click the AnchorPoint and drag.

![](images/media/image338.jpeg)

If you want to change the colour of the ImageArea when clicked at runtime, you can adjust that within the appearance-tab of the properties-view of the AnchorPoint (not of the angles).

The transparency can be modified by editing the value “transparency” in the core-rider of properties-View. Values from 0-100 are allowed.

![](images/media/image339.jpeg)

To create an ImageTextField within an ImageMap you use the ImageTextField-Tool:

![](images/media/image340.jpeg)

The size and the position of the ImageTextField can be changed by clicking and dragging.

Double click on the ImageTextField to open the Rich Text Editor. Here you can enter and edit your text.

![](images/media/image341.jpeg)

You can define the rotation degree of the imagetexfield (values from -180° to 180°). As long as you have a horizontal or vertical ImageTextField (e.g.. -180°, -90°, 0°, 90°, 180°), you can change its size by click and drag of the rectangle. If it is rotated apart from that, you have to change its size by going into the properties and edit the values for “editheight” and/or “editwidth”. To put the changes into effect you will have to open the Rich Text Editor afterwards and click on “save changes”.

![](images/media/image342.jpeg)

Note that (although the functionality is available in the RTE) embedded links will not work in ImageTextFields!

An ImageTextField behaves like a TextField, but does not support embedded links (however font, size, style, color and alignment can be modified). At runtime the portions of the text of an ImageTextField cannot be selected (unlike TextFields, where part of the text can be selected for copy and paste). An ImageTextField can be defined as an ImageArea. This allows making the ImageTextField selectable as a whole.

You should check if the way you created the ImageMaps and ImageTextFields is contradictory at runtime.

At runtime (and in the preview) the test person can select Image-Areas by clicking (the Image-Area is then highlighted according to the attributes you selected). The designer can use the attribute “selectable” (true”) if the TextField is supposed to be selectable at runtime. Those TextFields behave like ImageAreas when clicked.

This means that you have to make sure that a selectable ImageTextField and a selectable ImageArea do not overlap.

Multiple Select: You can select one or several ImageAreas/TextFields within one ImageMap. You deselect by clicking on the ImageArea/TextField again.

Single Select: Only one selectable element within one ImageMap can be selected at once (at runtime).

You can set the status to one of the two by going to the core-tab in the properties-menu of the ImageMap (right click when ONLY the image is selected in the designer view) and then set “Multiple-Select-Mode” to “true” or “false”.

The functionality „validity“helps you to find out whether there are overlaps. Right click outside of the Frame and you will find the command “validate” in the context-menu:

![](images/media/image343.jpeg)

„Validity“ will show you all the overlaps and also gives and explanation.

### <span id="_Ref369882161" class="anchor"><span id="_Toc380472953" class="anchor"></span></span>Highlighting

#### Scoring highlighted text within one text block

For the evaluation of highlighted text at runtime, it is needed to define so called Text Blocks in TextFields. Scoring Rules refer to defined text blocks in hit and miss conditions and evaluate whether a text block has been selected completely or partially.

Several text blocks can be defined. They can overlap and may consist of fragments. Text blocks can be used to delimit correct answers in a text but also to delimit false answers.

A text block can be defined by highlighting text in the Rich Text Editor, clicking the “New text block” button afterwards and setting a name in the appearing popup dialog. The extent of an existing text block can be changed by first selecting the regarding text block from the menu on the left, then highlighting the text area which should be defined for the text block and by clicking the “Change text block” button afterwards.

A distant text part can be added to an existing text block without changing the existing text parts, by highlighting the text which should be added an by then clicking the “Add to the text block” button.

The following tool bar is available for the management of text blocks:

![](images/media/image345.png)

The first button “New text block” creates a new text blocks. A unique name has to be specified. This button is context sensitive and only active when some text is selected. The “Delete” button allows deleting a text block (with all its text fragments) or only an individual text block fragment, depending of the selected element in the text block tree structure. This button is context sensitive and only active when some text block or text block fragment is selected in the text block list.

The third button “Change text block” is used to modify a text block. It is active when a text block is selected in the text block list and a selection is made in the text. When pressed the complete text block is replaced with the new selected text.

The fourth button “Add to text block” is used to add a new text block fragment to an existing text block. It is active when a text block is selected in the text block list and a text is selected. When presses the selected text block fragment will be added to the current text block.

The last button “Refresh” is used to refresh the text block list (and tree structure) after text has been changed in the Rich Text Editor which might implicitly delete or modify text block fragments or complete text blocks.

*The following Example shows the definition of Text Blocks for the Minimum and Maximim Correct Response and for the Miss Area: *

Question: What is the latest time that children should arrive at preschool?

Minimum: “9”

Maximum: “Please have your child here by 9:00 am.”

To score the highlighted text response to this question at runtime, text blocks have to be defined. The picture shows the definition of the Minimum Correct Response (Text Block T1):

![](images/media/image346.png)

The following two pictures show the definition of the complement of the maximum correct response, i.e., the miss area.

In the example, it was not possible to create one text block for the miss area using the “Add to the Text Block”-function, because the first paragraph and the bullet points are in two different TextFields.

This picture shows the first part of the Miss Area (Text Block T2):

![](images/media/image347.png)

This picture shows the second part of the miss area (Text Block T3):

![](images/media/image348.png)

Once the text blocks are defined, the Scoring Rule can be entered into the CBA Item Builder stimulus.

First, a Task needs to be created in the Task view menu (Project/Browse Tasks) by clicking the “New”-button and setting a Task name. The amount of minimum hits is always 1 (as only one hit condition should be defined). Every question is one task. For each task, a starting page will have to be defined. Click the “Tasks Start Page” column and select the page from the appearing drop down menu. You can choose all pages which also appear under Project View.

For each task hits and misses have to be added. To define a hit condition first select the according task from the tasks table, then click the “Add Hit”-button. The hits table relative to the selected task is now active and name and weight have to be set. Then click the “Open”-button right to the hits table. A condition tab will open where the hit Condition is defined, e.g., complete (T1). Here, the hit condition “complete (T1)” means that a correct sore requires the complete selection of text block T1 “9”.

This picture shows the definition of the hit condition:

> ![](images/media/image349.png)
>
> Thereafter the miss condition is defined by opening and editing the condition tab for the misses, e.g., “partial” (T2, T3). Here, the miss condition “partial (T2, T3)” means that a response is scored as incorrectly if parts of T2 and/or T3 are selected.

This picture shows the definition of the miss condition:

![](images/media/image350.png)

<span id="_Ref371328555" class="anchor"><span id="_Toc380472954" class="anchor"></span></span>Using Dynamic Functions
---------------------------------------------------------------------------------------------------------------------

### Value Displays

#### ImageValueDisplay

**Task:** Display different images according to test takers selection.

**Instruction:**

-   Start with a prepared simple page (see III.1.1.1).

-   Switch to the FSM and create a variable named “V\_Example” (see II.5.1.1).

-   Save the project in order to ensure the FSM variables are available in the page editor.

-   Add a ScaleValueInput to the panel and assign the variable “V\_Example” (right-click on the ScaleValueInput, select the entry “Link Variable” and select the variable “V\_Example”).

-   Open the “Resource Browser” and add the images 1.fw.png, 2.fw.png, 3.fw.png and 4.fw.png from the Folder “ValueDisplayExampleSimple”.

-   Open the “Value Map” editor and create a new value map named “M\_Example” (see 5.1.4).

-   Add new entries assigning the guard value 1 to the image 1.fw.png, the value 2 to the image 2.fw.png and proceed similar for the values 3 and 4.

-   Add an ImageValueDisplay to the panel and assign the variable “V\_Example” (see above) as well as the value map “M\_Example” (right-click on the ImageValueDisplay again, select the entry “Link Value Map”).

-   Link the value map “M\_Example” in the same way to the ScaleValueInput.

**IB Example:** ValueDisplayExampleSimple.zip

| ValueDisplayExampleSimple.zip | Design & Preview                                            |
|---------------------------------------------------------------------------------------------|
| ![](images/media/image351.png)                                                              |
| <span id="_Toc380473123" class="anchor"></span>Figure 162. Example for an ImageValueDisplay |

<span id="_Ref368782019" class="anchor"><span id="_Ref368782024" class="anchor"><span id="_Ref370128296" class="anchor"><span id="_Ref370128307" class="anchor"><span id="_Toc380472956" class="anchor"></span></span></span></span></span>Things you might need to know …
==========================================================================================================================================================================================================================================================================

Version 4-16

Advanced organizer

Things of Suboptimal Usability
------------------------------

Usability is not yet optimal:

| **Problem**                                                                                         | **Workaround**                                                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Preview a project, a page, or a task twice does not work.                                           | Only occurs if you have installed the IB under Windows 7 at drive C:\\ Use “Generate and save”, then you can open the preview again.                                                                                        |
| Preview does not work (white screen).                                                               | Close the IB and re-start it.                                                                                                                                                                                               |
| Preview does not work (Firefox is not opening).                                                     | Check if no any other preview is already open. If so, close it. Use “Generate and save”, then you can open the preview again.                                                                                               |
| “Close Project” definitely closes your current project.                                             | The IB does not ask you if you really want to close your project. You should better always save your work in case you click “Close project” by accident.                                                                    |
| User-defined IDs should be used for each element.                                                   | IB generated IDs are just temporary and change every time you save your project (see II.3.2.3).                                                                                                                             |
| You cannot drop elements from the palette.                                                          | You always have to create a container (i.e., normally a frame and panel) at first.                                                                                                                                          |
| You cannot duplicate some elements.                                                                 | Sorry, it is not always working. Try using the template function (see II.3.6).                                                                                                                                              |
| The clipboard in the graphical is not implemented.                                                  | Menu entries in the menu “Edit” (i.e., Cut, Paste and Copy) are always disabled.                                                                                                                                            |
| Missing some fonts. / Too many fonts.                                                               | List of fonts depends on the fonts installed on your system, i.e., the list might be rather long and you cannot type into the dialog elements to change the font.                                                           |
| Appearance tab in the properties is not displayed.                                                  | It might occur when you create an element (e.g., a frame) at first. Click at another element or into the undefined drawing area to deselect your newly created element and then re-click on it. Appearance tab now appears. |
| Regular buttons are not visible in web browser toolbars.                                            | Regular buttons in web browser toolbars need to have an activated image status. Define buttons as image buttons and link an image as activated image.                                                                       |
| The text properties from the Core tab or menu line do not work.                                     | Try to customize them under the appearance tab.                                                                                                                                                                             |
| Re-definition of table cells does not work.                                                         | Row and column number has to be configured at the beginning of table creation and is irreversable. Sorry, you have to define a new table.                                                                                   |
| Removal of tree column does not work.                                                               | Create a new tree view or set the width of the column to 0. Columns apply to both tree and tree view. To hide the tree it must have the same width.                                                                         |
| The line width in rectangles does not change in the Drawing Area.                                   | It is correctly displayed at runtime.                                                                                                                                                                                       |
| The Properties View seems to be frozen. It hangs for a selected element.                            | In that case close the page and re-open it again.                                                                                                                                                                           |
| Some menu items are missing in the Component View.                                                  | Create a new MenuItem in the Component View and delete it afterwards. This “repairs” the broken menu items.                                                                                                                 |
| Parallel assignment of FSM events with commands or (conditional) links to an element does not work. | Define an additional page and use a regular link for the assignment of the command or conditional link, respectively.                                                                                                       |
| Conditional links coming from taskbar pages with start buttons does not work.                       | Re-define the taskbar start button as regular taskbar button.                                                                                                                                                               |
| The page links for Image Maps, Image Areas and Image Text Fields do not work.                       | Try to use another element for linking.                                                                                                                                                                                     |
| Content of MicroFin Model Panel is not restored when coming back to a previous task.                | The state of the graphical model (i.e., State, Transition, and Weight) is lost.                                                                                                                                             |
| Linking images to spreadsheet table cells affects the whole column.                                 | The column is then left-aligned and the content of any other cell in that column is displayed left of the horizontal space taken by the image.                                                                              |
| Toolbar of an editable HTML text field is not displayed.                                            | Probably the HTML text field size is not large enough. Resize the width and height parameters.                                                                                                                              |

Things You Might Not Expect to Work but Actually Do
---------------------------------------------------

The IB is always good for a surprise:

| **Element**                                   | **Workaround**                                                                                                                                                                       |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Change properties for a selection of objects… | … works for background color.                                                                                                                                                        |
| TAO Integration                               | The current official release of TAO (Version 2.5) does not contain the appropriate connector for CBA-ItemBuilder items. For an intermediate version please contact <roelke@dipf.de>. |

Things That Do Not Work
-----------------------

*Ignore* the following elements of the graphical user interface, as they are most often not useful:

| **Element**                          | **Functioning**                                                                                                   |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| “Arrange Selection” in the menu bar… | … re-arranges all (or the selected) elements. However, this will rarely be a useful feature when designing items. |

List of Figures
===============

[Figure 1. Illustration of Correspondence to ZIP-File Examples in the IB Manual iv](#_Toc380472962)

[Figure 2. Idea of code generation and item presentation in the IB 3](#_Toc380472963)

[Figure 3. Example of Selection/Identification Implemented with Check Boxes in the IB (from Scalise, 2006, Figure 2) 5](#_Toc380472964)

[Figure 4. Examples of Multiple Choice with Radio Buttons (from Scalise, 2006, Figure 2 and Figure 4) 6](#_Toc380472965)

[Figure 5. Example of Rearrangement Implemented with RadioButtons in the IB (from Scalise, 2006, Figure 12) 6](#_Toc380472966)

[Figure 6. Example of an Item Using Image Maps to Provide Clickable Areas in a Coordinate 7](#_Toc380472967)

[Figure 7. Example of Substitution / Correction with Combo Box (from Scalise, 2006, Figure 14) 7](#_Toc380472968)

[Figure 8. Example of Completion with Single Line Input Field (from Scalise, 2006, Figure 19) 8](#_Toc380472969)

[Figure 9. Example of Completion with Single Line Input Field (from Scalise, 2006, Figure 18) 8](#_Toc380472970)

[Figure 10. Example of Construction with Input Field (from Scalise, 2006, Figure 25) 9](#_Toc380472971)

[Figure 11. Example of Construction with Buttons (from Goldhammer et al., 2012, released item) 9](#_Toc380472972)

[Figure 12. Example of Construction with Menu Entries (from Goldhammer et al., 2012, released item) 10](#_Toc380472973)

[Figure 13. Example of a Drag and Drop item 10](#_Toc380472974)

[Figure 14. Example of Construction with Highlightable Text (from NCES, 2013, released OECD PIAAC sample item) 11](#_Toc380472975)

[Figure 15. Example Page of a Questionnaire 11](#_Toc380472976)

[Figure 16. Setup wizard for the IB 14](#_Toc380472977)

[Figure 17. Start the IB by (double-)clicking on „cba-itembuilder.exe“ 15](#_Toc380472978)

[Figure 18. How to create a Shortcut on the Desktop 15](#_Toc380472979)

[Figure 19. Uninstall IB 16](#_Toc380472980)

[Figure 20. About Dialog of the IB 16](#_Toc380472981)

[Figure 21. Main Window of the IB 17](#_Toc380472982)

[Figure 22. Menu Entries and Icons for Creating a New Project or Opening an Existing One 18](#_Toc380472983)

[Figure 23. Preview a Project or a Page 19](#_Toc380472984)

[Figure 24. Preview Scope 19](#_Toc380472985)

[Figure 25. CBA Item Size 20](#_Toc380472986)

[Figure 26. Menu Entry and Icon for Closing an Opened Project 20](#_Toc380472987)

[Figure 27. Global project settings 21](#_Toc380472988)

[Figure 28. Central Elements of the IB User Interface 22](#_Toc380472989)

[Figure 29. Menu Bar and Menu Buttons 22](#_Toc380472990)

[Figure 30. Context Menu for the Current Project 25](#_Toc380472991)

[Figure 31. Context Menu for a Selected Page 25](#_Toc380472992)

[Figure 32. Multiple Page Editors above the Drawing Area 25](#_Toc380472993)

[Figure 33. Context Menu of Elements 26](#_Toc380472994)

[Figure 34. Show (or Hide) the Palette 26](#_Toc380472995)

[Figure 35. Opening the Properties View 27](#_Toc380472996)

[Figure 36. Editing Properties 27](#_Toc380472997)

[Figure 37. Settings for Properties View 28](#_Toc380472998)

[Figure 38. “Rulers & Grid” for the IB drawing area 28](#_Toc380472999)

[Figure 39. “Snap to Grid” and “Snap to Shape” 29](#_Toc380473000)

[Figure 40. Preference Settings for “Rulers & Grid” for the IB Drawing Area 29](#_Toc380473001)

[Figure 41. Frame and Panel in the Drawing Area of the IB 32](#_Toc380473002)

[Figure 42. Hierarchical Structure of Frame and Panel 33](#_Toc380473003)

[Figure 43. Additional Elements and Containers on a Panel 34](#_Toc380473004)

[Figure 44. Hierarchical List of Pages Elements in the Component View of the IB 34](#_Toc380473005)

[Figure 45. Additional Menu Bar for Editing a Page 35](#_Toc380473006)

[Figure 46. Example for User Defined IDs 36](#_Toc380473007)

[Figure 47. Editor for User Defined IDs 36](#_Toc380473008)

[Figure 48. The Resource Browser implemented in the IB 37](#_Toc380473009)

[Figure 49. Project Icon Editor 38](#_Toc380473010)

[Figure 50. Examples of Basic Design Elements in the IB 39](#_Toc380473011)

[Figure 51. Different Input Sources of SimpleTextFields 40](#_Toc380473012)

[Figure 52. HTMLTextField editor 41](#_Toc380473013)

[Figure 53. Text Editor for Rich Text 41](#_Toc380473014)

[Figure 54. Link Image 42](#_Toc380473015)

[Figure 55. Examples for the Use of Images to Design Pages 43](#_Toc380473016)

[Figure 56. Link Image to Buttons 44](#_Toc380473017)

[Figure 57. Standard Button (Text), Standard Button (Image) and Image Button 45](#_Toc380473018)

[Figure 58. Implementing a video player within an IB item 45](#_Toc380473019)

[Figure 59. Sorting of Pages in the Project View 47](#_Toc380473020)

[Figure 60. Links can be Assigned to Different Input Elements 47](#_Toc380473021)

[Figure 61. How to Link Pages 48](#_Toc380473022)

[Figure 62. Principle of Conditional Linking 49](#_Toc380473023)

[Figure 63. Conditional Link Example 50](#_Toc380473024)

[Figure 64. Default Link (left) and Condition (right) for the ConditionalLiniking Example 50](#_Toc380473025)

[Figure 65. Saving a page as template 51](#_Toc380473026)

[Figure 66. Message of Correct Template Saving 51](#_Toc380473027)

[Figure 67. Template Browser in the IB 52](#_Toc380473028)

[Figure 68. Menu Bar Entry and Icon for Creating a Page from a Template 52](#_Toc380473029)

[Figure 69. Create a New Page from Page Template 53](#_Toc380473030)

[Figure 70. Exporting Pages from Context Menu (left) or from Template Browser (right) 53](#_Toc380473031)

[Figure 71. Message of Correct Exporting Pages 54](#_Toc380473032)

[Figure 72. Importing Pages from Menu Bar (left) or from Template Browser (right) 54](#_Toc380473033)

[Figure 73. Developing a General Item Concept 55](#_Toc380473034)

[Figure 74. Icon for Opening the Task Editor 56](#_Toc380473035)

[Figure 75. Entries for Definition of an IB Task 57](#_Toc380473036)

[Figure 76. Composition of the Item Score 58](#_Toc380473037)

[Figure 77. Defining Hits and Misses in the Task Editor 59](#_Toc380473038)

[Figure 78. Elements of an IB Item Score (Scoring Viewer in the Preview) 60](#_Toc380473039)

[Figure 79. Example for Scoring Syntax (Simple Condition) 61](#_Toc380473040)

[Figure 80. Example for a Simple Logical Object that also Serves as Conditional Operator 61](#_Toc380473041)

[Figure 81. Example for a Comparison 61](#_Toc380473042)

[Figure 82. Error Message for Incorrect Syntax 62](#_Toc380473043)

[Figure 83. Scoring Example Checkbox (Design View and User-Defined IDs) 66](#_Toc380473044)

[Figure 84. Scoring Example Checkbox (Task definition) 66](#_Toc380473045)

[Figure 85. Adding Hits and Misses 67](#_Toc380473046)

[Figure 86. Scoring Example Checkbox (Hit and two Miss Conditions) 68](#_Toc380473047)

[Figure 87. Scoring Example Text Input (Design View and User-Defined IDs) 69](#_Toc380473048)

[Figure 88. Using the IB Scoring Viewer 69](#_Toc380473049)

[Figure 89. Name Variable Values 71](#_Toc380473050)

[Figure 90. Example for Input Elements Associated with Variables 72](#_Toc380473051)

[Figure 91. Different Settings for the ScaleVariableInput - Element 72](#_Toc380473052)

[Figure 92. Linking a Variable 73](#_Toc380473053)

[Figure 93. Example for Value Maps 74](#_Toc380473054)

[Figure 94. Edit a Value Map Entry in the IB 75](#_Toc380473055)

[Figure 95. Edit the Numeric Value of a Value Map Entry in the IB 75](#_Toc380473056)

[Figure 96. Example for Different Value Displays 76](#_Toc380473057)

[Figure 97. Linking Variables and Linking Value Maps 76](#_Toc380473058)

[Figure 98. Syntax for the FSM Definition 77](#_Toc380473059)

[Figure 99. Example for Events 77](#_Toc380473060)

[Figure 100. Setting Raised Events 78](#_Toc380473061)

[Figure 101. Graphical Editor to Define States 79](#_Toc380473062)

[Figure 102. Defining States 79](#_Toc380473063)

[Figure 103. Defining Regions 80](#_Toc380473064)

[Figure 104. Assigning Pages to FSM States 81](#_Toc380473065)

[Figure 105. Example for FSM Syntax 81](#_Toc380473066)

[Figure 106. StateMachine Diagram for Visualizing States and State Transitions Within a FSM 86](#_Toc380473067)

[Figure 107. Edit View of Two Pages with ImageValueDisplays 87](#_Toc380473068)

[Figure 108. Value Map (A), State Machine (B) and State Maching Rules (C) for Implementing Visual Feedback 88](#_Toc380473069)

[Figure 109. Preview of Different Pages during the Item Presentation 89](#_Toc380473070)

[Figure 110. Edit View of Used Pages. Pages in Part A and B Contain NumberValueDisplays 90](#_Toc380473071)

[Figure 111. State Machine (A) and State Maching Rules (B) for Implementing Navigation and Navigation Restrictions 91](#_Toc380473072)

[Figure 112. Preview of Different Pages and Timer Settings during the Items Presentation 92](#_Toc380473073)

[Figure 113. Assigning Commands 93](#_Toc380473074)

[Figure 114. Regular Expression in the Property “Input Validation Pattern” 96](#_Toc380473075)

[Figure 115. Scoring Regular Expressions 98](#_Toc380473076)

[Figure 116. Example for Requesting ItemScore Parameters 99](#_Toc380473077)

[Figure 117. Example for Requesting FSM Variable Parameter 100](#_Toc380473078)

[Figure 118. Syntax Editor for Conditional Linking 101](#_Toc380473079)

[Figure 119. Syntax Editor for Task Initializing 102](#_Toc380473080)

[Figure 120. Multiple Syntax Lines for Multiple Conditional Links 103](#_Toc380473081)

[Figure 121. Definition of Multiple Conditions and Multiple Initializations 103](#_Toc380473082)

[Figure 122. Example for Using Regular Expression (Character Strings) for Defining Conditions 104](#_Toc380473083)

[Figure 123. Example for Using a Comparision as Condition 106](#_Toc380473084)

[Figure 124. Example for Using Initialization to Setting Up the User-Interface 108](#_Toc380473085)

[Figure 125. Example of a SimplePage 111](#_Toc380473086)

[Figure 126. Example of a Welcome-Page 111](#_Toc380473087)

[Figure 127. Example of a Button with Text and Additional Mouse Over Text to Guide Test takers 112](#_Toc380473088)

[Figure 128. Example of IB Item with Images 113](#_Toc380473089)

[Figure 129. Examples for Navigation Implementation by Buttons. Note that the project example always contains two elements (Buttons, Images, Hyperlink, etc.) linked to different pages. 113](#_Toc380473090)

[Figure 130. Navigate with Images from Page to Page 114](#_Toc380473091)

[Figure 131. Linking to Different Pages by Text 114](#_Toc380473092)

[Figure 132. Navigate with a Combo Box to Different Pages 114](#_Toc380473093)

[Figure 133. Navigate with a Menu Entries to Different Pages 115](#_Toc380473094)

[Figure 134. Linking to Different Pages by Previously Defined Conditions 117](#_Toc380473095)

[Figure 135. Example for Navigation with States 118](#_Toc380473096)

[Figure 136. Example for Navigation by Timed Events 119](#_Toc380473097)

[Figure 137. An X-Page Remains During Item Processing 121](#_Toc380473098)

[Figure 138. Changing X-Pages During Item Processing 122](#_Toc380473099)

[Figure 139. Tasks Definition and Layout Settings for X-Page 123](#_Toc380473100)

[Figure 140. Example of an X-Page with no Special Settings 124](#_Toc380473101)

[Figure 141. Example with a Right-Aligned X-Page 124](#_Toc380473102)

[Figure 142. Example of an X-Page with a Slider 125](#_Toc380473103)

[Figure 143. Example for a Webbrowser Simulation 128](#_Toc380473104)

[*Figure 144. Example for a Webbrowser Simulation* 128](#_Toc380473105)

[Figure 145. Edit View and Preview TabfolderExample.zip 130](#_Toc380473106)

[Figure 146. TaskbarExample.zip 131](#_Toc380473107)

[Figure 147. Defining Dialogs in the Property View of a Frame 132](#_Toc380473108)

[Figure 148. Example for Dialog and a Modal Dialog 132](#_Toc380473109)

[Figure 149. Specify a Dialog as Not Closable 133](#_Toc380473110)

[Figure 150. Edit View for the Simple Checkbox Item 134](#_Toc380473111)

[Figure 151. Edit View and Preview for the Simple Checkbox Item 135](#_Toc380473112)

[Figure 152. Edit View for the RadioButtonExample 136](#_Toc380473113)

[Figure 153. Preview for the RadioButtonExample 136](#_Toc380473114)

[Figure 154. Preview for the ImageExamples 136](#_Toc380473115)

[Figure 155. Edit View for the InputFieldExample 137](#_Toc380473116)

[Figure 156. Edit View for the ComboBoxExample 139](#_Toc380473117)

[Figure 157. Preview for the ComboBoxExample 139](#_Toc380473118)

[Figure 158. Preview for the ComboBoxSimple 140](#_Toc380473119)

[Figure 159. Edit View for the ListBoxExample 141](#_Toc380473120)

[Figure 160. Preview for the ListSimple Example 142](#_Toc380473121)

[Figure 161. Comparison between ComboBox and List 143](#_Toc380473122)

[Figure 162. Example for an ImageValueDisplay 159](#_Toc380473123)

References
==========

(To be continued)

Bugbee, A. C. (1996). The Equivalence of Paper-and-Pencil and Conputer-Based Testing. *Journal of Research on Computing in Education, 28* (3), 282-299.

Clariana, R., & Wallace, P. (2002). Paper-based versus computer based assessment: key factors associated with the test mode effect. *British Journal of Educational Technology, 33* (5), 593-602.

Goldhammer, F., Naumann, J., & Keßel, Y. (2013). Assessing Individual Differences in Basic Computer Skills. Psychometric Characteristics of an Interactive Performance Measure. European Journal of Psychological Assessment. DOI: 10.1027/1015-5759/a000153.

Mason, B- J., Patry, M., & Bernstein, D. J. (2001). An examination oft he equivalence between non-adaptive computer based and traditional testing. *Journal of Educational Computing Research, 24* (1), 29-39.

National Center for Education Statistics [NCES] (2013). *Program for International Assessment of Adult Competencies (PIAAC). Literacy – Sample Item 1.* URL: <http://nces.ed.gov/surveys/piaac/figures/sample_lit1.asp>

OECD (2011). *PISA 2009 Results: Students on Line: Digital Technologies and Performance* (Volume VI). URL

[1] [www.tao.lu](../customXml/item1.xml); Note that the necessary connector is not deployed in the official package of tao version 2.5.3 and a local test package is necessary to use tao with items developed in the IB.

[2] Note that in the current version the IB does not support the assignment of images to check box elements. This is, however, possible for radio buttons.
