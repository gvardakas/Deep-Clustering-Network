### DCN: Deep Clustering Network

Forked from xuyxu (https://github.com/xuyxu/Deep-Clustering-Network)

# Results


| NMI | ARI | parameters |
|-----|-----|------------|
| 0.667 | 0.572 | xuyxu repo standard values |
| 0.629 | 0.474 | mnist.py --lamda 0.05 --pre-epoch 50 --epoch 50 --latent_dim 10 |
| 0.604 | 0.442 | mnist.py --lamda 0.05 --pre-epoch 50 --epoch 50 --latent_dim 5|
| 0.639 | 0.500 | mnist.py --lamda 0.5 --pre-epoch 20 --epoch 50 --latent_dim 10|
| 0.617 | 0.506 | mnist.py --lamda 0.5 --pre-epoch 20 --epoch 50 --latent_dim 3 |
| 0.685 | 0.492 | mnist.py --lamda 0.5 --pre-epoch 20 --epoch 50 --latent_dim 3 --lr 0.01 |
|-----|-----|------------|
|0.81|0.73| original paper claim, pre-/eps 50, lamda 0.05, 4-layer 500-500-2000-10|


