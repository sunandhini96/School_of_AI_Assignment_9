# School_of_AI_Assignment_9

# output summary :

           Conv2d-1           [-1, 16, 30, 30]             448
            Conv2d-2           [-1, 32, 28, 28]           4,640
            Conv2d-3           [-1, 48, 26, 26]          13,872
         AvgPool2d-4             [-1, 48, 1, 1]               0
            Linear-5                    [-1, 8]             384
            Linear-6                    [-1, 8]             384
            Linear-7                    [-1, 8]             384
            Linear-8                   [-1, 48]             432
      UltimusBlock-9                   [-1, 48]               0
           Linear-10                    [-1, 8]             384
           Linear-11                    [-1, 8]             384
           Linear-12                    [-1, 8]             384
           Linear-13                   [-1, 48]             432
     UltimusBlock-14                   [-1, 48]               0
           Linear-15                    [-1, 8]             384
           Linear-16                    [-1, 8]             384
           Linear-17                    [-1, 8]             384
           Linear-18                   [-1, 48]             432
     UltimusBlock-19                   [-1, 48]               0
           Linear-20                    [-1, 8]             384
           Linear-21                    [-1, 8]             384
           Linear-22                    [-1, 8]             384
           Linear-23                   [-1, 48]             432
     UltimusBlock-24                   [-1, 48]               0
           Linear-25                   [-1, 10]             490
================================================================
Total params: 25,786
Trainable params: 25,786
Non-trainable params: 0

Input size (MB): 0.01
Forward/backward pass size (MB): 0.55
Params size (MB): 0.10
Estimated Total Size (MB): 0.66

# Output training logs :

EPOCH: 1 (LR: 1.856635533445111e-05)
Batch_id=97 Loss=2.62711 Accuracy=15.57%: 100%|██████████| 98/98 [00:20<00:00,  4.84it/s]

Test set: Average loss: 2.0312, Accuracy: 2345/10000 (23.45%)

EPOCH: 2 (LR: 0.003735710158920203)
Batch_id=97 Loss=2.11942 Accuracy=21.48%: 100%|██████████| 98/98 [00:20<00:00,  4.83it/s]

Test set: Average loss: 1.9866, Accuracy: 2722/10000 (27.22%)

EPOCH: 3 (LR: 0.007452853962505956)
Batch_id=97 Loss=2.10211 Accuracy=22.70%: 100%|██████████| 98/98 [00:20<00:00,  4.90it/s]

Test set: Average loss: 1.9906, Accuracy: 2781/10000 (27.81%)

EPOCH: 4 (LR: 0.011169997766091707)
Batch_id=97 Loss=2.83089 Accuracy=19.05%: 100%|██████████| 98/98 [00:20<00:00,  4.89it/s]

Test set: Average loss: 1.9776, Accuracy: 2613/10000 (26.13%)

EPOCH: 5 (LR: 0.01488714156967746)
Batch_id=97 Loss=2.09412 Accuracy=22.81%: 100%|██████████| 98/98 [00:19<00:00,  4.91it/s]

Test set: Average loss: 1.9787, Accuracy: 2952/10000 (29.52%)

EPOCH: 6 (LR: 0.018556384154661588)
Batch_id=97 Loss=2.08744 Accuracy=23.45%: 100%|██████████| 98/98 [00:20<00:00,  4.81it/s]

Test set: Average loss: 1.9472, Accuracy: 3056/10000 (30.56%)

EPOCH: 7 (LR: 0.017579208535288125)
Batch_id=97 Loss=2.08331 Accuracy=23.82%: 100%|██████████| 98/98 [00:19<00:00,  5.01it/s]

Test set: Average loss: 1.9703, Accuracy: 2791/10000 (27.91%)

EPOCH: 8 (LR: 0.016602032915914663)
Batch_id=97 Loss=2.07809 Accuracy=24.13%: 100%|██████████| 98/98 [00:19<00:00,  4.91it/s]

Test set: Average loss: 1.9376, Accuracy: 3034/10000 (30.34%)

EPOCH: 9 (LR: 0.0156248572965412)
Batch_id=97 Loss=2.07603 Accuracy=24.34%: 100%|██████████| 98/98 [00:20<00:00,  4.89it/s]

Test set: Average loss: 1.9427, Accuracy: 2923/10000 (29.23%)

EPOCH: 10 (LR: 0.01464768167716774)
Batch_id=97 Loss=2.07687 Accuracy=24.09%: 100%|██████████| 98/98 [00:19<00:00,  4.91it/s]

