This game is still in progress. If you want to play test it, just push the play button, for a full screen experience, go to the main level (third person level) and then press the play button. FYI this game still has no assets, just mechanics. I'm working on it daily and hopefully will have implemented everything soon.

Controls (will probably change them later): 

Jump - Spacebar

Move - Arrows, WASD

Look - Mouse

Crouch - Left Control

Vault - Left Shift (must be near an object of the right height and thickness)

Assassinate/Action Button - Left Mouse

Sprint - Left Shift

Attack - Right Mouse (click again during attack animation to combo)

Caps - Roll

Enemy Target/Enemy Target disable - Z (does have to be within a certain distance and in view of the camera)

Pause - X (you can click the boxes on the side to open the equipment menus)

Bugs: 

Cannot vault over objects when on a platform other than the ground.
***Fixed***If you start a vault before an attack animation finishes, or at least until you hit the end combo notify state, you can no longer attack.
When killing the enemy, there is an invisible hurt box belonging to the enemy that still remains afterwards. Probably just the collider.

Blueprint locations:

Blueprints folder contains some of the main blueprints for the game including camera shake, dummy, attack system, player stats and the assassination interface. All are well commented.

ThirdPerson/Blueprints contains the blueprint for the main third person character. Most of the logic for the main character are here, although it does use other component blueprints.

Characters/Animations/AnimNotifies contains all of the ainim notifies and notify states for the characters.

UI folder contains the widget blueprints for the HUD and health systems

Under the Equipment system folder, you will find the structs, data tables, and enum types of the equipment. You will also find the blueprints for the equipment, equipment widgets, and the equipment component class that contains a lot of the functionality.

Animations: 

Characters/Mannequins/Animations/Manny contains some of the default animation that I used like running, jumping and landing.

Characters/Pirate/Animations is where you will find all the custom animations and montages. The animation blueprint for the main character is also here.

All of the blueprints are well commented and explain how everything connects. I didn't bother explaining the audio, but that's pretty self explanitory. It's all in the Audio folder where you'll find
the sound cues and metasounds as well as the wav and mp3 files. This game demo is constantly being worked on so stay tuned for more updates. I am still in the early phases.
