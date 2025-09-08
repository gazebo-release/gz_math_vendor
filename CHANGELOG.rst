^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gz_math_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.0 (2025-09-08)
------------------
* Jetty support: bump to 9.0.0, fix package names (`#12 <https://github.com/gazebo-release/gz_math_vendor/issues/12>`_)
  * Jetty support: bump to 9.0.0, fix package names
  Major version numbers have been removed from package
  names in Gazebo Jetty, so extra cmake config files are
  no longer needed.
  * Add option VENDOR_FROM_LIB_VCS_REF
  This allows vendoring from a specified vcs ref instead
  of the hard-coded tag. When this option is set to true,
  a branch, tag, or commit can be specified in the
  LIB_VCS_REF variable. If LIB_VCS_REF is unspecified,
  vendoring will use main.
  * remove unused cmake config file
  * use lowercase to fix linter complaint
  * build python bindings
  * 9.0.0~pre1
  ---------
* Contributors: Steve Peters

0.3.1 (2025-05-23)
------------------
* Bump version to 8.2.0 (`#11 <https://github.com/gazebo-release/gz_math_vendor/issues/11>`_)
* Contributors: Ian Chen, Jose Luis Rivero

0.3.0 (2025-04-28)
------------------

0.2.3 (2025-02-19)
------------------
* Bump version to 8.1.1 (`#10 <https://github.com/gazebo-release/gz_math_vendor/issues/10>`_)
* Contributors: Carlos Agüero

0.2.2 (2024-12-13)
------------------
* Bump version to 8.1.0 (`#8 <https://github.com/gazebo-release/gz_math_vendor/issues/8>`_)
  * This is a rerelease since #7 did not actually bump the version of the vendored package.
* Contributors: Addisu Z. Taddese

0.2.1 (2024-12-02)
------------------
* Bump version to 8.1.0 (`#7 <https://github.com/gazebo-release/gz_math_vendor/issues/7>`_)
* Contributors: Michael Carroll

0.2.0 (2024-09-30)
------------------
* Bump version to 8.0.0 (`#5 <https://github.com/gazebo-release/gz_math_vendor/issues/5>`_)
* Apply prerelease suffix (`#4 <https://github.com/gazebo-release/gz_math_vendor/issues/4>`_)
* Upgrade to Ionic
* Contributors: Addisu Z. Taddese

0.1.1 (2024-07-15)
------------------
* Update vendored package version to 7.5.0
* Contributors: Addisu Z. Taddese

0.1.0 (2024-04-23)
------------------
* Use an alias target for root library
* Contributors: Addisu Z. Taddese

0.0.4 (2024-04-10)
------------------
* Add support for the `<pkg>::<pkg>` and `<pkg>::all` targets, fix sourcing of dsv files
* Contributors: Addisu Z. Taddese

0.0.3 (2024-03-29)
------------------
* Disable SWIG to fix CMake warning
* Contributors: Addisu Z. Taddese

0.0.2 (2024-03-28)
------------------
* Disable pybind11 for now
* Require calling find_package on the underlying package (`#2 <https://github.com/gazebo-release/gz_math_vendor/issues/2>`_)
* Fix linter (`#1 <https://github.com/gazebo-release/gz_math_vendor/issues/1>`_)
* Remove Nate
* Update maintainers
* Initial import
* Contributors: Addisu Z. Taddese
