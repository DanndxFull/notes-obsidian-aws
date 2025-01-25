## USceneComponent

![[Pasted image 20250122150351.png]]

Every actor has a Root Component

### How to create Components and attach them to other componets of the same actor

![[Pasted image 20250122160512.png]]

First you have to create all those variables for the components to your Actor, and after create the pointer for the components using each respective class you have to create them into the .cpp file and attach using the construct method.

![[Pasted image 20250122160710.png]]

Using the CreateDefaultSubobject method you can specify the type of component and in the parameters give it a name.

Using the SetupAttachment method you can set the pointer value, it means the component, to another component using the pointer of that component.