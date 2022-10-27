# AI360 - Dive into Business Document Processing with AI Step by Step

## Description

This repository contains the material for the SAP TechEd 2022 session called AI360 - Dive into Business Document Processing with AI Step by Step.  

## Overview

This session introduces attendees to the steps required to create custom templates on Document Information Extraction.

## Requirements

To get the most out of this TechEd hands-on workshop, participants of this training need to create a BTP account and a service instance for Document Information Extraction as a prerequisite step.

### Get your free trial account on SAP Business Technology Platform
To create a service instance for Document Information Extraction it is necessary to generate a trial account if you do not have one. Please remember that your trial account can be extended unlimited times in case your trial account is already expired. You will find more information [here](https://developers.sap.com/tutorials/hcp-create-trial-account.html#0dcf1c45-cd6f-48cc-ae10-690765287a5a). 

### Run Booster for Document Information Extraction 
Once the account is generated, you can create your service instance for Document Information Extraction by running the Booster. [Begin with the tutorial](https://developers.sap.com/tutorials/cp-aibus-dox-booster-app.html)

*Duration: approximately 5 minutes* 

## Exercises

### Exercise 1: (Pre-check) Process a document with a pretrained model
<a id="Exercise0"></a>
- Step 1: Download the [sample document](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/cp-aibus-dox-swagger-ui/data/sample-invoice-1.pdf)
- Step 2: Upload document to the DOX UI and check the results as described [here](https://developers.sap.com/tutorials/cp-aibus-dox-ui.html)

*Duration: approximately 5 minutes*

### Exercise 2: Custom Document Type

<a id="Exercise2a"></a>
**Exercise 2a:**
[Create Custom Schema for Custom Documents](https://developers.sap.com/tutorials/cp-aibus-dox-ui-schema-custom.html)

<a id="Exercise2b"></a>
**Exercise 2b:**
[Create Custom Template for Custom Documents](https://developers.sap.com/tutorials/cp-aibus-dox-ui-template-custom.html)

*Duration: approximately 30 minutes*

### (Optional) Exercise 3: Standard Document Type 

<a id="Exercise3a"></a>
**Exercise 3a:**
[Create Custom Schema for Purchase Order Documents](https://developers.sap.com/tutorials/cp-aibus-dox-ui-schema.html)

<a id="Exercise3b"></a>
**Exercise 3b:**
[Create Custom Template for Purchase Order Documents](https://developers.sap.com/tutorials/cp-aibus-dox-ui-template.html)

*Duration: approximately 40 minutes*

#### Alternative 
Instead of creating the schema and template, they can also be imported by navigating to the template screen and clicking the 'Import Template' button and uploading the [zip-file](./Custom_purchase_order_template.zip). To do so, follow these steps:

* Navigate to the template overview, identify the 'Import Template' button on the very right and click it <img src="https://user-images.githubusercontent.com/33467822/197553317-4a4c2366-6ee3-482a-8150-f11576d14900.png" width="800">
* Select the downloaded zip file <img src="https://user-images.githubusercontent.com/33467822/197553569-589bcae5-bd1a-47c8-b74f-f150ea5c9a1c.png" width="800">
* A new template should appear in the overview with status 'Draft' <img src="https://user-images.githubusercontent.com/33467822/197553995-ba64d741-f53c-450e-9120-0d7de96dd459.png" width="800"> 
* Open the template details by clicking on it and click on 'Activate' <img src="https://user-images.githubusercontent.com/33467822/197554174-47dbae56-af38-46b1-b1f0-5ef3da3d3e48.png" width="800">

*Duration: approximately 5 minutes*

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
