# Video Reconstruction

Here is a demo to recreate the animation using an Autoencoder, which can predict the next frame given the current frame.

The animation.mp4 is the original video and generated_video.mp4 is the reconstruction.

Original video:

![](demostration/original_video.gif)

Reconstruction:

![](demostration/reconstructed_video.gif)

Here is a step-by-step implementation:

    Step 1: Extract Frames and Convert to Grayscale
        First, extract frames from the MP4 file and convert them to grayscale using OpenCV.
        
    Step 2: Prepare the Dataset
        Next, prepare the dataset by creating pairs of consecutive frames.
        
    Step 3: Build the Autoencoder
    
    Step 4: Train the NN
    
    Step 5: Generate the Animation

    Step 6: Fine tune the Model and Hyperparameter
