# Cartoonify-an-Image-
Do you miss your childhood? Yes, everyone does.! So today let’s head towards giving our pictures some cartoonic effects. 
This article is all about building a photo cartoonifyer using Python and OpenCV
Step 1: Importing the required modules
We will import the following modules:

CV2: Imported to use OpenCV for image processing
easygui: Imported to open a file box. It allows us to select any file from our system.
Numpy: Images are stored and processed as numbers. These are taken as arrays. We use NumPy to deal with arrays.
Imageio: Used to read the file which is chosen by file box using a path.
Matplotlib: This library is used for visualization and plotting. Thus, it is imported to form the plot of images.
OS: For OS interaction. Here, to read the path and save images to that path.

Step 2: Building a File Box to choose a particular file
In this step, we will build the main window of our application, where the buttons, labels, and images will reside. We also give it a title by title() function.

Step 3: How is an image stored?
Now, just think, how will a program read an image? For a computer, everything is just numbers. Thus, in the below code, we will convert our image into a numpy array.

Explanation:

Imread is a method in cv2 which is used to store images in the form of numbers. This helps us to perform operations according to our needs. 
The image is read as a numpy array, in which cell values depict R, G, and B values of a pixel.
