# move like a man

## resources

*touchdesigner*

- [MediaPipe in TouchDesigner 1 - installing mediapipe](http://www.magicandlove.com/blog/2021/05/20/mediapipe-in-touchdesigner-1/)
- [MediaPipe in TouchDesigner 9 - pose tracking](http://www.magicandlove.com/blog/2021/05/24/mediapipe-in-touchdesigner-9)
    - [github for series](https://github.com/chungbwc/TouchDesigner)
- [Sending and Receiving OSC Values with TouchDesigner](https://matthewragan.com/2013/10/10/sending-and-receiving-osc-values-with-touchdesigner/)

*blender*

- [blender.NodeOSC addon](https://github.com/maybites/blender.NodeOSC)
- [BlendyPose addon](https://github.com/zonkosoft/BlendyPose/blob/main/blendy_pose.py#L64)
    - used addon as ref for script to build blank pose
- [Expy Kit addon](https://github.com/pKrime/Expy-Kit)
    - convert mixamo rig to rigify

*blendshapes and kinematics*

the elements returned from mediapipe are 2D (although their are apis for z dim). when attached directly to a skeleton, they do not result in correct motion. the vectors need location or rotation transforms in order to work properly with how rigs are made. the following is research into the topic and (hopefully) a solution for my use.

- @carlosedubarreto
    - [b3d_mocap_import - alpha_realtime branch](https://github.com/carlosedubarreto/b3d_mocap_import/tree/alpha_realtime)
    - [Dev Preview - Mediapipe and new method of retarget](https://www.patreon.com/posts/dev-preview-and-53711794)

- [Application of 3D human pose estimation for motion capture and character animation - Anastasiia Borodulina](http://jultika.oulu.fi/files/nbnfioulu-201906262670.pdf)

- [sl-animation-blender](https://github.com/lanthaon/sl-animation-blender)
- [AI-Dance-based-on-Human-Pose-Estimation - SutirthaChakraborty fork](https://github.com/SutirthaChakraborty/AI-Dance-based-on-Human-Pose-Estimation)