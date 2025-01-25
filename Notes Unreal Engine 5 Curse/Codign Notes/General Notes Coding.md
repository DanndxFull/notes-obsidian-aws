## Coding notes
To create a c++ class select "Tools" and "New c++Class"

![[Pasted image 20241210163511.png]]

It creates you a .cpp and a .h file
the .h file for the methods and variables
the .cpp file for the logic

After that to use this in unreal you have to run Terminal->Run build terminal task into the VS Code to build that file in unreal
![[Pasted image 20241210163837.png]]

To make appear this variable in unreal editor use UPROPERTY(EditAnywhere):
![[Pasted image 20241210164007.png]]

To compile and update the code for unreal you have to press the next button on the Bottom-Right place on the screen
![[Pasted image 20241211161657.png]]
Tick Method is like update method for unity, its called every frame

To create and use functions in unreal  first declare it
![[Pasted image 20241220153848.png]]
Then use it with the name of the class like this
![[Pasted image 20241220153915.png]]

if our character can't go upward stairs you can adapt the blueprint class of the player in the Walkable Floor Angle to walk in harder angles
![[Pasted image 20241220173503.png]]

### Uproperty types

![[Pasted image 20250122162701.png]]


Links

[[Pointers & References]]
[[Combine Code With Blueprints]]
[[Process of compilation]]
[[Debugs in Unreal Engine]]