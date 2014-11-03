# CentOS Cloud SIG image repository for CentOS-7.

## Docker image creation 

Docker images are built from the kickstarts in the
[sig-cloud-instance-build](https://github.com/CentOS/sig-cloud-instance-build)
repository, using [ami_creator](https://github.com/katzj/ami-creator) 


## Repository Structure

Images in this repository have generic names so that they may be overwritten
as they are updated. In order to track when an image was created, the
timestamp will be placed in the commit message. 

This allows everyone to track when a given image was uploaded, and a rough
idea of the rpms/updates included in that image. 
