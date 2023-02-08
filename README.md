# ROSbot-Line-Following

# 1. Import These Libraries

```
import cv2
import numpy as np
from cv_bridge import CvBridge, CvBridgeError
```

# 2. Run The Following Commands In The Terminal

```
rosmsg show sensor_msgs/Image
rostopic echo -n1 /camera/rgb/Image_raw/height
rostopic echo -n1 /camera/rgb/Image_raw/width
rostopic echo -n1 /camera/rgb/Image_raw/encoding
rostopic echo -n1 /camera/rgb/Image_raw/data
```

