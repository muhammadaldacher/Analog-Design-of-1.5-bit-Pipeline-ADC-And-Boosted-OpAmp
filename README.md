# Analog-Design-of-1.5-bit-Pipeline-ADC-And-Boosted-OpAmp
This project is about designing a 1.5-bit stage Pipeline ADC & a Boosted OpAmp required for its MDAC.

# Whole System:
![wh](https://user-images.githubusercontent.com/27668656/61588141-521c6400-ab4b-11e9-82ce-309ce58dc03a.png)<br/><br/>
Schematics:<br/>
![wh](https://user-images.githubusercontent.com/27668656/61588150-6fe9c900-ab4b-11e9-98ff-0a2cd4ced414.png)<br/>

## 1) Comparator:
![1_Comp](https://user-images.githubusercontent.com/27668656/61586477-d827b300-ab29-11e9-84a9-81ca74f18817.png)<br/>
Refer to: https://github.com/muhammadaldacher/Analog-Design-of-Dynamic-Comparator <br/>

## 2) Switches:
![2_Switches](https://user-images.githubusercontent.com/27668656/61588164-9d367700-ab4b-11e9-8668-2014b8ef92a7.png)
Refer to: https://github.com/muhammadaldacher/Analog-Design-of-Bootstrapped-Switch <br/>

## 3) Sub-ADC Logic:
![3_SubADC](https://user-images.githubusercontent.com/27668656/61588170-b5a69180-ab4b-11e9-934e-bc0490992db4.png)

## 4) OpAmp Design:
### ==> Fully-Differential Gain-Boosted Telescopic OpAmp: (Main OpAmp)
![wh](https://user-images.githubusercontent.com/27668656/61592759-3e452200-ab8c-11e9-89b4-f8b3f8870c0d.png)

#### -> NMOS-input, Single Ended Output, Folded Cascode OpAmp:
![nmos](https://user-images.githubusercontent.com/27668656/61592866-87e23c80-ab8d-11e9-9a8c-14c19f1b5831.png)
#### -> PMOS-input, Single Ended Output, Folded Cascode OpAmp:
![pmos](https://user-images.githubusercontent.com/27668656/61592896-caa41480-ab8d-11e9-8afb-7b28df8bf489.png)

##### * Testbench for Single-Ended-Output OpAmps:
![se_testbench](https://user-images.githubusercontent.com/27668656/61592936-30909c00-ab8e-11e9-8404-d16333184b8e.png)
##### * Testbench for Boosted (Fully-Differential) OpAmp:
![se_testbench](https://user-images.githubusercontent.com/27668656/61592954-66358500-ab8e-11e9-827f-2b667ea8251f.png)
##### >> Bode Plots of the Boosted OpAmp:
![gp](https://user-images.githubusercontent.com/27668656/61593213-97638480-ab91-11e9-9bf9-9297ecf66588.png)

### Whole System Simulation:
![gp](https://user-images.githubusercontent.com/27668656/61593345-3dfc5500-ab93-11e9-95a5-59b8842a0916.png)<br/>
![gp](https://user-images.githubusercontent.com/27668656/61593401-e0b4d380-ab93-11e9-9f54-dcf0525a0be7.png)

*****************
### References:
More on OpAmp Design:<br/>
-> https://github.com/muhammadaldacher/Analog-Design-of-1.5-bit-Pipeline-ADC-And-Boosted-OpAmp/blob/master/B-%20Design%20of%20OpAmp%20for%20MDAC/Notes_OPAMP_for_ADC.pdf <br/>
-> https://github.com/muhammadaldacher/Analog-Design-of-1.5-bit-Pipeline-ADC-And-Boosted-OpAmp/blob/master/B-%20Design%20of%20OpAmp%20for%20MDAC/Basic%20OpAmp%20Design%20and%20Compensation.pdf <br/>
Tutorial Videos on OpAmp Design on Virtuoso Cadence:<br/>
-> https://www.youtube.com/playlist?list=PLK2eyR1C9gjoBp61ZDvz6Zdd_6Hu7vZTz <br/>
My project on google drive:<br/>
https://drive.google.com/drive/folders/1W9ip4MpMZNf3IQsoFQkhgg6QaUya4Yp4 <br/>
EE288 Lecture Notes:<br/>
https://drive.google.com/drive/folders/12Qqfw_TX1i7dvVVYXksaSdHV4gth1OD5 <br/>
Some papers on Gain-Boosted Opamps: <br/>
https://ieeexplore.ieee.org/document/1635302 <br/>
https://ieeexplore.ieee.org/document/4266730 <br/>
