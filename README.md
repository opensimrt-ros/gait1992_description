# Human control

Package created with [ospi2urdf]( https://gitlab.inria.fr/elandais/ospi2urdf) which is itself based on the [ospi package](https://github.com/Gepetto/ospi).

## TODO:

- The knees from our model are a custom joint and needed to be fixed manually. It is not guaranteed that the model will be diplayed properly. I believe that for the knee maybe a http://wiki.ros.org/joint_trajectory_controller needs to be used, so as to represent the spline trajectory which the knee takes. 

- For other joints perhaps simpler joint_state_controllers are sufficient (see http://wiki.ros.org/ros_control for details), which are not currently implemented on the [OpenSimRT_ros interface](https://github.com/frederico-klein/OpenSimRT/tree/slim-death).

- Migrate gait1992 osim model here and make sure that opensimrt_core looks here for the model instead.
- Read relevant parameters from model and update them in the visualization. 
- change the fixed paths in launch file to relative ones



