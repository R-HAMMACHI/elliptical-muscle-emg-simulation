-----------------------------------------------
# Description:
-----------------------------------------------
This is a MATLAB model that simulates surface EMG signals detected above an elliptical muscle, within a cylindrical limb containing bone, muscle, fat, and skin tissues.
Additionally it is used to model the motor unit (MU) recruitment and firing rate. 
The model’s basic parameters are described in the following research article: ( https://doi.org/10.1016/j.jelekin.2016.12.006 )

- The Zip. file comprises of 2 folders; one for circular electrode simulation and the other for rectangular electrode.
- Inside each folder, there is two other sub-folders for each firing strategy. 
- Other parameters (such as the used spatial filter, recruitment thresholds RR, peak firing rate PFR, inter-electrode distances IED, MVC levels, ...  ) can be manually adjusted as desired;
    e.g:  Filters configurations and IED can be adjusted in SF function (lines 47 and 60),
          PFR in cercles (line 19),
          RR in ellipse (line 36),
          Signals are generated in all MVC levels automatically but can be specified using Et2 variable in ellipse (line 38),
          ... etc.  
----------------------------------------------
# How to use ?
----------------------------------------------
- Download the zip. file and extract the files.
- Open your MATLAB program (preferably MATLAB R2020a)
- Scroll into the extracted folders, adjust the parameters as needed and run the FR1 or FR3 files for generating the signals (You need to modify the signal name accordingly).
----------------------------------------------
The descriptions and comments in the code are written in French !
