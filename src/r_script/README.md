# Machine Learning with PDI and R

1. Install R Script into PDI 7.0 EE and Windows 10 (64)

Steps:

* Install R and R Studio (use the latest version)
* Install rJava package using R Studio

```
install.packages('rJava')
```

* Set Environment variables for R:

Use the command below in R Studio in order to find out your R_HOME, R_LIBS_USER variables;

```
Sys.getenv("R_HOME")
Sys.getenv("R_LIBS_USER")

```

R_HOME -  C:\Program Files\R\R-3.0.1
R_LIBS_USER - C:\Program Files\R\R-3.0.1\library
Path - C:\Program Files\R\R-3.0.1\bin\i386


Install pentaho-r-plugin in /data-integration/plugins/steps folder  (find plugin in attachments)
Copy /rJava/jri/i386/jri.dll file (for 32 bit system) to /data-integration/libswt/win32
Restart PDI
In statistics step, you can find R script Executor step.
If you have any question you can ask me or else you can drop me email :


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

![Image 1](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r.PNG)

![Image 2](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r2.PNG)

![Image 3](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r3.PNG)

![Image 4](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r4.PNG)

![Image 5](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r5.PNG)

![Image 6](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r6.PNG)

![Image 7](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r7.PNG)

![Image 8](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r8.PNG)

![Image 9](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r9.PNG)

![Image 10](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r10.PNG)

![Image 11](https://github.com/caiomsouza/pdi_labs/blob/master/src/r_script/images/pdi_integration_with_r11.PNG)






