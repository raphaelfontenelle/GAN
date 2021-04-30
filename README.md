# GAN

Using GAN to create a digit image from a noise imput. Just open the file in Colab, choose GPU and Run the code.

The idea is to have two neural networks, a discriminator, which judges the output of the Generator if the image produced is true, that is, made by a person, or false. The Generator network tries to trick the Discriminator by making it assign a true value as if the digits had been created by a human. And Generator network receives feedback from the Discriminator a percentage of how close it has come to real one and makes de Generator adjustments itself to produce an even more real image.
