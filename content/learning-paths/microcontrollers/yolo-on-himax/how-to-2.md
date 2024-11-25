---
title: Build The Firmware
weight: 3

### FIXED, DO NOT MODIFY
layout: learningpathall
---

## Build The Firmware

Next, we need to build an image that contains the embedded software (firmware). You will need to have the git version control system installed. Run the command below to verify that git is installed on your system.

```bash
git --version
```

You should see output similar to that below.

```output
git version 2.39.3
```

If not, please follow the steps to install git on your system.

### Step 2.1. Clone the Himax project

You will first need to recusively clone the Himax repository. This will also clone the necessary sub repos such as Arm CMSIS. 

```bash
git clone --recursive https://github.com/HimaxWiseEyePlus/Seeed_Grove_Vision_AI_Module_V2.git
cd Seeed_Grove_Vision_AI_Module_V2
```

### Step 2.2. Compile the Firmware

The make build tool is used to compile the source code. This should take up around 2-3 minutes depending on the number of CPU cores available.

```bash
cd EPII_CM55M_APP_S
make clean
make
```


### Step 2.3. Generate a Firmware Image

```bash
cd ../we2_image_gen_local/
cp ../EPII_CM55M_APP_S/obj_epii_evb_icv30_bdv10/gnu_epii_evb_WLCSP65/EPII_CM55M_gnu_epii_evb_WLCSP65_s.elf input_case1_secboot/
./we2_local_image_gen project_case1_blp_wlcsp.json
```

Your terminal output should end with the following.

```output
Output image: output_case1_sec_wlcsp/output.img
Output image: output_case1_sec_wlcsp/output.img

IMAGE GEN DONE
```
