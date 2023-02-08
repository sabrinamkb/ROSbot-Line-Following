# ROSbot-Line-Following

# 1. Import These Libraries

```
import cv2
import numpy as np
from cv_bridge import CvBridge, CvBridgeError
```

# 2. Import This Package

```
mkdir -p ~/ros_workspace/src/my_following_line
cd ~/ros_workspace/src/my_following_line
catkin_init_workspace
sudo apt update
git clone https://github.com/sabrinamkb/ROSbot-Line-Following.git
cd ~/ros_workspace
rosdep install --from-paths src --ignore-src -r -y
catkin_make
source devel/setup.sh
```

# 3. Run The Following Commands In The Terminal

```
rosmsg show sensor_msgs/Image
rostopic echo -n1 /camera/rgb/Image_raw/height
rostopic echo -n1 /camera/rgb/Image_raw/width
rostopic echo -n1 /camera/rgb/Image_raw/encoding
rostopic echo -n1 /camera/rgb/Image_raw/data
```

# 4. Run Your Python Script To Check If It Works

```
rosrun my_following_line_package line_follower_basics.py
```

