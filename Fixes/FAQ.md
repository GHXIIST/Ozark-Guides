# FAQ & Fixes


### When do I inject?
> RDR: At the __main menu__, not in SP, not in online. (**RDR only!**)

> GTA: Preferable in SP.
### How do I open Øzark?
> You open Øzark by pressing F4.
### How can I open Øzark using a controller?
> For Xbox press `RB` & `Right Dpad`, for PS4 press `R1` & `Right Dpad`.
### Does Øzark work on Windows 7?
> Yes it does.
### What does the `[SH]`/`[SC-H]` tag next to a player means?
> The `[SH]`/`[SC-H]` tag stands for "Script Host", the script host is the host of scripted events like free mode/free roam events.
### What's the Overseer?
> It's basically a (black-)list where you can save other players, who you want to keep tabs on/grief or make sure they aren't trying to join you again. If you've saved players, you can also join them, as an example.


## Common Problems and Solutions/Fixes:

### My game crashes or keeps crashing after enabling a certain option.
> Go into your Øzark folder and delete your `Config.ini` (Location: `Documents/Ozark/Red Dead Redemption 2`/`Documents/Ozark/Grand Theft Auto V`) or edit it and disable the certain option.
### Øzark wont launch/my game keeps crashing.
> If you have programs like "Process Hacker/Process Hacker 2" opended or trying to inject Øzark with Process Hacker, close them and try again/use Xenos for manual injection.
### When I run the launcher it says "why u heff vm mayne".
> Disable your VM and/or disable (hardware) virtualization.
### How to fix "Bad Image" error.
> Run Øzark using a VPN.
### `Auth | Please check your credentials` (1. or 2.)
> 1. Re-download the latest files from the website and use the manual files. Copy the ozark folder from the downloaded zip into your documents folder and enter your credentials in the `Ozark.auth` file. If you're manually injecting, you'll have to inject `bypass.dll` [RDR] or `client.dll` [GTA]. You'll find more info on how to manual inject [here](https://github.com/GHXIIST/Ozark-Guides/blob/master/General%20Guides/How%20to%20manual%20inject%20%C3%98zark.md).
> 2. Navigate to your Øzark folder (C:\Users\Documents\Ozark), find the file called `Ozark.auth` and open it with notepad. Make sure the details are up to date and/or if the file doesn't exist simply create a file called Ozark.auth, then inside the file enter your credentials.
>Replace *yourusername123* with your username and *yourpassword123* with your password:
```
{
    "username": "yourusername123",
    "password": "yourpassword123"
}
```