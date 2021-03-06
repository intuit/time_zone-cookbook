[![Build Status](https://secure.travis-ci.org/intuit/time_zone-cookbook.png)](http://travis-ci.org/intuit/time_zone-cookbook)

**!!! This project has been deprecated.  We recommend you search the [Chef Supermarket ](https://supermarket.chef.io/) for a supported alternative !!!**

# time_zone cookbook
Configures the OS time zone

# Requirements
* Chef 10.x

Platform:
* CentOS 6.x
* RHEL 6.x

# Usage
Add the time_zone cookbook to your role/run_list. Typically this requires a
reboot. We currently use this cookbook in the building of our images/AMIs to
avoid this.

# Attributes
* ```node['time_zone']``` - The time zone to set for the OS. The default is
'UTC'

# Recipes
## default
Sets the the OS time zone

# Authors
* Thomas Bishop (@thbishop)
* Brett Weaver (@brettweavnet)
