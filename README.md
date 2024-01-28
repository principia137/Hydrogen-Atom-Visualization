# Wave function table

 <img width="318" alt="image" src="https://github.com/principia137/Hydrogen-Atom-Visualization/assets/62958764/f2be4858-6833-4fa7-b265-8c20e8ac8699">

# Probability Distribution

(set $a_0=1$)

## Radial Function($r^2 R(r)^2$) {#radial-functionr2-rr2 .unnumbered}

![for some n=1,2 , l=0,1](./img/Radial.PNG){width="13cm"}

## Spherical Harmonic Function($Y(\theta,\phi)^2$) {#spherical-harmonic-functionythetaphi2 .unnumbered}

$\leftarrow$ less probability    high probability $\rightarrow$

  --------------------------------------- --------------------------------------- ---------------------------------------
   ![image](./img/SH00.PNG){width="4.4cm"}   ![image](./img/SH10.PNG){width="4.4cm"}   ![image](./img/SH11.PNG){width="4.4cm"}
                $l=0, m=0$                              $l=1, m=0$                            $l=1, m=1, -1$
                                                                                  
   ![image](./img/SH20.PNG){width="4.4cm"}   ![image](./img/SH21.PNG){width="4.4cm"}   ![image](./img/SH22.PNG){width="4.4cm"}
                $l=2, m=0$                            $l=2, m=1, -1$                          $l=2, m=2, -2$
  --------------------------------------- --------------------------------------- ---------------------------------------

  --------------------------------------- --------------------------------------- ---------------------------------------
   ![image](./img/SH30.PNG){width="4.4cm"}   ![image](./img/SH31.PNG){width="4.4cm"}   ![image](./img/SH32.PNG){width="4.4cm"}
                $l=3, m=0$                            $l=3, m=1, -1$                          $l=3, m=2, -2$
                                                                                  
   ![image](./img/SH33.PNG){width="4.4cm"}                                          
              $l=3, m=3, -3$                                                      
  --------------------------------------- --------------------------------------- ---------------------------------------

  : Spherical Harmonics

## Wave Function($\psi(r,\theta,\phi)^2=R(r)^2Y(\theta,\phi)^2$) {#wave-functionpsirthetaphi2rr2ythetaphi2 .unnumbered}

$\leftarrow$ less probability    high probability $\rightarrow$

  -------------------------------------------- -------------------------------------------- --------------------------------------------
   ![image](./img/Hydrogen100.PNG){width="5cm"}   ![image](./img/Hydrogen200.PNG){width="5cm"}   ![image](./img/Hydrogen210.PNG){width="5cm"}
                $n=1, l=0, m=0$                              $n=2, l=0, m=0$                              $n=2, l=1, m=0$
                                                                                            
   ![image](./img/Hydrogen211.PNG){width="5cm"}                                               
              $n=2, l=1, m=1, -1$                                                           
  -------------------------------------------- -------------------------------------------- --------------------------------------------

  -------------------------------------------- -------------------------------------------- --------------------------------------------
   ![image](./img/Hydrogen300.PNG){width="5cm"}   ![image](./img/Hydrogen310.PNG){width="5cm"}   ![image](./img/Hydrogen311.PNG){width="5cm"}
                $n=3, l=0, m=0$                              $n=3, l=1, m=0$                            $n=3, l=1, m=1, -1$
   ![image](./img/Hydrogen320.PNG){width="5cm"}   ![image](./img/Hydrogen321.PNG){width="5cm"}   ![image](./img/Hydrogen322.PNG){width="5cm"}
                $n=3, l=2, m=0$                            $n=3, l=2, m=1, -1$                          $n=3, l=2, m=2, -2$
  -------------------------------------------- -------------------------------------------- --------------------------------------------

  : Hydrogen Atom Orbitals

# MATHEMATICA Code

## DensityPlot3D {#densityplot3d .unnumbered}

![image](./img/DensityPlot3D.PNG){width="15cm"}

## Reference {#reference .unnumbered}

<https://reference.wolfram.com/language/ref/DensityPlot3D.html>
