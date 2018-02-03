# My Home Assistant config

Work in progress....

# Install packages for Axis camera

apt-get install python3-gi gir1.2-gstreamer-1.0
ln -s /usr/lib/python3/dist-packages/gi /usr/local/lib/python3.6/site-packages
cd /usr/lib/python3/dist-packages/gi
cp _gi.cpython-34m-x86_64-linux-gnu.so _gi.cpython-36m-x86_64-linux-gnu.so
