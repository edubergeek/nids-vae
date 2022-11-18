# Network Intrusion Detection System (NIDS) using Variational AutoEncoder (VAE)
repo: nids-vae on github

Adapted from an excellent article by [Alon Agmon](https://medium.com/@alon.agmon) titled [Hands-on Anomaly Detection with Variational Autoencoders](https://towardsdatascience.com/hands-on-anomaly-detection-with-variational-autoencoders-d4044672acd5)

Uses the [UC Irvine KDD 1999 netflow dataset](https://kdd.ics.uci.edu/databases/kddcup99/task.html)

Best model weights are saved as vae-mlp.h5 obtained by running for 88 epochs and producing very good K=6 clustering, where 2 are normal and 4 are anomalous.
There still remain some unclassified attack samples classified as normal traffic.


