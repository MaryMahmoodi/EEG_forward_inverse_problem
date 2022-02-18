# EEG_forward_inverse_problem
1. EEG is the instant record of our brain electric activity through non-invasive conductive electrodes attached to the scalp.
EEG is the projection of activities of neural sources from the brain to the scalp.

2. In what way is EEG formed from neural source activities? We call it a forward problem and solve the poisson's current-electric field (-voltage gradient) equation in the head conductive volume to formulate the projection coefficients from neural source currents to the scalp electrode locations. 

3. How can we localize the neural source activities responsible for a specific EEG map? We call it an inverse problem and solve it based on the EEG forward problem and linear algebra rules.

Why do we do the inverse problem???!!!
The goal is to design a non-invasive and reliable source localization software for pre-surgical planning.
Do we have such reliable non-invasive tools right now, or are they all research-purpose software?  

In this repository, I will be sharing my findings regarding EEG forward/inverse problems from neural concepts and model to formulas.   
