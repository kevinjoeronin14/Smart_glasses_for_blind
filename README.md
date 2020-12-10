# Smart glasses for blind             

- ##  Project Aims

  Face recognition for “Blind People” aims to develop the best and most comfortable way for interaction between the blind people and their    surrounding environment the main core of this project is to make the blind people's life equally compared to the normal paper life.


  ![legally-blind-person-dog-clouds-1200x630](https://user-images.githubusercontent.com/37952915/59888573-9d1a4e80-93c8-11e9-8462-926b4f2a2111.jpg)


 




-  ## What's the project? 

    In our proposed system, camera network is built by placing a camera at the blind's glasses.
    The cameras provide scene around faces of people and the objects of his surrounding , then inform blind user what and who is on the front of him.
In this process, matching-based face recognition is performed to find out the faces in the dataset (CSV file).

   
   ![power supply](https://user-images.githubusercontent.com/37952915/59888392-ba9ae880-93c7-11e9-93a0-6c568809d9ce.PNG)
   
   #
   ![Face recognition](https://user-images.githubusercontent.com/37952915/59977764-aa585880-95d5-11e9-82aa-7b54c9871351.gif)
   
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

   ![activity digram](https://user-images.githubusercontent.com/37952915/60112020-54b7b380-976f-11e9-8a31-3f5b4dd34ee3.PNG)


- ## Requirements and analysis:

  ### Software:
   #### Face recogntion step by step: 
   #
   
 

   recognize faces with 98% accuracy which is pretty much as good as humans can do!
   this is the steps to recognize face:
   
   1. First, look at a picture and find all the faces in it

   2. Second, focus on each face and be able to understand that even if a face is turned in a weird direction or in bad lighting, it is still the same person.

   3. Third, be able to pick out unique features of the face that you can use to tell it apart from other people like how big the eyes are, how long the face is, etc.

   4. Finally, compare the unique features of that face to all the people you already know to determine the person’s name.
    
    
  


   #
   #### object detection step by step:
   
  1. Break the image into overlapping image tiles.
   
  2. Feed each image tile into a small neural network.
   
  3. Save the results from each tile into a new array.
   
  4. Downsampling. 
 


#
      
 - ## Hardware Design and Components:
 
   - RaspberryPi 3 B+
   - camera
   - 3d printing glasses & models
   - Battery or Power Bank
   - Breadboard
   - Cables 
   - headphone
   - Button
   - Heatsink
   
    

#

## Testing:
  ### Hardware:
  
  Hardware testing is usually more detailed and thorough than verication. Testing is needed to ensure that every component of a system is operating as it should and that the system is performing exactly in accordance with the specic local requirements. A comprehensive structured testing program is one that ensures that all aspects of a system are tested. This is especially important for key systems such as electronic voting systems. Testing measures that could be followed include.

• Applying ’non-operating’ tests to ensure that equipment can stand up to
expected levels of physical handling, such as transit drop tests
• Examining if appropriate any code ’hard-wired’ in hardware (this code is
sometimes known as rmware) to ensure its logical correctness and to ensure
that appropriate standards are followed.
• Applying qualitative assessments to determine whether the test crite- ria have
been met.

#### Hardware Test Strategies:



   The focus in system testing is testing the interactions
between components. System testing checks that
components are compatible, interact correctly and
transfer the right data at the right time across their
interfaces

### Software:

Software Testing is an investigation that is
conducted to provide stakeholders with information about
the quality of the software product or service being tested.
Software testing can also provide an objective,
independent view of the software so that the company can
recognize and understand the risks of software
implementation. Testing techniques include the process
of executing a program or application with the intention of
ending software errors (errors or other errors) and verifying
that the software product is suitable for use. Software
testing involves the execution of a software component or
system component to evaluate one or more
properties of interest. In general, these properties indicate the
extent to which the component or system is being tested:
• meetsthe requirements ofplanninganddevelopmentofresponds properly to
all types of input.
• performs its functions in an acceptable time is suciently usable.
• can be installed and run in its intended environments, and achieves the general result of the wish of the stakeholder.






