# ASL-Gestures-Simplified
Basically plug and play

Huge Thanks to all my friends for the inspiration and to all the people who use this in game ^~^

Highly recommend using [@benaclejames](https://github.com/benaclejames/OVRThumbParams) to automatically run with SteamVR.

Alternative method using [@I5UCC](https://github.com/I5UCC/VRCThumbParamsOSC) OSC program.

## To add to Avatar
1. Import Package
2. Choose and place "ASL Simplified Index" or "ASL Simplified Oculus" 
into the "Gesture" playable layer

![image_2022-06-02_194028904](https://user-images.githubusercontent.com/68105767/171770429-b13b7044-ace3-484c-8ed3-b587b391e65d.png)

3. If you don't have a menu for avatar place "Blank menu" and "ASL Params" into the Expressions dropdown, otherwise add Parameters to existing controller

![image_2022-06-02_194139998](https://user-images.githubusercontent.com/68105767/171770529-9119e63e-841d-49bf-9fcd-df6ce088a94c.png)

4. UPLOAD!

## To add to Existing Avatar
1. Import Package
2. Merge "ASL Simplified (XX)" to existing Gesture Layer Controller using [AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager)

![image_2022-06-02_200001671](https://user-images.githubusercontent.com/68105767/171772168-41f523b3-3b7a-494d-98b2-e7b66a9f8377.png)

3. Add these Integers to existing Parameters list (CASE SENSITIVE!)
  - LeftThumb
  - RightThumb

![image_2022-06-02_200253106](https://user-images.githubusercontent.com/68105767/171772425-4ad9fdef-b7a6-4363-88c0-0bcbf65ec998.png)

4. UPLOAD!

## To change bindings or add animations
1. Make custom hand animation
2. Open "ASL Simplified (XX)" controller in the Animator tab for either Left or Right hand

![image_2022-06-02_194423284](https://user-images.githubusercontent.com/68105767/171770771-531a100e-f4da-4848-8b6b-9f867595acc6.png)

3. Find which binding you want to add your new animation to
  - Notation of bindings:
    - G#= hand gesture value
    - T#= thumb param value
    - GW#= trigger pull value

![image_2022-06-02_194826054](https://user-images.githubusercontent.com/68105767/171771148-46048212-70ae-4245-bc26-4d3b2f274eda.png)

4. Select binding and place new animation in Inspector

![image_2022-06-02_195125455](https://user-images.githubusercontent.com/68105767/171771392-233d4856-3ff8-4183-be2c-848d49573a4b.png)

![image_2022-06-02_195043282](https://user-images.githubusercontent.com/68105767/171771344-e1b6fb30-09a6-4240-84b9-0352977f8f07.png)

5. Finally enable the transition to your animation by unmuting it

![image_2022-06-02_195239092](https://user-images.githubusercontent.com/68105767/171771497-2782073d-e540-4744-839c-2beb796a1f52.png)

![image_2022-06-02_195356158](https://user-images.githubusercontent.com/68105767/171771603-1980dfca-ae39-41f0-9826-7a7d93ba3212.png)

6. Repeat steps 3-5 for opposite hand
7. UPLOAD!
