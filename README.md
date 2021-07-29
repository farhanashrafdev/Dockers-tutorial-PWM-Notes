# Dockers-tutorial-PWM-Notes
Notes i made while learning dockers

Dockers:
A platofrm for building running and shipping applications.
The reason: app works on dev machine not on production application
due to one or more files missiing, software mismatch,different configuration settings.
with docker we package every application with everything it needs, and run on all machines using dockers. production machine doesnt need setup and saves your half day

it runs applications side by side 
one can be on Node 14, one can be on Node 9
we can remove app and all dependecies in a one go.
APPs work in safe isolated enviroment.
Software and devop eng must learn it these days.
VM vs Container:
Container is isolated env running an app.
virtaul machine is abtraction of a machine(physical hardware).

Hypervisors: Virtual box,VM ware, Hyper-v.

Benefit of building virtual machien:
we can run an application in isolation in a virtual machine.
on same physical we can have more then 1 virtual machine all in dif isolated env.
Number of probelsm i9n virtual machine:
each vm needs a full blown os.
slow to start.
resource intensive *need slice of actual hardware).

Containers: allow running multiple apps in isolatio9n
lightwiehgt.
use os of the host.
start quickly.
need less hardware resources.

# Dockers Architecture:
Uses client server architecture.
   
   14:10
