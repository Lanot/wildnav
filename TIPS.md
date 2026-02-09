# INSTALLATION

```
git submodule update --init --remote

python -m pip list | grep haversine
python -m pip list | grep matplotlib
python -m pip list | grep numpy
python -m pip list | grep opencv_python
python -m pip list | grep pandas
python -m pip list | grep requests
python -m pip list | grep scikit_learn
python -m pip list | grep seaborn
python -m pip list | grep torch


python -m pip list | grep matplotlib
python -m pip list | grep numpy
python -m pip list | grep requests
python -m pip list | grep torch
```

# FIX for ``
```
pip install numpy==1.26.4 --force-reinstall  --break-system-packages
pip install setuptools==75.3.3 --force-reinstall  --break-system-packages
```

# FIX for `AttributeError: module 'cv2.dnn' has no attribute 'DictValue'`
```
sudo apt-get install python3-opencv
python -m pip install opencv-contrib-python --break-system-packages
```

# python -m pip install opencv_python==4.5.5.64 --user --break-system-packages
# python3-opencv is already the newest version (4.6.0+dfsg-13.1ubuntu1).

# The rest of uninstalled packages (others may exist, if not install them too in the similar way)
```
python -m pip install haversine==2.5.1 --user --break-system-packages
python -m pip install pandas==1.4.2 --user --break-system-packages
python -m pip install scikit_learn --user --break-system-packages
python -m pip install seaborn>=0.11.2 --user --break-system-packages
```

# Yaw/Pitch/Roll Gimbal Visualization
@See: https://ursinusgraphics.github.io/RollPitchYaw/
@See: https://danceswithcode.net/engineeringnotes/rotations_in_3d/demo3D/rotations_in_3d_tool.html
