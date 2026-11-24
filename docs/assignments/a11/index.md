# A11 – Motor Selection

## Objective
to design a motor to drive the system in A10 using these constraints.
Key Constraints

No electronics, no software: purely mechanical.
Load capacity: 2 kN (with appropriate safety factor in structure and drivetrain).
Speed range: 1–50 mm/min (achieved via screw lead selection).
Form factor: bench-top footprint favored; manageable overall height; 18 inch leadscrew minimum.
Safety Factor: 4
## Motor selection
these are the calculations that I did for my motor selection.

![my truss system](unnamed-1.png) (Gavin Anderson)

![my truss system](unnamed-1.png) (Gavin Anderson

From my calculations the motor is going to have to spin at a rate of at least 20.5 lb * in so using this information and looking in McMaster, I selected a 12 V 1.2 rpm motor. which met all of the requirements and met all of my required dimensions.
![my truss system](unnamed-1.png)

## Motor mount (Gavin Anderson)
Here is an image of the calculations that I did for the design of the motor mount. These calculations to calulated and design a motor mount that could support 276 MPA while still maintaining a saftey factor of 4 for the whole time.

![my truss system](unnamed-1.png)

From my calculations I got a very small thickness which would be very odd to work with so I went ahead and rounded the number up to a quarter of an inch which will only make the motor mount have more support. The material for the motor head design is also made out of A6061 Aluminum.

## coupler (Gavin Anderson)
These are the calculations for the coupler that is used to help me find a coupler in MacMaster that would fit the requiments.
![my truss system](unnamed-1.png)

from these calculations I decided to use another 1/4 of an inch part in diameter because it would fit well within the contraints and it would make it easier on the designer.
![my truss system](unnamed-1.png)
## Frame analysis  (Kiishi Ayoola)
Designing Based on Twist of Motors
![my truss system](unnamed-1.png)
The design of the frame started with listing the knowns and the unknowns, so I did that and after that I drew a Free Body Diagram. I then solved for the forces symbolically and after I chose a proper mounting from the top to the vertical frame, I chose an inside corner bracket. The

calculations are pictured below.

Verifying top of frame strength

Now we had to determine if the top of the frame that was constructed from heavy 40 Series will be strong enough to withstand the loads of the lead screw load and the torque. To analyze and determine that, a Finite Element Analysis will be conducted with the proper constraints and loads. To start I got the top of the frame and put constraints on the ends, and loads in the proper spots. Once I did that I began the Finite Element Analysis and got the results from it.

![my truss system](unnamed-1.png)

It seems to bend and warp near the middle of the frame but the deflection is not major.

It seems again to bend and warp near the middle of the frame and the deflection is similar to before.

Optimization

Both of the results show that there might need to be more support near the middle of the frame. It also may need to be thicker. Since it needs to support the large load, these ideas need to be brought into consideration.

Verifying the Frame’s Vertical Component Strength

For the vertical frame FEA I wasn’t sure how to interpret that so I chose to do one frame, and the results would be the same for the other side as the loads are equally shared. I created the fixed ends and applied the loads to the top frame. I started with a medium mesh for my first iteration. After I ran this mesh and received the results, I used a more defined mesh for the next step.

Model Setup - I constrain interfaces to frame brackets and motor brackets. I then applied the loading that represents the two loads being felt by the vertical frame, one axial compression and one transverse load.


![my truss system](unnamed-1.png)

![my truss system](unnamed-1.png)

Results to Report - The load path I created was so that the side would feel the load from the top and from the side of the motor mount and so there was a torque and I believe this led to the increased bending. There wasn’t much twisting or warping but I think if more force was applied to the part the twist would be much more noticeable as for now it was not a problem.

Optimization Pass - After this analysis I would propose thicker flanges on the motor mount but and then remove material from places the stress concentration was not fixed at. We could also look into different materials in the same price range and see if a better strength is easily available. I would say the critical locations of force are fine as they are because it ended up not affecting the result too much.

## bearing mount (Kiishi Ayoola)
To start with designing the floating bearing mount I needed to research the purposes and the models of floating bearing mounts. I looked into the Machenery’s handbook for the fit of the sliding fit onto the leadscrew. On page 654 of the handbook I found the tolerances and clearances for RC3 running and sliding fits. I used this for the diameter of the main bore in the bearing mount. Then on page 657 I found the tolerances and clearances for LC6 clearance fits. I then used this for the fit of the bolt holes. I then found a similar piece to my drawing online and included it for clarity.

![my truss system](unnamed-1.png)
![my truss system](unnamed-1.png)
![my truss system](unnamed-1.png)
![my truss system](unnamed-1.png)
## material cost (Kiishi Ayoola)
total cost
![my truss system](unnamed-1.png)
## lesson learned (Gavin Anderson)

The project had many communication problems which made it very hard. Another thing was It was very eye opening to see how much cost actually effects things because you don't really ever think about it when you are just doing stuff on the computer or through a cad system.
