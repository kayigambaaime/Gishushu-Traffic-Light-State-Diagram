<img width="443" alt="gishushu state diagram " src="https://github.com/user-attachments/assets/e4e1e906-417c-4698-9bbe-5aef47bc7825">
The Gishushu Traffic Light System is designed to manage traffic flow at an intersection with six roads, using a state diagram to control alternating green and yellow light phases for North-South and East-West directions. The system consists of five primary states: North-South Green, North-South Yellow, All Directions Red, East-West Green, and East-West Yellow.

North-South Green (45 sec) allows vehicles traveling in the North-South direction to move through the intersection for 45 seconds. Once this time elapses, the light transitions to North-South Yellow (5 sec), signaling vehicles to slow down and prepare to stop. After the yellow phase, the system enters All Directions Red (3 sec) to provide a brief safety buffer where all lights are red, allowing any vehicles to clear the intersection before switching directions.

After the red phase, the system shifts to East-West Green (45 sec), allowing vehicles in the East-West direction to move for 45 seconds. This is followed by East-West Yellow (5 sec), indicating a transition to red. Once the East-West yellow phase is complete, the system again enters the All Directions Red (3 sec) phase for safety.

The cycle then repeats, switching between North-South and East-West directions, ensuring that each direction has adequate time to clear traffic while maintaining a safe gap between switching light states.

The All Directions Red phase, lasting 3 seconds, acts as a buffer between the switching of traffic flows, ensuring that there is no overlap and reducing the risk of accidents. Each green phase for North-South and East-West directions lasts for 45 seconds, while the yellow phases are short (5 seconds) to signal the impending transition.

This state diagram is designed to provide an optimal balance between traffic flow and safety. It can be used for traffic system simulations, software development, and traffic flow optimization studies, offering a clear and structured representation of how the Gishushu intersection operates.









