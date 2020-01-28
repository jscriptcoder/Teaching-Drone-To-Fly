# Machine Learning Engineer Nanodegree
## Deep Reinforcement Learning
### Project: Teach a Quadcopter How to Fly

See [project report](Quadcopter_Project.ipynb)

Untrained agent:

<img src="videos/quadrotor_anim_8163d3a2-5e86-4318-975f-803daa7545da.gif" />

---
Better trained agent, trying to reach the target:

<img src="videos/quadrotor_anim_8163d3a2-5e86-4318-975f-803daa7545da.gif" />

### Project Overview
The Quadcopter or Quadrotor Helicopter is becoming an increasingly popular aircraft for both personal and professional use. Its maneuverability lends itself to many applications, from last-mile delivery to cinematography, from acrobatics to search-and-rescue.

Most quadcopters have 4 motors to provide thrust, although some other models with 6 or 8 motors are also sometimes referred to as quadcopters. Multiple points of thrust with the center of gravity in the middle improves stability and enables a variety of flying behaviors.

But it also comes at a price–the high complexity of controlling such an aircraft makes it almost impossible to manually control each individual motor's thrust. So, most commercial quadcopters try to simplify the flying controls by accepting a single thrust magnitude and yaw/pitch/roll controls, making it much more intuitive and fun.

The next step in this evolution is to enable quadcopters to autonomously achieve desired control behaviors such as takeoff and landing. You could design these controls with a classic approach (say, by implementing PID controllers). Or, you can use reinforcement learning to build agents that can learn these behaviors on their own. This is what you are going to do in this project!
