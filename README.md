![Static Badge](https://img.shields.io/badge/:badgeContent)


# Haxball Roles Script

A lightweight role management script for Haxball rooms. It allows
administrators to easily assign, manage, and visually identify player
roles through color-coded names and simple chat commands.

This script is designed for communities that want a clean and organized
way to distinguish between different types of players such as
administrators, VIP members, regular players, and spectators.

## Features

-   Color-coded roles for quick visual identification
-   Automatic role assignment when players join the room
-   Simple chat commands for role management
-   Clear distinction between Spectators, Players, VIPs, and
    Administrators
-   Minimal and easy-to-understand configuration

## Roles

The script includes four predefined roles:

-   Spectator -- Default role for players who are not currently playing
-   Player -- Standard role for active players
-   VIP -- Special role for trusted or notable members
-   Administrator -- Full permissions to manage roles

Each role is displayed with its own unique color in the room.

## Commands

Administrators can manage roles directly from the chat.

Give VIP role:

!vip `<player>`{=html}

Set a role manually:

!setrole `<player>`{=html} `<role>`{=html}

Example:

!setrole Mateo admin

## Usage

1.  Add the script to your Haxball room host.
2.  Start the room normally.
3.  Use the available chat commands to manage roles.

The script will automatically apply role colors when players join the
room.

## Goal

The main goal of this script is to provide a simple and efficient way to
organize player roles in Haxball communities without adding unnecessary
complexity.

## License

This project is free to use and modify for Haxball communities.


## Author

Script made by Mateo Collar.