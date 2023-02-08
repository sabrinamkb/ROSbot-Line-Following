# ROSbot-Line-Following

# 1. Import These Libraries

```
import cv2
import numpy as np
from cv_bridge import CvBridge, CvBridgeError
```

# 2. Import This Package

```
git clone https://github.com/sabrinamkb/ROSbot-Line-Following.git
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
rosrun ROSbot_Line_Following line_follower_basics.py
```

