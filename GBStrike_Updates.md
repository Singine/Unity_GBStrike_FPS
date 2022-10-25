
# GBStrike UPDATES 


### 2022.09.08 ~  2022.09.11

> 1. Sculp <i style="color:white">Character</i> Models with Blender.
> 2. Make Map Structure with Blender.
> 3. Sculp <i style="color:white">Weapons_AK47</i> Models with Blender.
> 4. Import <i style="color:white">Azure SkyBox System</i> into Unity.
> 5. Set the Idle posture and Idle Animation of Character with AK in Unity.

------------

### 2022.09.11

> 1. BEGIN <u><i style="color:orange">'First-person'</i></u> Mode developing.
> 2. Set <u><i style="color:orange">'First-person'</i></u> camera for character.
> 3. Set character's movment and jump without animations.
> 4. Set the Standby posture of Character with AK in Unity.

------------

### 2022.09.12

> 1. ReProgram the Up and Down Controller with <i style="color:white">Armature</i>.
> 2. Set the <a style="color:lightgreen">Crosshair</a> of <u><i style="color:orange">'First-person'</i></u> Mode.
> 3. Program the <a style="color:pink">Raycast</a> between 'shootingPoint' and 'target'.
> 4. Program <i style="color:white">Weapons_AK47</i> shooting logic.

------------

### 2022.09.13

> 1. Sculp <i style="color:white">Weapons_Vector</i> Models with Blender.
> 2. Set the Idle posture and Animation of Character with Vector in Unity.

> 3. Set the Standby posture and Animation of Character with Vector in Unity.
> 4. Learn how to use <a style="color:#000;background-color:#000;">UI Toolkit</a> to set game <a style="color:#75b1ff;">UI</a>.
> 5. Edit <i style="color:white">Weapons_AK47</i> icon in Photoshop.
> 6. Set up <a style="color:#75b1ff;">Weapon & Bullets Infomation UI</a> in bottom-right corner.

------------

### 2022.09.14

> 1. Program the logic of adjusting <a style="color:#75b1ff;">Bullets Infomation UI</a> during the shooting.
> 2. ~~Give up using <a style="color:#000;background-color:#000;">UI Toolkit</a> to build game <a style="color:#75b1ff;">UI</a>.~~
> 3. Use <a style="color:#af7aed;">UGUI</a> to re-make <a style="color:#75b1ff;">Weapon & Bullets Infomation UI</a> in bottom-right corner.
> 4. Replace the <a style="color:lightgreen">Crosshair</a>'s image(Sprite type) with a <a style="color:lightgreen">Circle-Ranged</a> image as the aim point.

> 5. Update the <a style="color:#75b1ff;">health & Armor Bar UI</a> and the <a style="color:#75b1ff;">Weapon & Bullets Infomation UI</a>.
> 6. Program the logic of playing footsteps sounds.
> 7. Figure out how to change the footsteps sounds according to the different <a style="color:pink">Materials</a> of the plane.

------------

### 2022.09.15

> 1. Defines class & methods for storing weapons' parameters.
> 2. Re-do the style of aim point. 
> 3. Program the logic of the animation of aim point. (by the speed of movement) 

> 4. Set the <a style="color:#75b1ff;">Muzzle Flame</a> of the Weapon. 
> 5. Set the sputtering stuff and the shell holes. The sputtering things are in the <a style="color:pink">Materials</a> of the origin item.
> 6. Add the lighting system of the <a style="color:#75b1ff;">Muzzle Flame</a>.
> 7. Look for some audios of the <i style="color:white">Weapons_AK47</i> and finally got them.

------------

### 2022.09.16

> 1. Re-edit the audios which contains 'single shooting', 'Bolt', 'Magazine in&out', etc.
> 2. Add the weapon audio controller script to store the certain audio.
> 3. Promgram the logic of playing the shooting audio when it opens fire.
> 4. Animate the character's walking and running animation, but failed. It has to be done, but maybe next time.
> 5. Do made the simplfied animation of walking and running just including the upper body.
> 6. Promgram the logic of switching the animation between walking and running with its speed.
> 7. Match the frequency of animation and footstep audio.

