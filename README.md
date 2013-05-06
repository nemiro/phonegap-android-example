# App47 PhoneGap plugin Android Example Project

Clone this repository (or download the tar ball) and then proceed to import the sample project (in the 2.x directory, for example) using Eclipse (or your favorite IDE). If you are using Eclipse, when you do import the sample code, make sure you import it as a 'Existing Android Code into Workspace'. 

## Getting started with PhoneGap Android and App47's Android Agent

- Download the [App47 Android Agent](http://app47.com/wiki/doku.php?id=configure:androidapp) from the [App47 Dashboard](https://cirrus.app47.com)
- Copy the AndroidAgent-x.x.x.jar file into your project's `libs` directory
- In your project's `res` directory, copy the `EmbeddedAgentConfig.xml` file into the `xml` diretory (where the PhoneGap `config.xml` file lives)
- Inside the `EmbeddedAgentConfig.xml` file, put your target App's ID (as found in the App47 Dashboard) in the element dubbed `EmbeddedAgent_applicationID`
- Edit the PhoneGap `config.xml` file and whitelist the following URL with subdomains set to true: https://app47.com, http://app47.mobi/, and https://app47.mobi/ 
- Grab the App47 Android Plugin and configure it as a normal PhoneGap plugin.

# License

The MIT License

Copyright (c) 2011 App47, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE