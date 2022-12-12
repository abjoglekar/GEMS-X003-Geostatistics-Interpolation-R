<img src="images/GEMS Informatics Learning.png" width=600 alt="GEMS Learning Logo" title="GEMS Learning" />

# X003.5 Geostatistics and Interpolation in R

This course is designed for those who are interested in collecting, creating, processing, and interpolating geostatistical data. Through this course, you will learn variogram analysis and kriging methods to model and analyze spatial data based on information collected from sampled locations. You will have the opportunity to immediately practice your new skills via hands-on exercises focused on agri-food applications throughout the 2.5-hour course. 

The course will be delivered via a Jupyter Notebook hosted on the GEMS Informatics Platform. You do not need to have R or RStudio installed on your machine to participate.

## Prerequisites: 
- Access to the internet
- A [GEMS Platform](https://gems.agroinformatics.org/webui/#) user account
- GEMSx003.0  

## Initial Setup
1. Login to GEMS Platform at https://gems.agroinformatics.org/
    - GEMS Platform uses Globus to authenticate your account, so if your institution is already linked to Globus (for example, University of Minnesota and many other universities), you can search and select your institution from the list and use your institutional account to log into GEMS Platform. Alternatively, you can log in using Google or ORCID iD, or create  your own Globus account to log in.   

2. Once logged in, click `Analyze > JupyterLab` from the homepage

3. Open a bash terminal by clicking 'Terminal' icon in the Launcher **OR** by clicking `File > New > Terminal`

4. If the directories `classes\GEMSX003` were not created before, create directories for this class in the bash terminal using the following four commands  
    ```shell
    mkdir classes  
    cd classes  
    mkdir GEMSX003  
    cd GEMSX003
    ```  
    If these directories already exist, use the following commands to change to this directory
    ```shell
    cd classes
    cd GEMSX003
    ```
    
    
## Lecture: Geostatistics and Interpolation
1. Navigate to your `GEMSX003` directory using the following commands:
    ```shell
    cd classes
    cd GEMSX003
    ```
2. Clone the git repository for this week's lecture  
    ```shell
    git clone https://github.com/abjoglekar/GEMS-X003-Geostatistics-Interpolation-R.git
    ```
3. In your JupyterLab environment, open the `GEMS-X003-Geostatistics-Interpolation-R` directory and then open the `x003_Module5_Geostats.ipynb` Jupyter Notebook to follow along throughout the class 

