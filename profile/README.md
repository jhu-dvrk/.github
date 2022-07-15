The da Vinci Research Kit (**dVRK**) is an “open-source mechatronics” system, consisting of electronics, firmware, and software that is being used to control research systems based on the now retired first-generation da Vinci system from [Intuitive Surgical Inc](https://www.intuitive.com/).  The da Vinci system is designed for Robot-Assisted Minimally Invasive Surgery (RAMIS).  The dVRK is now deployed in close to [40 differents institutions worldwide](/jhu-dvrk/sawIntuitiveResearchKit/wiki/Timeline).

Repositories:
* **dVRK**: [sawIntuitiveResearchKit](https://github.com/jhu-dvrk/sawIntuitiveResearchKit) Main repository for the dVRK.  This code depends on the *cisst* libraries but doesn't require ROS.  The dVRK documentation is hosted on the [wiki](https://github.com/jhu-dvrk/sawIntuitiveResearchKit/wiki).
* **ROS 1**:
  * [dvrk-ros](https://github.com/jhu-dvrk/dvrk-ros): ROS node for the dVRK, configuration files (URDF and CAD), Python and Matlab clients API over ROS...
* **ROS 2**: :warning: ROS 2 support is new and barely tested
  * [ros2_dvrk_robot](https://github.com/jhu-dvrk/ros2_dvrk_robot): ROS node for the dVRK
  * [ros2_dvrk_model](https://github.com/jhu-dvrk/ros2_dvrk_model): configuration files (URDF and CAD)
  * [ros2_dvrk_python](https://github.com/jhu-dvrk/ros2_dvrk_model): Python client API over ROS
