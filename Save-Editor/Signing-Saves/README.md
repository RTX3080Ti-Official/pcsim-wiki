---
layout: default
title: Signing Saves
---

# Signing Saves

## What is signing?
Signing is ensensially adding your signature to the save (in this case a text which should be your username), when signing your save, you cannot save it anymore, in the pause menu, there's only "Exit without Save" and "Cancel", it's obviously missing "Save and Exit".\
Fun fact: The game still tells you a warning that the save won't be saved when clicking on "Exit without Save" even tho you can't save.

## How to add one?

Well there's two methods, either use the official method, you need to be an *Awesome* in the official PC Simulator Discord server, beacause this will unlock a channel called "#awesome-chat" from what I've seen and I remember, in the *pinned messages*, there's a software (Windows only) to sign your save, but be honest, no one except stupid people have the *Awesome* rank.

And now, for the unofficial method, open [a save editor](../Save-Editors) and open your save file, the first line should look something like this:
```json
{"version":"1.8.0","roomName":"best pc ever","coin":1115385,"room":2,"gravity":true,"hardcore":false,"playtime":1521.516845703125,"temperature":20.0,"ac":false,"light":true,"sign":""}
```

What is gonna interest us here is this part:
```json
"sign":""
```
If the value is empty, then your save isn't signed, you can make this value say anything! From your username to aome stupid shi
