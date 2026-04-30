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
3. Work on Raycastaing
    1. Get the sourceposition, targetposition, and hit set up
    2. Script and plug in values in the inspector.


