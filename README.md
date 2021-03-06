This is the code for the paper: ["Exploring and Improving Robustness of Multi Task Deep Neural Networks via Domain Adaptable Defenses"](https://arxiv.org/abs/2001.05286)

To run: import the requirements.txt and utilize the command structure below.

python train.py --data_dir data\canonical_data\bert_uncased --train_dataset sst --test_dataset sst // FOR MT-DNN

python main.py --dynet-seed 1 --mode dev --load model_dumps/bilstm-word-only --attack swap --num-attacks 3 --model bilstm-char // FOR ADVERSARIAL MISPELLINGS


In case of any questions feel free to email me at: katchu11@gmail.com

The code is adapted from: 
https://github.com/danishpruthi/Adversarial-Misspellings
https://github.com/namisan/mt-dnn
https://github.com/google-research/bert
