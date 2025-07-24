# UR5e-Gesture-control
Controlling of UR5e Robot with Gesture control using Mediapipe

“Wave It, Move It!” ✋🤖

Youtube Link: https://youtu.be/HPGEiMZfP5M


Another Weekend Wrap: I built a foundational-level gesture‑controlled UR5e demo using MediaPipe and Python, laying the groundwork for more advanced AI and machine‑vision integrations.



📹 Captured real‑time hand landmarks with MediaPipe’s high‑fidelity hand‑tracking pipeline.

🖥️ Processed landmarks in Python to interpret five discrete commands (Home, Up, Down, Left, and Right).

🔌 Streamed URScript commands over a TCP socket to the UR5e, enabling intuitive teleoperation.

🎯 Ensured safe motion with speed‑limiting.



Key technical highlights:

MediaPipe Hands for robust, low‑latency landmark detection.

URScript via socket: speedl() for smooth Cartesian movements.

Modular architecture for easy scaling.



While this demo remains fun and foundational, it’s a crucial stepping stone toward industrial use cases:

Select tools or parts on an assembly line with a simple finger point

Trigger safety stops instantly with a clear “stop” gesture

AI‑driven gesture recognition using convolutional neural networks.

Reinforcement learning to teach the robot adaptive grasping and motion strategies.

ROS‑based frameworks for multi‑modal control (vision + gesture + voice).



With further work on integration with PLCs or ROS, gesture control could become a useful layer of human‑robot collaboration in smart manufacturing.



Please excuse any stutter. This code is running on a standard laptop and hasn’t been performance-tuned.
