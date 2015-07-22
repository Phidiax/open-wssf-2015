# open-wssf-2015
Open Web Service Software Factory 2010 - Visual Studio 2015

This is a port using the Open Source Web Service Software Factory 2010 code for Visual Studio 2015 from 
http://servicefactory.codeplex.com/

Requirements to build code:
Visual Studio 2015
Visual Studio 2015 SDK
Visual Studio 2015 Modeling and Visualization SDK

To install the resulting VSIX files, please install all four VSIX files. Normally these should all install using the Service Factory Package VSIX on the target machine, but this does not properly work. To work around:
1) Install the Service Factory Package
2) Install the Data Contract Package
3) Install the Service Contract Package
4) Install the Host Designer Package.
