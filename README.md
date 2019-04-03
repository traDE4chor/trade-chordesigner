# trade-chordesigner
TraDE-aware ChorDesigner enabling the modeling of data-aware service choreographies

Install within Eclipse through the update site: https://raw.githubusercontent.com/traDE4chor/trade-chordesigner/master

## Installation
* Download an Eclipse IDE Helios SR2 Package for Java EE Developers from the [Eclipse website](https://www.eclipse.org) based on your OS; direct link to [Eclipse IDE Helios SR2 Packages](https://www.eclipse.org/downloads/packages/release/helios/sr2).
* Extract the archive and start the Eclipse IDE
* Register the TraDE ChorDesigner Update Site within the Eclipse IDE
  * Menu entry [Help] => [Install New Software...]
  * Click on [Add] to add a new source
  * Specify a name for the source, e.g., TraDE ChorDesigner
  * And put the URL of the update site in the location textfield: https://raw.githubusercontent.com/traDE4chor/trade-chordesigner/master
  * Click on OK to add the new entry
* Install both features provided through the update site:
  * TraDE BPEL Designer
  * TraDE ChorDesigner
* Follow the instructions within the wizard to complete the installation and restart the Eclipse IDE

## Pre-packaged Releases
You can either follow the installation instructions above or download one of the prepackaged releases (https://github.com/traDE4chor/trade-chordesigner/releases). 

Depending on your OS select one of the available releases which contain an 
   * Eclipse IDE with installed TraDE ChorDesigner (using the update site),
   * as well as the Opal choreography model (see: [Opal Case Study](https://github.com/traDE4chor/trade-core-evaluation/tree/master/opal-case-study)) as an example.