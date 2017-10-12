## How many balls fit into a 10x10x10 room?

Here is the solution to how many balls fit into a 10x10x10 room?

*NOTE:* Assuming the dimensions of the room are in feet

#### Case 1

##### Antecedent:

- We are counting number of balls at any given specific time.

- Assuming room is empty and total volume of the room is available.

- Balls are **inflated**.

- Balls on lowest tiers of the stack are not deflated from the weight of the ones on top of them.

##### Behavior:
- Size of the room - ``10ft x 10ft x 10ft``

- Total volume of the room - **1000** cubic ft

- 1 cubic foot = **1728** inches

- Therefore ``1000 * 1728`` = **1728000** cubic inches

- Radius of the golf ball = **0.85** inches (approximate)

- Volume of the golf ball = ``4/3 * pi * (r^3)`` = **2.5** cubic inches

##### Consequence:
- Therefore number of golf balls that can be accommodated in the room is ``1728000/2.5`` = **691200**

#### Case 2

##### Antecedent:
- We are counting number of balls at any given specific time.

- Assuming room is occupied by chairs/tables and total volume of the room is not available only ``80%`` of the room is available.

- Balls are **inflated**.

- Balls on lowest tiers of the stack are not deflated from the weight of the ones on top of them.

##### Behavior:
- Total volume available is ``1728000 * 0.80`` = **1382400**

##### Consequence:
- Number of golf balls that can be accommodated is ``1382400/2.5`` = **552960**


#### Case 3

##### Antecedent:
- We are counting number of balls at any given specific time.

- Assuming room is empty and total volume of the room is available.

- Balls are **deflated**.

- Balls on lowest tiers of the stack are not deflated from the weight of the ones on top of them.

##### Behavior:

- Size of the room - ``10ft x 10ft x 10ft``

- Total volume of the room - **1000** cubic ft

- 1 cubic foot = **1728** inches

- Therefore ``1000*1728`` = **1728000** cubic inches

- Radius of the golf ball = **0.4** inches (approximate)

- Volume of the golf ball = ``4/3 * pi * (r^3)`` = **0.27** cubic inches

##### Consequence:
- Therefore number of golf balls that can be accommodated in the room is 1728000/2.5 = **6400000**

#### Case 4:

##### Antecedent:

- We are counting number of balls at any given specific time.

- Assuming room is occupied by chairs/tables and total volume of the room is not available only ``80%`` of the room is available.

- Balls are **deflated**.

- Balls on lowest tiers of the stack are not deflated from the weight of the ones on top of them.

##### Behavior:
- Total volume available is ``1728000 * 0.80`` = **1382400**

##### Consequence:
- Number of golf balls that can be accommodated is ``1382400/0.27`` = **5120000**

Similarly we could find how many other balls (basketball, football and more) that could fit in a room under similar conditions provided we know the radius of the ball.
