# game-off-nov-2019

Unity best practices:

- class names should be UpperCamelCase
- variable names and function parameters should be lowerCamelCase
- Scripts, Sprites, Audio files, Animations, Scenes, Object Tags and all other Assets should be UpperCamelCase
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
- choose vs code as default editor in unity (edit->preferences->external tools->external script editor->browse to
  AppData\Local\Programs\Microsoft VS Code\Code.exe
- (Darcula Theme if you don´t want to kill your eyes)
