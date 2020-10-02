# ESPCN-tf2.0

You need tensorflow 2.0 to run this code.

Learning rate = 0.001(initial, recommended), which is different from original paper. Original paper suggest start with 0.01 and decay to 0.0001, but this simply didn't work for me.

Dataset : https://www.kaggle.com/saputrahas/dataset-image-super-resolution?

Some images are grey scaled. I cropped the image by 720 x 720 and dropped if grey scaled.

I couldn't handle whole dataset because of V-ram problem. I only used 150 images from dataset. Additional study is needed to solve this problem.

Therefore, performance is not as good as the original paper's.

Review of ESPCN paper : https://yun905.tistory.com/1
