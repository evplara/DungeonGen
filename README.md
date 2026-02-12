# 3D Dungeon Generator
This generator creates random cave like structures that can be exported and used in any 3D game/project. 
It does this by:

Starting with a single starting room.

Randomly attaches additional rooms to open doorways.

Makes sure rooms connect properly without overlapping.

Stops once it reaches the chosen number of rooms (or runs out of valid connections).

Seals off any remaining unused doorways with door caps.

# How to Use

## Controls 

(G): Generates Dungeon based off current seed.

(P): Generates Dungeon and changes seed randomly.

(C): Clears the current Dungeon.

Type in the number of rooms in the button in the top left. Click the button to generate a dungeon with the current seed and amount of rooms inputted. (Min: 1, Max: 50)

## How to Download

### Download the zip file of the code from this GitHub page
<img width="1380" height="861" alt="image" src="https://github.com/user-attachments/assets/2aea6e6e-257c-4af6-b6e6-2c0c6163194f" />

### Extract the zip file anywhere and open the DungeonGen.uproject file in Unreal Engine.

<img width="937" height="661" alt="image" src="https://github.com/user-attachments/assets/3c8f8713-8dbb-476e-9ea4-c4798414c1f7" />

### Double click the .uproject file or open it inside Unreal Engine by going to browse and finding where you extracted the file.

# How to Extract Cave Models

### Run the game in the editor viewport and select all the cave files that were generated in the Outliner. These all start with BP_ and either Room, Corridor, or Door.

<img width="1919" height="951" alt="image" src="https://github.com/user-attachments/assets/3326fe12-cfc3-43c5-bfe8-c9c818c7be7c" />

### Once selected, go to the "Actor" tab at the top, look for "Merge Actors" and click "Merge".

<img width="1919" height="886" alt="image" src="https://github.com/user-attachments/assets/6143155b-7e90-4954-a99a-c31b21f13652" />

### It will then prompt you to save the merged file somewhere in the project folder. Save it, and you now have a .uasset file of the cave that was generated.
### If you wish to use this 3D model on another engine or project (Unity, Blender, etc.), you can export it to a .fbx file.
### Right click on the file made in the Content Drawer, go to "Asset Actions" and click on "Export." This will prompt you to save this file as a .fbx file and to be saved anywhere on your device.

<img width="1811" height="994" alt="image" src="https://github.com/user-attachments/assets/315143d0-8d05-4ac1-8a83-d869e05435d3" />