> 8. Start <a style="color:#ffbe00;">Plan B</a> , replace <i style="color:#ffbe00;">Cowboy</i> with Mixamo Character & Animation.
> 9. ~~Spend a lot of time, wasting on the rig & animation & controller.~~

------------

### 2022.09.17

> 1. Still Waste time on Debugs and cannot make it right.

> 2. Finally back to <a style="color:#ffbe00;">Plan A</a> (<i style="color:#ffbe00;">Cowboy</i>).
> 3. Animate the Reload Animation. Too tough to work out.
> 4. Prepare to find a <a style="color:#ffbe00;">Plan C</a> . Cannot wasting time.

------------

### 2022.09.18

> 1. Get a brand new <a style="color:#ffbe00;">Plan C</a> . Just has two arms. I call it <i style="color:#ffbe00;">Arm Solider</i>.
> 2. Study how to use the materials and the scripts of the new plan.
> 3. Make it work in a little demo. 
> 4. Ready to work forward.

> 5. <a style="color:#ffbe00;">Plan C</a> settings needs to be merged with <a style="color:#ffbe00;">Plan A</a>. 
> 6. See the <a style="color:#ff6f42;" href="#todolist">TODO</a> List.
> 7. See the <a style="color:#b3ff00;" href="#buglist">BUG</a> List.

> 
> 8. <u>Daytime ends with working on Shell holes. </u>

------------

### 2022.09.19

> 1. Continue working on the Shell holes on <a href="#todolist" style="color:#ff6f42;">TODO</a> List.
> 2. Shell holes DONE!
> 3. Edit <i style="color:white">Weapons_DessertEagle</i> icon in Photoshop.
> 4. Sync Bullet UI Update when it fire and reload.
> 5. If there's no remainning bullet, the icon will turn red.

> 6. Program the logic of switching 2 guns.
> 7. Change the <a style="color:#75b1ff;">Weapon Cuts UI</a> when the guns switch. And the <a style="color:#75b1ff;">Bullets UI</a> changes at the same time.
> 8. When one weapon's bullet went out, the UIs turn red wheather it switches lately.
> 9. Fix <a style="color:#b3ff00;">BUGs</a> in Weapon Reloading.

------------

### 2022.09.20

> 1. Get pistol audios: Magazine-in, Magazine-out, Bolt.
> 2. Edit and program the logic of playing audio functions.
> 3. Match and sync the audio and the reload animations. (<i style="color:white">Weapons_DessertEagle</i> & <i style="color:white">Weapons_AK</i>) 

> 4. Sync the <a style="color:lightgreen">Crosshair</a> when the player's state changes. (Idle, Walking, Running, Jump)
> 5. Add Dry Fire audio when there's no bullet in the gun.
> 6. Sync the <a style="color:#75b1ff;">Tips UI</a> when there is no ammo or need reload.
> 7. Prepare the new map stuffs.

------------

### 2022.09.21

> 1. Make new map: <i style="color:orange">'MazeBamboo'</i>.
> 2. Design the game mode on this new map: <i style="color:orange">'MazeBamboo'</i>.

> 3. Fix current <a style="color:#b3ff00;">BUGs</a>. All clear.
> 4. Sync Crosshair changes when open fire.

------------

### 2022.09.22

> 1. Design <b style="color:orange">"<u>GBStrike Logo</u>"</b> in Photoshop.
> 2. Make fire and smoke Effect in Unity.

> 3. Program Gun's fire kick. Done!
> 4. Fix a little <a style="color:#b3ff00;">BUG</a> which bullets do not destory itself.

------------

### 2022.09.23

> 1. Design the forest scene and the foggy enviroment.
> 2. Set two cameras' position, angle, FOV and priority.
> 3. Program camera-switch when any button pressed. And the UI fade out.

> 4. Copy the old character models into the scene.
> 5. Add colliders for each part of the body which can be hit.
> 6. Test the <a style="color:#fb4949;">Blood Effect</a>. COOL!

------------

### 2022.09.24

