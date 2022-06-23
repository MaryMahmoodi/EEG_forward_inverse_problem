# EEG_forward_inverse_problem
![Uploading image.png…]()

![Uploading image.png…]()

![Uploading image.png…]()


1. EEG is the instant record of our brain electric activity through non-invasive conductive electrodes attached to the scalp.
EEG is the projection of activities of neural sources from the brain to the scalp.

2. In what way is EEG formed from neural source activities? We call it a forward problem and solve the Poisson's current-voltage equation in the conductive head volume in order to formulate the projection coefficients from neural source currents to the scalp electrode locations.
   The projection coefficients for each source and Ne electrodes are gathered in a matrix called lead-field (dimension: Ne*3). 3 refers to 3 cartesian diemensions. 

3. How can we localize the neural sources which are active at an instant of EEG map? We call it an inverse problem and solve it based on the forward problem and linear algebra rules.

## ❓The main questions is, why do we do the EEG inverse problem???

🎯The goal is to design a non-invasive and reliable source localization software for pre-surgical planning like seizure source localization or other BCI applications like movement trajectory tracking (classification) in source space.

❓Do we have such reliable "non-invasive" tools in clinics right now, or are they all research-purpose? 

# In this repository, I share a step-by-step presentation from neural current source modeling to forward/inverse formulas. 


The reader would go to https://github.com/MaryMahmoodi/3D-brain-mapping 
for downloading the code: main_mri2brainmap_allsteps.m regarding 
MRI segmentation,
surface mesh volume generation of head, skull, and brain,
EEG electrode registartion,
and brain-map.

This step comes before lead-field calculation. 

