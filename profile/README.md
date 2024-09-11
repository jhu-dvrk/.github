The da Vinci Research Kit (**dVRK**) is an “open-source mechatronics” system, consisting of electronics, firmware, and software that is being used to control research systems based on the now retired first-generation da Vinci system from [Intuitive Surgical Inc](https://www.intuitive.com/).  The da Vinci system is designed for Robot-Assisted Minimally Invasive Surgery (RAMIS).  The dVRK is now deployed in close to [40 differents institutions worldwide](https://github.com/jhu-dvrk/sawIntuitiveResearchKit/wiki/Timeline).

The dVRK documentation is hosted on the :point_right: [sawIntuitiveResearchKit Wiki](https://github.com/jhu-dvrk/sawIntuitiveResearchKit/wiki) :point_left:.  Please check the build instructions in the Wiki before cloning any repository.  The build instructions show how to use `wstool` or `vcs` to pull all the repositories you might need for ROS 1 or ROS 2.

Repositories:
* **dVRK**: [sawIntuitiveResearchKit](https://github.com/jhu-dvrk/sawIntuitiveResearchKit) Main repository for the dVRK.  This code depends on the *cisst* libraries.  It also includes the main ROS nodes for the dVRK (ROS1 and ROS2)
* **ROS**:  Extra ROS features are provided across multiple repositories.
  * [dvrk_model](https://github.com/jhu-dvrk/dvrk_model): configuration files (URDF and CAD)
  * [dvrk_python](https://github.com/jhu-dvrk/dvrk_python): Python client API over ROS, calibration scripts and examples
  * [dvrk_video](https://github.com/jhu-dvrk/dvrk_video): launch files for the video pipeline