> 1. Design Lobby UI.
> 2. Prepare button, background, border, fonts & etc. in Photoshop.
> 3. Make a Information Canvas. It can be used in any scene.
> 4. Program the logic to control the Information Canvas show or hide.
> 5. Add the interact sound.

> 6. Set the <a style="color:#fb4949;">Blood Effect</a> on Character Prefabs.
> 7. Program the logic to determine whether Character is hit. If hit, instantiate the <a style="color:#fb4949;">Blood Effect</a> at the position where got hit.
> 8. Design the damamge Algorithm.

#### Damage Algorithm with armor _temp
* a. Head damage x4 with armor x0.65 -- armor reduce = real damage x1
* b. Body damage x1 with armor x0.65 -- armor reduce = real damage x1
* c. Arm damage x0.65 with armor x0.7 -- armor reduce = real damage x0.65
* d. Leg damage x0.65 with armor x0.7 -- armor reduce = real damage x0.65
#### Weapon Damage
* AK47 -- damage = 35
* DessertEagle -- damage = 50

------------

### 2022.09.25

> 1. Re-do the Game Logo GBStrike AREA. Add a material mask, make it more textured.
> 2. Design Buttons Background images in Photoshop.
> 3. Adjust the camera angle, place a character into the scene with a cautious animation.
> 4. Program the logic which layer should be shown or fade out.

> 5. Program the logic of Damage System.
> 6. Fix a little <a style="color:#b3ff00;">BUG</a> that the damage would apply twice.
> 7. Re-Scale the blood effect size.
> 8. Add the Bot Information Canvas that can show the health, armor and last hit part.

------------

### 2022.09.26

> 1. Prepare some texture and logo in Photoshop. 
> 2. Add Canvas: <a style="color:white">"New Game"</a> UI. 
> 3. Adjust the UI interface, change the scale mode. Right now, it can fulfill the screen with height or width.

> 4. Learn A* algorithm which is the basic foundation of AI's pathfinding.
> 5. Make a demo. Click one place and the BOT will find the shortest path.
> 6. Place the character into the Map <i style="color:orange">'MazeBamboo'</i> and run. But unfortunately got a bad gaming experience. Need to be optimized.

------------

### 2022.09.27

> 1. Fouce on making the UI Canvas <a style="color:white">"New Game"</a>. And almost finished.
> 2. Design the UI Canvas <a style="color:white">"Create Room"</a>. Will begin next night.

> 3. Adjust the sensitivity of X-axis and Y-axis. Adjust the camera's shaking during walking and running. Gain better experience.
> 4. Apply A* Pathfinding into Map <i style="color:orange">'MazeBamboo'</i>. Add a plane as Ground, and set all the bamboos and fences as Obstacles.
> 5. Add the collider to all the bamboos, so they can be hit and leave bullet hole. Unfinished.

------------

### 2022.09.28

> 1. Finish adding the collider to all the bamboos. Totally 700+ bamboos.
> 2. Get a new BIG <a style="color:#b3ff00;">BUG</a>.

> 3. Set a series of points, and let BOT move alone the path points.
> 4. Program the logic BOT moves with animation.
> 5. Get a <a style="color:#b3ff00;">BUG</a>. The BOT sometimes turns around in circle.

------------

### 2022.09.29

> 1. Design the UI <a style="color:white">"Create Room"</a>. Prepare the background images.
> 2. Make the popup canvas.
> 3. Design another three maps that will come soon.

> 4. Fix a <a style="color:#b3ff00;">BUG</a> : The BOT sometimes turns around in circle.
> 5. Remove damage system after Bot died.

------------

### 2022.09.30

> 1. Add the missing buttons.
> 2. Edit the background pictures in Photoshop.
> 3. Finish the UI <a style="color:white">"Create New Room"</a>.
> 4. There are four maps in progress. 

> 5. Program the logic of the Lobby menu. Make it more reasonable.
> 6. Start making the UI of the Map <i style="color:orange">'MazeBamboo'</i>. Start with the TAB UI.

------------

### 2022.10.01

