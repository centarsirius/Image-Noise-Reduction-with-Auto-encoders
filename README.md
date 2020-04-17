# Image-Noise-Reduction-with-Auto-encoders.\

The goal is to create a composite model in which we can simply feed a noisy image, and the model will first reduce noise in that image and then use this output image and run it through the Classifier to get the class prediction. Idea being that even if our incoming data in a production setting is noisy, our classifier should be able to work well because of the noise reduction from the Auto-encoder.
