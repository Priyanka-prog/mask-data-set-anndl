# mask-data-set-anndl

Image Classification
Artificial Neural Networks and Deep Learning
Priyanka Rajendran Sai Ram Sadineni
10704486 10744802

Statement of Work:
To classify images depicting groups of people based on the number of masked people. In specific, to discriminate between images depending on the following cases:
1) All the people in the image are wearing a mask
2) No person in the image is wearing a mask
3) Someone in the image is not wearing a mask.

Predictions using classifiers:
We implemented a basic model and fed the dataset for training. The accuracy was very less so we decided to change some parameters. By tuning hyperparameters like learning rate and batch size normalization provided an improvement in training. By using a different technique for feature extraction, increasing the number of
epochs and reducing image size also provided better results. Techniques like dropout, kernel regularization, adding more dense layers doesn’t provide expected results.

Transfer Learning:
We implemented the basic model as discussed in the exercise class. And training the datasets with different numbers of layers and different learning rates with
minimum epoch . And tried using the keras application Xception because it outperforms with better computational efficiency. And changed the optimizer to RMSprop. And we improved our prediction with these settings.