> 1. Design the UI in Photoshop.
> 2. Implemente the TAB UI and DONE!
> 3. Here is the Score Algorithm.
#### Score Algorithm
* Total Score = KILL x10 + ASSIST x5
#### KDA Algorithm
* KDA = ( KILL + ASSIST ) / DEATH

> 3. Add a HOST logo to mark the room host.
> 4. Add players' ping, the network delay.

------------

### 2022.10.02

> 1. Design the Host Controller Menu in Photoshop.
> 2. Make the Menu in Unity as the PS design.

> 3. Program the logic of buttons and the layers. Make a new button logic as my wish.
> 4. Debug some controlling details, like when the menu shows, player cannot move or shot. And the cursor shows during the menu controlling.

------------

### 2022.10.03

> 1. Add the mouse events like mouseenter, mouseleave and mouseclick.
> 2. When the SWAP MAP Button clicked, a system information appears. Should confirm to change map.

> 3. Finish the function to initalize the player and Bot. First of all, the player will be placed. Then, the player can add bots. 
> 4. The bot will automatically doing the map patrol following the certain points.

------------

### 2022.10.04

> 1. Add a id code in <a style="color:#75b1ff;">Tab UI</a>.
> 2. All characters will have their own id when it initialized.
> 3. All bots can be kicked at the same time.

> 4. Optimized the logic of the Bots' map patrol. Now they will randomly choose different point as the next target postion. And the pervious one will be move to the index 0 of the array.
> 5. Find two <a style="color:#b3ff00;" href="#buglist">BUGs</a>.

------------

### 2022.10.05

> 1. Continue working on the <a style="color:#75b1ff;">Tab UI</a>. The characters' infomation line will be added when initialized, and will be deleted when the character is kicked or exit.
> 2. And figure out how to update the data in lines.

> 3. Add the bots' footsteps so they can be heard in distance.
> 4. Work on the logic of detecting and finding enemies. Search some information online and study the method in some other games.

------------

### 2022.10.06

> 1. Try to figure a workable way to detete enemies. Use the sphere collider and the raycast.
> 2. If the enemy is found, the Bot will stop moving and will play shotting animation.
> 3. Fix the animation switching error.

> 4. Further the <a style="color:#ff6f42;" href="#todolist"> TODO List </a>.
> 5. Finish the Bot Found & Lose Enemy cycle. The bot will chase the target for a while and will move to the lastest position the enemy is found. Then continue map patrol.

------------

### 2022.10.07

> 1. The bot can be killed and will automatically reborn in random place.
> 2. The health and armor will be reset to full state when the bot is reborned.

> 3. Find <a style="color:#b3ff00;" href="#buglist">BUG</a>. After reborning, the bot will sometimes go through walls.
> 4. Add a fade-out effect, the body will dissolve and disappear in 5 seconds after death.

------------

### 2022.10.08

> 1. Remake and clean up the collider area of the map. Rescan the bot's pathfinding. Fix the BUG.
> 2. Program the code to get the damage origin. And the score can be calculated.
> 3. Store a list of bots' name. When the bot is set, it will automatically assigned a unique name.
> 4. Fix a <a style="color:#b3ff00;" href="#buglist">BUG</a> that the program will loop endlessly.

------------

### 2022.10.09

> 1. Improve the scene UI. 
> 2. The total score will shown on the TAB plane.
> 3. Add a score progress bar that grows with the score.

> 4. Add bots' shooting animation when enemy is detected and the muzzle flame effect of the gunshot.
> 5. Add the bullet fired by bots and it can hit the collider and make damage.
> 6. Add the blood effect.

------------

### 2022.10.10

> 1. Put the bot in map <i style="color:orange">'MazeBamboo'</i>. When enemy is found, the bot will open fire automatically.
> 2. Adjust the shooting parameters of the bot to make the shooting distribution more dispersed.
> 3. Re-format KDA calculation, and leave two decimal places.
> 4. Program the health UI and Armor UI.

> 5. Plan to program the bots attacking each other but failed.
> 6. Find a <a style="color:#b3ff00;" href="#buglist">BUG</a> that the bot keeps shooting after killing the enemy.

