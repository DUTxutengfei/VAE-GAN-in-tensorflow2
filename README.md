# VAE-GAN-in-tensorflow2
## an implementation of VAE-GAN in tensorflow2

original paper:

http://arxiv.org/abs/1512.09300

input :

64×64×1 Grayscale image in **tfrecord** format.

batch size = 128;

I added a new idea in this code which did not appear in the original paper,it is called **"weighted loss"**,which performed well in my task.
