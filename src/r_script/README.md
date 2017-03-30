# Machine Learning with PDI and R

1. Install R Script into PDI 7.0 EE and Windows 10 (64)




http://biwithui.blogspot.co.uk/2015/05/r-integration-with-pdi.html


C:\Users\csouza\Documents\R\win-library\3.3\rJava


Hey Guys,

Here i would like to explain the How to integrated R with PDI .

Steps:
Install R 3.0.1
Install rJava package along with REngine
Set Environment variables for R:
R_HOME -  C:\Program Files\R\R-3.0.1
R_LIBS_USER - C:\Program Files\R\R-3.0.1\library
Path - C:\Program Files\R\R-3.0.1\bin\i386
Install pentaho-r-plugin in /data-integration/plugins/steps folder  (find plugin in attachments)
Copy /rJava/jri/i386/jri.dll file (for 32 bit system) to /data-integration/libswt/win32
Restart PDI
In statistics step, you can find R script Executor step.
If you have any question you can ask me or else you can drop me email :
 
Sumit Bansal
BI Developer


C:\Pentaho\pentaho-ee-7.0.0.2-52-x64\design-tools\data-integration\libswt\win64

PATH
C:\Program Files\R\R-3.3.1\bin\x64

setwd("~/")


C:\Users\csouza\Documents\R\win-library\3.3\rJava\jri\x64









