"# IT-3190-Art-Classification" 

This is my project for midterm score. The subject of the project is about art styles classification. There will be 5 classes: rococo, realism, surrealism, neoclassicism and baroque.
The structure of the project:  

<pre>
Project Root
|-- Data
|   |-- train
|   |-- test
|   |-- val
</pre>

<pre>
|-- Images
|   |-- a.png
</pre>

<pre>
|-- Zipfile
|   |-- a.zip
|   |-- ...
</pre>  

  If you use this project for reference purposes, you should create a folder named Zipfile, and it will contain all of .zip file of your workart style and can be download at https://github.com/asahi417/wikiart-image-dataset .  
  Thank you a lot for helping me crape all of this data.  
In the Art_Classify_CNN.ipynb, it will contain some comment code I used to extracted from the .zip files, split data and move them to Data folder. (The reason why I did it because I use a library from tensorflow, and it will helping me to labeling the data automatically).  
  First you have to create an empty folder Data, then uncomment the code in Art_Classify_CNN.ipynb and run to make a structure like above. Then you can run all the algorithms inside.
btw, I did it myself although the project is a group assignment (include writing the report :< )
