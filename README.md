docker run -d \
--rm \
--name x11vnc \
-v ~/Desktop/tmp/.X11-unix:/tmp/.X11-unix \
-e DISPLAY=:99 \
-e RESOLUTION=1920x1080x24
-p 5900:5900 \
x11vnc
