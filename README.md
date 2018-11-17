Use of K-nearest neighbours to predict the particulate matter for one day.
The features used for training are as follows:
1) BEN
2) CO
3) EBE
4) NHMC
5) NO
6) NO_2
7) O_3
8) SO_2
9) TCH
10) TOL

24 more dummy features were created for the one hot encoding of the 24 station IDs present.
The values predicted were
1) PM10
2) PM25

Four methods were applied:
1) Rolling window
2) Recursive window
3) Rolling window with normalized vectors, so that magnitude of values in the above fields won't
create a bias
4) Recursive window with normalized vectors

The results are presented separately with overall and zoomed-in graphs to pinpoint the minima
in RMSE vs the number of neighbours.

