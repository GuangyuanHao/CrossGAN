# Cycle-Consisted Adversarial Networks with Cross Latent Spaces

  This project is under research. Based on CycleGAN, the aim is expected to improve quality of translated images of CycleGAN.
  
  This model's novel points: 
  
  Every translator in CycleGAN are divided into an encoder and a decoder, so a kind of new L1 loss can added into the total loss of CycleGAN. Latent spaces, i.e., spaces of features which encoders encode images into, are expected to be pushed into the same space, so that the model is expected to be pushed to learn more common information between two domains. The UNIT also achieved the same idea, but UNIT made all the two kinds of latent spaces get into the space of normal distribution, This project is just expected to achieve that the two kinds of latent spaces are drawn together. The common space will be still unknown.
  ## Current results
  The current results get the similar effect as CycleGAN. When translated to horse, zebra's stripe is still a bit clear. This model still needs to be improved.
  ### Horse to Zebra
   ![h2](https://github.com/GuangyuanHao/CrossGAN/raw/master/results/h2.jpg) 
   ![z2](https://github.com/GuangyuanHao/CrossGAN/raw/master/results/z2.jpg)
  ### Zebra to Horse 
   ![zz1](https://github.com/GuangyuanHao/CrossGAN/raw/master/results/zz1.jpg) 
   ![hh1](https://github.com/GuangyuanHao/CrossGAN/raw/master/results/hh1.jpg) 
