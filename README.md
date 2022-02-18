# EEG_forward_inverse_problem
1. EEG is the instant record of our brain electric activity through non-invasive conductive electrodes attached to the scalp.
EEG is the projection of activities of neural sources from the brain to the scalp.

2. In what way is EEG formed from neural source activities? We call it a forward problem and solve the Poisson's current-electric field (-voltage gradient) equation in the conductive head volume to formulate the projection coefficients from neural source currents to the scalp electrode locations. 

3. How can we localize the neural source activities responsible for a specific EEG map? We call it an inverse problem and solve the EEG forward problem and linear algebra rules for that.

The main questions is, why do we do the inverse problem???
The goal is to design a non-invasive and reliable source localization software for pre-surgical planning.

Do we have such reliable "non-invasive" tools in clinics right now, or are they all research-purpose?  

In this repository, I will be sharing a step-by-step presentation from neural source concepts and modeling to forward/inverse formulas and codes. 

