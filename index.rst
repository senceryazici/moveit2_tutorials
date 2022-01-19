MoveIt 2 Tutorials
===================

Welcome to the unified MoveIt documentation, which includes tutorials, how-to-guides, core concepts, and more.

MoveIt 2 is the robotics manipulation platform for ROS 2, and incorporates the latest advances in motion planning, manipulation, 3D perception, kinematics, control, and navigation. MoveIt 2 was first release in 2019; for ROS 1 documentation, see `MoveIt 1 tutorials <https://ros-planning.github.io/moveit_tutorials>`_.

.. image:: https://moveit.ros.org/assets/images/roadmap.png
   :width: 400px

In these tutorials, the Franka Emika Panda robot is used as a quick-start demo.

<<<<<<< HEAD
Getting Started with MoveIt and RViz
-------------------------------------
.. toctree::
   :maxdepth: 1
=======
* :doc:`/doc/tutorials/tutorials` will walk you through creating your first project with MoveIt.
* :doc:`/doc/how_to_guides/how_to_guides` answers the question "How to do X with MoveIt?"
* :doc:`/doc/concepts/concepts` discusses the design of MoveIt.
* :doc:`/doc/how_to_contribute/how_to_contribute` is a place to learn about making changes to MoveIt and this website.
* :doc:`/doc/examples/examples` contains other useful pages that have not been adapted to the new layout of this site or are not yet ported from ROS 1.
* :doc:`/doc/api/api` will redirect you to a reference API page.
>>>>>>> f680cbe (Api Documentation CI (#310))

   doc/getting_started/getting_started
   doc/quickstart_in_rviz/quickstart_in_rviz_tutorial

MoveGroup - ROS Wrappers in C++
------------------------------------------
The simplest way to use MoveIt through scripting is using the ``move_group_interface``. This interface is ideal for beginners and provides unified access to many of the features of MoveIt.

.. toctree::
   :maxdepth: 1

<<<<<<< HEAD
   doc/move_group_interface/move_group_interface_tutorial

Using MoveIt Directly Through the C++ API
------------------------------------------
Building more complex applications with MoveIt often requires developers to dig into MoveIt’s C++ API. As an added plus, using the C++ API directly skips many of the ROS Service/Action layers resulting in significantly faster performance.

.. toctree::
   :maxdepth: 1

   doc/robot_model_and_robot_state/robot_model_and_robot_state_tutorial
   doc/planning_scene/planning_scene_tutorial
   doc/planning_scene_monitor/planning_scene_monitor_tutorial
   doc/planning_scene_ros_api/planning_scene_ros_api_tutorial
   doc/motion_planning_api/motion_planning_api_tutorial
   doc/moveit_cpp/moveitcpp_tutorial

Integration with a New Robot
----------------------------
Before attempting to integrate a new robot with MoveIt 2, check whether your robot has already been setup (see the `list of robots running MoveIt <http://moveit.ros.org/robots/>`_). Otherwise, follow the tutorials in this section to integrate your robot with MoveIt (and share your results on the MoveIt mailing list)

.. toctree::
   :maxdepth: 1

   doc/urdf_srdf/urdf_srdf_tutorial

**Note:** The list of the robots above are for MoveIt, a list is on the works for MoveIt 2.

Miscellaneous
----------------------------

.. toctree::
   :maxdepth: 1

   doc/realtime_servo/realtime_servo_tutorial
=======
   doc/tutorials/tutorials
   doc/how_to_guides/how_to_guides
   doc/concepts/concepts
   doc/how_to_contribute/how_to_contribute
   doc/examples/examples
   doc/api/api
>>>>>>> f680cbe (Api Documentation CI (#310))

Attribution
-----------

Some major past contributors to the MoveIt tutorials are listed in chronological order: Sachin Chitta, Dave Hershberger, Acorn Pooley, Dave Coleman, Michael Gorner, Francisco Suarez, Mike Lautman, Tyler Weaver, David Lu!!, Vatan Tezer, and Andy Zelenak. These are just some of the `46+ Contributors over the years <https://github.com/ros-planning/moveit2_tutorials/graphs/contributors>`_ who have a big impact on this documentation.

Help us improve these docs and we'll be happy to include you here also!

**Corporate Sponsorship**

* The tutorials had a major update in 2018 during a code sprint sponsored by Franka Emika in collaboration with PickNik Robotics (`Check out the blog post! <http://moveit.ros.org/moveit!/ros/2018/02/26/tutorials-documentation-codesprint.html>`_)
* The tutorials had another major update in 2022 during a doc-a-thon sponsored by PickNik Robotics
