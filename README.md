# opendigitaltwins-airport
WillowTwin open digital twin definition language (DTDL) ontology for airports

## Prerequisites

Before getting started:
* Install a code editor such as [Visual Studio Code](https://code.visualstudio.com/) to view, manage, and update the files.
* Install git to allow for cloning and working with this repo and its submodules. For Windows, we recommend [Git for Windows](https://gitforwindows.org/).
* Learn [basic git techniques](https://docs.github.com/en/github/using-git) such as creating a branching, committing, pulling, and pushing.
* Learn about the [Digital Twin Definition Language (DTDL)](https://github.com/Azure/opendigitaltwins-dtdl/blob/master/DTDL/v2/dtdlv2.md) which defines the language used to describe models of digital twins.
* Learn about [Azure Digital Twins](https://docs.microsoft.com/en-us/azure/digital-twins/) which is the service WillowTwin is built upon and this ontology gets loaded into as [Models](https://docs.microsoft.com/en-us/azure/digital-twins/concepts-models).

## Getting Started

* Clone this repo to your local machine by running `git clone`.

* Confirm all of the DTDL files have been downloaded by navigating to the Ontology directory in a command prompt and running `DTDLValidator.exe`. The output should include **Validated all files - Your DTDL is valid**. After making changes to the DTDL files, it is recommended to run this command prior to committing changes.

* Start browsing the Ontology which has the following top-level directories:

    | Directory | Description |
    | --------- | ----------- |
    | Willow | This is the set of WillowTwin DTDL models which are used for creating digital twins |

    NOTE: When creating twins in the WillowTwin, they are always based on a Willow DTDL model id which begins with `dtmi:com:willowinc:airport:`.