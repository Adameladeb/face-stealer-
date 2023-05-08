Capture Camera 📷

Capture Camera is a simple web application that allows users to capture images using their device's camera and send them to a Discord webhook. This can be used to scare kids :D.

I highly recommend index3.html

How it Works

Capture Camera uses the MediaDevices.getUserMedia() method to access the user's camera and capture images. The captured images are then sent to a specified Discord webhook using the XMLHttpRequest() method.

How to Use

To use Capture Camera:

Click on the "Allow Camera Access" button to allow the application to access your camera.
Click on the camera icon to capture an image.
The captured image will be sent to the specified Discord webhook, and a confirmation message will be displayed on the screen.
Customization

Capture Camera is highly customizable and can be easily adapted to your needs. Some possible customizations include:

Changing the Discord webhook URL.
Changing the name of the captured image file.
Adding additional data to the webhook payload, such as a username or a message.
To customize Capture Camera, you can modify the captureImage() function in the JavaScript code.

Credits

Capture Camera was created by Adam El Adeb W乇乇り#9249.
