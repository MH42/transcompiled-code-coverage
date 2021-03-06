# TransCompiled Code Coverage (TC3)

### Overview
<span style="font-variant: small-caps">TransCompiledCodeCoverage</span> (<span style="font-variant: small-caps">TC3</span>) is a code coverage prototype offered for download as Eclipse-Plug-In. It calculates the code coverage of transcompiled cross-platform applications. By transcompiled applications, we understand applications that are written in a specifc source programming language before they are compiled in another target language to meet special requirements. The application in the target language might run in a completely different environment. That is, the application is platform independent (also called cross- or multi-platform).

### Features
The main features of <span style="font-variant: small-caps">TC3</span> are:
- Calculation of code coverage for any kind of test (unit, integration or ui/web test) 
- Tests can be developed with your favorite test framework (e.g. JUnit, TestNG, Selenium, TestComplete)
- Support of transcompiled web applications (currently web applications based on Google Web Toolkit) and common desktop applications written in Java

In the evaluation of <span style="font-variant: small-caps">TC3</span>, we have used the open source mail client [Hupa](http://james.apache.org/hupa/index.html). See the [webtests](./webtests)-directory for code coverage results and webtests. In order to demonstrate the usability in other applications, we have additionally evaluated our tool using standard desktop applications. In this area, researchers often used
the ["Software-artifact Infrastructure Repository (SIR)"](http://sir.unl.edu/). (See also ["Supporting Controlled Experimentation with Hyunsook et al.: Testing Techniques: An Infrastructure and its Potential Impact"](http://dx.doi.org/10.1007/s10664-005-3861-2).) Thereof, we have used the latest version of JMeter, JTopas and Xml-Security. 
Unfortunately, we do not have the permission to publish the source code of these tools. For this reason, please download the sources from the ["Software-artifact Infrastructure Repository (SIR)"](http://sir.unl.edu/).

### Screenshots

<img src="Code Coverage Results.png" width="600px" alt="TC3"/>
<img src="coverage.png" width="600px" alt="HTML-Code Coverage Report"/>
