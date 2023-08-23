
This repository was forked from [LG SVL Msgs](https://github.com/lgsvl/lgsvl_msgs)
for the evaluation of [Perception Simplex](https://github.com/CPS-IL/perception_simplex), please refer to the instructions at [Perception Simplex](https://github.com/CPS-IL/perception_simplex).
The engineering version, uploaded and maintained by Simon Yu, is also [available](https://github.com/cpsintegrationlab/lgsvl_msgs).

---
The original ReadMe follows:


# Protobuf Package lgsvl_msgs for LG SVL Automotive Simulator

This repository contains protobuf message definitions for lgsvl_msgs to subscribe protobuf messages being published by LG SVL Automotive Simulator via cyber bridge.


```text
<proto>
  - detection2d.proto       # 2D detection including id, label, score, and 2D bounding box
  - detection2darray.proto  # A list of 2D detections
  - detection3d.proto       # 3D detection including id, label, score, and 3D bounding box
  - detection3darray.proto  # A list of 3D detections
```


# Copyright and License

Copyright (c) 2018 LG Electronics, Inc.

This software contains code licensed as described in LICENSE.
