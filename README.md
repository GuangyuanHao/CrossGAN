# Cycle-Consisted Adversarial Networks with Cross Latent Spaces

  Based on CycleGAN, the aim is expected to improve quality of translated images of CycleGAN.
  
  This model's novel points: every translator in CycleGAN are divided into an encoder and a decoder, so a kind of new L1 loss can added into the total loss of CycleGAN. Latent spaces, i.e., spaces of features which encoders encode images into, are expected to be pushed into the same space, so that the model is expected to be pushed to learn more common information between two domains.
