^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mav_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
3.2.0 (2017-03-02)
------------------
* Access covariance in eigen odometry
* External force default topic
* External wind speed default topic

3.1.0 (2016-12-01)
------------------
* Add getEulerAngles method to EigenOdometry message.
* Improved quaternionFromMsg unit quaternion checking.
* Add EigenMavState to eigen_mav_msgs.
* Add EigenMavStateFromEigenTrajectoryPoint conversion.
* Add `timestamp_ns` to EigenTrajectoryPoint.
* Add default values in a seperate header.
* Add in_air bool to Status.msg.
* Add many helper function to calculate earth gravitational field based on hight and latitude, get euler angles from quaternion and shortest distance between two yaw angles.
* Contributors: Mina Kamel, Helen Oleynikova, Michael Burri

2.0.3 (2015-05-22)
------------------
* added install target for include
  Headers can be included outside of this package.
* Contributors: Fadri Furrer
