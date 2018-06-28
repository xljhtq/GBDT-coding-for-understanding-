# GBDT-coding-for-understanding-
GBDT demo for sample train

Here is the reference blog:
http://nbviewer.jupyter.org/github/liudragonfly/GBDT/blob/master/GBDT.ipynb

innitialize F
for each epoch:
        1. cur_epoch_samples= 0.8* total_samples
        2. compute residual of every sample  (equation 14)
        3. build tree based on MSE, and then compute the weight of each node (equation 15-2)
        4. update F value with weights of sample-nodes and other samples
