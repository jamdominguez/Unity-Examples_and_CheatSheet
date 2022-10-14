# Unity guide
A bunch of Unity examples to play and test the engine elements and tools. Documentation and cheatsheet.

# Introduction 
Unity is the most popular video game engine. Reason:
- **Free**: It is free at 100k€ of benefist
- **Easy**: No much dificult to learn and use a extended programming language (C#)
- **Versatile**: It is possible build 2D and 3D games

# 1. Install Unity

# 2. Unity Workspace

# 3. Unity Engine Elements
## <u>Sprite</u>
Is a image resource used in the project. The sprites can be used to create animations, background, etc.<br>
Selecting a sprite in Unity browser is possible check his parameters.<br>
If drag and drop into the scene an sprite, automatically a new object is created with the Transform, Sprite Renderer components.<br>

**Relevant Parameters:**
- **Texture Type**: Indicates for what will be used the sprite.
- **Sprite Mode**: Determines the if the sprite is single or composed sprite.
- **Pixels Per Unit**: Determines the sprite size in the scene.
- **Sprite Edtior**: Used to adjust the sprtie or divide composed sprite (Slice > Method > Smart).
- **Filter Moder**: Set a softened type to the sprite (pointer is pixel-art).

![sprite](section3/sprite.png)

## <u>Animation</u>
This element is used to create animations from sprite. Selecting several sprites and clicking right button then Create > Animation.<br>
![animation bunch sprites](section3/animation_1.png)

It is advisable to organize all Animation into same folder. This folder normally is used to store the Animator Controller too.<br>
![animation](section3/animation_2.png)

- **Loop Time**: Determines the animation is shown in loop.

<br>

With double click on the Animation icon the Animation panel will be shown. Here it is possible watch the animation by sprite and Add event in some animation moment. For example at the last of a bullet animation call a function for destroy the object.
- **Function**: Function name
- **Object**: Script where the function is implemented

![animation add event](section3/animation_3.png)

## <u>Animator Controller</u>
This element manage the differents states (with Aimation associated) for a object. It is possible create a Animator Controller clicking right button then Create > Animator Controller, althouhg other way is drag and drop a Animation element into object.<br>
Like with Animation is advisable to organize all Animator Controller into same folder. This folder normally is used to store the Animation too.<br>
With double click on Animator Controller icon the Animator panels appears, showing the Animator states and transitions.

![animatior controller](section3/animatorController_1.png)

It is possible create variable to manage the transition between states.<br>
Clicking in a state it is possible check the Animation (**Motion**) assigned to the state

![animatior controller state](section3/animatorController_2.png)

Clicking in a tansiton (is created with right button on state and Make Transition), can be detemined the parameter values for change the state

![animatior controller transition](section3/animatorController_3.png)

Has Exit Time and Settings > Fixed Duration should be unchecked to avoid transition problems:
- **Has Exit Time**: Trasition has a fixed exit time
- **Fixed Duration**: Transition duration is independent of state length

<br><br>

# 4. Unity Object Components


<br><br>

# 5. C# in Unity
## <u>Public Variables</u>
It is possible create public variable in the script associated to a object. Theses variables can be modyfied from editor inclusive with the game running. Normally are used to:
- Test de variable value in game (screen in red).
- Assign a scene object to the script. It let get the object assigned properties inside the another object script (screen in green).
![publicVariables_1](section5/publicVariables_1.png) ![publicVariables_1C](section5/publicVariables_1C.png)
<br>
![publicVariables_2](section5/publicVariables_2.png) ![publicVariables_2C](section5/publicVariables_2C.png)

<br><br>

# 6. CheatSheet
## 6.1. Engine Elements
## 6.2. Object Components
## 6.3. Classes
## 6.4. Relevant Functions and Parameters
## 6.5. Hot Keys