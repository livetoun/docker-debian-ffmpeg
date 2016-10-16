# Docker debian FFMPEG

- Provides latest FFMPEG on Ubuntu Base


## installation docker
~~~
cd /~
wget https://raw.githubusercontent.com/docker/docker/master/hack/install.sh
chmod +x install.sh
./install.sh
~~~


## run installation FFMPEG
~~~
docker build -t livetoun/docker-debian-ffmpeg github.com/livetoun/docker-debian-ffmpeg
~~~
