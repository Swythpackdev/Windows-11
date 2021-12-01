# Windows-11
Win11
Follow me Follow Twitter Join Build

"Buy Me A Coffee"

This open source project is made in the hope to replicate the Windows 11 desktop experience on web, using standard web technologies like React, CSS (SCSS), and JS.

Notice
This project is not in anyway affiliated with Microsoft and should not be confused with Microsoft’s Operating System or Products.
This is also not Windows 365 cloud PC.
THIS IS NOT THE APP STORE REPO

App Store

Live Experience🌈: win11.blueedge.me
home

Gallery
pic1

pic1

pic1

Why
WHY NOT? Why not just waste a week of your life creating a React project, just to cover up your insecurities of how incompetent you are. Just why not!

Features
 Start Menu, Search Menu and Widgets
 Desktop and Right Click action
 Side Navigation and Calendar View
 Snap windows in different layouts
 Browser, Store, Terminal, Calculator
 Notepad, Vscode, Whiteboard
 File Explorer + Setting
 Drag and Resize windows
 Startup and Lock screen
 Themes and Background
📑 suggest more

Stack
Framework - React (^17.0.2) + Redux
Component/UI Library - None!!
Styling Solution - SCSS and CSS Modules (tailwind).
Icons - fontawesome
FAQ
Is this the full operating system?

No, This is not a full operating system and It is also not affiliated by Microsoft in anyway.
How long it took?

Honestly It took 2-3 days collecting assets, 2-3 planning and about 6 days programming it.
Did you use any UI/Library?

No.
Can I contribute?

Yes, you can! Open an issue, create a pull request, head over to discussions or join the discord.
Where did you get the inspiration from, if you have?

I got the inspiration from this youtube video.
What is the answer of Life, the Universe, and Everything?

42

answer

Local Deployment
Docker
To use docker use the following command docker run -d --restart unless-stopped --name win11react -p 3000:3000 blueedge/win11react:latest

Homeassistant
Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.

Balena-Cloud
balena deploy button

Compiled
You can find a compiled .exe in the Releases section or via clicking HERE

WINGET - WINDOWS PACKAGE MANAGER

If you have one of the latest windows builds then you can enter the command below in CMD

winget install blueedge.win11react

APT/DEBIAN/UBUNTU

AMD64 ONLY

curl -s --compressed "https://projects.asylum-os.com/apt/KEY.gpg" | sudo apt-key add -

sudo curl -s --compressed -o /etc/apt/sources.list.d/asylum.list "https://projects.asylum-os.com/apt/apt.list"

sudo apt update

sudo apt install win11in-react

Online Deployment
Deploy

Deploy on Railway

Deploy to Netlify

Deploy with Vercel

Contributors

Known Issues
Blur not working in Firefox browser.
Solution:
Open about:config in your firefox browser.
Search for layout.css.backdrop-filter.enabled and set it to true.
License
⚖️ CC0-1.0 License
