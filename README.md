# Customizing-Extrusion-based-3D-Printing

Additive and Subtractive Processes in Custom Manufacturing  Graduate Level Project:
In this project, my team and I designed a system to 3D print silicone rubber. The material chosen is Dragon Skin 10 Fast from Smooth-on (https://www.smooth-on.com/products/dragon-skin-10- fast/), which is a two-part curing system. We learned how to control the extrusion rate and were tasked to find a proper printing speed for a given extrusion rate. Two sets of experiments were conducted.

![image](https://github.com/carlos-navarro-naranjo-backup-account/Customizing-Extrusion-based-3D-Printing/assets/134238682/3b737042-9bfa-4c9c-9b81-87aac07c1109)


# Problem Statement & Goal:
# Extrusion Rate
Silicone resin is in liquid form, so the extrusion is controlled by pressure in a syringe. In the experiment, a 50 mL plastic syringe, and a 14 Gauge needle (1.55 mm ID and 2.1 mm OD) were used. The needle is about 20 mm long. The mass flow rate was measured at different pressures, and each pressure was repeated four times (5 runs total). 

![image](https://github.com/carlos-navarro-naranjo-backup-account/Customizing-Extrusion-based-3D-Printing/assets/134238682/2afc507c-432a-411c-8da1-148a0e0ff4ef)


a.	We made a plot showing the average flow velocity (mm/s) vs. the gauge pressure (psig).
b.	Produced a theoretical curve on the same plot. 
c.	Explained the reasons for discrepancies. 


# Printing Quality

![image](https://github.com/carlos-navarro-naranjo-backup-account/Customizing-Extrusion-based-3D-Printing/assets/134238682/2ff6c681-72a7-4359-8162-51ac9d7bca75)

We determine a proper printing speed for a given flow velocity. In theory, the printing speed should be the same as the flow velocity to avoid excessive or lack of material deposited on the platform. However, such a relationship may not hold true for liquid resin. In this experiment, a constant pressure (40 psig) was used to observe the printing quality at various printing speeds from below to above the flow velocity. The printed line was measured with its width, as the results are shown below. Each test was repeated four times (5 runs). 
a. We plotted the width (of printed line) vs. printing velocity. 
b. Assuming a continuous line, I developed a physical model to predict the line width based on the printing velocity. Found the corresponding flow velocity for 40 psig.
c. Explained the reasons for discrepancies. 

# System Design

![image](https://github.com/carlos-navarro-naranjo-backup-account/Customizing-Extrusion-based-3D-Printing/assets/134238682/eab1f94c-1b9e-4a6f-a6ed-c5db93a3090c)

At this point, we have a set of good models (or data) to control extrusion. However, there is a lot more to do to customize the process. We conducted a literature review and summarized other aspects that determine the “printability” of a material, and then discussed whether printing this material is feasible. 
