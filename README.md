# Lumina Trace

<p align="center">
  <img src=".github/images/lumina-trace.gif" width="800">
</p>

`Lumina Trace` is a visual interaction project where you control a comet-like luminous core floating in a 3D space, enjoying light trails created by a Trail Renderer and afterglow effects powered by a Particle System.

## Play Now

👉 [https://ganesha-shiisa.github.io/lumina-trace/](https://ganesha-shiisa.github.io/lumina-trace/)

## Features

- **Comet-Style Trail Effects**:
  - Implements glowing trail effects using the Unity Particle System.
  - Continuously emits particles behind the object to create a comet- or meteor-like afterglow.
  - Dynamically adjusts tail behavior based on speed for an immersive flight feel.

- **Ribbon-Like Trail Renderer**:
  - Draws the movement history of the luminous core using a Trail Renderer, leaving a beautiful trace in space.

- **Luminous Core Movement Control**:
  - Delivers smooth and weighty curved trajectories powered by a Rigidbody-based movement system.

- **Camera Tracking and Dynamics**:
  - Features a dynamic tracking camera that reacts to movement speed.
  - Achieves natural, drone-like tracking with smooth, inertia-based position interpolation.
  - Employs smooth gaze interpolation for immersive camera work that locks onto the subject.

## Controls

| Action                            | Assignment             | Description                                                                             |
| --------------------------------- | ---------------------- | --------------------------------------------------------------------------------------- |
| **Change Direction / Accelerate** | Left Mouse Click / Tap | Applies a new impulse to the luminous core, creating dynamic changes in its trajectory. |

## Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ganesha-shiisa/lumina-trace.git
   ```

2. **Open in Unity Hub**:
   - Launch Unity Hub, add the project, and open it with `Unity 6` (or the target version).

3. **Open the Main Scene**:
   - Open the main scene under `Assets/Scenes/` (e.g., `SampleScene`) and hit Play.

## License

[MIT License](LICENSE)

## Author

- **GaneshaShiisa** [GitHub Profile](https://github.com/ganesha-shiisa)
