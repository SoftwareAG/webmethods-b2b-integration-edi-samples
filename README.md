# webmethods-b2b-integration-edi-samples
The webMethods Module for EDI Sample package contains EDI samples. These samples serve as examples for converting EDI documents into different formats, mapping and converting XML documents into EDI documents, generating and sending functional acknowledgments, generating and processing AUTACK messages, and so on. The EDI samples require the WmEDIINTSamples package for some of its functionalities to work.

## Requirements

The project was developed and tested on the following installation:
1. Integration Server 9.12
2. webMethods Module for EDI 9.12
3. Flat File 9.12 Fix 1 (Note: Fix 1 is required for this project to run. Prior fix levels are not supported)
4. Software AG Designer 9.12 with Service Development

## Installation
1. Copy the package WmEDISamples.zip into the <install_dir>/IntegrationServer/instances/<instance>/replicate/inbound directory.
2. In the Integration Server Administrator, go to the Packages > Management page.
3. Click “Install Inbound Releases”.
4. In the “Release file name” drop-down list, select “WmEDISamples.zip”.
5. Click “Install Release”.




______________________
These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.
_____________
Contact us at [TECHcommunity](mailto:technologycommunity@softwareag.com?subject=Github/SoftwareAG) if you have any questions.
