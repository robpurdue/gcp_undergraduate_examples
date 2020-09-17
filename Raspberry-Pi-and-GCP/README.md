# Projects for CSI4900/5900 at Oakland University

These project were developed to get students thinking about how you can leverage Google Cloud from the constraints of a microcomputer, such as a Raspberry Pi.

## Lab Overviews

* [Compute Engine VM Setup (Ubuntu + Windows)](https://docs.google.com/document/d/1milnVxYIhTioB10vyhsUx91jpjiE0KIGjWffweNbJf0/edit?usp=sharing) 

    * This lab has the student get up and running with the Compute Engine for virtual machines.  They setup an Ubuntu web server using the free microinstance and then setup a Windows Server using a non-free instance (with hopefully sufficient warnings to shut it down once they're done).  The lab was given to multiple years of students in a System Adminstration course sequence.

* [CloudPi](https://docs.google.com/document/d/1C6vvCtzFoL9c10yp2gD-V340VPaSfjGXJEwAezE-No0/edit?usp=sharing): This assignment has the student setting up access to Google Cloud from a Raspberry Pi (using Raspbian).  It leverages the Vision API for performing image recognition tasks (loading files, however since it is on a Pi you could redirect an image from a camera) and interacting with BigQuery to parse out GitHub text for data mining.  Note: this lab was last run in Winter 2020 -- if any of the credential flows or BigQuery hooks have changed (and they most likely have), then the lab needs to be updated to suit your purposes.  The lab was given to both undergraduate and graduate students in a special topics class on software engineering for cyber-physical systems.


