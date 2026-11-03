# FPGA-based-Arm-Inverse-Kinematics-Acceleration-System
A Zynq FPGA HW/SW co-acceleration system is built for real-time robotic arm inverse kinematics (IK). A PL-side LM-based IK IP core uses HLS pipelining and loop unrolling for matrix ops and Cholesky decomposition. With LeRobot and SO-101, it enables pose solving, joint control and teleoperation. Iteration is ~10× faster than software.
