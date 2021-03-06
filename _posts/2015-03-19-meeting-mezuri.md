---
title: Status update on Mezuri
author: Dav Clark
layout: meeting
---
## In attendance

 - Matt Podolsky (TIER / Mezuri)
 - Dav Clark (D-Lab, BIDS)

## Notes

Mezuri is focused on data integration / modeling. Remote sensing + sensor
functionality would be awesome. Mezuri will not work on controlling sensors
remotely from an integrated platform.

ODK sensors may do this (use bluetooth LE to speak to arduino sensors). Note -
we are working on doing this in Glass Bead Labs. Need to package a new APK for
the ODK sensors app. Also do OTA bluetooth upgrades. This work may not be
completed / polished.

Javier working on demand / response stuff for energy grids.

Rohid may be working on this still up at Washington. Ask Waylon if it's worth
talking to anyone about this.

### Focus

How to store and process data from sensors (you get stuff out of deployment area
on your own).

Currently, there are performance issues and missing features. Focus on
performance (moving data out of data store to docker container is slow, sending
back also?).

Big feature - more support for metadata, just as query-able.

Goal is to have re-usable tasks via the Mezuri platform. **How do we share
projects?**

Detecting when a "cooking event" happens using machine learning.

Looking at refridgeration sensors in nicaragua.

Set up flux boxes to shut off power (or change set-point temp) to fridge to
reduce demand on grid, or optimize pricing. Can we coordinate entire "fleets" of
fridges?

Parameters can be tuned / updated remotely.

Javier and U Mich group - work with tiny OS, terraswarm. NoSQL streaming data
w/o much querying or historical processing.

Javier has worked with bitsync (or bit torrent) to cloud, when phones don't have
access to internet, but a base workstation does. Want more of a LIFO view for
realtime data (but back-fill when you can). Built on Rabbit MQ.

David Culler working with LoCAL - talk to him about what we should do w/
sensors.

Campus limited SI^2 proposal. Only allowed to submit one to each type.

### Really useful outcomes (potential TODOs)

DOCUMENT EXISTING PROJECTS - maybe we can get reproducibility group from BIDS
involved in this? Note the incredible complexity that goes into, e.g., counting
cooking events!

Get a talk in BIDS about existing projects in TIER - talk about existing work
with OpenRefine, it'd be nice to do something similar with IPython (etc.).
Sounds like they need to learn to use version control! It'd be good for Eric and
Fernando to be in touch about THIS.

Maybe figure out ways to integrate Mezuri into the S2I2 grant? might also be
good to bring in UW and UCSD.
