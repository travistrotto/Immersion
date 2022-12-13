# Immersion

Immersion is an immersive 3D start page, built on three.js.

## Installation

Clone or download the html file [here](https://github.com/travistrotto/Immersion/archive/refs/heads/main.zip) to install Immersion.

## Usage

[] Edit Immersion to your liking using your preferred text editor of choice.
[] Host your the html page on githubpages or something similiar

```javaScript
<script type="module">
        import * as THREE from 'https://threejsfundamentals.org/threejs/resources/threejs/r132/build/three.module.js';

        /*  
         *  Light Material
         *  - Uncomment next two lines
         *  - Comment out the cool material to use
         *  - (optional: swap lines 265 and 266) [lighterColor]
         */
        // const material = new THREE.MeshBasicMaterial({ color: lighterColor })
        // material.opacity = 0.1

        /*  
         *  Cool Material
         */
        const material = new THREE.MeshNormalMaterial()
        material.flatShading = true
        material.opacity = 0.25

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)