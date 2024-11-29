# Car-Reviewer-Project
The “Car Reviewer” project is an interactive 3D web application that allows users to view and explore car models from home. Built using HTML, JavaScript, and the Three.js library, it offers detailed visualizations where users can rotate and zoom in on vehicles. This tool enhances the online car shopping experience, helping users make informed decisions without visiting a showroom.

1. File Descriptions:
The repository includes the following files:

- index.html: Main homepage for the "Car Reviewer" web application. Contains the navigation bar, welcome message, and contact form.
- 3d-viewer.html: Implements the 3D car model viewer using Three.js. Allows users to rotate, zoom, and explore the loaded car model interactively.
- css/style.css: Contains the CSS styles for the homepage, including navigation, welcome section, and footer.
- css/bootstrap.min.css: Bootstrap CSS library for responsive design and layout.
- java/bootstrap.bundle.min.js: Bootstrap JavaScript library for interactive features (e.g., form handling).
- scene.gltf: 3D model of the car used in the project.
- README.md: Comprehensive documentation and setup instructions.
- LICENSE (Optional): Specifies the licensing terms for the project.

2. Project Setup Instructions:
Prerequisites:

- A modern browser supporting WebGL (e.g., Chrome, Firefox).
- A local server (e.g., XAMPP, WAMP, or Node.js) to serve the files locally for optimal functionality.
- Internet connection to load external libraries (Three.js, Bootstrap).
  
Steps to Set Up and Run the Project:

1) Download the Repository.
- Clone the repository to your local machine using the following command:
Code: 
git clone https://github.com/alaahassan14/Car-Reviewer-Project

- Or download the repository as a ZIP file and extract it.

2) Install Required Dependencies.
- Ensure the following libraries are accessible via a CDN:
 a) Three.js
 b) GLTFLoader
 c) OrbitControls

- Ensure Bootstrap resources are linked in index.html and style.css.
  
3. Run a Local Server.

- Place the project folder in your local server's root directory.
- Start the server and navigate to:
     * http://localhost/index.html to view the homepage.
     * http://localhost/3d-viewer.html to interact with the 3D model viewer.
       
4. Verify the 3D Model.
- Ensure scene.gltf is in the correct directory as referenced in 3d-viewer.html.

5. Optional Customization.
- To load a different 3D model, replace scene.gltf with another .gltf file and update the loader.load() path.
