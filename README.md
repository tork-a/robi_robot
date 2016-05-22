robi_robot
==========

This package contains ROS drveir for [Robi](http://deagostini.jp/rbi/) Robot
## Run robi ros driver

```
rosrun robi_driver robi_bringup.launch
```

## Run example codes

Let Robi to speak pre-installed voice
```
rosrun robi_driver speak_hello
rosrun robi_driver speak_drink
```

Let Robi to move
```
rosrun robi_driver do_sit
rosrun robi_driver do_standup
rosrun robi_driver do_walk
```

Let Robi to command arbitrary joint angles and led colors
```
rosrun robi_driver move_servo
```

## Technical Details

### WIfi-nize the Robi Robot with Flashair SD Card
https://sites.google.com/site/jijytadano/home/flashair_settings

### Technical details on remote control
http://www.mcc.mbsrv.net/robox/index.html
http://www.kumagaya.or.jp/~mcc/robox/RBMotion/remote.html