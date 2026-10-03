# How to Publish with Godot   
   
I plan to create two applications:     
* **Code Lab TV** – A lightweight mini-game designed to run on Android TV and other low-powered devices, helping users learn programming concepts.   
* **Code Lab XR** – An interactive laboratory for learning IoT, programming, and QA testing.   

The goal of starting with **Code Lab TV** is to build a simple application that can run on as many platforms as possible. This will allow me to learn the complete publishing and deployment process across different platforms.     

The Android TV version is designed around a shared-screen experience. Players interact with the game through **UDP** or **WebSocket** connections from external devices, rather than using direct input on the TV application itself. This architecture also provides an opportunity for junior developers to build and experiment with the companion controller application.    

Both applications share the same vision: **learning by playing**. Instead of reading tutorials, users will develop programming skills by completing interactive game-based challenges that teach coding concepts in an engaging and practical way.    




# Challenge

<img width="731" height="523" alt="image" src="https://github.com/user-attachments/assets/a4fe204a-b4fd-41ce-b41b-bdf397230625" />  
<img width="743" height="421" alt="image" src="https://github.com/user-attachments/assets/2eb51f2a-e1a1-4aea-9318-0608903a9225" />  

Publishing a game also means finishing it and maintaining it.

When I arrived on Steam Frame, I realized that I needed two small apps to teach and have fun.

They can run on any platform using Godot:

* An SSD1306 screen, commonly used in IoT for debugging
* A simple ESP32-S3 camera view

Let's try to publish the SSD1306 screen on all platforms, and the ESP32-S3 camera on Android phones and Linux Flatpak at least.
