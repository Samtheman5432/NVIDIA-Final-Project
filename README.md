**Pushup identifier**

The AI model would recognize the correct bodily form of a good push up; being arms shoulder length apart and chest touching the floor. 

 

![add image description here](direct image link here)

## The Algorithm
The model works through 9 different cells. The first block sets the size of the images and starts the camera. The second block defines the TASK and CATEGORIES (good & bad pushups), as well as how many datasets you want to track. Using an iPython widget, the third cell sets up the collection mechanism to count your images and produce the user interface. The fifth cell uses the resnet-18 model and defines the neural network used. The sixth block allows the viewer to see the live webcam feed. 

## Running this project

1. ssh into your nano with the webcam already plugged in via your terminal (ssh nvidia@ipnet)
2. Load jupiter labs (./docker_dli_run.sh)
3. Ensure that the pushup folder with the classification interactive document, dataset.py and utils.py are inside the folder
4. Run all of the cells
5. Look at the widget while you go down on your pushup to see if you're doing a proper pushup

[View a video explanation here](video link)
