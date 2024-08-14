<!--------------------------------------------------------------------------------------------------------------------->
<p align="center">
  <img alt="OpenDevin Logo" src="https://github.com/unknown144p/fiveam/assets/93508554/0c60b3e4-58ec-412a-9520-fa9e12f4a28d" width="256" />
</p>


# FiveM External
<div align="center">
   
  ![License](https://img.shields.io/badge/license-MIT-orange) [![Build status](https://ci.appveyor.com/api/projects/status/d2jnxclg20vd0o50?svg=true&branch=v1.x)](https://ci.appveyor.com/project/gabime/spdlog) [![Windows](https://github.com/SuperTux/supertux/actions/workflows/windows.yml/badge.svg?branch=master)](https://github.com/SuperTux/supertux/actions/workflows/windows.yml?branch=master) [![Chat on Discord](https://img.shields.io/badge/Discord-5865f2?logo=discord&logoColor=green)](https://discordapp.com/invite/ZdqEheK)
  
</div>


ActiveBypass is a cheat tool designed for the game FiveM. It offers various features such as aimbot, triggerbot, exploits, and settings customization.

- **Cheating is Completely Undetectable. Unless Admins Ban**
## KeyAuth System 

KeyAuth System is available. You can optionally develop the project.
KeyAuth is prepared in a simple way.[Click for Details](#KeyAuth)

<!--------------------------------------------------------------------------------------------------------------------->


## Usage

- Open FiveM (Mandatory).

- Open the cheat you have compiled.

- **Ready to Use. Have Fun!**

**Note:** Make sure you have all the necessary drivers installed on your computer, otherwise the tool may give some errors.

**Note:** If you can't press anything in the menu, press the `F4` key 2 times, it will help to fix the menu.

**Note:** The key to open and close the menu is `F4`.

<!--------------------------------------------------------------------------------------------------------------------->

## Features

- **Aimbot**
   - Aimbot (Adjustable)
   - Show FOV (Adjustable)
   - Target NPCs
- Visuals
   - Box
   - Box Corner
   - Skeleton
   - Distance
   - Health Text
   - Lines
   - Draw NPCS
   - Filled Box
   - HP Bar
   - Head
   - Show ID
- TriggerBot
   - TriggerBot
   - TriggerBot FOV (Adjustable)
- Exploits
   - God Mode
   - Semi God Mode
   - Run Speed (Adjustable)
   - Vehicle Acceleration (Adjustable)
   - Vehicle GodMode
   - No Recoil
   - No Reload
   - No Spread
- Firend List
   - You can add your friends to the Safe Area.
- Settings
   - Here you can edit the menu's On/Off and Ambot, TriggerBot key assignment.

<!--------------------------------------------------------------------------------------------------------------------->

## Photo

![photo1](https://github.com/unknown144p/fiveam/assets/93508554/16ef2363-3a0e-46f7-bf60-585cd2e31768)
![photo2](https://github.com/unknown144p/fiveam/assets/93508554/80bb2603-53b8-4f17-bfa9-86065bc07cdb)
![photo3](https://github.com/unknown144p/fiveam/assets/93508554/576e0ebf-c60b-4c7a-90a8-3202605e22dd)
![photo4](https://github.com/unknown144p/fiveam/assets/93508554/2ce58e39-45f1-4f68-85da-92c64c89d1f6)
![photo8](https://github.com/unknown144p/fiveam/assets/93508554/ffbe19df-6edc-48a7-bb60-2ac9f632a068)
![photo5](https://github.com/unknown144p/fiveam/assets/93508554/f26d655f-58d5-4233-a8ac-f06a269feae1)
![photo6](https://github.com/unknown144p/fiveam/assets/93508554/756cca63-efee-42f8-b247-73ad2498e5c1)
![photo7](https://github.com/unknown144p/fiveam/assets/93508554/a9f1483f-dd8f-4587-975a-d6f100917a27)

<!--------------------------------------------------------------------------------------------------------------------->

# KeyAuth

This KeyAuth Interface is Prepared for FiveM. However, you can use it in different applications by changing the interface.

If you are going to try it as standard
- Username: `fivem`
- Password: You can find out by pressing `Forgot Password`

Create a New KeyAuth Account for Yourself.

On `line 17` of `Login.cs` and `Main.cs`

```c++
public static api KeyAuthApp = new api(
    name: "FiveM",
    ownerid: "Example",
    secret: "SecretExample",
    version: "1.0"
);
```

Replace this code with the values of your own code.

Create a New User with KeyAuth. Check out [KeyAuth's](https://www.youtube.com/@KeyAuth/videos) Personal Channel for more details.


Upload the file you have compiled somewhere (Discord for example).

Inside the `Main.cs` File, paste the link in the `url` section at `line 87`. and your code is ready to run.

**Note:** It adds user information to Regedit so you don't have to use username and password every time. | Regedit Path: `.\HKEY_CURRENT_USER\SOFTWARE\FiveMExternal`

**Note:** The code is open source so you can develop it the way you want.

<!--------------------------------------------------------------------------------------------------------------------->

## KeyAuth GUI Photo

![keyauthgui1](https://github.com/unknown144p/fiveam/assets/93508554/7050bf8b-c341-423a-b8bc-2059a46115cd)

![keyauthgui2](https://github.com/unknown144p/fiveam/assets/93508554/1eefb308-9566-4072-afb3-f3a46e251b99)

<!--------------------------------------------------------------------------------------------------------------------->

## Requirements

- [Visual Studio](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&passive=false&cid=2030)
- [DirectX SDK June2010](https://www.microsoft.com/en-us/download/details.aspx?id=6812)

<!--------------------------------------------------------------------------------------------------------------------->

## Possible Mistakes

One of the Common Errors Users Often Encounter is d3dx9.h error.
The solution to this error is quite simple.

Download [DirectX SDK June 2010](https://www.microsoft.com/en-us/download/details.aspx?id=6812) to your computer. Add Include and Libs to VC++. If you don't know how to do this. [Tutorial](https://www.youtube.com/watch?v=HbMt-hJuVts) You Can Watch This Video.

Watch this video [Fix](https://youtube.com/watch?v=Q6lsdOyWNQE) if you are getting this error `S1023` during DirectX SDK June 2010 Installation.

- You can investigate and solve other errors that may occur.

<!--------------------------------------------------------------------------------------------------------------------->


## TODO

I'll Add Some New Features. And Optimization Settings.

## Contributions

We look forward to your contributions! Share the Project and Star this Repo to Contribute

## Disclaimer

This Project is purely for learning and educational purposes. I accept no responsibility for any misuse of this software.

## License

This project is licensed under the [MIT License](LICENSE).

<!--------------------------------------------------------------------------------------------------------------------->
