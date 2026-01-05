# 3D Solar System in THREE.js

An interactive and visually immersive 3D Solar System simulation built with THREE.js and powered by Vite. The project features realistic planets, moons, orbits, dynamic lighting, post-processing effects, and intuitive user controls — delivering a rich, educational space experience.


![Solar_System](images/solar_system.png)

![Earth](images/earthnew.png)

![Sun](images/sunnew.png)

![Mars](images/mars.png)

## Features

### Core Setup
- Scene, Camera, and Renderer configured for efficient real-time rendering.
- Orbit Controls for smooth navigation.
- Optimized Texture Loading for planets, moons, and rings.

### Post-Processing Effects
- BloomPass — glowing halo around the Sun.
- OutlinePass — white hover outline on planets.
- EffectComposer — manages layered visual effects.

### Starfield Background
- Realistic deep-space star environment.

### Interactive Controls
- dat.GUI panel for:
  - Orbit speed adjustments
  - Visual tuning
  - Sun glow intensity
- Play / Pause button to Play / Stop animation.
### Lighting System
- AmbientLight for global illumination.
- PointLight at the Sun for realistic shadows.

### Planet and Moon Detail
- Accurate size, tilt, textures, bump maps, rings, and atmospheres.
- Moons with realistic orbits.
- Earth ShaderMaterial simulating day/night transitions and animated clouds.
- Non-spherical moons (Phobos and Deimos) modeled from 3D geometry.

### Orbits and Rotation
- Planets and moons rotate and orbit with scaled motion.
- Inner planets remain near true-scale; gas giants visually reduced for balance.

### Shadows
- Dynamic shadows cast from the Sun’s light source.

### Asteroid Belts
- Procedurally generated asteroid fields:
  - 1,000 between Mars and Jupiter
  - 3,000 in the Kuiper Belt
- Lightweight textures for smooth performance.

### Selection and Interaction
- Hover highlight on planets.
- Click-to-zoom with planet information popup.
- Closing the popup returns the camera to the default view.

### Music 
- Preloaded background music for immersion.
- On-screen music control panel including:
  - Play / Pause
  - Volume control
  - Music toggle on/off

## Resources
3D objects and textures were sourced from the following free repositories:
- [NASA 3D Resources](https://nasa3d.arc.nasa.gov/images)
- [Solar System Scope Textures](https://www.solarsystemscope.com/textures/)
- [Planet Pixel Emporium](https://planetpixelemporium.com/index.php)
- [TurboSquid](https://www.turbosquid.com/)

## Installation and Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/3d-solar-system.git
    ```
2. Navigate to the project directory:
    ```sh
    cd 3d-solar-system
    ```
3. Install dependencies:
    ```sh
    npm install
    ```
4. Start the development server:
    ```sh
    npm run dev
    ```
5. Open your browser and navigate to `http://localhost:3000` to see the 3D Solar System in action.

## Conclusion
This project delivers a detailed and engaging visualization of our solar system — combining realistic planetary modeling, advanced effects, user interaction, and immersive background music. Explore planets, moons, and asteroid belts in a fully interactive 3D environment.