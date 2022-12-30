![](images/ahlsbanner.png)
<h1>A-HLS OmniScript Widget w/ Google Maps API Accelerator - Documentation</h1>

<h2>Overview</h2>

The OmniScript widget framework provides customers with various record view/edit/update capabilities and Google Maps API integration that customers can customize to their business needs. 

<h2>Business Objective</h2>

The objective of the Accelerator is to enable your organization to more quickly provide users with an intuitive, visual interface to view and update records.

<h3>Business Value and Benefits</h3>

* Reduce development time and IT costs
* Improve end user experience


<h2>Industry Focus and Workflow</h2>

<h3>Primary Industry:</h3>

* Healthcare and Life Sciences

<h3>Intended End User:</h3>

* Multiple


<h2>Package Includes:</h2>

<h3>OmniScript Widget Framework</h3>

The included OmniScript Widget provides customers with a pre-built OmniScript framework that can be leveraged and configured for various workflows. The capabilities that are in the widget framework include: 

* Google Maps API
* Concatenating discrete fields (e.g. Street, State, Zip) to form a readable Address field by the Google Maps API
* Pub/Sub OmniScript Action which updates the Parent FlexCard when the Child FlexCard is updated.
* Static Google Map image of the Address which is presented to the end user

By default, the OmniScript framework is configured with the Account and Contact objects, but can easily be cloned or configured to interact with any object/data.

*OmniScript (2)*

* ContactEdit
* AccountEdit

*DataRaptor (3)*

* ContactRead
* AccountUpdate
* ContactUpdate

*FlexCard (1)*

* Contact


<h2>Configuration Requirements</h2>

<h3>Installation Steps:</h3>

The following steps are required for installation.

*DPA Components*

1. The DPA components for the are distributed as .json files and are located in the following GitHub repository: https://github.com/healthcare-and-life-sciences/omniscript-view-edit-widget.
2. Please download the .json files and save them to your machine. Then, complete the following steps to import them into your Salesforce org.
    1. To Import, in your destination Salesforce org, Click on *App Launcher* → Search for '*OmniScripts*' and click on it.
    2. Click on '*Import*' and select '*From File*' - When the window opens, select the .json file that you downloaded and stored on your machine. Click '*Install*'.

<h3>Post-Install Configuration Steps:</h3>

1. In order to activate the Google Maps integration, please follow the below steps:
    1. Obtain a Google Maps API Key at the following URL: 
        1. https://developers.google.com/maps/documentation/javascript/get-api-key
    2. Update the OmniScripts “Account Edit” and “Contact Edit” which you installed above to reference the Google Maps Key you created in the previous step. Refer to the following article for additional guidance:
        1. https://docs.vlocity.com/en/Using-Google-Maps-Autocomplete-in-LWC-OmniScripts.html


<h2>Assumptions</h2>

* A customer has licenses for Health Cloud and the HINS Managed Package with OmniStudio.  These solutions have all be installed and are functional.
* A customer is assuming Salesforce Lightning Experience — not Classic.
* Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.
* The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved.


<h2>Revision History</h2>

* *Revision Short Description (Month Day, Year)*

    * Version 1 - May 17, 2022
    * Version 2 - May 31, 2022
    * Version 3 - June 1, 2022
    * Version 4 - July 19, 2022

