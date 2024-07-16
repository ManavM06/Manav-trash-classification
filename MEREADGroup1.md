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
Our project is about trash classification. This model will be able to identify the difference between recyclables, compostables, and waste. We chose to do this project because environmental waste pollution is a major issue in the world. Many people are uninformed about the negative effects of littering or discarding items into the wrong bins. For example, many people disregard recycling their plastic. This has heavily damaged water ecosystems where animals like ducks become tangled in plastic beverage rings resulting in their death. In a 2021 Global Citizen article about pollution it predicts, "oceans will contain at least 937 million tons of plastic and just 895 million tons of fish by 2050". With the increasing rate of plastic and other harmful items in our ecosystems, there may be a drastic decline in the amount of living organisms.

What will you do?/How will you do it?
In summary, the model will take in input images of a variety of trash items. Depending on the type of trash (paper, metal, food, etc.), the model will give us an output value that tells us what category of trash that the item belongs to. Our dataset contains over 2,000 images which the model will use to train and classify those images into specific labels like recyclables, compostables, and waste.

What results do you expect to have?
We expect for our model to increase the global use of proper trash dumping. With this helpful tool, people will hopefully gain more knowledge about what trash belongs to a certain bin. This would be benefitial for the environment because with each item of trash being placed in their respective bins, there may be a decrease in the amount of harmful metals and plastics that mistakenly enter ecosystems. 
