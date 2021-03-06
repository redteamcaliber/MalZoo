# What is MalZoo?
MalZoo is a mass static malware analysis tool that collects information from malware and stores this in a Mongo database. It moves the malware samples to a repository directory based on the first 4 characters of the MD5 hash for reference.
It was build for an internship project to analyze sample sets of 50 G.B.+ (e.g. from [VirusShare](http://virusshare.com))
so correlations between malware samples can be found. This can aid as input for Threat Intelligence or help incident response to classify a sample.

A few use cases are:
* Use the collected information to get insights in malware (e.g. see most used packers),
* Gather intell of large open source malware repositories, 
* Visualize the results by exporting them to a data analysis tool (e.g. [Splunk](https://www.splunk.com))

## Information collected
See the Wiki [Collected data](https://github.com/nheijmans/MalZoo/wiki/Collected-data) page

# Installation
See the Wiki [Installation](https://github.com/nheijmans/MalZoo/wiki/Installation-and-configuration) page

# Idea's to make MalZoo better:  
* Support other file formats (e.g. PDF, APK, JAR, Office)
* ~~Directory monitor for live monitoring~~
* Add visualisation scripts (with the help of  matplotlib, numPy and Pandas)
* Add ClamAV module
* Add VirusTotal module

# Credit
Special thanks goes to the [Viper project](https://github.com/viper-framework/viper). I learned alot about how to automate malware analyse thanks to this project.
Also a big thanks to all the developers of the modules and software used and making it available for everyone.

# License
This project is released under the GPL 2.0 License. See the LICENSE for details.
