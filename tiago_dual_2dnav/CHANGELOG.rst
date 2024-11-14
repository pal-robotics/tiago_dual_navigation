^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package tiago_dual_2dnav
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.5.0 (2024-11-14)
------------------
* Merge branch 'aca/feat/nav-params' into 'humble-devel'
  feat nav-params
  See merge request robots/tiago_dual_navigation!32
* using TiagoDualArgs
* linters
* using new architecture
* removed advanced_navigation rviz config
* Contributors: andreacapodacqua, antoniobrandi

4.4.0 (2024-10-25)
------------------
* Merge branch 'fix/aca/mppi-omni' into 'humble-devel'
  mppi omni
  See merge request robots/tiago_dual_navigation!30
* mppi omni
* Merge branch 'abr/feat/use-mppi' into 'humble-devel'
  Use mppi
  See merge request robots/tiago_dual_navigation!29
* Use mppi
* Contributors: andreacapodacqua, antoniobrandi

4.3.0 (2024-10-23)
------------------
* Merge branch 'feat/aca/omni-navigation-mppi' into 'humble-devel'
  Using MPPI
  See merge request robots/tiago_dual_navigation!28
* Using MPPI
* Contributors: andreacapodacqua

4.2.1 (2024-09-23)
------------------
* Merge branch 'fix/aca/dep' into 'humble-devel'
  fix dep
  See merge request robots/tiago_dual_navigation!27
* fix dep
* Contributors: andreacapodacqua, thomaspeyrucain

4.2.0 (2024-07-30)
------------------
* Merge branch 'air/feat/unify_pkgs' into 'humble-devel'
  Restructure launch file
  See merge request robots/tiago_dual_navigation!26
* Unify quotation marks
  Unify quotation marks
* fix robot name to tiago_dual
* Restructure launch file
* Contributors: Aina, antoniobrandi

4.1.3 (2024-07-19)
------------------
* Merge branch 'fix/aca/laser-frames' into 'humble-devel'
  fix laser frames
  See merge request robots/tiago_dual_navigation!25
* fix laser frames
* Contributors: andreacapodacqua

4.1.2 (2024-07-15)
------------------
* Merge branch 'feat/aca/using-pipelines' into 'humble-devel'
  using variables for pipelines
  See merge request robots/tiago_dual_navigation!24
* fix robot_radius
* using variables for pipelines
* Contributors: andreacapodacqua

4.1.1 (2024-07-09)
------------------
* Add warning for pal_module_cmake not found
* fix: replace diff_base by pmb2 as base_type
* feat: ros2 support for laser navigation
* Initial ROS2 commit
* Contributors: Noel Jimenez, josegarcia

1.2.0 (2023-12-18)
------------------
* Merge branch 'feat/move-base-flex' into 'erbium-devel'
  using move base flex
  See merge request robots/tiago_dual_navigation!11
* using move base flex
* Contributors: antoniobrandi

1.1.9 (2023-04-21)
------------------

1.1.8 (2023-04-19)
------------------

1.1.7 (2023-03-23)
------------------

1.1.6 (2023-03-15)
------------------

1.1.5 (2023-03-08)
------------------

1.1.3 (2023-03-06)
------------------

1.1.2 (2023-01-30)
------------------
* Merge branch 'feat/map-manager' into 'erbium-devel'
  move to map manager
  See merge request robots/tiago_dual_navigation!10
* move to map manager
* Contributors: antoniobrandi

1.1.1 (2022-06-20)
------------------
* replaced teb by pal local planner
* Contributors: josegarcia

1.1.0 (2021-11-03)
------------------
* Merge branch 'omni_base_robot' into 'erbium-devel'
  tiago dual navigating with omni base
  See merge request robots/tiago_dual_navigation!9
* tiago dual navigating with omni base
* Contributors: antoniobrandi, saikishor

1.0.16 (2020-07-30)
-------------------
* Merge branch 'rename_tf_prefix' into 'erbium-devel'
  Rename tf_prefix param
  See merge request robots/tiago_dual_navigation!8
* Rename tf_prefix param
* Contributors: davidfernandez, victor

1.0.15 (2020-05-14)
-------------------
* updated rviz configs
* Contributors: Procópio Stein, procopiostein

1.0.14 (2020-05-14)
-------------------
* Merge branch 'nav-valid' into 'erbium-devel'
  updated rviz config
  See merge request robots/tiago_dual_navigation!5
* updated rviz config
* Contributors: Procópio Stein, procopiostein

1.0.13 (2020-04-21)
-------------------
* Merge branch 'scripts_tiago_2dnav' into 'erbium-devel'
  Copied scripts and config folder from tiago_2dnav
  See merge request robots/tiago_dual_navigation!4
* remove other scripts except the navigation_camera_mgr
* Copied scripts and config folder from tiago_2dnav
* Contributors: Sai Kishor Kothakota, procopiostein

1.0.12 (2020-01-28)
-------------------
* Merge branch 'remove-tiago-dependency' into 'erbium-devel'
  Remove tiago dependency
  See merge request robots/tiago_dual_navigation!2
* replacing dependency on laser_sensors
* remove unused dependencies and minor fixes
* parsing subtype parameter
* updated launch and package files to bypass tiago dependency
* Contributors: Federico Nardi, Procópio Stein

1.0.11 (2019-09-26)
-------------------
* Readd tiago_dual_maps
* Contributors: Victor Lopez

1.0.10 (2019-09-26)
-------------------
* Add missing dependency
* Contributors: Victor Lopez

1.0.9 (2019-08-07)
------------------
* Merge branch 'fix_navigation' into 'erbium-devel'
  Fixing some name error and launch files due to the refactoring of the tiago_2d_nav
  See merge request robots/tiago_dual_navigation!1
* Fixed the cfg package for the navigation
* Fixing some name error and launch files due to the refactoring of the tiago_2d_nav
* Contributors: Victor Lopez, alessandrodifava

1.0.8 (2019-04-15)
------------------
* Remove tiago_maps and fix install rules
* Add args to navigation.launch
* Initial commit
* Contributors: Victor Lopez
