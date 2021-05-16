# Smart glasses for blind             

- ##  Project Aims

  Face recognition for “Blind People” aims to develop the best and most comfortable way for interaction between the blind people and their    surrounding environment the main core of this project is to make the blind people's life equally compared to the normal paper life.


  ![legally-blind-person-dog-clouds-1200x630](https://user-images.githubusercontent.com/37952915/59888573-9d1a4e80-93c8-11e9-8462-926b4f2a2111.jpg)


 




-  ## What's the project? 

    In our proposed system, camera network is built by placing a camera at the blind's glasses.
    The cameras provide scene around faces of people and the objects of his surrounding , then inform blind user what and who is on the front of him.
In this process, matching-based face recognition is performed to find out the faces in the dataset (CSV file).

   
   
   
-  ##  How it work?

   1. First step: The user(blind) will click on the
  button.

   2. Second step: camera take an images when the user do an action” clicking on the button “ ,then microcontroller receives an images from the camera and resend it to the “cloud”.

   3. Third step: After the cloud load the model, the cloud normalizing image inputs: Data normalization is an important step which ensures that each input parameter (pixel, in this case) has a
similar data distribution. This makes convergence
faster while training the network. Data
normalization is done by subtracting the mean from
each pixel, and then dividing the result by the
standard deviation. The distribution of such data
would resemble a Gaussian curve centered at zero.
For image inputs we need the pixel numbers to be
positive, so we might choose to scale the normalized
data in the range [0,1] or [0, 255]. For our data-set
example, the following montage represents the
normalized data.>>Then Recognize face & detect object.>>Finally send output to microcontroller.

   4. Fourth step: microcontroller convert the output
“text” to sound when receives it from the “cloud”.
“This sound will be the output for the user, this is more
flexibility for the user.”

   !

