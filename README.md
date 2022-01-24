# Mixel Block Proxy

## Features:
> [Commands](#Commands)

> [Tablist](#Tablist)

> [Listener](#Listener)

___




## Commands

- ### Tab
    - Usage: `/tablist` oder `/tab`
    - Permission: `proxy.command.tab`
    

- ### Maintenace
    - Usage: `/maintenance`, `/wartungen` oder `/lock`
    - Permission: `proxy.command.maintenance`


- ### Lobby
    - Usage: `/lobby` oder `/hub`
    - Permission: `proxy.command.lobby`
    <br>

- ### Citybuild
    - Usage: `/citybuild-1` oder `cb-1`
    - Permission: `proxy.command.lobby`

- ### Farmwelt
    - Usage: `/farmwelt-1`, `/farming-1` oder `/fw-1`
    - Permission: `proxy.command.lobby`

- ### Message
    - Usage: `/msg` oder `/whisper`
    - Permission: `proxy.command.msg`

- ### Reply
    - Usage: `/reply`oder `/r`
    - Permission: `proxy.command.reply`

- ### List
    - Usage: `/list`, `/online`, `/players` oder `/on`
    - Permission: `proxy.command.list`

- ### Teamchat
    - Usage: `/teamchat` oder `/tc` 
    - Permission: `proxy.command.teamchat`

<br>

## Tablist
- Prefix und Suffixes werden unterstüzt
- Map auf der gerade gespielt wird
- Ping des Spielers
- Anzahl der Online Spieler
- Ip des Servers
- Geld des Spielers

<br>

## Listener
1. PlayerConnect:
    - Ban Screen
    - Wartungsarbeiten Screen

2. ProxyPing:
    - Wartungsarbeiten Description
    - Sonst eine Wechselnde Description

3. TabList
    - Tablist wird initialisiert
    
<br>
