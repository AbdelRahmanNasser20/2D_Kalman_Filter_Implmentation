# 2D Kalman Filter Implementation

This repository contains a simple 2D Kalman filter implementation using C++ and the Eigen library. The purpose of this implementation is to demonstrate the basic concepts of the Kalman filter for a 2D constant velocity model. This example can be extended and modified for other applications such as object tracking, sensor fusion, and control systems.

## Prerequisites

To compile and run the code, you need to have the following software installed on your system:

- A C++ compiler supporting C++11 or later (e.g., GCC, Clang, or Visual Studio)
- The Eigen library (http://eigen.tuxfamily.org/index.php?title=Main_Page)

## Setup

1. Install the Eigen library following the instructions on the official website (http://eigen.tuxfamily.org/index.php?title=Main_Page).

2. Clone this repository to your local machine:

```
git clone https://github.com/your_username/2D_Kalman_Filter.git
```

3. Navigate to the repository folder:

```
cd 2D_Kalman_Filter
```

4. Compile the code:

```
g++ -std=c++11 -I /path/to/eigen/ main.cpp -o kalman_filter
```

Replace `/path/to/eigen/` with the actual path to the Eigen library on your system.

5. Run the compiled executable:

```
./kalman_filter

```


## Description

The `KalmanFilter2D` class implements a 2D Kalman filter using a constant velocity model. It provides `predict` and `update` methods to estimate the state of a 2D object given a sequence of noisy observations.

The example program in `main.cpp` demonstrates the use of the `KalmanFilter2D` class with a simple set of simulated noisy observations. The program outputs the filtered state estimate for each observation.

Note that this example is a basic demonstration of the Kalman filter concept and should be extended and modified for other applications or real-world problems.
