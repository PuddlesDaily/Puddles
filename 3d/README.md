# 3D

- **[puddles.blend](puddles.blend)**: Puddles in Blender, with textures packed in.
  The legs are split into rigid parts (thigh, shin, foot) hung off joint empties
  (`PD_Hip_L/R`, `PD_Knee_L/R`, `PD_Ankle_L/R`) under `PD_Rig`, which carries the
  body bob and side-to-side waddle. The walk is a one-second stride that loops.
- **[puddles.glb](puddles.glb)**: the same rigged model with the walk cycle, as glTF.
  This is the exact file that walks around the planet on
  [puddlesdaily.com](https://puddlesdaily.com) (three.js, `AnimationMixer`).

- **[puddles.usdz](puddles.usdz)**: Puddles as USDZ, with textures inside. Open it
  on an iPhone or iPad to drop him into the room in AR, or use it in Reality
  Composer and other USD tools.

Scale is 1 unit ≈ 10 cm, so he stands about 2.6 units tall. He faces -Y in Blender
(+Z in glTF).

The model started as an image-to-3D scan of the real Puddles and was cleaned up,
decimated to ~42k faces and rigged in Blender. It's a likeness for animation and
the website, not a build file for the robot. For the real body, see
[Pollen Robotics](https://www.pollen-robotics.com).
