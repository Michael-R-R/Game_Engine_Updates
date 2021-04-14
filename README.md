# Game_Engine_Updates
Repo for updating and showcasing new features in my graphics engine. Source code remains private. 
This project is mainly for education purposes. Any graphics engine names are just place holders.


UPDATE_00: 
- Implemented the first version of a GUI using IMGUI in order to easily update and tweak scene lightings.
   - Abilty to add: Directional lighting, Point lighting, and Spot lighting
   - Ability to tweak the settings of each type of lighting
- Implemented a 'hierarchy' to show which lights have been added to the scene and allow for selection
  based picking.
  
![AE_01](https://user-images.githubusercontent.com/54217603/104331324-efe0bd00-54bc-11eb-8b87-3cfa4c2ecf5e.gif)


UPDATE_01:
   - Backpack model aquired from LearnOpenGL.com, Artist: Berk Gedik
   - New implementions:
      - Added grid to scene for better orientation while moving around.
      - Changes to the light GUI. Changed from two windows down to one and made selection of lights easier. 
        But, bugs remain to iron out and make it more smooth experience of selection.
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


UPDATE_03:
   - Added in the functionality to update vertex and fragment shader files during run time within the engine.
   - Added in the functionality to load in models from the GUI.
      - Ability to assign different shaders to different models and render correctly
      - Ability to adjust model properties indivudally.
   - Made the grid a default mesh and shader attached to it. User is not allowed to delete the grid or grid shader.

![AE_04](https://user-images.githubusercontent.com/54217603/104964444-6cd2d180-59aa-11eb-924a-672d6d4515de.gif)

UPDATE_04:
   - Documented all the current code.
   - Fixed some syntax conventions.
   - Started another semester of college, Spring 2021, so updates will roll out slower. I will only get to work on the project 
     a little bit during the week, but plan on dedicating some time to work on the engine on Saturdays and Sundays
     as long as time allots.
   - TODO NEXT:
      - Create a gui file explorer to more easily load in shaders and models.
