# Immersion

![image](https://immersion-bucket-bucket.s3.us-east-2.amazonaws.com/torus.png)
![image](https://immersion-bucket-bucket.s3.us-east-2.amazonaws.com/spheres3.png)

Immersion is an immersive 3D start page, built on three.js.

## Installation

Clone or download the html file [here](https://github.com/travistrotto/Immersion/archive/refs/heads/main.zip) to install Immersion.

## Usage

1. Edit Immersion to your liking using your preferred text editor of choice.
2. Host your the html page on githubpages or something similiar

```javascript
<script type="module">
        </> Bonus Light Material included: </>
        
        /*  
         *  Light Material
         *  - Uncomment next two lines
         *  - Comment out the cool material to use
         *  - (optional: swap lines 285 and 286) [lighterColor]
         */
        // const material = new THREE.MeshBasicMaterial({ color: lighterColor })
        // material.opacity = 0.1

        /*  
         *  Cool Material
         *  - Comment all three lines to use Light Material
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