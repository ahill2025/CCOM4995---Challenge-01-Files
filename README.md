Grupo 2:									Septiembre 9, 2025
- Luis Aparicio (801-21-8072)
- Alec Hillman (802-15-3423)


Steps to creating a Simple House:


We want to create a simple house with a 7 x 7 = 49 area.  Start your project by creating an empty game object and rename it ‘Simple House’.  
Position your ‘Simple House’ coordinates to the following: 
  - x = 0
  - y = 0
  - z = 0


These coordinates were chosen to facilitate the creation of our front door by having a designated 1x1 square for the length of the door.  

<img width="1902" height="727" alt="1" src="https://github.com/user-attachments/assets/b9e9d847-5622-418c-b633-7a1571568a5d" />


Next, create an empty child object and name it ‘Front Wall’.  According to challenge conditions, we can only move, rotate and scale the cube objects.  Thus, we can create 3 cubes and orient them to simulate a front wall with a door frame.  
Create the 3 cubes and drag them to the ‘Front Wall’ object to have control of all objects simultaneously.  Name two of the cubes ‘Left Front’ and ‘Right Front’ and provide them with the same scaling values. 
  *	Scaling Values for ‘Right Front’ and ‘Left Front’ objects:
    - x = 2.75 (wall length)
    - y = 1.5 (wall width)
    - z = 0.25 (wall thickness)
   

Wall length is 2.75 to account for wall thickness of left and right-side walls of 0.25.  Name the remaining cube ‘Top Door’ and apply the following scaling values.  
  * Scaling Values for ‘Top Door’ object:
    -	x = 1 (wall length)
    -	y = 0.35 (wall width)
    -	z = 0.25 (wall thickness)
   

After scaling all ‘Front Wall’ cube objects, provide the following position values:
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

Copy cube object for the remaining walls (2) and only modify their position values. Change ‘Left Wall’ position ‘x’ value from 2.875 to -3.875.  Then change ‘Rear Wall’ scaling and position values to the following:
  *	Scaling values: 
    -	x = 6.5
    -	Rotation in y-axis = 0˚
  *	Position values:
    -	x = -0.5
    -	y = 0.75
    -	z = -6.875
    

<img width="1919" height="739" alt="4" src="https://github.com/user-attachments/assets/e6fee412-d590-4bdc-b740-20b631bb0cab" />

















    