------------

### 2022.10.11

> 1. Start to make the initialization UI of the map <i style="color:orange">'MazeBamboo'</i>.

> 2. Program the code to initialize an avatar to replace the player after death, which makes it more reasonable.
> 3. And the main camera will switch to a bird's-eye view.

------------

### 2022.10.12

> 1. Continue to make the initialization UI of the map <i style="color:orange">'MazeBamboo'</i>.
> 2. Characters can be selected and when the cursor goes through the select arae, the character will play a ready animation.

> 3. Make the effect of player's getting hurt.
> 4. Program the logic to calculate the angle that the damage comes from and show the certain effect.

------------

### 2022.10.13

> 1. Make the effect of player's low health state in PS.
> 2. Program the logic to show the low health effect and the scene color will become black and white.
> 3. It will return to normal color after reborn.

> 4. Make a hit icon in PS.
> 5. Program the logic that the hit icon will shown in the middle when the bullets hit the enemy and make damage.

------------

### 2022.10.14 

> 1. Add a player state tips on the top-middle of the UI.
> 2. It will display the state of the current players' death, alive or no-player.

> 3. Fix a <a style="color:#b3ff00;" href="#buglist">BUG</a> that when the game exported, the materials will go wrong. The transparent background image will turn black.

------------

### 2022.10.15 

> 1. Add the killing Tips on the Top-Right corner of the UI. The information contains the origin of the kill,the weapon used, headshoot or not, and the dead player.
> 2. The current players state line will change in the same time.

> 3. Add another killing tips that can be seen by player self with a rising animation. 

------------

### 2022.10.16

> 1. Process the audios of player's death and get hit.
> 2. Add a chatbox into the UI.

> 3. Program the logic of the chatbox and it will chage the transparent value.

------------

### 2022.10.17

> 1. Add a ESC UI. If the button 'ESC' is down, the UI will slide in from the left.
> 2. Program the logic to show the background of the ESC UI.
> 3. Program the logic of the button to exit room and back to the lobby. 

------------

### 2022.10.18

> 1. 







## <a style="color:#ff6f42;" id="todolist">TODO List</a>

> * <a style="color:white">The characters should reborn in 5s after death.</a> 2022.10.06
> * <a style="color:white">The bot will shot bullets and make damage.</a> 2022.10.06
> * <a style="color:white">The bot's firing audio and flame.</a> 2022.10.06
> * <a style="color:white">The Tab ScoreBoard update data.</a> 2022.10.06
> * <a style="color:white">When the HOST Controller closed, the expended columns should be reset.</a> 2022.10.04
> * ~~Add Bot's animation during its move.~~ 2022.09.26 - <a style="color:#ff6f4270">2022.09.26</a>
> * ~~Bot with AI System can move from one place to another.~~ 2022.09.26 - <a style="color:#ff6f4270">2022.09.26</a>
> * ~~AI System that can find its own way.~~ 2022.09.26 - <a style="color:#ff6f4270">2022.09.26</a>
> * ~~Blood Effect System instantiate when got hit.~~ 2022.09.23 - <a style="color:#ff6f4270">2022.09.24</a>
> * <a style="color:white">Machineguns switch open fire mode. (Single / Auto) And its UI.</a> 2022.09.21
> * ~~Lobby UI: Information Pops.~~ 2022.09.23 - <a style="color:#ff6f4270">2022.09.24</a>
> * ~~Lobby UI: Starter Scene & Main Lobby.~~ 2022.09.22 - <a style="color:#ff6f4270">2022.09.25</a>
> * ~~Lobby UI: Select game mode. Create / Join the online hostrooms.~~ 2022.09.21 - <a style="color:#ff6f4270">2022.09.30</a>
> * ~~Map Bamboo: Add Bamboo Colliders ~~ 2022.09.21 - <a style="color:#ff6f4270">2022.09.29</a>
> * <a style="color:white">Map Bamboo: Special Object</a> 2022.09.21
> * ~~Map Bamboo: Tab UI~~ 2022.09.21 - <a style="color:#ff6f4270">2022.10.01</a>
> * <a style="color:white">Map Bamboo: Starter UI</a> 2022.09.21
> * <a style="color:white">Map Bamboo: Intialize Players Points</a> 2022.09.21
> * <a style="color:white">Add Crouch mode when 'CTRL' is button down.</a> 2022.09.20
> * ~~Sync Crosshair when got kicks.~~ 2022.09.20 - <a style="color:#ff6f4270">2022.09.21</a>
> * ~~Gun fire kick~~ ?? - <a style="color:#ff6f4270">2022.09.22</a>
> * ~~Show UI tips when no ammo or need reload~~ 2022.09.20 - <a style="color:#ff6f4270">2022.09.20</a>
> * ~~Dry Fire~~ ?? - <a style="color:#ff6f4270">2022.09.20</a>
> * ~~Sync Reload audio~~ ?? - <a style="color:#ff6f4270">2022.09.20</a>
> * ~~Sync UI Crosshair~~ ?? - <a style="color:#ff6f4270">2022.09.20</a>
> * ~~Switching Weapons and adjust UI~~ ?? - <a style="color:#ff6f4270">2022.09.19</a>
> * ~~Sync UI Bullets & Reload~~ ?? - <a style="color:#ff6f4270">2022.09.19</a>
> * ~~Shell holes~~ ?? - <a style="color:#ff6f4270">2022.09.19</a>
> * ~~Muzzle flame~~  ?? - <a style="color:#ff6f4270">2022.09.18</a>
> * ~~Shooting Audio~~  ?? - <a style="color:#ff6f4270">2022.09.18</a>
> * ~~Footsteps~~  ?? - <a style="color:#ff6f4270">2022.09.18</a>






