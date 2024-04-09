
mEDI measurements and  mEDI calculations using ALFA simulations for a period of 10 days in a typical office in Copenhagen Denmark. 

In total there are 1600 measurements and 1600 calculations with ALFA.

Parameters include: **Day &amp; Time**, **Daylight / Electric light**, **Direction of view**, **Position (distance from window)**, **Sky Type**.

Spectrometer used: GL SPECTIS 1.0 Touch + Flicker (mEDI was measured 120cm above the floor on a vertical plane)

Columns in dataset:

- DAY: Values 1 to 10

- TIME: 9 or 11 or 13 or 15 or 17 (each number corresponds to time eg 09.00 or 11.00)

- LIGHT: dl or dl+el (daylight or daylight+electric light)

- POSITION: 1,8 or 4 (1,8m or 4m distance from the window)

- DIRECTION: window or task (towards window or towards the task desk)

- mEDI: the value of the measured melanopic Equivalent Daylight Illuminance

- RECOMMENDATION: measured mEDI value above or below the threshold (mEDI >= 250)

- SKY TYPE: the sky type during the measurement - the same sky type was used for the simulation
  
- ALFA mEDI: the calculated value of melanopic Equivalent Daylight Illuminance using ALFA simulation

- ALFA RECOMMENDATION: calculated mEDI value above or below the threshold (mEDI >= 250)

Threshold suggested by Brown T.M. et al. “Recommendations for daytime, evening, and nighttime indoor light exposure to best...”; PLoS Biol 20(3): e3001571

Note: mEDI calculations at 17:00 in the "dl" case were not possible (due to low daylight), so mEDI values were set to 0

Preliminary colab notebook for analysing the dataset:
https://colab.research.google.com/drive/1NiZZ6bFU0yV6oZGEGGxpfDfemH1YWfOM?usp=sharing

Office and Positions of measurements/calculations (in green):

<img width="320" alt="image" src="https://github.com/gatrian/mEDI_measurements_ALFA_simulations/assets/159296200/97366110-8c29-445b-aa97-f953da2b7c66">
<img width="320" alt="image" src="https://github.com/gatrian/mEDI_measurements_ALFA_simulations/assets/159296200/a443307e-fdc6-4ec6-96b3-c8eddfbb0151">

Dataset made by Gabriele Zoochi and supervised by Georgios Triantafyllidis in Lighting Design Lab AAU (https://www.light.aau.dk/)


## Citation

If you find this project useful and wish to cite it in your work, please use the following BibTeX entry:

@misc{Zoochi2024,
title = {A database of mEDI measurements and  mEDI calculations using ALFA simulations},
author = {Zoochi, G and Triantafyllidis, G},
year = {2024},
publisher = {GitHub},
journal = {GitHub Repository},
howpublished = {\url{https://github.com/gatrian/mEDI_measurements_ALFA_simulations}},
}



