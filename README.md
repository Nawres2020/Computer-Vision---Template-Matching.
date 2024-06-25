# Computer-Vision---Template-Matching.
Computer Vision - Template Matching
In this example, we will introduce a simple code snippet using OpenCV in Python for template matching. This technique verifies if a given template exists within the main image.
To understand the code, check my [https://medium.com/@naouresatidel.hamrouni/computer-vision-template-matching-ad3218d0aa7a](URL)

First of all, what is template matching?
Template matching is a technique in computer vision for identifying parts of an image that match a predefined template. It is robust enough to handle variations in orientation and lighting. It is widely applied in medical image analysis, vehicle tracking, robotics, and manufacturing and leverages distinctive features for object identification. However, its performance can be limited by the processing power available, particularly with large or complex templates.


To better understand this, let us dig into today's example:

First of all, this is the main image:

![main_image](https://github.com/Nawres2020/Computer-Vision---Template-Matching./assets/74150824/4b59cd4a-cb0f-44e8-b53f-de1839961145)

We are trying to identify if this template exists or not inside the main image:


![template](https://github.com/Nawres2020/Computer-Vision---Template-Matching./assets/74150824/1e610528-ad84-4ee8-8340-1d41f3395097)




![resultat](https://github.com/Nawres2020/Computer-Vision---Template-Matching./assets/74150824/93d2e673-ca69-461c-9389-f29ad20ca0c1)

The resulting image consists of two parts side by side:

First the Matching Result:

This section shows the result of the template-matching process. The image is a blurred grayscale representation where brighter areas indicate a higher correlation between the template and the main image. The brightest spot in the image represents the location with the highest match score, suggesting where the template is most likely found within the main image.
Second The Detected Point:

This section shows the main image with a rectangle drawn around the detected region where the template was found. The rectangle highlights the part of the main image that best matches the template. In this case, it appears to highlight a wolf's head, indicating that the template was successfully matched and located within the main image.
