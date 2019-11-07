# game-off-nov-2019

Best Practices:

- class names should be UpperCamelCase
- variable names and function parameters should be lowerCamelCase
- Scripts, Sprites, Audio files, Animations, Scenes and all other Assets should be UpperCamelCase
- no unneccessary bloat in the Update() method! This method is called every frame and can kill performance
- use PlayerPrefs to store values between game sessions
- important settings for GitHub:
	- Edit->Project Settings->Editor->Version Control->Mode must be set to Visible Meta Files
	- Edit->Project Settings->Editor->Asset Serialization->Mode must be set to Force Text

editor recommendation: VS Code(loads faster than visual studio), with following extensions:
- C#
- C# FixFormat
- Debugger for Unity
- Unity Code Snippets Improved
- Unity Tools
- Visual Studio IntelliCode
- (Darcula Theme if you don´t want to kill your eyes)
