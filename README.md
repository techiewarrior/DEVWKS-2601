[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/RunSi/DEVWKS-2601)

# DevNet Workshop (DEVWKS-2601)- pyATS Genie Ops and Parsers
---

### Table of Contents
---
* [Introduction](/README.md)
* [Step 1 - Getting Started](/guide/step1.md)
* [Step 2 - Topology](/guide/step2.md)
* [Step 3a - Genie Ops](/guide/step3a.md)
* [Step 3b - Genie Ops Continued](/guide/step3b.md)
* [Step 4 - Tabular parsing with Parsergen](/guide/step4.md)
* [Step 5a - Non Tabular parsing with Parsergen - Regex](/guide/step5.md)
* [Step 5b - Non Tabular parsing wtih Parsregen - Markup](/guide/step5b.md)
* [Step 6 - Creating an Ops object](/guide/step6.md)
* [Step 7 - Bringing it home with Easypy](/guide/step7.md)
---

pyATS - Python Automated Test Systems is a Python3 based test automation infrastructure.  
It is developed as the next-generation Cisco mainstream automation infrastructure, is compatible to existing tooling & 
infrastructure, and is officially endorsed by Cisco executive team.  

## The Lab


The files within this Github repository should be cloned to the local machine.

The objective of this lab is to:

* Become familiar with connecting to a testbed
* Leverage the Genie Ops libraries for retrieving operational data
* Explore the models and parsers leveraged by Genie Ops
* To become familiar with the Genie Parsergen library
* To start the journey on creating your own libraries

## The Testbed

So as to provide the best experience in this lab the Genie Unicon Playback feature is being used.  Playback allows for the interaction with a device without the device actually existing.  If you wish to run the lab against a real or virtual device, then please modify the Topology file. 

## Pre-requisites

Users of this lab should have some familiarity with Python and basic concepts of 
object-oriented programming.




### To start please proceed to [Step1](/guide/step1.md)




## Authors & Maintainers

Smart people responsible for the creation and maintenance of this project:

- Simon Hart <sihart@cisco.com>

## Credits

The code snippets and lab could not have been created without the excellent support and guidance from the Cisco ASG Genie Development team, 
2018 Pioneer Award Winners.  
In particular [Siming Yuan](https://github.com/siming85), [Jean-Benoit Aubin](https://github.com/jeaubin) and [Karim Mohamed](https://github.com/karmoham).  Could not have done without 
support of [Kevin Corbin](https://github.com/kecorbin) either, and lastly, but by no means least, [Hank Preston](https://github.com/hpreston) for the 
Box Building and Vagrant plagiarism.

Further information on pyATS can be found on [DevNet](https://developer.cisco.com/site/pyats/)

## License

This project is licensed to you under the terms of the [Cisco Sample
Code License](./LICENSE).
