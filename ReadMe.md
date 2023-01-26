In this project, We will train a generative adversarial network (GAN) to generate new handwritten digits after showing it pictures of many real handwritten digits from mnist dataset provided by Tensorflow.
Generative Adversarial Nets is that you have two networks, a generator G and a discriminator D, competing against each other.

The generator is trained to fool the discriminator, it wants to output data that looks as close as possible to real, training data.

The discriminator is a classifier that is trained to figure out which data is real and which is fake.
I trained it for 400 epochs.

Images Generated by Generator After Particular epochs------------
             EPOCH 1
![gan_generated_image_1](https://user-images.githubusercontent.com/96010766/214817848-7a2041ed-99cf-453b-bb1d-c6246073cf62.png)EPOCH 20
![gan_generated_image_20](https://user-images.githubusercontent.com/96010766/214818080-e0c7c7e6-24a4-4baa-a912-1ab800f19da0.png)EPOCH 100
![gan_generated_image_100](https://user-images.githubusercontent.com/96010766/214818198-7ece46c5-0ee8-441f-914f-02244854db4e.png)EPOCH 200
![gan_generated_image_200](https://user-images.githubusercontent.com/96010766/214818300-3c781f13-502d-4775-a237-79239a1abff8.png)EPOCH 300
![gan_generated_image_300](https://user-images.githubusercontent.com/96010766/214818359-17809780-5c28-471d-b27c-215efc54e912.png)EPOCH 400
![gan_generated_image_400](https://user-images.githubusercontent.com/96010766/214818407-39a0fde8-428d-4f34-a948-33c3e0f4f010.png)
