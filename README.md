# ai_OmnAIProject_doc
Repository for the documentation of the OpenSource OmnAIProject 


# Introduction

Last update : 21.02.2025

The OmnAIProject is a project to design an USB-oscilloscope, that is much easier to handle than a normal oscilloscope and has a variable multichannel functionality. Additionally, its integrated analyses make it accessible to individuals outside the scientific community.

This document provides an overview of the various repositories included in the OmnAIProject. The first line displays the last update date, indicating the document's current temporal standpoint.

In this document you can find the repositories and documentation of the Hardware, Firmware and Software of the OmnAIScope and OmnAIView. 

The project is mostly an OpenSource project started by the Auto-Intern company. 


## Hardware

The Hardware of the OmnAIScope is internally within the company. 

## Firmware
The Firmware is internally within the company 

## Software
### The OmnAIView GUI

The OmniView GUI is the main part of the OmnAIProject. The Software is used to connect the OmnAIScope to the Laptop, take measurements and analyse this measurements. 

A representation of the OmnAIView software structure for OmnAIView 1.0 can be found in the OmnAIView-Product-Vision Document which is linked in the repository under sw/OmnAIView-Product-Vision. 

The first version of the software written in c++ can be found under sw/OmnAIView.

The documentation of the used API's for analysis can be found under sw/API/file. Currently only the documentation for the FFT API exists. 

The second version OmnAIView 2.0 is currently in development. It is seperated into a cpp backend and an angular frontend. 
Both repositorys as well as the API description for the connection between backend an frontend can be found in the sw/ folder.


### DLL
Some parts of the code should be outsourced into a .dll. 
The demo is right now documented in the linked UaDI repository linked under fw/UaDI.  

## Contact person
If you got any questions about the documentation please create an issue in this repository. 
