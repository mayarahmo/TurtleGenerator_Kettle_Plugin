# Turtle Generator Kettle Plugin 
> Kettleplugin to write a RDF Turtle file from a CSV file.
Turtle Generator is a plugin developed from the DataCube Transformator plugin: https://github.com/mayarahmo/DataCube_Kettle_Plugin

To run a transformation do the following:
--- 
#**1** Download the dataintegration4.1, Kettle modified with the TurtleGenerator
or copy the plugin folder (plugins/steps/TurtleTransformator) into your Kettle plugin folder (this procediment is not garanteed).

**2** Open the Kette (Spoon) folder and execute spoon.bat.  

**3** Go to file > new > Transformation.

**4** In Design tab go to "LinkedDataBR" and drag the "Turtle Generator" to the Transformation field.

![Dragging Turtle Generator into the Transformation](https://user-images.githubusercontent.com/8130000/29002728-6d692260-7a7f-11e7-9135-d5b2971da22f.png)

**5** In input folder select "CSV file input" and drag it to the transformation field. Do the same to the "Text file Output" inside the "Output" folder.

![Drag steps into the Transformation](https://user-images.githubusercontent.com/8130000/29002731-74ae7822-7a7f-11e7-8ec4-7ae45fdf8d61.png)

**6** Mouse over the "CSV Output Input" click in the right arrow, drag your mouse to the "Turtle Generator" and click on it and select "Main output of the step". 
 
![Main Output of the Step](https://user-images.githubusercontent.com/8130000/29002946-038776b2-7a84-11e7-82e1-36fae0b55674.png)
 
**7** Do the same to the "Input CSV File". It's going to be like:

![Turtle Transformation](https://user-images.githubusercontent.com/8130000/29002734-7947c596-7a7f-11e7-988f-8e50f0db2471.png)
 
