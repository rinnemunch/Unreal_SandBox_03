# 💀 Project 1 – Triggered Jump Scare System

This project demonstrates how to build a **cinematic triggered jump scare** in **Unreal Engine 5.5.4** using Blueprints only.
It combines sound, animation, and visibility logic into one clean event that activates the moment a player enters a trigger zone — delivering a sharp, timed horror effect without any C++.

---

## 🖼️ Preview

![Jump Scare Preview](Media/JumpScare.gif)

---

## 🧱 Features

- **Hidden Skeletal Mesh (JumpScare)** attached to the player camera
- **Trigger Box** activates event on player overlap
- **Cast To BP_ThirdPersonCharacter** ensures player-only trigger
- **Do Once** node prevents reactivation
- **Play Sound 2D** for synchronized scream or impact sound
- **Set Visibility + Play Animation** combo for visual scare moment
- **Delay node** hides the mesh again for reset
- Entire system built with clean, minimal Blueprint logic — zero scripting required

---

## 🚀 Result

As soon as the player enters the trigger zone, the **jump scare mesh appears**, **animation plays**, and **sound hits** — all in sync.
After a short delay, the mesh vanishes, leaving behind a perfectly timed, cinematic horror moment.

---
