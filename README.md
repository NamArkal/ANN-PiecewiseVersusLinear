# ANN-PiecewiseVersusLinear
First homework where we compare performance of replacing sigmoid activation function with different number of segments for piecewise activation.

Dataset used: Bank note Authentication with output 0/1 i.e. not fake or fake.

Below is the comparison table:

Accuracy (at the end of 50 epochs) and loss ( also at the end of 50 epochs) for sigmoid and different number of pieces for piecewise linear are given below:
1. Sigmoid 
  - 0.9812
  - 0.24
2. N=4
  - 0.9792
  - 0.0332
3. N=6
  - 0.9792
  - 0.0319
4. N=8
  - 0.9865
   - 0.0245
5. N=10
  - 0.9781
  - 0.0277
6. N=12
  - 0.9062
  - 0.09
7. N=14
  - 0.9885
  - 0.0284

For Sigmoid versus piecewise, the loss is reduced by a factor of 10 and hence piecewise performs better for loss.
Accuracy mostly stays the same with little fluctuations between sigmoid and piecewise.
As for comparing the performance between the different number of segments in piecewise, there is a gradual dip in loss till n=8 and an increase again as number of segments increase. 
