# Welcome to the Minecraft Bedrock Editor! 

<img width="750" alt="Stylized image of the Minecraft Bedrock Editor" src="https://user-images.githubusercontent.com/56832421/218781941-acb626bd-b9a3-4893-a1b0-d6a33b2f3d78.png">

Minecraft Editor is a natively built, multiblock editing experience focused on making it possible for creators of all skillsets to easily craft high-quality experiences in Bedrock. 

---

## Housekeeping
- Editor will be exclusively available in Bedrock Preview on Windows until the feature set and quality meets our standards to be made visible in Retail and the Launcher.
- Editor is not a new gamemode, and actively being made to be intentionally distinct from Creative, Survival, and Adventure. 

---

## Development
We are in early development and there is still a lot of work our team has ahead of us. In line with our principles, we want to share early and often with you, and develop alongside our creator community! We are eager for your feedback and want to work with you to iterate.

---

## Extensibility
We are building an Editor API. While we have iterations to the core Editor experience we want to make, we are also focused on unlocking functionality via the API for you to build your own editing tools -- which we are calling "extensions." 

In releases to come, we will make our initial iteration of the Editor API visible. However, for now we invite you to acquaint yourself with the existing [scripting](https://docs.microsoft.com/en-us/minecraft/creator/scriptapi/) efforts. 

_Note:_ If you are exploring scripting outside of the Editor, make sure to enable the "Beta APIs" toggle in Experiments when creating a new world. We also encourage you to proactively brush up on Javascript and Typescript, as that will be the language used for Editor extensions.

---

## Accessing the Editor
Bedrock Editor is for Windows PC, keyboard + mouse only. View the [documentation](https://aka.ms/LearnEditor) to learn more about the Editor. 

Three-step quick start for getting the Editor: 

1. Install Bedrock Preview via the [Launcher](https://help.minecraft.net/hc/en-us/articles/4412261881229-Minecraft-Launcher-for-Windows-).

| Install the Launcher | Install Bedrock Preview |
|--|--|
| <img width="761" alt="Image of installing the Launcher from the Microsoft Store" src="https://user-images.githubusercontent.com/56832421/218183602-be85617f-b05c-46ea-b682-0280c61392c2.png"> | <img width="753" alt="Image of installing Minecraft Bedrock Preview from the Minecraft Launcher" src="https://user-images.githubusercontent.com/56832421/218184144-8850d7bb-7493-4233-a3e0-c9b2f418f673.png"> |

2. Create a desktop shortcut. When prompted for the filename, copy/paste the following into the textfield: `minecraft:?Editor=true`

| Create a new shortcut | Specify the destination |
|--|--|
| <img width="416" alt="Image of right clicking on Windows desktop to create a new shortcut" src="https://user-images.githubusercontent.com/56832421/218183560-2d9de360-65f0-4c93-afcf-150ff2958e6a.png"> | <img width="443" alt="Image of pasting the shortcut minecraft:?Editor=true as the destination for the shortcut" src="https://user-images.githubusercontent.com/56832421/218183578-355804d4-76e9-48c5-b76c-9748700208d3.png"> |


3. Open the Editor via the desktop shortcut you created.

<img width="416" alt="Animation of opening the Editor via the desktop shortcut you created" img src="https://user-images.githubusercontent.com/56832421/218185006-65dac070-7283-42b3-8091-ba9240cb7df3.gif" width="250" />

---

## Resources 

| **Resource** | **Description** |
|--|--|
| [Documentation](https://aka.ms/LearnEditor) | Learn how to use the Editor | 
| [Minecraft: Bedrock Edition Preview Changelogs](https://feedback.minecraft.net/hc/en-us/sections/360001185332-Beta-and-Preview-Information-and-Changelogs) | View the Preview changelogs |
| [/mojang/minecraft-editor](https://github.com/Mojang/minecraft-editor) | Participate in [discussions and provide feedback to our team](https://github.com/Mojang/minecraft-editor/discussions) | 
| Coming soon! | Editor API documentation, extension samples, starter kit, and where to create and share Editor API feedback |

---

## Troubleshooting

If your desktop shortcut doesn't appear to be launching the Editor, you may need to change the default app from `Minecraft` to `Minecraft Preview`. Follow the directions below: 
1. Press `Windows + I` to open the Settings app
2. Select `Apps` and click `Default apps`
3. Search for `Minecraft` and select it
4. Scroll down and find the `MINECRAFT` entry (it should also say `Minecraft | URL:minecraft`) and click it
5. In the pop-up, select `Minecraft Preview` and click ok

| Change default app | What you should see when the Editor launches | 
|--|--|
| <img width="564" alt="image (47)" src="https://user-images.githubusercontent.com/56832421/218187943-634d143a-9775-44ae-9027-0bb5e2acc68f.png"> | <img width="1200" alt="image (48)" src="https://user-images.githubusercontent.com/56832421/218188757-8517ebe3-214a-4923-81ef-84b651b28551.png"> |
