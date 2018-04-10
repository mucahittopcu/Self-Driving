Bu dosyada Ros Kinetic sürümünün kurulum adımlarını bulabilirsiniz.

## Ubuntu 15.10 - Xenial (Ubuntu 16.04) - Jessie (Debian 8)
  - sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
  - sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116
  - sudo apt-get update
  - sudo apt-get install ros-kinetic-desktop-full
  - apt-cache search ros-kinetic
  - sudo rosdep init
  - rosdep update
  - echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc
  - source ~/.bashrc
  
  Yukarıdaki adımları sırası ile terminalde çalıştırın. Eğer hata almadan tamamlarsanız terminalde "roscore" yazdığınızda resimdeki gibi bir sonuç almanız gerekmektedir.
  ![roscore](https://github.com/satilmisyusuf/Self-Driving/blob/master/images/roscore.png)
  
  
