# CARLA文档

欢迎浏览CARLA文档.

这个是[CARLA文档](https://carla.readthedocs.io/)的中文翻译版本，欢迎大家跟我一起翻译这个文档

这个主页包含一个索引，其中包含文档中不同部分的简要描述。你可以随意按照自己喜欢的顺序阅读。但是无论如何，这里有一些对新人的建议.

* __安装 CARLA.__ 要么遵循[快速启动安装](start_quickstart.md)来获得CARLA发布，要么遵循[构建](build_linux.md)来获得所需平台.
* __使用 CARLA.__ 标题为[第一步](core_concepts.md)的章节介绍了最重要的概念.
* __查看 API.__ 有一个方便的[Python API参考](python_api.md)来查找可用的类和方法.

在阅读过程中，您可以在CARLA论坛上提出任何疑问或建议.
<div class="build-buttons">
<a href="https://github.com/carla-simulator/carla/discussions/" target="_blank" class="btn btn-neutral" title="Go to the latest CARLA release">
CARLA forum</a>
</div>

<br>

!!! 警告
    __更改文档版本以适应您正在使用的CARLA版本__. 使用此窗口右下方的面板可以更改为以前的版本. __最新版本__ 指向`dev`分支中的文档，可能涉及当前正在开发且在任何 CARLA 打包版本中 __不可用__ 的功能，以及一般文档改进 ![docs_version_panel](img/docs_version_panel.jpg) __（这部分仅仅是翻译原文，由于本人能力有限，所以只翻译0.9.13版本的文档，其他版本的文档请查看原文）__.

---


## Getting started

[__Introduction__](start_introduction.md) — What to expect from CARLA.  
[__Quick start package installation__](start_quickstart.md) — Get the CARLA releases.  


## Building CARLA

[__Linux build__](build_linux.md) — Make the build on Linux.  
[__Windows build__](build_windows.md) — Make the build on Windows.  
[__Update CARLA__](build_update.md) — Get up to date with the latest content.  
[__Build system__](build_system.md) — Learn about the build and how it is made.  
[__CARLA in Docker__](build_docker.md) — Run CARLA using a container solution.  
[__F.A.Q.__](build_faq.md) — Some of the most frequent installation issues.  


## First steps
[__Core concepts__](core_concepts.md) — Overview of the basic concepts in CARLA.  
[__1st. World and client__](core_world.md) — Manage and access the simulation.  
[__2nd. Actors and blueprints__](core_actors.md) — Learn about actors and how to handle them.  
[__3rd. Maps and navigation__](core_map.md) — Discover the different maps and how do vehicles move around.  
[__4th. Sensors and data__](core_sensors.md) — Retrieve simulation data using sensors.  

## Advanced concepts
[__OpenDRIVE standalone mode__](adv_opendrive.md) — Use any OpenDRIVE file as a CARLA map.  
[__PTV-Vissim co-simulation__](adv_ptv.md) — Run a synchronous simulation between CARLA and PTV-Vissim.  
[__Recorder__](adv_recorder.md) — Register the events in a simulation and play it again.  
[__Rendering options__](adv_rendering_options.md) — From quality settings to no-render or off-screen modes.  
[__RSS__](adv_rss.md) — An implementation of RSS in the CARLA client library.  
[__Synchrony and time-step__](adv_synchrony_timestep.md) — Client-server communication and simulation time.  
[__Benchmarking Performance__](adv_benchmarking.md) — Perform benchmarking using our prepared script.  
[__CARLA Agents__](adv_agents.md) — Agents scripts allow single vehicles to roam the map or drive to a set destination.  

## Traffic Simulation

[__ Traffic Simulation Overview__](ts_traffic_simulation_overview.md) — An overview of the different options available to populate your scenes with traffic  
[__Traffic Manager__](adv_traffic_manager.md) — Simulate urban traffic by setting vehicles to autopilot mode.  
[__SUMO co-simulation__](adv_sumo.md) — Run a synchronous simulation between CARLA and SUMO.  
[__Scenic__](tuto_G_scenic.md) — Follow an example of defining different scenarios using the Scenic library.  

## References
[__Python API reference__](python_api.md) — Classes and methods in the Python API.  
[__Blueprint library__](bp_library.md) — Blueprints provided to spawn actors.  
[__C++ reference__](ref_cpp.md) — Classes and methods in CARLA C++.  
[__Recorder binary file format__](ref_recorder_binary_file_format.md) — Detailed explanation of the recorder file format.  
[__Sensors reference__](ref_sensors.md) — Everything about sensors and the data they retrieve.  

## Plugins
[__carlaviz — web visualizer__](plugins_carlaviz.md) — Plugin that listens the simulation and shows the scene and some simulation data in a web browser.  

## ROS bridge
[__ROS bridge documentation__](ros_documentation.md) — Brief overview of the ROS bridge and a link to the full documentation  

## Custom Maps

[__Overview of custom maps in CARLA__](tuto_M_custom_map_overview.md) — An overview of the process and options involved in adding a custom, standard sized map  
[__Create a map in RoadRunner__](tuto_M_generate_map.md) — How to generate a customs, standard sized map in RoadRunner  
[__ Import map in CARLA package__](tuto_M_add_map_package.md) How to import a map in a CARLA package  
[__Import map in CARLA source build__](tuto_M_add_map_source.md) — How to import a map in CARLA built from source  
[__Alternative ways to import maps__](tuto_M_add_map_alternative.md) — Alternative methods to import maps  
[__ Manually prepare map package__](tuto_M_manual_map_package.md) — How to prepare a map for manual import  
[__Customizing maps: Layered maps__](tuto_M_custom_layers.md) — How to create sub-layers in your custom map  
[__ Customizing maps: Traffic lights and signs__](tuto_M_custom_add_tl.md) — How to add traffic lights and signs to your custom map  
[__ Customizing maps: Road painter__](tuto_M_custom_road_painter.md) — How to use the road painter tool to change the apearance of the road  
[__Customizing Maps: Procedural Buildings__](tuto_M_custom_buildings.md) — Populate your custom map with buildings  
[__ Customizing maps: Weather and landscape__](tuto_M_custom_weather_landscape.md) — Create the weather profile for your custom map and populate the landscape  
[__Generate pedestrian navigation__](tuto_M_generate_pedestrian_navigation.md) — Obtain the information needed for walkers to move around.  

## Large Maps

[__Large maps overview__](large_map_overview.md) — An explanation of how large maps work in CARLA  
[__Create a Large Map in RoadRunner__](large_map_roadrunner.md) — How to create a large map in RoadRunner  
[__Import/Package a Large Map__](large_map_import.md) — How to import a large map  
## Tutorials — General
[__Add friction triggers__](tuto_G_add_friction_triggers.md) — Define dynamic box triggers for wheels.  
[__Control vehicle physics__](tuto_G_control_vehicle_physics.md) — Set runtime changes on a vehicle physics.  
[__Control walker skeletons__](tuto_G_control_walker_skeletons.md) — Animate walkers using skeletons.  
[__Generate maps with OpenStreetMap__](tuto_G_openstreetmap.md) — Use OpenStreetMap to generate maps for use in simulations.  
[__Retrieve simulation data__](tuto_G_retrieve_data.md) — A step by step guide to properly gather data using the recorder.  
[__CarSim Integration__](tuto_G_carsim_integration.md) — Tutorial on how to run a simulation using the CarSim vehicle dynamics engine.  
[__RLlib Integration__](tuto_G_rllib_integration.md) — Find out how to run your own experiment using the RLlib library.  
[__Chrono Integration__](tuto_G_chrono.md) — Use the Chrono integration to simulation physics  
[__Build Unreal Engine and CARLA in Docker__](build_docker_unreal.md) — Build Unreal Engine and CARLA in Docker  

## Tutorials — Assets
[__Add a new vehicle__](tuto_A_add_vehicle.md) — Prepare a vehicle to be used in CARLA.  
[__Add new props__](tuto_A_add_props.md) — Import additional props into CARLA.  
[__Create standalone packages__](tuto_A_create_standalone.md) — Generate and handle standalone packages for assets.  
[__Material customization__](tuto_A_material_customization.md) — Edit vehicle and building materials.  

## Tutorials — Developers
[__How to upgrade content__](tuto_D_contribute_assets.md) — Add new content to CARLA.  
[__Create a sensor__](tuto_D_create_sensor.md) — Develop a new sensor to be used in CARLA.  
[__Create semantic tags__](tuto_D_create_semantic_tags.md) — Define customized tags for semantic segmentation.  
[__Customize vehicle suspension__](tuto_D_customize_vehicle_suspension.md) — Modify the suspension system of a vehicle.  
[__Generate detailed colliders__](tuto_D_generate_colliders.md) — Create detailed colliders for vehicles.  
[__Make a release__](tuto_D_make_release.md) — How to make a release of CARLA  

## CARLA Ecosystem

[__Ansys Real Time Radar Model__](ecosys_ansys.md) — Details about the Ansys RTR Webinair  
## Contributing
[__Contribution guidelines__](cont_contribution_guidelines.md) — The different ways to contribute to CARLA.  
[__Code of conduct__](cont_code_of_conduct.md) — Standard rights and duties for contributors.  
[__Coding standard__](cont_coding_standard.md) — Guidelines to write proper code.  
[__Documentation standard__](cont_doc_standard.md) — Guidelines to write proper documentation.  
