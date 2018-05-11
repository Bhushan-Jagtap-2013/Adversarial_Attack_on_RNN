### About

This project tries to extend existing C&W attack on Recurrent Neural Network


### Required Packages

```bash
    sudo apt-get install python3-pip
    sudo pip3 install --upgrade pip
    sudo pip3 install pillow scipy numpy tensorflow-gpu keras h5py
```
   
#### To create the RNN sentiment analysis models:

```bash
    python3 Train_RNN_model.py
```

#### To test attack on RNN

```bash
    python3 test_attack.py
```

#### Reference paper

Towards Evaluating the Robustness of Neural Networks" by Nicholas Carlini and David Wagner, at IEEE Symposium on Security &
Privacy, 2017.
