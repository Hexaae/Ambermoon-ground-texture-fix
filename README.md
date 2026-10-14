# Ground texture fix for Ambermoon

Ground texture replacement for the Ambermoon project (as well as the original game on the Amiga) by @Pyrdacor https://github.com/Pyrdacor/Ambermoon/ to finally fix the "green alien vomit" ;-) broken texture in the original game having (allegedly) swapped colors palette:

<img width="1807" height="1118" alt="ground_fixed_ezgif com-gif-maker" src="https://github.com/user-attachments/assets/6b37adf1-8ba4-4686-8338-9e0f8068c1c8" />
<br>
(green = original game, grey flagstone paving = mod-fix)

### ℹ️ Info
The "correction" is still a matter of debate amongst purists, but there are some clear clues to suggest that, amongst the many minor bugs in this incredible game, this ground texture might also have been bugged with swapped colors... More details, if interested, in this discussion https://github.com/Pyrdacor/Ambermoon/issues/136#issuecomment-6151645749 <br>
- The texture itself has not been changed, keeping the original palette and _**just rearranging colors**_ for a more logical result:

<img width="64" height="64" alt="010_indexed - orig" src="https://github.com/user-attachments/assets/39e79c19-7b6e-46ed-9b9b-196474908833" /> ---> <img width="64" height="64" alt="010_indexed" src="https://github.com/user-attachments/assets/d044266b-3667-42bb-b17b-c78323f247fa" />

... which now "suspicioulsy" perfectly matches the rest of the graphics in the game and the original art-direction. Look at the ground gfx for example, still in Spannenberg (same as pic above), when in combat-mode:

<img width="1807" height="1118" alt="ground_fix_03_combat_mode" src="https://github.com/user-attachments/assets/8aea2d9e-ce42-42bf-9c9e-8aa37fb3b851" />


### 🔨 Installation
Just overwrite "Ambermoon/Amberfiles/Floors.amb" with the file "Floors.amb" in this repository, and re-launch the game.<br>
Simple as that.
