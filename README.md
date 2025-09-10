Grupo 2:									
- Luis Aparicio (801-21-8072)
- Alec Hillman (802-15-3423)


Steps to creating a Simple House:


We want to create a simple house with a 7 x 7 = 49 area.  Start your project by creating an empty game object and rename it ‘Simple House’.  
Position your ‘Simple House’ with the following values: 
  - x = 0
  - y = 0
  - z = 0


These coordinates were chosen to facilitate the creation of our front door by having a designated 1x1 square for the length of the door.  

<img width="1902" height="727" alt="1" src="https://github.com/user-attachments/assets/b9e9d847-5622-418c-b633-7a1571568a5d" />


Next, create an empty child object and name it ‘Front Wall’.  According to the challenge conditions, we can only move, rotate and scale the cube objects.  Thus, we can create 3 cubes and orient them to simulate a front wall with a door frame.  
Create the 3 cubes and drag them to the ‘Front Wall’ object to have control of all objects simultaneously.  Name two of the cubes ‘Left Front’ and ‘Right Front’ and provide them with the same scaling values. 
  *	Scaling Values for ‘Right Front’ and ‘Left Front’ objects:
    - x = 2.75 (wall length)
    - y = 1.5 (wall width)
    - z = 0.25 (wall thickness)
   

Wall length X is 2.75 to account for wall thickness Z of left and right-side walls of 0.25.  Name the remaining cube ‘Top Door’ and apply the following scaling values.  
  * Scaling Values for ‘Top Door’ object:
    -	x = 1 (wall length)
    -	y = 0.35 (wall width)
    -	z = 0.25 (wall thickness)
   

After scaling all ‘Front Wall’ cube objects, input the following position values:
  *	Position Values for ‘Right Front’ object:
    -	x = 1.325
    -	y = 0.75
    -	z = -0.125
  *	Position Values for ‘Left Front’ object:
    -	x = -2.375
    -	y = 0.75
    -	z = -0.125
  *	Position Values for ‘Top Door’ object:
    -	x = -0.5
    -	y = 1.325
    -	z = -0.125

<img width="1918" height="741" alt="2" src="https://github.com/user-attachments/assets/fe0de371-6bfe-471d-a467-f341cff6547c" />

Once the front wall of the house is built, copy either ‘Left Front’ or ‘Right Front’ object and rename it ‘Right Wall’.  Modify scaling and position values to the following:
  *	Scaling values for ‘Right Wall’:
    -	x = 7
    -	y = 1.5
    -	z = 0.25
    -	Rotation in y-axis = 90˚
  *	Position values for ‘Right Wall’:
    -	x = 2.875
    -	y = 0.75
    -	z = -3.5

<img width="1919" height="739" alt="3" src="https://github.com/user-attachments/assets/e0802651-c4fa-4fd4-98ce-f30fac0923a4" />

Copy cube object twice for the remaining walls and only modify their position values. Change ‘Left Wall’ x-position value from 2.875 to -3.875.  Then change ‘Rear Wall’ scaling and position values to the following:
  *	Scaling values: 
    -	x = 6.5
    -	Rotation in y-axis = 0˚
  *	Position values:
    -	x = -0.5
    -	y = 0.75
    -	z = -6.875
    

<img width="1919" height="739" alt="4" src="https://github.com/user-attachments/assets/e6fee412-d590-4bdc-b740-20b631bb0cab" />


Then, create a cube object for the house roof and name it ‘Right Roof Section’.  Below are scaling and initial position values for the roof section:

  *	Scaling values for ‘Right Roof Section’:
    -	x = 2 (Roof section length)
    -	y = 1.75 (Roof section height)
    -	z = 9 (Roof section depth)
  *	Position values:
    -	x = 2
    -	y = 1.75
    -	z = -3.5


Roof depth Z is 2 units larger than the wall length X to guarantee roof covers house area.  Length X is valued at 2 due to x-position = 2, to ensure roof section does not “over-merge” with wall sections.  Roof height Y is set to 1.75 to be in contact with wall top face.  

After setting ‘Right Roof Section’ horizontally, create a copy of it, called ‘Left Roof Section’ and modify x-position value to -3.  


<img width="1916" height="726" alt="5" src="https://github.com/user-attachments/assets/255615bb-92c7-4c9b-b8c6-6eec464e43d1" />

<br>

Apply initial rotation values in Z of -13˚ (167˚) for ‘Right Roof Section’ and 13˚ for ‘Left Roof Section’.  Extend X scale value for both sections from 5 to 5.25.  As seen in the image below, the sections pass through each other with a slight extrusion of each section on the other.  This can be fixed by adjusting the angle by adding -0.1˚ and 0.1˚ to the ‘Right Roof Section’ and ‘Left Roof Section’ Z angle, respectively.  
<br>


<img width="1916" height="721" alt="6" src="https://github.com/user-attachments/assets/5b17c240-56a5-4afd-99e7-f0c529e56ca8" />

<br><br>


<img width="1916" height="722" alt="7" src="https://github.com/user-attachments/assets/c712e5e3-df6d-47de-b4d9-b6b0107ef078" />

<br><br>


The last step would be to adjust y-position for each section to ensure contact with house walls.  Adjust both section’s y-positions to 1.95.
<br>



<img width="1913" height="725" alt="8" src="https://github.com/user-attachments/assets/54f69b43-828f-4a9f-82a7-966da4d10d49" />


Edit 9/10/2025:


Alec Hillman:


Learning a program with assistance is not the same as sitting down and experimenting with the program yourself.  I learned how to approach designing a figure after going through some small hurdles, these coming from creating the roof sections.  
Initially, both left and right roof top cubes were set as child objects for the left and right wall cubes, respectively.  This caused problems with scaling and positioning and eventually, the design for the roof section was changed using a simpler method.
In the end, I did end up learning that child object scaling values are affected by their respective parent object, which was pretty cool.  Overall, a very nice introudction.  

Luis Aparicio:








    
