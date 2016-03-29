[<img src="img/STTR%20Cancer%20Binder_spine_horizontal.png">](http://www.sttrcancer.org/en.html)

[<img src="https://github.com/FredHutch/Oncoscape/blob/newReadme/img/oncoscape_bigger.png">](http://oncoscape.sttrcancer.org)

[![Circle CI](https://circleci.com/gh/FredHutch/Oncoscape/tree/develop.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/FredHutch/Oncoscape/tree/develop)

[![Join the chat at https://gitter.im/FredHutch/Oncoscape](https://badges.gitter.im/FredHutch/Oncoscape.svg)](https://gitter.im/FredHutch/Oncoscape?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Oncoscape is a [web application](http://oncoscape.sttrcancer.org) that hosts an integrated suite of analysis tools for users to explore hypotheses related to molecular and clinical data in order to better understand cancer biology and treatment options.

--**_Intro and Demo and videos coming soon_**

Oncoscape is developed at the Fred Hutchinson Cancer Research Center under the auspices of the Solid Tumor Translational Research initiative. 		

Oncoscape is as an SPA -- a single page web application -- using JavaScript in the browser and R (primarily) on the backend server. It is an R package, though the immediate web-facing http server, currently written in R, will likely change over time to a more traditional architecture. For more detailed information, please see [wiki](https://github.com/FredHutch/Oncoscape/wiki).		

## The Goal 

Oncoscape is to provide browser-based, user-friendly data exploration tools for rich clinical and molecular cancer data, supported by statistically powerful analysis. R is very well-suited to handling data, and performing analysis. JavaScript in the browser provides a rich and nimble user experience.  Data & methods are sent and received through websockets using the chinook protocol (https://github.com/oncoscape/chinook) for message passing.		

Oncoscape's design encourages custom deployments focused on any clinical/molecular data set. Oncoscape, here at GitHub, ships with patient and molecular data from the TCGA. 

If you would like to update the code or contribute with new features, please read [wiki contribution](https://github.com/FredHutch/Oncoscape/wiki/Contribution).

## Contact		

To report any bugs, submit patches, or request new features, please log an issue [in our issue tracker](https://github.com/FredHutch/Oncoscape/issues/new).  For direct inquiries, please send an email to contact@oncoscape.org.

STTRcancer		
Fred Hutchinson Cancer Research Center		
1100 Fairview Ave N		
Seattle, WA 98109		

## LICENSE

Copyright (c) 2014  Solid Tumor Translational Research    http://www.sttrcancer.org		
	
[The MIT License (MIT)](LICENSE)
