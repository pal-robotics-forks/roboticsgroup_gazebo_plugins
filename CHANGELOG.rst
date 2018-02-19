^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package roboticsgroup_gazebo_plugins
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Merge branch 'dubnium-devel' into gazebo7
* changed namespace for gains
* Added gazebo7 support
* Contributors: Hilario Tome, Hilario Tomé, Hillario Tome

0.0.3 (2018-01-22)
------------------
* change pid gains namespace
* Contributors: Jordi Pages

0.0.2 (2016-10-12)
------------------
* Added install rules
* Add verbose mention that we are loading the plugin and with what
* Merge pull request #3 from tu-darmstadt-ros-pkg/add_set_force_for_pid_option_pr_upstream
  Add missing setForce() call (otherwise PID option doesn't do anything)
* Add missing setForce() call (otherwise PID option doesn't do anything)
* Merge pull request #2 from tu-darmstadt-ros-pkg/master
  Move catkin_package macro so it is called before targets are defined.
* Move catkin_package macro so it is called before targets are defined.
  Fixes plugins not getting found when doing isolated builds
* Code cleaning...
* README typo
* Added PID control capability to mimic joint plugin
* Added maxEffort parameter to MimicJoint plugin
* Added sensitiveness parameter to MimicJointPlugin
* Changed name of package
* Fixed typo in README and added checks in mimic plugin
* Added DisableLink Model Plugin
* Updated README
* Fixed small error in MimicJointPlugin
* Fixed type in README
* Initial commit..MimicJointPlugin..
* Contributors: Hilario Tome, Konstantinos Chatzilygeroudis, Sam Pfeiffer, Stefan Kohlbrecher, costashatz
