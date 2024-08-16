## Med identifier

The AI model would recognize the difference between a claritin and advil medication. 
 

The following images show how the AI model can distinguish between claritin and advil: 
https://drive.google.com/file/d/1rpM3lPGjG6bh2bzsA8HY4EgWyeqWnuxo/view?usp=sharing
https://drive.google.com/file/d/1jOaIiM6poy0e-z7IQPmj7qxlLzkO6OKp/view?usp=sharing

## The Algorithm
The model works through 9 different cells. The first block sets the size of the images and starts the camera. The second block defines the TASK and CATEGORIES (Advil & Claritin), as well as how many datasets you want to track. Using an iPython widget, the third cell sets up the collection mechanism to count your images and produce the user interface. The fifth cell uses the resnet-18 model and defines the neural network used. The sixth block allows the viewer to see the live webcam feed. The final cell allows for all the widgets and the webcam feed to be displayed at once. 

## Running this project

1. ssh into your nano with the webcam already plugged in via your terminal (ssh nvidia@ipnet)
2. Load jupiter labs (./docker_dli_run.sh)
3. Ensure that the pushup folder with the classification interactive document, dataset.py and utils.py are inside the folder
4. Run all of the cells
5. Look at the widget while showing a medication (claritin or advil) to see which one it is. 

Video explanation: https://drive.google.com/file/d/1v-P_K2NYppeeyoZe1UTHBbXxxZ150PVc/view?usp=sharing
