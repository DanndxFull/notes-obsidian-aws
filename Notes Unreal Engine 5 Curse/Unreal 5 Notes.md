#### Basic concepts and controls

- Unity Gameobjects are Actors in Unreal Engine
- Hold alt and an arrow to move to duplicate
![[Pasted image 20241127163512.png]]
On the Botom View is the outputlog with the console logs 
- Maps Are levels like scenes in unity
- Event Graph is the canvas for blueprints

For Collisions we have to open the prop and select the tipo of collision into a dropdown menu in the top
![[Pasted image 20241202183939.png]]

To add some basic stuff templates like third person controllers go to content draw and the add button bring you the packages to the project
![[Pasted image 20241209181407.png]]

To use a character that you put into a scene and avoid the start player default:
1. Open the blueprint of the character 
2. In details look for the word auto
3. in the Pawn Panel change Auto Possess Player to Player 0
![[Pasted image 20241209181707.png]]

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

## Debugs In Unreal Engine

To make a debug.log as unity in unreal engine you have to write:

UE_LOG(LogTemp,Display,TEXT("Cosa Cosa"));

If you want to declare a string and use it in the debug:

 FString MyString = "My String Value";
 UE_LOG(LogTemp,Display,TEXT("Cosa Cosa: %s"), *MyString);

To create and use functions in unreal  first declare it
![[Pasted image 20241220153848.png]]
Then use it with the name of the class like this
![[Pasted image 20241220153915.png]]

if our character can't go upward staris you can adapt the blueprint class of the player in the Walkable Floor Angle to walk in harder angles
![[Pasted image 20241220173503.png]]
