# Fuzzy-Logic-InvertedPendulum

Here, I want to design a fuzzy controller in order to solve the inverted pendulum problem. Our pendulum is located on a cart consists of a mass M at the top of a rod of length l pivoted on a horizontally moving base. The rod is considered massless and is carrying a mass m.

For implementing the fuzzy controller, I have to write my code in inverted_pendulum.fcl file which is a Fuzzy Control Language file. I have to declare my needed inputs and outputs. After that, it is necessary to FUZZYFY and DEFUZZYFY the required variables, and at the end I write my fuzzy rules in the RULEBLOCK section.

After every run, you get a report from the system that contains charts from x (cart position), x_dot (cart velocity), x_dot_dot (cart acceleration), theta - 180 (pendulum degree), theta_dot (pendulum angular velocity), theta_dot_dot (pendulum angular acceleration), and
f (force applied to the cart).

<img src="https://github.com/mahsawz/Fuzzy-Logic-InvertedPendulum/blob/main/inverted_pendulum_image.png" width="200" height="200">

Note that theta starts from the bottom of the unit circle and goes on the counterclockwise circle.
Therefore, theta value is always 90 degrees more than that of the unit circle.

Stable state: a state in which the pendulum degree, pendulum angular velocity, pendulum angular acceleration, cart acceleration, and force applied to the cart equal to 0.
