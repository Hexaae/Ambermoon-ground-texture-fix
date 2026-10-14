# Ground texture fix for Ambermoon

Ground texture fix/replacement for the Ambermoon project (as well as the original game on the Amiga) by @Pyrdacor https://github.com/Pyrdacor/Ambermoon/ to finally correct the "green alien vomit" ;-) broken texture in the original game having (allegedly) swapped colors palette:

<img width="1807" height="1118" alt="ground_fixed_ezgif com-gif-maker" src="https://github.com/user-attachments/assets/6b37adf1-8ba4-4686-8338-9e0f8068c1c8" />
<br>
(green = original game, grey flagstone paving = mod-fix)

### ℹ️ Info
The "correction" is still a matter of debate amongst purists who think original was ok "grass" (?!), but there are some clear clues to suggest that amongst the many minor bugs in this incredible game, this  might have been simply a flagstone texture bugged with swapped colors... More details, if interested, in this discussion https://github.com/Pyrdacor/Ambermoon/issues/136#issuecomment-6151645749 <br>
- The texture itself has not been changed, keeping the original palette and _**just rearranging colors**_ for a surprisingly coherent result (hard for me to believe it can be just a coincidence by swapping a few colors):

<img width="64" height="64" alt="010_indexed - orig" src="https://github.com/user-attachments/assets/39e79c19-7b6e-46ed-9b9b-196474908833" /> ---> <img width="64" height="64" alt="010_indexed" src="https://github.com/user-attachments/assets/d044266b-3667-42bb-b17b-c78323f247fa" />

... which now "suspicioulsy" perfectly matches the original art-direction of the rest of the graphics in this masterpiece. Look here for example at the ground, when in combat-mode, still in Spannenberg (as in the 1st pic) which confirms my assumption:

<img width="1807" height="1118" alt="ground_fix_03_combat_mode" src="https://github.com/user-attachments/assets/8aea2d9e-ce42-42bf-9c9e-8aa37fb3b851" />


### 🔨 Installation
Just overwrite "Ambermoon/Amberfiles/Floors.amb" with the file "Floors.amb" in this repository, and re-launch the game.<br>
Simple as that.
