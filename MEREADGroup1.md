# Project Classification + X

[See this example live!](https://dkguo.github.io/classification-web-template/)

This is a template website to host a TensorFlow JS (TFJS) version of image classification models online. 

To host your own classification + X website:
- Copy this repository to your own repository
- Place the TFJS model JSON and shards to the `model_tfjs/` folder
- Open `model_tfjs/model.json` and replace instances of "Functional" with "Model"
- Overwrite the `CLASSES_NAMES` list in `index.js`
- Make sure the image normalization steps in `index.js` is the same as training
- Modify `index.html` as desired
- Host on GitHub Pages

Learn more about exporting models from TensorFlow to TFJS [here.](https://www.tensorflow.org/js/tutorials/conversion/import_keras)

See more TFJS examples [here.](https://github.com/tensorflow/tfjs-examples)

What’s the project about? Why is it important/interesting?
Our project is about trash classification. The AI will be able to identify the difference between recyclable, compostable, and waste. We chose to do this project because 
What will you do?/How will you do it?
What results do you expect to have?
