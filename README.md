
# Machine Learning AMR Reley Differential Curve

Implementing AMR Reley Differential Curve with Deep Neural Network


### Features
  - using <b>Python Tensorflow</b> for build Deep Neural Network model
  - converting <b>Tensorflow</b> model to tflite for running on Embedded Board ARM Architecture
  - using <b>Golang</b> TFLite to be able to easily run tflite model
  - running on <b>xilinx Zynq-7020</b> Embedded Board
  
## Installation

For Linux/MacOs amd64:

```bash
  go build main.go
```

For xilinx Zynq-7020 (ARM-based computers):

```bash
  CGO_ENABLED=1 GOOS=linux GOARCH=arm CC=arm-linux-gnueabihf-gcc go build -o main
```

## Running

This running for ubuntu/MacOs amd64:

```bash
  ./main
```

This running for xilinx Zynq-7020 (ARM-based computers):

```bash
  LD_LIBRARY_PATH=~/arm ./main
```

#### AMR Relay Differential Curve From AMPro software
![Graph](https://github.com/taherfattahi/dnn-amr-reley-differential-curve/blob/master/images/AMR_Relay_Differential_Curve.png)

#### Graph of the Deep Neural Network
![Graph](https://github.com/taherfattahi/dnn-amr-reley-differential-curve/blob/master/images/graph.png)

#### Model Accuracy Plot
![Graph](https://github.com/taherfattahi/dnn-amr-reley-differential-curve/blob/master/images/model_accuracy_plot.png)

#### Model Loss Plot
![Graph](https://github.com/taherfattahi/dnn-amr-reley-differential-curve/blob/master/images/model_loss_plot.png)

## Collaborators

- Dr.Mohammad Parpaei - Sajad Ansari - [Nima Akbarzade](https://www.github.com/iw4p) 


## License

[MIT](https://choosealicense.com/licenses/mit/)

