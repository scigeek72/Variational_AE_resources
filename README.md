# Variational_AE_resources
Contains all the sources I have used to build VAE

## Books

## Paper
- [Tutorial on Variational Autoencoders](https://arxiv.org/pdf/1606.05908.pdf) By Carl Doersch
- [Variational Inference with Normalizing Flows](https://arxiv.org/pdf/1505.05770.pdf) By Resende and Mohamed (google/DeepMind)
- [Auto-encoding Variational Bayes](https://arxiv.org/abs/1312.6114) By Kingma and Welling
- [An Introduction to Variational AutoEncoders](https://arxiv.org/pdf/1906.02691.pdf) by Kingma and Welling   
  - An extended version of their seminal paper on VAE 
- [GEE: A Gradient-based Explainable Variational Autoencoder for Network Anomaly Detection System](https://www.comp.nus.edu.sg/~lowkh/pubs/cns2019.pdf)
- [Normalizing Flows: An Introduction and Review of Current Methods](https://arxiv.org/abs/1908.09257) By Koyzev, Simon, Brubaker (2020)
- [beta-VAE:Learning Basic Visual Concepts with a Constrained Variational Framework](https://www.deepmind.com/publications/beta-vae-learning-basic-visual-concepts-with-a-constrained-variational-framework) by Higgins, Matthey, Pal, Burgess, Glorot, Botvinick, Mohamed, Lerchner (DeepMind)
- [Hands-On Bayesian Neural Network-A tutorial bfor Deep Learning Users](https://arxiv.org/pdf/2007.06823.pdf)
- [Data Augmentation in HDLSS with VAE](https://arxiv.org/pdf/2105.00026.pdf)
  - This is a very nice paper in terms of how easily it explained some of the complicated stuff on how to improve upon the traditional VAE. More importantly, it contains lots of references to other papers that tried to improve modeling of the data distribution as well as moving away from traditional gaussian prior. **Must read** (even if some of the Reimannian Metric stuff is not clear).    

## Blogs
- [Variational Autoencoder](https://mbernste.github.io/posts/vae/) By Jeremy Bernstein
- [Black-box Variational Inference via the reparameterization gradient](https://mbernste.github.io/posts/reparameterization_vi/) By Jeremy Bernstein
- [Variational Inference](https://mbernste.github.io/posts/variational_inference/) By Jeremy Bernstein 
  - Note: These blogs by Jeremey Bernstein contains mathematical discussion on variational autoencoder and why it is called variational and so forth. Nice one.
- [Totorial#5: Variational Autoencoder](https://www.borealisai.com/research-blogs/tutorial-5-variational-auto-encoders/) By Borealis AI
- [A Step Up with Variational AutoEncoders] (https://jaketae.github.io/study/vae/) By Jake Tae
  - Note: Other blog posts by Jake Tae are very informative  
- [From ELBO to DDPM](https://jaketae.github.io/study/elbo/) By Jake Tae 
  - *DDPM* stands for Denoising Diffusion Probabilistic Models 
- [Variational AutoEncoders](https://docs.google.com/presentation/d/1RXzhDy3TTN8qZ2coLPn1HSab1-aSBMFdWHLiSP6WNr8/edit#slide=id.ga9c05187ea_0_447) 
  - Slides
- [Understanding KL-Divergence](https://nipunbatra.github.io/blog/ml/2022/01/29/kl-divergence.html) By Nipun Batra 
- [Bayesian Linear Regression](https://nipunbatra.github.io/blog/ml/2020/02/20/bayesian-linear-regression.html) by Nipur Batra
- [A quick intro to Bayesian Neural networks](https://matthewmcateer.me/blog/a-quick-intro-to-bayesian-neural-networks/) By Matthew McAteer
- [Understanding The Variational Lower Bounds](https://xyang35.github.io/2017/04/14/variational-lower-bound/) By Xiton Yang
- [What is Variational Autoencoders?](https://github.com/christianversloot/machine-learning-articles/blob/main/what-is-a-variational-autoencoder-vae.md#continuity-and-completeness) By Christian Versloot
- [Variational Autoencoders](https://www.jeremyjordan.me/variational-autoencoders/) By Jeremy Jordon
  - Notes: The resources mentioned at the end of this blog is **priceless**.
- [Building Variational Autoencoders in Tensorflow](https://danijar.com/building-variational-auto-encoders-in-tensorflow/) By Danijar Hafner
- [Tutorial- What is a Variational AutoEncoder?](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/) By Jaan Altosaar 
  - This is the [github repo](https://github.com/altosaar/variational-autoencoder) 
- [Density Estimation: Variational Autoencoders](http://ruishu.io/2018/03/14/vae/) By Rui Shu
- [KL-Divergence Explained](https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained) 
- [Variational Inference with Normalizing Flows](https://indico.cern.ch/event/939335/contributions/3946863/attachments/2073692/3491279/mpp-jc-23July20.pdf) by Jennifer Ngadiuba (caltech) ML Journal Club
- [Normalizing Flows](https://github.com/kamenbliznashki/normalizing_flows) 
- [Normalizing Flows Tutorial](https://blog.evjang.com/2018/01/nf1.html) By Eric Jang 
- [A Tutorial on VAE with Concise Keras Implementation](https://tiao.io/post/tutorial-on-variational-autoencoders-with-a-concise-keras-implementation/) By Louis Tiao
- [Implementating VAE in Keras:Beyond the QuickStart Tutorial](http://louistiao.me/posts/implementing-variational-autoencoders-in-keras-beyond-the-quickstart-tutorial/) By Louis Tiao
- [Simple and Effective VAE Training with Calibrated Decoders](https://orybkin.github.io/sigma-vae/) by Rybkin, Daniildis and Levin
- [Understanding VAEs](https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73) By Joseph Rocca
- [From AE to Beta-VAE](https://lilianweng.github.io/posts/2018-08-12-vae/) By Lil'Log 
  - **Note** Her other posts on Diffusion models and ML in general is very informatave.  
- [Evidence, KL-divergence, and ELBO](https://mpatacchiola.github.io/blog/2021/01/25/intro-variational-inference.html) By Massimiliano Patacchiola 
  - A good read on ELBO. Read his other posts as well.  
- [Variational Inference in Bayesian Neural Network](http://krasserm.github.io/2019/03/14/bayesian-neural-networks/) By Martin Krasser

## Python resources/Packages
- [Tensorflow-Probability + Keras]()
- [Pyro: Variational AE](http://pyro.ai/examples/vae.html)
  - Note: VAE in pytorch

