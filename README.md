# project-hackpad-rps-project-waow

Hello everyone! This is the landing page(i think thats what its called) for my macropad!

Project RPS

A Rock, Paper, Scissors CPU bot to play against for never-ending fun, all in a package that can teach kids STEM concepts in an easy-to-understand environment!

Each folder in the repo above has all the files for the project such as the design, PCB itself, and any and all firmware.
Major note is that you need an additional two screws for the project in addition to the Hackpad kit!
If there are any bugs or issues that you find, please let me know so I can fix them lol :D - email me at spyderbotz25@gmail.com
Below are the images of all the parts and documents and I will also add a step-by-step build guide in the future

<img width="682" height="386" alt="image" src="https://github.com/user-attachments/assets/9fc48bf2-7bfc-45cf-87d9-d0ef0e491d3b" />

A live model of the project that can be downloaded and seen being updated in real time:[https://cad.onshape.com/documents/c20fb2989cfb41f0dac3f499/w/c5f5d0cbd9102e8367040c72/e/38d4e4337ab350df89cf3e28?renderMode=0&uiState=6a447053a9e76bdc7db3e8f7
](url)

<img width="1010" height="742" alt="image" src="https://github.com/user-attachments/assets/0d09d938-efec-43c2-aaa7-88cb3b619640" />
<img width="977" height="627" alt="image" src="https://github.com/user-attachments/assets/6e3cdb6c-e53f-4c73-ad30-f62702383b8a" />
<img width="341" height="547" alt="image" src="https://github.com/user-attachments/assets/3f994b62-883c-4bc9-9983-da8de62d2205" />
<img width="625" height="865" alt="image" src="https://github.com/user-attachments/assets/bea6761c-791d-46b8-a5f3-f72425cd0562" />
<img width="531" height="552" alt="image" src="https://github.com/user-attachments/assets/dbd1fb27-8932-475d-98e3-61425370a0d4" />

IMPORTANT:BELOW IS THE PARTS LIST FOR THE PROJECT I HAVE DESIGNED READ IT CAREFULLY
- 1 Seeed XIAO RP2040
- 2 6 pin male headers
- 1 4 pin male header
- 3x MX-Style switches
- 1x 0.91 inch OLED display
- 3x white blank DSA keycaps
- 2x SK6812 MINI-E LEDs
- 6x M3x16mm screws
- 2x M3x8mm screws
- 6x M3x5mx4mm heatset inserts
- Soldering Iron(Type doesn't mattter for the most part)

Quick Start guide:

I am going to try my best to make sure that all of you will be able to set this beautiful game up as fast as possible lol

Important! - Before beginning, ensure you have gloves for heat protection. You do NOT want molten metal getting on your hands and causing third or second-degree burns.

Additional notes - This build is not meant for total amateurs. If you are under the age of 12, seek help from an adult for any steps that may involve heat or precise control.

First step: Order the PCB using the "production" folder's files given through JLCPCB or whatever PCB vendor you may choose

Second Step: Download all the files in the "CAD" folder and upload them to the 3D printing slicer of your choice to prep them for printing, or upload them to Hack Club's Printing Legion to get started

Third Step: Order any other miscellaneous parts that you don't have access to from the parts list provided

Fourth Step: Upon the arrival of all listed parts, first solder both the microcontroller and OLED panel to their respective pin headers and solder the LEDs to their respective positions on the PCB as displayed in the CAD model.

Fifth Step: With great control so as not to damage the PCB(I find placing it on a nice cardboard box does the trick), solder the microcontroller onto the board the EXACT same way it's displayed in the CAD model

Sixth Step: Take the 2 M3x8mm screws and put them in the designated screw holes. Turn the PCB upside down(but still hold it in your hand!) and place the standoffs onto the screws.

Seventh Step: This is one of the MOST dangerous parts of the whole build, so ensure you have those safety gloves on nice and tight and keep a steady hand. You must use your soldering iron to heat up the heatset inserts purchased, and then you must press them into the 3D printed base as specifically shown in the CAD

Eighth step: Take your newly assembled RPS PCB unit and assemble the remaining parts according to the CAD model. I find that starting with the base and working up tends to work out best.

Ninth step: We are almost ready to play! Simply take your personal device of choice(a phone, laptop, desktop machine - it doesn't matter!), and upload the firmware(not yet here sadly😢). After this, you are ready to play with your new RPS toy!

To play, the only requirement is some form of USB-C power to the module. Aside from this, there are no other requirements!

The way the project is built to function is with the microcontroller receiving the inputs from the user, which is meant to be a choice for whether they want to play rock, paper, or scissors. The OLED panel then receives inputs from the microcontroller and displays the results. This can differ based on whether or not the user won, lost, or tied.

Huge thanks to the Orpheuspad devs, those guys really contributed to the good structure of this project and to my understanding of PCBs. I also should credit the Kirby artists because I kind of copied an image they made so shout out to them :D
