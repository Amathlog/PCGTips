# PCGTips
Gathering of PCG tips in Unreal Engine published on socials, you'll also find the graph assets in their respective folder. Check this page to know with which version they were generated on.

## Random rotations
If you ever tried to use Transform Points and were sad that you can't provide a Rotation Min/Max for each point, here is a solution!
The gist is to generate a random value for each point, then apply Lerp between max and min provided as attributes!

### Graph
![Alt text](RandomRotations/Graph.jpg?raw=true "Graph")

### Without random rotation
![Alt text](RandomRotations/WithoutRandomRot.jpg?raw=true "WithoutRandomRot")

### With random rotation
![Alt text](RandomRotations/WithRandomRot.jpg?raw=true "WithRandomRot")

### Asset version
5.6
