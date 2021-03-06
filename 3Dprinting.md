# 3D PRINTING

This is where you can connect to the quote " You can make almost anything here ".

>What is 3D printing?

The action or process of making a physical object from a three-dimensional digital model, typically by laying down many thin layers of a material in succession.

## Software Required:

A few software applications were installed which would be useful in the fabrication lab. Some of the softwares that were told to be installed were:

* AutoCAD ( Ex. : EagleCAD, Rhinoceros)
It is used for creating blueprints for our designs in mind.

![FABLAB class](/images/autocad1.png)

* Cura 
It is a 3D printing slicing application. This is the software that is used to turn our design image into a format that can be used by the 3D printer to print the corresponding 3D object. 
![FABLAB class](/images/curascreen1.png)

###### A Guide to use the above software

We learnt how to use the AutoCAD software in order to make blueprints for our designs in mind. We used Rhinoceros Corporate (version for 64-bit OS).
First of all 2D shapes can be constructed easily by the given tools. In order to convert a 2D image to 3D image we use the following command:

<B> COMMAND : </B> 

* ExtrudeCrv 

The required dimensions can be given.

Next, in order to create a solid object we use the command: 

<B> COMMAND : </B>

* Cap

In order to subract portions of the object we use the command : 

<B> COMMAND : </B> 

* BooleanDifference

The appropriate surfaces to be subtracted and those to be kept can be selected according to our choice.

Once the designed object is ready we converted it into STL format through the following steps:

* File
 * Export selected
   * STL format
     > Name the file and save it.
  
 Next we use the CURA software that has been installed earlier and then set it accordingly in order to print it using the 3D printer.
 We made the following settings.
 Profile : Fine
 Material : PLA
 Infill : 50%
 Support : Use 
 
Then click Save to removable drive. Now the image is ready to be fed to the 3D printer in order to print it by inserting the memory card consisting the image.


## My Assignment

I tried to design a ear phone holder using AutoCad and then 3D prited it using the 3D printer.


![3d printing](/images/imagestwo/3d1.jpg.png)                                                             
![3d printing](/images/imagestwo/3d2.jpg)

![3d printing](/images/imagestwo/3d3.jpg)

## How to 3D print ?

* STEP 1

First of all you need to design the prototype using any of the appropriate softwares such as Rhinoceros, Adobe Illustrator, Solidworks etc. Why do you have to use the specific softwares ? Well you are going to turn your 2D design to a  3D model , Aren't you? This 2D image must be readable by the 3D printer. This format is the Gcode. 

So the first step is to design the image using any  appropriate software and then save the image in stl format.

>What is G-code?
GCode is the generic name for a control language for CNC (or Reprap) machines. It is a way for you to tell the machine to move to various points at a desired speed, control the spindle speed, turn on and off various coolants, and all sorts of other things. It is fairly standard, and is a useful tool.

Here, I'll show you my design for the ear phone holder using Rhinoceros.
You can download the file in STL format [here](http://liyanafzl.github.io/headset_al_stl.stl)

![3d printing](/images/imagestwo/3dscreen1.png)

After you are done designing, save the file in STL format.

![3d printing](/images/imagestwo/3dscreen2.png)


Now you need to convert this STL file to Gcode. This can be done using the Cura software.

The Cura tell us how much time it would take to print the object. Also we can specify the quality needed for the object ( 20%, 50%, 100% etc) depending on the strength required for the design. Supports need to be generated if necessary. That needs to be specified. After printing , these supports can be removed easily.

![3d printing](/images/imagestwo/3dscreen3.png)

![3d printing](/images/imagestwo/3dscreen4.png)

Now your Gcode file is ready to be fed to the 3D printer. Save it in the memory card that can be inserted into the 3D printer.

![3d printing](/images/imagestwo/3d4.jpg)

Now just rotate the button and select the file.

![3d printing](/images/imagestwo/3d5.jpg)

Print : to select the file from the memory card
Material : to specify what kind of material is loaded into the machine.
Maintainance: to change the setting on the machine regarding nozzle size, power used etc.

After the settings are done, the machine takes a while to start printing because the material has to get heated. Then you can see the 3D printer printing your 2D design layer by layer.

![3d printing](/images/3dprinting.gif)




## File available for download

[Design for ear phone holder ( in STL File format )](http://liyanafzl.github.io/headset_al_stl.stl)





