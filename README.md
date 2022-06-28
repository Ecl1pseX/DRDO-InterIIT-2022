# DRDO-InterIIT-2022
Our approach to the problem statement can be divided into the following sub-problems.
- Terrain recognition- The sensors aboard the UAV are capable of extracting vision and
depth data from the given terrain.
- Road mapping- Processing the data enables us to identify feasible roadways in the
region. The next step is then to control the UGV to follow the given path.
- UGV Controller- A basic controller is developed to instruct kinematic inputs to the UGV
(position, orientation and velocity).
- Feedback- A reliable real-time feedback loop of the UGV’s state is built. This achieves 2
things.
  - The controller’s next instruction is based on the UGV’s current state. Hence the
feedback loop allows the controller to publish optimal instructions.
  - It mitigates the chances of derailing of the UGV.
