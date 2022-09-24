
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
> 8. Design the damamge calculation.

#### Damage Calculation with armor _temp
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

> 5. 



## <a style="color:#ff6f42;" id="todolist">TODO List</a>

> * ~~Blood Effect System instantiate when got hit.~~ 2022.09.23 - <a style="color:#ff6f4270">2022.09.24</a>
> * <a style="color:white">Machineguns switch open fire mode. (Single / Auto) And its UI.</a> 2022.09.21
> * ~~Lobby UI: Information Pops.~~ 2022.09.23 - <a style="color:#ff6f4270">2022.09.24</a>
> * ~~Lobby UI: Starter Scene & Main Lobby.~~ 2022.09.22 - <a style="color:#ff6f4270">2022.09.25</a>
> * <a style="color:white">Lobby UI: Select game mode. Create / Join the online hostrooms.</a> 2022.09.21
> * <a style="color:white">Map Bamboo: Add Bamboo Colliders </a> 2022.09.21
> * <a style="color:white">Map Bamboo: Special Object</a> 2022.09.21
> * <a style="color:white">Map Bamboo: Tab UI</a> 2022.09.21
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

> * ~~After bullet shoot out and fly a distance, it didn't destory itself.~~ 2022.09.22 - <a style="color:#b3ff0070">2022.09.22</a>
> * ~~Animation Error when DE reloads.Error in 'PlayerSync' Script~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.19</a>
> * ~~Animation Error when AK47 keeps shooting.~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.21</a>
> * ~~Audio Error when AK47 keeps shooting. (bullets 20-30)~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.21</a>
> * ~~Once press R, but multiple reloads.~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.19</a>
> * <~~There's a bug in Reload. It should not fire-able during Reload. And Bullet UI should be updated after the Reload animation.~~ 2022.09.19 - <a style="color:#b3ff0070">2022.09.21</a>
> * ~~Bullet can fly through the collider. Return no hit.~~ 2022.09.18 - <a style="color:#b3ff0070">2022.09.19</a>
> * ~~DE Fire Error. Sometimes double click, or still in fire CD but play animations.~~ 2022.09.18 - <a style="color:#b3ff0070">2022.09.21</a>

