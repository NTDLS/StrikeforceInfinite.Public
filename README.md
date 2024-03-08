# Strikeforce Infinite
![image](https://github.com/NTDLS/StrikeforceInfinite/assets/11428567/b446acfb-3333-4b79-9ccc-ce4a60621848)

Strikeforce Infinite is a 2D space fighter game written in C# (currently .net8) and rendered with DirectX.
The game features infinite space, neural network AI, multiple scenarios, single-player, multi-player, locking/seeking weapons, a "speed-scaled" environment, dozens of weapons and massive fiery explosions...

Check out the alpha build 13 gameplay on YouTube: [https://www.youtube.com/watch?v=Kd-aEshWiNg](https://youtu.be/uxRjQ9BHlek)

**Ship Class Selection**

![image](https://github.com/NTDLS/StrikeforceInfinite/assets/11428567/de754036-2e2a-48ff-9ef9-a4f8e7364d98)

**Early Gameplay**

![image](https://github.com/NTDLS/StrikeforceInfinite/assets/11428567/89468ceb-6645-41fb-856d-ad6b732b11bc)

**GDI Notes**
The rendering engine was originally written to use GDI+. Before moving to DirectX, the framerate was still 80+FPS, but the resource contention required for measuring strings was causing all kinds of odd race conditions. That said, the GDI+ code contains a lot of "lessons" learned" code so we are providing it here for educational purposes. The last DGI+ (no-DirectX) commit was https://github.com/NTDLS/HellsGenesis/tree/6f593ea1daf21054382b54e98f9d41ab3303ba8a.


