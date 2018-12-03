^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package dbw_fca_can
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.2 (2018-10-23)
------------------
* Updated firmware versions
* Added platform FCA_WK2 (Jeep Grand Cherokee)
* Force forwarding of brake command type when ABS module is present (instead of BPEC module)
* Disengage on any fault for brake/throttle/steering (change AND to OR)
* Added cruise control buttons
* Latch firmware version on any change (previously only latched once)
* Changed pedal_luts default from true to false (forward command type by default now)
* Disregard overrides on unused subsystems using the TIMEOUT bit
* Removed cruise control related buttons that are not implemented by firmware at this time
* Fixed typo in nodelets.xml of dbw_fca_can
* Renamed steering CMD_TYPE and TMODE
* Set CXX_STANDARD to C++11 only when necessary
* Use sign of wheel speeds to set sign of vehicle speed
* Removed unused dependencies and includes
* Removed steering debug message
* Handle version message with a map/database of several platform/module combinations (ported from dbw_mkz_can)
* Contributors: Kevin Hallenbeck, Micho Radovnikovich

0.0.1 (2018-08-08)
------------------
* Initial release
* Contributors: Kevin Hallenbeck
