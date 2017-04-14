# CarND-Term2-P1-EKF

My achievement for CarND-Extended-Kalman-Filter-Project.

See detailed implementations in [`src/FusionEKF.cpp`](src/FusionEKF.cpp), [`src/kalman_filter.cpp`](src/kalman_filter.cpp), and [`src/tools.cpp`](src/tools.cpp).

---
## Setup

When under root path of this repo, compile the source files.
```bash
mkdir build
cd build
cmake ..
make
```

---
## Run Tests

Run tests for the sample data.
```
./ExtendedKF ../data/sample-laser-radar-measurement-data-1.txt output1.txt
./ExtendedKF ../data/sample-laser-radar-measurement-data-2.txt output2.txt
```

For [sample data1](data/sample-laser-radar-measurement-data-1.txt), the RMSE is

| RMSE      |
| --------: |
| 0.0651648 |
| 0.0605379 |
| 0.533212  |
| 0.544193  |
.

For [sample data2](data/sample-laser-radar-measurement-data-2.txt), the RMSE is
| RMSE      |
| --------: |
| 0.185496  |
| 0.190302  |
| 0.476754  |
| 0.804469  |
.

Both satisfy the rubic requirements.
