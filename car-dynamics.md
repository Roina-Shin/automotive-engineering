## Vehicle Dynamics


![vehicle-forces](/pictures/vehicle-dynamics/vehicle-dynamics.PNG "vehicle forces")


- **Weight**: Defined by the car, constant. Always pointing towards the center of the Earth.


- **Support (Normal)**: Force provided by the ground to the car, equal to the Weight. Always perpendicular to the ground.


- **Traction**: Force provided by the engine of the car through the motion of the wheels.


- **Drag (Resistance)**: Aerodynamic decelerating force by the air flowing around the car. It increases with the speed of the car (D ~ V^2).



### Newton's 1st Law

- If a body is at rest or moving at a constant speed, it will remain at rest or keep moving at constant speed unless it is acted upon by a force.


### Newton's 2nd Law

- An unbalanced force acting on a body will produce an acceleration to such body in the direction of the force in accordance to its mass.


![newton's-law-of-motion](/pictures/vehicle-dynamics/newton's-law-of-motion.PNG "Newton's law of motion")


- In other words: Force equals mass multiplied by acceleration.


![fma-formula](/pictures/vehicle-dynamics/fma-formula.PNG "f = m * a formula")


- The sigma sign here means **summation**, meaning the sum of all forces.


![with-sigma](/pictures/vehicle-dynamics/with-sigma.PNG "with sigma")


- If all the forces are not balanced, that would imply an acceleration in the direction of the resulting forces. And to combine all forces, we simply put the sigma over there, which means the compound of all forces. 


![centripetal-and-cornering-force](/pictures/vehicle-dynamics/centripetal-and-cornering-forces.PNG "centripetal and cornering forces")


- **Weight**: Constant, vertical.


- **Normal**: Force provided by the ground to the car, perpendicular to the ground.


- **Centripetal force**: Inertial force due to car's opposing change of direction.


- **Cornering force**: Force produced by a vehicle tire during cornering.


![positive-and-negative-cambers](/pictures/vehicle-dynamics/negative-and-positive-camber.PNG "positive and negative cambers")


*Source*: https://apexwheels.com/blog/technical-discussion/the-positives-of-negative-camber


- **Negative camber**: Increased handling during heavy cornering.


- **Zero camber**: Most uniform tire wear over time.


- **Positive camber**: Reduced steering effort, greater stability.


- Generally, sports cars prefer to have **negative camber** in order to improve the cornering response, effectiveness, and performance, while also adding a touch of instability in the straight line. Clearly, this is similar to what a sports car might be intended to perform. 


- On the other hand, **positive camber** is quite common for agricultural vehicles, especially when terrain is irregular. This will aid when steering the vehicle due to its improved steering performance and adaptability to the terrain. 


### Pure rotation and pure translation = Rolling motion

- Addition of pure rotation and pure translation is rolling motion.


![pure-rotation-and-pure-translation](/pictures/vehicle-dynamics/pure-rotation-and-pure-translation.PNG "pure rotation and pure translation")


- In order for the velocity at point P to be equal to zero, we must have that **pure rotation** and **pure translation** velocities at point P must be equal to zero.


- In other words, the velocity of the rotation and the velocity of the translation **must be equal at the point P** so that the wheel does not slip. This then results in the fact that the velocity at which the vehicle will be moving.



### D'Alembert's Principle

- Mass times Acceleration equals Force. In this equation, the mass is constant. As you can see in the second equation, Force is actually equal to the **derivative over time** of the Mass time Velocity.



![newton-second-law-of-nituib](/pictures/vehicle-dynamics/newton's-second-law-of-motion.PNG "newton's second law of motion")



- Now, if we assume that the Mass doesn't change over time, that is the Mass of the car, then it can be assumed that the Mass is constant. 



![third-equation](/pictures/vehicle-dynamics/third-equation.PNG "third equation")


- If the Mass is constant, then we can simply move it from the derivative, from the inside of the derivative, to a constant multiplying on the outside. In other words, the derivative is useful to understand how a variable varies over time, because **dt** is derivative over time. 


- Therefore, the equation changes to that indicator on the third equation, which is **the Mass times the Derivative Over Time of the Velocity**.


- The rate at which the velocity changes is precisely the acceleration. That means that the acceleration is the derivative of the velocity. Therefore, Force is equal to Mass times Acceleration.


- The objective of this study is to understand how the motion of a car is related to the Newton's second law of motion.


![different-way-of-expressing-equation](/pictures/vehicle-dynamics/different-way-of-expressing-equation.PNG "different way of expressing equation")


- The above is another way of expressing the same equation. But Force here indicates an external force, whereas Mass times Acceleration is a Force related to the mass of the body. And this type of Force (Mass * Acceleration) is commonly known as an inertial force.


![derivative-over-time](/pictures/vehicle-dynamics/derivative-over-time.PNG "derivative-over-time")


- And the third equation above has been expressed or indicated as a V with a dot on the top. This is the same as the **derivative over time of the velocity**.


![d'alembert's-principle](/pictures/vehicle-dynamics/d'alembert's-principle.PNG "d'alembert's principle")


- In the D'alembert's Principle, the force is assumed to cause a certain displacement. That is, by applying a force, the body will displace a certain amount.


- So, D'alembert's principle simply considers that all of the external forces applied to the body minus all of the inertial forces is equal to zero. In the third equation, the subindex *i* stands for each one of the forces applied to the vehicle. So, in this case, we are not only considering only one of the forces, but rather consider all of the forces, that is the compound of the forces acting on the car at that moment.


- And if you look at the sigma at the far left of the equation, its *n* implies that the *n* number of forces are applied to the vehicle.


- So, in other words, the D'alembert's Principle postulated that all forces, **external and inertial** applied to a car or applied to any body, really must be equal to zero.


- For any body, the sum of externally applied forces and the inertial (mass) forces resisting motion in any given direction is zero.


![inertial-forces](/pictures/vehicle-dynamics/inertial-forces.PNG "inertial forces")


- So, the mass of the object we are trying to move opposes the force that is being applied. Thus, the difficulty to move an object is the very definition of the inertial force. 