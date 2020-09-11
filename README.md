# tf-builds

This is a list of optimized WHL Tensorflow builds for cloud computing use with Intel® Xeon® Scalable CPUs.

## Download links
|Date of build|Tensorflow|Python|Platform|Architecture|Links|
|-------------|----------|------|--------|------------|-----|
|2019-07-29|1.14.0|3.6|Linux|skylake|[download](https://github.com/publicMindee/tf-builds/releases/download/1.14.0-no-mkl-c5/tensorflow-1.14.0-cp36-cp36m-linux_x86_64.whl)|


## Installation
In your Python environment, run 
```pip install --upgrade /path/to/file.whl```

## Best VMs
A non exhaustive list of VMs that work best for CPU Tensorflow inference.

#### AWS

> *Intel® Xeon® Platinum 8124M*
* c5.4xlarge (16 vCPUs / 32GB)
* c5.9xlarge (36 vCPUs / 72GB)

> *Intel® Xeon® Platinum 8275L*
* c5.12xlarge (48 vCPUs / 96GB)

#### Azure

> *Intel® Xeon® Platinum 8168*
* F16s_v2 (16 vCPUs / 32GB)
* F32s_v2 (32 vCPUs / 64GB)
* HC44rs (44 vCPUs / 352GB)

> *Intel® Xeon® Platinum 8272*
* F48s_v2 (48 vCPUs / 96GB)

#### GCP
> *Undisclosed Intel® Xeon® Scalable CPU*
* c2-standard-30 (30 vCPUs, 120GB)
