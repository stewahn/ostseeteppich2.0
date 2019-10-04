# ostsee2.0
ar.js and a-frame project with two different custom markers for two different 3d-models. This code is a working example for ar.js and a-frame. ostsee is the name of a local water-project. It exists a carpet for marketing-issues with a picture of the topography in the scale 1:2700. The idea is to put analog markers on the analog carpet and go for augmented reality. One model which can be seen is the eiffel-tower. Maybe it helps to imagine how big is this water-project. You can run this code via https://stewahn.github.io/ostsee2.0/ which calls directly the index.html in this github repository. A question appears: Allow the browser to use your camera. After it you see on your display what your camera is seeing. Hold the camera in the direction of the custom markers. (The markers are in this repository as .jpg-files too. Print that out or show it on other displays.) The marker has to fill the half of the screen. Freeze the position. After one or two seconds you should see on your display a 3d-model of the eiffel tower or a container ship, depends on the marker. Go arround it, move the camera and you can explore the 3d-model from every single side. In the code you can see, that the models are scaled. The three.js editor finds out, how much it has to be scaled https://threejs.org/editor/ (import your model there and if it fits on the grid, you are on the right way. Use that scale-numbers in your own code). This project based on the following links:
https://jeromeetienne.github.io/AR.js-docs/posts/post-XX-how-to-use-arjs-with-aframe.html
https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
https://medium.com/swlh/ar-js-the-simplest-way-to-get-cross-browser-augmented-reality-on-the-web-10cbc721debc
https://medium.com/@aschmelyun/so-you-want-to-get-started-with-ar-js-41dd4fba5f81
