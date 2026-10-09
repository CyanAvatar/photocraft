# Free Transform layer-order reproduction

Original synthetic artwork by CyanAvatar, licensed MIT OR Apache-2.0; adjacent license files apply to this fixture and its canvas captures.

Open `transform-layer-order.pcraft`, select the lower red rectangle, and press Ctrl+T. The opaque blue and translucent green rectangles should stay above it during the transform. Move, scale, or rotate the red rectangle; commit and cancel should preserve the same composition rules.

`before.png` and `after.png` are cropped canvas captures from PhotoCraft's offscreen GPU snapshot harness, using baseline `3e8d548` and the locally tested fix `45bf6d8`, respectively. The source patch was subsequently adapted to upstream `82148e7` for the pull request. These captures contain only synthetic rectangles; no personal artwork is included.
