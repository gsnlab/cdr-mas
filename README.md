# CDR-MAS
<br/>
Download the Inputs zip file and the source files of the NetLogo simulation. Inputs zip file contains the input shapefiles to create the NetLogo enviornment and the raster files (ascii format) to recreate the event in the NetLogo world. <br/>
<br/>
![Screenshot of the NetLogo world](https://github.com/gsnlab/cdr-mas/blob/master/NetLogo_Screen.PNG)

<br/>
Please note that the following set of parameters can be changed based on the scenario. For the specific customization to simulate the 2018 Montecito mudslide, the following values were used for the parameters.
<br/>
<h3>Parameters:</h3><br/><br/>

Interval: 5 Secs<br/>
Start: 0 Secs<br/>
Buffer-Zone (BZR): 4 patches<br/>
Max-SR: 4 patches <br/>
Max-VR: 3 patches<br/>
Max-WS: 4 kmph<br/>
Max-RS: 8 kmph<br/>
Max-DS: 25 kmph<br/>
Threshold-PI: 0.5<br/>
avg-occupants-per-house: 2.45<br/>
%-of-people-can-drive: 20%<br/>
%-of-age<18: 18%<br/>
%-of-age<=64-and-age>=18: 53%<br/>
%-of-age>=65: 29%<br/>
start-at-home: <The percentage of the agents start at a building location. Rest will be starting at random street locations.><br/>
-----------------------------------------------------------------<br/>
<b>bias-to-stay-put</b> of an agent will be set based on the below range<br/>
min-bias-to-stay-put: 50 <br/>
max-bias-to-stay-put: 100<br/>
-----------------------------------------------------------------<br/>
%-of-people-update: 100% <In the code the different update samples are generated for testing. Ex: 20%, 40%, 60%, 80%, 100%><br/>

<br/>
<h3>Execution:</h3>
<br/>
Install the NetLogo 5.3.1 and open the Main.nlogo.
<br/>
Press "Setup" button. Once the setup completes, press "Simulate" button. If the rendering takes longer time, disable "view updates".
<br/>
For each time step, the simulation creates output stream in a format as CSV.
