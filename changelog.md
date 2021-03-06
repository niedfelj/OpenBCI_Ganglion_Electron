# 0.4.1

### New Features
* BLE error on start up now sends error 

### Bug Fixes
* Fixes #12 - Absorb 'no valid USB' found and send log

# 0.4.0

### Breaking Changes
* Changed name of built app from `Ganglion Hub` to `GanglionHub`. 

### Bug Fixes
* On client leave if ganglion is connected, the connection will close.

# 0.3.1

### Enhancements
* Building the proper builds by tweaking appveryor. 

# 0.3.0

### Enhancements
* Standardization of Specification. 

### Breaking changes
* Accelerometer, Impedance, and Sample data all have specific success error codes: 202, 203, and 204 respectively. Prior to this version all were using the same 200 code. 

# 0.2.3

### Enhancements
* Calling connect with device name now performs a scan to ensure that device is really still available to connect to.

### Bug Fixes
* Calling connect with timeout caused another bug, for timeout.

# 0.2.2

### Enhancements
* Bump `openbci-ganglion` to `0.4.1`.
* Calling connect now has a timeout!

### Bug Fixes
* Dropped connections now eject a message out to connected client.

# 0.2.1

### Bug Fixes
* `ganglionFound` event emitter was not removed on start of new scan.

### Enhancements
* Disabled verbose print out for production build.
* Bump `openbci-ganglion` to `0.3.8`.

# 0.2.0

### Bug Fixes
* Disconnect did not clean up event emitters added in connect.

### Enhancements
* Bump `openbci-ganglion` to `0.3.7`

# 0.1.6

### Enhancements
* Bump `openbci-ganglion` to `0.3.6`

### Bug Fixes
* Ganglion would not disconnect.
* Change Appveyor to Node 6

# 0.1.5

### Enhancements
* Bump `openbci-ganglion` to `0.3.3`

### Bug Fixes
* Ganglion could not stop seaching.

# 0.1.4

### New Features
* Add Accel

### Bug Fixes
* Ganglion could not connect twice.

# 0.1.3

### Bug Fixes
* Add accelerometer data flow
* Bump ganglion node to `0.3.0`

# 0.1.2

### Bug Fixes
* Fix bug with undefined impedance

# 0.1.1

### Enhancements
* Update to use 18 bit compression.
* Update to v0.2.0 of `openbci-ganglion`.
* Fix bug in impedance sending.

# 0.1.0

* Initial Release