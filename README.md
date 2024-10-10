# 🌍 [Earth - 3D Visualization Project](https://your-netlify-link-here.netlify.app/)

## 📝 Description

This GitHub repository contains the source code for a **3D Earth Visualization Website** built using **Three.js**. The website features a rotating Earth with dynamic controls, allowing users to adjust rotation speed, planet tilt, star count, and more! 🌟 The planet's surface, clouds, and city lights are rendered with realistic textures, and a starfield surrounds the Earth for added visual appeal. 🌌

Live demo of the project is hosted on **Netlify**. 🚀

## 🌐 Demo

Check out the live demo of the project here:

[Earth Demo on Netlify](https://earth-threejs-harman.netlify.app/) 🌍

## 🖼️ Preview

![Earth Preview](https://github.com/user-attachments/assets/857873c0-ea9a-4798-bd29-9d8134ec05c4)
![Earth Preview-2](https://github.com/user-attachments/assets/b946c068-de73-4fa2-8ba3-0925580e560a)

## 🤵 Owner

- **Name:** Harman Deep Singh
- **GitHub:** [Harman8815](https://github.com/Harman8815)
- **Netlify:** [Earth on Netlify](https://earth-threejs-harman.netlify.app/)

## 🚀 Technologies Used

- **Languages:** HTML, CSS, JavaScript
- **Library:** [Three.js](https://threejs.org/) (3D Rendering), [OrbitControls.js](https://threejs.org/examples/?q=orbit#misc_controls_orbit) (Camera Controls), [Lil-GUI](https://github.com/georgianc/lil-gui) (UI Controls)
- **Hosting:** [Netlify](https://www.netlify.com/)

## ⚙️ Setup Instructions

**Prerequisites:**
- Clone the repository to your local machine:
  ```bash
  git clone https://github.com/Harman8815/earth-project.git
  ```
- Navigate to the project directory:
  ```bash
  cd earth-project
  ```
- Install dependencies:
  ```bash
  npm install
  ```

**Run the Development Server:**
- Start the local server:
  ```bash
  npm run dev
  ```
- Open your browser and go to `http://localhost:3000`.

## 📲 Features

- 🌍 **3D Earth Visualization** with textures for the surface, clouds, and city lights.
- ✨ **Starfield** with dynamic star count (up to 20,000 stars).
- 🎮 **Interactive Controls** using lil-gui to adjust:
  - 🌠 **Number of stars**
  - 🌀 **Rotation speed** of the Earth
  - 🌎 **Tilt angle** of the Earth
  - 🌟 **Glow effect** around the planet
- 🔄 **Smooth camera movement** using OrbitControls.
- 🖥️ **Responsive Design**: The website automatically adjusts to different screen sizes.

## 🕹️ How to Use

1. 🌐 Open the **Earth Visualization** website in your browser.
2. 🎨 Adjust the settings using the **GUI Panel**:
   - 🌟 Change the **stars count**.
   - 🔄 Adjust the **planet rotation speed**.
   - 🌎 Modify the **planet's tilt angle**.
   - 🌟 Change the **glow effect** around Earth.
3. 🌀 Watch the Earth rotate in real-time with the settings you've configured.

## 🛠️ Build & Deployment

1. **Build the project for production:**
   ```bash
   npm run build
   ```

2. **Deploy the `earth_output` folder** to a hosting service like **Netlify**.

## 📁 File Structure

- `index.html`: The entry point of the project.
- `main.js`: JavaScript file containing Three.js logic and rendering.
- `textures/`: Folder containing textures for the Earth's surface, clouds, and city lights.
- `earth_output/`: Folder containing the built version of the project, used for deployment.

## 🧑‍💻 Contributing

Feel free to fork the repository, make changes, and submit pull requests. Contributions are welcome! 🙌