## <a style="color:#b3ff00;" id="buglist">BUG List</a>

> * ~~when the game exported, the materials will go wrong. The transparent background image will turn black.~~ 2022.10.14 - <a style="color:#b3ff0070">2022.10.14</a>
> * ~~The bot keeps shooting after killing the enemy.~~ 2022.10.10 - <a style="color:#b3ff0070">2022.10.10</a>
> * ~~The program will loop endlessly.~~ 2022.10.08 - <a style="color:#b3ff0070">2022.10.08</a>
> * ~~After reborning, the bot will sometimes go through walls.~~ 2022.10.07 - <a style="color:#b3ff0070">2022.10.08</a>
> * <a style="color:white">Sometimes can shot during reload.</a> 2022.10.04
> * <a style="color:white">Sometimes cannot switch aim and idle during shotting.</a> 2022.10.04
> * ~~The BOT sometimes turns around in circle.~~  2022.09.28 - <a style="color:#b3ff0070">2022.09.29</a>
> * ~~In <i style="color:orange">'MazeBamboo'</i>, the bullets will be blocked by 'col_w'.~~ 2022.09.28 - <a style="color:#b3ff0070">2022.09.29</a>
> * ~~When the bullet hit the Bot, it will trigger twice or more.~~ 2022.09.26 - <a style="color:#b3ff0070">2022.09.26</a>
> * ~~After bullet shoot out and fly a distance, it didn't destory itself.~~ 2022.09.22 - <a style="color:#b3ff0070">2022.09.22</a>
> * ~~Animation Error when DE reloads.Error in 'PlayerSync' Script~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.19</a>
> * ~~Animation Error when AK47 keeps shooting.~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.21</a>
> * ~~Audio Error when AK47 keeps shooting. (bullets 20-30)~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.21</a>
> * ~~Once press R, but multiple reloads.~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.19</a>
> * <~~There's a bug in Reload. It should not fire-able during Reload. And Bullet UI should be updated after the Reload animation.~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.21</a>
> * ~~Bullet can fly through the collider. Return no hit.~~ 2022.09.18 - <a style="color:#b3ff0070">2022.09.19</a>
> * ~~DE Fire Error. Sometimes double click, or still in fire CD but play animations.~~ 2022.09.18 - <a style="color:#b3ff0070">2022.09.21</a>

