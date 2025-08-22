# Install Guide

Prerequisites:
- SteamCMD
- Preferrably a VPS

If you haven't already, please [install SteamCMD](https://developer.valvesoftware.com/wiki/SteamCMD#Downloading_SteamCMD) This guide will show you how to fully reinstall Counter-Strike 2 from scratch (although if you have it installed already you should be able to use your existing install as a dedicated server.), install CSS and MetaMod: Source and everything inbetween.

# Linux Guide
Note: Most of the Linux guide can be reused on Windows, just swapping out the paths and opening SteamCMD differently.

1. SteamCMD
- Open SteamCMD

If you installed SteamCMD through your package manager it should be as simple as running "steamcmd" in the terminal. Otherwise refer to the Valve Developer Wiki.
- Set an install directory

SteamCMD by default installs games to god knows where so we'll want an install directory. Before launching SteamCMD make a directory. For this guide I'll use /home/steam/cs2. Before signing into Steam run "force_install_dir /home/steam/cs2". This will install the game to "/home/steam/cs2" later.
- Sign in

Usually you can sign in with the anonymous account but for your server to be public and accessible outside of LAN you will need to sign in with your main Steam account (or a burner one) and use a Steam GSLT. To sign in run "login <Steam account name> <password>". Verify the login on your phone and you're in.
- Install CS2

This is probably the longest part if you know what you're doing, and mostly depends on the speed of either you're VPS' down speeds or your internet's down speeds. To download the game we'll run "app_update 730 validate". Once this has started move on with your day for an hour or so.
