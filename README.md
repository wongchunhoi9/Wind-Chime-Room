# Wind Chime Room (Title TBC)

[working note](https://www.notion.so/ioior/idea-Room-wind-chime-playlist-experiential-website-56e650d1bd464ef7ba0dafb3d4a9bb66)
## First build by trying out this Tutorial Video: 

*Unity 3D / 5 - Wind and RigidBody (Download)*
[Video link](https://www.youtube.com/watch?v=iD_iwP-jkeM&fbclid=IwAR0ZCGORwru2Qr_halsAM-7sWvv2-HD8vOhaw7ELiTr1pmhu37ARhy3SAbM\)

In the Scene *Room windzone test* ,   rotate the game object **Wind.Remote.control** to move around the wind direction.
A tree on the terrane is just for a visualisation of wind. 
Red object can be blown out.

Screenshot:
![2020-05-22](https://raw.githubusercontent.com/wongchunhoi9/Wind-Chime-Room/master/P8-in-progress-1.png "screenshot")
![2020-05-25](https://raw.githubusercontent.com/wongchunhoi9/Wind-Chime-Room/master/P8-in-progress-2.png "screenshot")

## update on 2020-05-26
virtual ***Wind*** force by particle system

   ->**Shuruken Particle system** in Unity   /[Create -> Effect -> Particle System/] 
check-box  
- [x] collision , add a collision force there
- [x] external force 
- [x] reaction with 3D world

## updated on 2020-05-25
Using *Joint* in Unity to connect the objects and manipulated by a adding-force-WIND windzone Object
3 pipes has been added an audio source to just trigger on collision
more fine tune soon and layout of the room later this week. 



## next step:
- to build a wind chime with rope rigging?
- collision programming


## keywords might be useful for 3D builder beginner: 
- 

## Prototype Prototype version idea

1. Unity Version 2018.2.20
2. tree objects (response to wind)  ← need to know how rigid body can collide with wind 
3. or else, assume it is a particle system (like fluid or gas but with transparent texture) 
4. need a inter-collision system in the particles?   
5. room wall & obstacle are rigid body
6. try **wind tunnel** for 3D environment?  ← keywords that articulating between obstacle and wind flow 
7. each pole should be able to interact with each other as well. 
8. ?

