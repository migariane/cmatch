# cmatch: Tabulation of matched pairs in 1:1 case control study by exposure status

Matched case-control studies are a **classical Epidemiology** study design. Case-control study designs are used
to estimate the relative risk for a disease from a specific risk factor. The estimate is the odds ratio, which is 
a good estimate of the relative risk especially when the disease is rare. **cmatch** tabulates the number of 
matched pairs by **c** levels of an exposure variable. **cmatch** forms a **c x c** table of matched pairs 
by the exposure status of the case and the exposure status of the control. The data must be in the form of individual records.  

# Installation note    

To install **cmatch** directly from github you need to use a Stata module for installing Stata packages from GitHub, including previous releases of a package. You can install the latest version of the github command by executing the following code in your Stata session.  

**Note**: you need a Stata version greater or equal than 13.2, otherwise you can install the package manually downloading the files from the Github repository and placing it in your Stata ADO PERSONAL folder:   

    net install github, from("https://haghish.github.io/github/")  

    then, you can install cmatch simply using the following code in Stata:  

    github install migariane/cmatch  
   
        .which cmatch   
        .help cmatch   

# Authorship and Developer

Note: **cmatch** is an improved version of **match** originally developed by the EPM-304 (Adavance Statistical Methods in Epidemiology) distance Learning MSc programme in Epidemiology from the London School of Hygiene and Tropical Medicine, London, UK.  

Developer: Miguel Angel Luque-Fernandez, LSHTM, NCDE, Cancer Survival Group, London, U.K.      
Email: miguel-angel.luque@lshtm.ac.uk   

In case you have updates or changes that you would like to make, please send me a pull request.    
Alternatively, if you have any questions, please e-mail me.       
You can cite this repository as:    
Luque-Fernandez MA, (2017). Tabulation of matched pairs in 1:1 case control study by exposure status.   
GitHub repository, https://github.com/migariane/cmatch   
Miguel Angel Luque-Fernandez    
E-mail: miguel-angel.luque at lshtm.ac.uk  
Twitter @WATZILEI  

# Copyright
This software is distributed under the GPL-2 license.  


