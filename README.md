![42](img/42Project.png "42")

# miniRT

Project done with [rcollas](https://github.com/rcollas)

*Subject: The goal of the program is to generate images using the Raytracing protocol.
Those computer-generated images will each represent a scene, as seen from a specific
angle and position, defined by simple geometric objects, and each with its own lighting
system.*

Usage:
- cd miniRT && make && ./webserv scenes/*some_scene*
- cd miniRT_bonus && make && ./webserv_bonus scenes_bonus/...

./webserv scenes/plan.rt
![plan](img/plan.png "plan")

./webserv_bonus scenes_bonus/multi.rt
![cone](img/cone.png "cone")

./webserv_bonus scenes_bonus/checker.rt
![checker](img/checker.png "checker")

./webserv_bonus scenes_bonus/earth.rt
![earth](img/earth.png "earth")

./webserv_bonus scenes_bonus/saturn.rt
![saturn](img/saturn.png "saturn")

./webserv_bonus scenes_bonus/solar_system.rt
![solar_system](img/solar_system.png "solar_system")
