# Project-Trash

# Inspiration :
<br>With the increasing population, the problem of waste generation and management is inevitable. With the rise of the fast life in big cities, the monitorization of waste saw its downfall due to a decrease in the number of municipality workers and irregularity of garbage collection trucks. Due to this, an abundance of waste is getting piled up in remote areas that are out of the knowledge scope of the municipality. Since these waste disposals are not treated, they have to lead to the spread of numerous diseases, sanitation, and environmental problems</br>

# Solution :
<br>Image Source = [ citizens capture the garbage images/images captured from a camera mounted public transport/ CCTV surveillance camera ], the images are stored in a firebase database along with the locational coordinates. The Resnet101 CNN model accesses the images and computes garbage volume, volume, type, and based on its location, a heat map is built using google map APIs for reference of Municipalities.</br>

<br>When images are stored in the online storage and its locational coordinates in the real-time database, the images are downloaded and passed on to ResNet 101 CNN architecture, which classifies the garbage present in the image and calculates the volume of the garbage present using a bounding box technique. the calculated information is updated back in the database. The collective garbage information (volume, type, and location) is then visualized on a google heat map with points proportional to the volume of garbage detected.</br>

<img src="Project Trash/garbage_visual.png" width=700 height=400>
<img src="Project Trash/explain.jpeg" width=700 height=400>


# Outcome :

<img src="Project Trash/detected_home.PNG" width=650 height=400>        
<img src="Project Trash/detected_3.PNG" width=650 height=400>
<img src="Project Trash/detetcted_2.PNG" width=650 height=400>
<img src="Project Trash/heat_map+garbage.png" width=500 height=400>
<img src="Project Trash/current_heat_map.PNG" width=500 height=400>



<br><b>[Video-Presentation]</b> = https://youtu.be/uv-k9zUQn6s</br>

<br><b>[PPT]</b> = https://drive.google.com/file/d/1CkE8XYlNXy-z-Ud9nj8H7kG4OoBc7Ced/view?usp=sharing</br>

<br><b>[Full Project]</b> =https://drive.google.com/drive/folders/1AxlNjnyiuLlEKgOFlXUEJaYqeil4-EZU?usp=sharing</br>


# Future : 
<br>The next phase of development for us would be the integration of Drones and implementing automated machinery for cleaning and collection purposes thus improving the sanitation standards.</br>
