# Game_Engine_Updates
Repo for updating and showcasing new features in my game engine. Source code remains private. 
This project is mainly for education purposes. Any game engine names are just place holders.


UPDATE_00: 
- Implemented the first version of a GUI using IMGUI in order to easily update and tweak scene lightings.
   - Abilty to add: Directional lighting, Point lighting, and Spot lighting
   - Ability to tweak the settings of each type of lighting
- Implemented a 'hirearchy' to show which lights have been added to the scene and allow for selection
  based picking.
  
![AE_01](https://user-images.githubusercontent.com/54217603/104331324-efe0bd00-54bc-11eb-8b87-3cfa4c2ecf5e.gif)


UPDATE_01:
   - Backpack model aquired from LearnOpenGL.com, Artist: Berk Gedik
   - New implementions:
      - Added grid to scene for better orientation while moving around.
      - Changes to the light GUI. Changed from two windows down to one and made selection of lights easier. 
        but bugs remain to iron out and make it more smooth experience of selection.
      - Changes to the way shaders are loaded and applied to models, demostrated with two models being shaded by
        different shaders (one point and the other directional lighting)
      - Ability to load in .obj file models with the assimp library. More work still needed as it doesn't support all formats.


![AE_02](https://user-images.githubusercontent.com/54217603/104759489-fcb81780-572d-11eb-9f47-59fd1d380b1e.gif)


UPDATE_02:
   - Reworking the structure of the source code to better integrate with the GUI and attempt at avoiding circular dependacy.
   - Added functionality for adding multiple scene cameras, as well as:
      - Deleting scene cameras, easy camera selection, adjusting various camera values, hierarchy of all scene cameras
   - Added functionality for adding shaders from file path and to change shaders during run time.

![AE_03](https://user-images.githubusercontent.com/54217603/104824560-c60ef980-5820-11eb-982c-4a64eea76414.gif)
