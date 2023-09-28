# End-to-end Reinforcement Learning for Torque Based Variable Height Hopping
**Raghav Soni [1], Daniel Harnack [2], Hannah Isermann [2], Sotaro Fushimi [3], Shivesh Kumar [2], Frank Kirchner [2]**

[1]: [Department of Electronics Engineering, Indian Institute of Technology (Banaras Hindu University), Varanasi, India.](https://iitbhu.ac.in/dept/ece)\
[2]: [DFKI GmbH Robotics Innovation Center, Bremen, Germany.](https://robotik.dfki-bremen.de)\
[3]: [Department of Mechanical and Systems Engineering, Kyoto University, Kyoto, Japan.](https://www.kyoto-u.ac.jp/en)


## Abstract
Legged locomotion is arguably the most suited and
versatile mode to deal with natural or unstructured terrains.
Intensive research into dynamic walking and running con-
trollers has recently yielded great advances, both in the optimal
control and reinforcement learning (RL) literature. Hopping is
a challenging dynamic task involving a flight phase and has
the potential to increase the traversability of legged robots.
Model based control for hopping typically relies on accurate
detection of different jump phases, such as lift-off or touch
down, and using different controllers for each phase. In this
paper, we present a end-to-end RL based torque controller that
learns to implicitly detect the relevant jump phases, removing
the need to provide manual heuristics for state detection. We
also extend a method for simulation to reality transfer of
the learned controller to contact rich dynamic tasks, resulting
in successful deployment on the robot after training without
parameter tuning.

## Video
<div align="left">
      <a href="https://www.youtube.com/watch?v=uzlkz2N8t0c">
         <img src="https://img.youtube.com/vi/uzlkz2N8t0c/0.jpg" style="width:100%;">
      </a>
</div>
 