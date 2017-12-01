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

**6** Holl over the "CSV Output Input" click in the right arrow, drag your mouse to the "Turtle Generator", click on it and select "Main output of the step". 
 
![Main Output of the Step - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29002946-038776b2-7a84-11e7-82e1-36fae0b55674.png)
 
**7** Do the same to "Turtle Generator". It's going to be like:

![Turtle Transformation - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29002734-7947c596-7a7f-11e7-988f-8e50f0db2471.png)

**8** Open "CSV File Input" and selected the input file in your computer. In "Delimiter" configure to ";" or ",".

![CSV File Input - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29244002-f0cb0b88-7f83-11e7-8bb9-945f2e00aa6d.png)

**9** In "Text File Output" select the output file. In "Content" tab deselect "Separator" and "Header".

![Text Output File - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29244074-b38b8926-7f85-11e7-9594-65ce176876d1.png)

**10** In "TurtleGenerator Transformator" in "Definição e Descrição das Propriedades" each line select the column (property) its label and the uri that describes it (owl:sameAs) 

![CSV Properties definition - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29320784-b1dc4db0-81ae-11e7-826b-ba74783a6cbf.png)

**11** In "Prefixos" click in "Defaults" to add. You can add more if you want to. OBS: Remove empty lines in any tab.

![Prefixes - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29320944-3f62ecd4-81af-11e7-9be0-1b0b7f70c624.png)

**12** In "Descrição da unidade" put a description to each triples group. p.e. "Pesticide consumption by cultivation and year in Brazil".

![Unity Description - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29321151-e0729750-81af-11e7-80f1-75dabb73f141.png)

**13** Describe the hierarchys if exist. Click Ok.

![Hierarchys - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29321295-5c6759e0-81b0-11e7-953c-aa4c5849a661.png)

**14** Execute

![Execute - Turtle Generator Transformator](https://user-images.githubusercontent.com/8130000/29002755-f448538c-7a7f-11e7-8215-9e913e64ec57.png)

**15** Well done. Now your output is something like this: https://github.com/mayarahmo/TurtleGenerator_Kettle_Plugin/blob/master/output.txt

[output.txt](https://github.com/mayarahmo/TurtleGenerator_Kettle_Plugin/files/1225533/output.txt)



 
