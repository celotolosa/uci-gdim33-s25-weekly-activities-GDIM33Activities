[GDIM 33 In class Notes.pdf](https://github.com/user-attachments/files/26767307/GDIM.33.In.class.Notes.pdf)
# GDIM 33 In-Class Activities
## W1
### Activity 1
([Marcelo Brainstorm]https://docs.google.com/drawings/d/1vbrhy8JUdhXs2NTZnbxYpjGCjTQEwvrmczOQLUz7ky4/edit?usp=sharing)

1. The patterns emerging from my inspiration involve horror and blood loss, where the user must win minigames in order to prevent blood loss.
2. 2 of my groupmates and I are doing 3D horror games where we're all interested in having scary themes. My personal style and interests involve mechanics that keep you alive similar to Kai's game where the player must be heavily attentive to the world's surroundings involving heavy attentiveness.
3. Eric likes first person shooter games where his favorite game is Overwatch. Personally, I also love FPS games, where my favorites include Valorant, and Overwatch.


### Activity 2
([Activity 2 breakdown] https://docs.google.com/drawings/d/1Uycbb-Rh2sH7v_BpP8sE25FD3RBjTPwPx1a4TdFzBns/edit)


## W2
Write your W2 Devlog here.

Continue adding additional headers below this one for future weeks and future activities.

## W3

### Activity 1
[GDIM 33 In class Notes.pdf](https://github.com/user-attachments/files/26767320/GDIM.33.In.class.Notes.pdf)

### Activity 2:
1- You can create it in the game controller and access it through the walrus
2- Using at least one Debu.Log() helped with my test in my graphs to let me know whether an event was being triggered or not
3- The set cursor lock state is relevant to my vertical slice because my PC will be talking to NPC's
4- Game state is relevant to my vertical slice because certain states will restrict my user from doing things. Many states have to be mutually exclusive.

## W4

### Activity 1: 
My playtesting goal is to figure out what else to add on top of what I have besides movement and being able to look around, additionally implementing movement relative to where I am looking. Currently, the user can move forward, backwards and side to side, but while the camera moves, the player body doesn't move relative to the camera position (where the camera is facing). I would like to fix this issue for the milestone assignment. 
Playtest notes:
add rigidbody, fix camera, add timer and different finite state machines

### Acitvity 2:

1. Yes because the logic uses scriptable objects which can store data and add more
2. There is no limit to the amount of dialogue nodes that the writer could create without writing any code
3. It also helps fix issues where nodes are missing, broken, or showing errors because the script changed

## W5

### Activity 0:

Navmesh table

### Activity 1:

1. Add Navmesh/NavMeshAgent
    1. In the inspector wnidow, Add component
    2. Select Navigation > NavMesh Surface
    3. Specify details in the settings
    4. click Bake
    5. Creating NavMeshAgent
        1. Create a game object, and add the navmesh agent component (Component > Navigation > NavmeshAgent)
2. Test NavmeshAgent navigation
    1. using the transform of a "dummy"
        1. Test the navmesh agent to move towards said "dummy"
        2. make sure it works
    2. change the "goal" to the player transform.
3. Work on Raycasting
    1. Get the sourceposition, targetposition, and hit set up
    2. Script and plug in values in the inspector.

### Activity 2:

In class, I created the NavMesh Surface as well as a NavMesh Agent for the NPC who follows the player around. I got it to follow a specific target before following a player, and will implement random locations before the player can find them. Additionally, I implemented a raycast system to detect when the NPC finds the player, and diffeernt outputs will happen in further sessions.

## W6

### Activity 1:

Playtesting goals include finding bugs in the movement of my player character, as well as what can be improved visually regarding the map. I currently don't have a map that I have completed, but I wanted to use cave assests to create an eerie environment. Currently have the mechanics down, but I will have the NPC dialogue and Nodes ready for next week. 

What is NEW? 
Animations (walking/idle) for both NPC and Player
Chasing state for NPC that stops when within a certain distance
New map assets (cave)

([Playtest 2 Link]https://celotolosa.itch.io/playtest-2)

Playtest Notes:
Users who played my game mentioned that I need a gameplay loop, and I need to finish creating my map. I also need to finish creating the NPC dialogue and find out how to create a minigame by the next playtest. Just doing NPC dialogue isn't enough. I will definitely dedicate much more time to the creation of the next build. For now, I need to create a map that one can navigate, create VFX, have NPC Dialogue, and have the minigame at least STARTED.

### Activity 2:
1. The multiply setting of the blend node make the resulting color darker and less saturdated because it multiplies the values of the RGB, making the color more dull
2. If we use multiply to combine alpha values, I believe the resulting value will be more transluscent, because when the alpha value increases, it becomes more oqaque.
3. The Shader gets these UV Vvalues from the material
4. Yes it sounds interesting!

## W7

1. The vertex color data comes from the mesh itself, each vertex in the Shiba mesh stores types of data: position, normal, tangent, color and UV
2. Even though color is stored per - vertex the GPU interpolates values across the surface of each polygon between adjacent vertics. The fragment shader recieves a blended mix of each color
3. Vertex color resolution is limited by the number of vertices on the mesh and get one color value per vertex. A textrue gives more detail, while vertex color might be useful for things like color region masking
4. Yes, the shiba's back-left leg shows a slight bug in normal view. The normals on that part may be incorrect
5. UV coordinates would be a userful one to visualize. The map of the U and V values can be mapped to the R and G channels
6. The back left leg is inforrect vertex normals since the lighting calculation uses those normals to determine how much light hits the surface
7. Additie blending allows for the shader's output color on top of what is already in the frambuffer behind it rather than replacing it.

## W8

### Activity 1:
Playtest goals:
- I want to know how the movement is
- what can I do to the UI to improve it/polish
- How can the UI in the dialogue be improved
- any bugs?

Playtest Notes:
- Fix typo
- Fix camera rotation to see the user rather than just the sky
- Possibly make character a little smoother
- make player chocies in the middle of the screen rather than to the left

### Activity 2C:

1. The name of the pass created is called FinalBlit. I can tell by clicking on the pass
2. When the float is changed in lerp from 0, 0.5, and 1, the "opaque-ness" of the cobllestone effect changes with every value change.
3. The Lerp value changes the opaqueness of the fullscreen effect.
4. The algorithm for the lerp armount uses (sin(time) +1) /2 instead of sin(time) because sin(time) + 1 /2 takes values between 0-1.

## W9

Wasn't in class, got excused

## W10

### Activity 1:
Playtest goals:
- Find any bugs that make the game feel "unnatural" or buggy
- How is the lighting?
- What type of music would go well with the game (genre-wise)
- Is the sensitivity too high or low?
- Is the white dialogue background too contrasting?
- Is the minigame fun?

NEW BUILD: ([Week 10 Playtest link]https://celotolosa.itch.io/week-10-playtest)



