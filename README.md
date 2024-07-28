## Training GPT-2 from Scratch using Tiny Shakespeare dataset

In this repo you can find the Tiny Shakespeare dataset (input.txt) and 17 files each representing a step in training GPT-2 model from scratch. In files train_get2-1 through train_get2-8 we setup our code for training. From train_get2-9-speedup-1 thorugh speedup-9 we implement different techniques to speed up our training process.

## Objective

Target - loss less than 0.099

## Training Params - 

- Epochs - 6000
- Batch size = 8
- Number of tokens = 1024

## Results

As seen in below image, after runnning for 6000 epohcs with batch size 8 and tokens 1024, we are able to get our loss to 0.06

<img width="1440" alt="Screenshot 2024-06-27 at 5 28 10 PM" src="https://github.com/Himank-J/ERAV2/assets/55919214/483e98c3-1e9f-4150-9aef-02272bb4623b">

## App

Link to app - https://huggingface.co/spaces/HimankJ/GPT2_CustomTrained

<img width="1247" alt="Screenshot 2024-06-28 at 8 54 01 PM" src="https://github.com/Himank-J/ERAV2/assets/55919214/61ad055f-ff14-458a-811d-087d84a784a3">
