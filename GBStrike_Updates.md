
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

> 6. 






## <a style="color:#ff6f42;" id="todolist">TODO List</a>
> * <a style="color:white">Gun fire kick</a>
> * <a style="color:white">Dry Fire and Reload audio</a>
> * <a style="color:white">Sync UI Crosshair</a>
> * <a style="color:white">Switching Weapons and adjust UI</a>
> * ~~Sync UI Bullets & Reload~~ ?? - <a style="color:#ff6f4270">2022.09.19</a>
> * ~~Shell holes~~ ?? - <a style="color:#ff6f4270">2022.09.19</a>
> * ~~Muzzle flame~~  ?? - <a style="color:#ff6f4270">2022.09.18</a>
> * ~~Shooting Audio~~  ?? - <a style="color:#ff6f4270">2022.09.18</a>
> * ~~Footsteps~~  ?? - <a style="color:#ff6f4270">2022.09.18</a>






## <a style="color:#b3ff00;" id="buglist">BUG List</a>
> * <a style="color:white">There's a bug in Reload. It should not fire-able during Reload. And Bullet UI should be updated after the Reload animation.</a> 2022.09.19
> * <a style="color:white">Bullet can fly through the collider. Return no hit.</a> 2022.09.18
> * <a style="color:white">Fire Rate Error. Sometimes double click, or still in fire CD but play animations.</a> 2022.09.18

