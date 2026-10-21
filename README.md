# RCGDBC

**The code  will be open-sourced upon the acceptance of this paper to ensure reproducibility.**

This is the code for the accepted paper:

**Authors:** Anonymous

**Title:**  *Robust Correntropy Granular Ball Learning for Discrete Bipartite Graph Clustering*



**XX is the main function file.**

Example Output on the **MNIST** dataset:

```txt
MNIST: n=70000, d=784, c=10, p=5000, T=7
MNIST | Parameter progress [1-10/90] | sigma=0.0001 | k=c,...,10c | Starting computation
MNIST | Parameter progress [1/90] | sigma=0.0001 | k=10 | ACC=0.3903±0.0404 | NMI=0.3391±0.0393 | ARI=0.2105±0.0339 | PURITY=0.4224±0.0365 | TIME=27.6229±2.0289 | Iterations=18.80±2.14 | m=1207.2 | SUCCESS
MNIST | Parameter progress [2/90] | sigma=0.0001 | k=20 | ACC=0.5179±0.0479 | NMI=0.4978±0.0445 | ARI=0.3607±0.0563 | PURITY=0.5555±0.0511 | TIME=27.9594±2.0450 | Iterations=24.80±6.71 | m=1207.2 | SUCCESS
MNIST | Parameter progress [3/90] | sigma=0.0001 | k=30 | ACC=0.5534±0.0579 | NMI=0.5500±0.0341 | ARI=0.4161±0.0464 | PURITY=0.6001±0.0398 | TIME=28.2245±2.0226 | Iterations=25.20±4.92 | m=1207.2 | SUCCESS
MNIST | Parameter progress [4/90] | sigma=0.0001 | k=40 | ACC=0.5813±0.0526 | NMI=0.5661±0.0341 | ARI=0.4427±0.0498 | PURITY=0.6311±0.0446 | TIME=28.5076±2.2828 | Iterations=24.80±7.86 | m=1207.2 | SUCCESS
MNIST | Parameter progress [5/90] | sigma=0.0001 | k=50 | ACC=0.5963±0.0599 | NMI=0.5802±0.0428 | ARI=0.4665±0.0609 | PURITY=0.6382±0.0532 | TIME=28.6856±1.8432 | Iterations=24.20±8.08 | m=1207.2 | SUCCESS
MNIST | Parameter progress [6/90] | sigma=0.0001 | k=60 | ACC=0.6364±0.0412 | NMI=0.6100±0.0331 | ARI=0.5101±0.0456 | PURITY=0.6777±0.0362 | TIME=29.1767±1.8690 | Iterations=28.60±7.31 | m=1207.2 | SUCCESS
MNIST | Parameter progress [7/90] | sigma=0.0001 | k=70 | ACC=0.6325±0.0269 | NMI=0.6074±0.0110 | ARI=0.5122±0.0182 | PURITY=0.6787±0.0187 | TIME=29.1917±2.1369 | Iterations=25.40±2.80 | m=1207.2 | SUCCESS
MNIST | Parameter progress [8/90] | sigma=0.0001 | k=80 | ACC=0.6298±0.0204 | NMI=0.5946±0.0138 | ARI=0.4942±0.0202 | PURITY=0.6716±0.0159 | TIME=29.1592±2.0893 | Iterations=21.20±3.76 | m=1207.2 | SUCCESS
MNIST | Parameter progress [9/90] | sigma=0.0001 | k=90 | ACC=0.5705±0.0410 | NMI=0.5496±0.0377 | ARI=0.4313±0.0538 | PURITY=0.6173±0.0456 | TIME=29.7937±2.3938 | Iterations=27.00±9.65 | m=1207.2 | SUCCESS
MNIST | Parameter progress [10/90] | sigma=0.0001 | k=100 | ACC=0.5964±0.0126 | NMI=0.5707±0.0168 | ARI=0.4667±0.0181 | PURITY=0.6469±0.0199 | TIME=29.5923±1.6621 | Iterations=21.20±8.06 | m=1207.2 | SUCCESS
MNIST | Parameter progress [11-20/90] | sigma=0.001 | k=c,...,10c | Starting computation
MNIST | Parameter progress [11/90] | sigma=0.001 | k=10 | ACC=0.3903±0.0404 | NMI=0.3391±0.0393 | ARI=0.2105±0.0339 | PURITY=0.4224±0.0365 | TIME=27.7784±2.4888 | Iterations=18.80±2.14 | m=1207.2 | SUCCESS
MNIST | Parameter progress [12/90] | sigma=0.001 | k=20 | ACC=0.5179±0.0479 | NMI=0.4978±0.0445 | ARI=0.3607±0.0563 | PURITY=0.5555±0.0511 | TIME=28.1006±2.5193 | Iterations=24.80±6.71 | m=1207.2 | SUCCESS
MNIST | Parameter progress [13/90] | sigma=0.001 | k=30 | ACC=0.5534±0.0579 | NMI=0.5500±0.0341 | ARI=0.4161±0.0464 | PURITY=0.6001±0.0398 | TIME=28.4382±2.4049 | Iterations=25.20±4.92 | m=1207.2 | SUCCESS
MNIST | Parameter progress [14/90] | sigma=0.001 | k=40 | ACC=0.5813±0.0526 | NMI=0.5661±0.0341 | ARI=0.4427±0.0498 | PURITY=0.6311±0.0446 | TIME=28.7493±2.4106 | Iterations=24.80±7.86 | m=1207.2 | SUCCESS
MNIST | Parameter progress [15/90] | sigma=0.001 | k=50 | ACC=0.5963±0.0599 | NMI=0.5802±0.0428 | ARI=0.4665±0.0609 | PURITY=0.6382±0.0532 | TIME=28.9025±2.2912 | Iterations=24.20±8.08 | m=1207.2 | SUCCESS
MNIST | Parameter progress [16/90] | sigma=0.001 | k=60 | ACC=0.6364±0.0412 | NMI=0.6100±0.0331 | ARI=0.5101±0.0456 | PURITY=0.6777±0.0362 | TIME=29.3598±2.4559 | Iterations=28.60±7.31 | m=1207.2 | SUCCESS
MNIST | Parameter progress [17/90] | sigma=0.001 | k=70 | ACC=0.6325±0.0269 | NMI=0.6074±0.0110 | ARI=0.5122±0.0182 | PURITY=0.6787±0.0187 | TIME=29.4175±2.5720 | Iterations=25.40±2.80 | m=1207.2 | SUCCESS
MNIST | Parameter progress [18/90] | sigma=0.001 | k=80 | ACC=0.6298±0.0204 | NMI=0.5946±0.0138 | ARI=0.4942±0.0202 | PURITY=0.6716±0.0159 | TIME=29.3017±2.5446 | Iterations=21.20±3.76 | m=1207.2 | SUCCESS
MNIST | Parameter progress [19/90] | sigma=0.001 | k=90 | ACC=0.5705±0.0410 | NMI=0.5496±0.0377 | ARI=0.4313±0.0538 | PURITY=0.6173±0.0456 | TIME=30.0013±2.4697 | Iterations=27.00±9.65 | m=1207.2 | SUCCESS
MNIST | Parameter progress [20/90] | sigma=0.001 | k=100 | ACC=0.5964±0.0126 | NMI=0.5707±0.0168 | ARI=0.4667±0.0181 | PURITY=0.6469±0.0199 | TIME=29.6348±2.5082 | Iterations=21.20±8.06 | m=1207.2 | SUCCESS
MNIST | Parameter progress [21-30/90] | sigma=0.01 | k=c,...,10c | Starting computation
MNIST | Parameter progress [21/90] | sigma=0.01 | k=10 | ACC=0.3903±0.0404 | NMI=0.3391±0.0393 | ARI=0.2105±0.0339 | PURITY=0.4224±0.0365 | TIME=28.6923±1.5220 | Iterations=19.00±1.79 | m=1207.2 | SUCCESS
MNIST | Parameter progress [22/90] | sigma=0.01 | k=20 | ACC=0.5180±0.0478 | NMI=0.4980±0.0443 | ARI=0.3609±0.0561 | PURITY=0.5558±0.0509 | TIME=29.0082±1.5547 | Iterations=24.20±6.62 | m=1207.2 | SUCCESS
MNIST | Parameter progress [23/90] | sigma=0.01 | k=30 | ACC=0.5533±0.0580 | NMI=0.5489±0.0353 | ARI=0.4151±0.0474 | PURITY=0.5998±0.0401 | TIME=29.2894±1.4704 | Iterations=23.80±5.46 | m=1207.2 | SUCCESS
MNIST | Parameter progress [24/90] | sigma=0.01 | k=40 | ACC=0.6059±0.0283 | NMI=0.5835±0.0194 | ARI=0.4678±0.0270 | PURITY=0.6517±0.0326 | TIME=29.7308±1.3080 | Iterations=26.40±7.09 | m=1207.2 | SUCCESS
MNIST | Parameter progress [25/90] | sigma=0.01 | k=50 | ACC=0.5972±0.0604 | NMI=0.5823±0.0447 | ARI=0.4681±0.0622 | PURITY=0.6391±0.0539 | TIME=29.9236±1.6849 | Iterations=25.20±9.54 | m=1207.2 | SUCCESS
MNIST | Parameter progress [26/90] | sigma=0.01 | k=60 | ACC=0.6305±0.0390 | NMI=0.6048±0.0309 | ARI=0.5034±0.0427 | PURITY=0.6739±0.0339 | TIME=30.3531±1.5906 | Iterations=29.00±7.32 | m=1207.2 | SUCCESS
MNIST | Parameter progress [27/90] | sigma=0.01 | k=70 | ACC=0.6343±0.0241 | NMI=0.6086±0.0092 | ARI=0.5139±0.0156 | PURITY=0.6803±0.0167 | TIME=30.2865±1.6970 | Iterations=26.20±3.37 | m=1207.2 | SUCCESS
MNIST | Parameter progress [28/90] | sigma=0.01 | k=80 | ACC=0.6296±0.0203 | NMI=0.5944±0.0135 | ARI=0.4940±0.0199 | PURITY=0.6714±0.0156 | TIME=30.1683±1.3435 | Iterations=21.20±3.76 | m=1207.2 | SUCCESS
MNIST | Parameter progress [29/90] | sigma=0.01 | k=90 | ACC=0.5705±0.0410 | NMI=0.5496±0.0377 | ARI=0.4313±0.0538 | PURITY=0.6173±0.0456 | TIME=31.0354±0.9197 | Iterations=27.00±9.65 | m=1207.2 | SUCCESS
MNIST | Parameter progress [30/90] | sigma=0.01 | k=100 | ACC=0.5958±0.0129 | NMI=0.5710±0.0163 | ARI=0.4674±0.0170 | PURITY=0.6477±0.0184 | TIME=30.6932±1.4777 | Iterations=23.20±8.95 | m=1207.2 | SUCCESS
MNIST | Parameter progress [31-40/90] | sigma=0.1 | k=c,...,10c | Starting computation
MNIST | Parameter progress [31/90] | sigma=0.1 | k=10 | ACC=0.3927±0.0406 | NMI=0.3447±0.0430 | ARI=0.2096±0.0358 | PURITY=0.4145±0.0398 | TIME=27.9012±2.8149 | Iterations=17.40±1.85 | m=1207.2 | SUCCESS
MNIST | Parameter progress [32/90] | sigma=0.1 | k=20 | ACC=0.5025±0.0407 | NMI=0.4831±0.0236 | ARI=0.3406±0.0306 | PURITY=0.5335±0.0354 | TIME=28.2088±2.8039 | Iterations=23.60±3.77 | m=1207.2 | SUCCESS
MNIST | Parameter progress [33/90] | sigma=0.1 | k=30 | ACC=0.5640±0.0543 | NMI=0.5578±0.0273 | ARI=0.4249±0.0381 | PURITY=0.6062±0.0325 | TIME=28.5555±2.7653 | Iterations=26.20±4.26 | m=1207.2 | SUCCESS
MNIST | Parameter progress [34/90] | sigma=0.1 | k=40 | ACC=0.5990±0.0529 | NMI=0.5823±0.0388 | ARI=0.4671±0.0564 | PURITY=0.6413±0.0500 | TIME=28.6666±2.7935 | Iterations=21.00±4.34 | m=1207.2 | SUCCESS
MNIST | Parameter progress [35/90] | sigma=0.1 | k=50 | ACC=0.6082±0.0275 | NMI=0.5876±0.0165 | ARI=0.4795±0.0198 | PURITY=0.6463±0.0197 | TIME=29.0098±2.9793 | Iterations=24.00±7.80 | m=1207.2 | SUCCESS

MNIST | Parameter progress [36/90] | sigma=0.1 | k=60 | ACC=0.6309±0.0382 | NMI=0.6089±0.0287 | ARI=0.5075±0.0399 | PURITY=0.6740±0.0383 | TIME=30.0700±2.8208 | Iterations=40.20±10.53 | m=1207.2 | SUCCESS
MNIST | Parameter progress [37/90] | sigma=0.1 | k=70 | ACC=0.6062±0.0349 | NMI=0.5952±0.0203 | ARI=0.4920±0.0332 | PURITY=0.6644±0.0308 | TIME=29.6264±3.1040 | Iterations=25.80±7.30 | m=1207.2 | SUCCESS
MNIST | Parameter progress [38/90] | sigma=0.1 | k=80 | ACC=0.6210±0.0140 | NMI=0.5938±0.0165 | ARI=0.4927±0.0219 | PURITY=0.6700±0.0164 | TIME=29.6117±2.6360 | Iterations=23.60±4.08 | m=1207.2 | SUCCESS
MNIST | Parameter progress [39/90] | sigma=0.1 | k=90 | ACC=0.5939±0.0336 | NMI=0.5701±0.0319 | ARI=0.4603±0.0475 | PURITY=0.6480±0.0325 | TIME=29.8137±2.4582 | Iterations=23.40±7.63 | m=1207.2 | SUCCESS
MNIST | Parameter progress [40/90] | sigma=0.1 | k=100 | ACC=0.5551±0.0675 | NMI=0.5498±0.0484 | ARI=0.4337±0.0664 | PURITY=0.6152±0.0612 | TIME=30.1765±2.8390 | Iterations=25.60±10.84 | m=1207.2 | SUCCESS
MNIST | Parameter progress [41-50/90] | sigma=1 | k=c,...,10c | Starting computation
MNIST | Parameter progress [41/90] | sigma=1 | k=10 | ACC=0.3940±0.0255 | NMI=0.3304±0.0363 | ARI=0.2018±0.0327 | PURITY=0.4167±0.0291 | TIME=33.1268±1.4317 | Iterations=21.20±2.79 | m=1236.4 | SUCCESS
MNIST | Parameter progress [42/90] | sigma=1 | k=20 | ACC=0.4861±0.0301 | NMI=0.4735±0.0373 | ARI=0.3267±0.0372 | PURITY=0.5106±0.0303 | TIME=33.3425±1.4938 | Iterations=21.20±3.71 | m=1236.4 | SUCCESS
MNIST | Parameter progress [43/90] | sigma=1 | k=30 | ACC=0.5381±0.0242 | NMI=0.5277±0.0176 | ARI=0.3859±0.0313 | PURITY=0.5667±0.0285 | TIME=33.7005±1.4018 | Iterations=25.20±3.66 | m=1236.4 | SUCCESS
MNIST | Parameter progress [44/90] | sigma=1 | k=40 | ACC=0.6141±0.0436 | NMI=0.6003±0.0295 | ARI=0.4897±0.0440 | PURITY=0.6632±0.0388 | TIME=34.0070±1.4447 | Iterations=25.80±3.49 | m=1236.4 | SUCCESS
MNIST | Parameter progress [45/90] | sigma=1 | k=50 | ACC=0.6102±0.0203 | NMI=0.5795±0.0280 | ARI=0.4690±0.0336 | PURITY=0.6447±0.0289 | TIME=34.0019±1.4581 | Iterations=19.80±2.32 | m=1236.4 | SUCCESS
MNIST | Parameter progress [46/90] | sigma=1 | k=60 | ACC=0.6235±0.0505 | NMI=0.6057±0.0471 | ARI=0.4999±0.0695 | PURITY=0.6637±0.0645 | TIME=34.5476±1.4271 | Iterations=23.40±3.50 | m=1236.4 | SUCCESS
MNIST | Parameter progress [47/90] | sigma=1 | k=70 | ACC=0.6151±0.0258 | NMI=0.5962±0.0327 | ARI=0.4941±0.0386 | PURITY=0.6671±0.0252 | TIME=34.6618±1.4864 | Iterations=24.40±5.35 | m=1236.4 | SUCCESS
MNIST | Parameter progress [48/90] | sigma=1 | k=80 | ACC=0.6132±0.0485 | NMI=0.5956±0.0397 | ARI=0.4931±0.0529 | PURITY=0.6639±0.0450 | TIME=34.7812±1.6811 | Iterations=22.80±5.60 | m=1236.4 | SUCCESS
MNIST | Parameter progress [49/90] | sigma=1 | k=90 | ACC=0.6095±0.0384 | NMI=0.5856±0.0346 | ARI=0.4845±0.0452 | PURITY=0.6604±0.0311 | TIME=35.7404±0.6915 | Iterations=31.40±13.17 | m=1236.4 | SUCCESS
MNIST | Parameter progress [50/90] | sigma=1 | k=100 | ACC=0.6053±0.0240 | NMI=0.5792±0.0144 | ARI=0.4707±0.0164 | PURITY=0.6465±0.0145 | TIME=35.4879±1.4801 | Iterations=27.80±4.83 | m=1236.4 | SUCCESS
MNIST | Parameter progress [51-60/90] | sigma=10 | k=c,...,10c | Starting computation
MNIST | Parameter progress [51/90] | sigma=10 | k=10 | ACC=0.3932±0.0366 | NMI=0.3309±0.0346 | ARI=0.2009±0.0321 | PURITY=0.4077±0.0397 | TIME=31.0538±1.6102 | Iterations=17.60±2.33 | m=1200.4 | SUCCESS
MNIST | Parameter progress [52/90] | sigma=10 | k=20 | ACC=0.4803±0.0369 | NMI=0.4767±0.0290 | ARI=0.3188±0.0315 | PURITY=0.5068±0.0322 | TIME=31.4348±1.5655 | Iterations=28.20±9.66 | m=1200.4 | SUCCESS
MNIST | Parameter progress [53/90] | sigma=10 | k=30 | ACC=0.5867±0.0783 | NMI=0.5706±0.0525 | ARI=0.4359±0.0706 | PURITY=0.6106±0.0675 | TIME=31.8007±1.6827 | Iterations=28.20±10.32 | m=1200.4 | SUCCESS
MNIST | Parameter progress [54/90] | sigma=10 | k=40 | ACC=0.6039±0.0327 | NMI=0.5993±0.0147 | ARI=0.4744±0.0203 | PURITY=0.6303±0.0231 | TIME=31.9481±1.9136 | Iterations=26.20±9.02 | m=1200.4 | SUCCESS
MNIST | Parameter progress [55/90] | sigma=10 | k=50 | ACC=0.5792±0.0801 | NMI=0.5878±0.0599 | ARI=0.4559±0.0851 | PURITY=0.6191±0.0730 | TIME=32.1439±1.7955 | Iterations=24.60±5.54 | m=1200.4 | SUCCESS
MNIST | Parameter progress [56/90] | sigma=10 | k=60 | ACC=0.6460±0.0333 | NMI=0.6323±0.0251 | ARI=0.5263±0.0398 | PURITY=0.6873±0.0321 | TIME=32.6799±1.4546 | Iterations=29.20±9.95 | m=1200.4 | SUCCESS
MNIST | Parameter progress [57/90] | sigma=10 | k=70 | ACC=0.6866±0.0361 | NMI=0.6495±0.0063 | ARI=0.5521±0.0105 | PURITY=0.7078±0.0135 | TIME=32.6579±1.6462 | Iterations=26.20±10.34 | m=1200.4 | SUCCESS
MNIST | Parameter progress [58/90] | sigma=10 | k=80 | ACC=0.6124±0.0457 | NMI=0.6092±0.0295 | ARI=0.4950±0.0492 | PURITY=0.6598±0.0381 | TIME=32.4927±1.6287 | Iterations=21.00±5.51 | m=1200.4 | SUCCESS
MNIST | Parameter progress [59/90] | sigma=10 | k=90 | ACC=0.6552±0.0397 | NMI=0.6249±0.0219 | ARI=0.5347±0.0353 | PURITY=0.6936±0.0231 | TIME=32.5977±1.7575 | Iterations=19.80±2.32 | m=1200.4 | SUCCESS
MNIST | Parameter progress [60/90] | sigma=10 | k=100 | ACC=0.5854±0.0481 | NMI=0.5752±0.0407 | ARI=0.4604±0.0594 | PURITY=0.6458±0.0454 | TIME=32.8011±1.9085 | Iterations=19.40±4.84 | m=1200.4 | SUCCESS
MNIST | Parameter progress [61-70/90] | sigma=100 | k=c,...,10c | Starting computation
MNIST | Parameter progress [61/90] | sigma=100 | k=10 | ACC=0.3927±0.0528 | NMI=0.3239±0.0289 | ARI=0.1968±0.0296 | PURITY=0.4058±0.0423 | TIME=31.6545±2.5938 | Iterations=20.60±6.44 | m=1188.6 | SUCCESS
MNIST | Parameter progress [62/90] | sigma=100 | k=20 | ACC=0.4529±0.0477 | NMI=0.4411±0.0360 | ARI=0.2900±0.0396 | PURITY=0.4850±0.0464 | TIME=31.8817±2.5903 | Iterations=20.80±8.66 | m=1188.6 | SUCCESS
MNIST | Parameter progress [63/90] | sigma=100 | k=30 | ACC=0.6080±0.0240 | NMI=0.5774±0.0165 | ARI=0.4512±0.0289 | PURITY=0.6222±0.0219 | TIME=32.3014±2.4533 | Iterations=25.20±4.92 | m=1188.6 | SUCCESS
MNIST | Parameter progress [64/90] | sigma=100 | k=40 | ACC=0.5947±0.0852 | NMI=0.5791±0.0654 | ARI=0.4534±0.0897 | PURITY=0.6166±0.0765 | TIME=32.5378±2.8014 | Iterations=24.40±7.96 | m=1188.6 | SUCCESS
MNIST | Parameter progress [65/90] | sigma=100 | k=50 | ACC=0.6894±0.0284 | NMI=0.6578±0.0171 | ARI=0.5582±0.0220 | PURITY=0.7115±0.0172 | TIME=32.9271±2.7716 | Iterations=29.00±5.90 | m=1188.6 | SUCCESS
MNIST | Parameter progress [66/90] | sigma=100 | k=60 | ACC=0.5998±0.0747 | NMI=0.5915±0.0452 | ARI=0.4663±0.0638 | PURITY=0.6294±0.0574 | TIME=33.0751±2.9675 | Iterations=26.80±9.04 | m=1188.6 | SUCCESS
MNIST | Parameter progress [67/90] | sigma=100 | k=70 | ACC=0.6386±0.0702 | NMI=0.6164±0.0425 | ARI=0.5109±0.0617 | PURITY=0.6814±0.0572 | TIME=33.4385±2.4419 | Iterations=27.80±5.11 | m=1188.6 | SUCCESS
MNIST | Parameter progress [68/90] | sigma=100 | k=80 | ACC=0.6725±0.0391 | NMI=0.6380±0.0220 | ARI=0.5444±0.0336 | PURITY=0.7055±0.0246 | TIME=33.1112±2.7702 | Iterations=20.40±5.28 | m=1188.6 | SUCCESS
MNIST | Parameter progress [69/90] | sigma=100 | k=90 | ACC=0.6212±0.0608 | NMI=0.6031±0.0382 | ARI=0.4984±0.0618 | PURITY=0.6643±0.0448 | TIME=33.2531±2.8199 | Iterations=20.00±3.74 | m=1188.6 | SUCCESS
MNIST | Parameter progress [70/90] | sigma=100 | k=100 | ACC=0.6062±0.0663 | NMI=0.5937±0.0450 | ARI=0.4825±0.0654 | PURITY=0.6503±0.0475 | TIME=33.3870±2.2608 | Iterations=20.20±8.03 | m=1188.6 | SUCCESS
MNIST | Parameter progress [71-80/90] | sigma=1000 | k=c,...,10c | Starting computation
MNIST | Parameter progress [71/90] | sigma=1000 | k=10 | ACC=0.3796±0.0467 | NMI=0.3380±0.0379 | ARI=0.2031±0.0328 | PURITY=0.4106±0.0335 | TIME=29.3723±1.8136 | Iterations=20.20±4.17 | m=1191.4 | SUCCESS
MNIST | Parameter progress [72/90] | sigma=1000 | k=20 | ACC=0.5076±0.0643 | NMI=0.5075±0.0509 | ARI=0.3557±0.0579 | PURITY=0.5404±0.0558 | TIME=29.6524±1.8783 | Iterations=24.80±3.76 | m=1191.4 | SUCCESS
MNIST | Parameter progress [73/90] | sigma=1000 | k=30 | ACC=0.5510±0.0636 | NMI=0.5597±0.0463 | ARI=0.4134±0.0625 | PURITY=0.5816±0.0588 | TIME=29.9938±1.8619 | Iterations=27.80±7.81 | m=1191.4 | SUCCESS
MNIST | Parameter progress [74/90] | sigma=1000 | k=40 | ACC=0.6108±0.0724 | NMI=0.6064±0.0419 | ARI=0.4807±0.0559 | PURITY=0.6447±0.0561 | TIME=30.1024±1.8826 | Iterations=21.40±6.89 | m=1191.4 | SUCCESS
MNIST | Parameter progress [75/90] | sigma=1000 | k=50 | ACC=0.6627±0.0537 | NMI=0.6333±0.0287 | ARI=0.5274±0.0442 | PURITY=0.6913±0.0340 | TIME=30.2865±1.8604 | Iterations=22.00±6.10 | m=1191.4 | SUCCESS
MNIST | Parameter progress [76/90] | sigma=1000 | k=60 | ACC=0.6307±0.0490 | NMI=0.6020±0.0409 | ARI=0.4873±0.0564 | PURITY=0.6610±0.0489 | TIME=31.2464±1.8505 | Iterations=34.20±9.33 | m=1191.4 | SUCCESS
MNIST | Parameter progress [77/90] | sigma=1000 | k=70 | ACC=0.6392±0.0192 | NMI=0.6280±0.0179 | ARI=0.5228±0.0199 | PURITY=0.6843±0.0131 | TIME=31.2970±1.6445 | Iterations=30.40±4.22 | m=1191.4 | SUCCESS
MNIST | Parameter progress [78/90] | sigma=1000 | k=80 | ACC=0.6605±0.0252 | NMI=0.6378±0.0157 | ARI=0.5397±0.0195 | PURITY=0.6992±0.0101 | TIME=30.6983±2.0133 | Iterations=19.00±3.41 | m=1191.4 | SUCCESS

MNIST | Parameter progress [79/90] | sigma=1000 | k=90 | ACC=0.6335±0.0470 | NMI=0.6125±0.0249 | ARI=0.5074±0.0341 | PURITY=0.6752±0.0251 | TIME=31.1968±1.9241 | Iterations=23.80±5.19 | m=1191.4 | SUCCESS
MNIST | Parameter progress [80/90] | sigma=1000 | k=100 | ACC=0.5875±0.0258 | NMI=0.5784±0.0225 | ARI=0.4568±0.0264 | PURITY=0.6357±0.0307 | TIME=30.9898±2.3081 | Iterations=19.00±7.69 | m=1191.4 | SUCCESS
MNIST | Parameter progress [81-90/90] | sigma=10000 | k=c,...,10c | Starting computation
MNIST | Parameter progress [81/90] | sigma=10000 | k=10 | ACC=0.3905±0.0427 | NMI=0.3294±0.0235 | ARI=0.1961±0.0243 | PURITY=0.4077±0.0378 | TIME=26.7391±2.0625 | Iterations=23.40±5.89 | m=1207.2 | SUCCESS
MNIST | Parameter progress [82/90] | sigma=10000 | k=20 | ACC=0.4917±0.0512 | NMI=0.4818±0.0592 | ARI=0.3329±0.0648 | PURITY=0.5239±0.0547 | TIME=26.8850±1.9755 | Iterations=19.60±3.67 | m=1207.2 | SUCCESS
MNIST | Parameter progress [83/90] | sigma=10000 | k=30 | ACC=0.5832±0.0761 | NMI=0.5804±0.0644 | ARI=0.4492±0.0926 | PURITY=0.6141±0.0764 | TIME=27.4842±1.9961 | Iterations=31.20±4.96 | m=1207.2 | SUCCESS
MNIST | Parameter progress [84/90] | sigma=10000 | k=40 | ACC=0.5830±0.0713 | NMI=0.5789±0.0529 | ARI=0.4487±0.0766 | PURITY=0.6195±0.0685 | TIME=27.5177±1.8054 | Iterations=23.60±6.34 | m=1207.2 | SUCCESS
MNIST | Parameter progress [85/90] | sigma=10000 | k=50 | ACC=0.6313±0.0322 | NMI=0.6129±0.0187 | ARI=0.5035±0.0269 | PURITY=0.6670±0.0310 | TIME=27.6729±2.1262 | Iterations=21.60±3.93 | m=1207.2 | SUCCESS
MNIST | Parameter progress [86/90] | sigma=10000 | k=60 | ACC=0.6422±0.0426 | NMI=0.6047±0.0305 | ARI=0.5023±0.0386 | PURITY=0.6770±0.0314 | TIME=28.1317±1.8448 | Iterations=26.60±7.86 | m=1207.2 | SUCCESS
MNIST | Parameter progress [87/90] | sigma=10000 | k=70 | ACC=0.6340±0.0266 | NMI=0.6097±0.0160 | ARI=0.5054±0.0215 | PURITY=0.6790±0.0166 | TIME=28.1841±1.9474 | Iterations=23.40±3.32 | m=1207.2 | SUCCESS
MNIST | Parameter progress [88/90] | sigma=10000 | k=80 | ACC=0.5986±0.0523 | NMI=0.5843±0.0364 | ARI=0.4625±0.0510 | PURITY=0.6367±0.0437 | TIME=27.9969±1.9282 | Iterations=18.40±3.72 | m=1207.2 | SUCCESS
MNIST | Parameter progress [89/90] | sigma=10000 | k=90 | ACC=0.6082±0.0105 | NMI=0.5936±0.0058 | ARI=0.4836±0.0104 | PURITY=0.6587±0.0220 | TIME=28.6560±1.8952 | Iterations=25.40±6.47 | m=1207.2 | SUCCESS
MNIST | Parameter progress [90/90] | sigma=10000 | k=100 | ACC=0.6222±0.0449 | NMI=0.5949±0.0282 | ARI=0.4842±0.0395 | PURITY=0.6603±0.0332 | TIME=28.5068±2.0011 | Iterations=20.80±4.17 | m=1207.2 | SUCCESS
Best mean-ACC parameter:
MNIST | Parameter progress [65/90] | sigma=100 | k=50 | ACC=0.6894±0.0284 | NMI=0.6578±0.0171 | ARI=0.5582±0.0220 | PURITY=0.7115±0.0172 | TIME=32.9271±2.7716 | Iterations=29.00±5.90 | m=1188.6 | SUCCESS
Best individual: sigma=1000, k=40, ACC=0.7495
Labels: experiment_results\Seven\labels\MNIST_Seven_labels.npz
Convergence: experiment_results\Seven\convergence\MNIST_Seven_convergence.xlsx
'''
