<div align="center">
<h1><kbd>🧩 UIStyle</kbd></h1>
An extension for MIT App Inventor 2.<br>
UiStyle is a component developed by th using Fast.<br>It provides a range of styling options for HVArrangements, including custom curved corner radius, inner curved corners, shadow effect with curved corners, and animated wave and layered wave effects. Additionally, it offers a gradient background feature with customizable colors, direction, angle, and opacity.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.uistyle<br>
💾 **Size:** 15.93 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-05-10 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small><br>
<br>

## Demo

![MIT-App](https://github.com/user-attachments/assets/2ef6b10c-1d3f-4d96-9a4d-ba141a7cc1c6)
![blocks](https://github.com/user-attachments/assets/10ecbd20-d1f5-47d9-8a59-7a1a6c2a2e88)


## Blocks

![StopWaveAnimation_Method](https://github.com/user-attachments/assets/ae532906-a9bd-443b-8ac2-b495fa2ea802)
![StartWaveAnimation_Method](https://github.com/user-attachments/assets/b8288b35-91b8-4064-b775-b2c96461351d)
![ShadowCorners_Method](https://github.com/user-attachments/assets/c42e5aac-8113-4429-876f-224400a266e9)
![LayeredWave_Method](https://github.com/user-attachments/assets/16627858-e72c-4ebf-80cb-2951daa6c956)
![InnerCornerRadius_Method](https://github.com/user-attachments/assets/0aabfd26-d2ed-4f01-8980-cb1e352f8b2d)
![GradientBackground_Method](https://github.com/user-attachments/assets/10a9bfbd-7a94-4e10-9862-11d9911ca401)
![CustomCornerRadius_Method](https://github.com/user-attachments/assets/5a9e7ced-e3bd-41a9-956a-097cd7d2c216)
![CurvedStyle_Method](https://github.com/user-attachments/assets/2ec89921-9586-42dd-a21e-0b4b4fa41ab7)
![WaveStyle_Method](https://github.com/user-attachments/assets/3364809b-c132-4bd6-892e-15e01a95ff05)


## <kbd>Methods:</kbd>
**UIStyle** has total 9 methods.

### CustomCornerRadius
Set a custom curved corner radius to an HVArrangement.

| Parameter | Type
| - | - |
| arrangement | component
| color | number
| topLeft | number
| topRight | number
| bottomRight | number
| bottomLeft | number

### InnerCornerRadius
Set inner curved corners to an HVArrangement.

| Parameter | Type
| - | - |
| arrangement | component
| backgroundColor | number
| borderColor | number
| radius | number

### CurvedStyle
Set curved style to an HVArrangement with border opacity and shadow.

| Parameter | Type
| - | - |
| arrangement | component
| backgroundColor | number
| borderColor | number
| topLeft | number
| topRight | number
| bottomRight | number
| bottomLeft | number
| borderOpacity | number
| shadowRadius | number

### ShadowCorners
Set shadow effect with curved corners.

| Parameter | Type
| - | - |
| arrangement | component
| backgroundColor | number
| radius | number
| shadowRadius | number

### WaveStyle
Creates an animated wave style effect. Example: WaveStyle(MyArrangement, 20, "horizontal", "#0000FF", "#FFFFFF", "#808080")

| Parameter | Type
| - | - |
| arrangement | component
| peakStep | number
| direction | text
| waveColor | number
| backgroundColor | number
| fillColor | number

### LayeredWave
Creates an animated layered wave effect on the specified HVArrangement. Example: LayeredWave(arrangement, 'horizontal', 0xFF0000, 0xFF000000, 3, 0.5)

| Parameter | Type
| - | - |
| arrangement | component
| direction | text
| waveColor | number
| backgroundColor | number
| waveCount | number
| overlap | number

### StartWaveAnimation
Start wave animation

### StopWaveAnimation
Stop wave animation

### GradientBackground
Create gradient background

| Parameter | Type
| - | - |
| arrangement | component
| startColor | number
| endColor | number
| direction | text
| angle | number
| opacity | number

## Thank
TechHamara
