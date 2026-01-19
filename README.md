# Slime-Survivor

# Slime Survivor 🟢

Slime Survivor is a fast-paced 2D survival game built for the Hack Club Milky Way program. Take control of a brave slime and defend your forest home against incoming threats using an automated defense system.

🚀 How to Play
- Survive: Dodge enemies to keep your health from hitting zero.
- Auto-Aim: The turret system automatically targets the nearest enemy in range.
- Victory: Survive as long as you can while your score increases!

🛠️ Technical Features
- Smart Targeting: Built an `Area2D` system that detects overlapping bodies and uses `look_at()` to track enemies in real-time.
- Projectile Physics: Custom bullet script using `Vector2` math to handle independent travel and range limits.
- Enemy AI: Enemies use `global_position.direction_to()` to intelligently hunt the player down.
- Animation System: Integrated a state-based animation system for walking and taking damage (`%Slime.play_hurt()`).
- Object Pooling: Efficiently handles object cleanup using `queue_free()` and spawns dynamic smoke particle effects upon enemy defeat.

📦 Built With
- Engine: Godot Engine (v4.x)
  Language: GDScript
- Program: Hack Club - Milky Way

📂 Installation / Development
If you want to run this project locally in Godot:
1. Clone this repository.
2. Open Godot Engine and click Import.
3. Select the `project.godot` file in this folder.
4. Press F5 to play!

---
Created with ❤️ for the Hack Club community.
