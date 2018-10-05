# MeshRotator
Super simple mesh rotation controller

## How does it work

Simply call `possess` on a given mesh(s), and MeshRotator will automatically rotate your possessed meshes using your user's mouse motion.

## Why is this useful?

Rotation controls are essential for 3d viewing applications. With this library, you can painlessly enable user rotation on a given mesh with a simple `possess` call. No other configuration is required.

## Configuration

Settings are exposed for rotation speed and pivot point. Hooks for converting client mouse motion into rotation deltas are also provided.