Test set: Average loss: 1.9355, Accuracy: 3068/10000 (30.68%)

EPOCH: 11 (LR: 0.013670506057794277)
Batch_id=97 Loss=2.06931 Accuracy=24.63%: 100%|██████████| 98/98 [00:19<00:00,  4.92it/s]

Test set: Average loss: 1.9549, Accuracy: 2990/10000 (29.90%)

EPOCH: 12 (LR: 0.012693330438420816)
Batch_id=97 Loss=2.07199 Accuracy=24.70%: 100%|██████████| 98/98 [00:19<00:00,  4.90it/s]

Test set: Average loss: 1.9360, Accuracy: 3054/10000 (30.54%)

EPOCH: 13 (LR: 0.011716154819047354)
Batch_id=97 Loss=2.06916 Accuracy=24.65%: 100%|██████████| 98/98 [00:20<00:00,  4.85it/s]

Test set: Average loss: 1.9338, Accuracy: 3017/10000 (30.17%)

EPOCH: 14 (LR: 0.010738979199673891)
Batch_id=97 Loss=2.06743 Accuracy=24.82%: 100%|██████████| 98/98 [00:20<00:00,  4.82it/s]

Test set: Average loss: 1.9269, Accuracy: 3132/10000 (31.32%)

EPOCH: 15 (LR: 0.009761803580300429)
Batch_id=97 Loss=2.06403 Accuracy=24.97%: 100%|██████████| 98/98 [00:19<00:00,  5.02it/s]

Test set: Average loss: 1.9330, Accuracy: 3055/10000 (30.55%)

EPOCH: 16 (LR: 0.008784627960926968)
Batch_id=97 Loss=2.06572 Accuracy=24.94%: 100%|██████████| 98/98 [00:19<00:00,  5.00it/s]

Test set: Average loss: 1.9401, Accuracy: 3090/10000 (30.90%)

EPOCH: 17 (LR: 0.007807452341553507)
Batch_id=97 Loss=2.06190 Accuracy=25.27%: 100%|██████████| 98/98 [00:19<00:00,  4.96it/s]

Test set: Average loss: 1.9210, Accuracy: 3113/10000 (31.13%)

EPOCH: 18 (LR: 0.006830276722180043)
Batch_id=97 Loss=2.05988 Accuracy=25.04%: 100%|██████████| 98/98 [00:20<00:00,  4.89it/s]

Test set: Average loss: 1.9154, Accuracy: 3155/10000 (31.55%)

EPOCH: 19 (LR: 0.00585310110280658)
Batch_id=97 Loss=2.05973 Accuracy=25.32%: 100%|██████████| 98/98 [00:19<00:00,  4.91it/s]

Test set: Average loss: 1.9240, Accuracy: 3145/10000 (31.45%)

EPOCH: 20 (LR: 0.00487592548343312)
Batch_id=97 Loss=2.06200 Accuracy=25.14%: 100%|██████████| 98/98 [00:20<00:00,  4.88it/s]

Test set: Average loss: 1.9125, Accuracy: 3235/10000 (32.35%)

EPOCH: 21 (LR: 0.003898749864059657)
Batch_id=97 Loss=2.06142 Accuracy=25.56%: 100%|██████████| 98/98 [00:19<00:00,  4.93it/s]

Test set: Average loss: 1.9146, Accuracy: 3167/10000 (31.67%)

EPOCH: 22 (LR: 0.0029215742446861946)
Batch_id=97 Loss=2.05658 Accuracy=25.35%: 100%|██████████| 98/98 [00:20<00:00,  4.82it/s]

Test set: Average loss: 1.9132, Accuracy: 3193/10000 (31.93%)

EPOCH: 23 (LR: 0.0019443986253127321)
Batch_id=97 Loss=2.05563 Accuracy=25.68%: 100%|██████████| 98/98 [00:19<00:00,  4.98it/s]

Test set: Average loss: 1.9120, Accuracy: 3220/10000 (32.20%)

EPOCH: 24 (LR: 0.0009672230059392731)
Batch_id=97 Loss=2.04934 Accuracy=25.92%: 100%|██████████| 98/98 [00:19<00:00,  5.03it/s]

Test set: Average loss: 1.9082, Accuracy: 3257/10000 (32.57%)

# Training and validation loss curves :

<img width="701" alt="sc" src="https://user-images.githubusercontent.com/63030539/221403630-1bf0ea26-fc57-4ba6-b496-6d7f63017a4d.png">
