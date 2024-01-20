# Multi Window Comm (3D scene)

## Introduction
Using Three.js and localStorage API, this project demonstrates how to communicate accross multiple windows in this case 3d rendering and mixing the 2 worlds together when the windows overlap. You can use this kind of thing to implement multiplayer multi window games where the players al share 1 machine (i don't know how you'll do it) It's designed for developers interested in advanced web graphics and window management techniques.

## Features
- 3D scene creation and rendering with Three.js.
- Synchronization of 3D scenes across multiple browser windows.
- Dynamic window management and state synchronization using localStorage.

## Installation
Clone the repository and open `index.html` in your browser to start exploring the 3D scene.

```
git clone https://github.com/abummoja/MultiWindowJS-HTML
```

or just Download the source code.
## Usage
The 3D scene is rendered in `index.html`, which serves as the entry point of the application.

## Structure and Components
- `index.html`: Entry point that sets up the HTML structure and includes the Three.js library and the main script.
- `three.r124.min.js`: Minified version of the Three.js library used for 3D graphics rendering.

## Detailed Functionality
- `WindowManager` handles the lifecycle of multiple browser windows, including creation, synchronization, and removal. It uses localStorage to maintain state across windows.

## Contributing
Contributions to enhance or expand the project are welcome. Feel free to fork the repository, make changes, and submit pull requests.

## License
This project is open-sourced under the MIT License.

## Acknowledgments
- The Three.js team for their comprehensive 3D library.