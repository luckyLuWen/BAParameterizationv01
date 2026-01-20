# BAParameterizationv01
Dataset used in the BA parameterization scheme described in our journal paper, including all data required for the experiments.

## Example Command

The following command illustrates how the BA demo program can be executed.
The paths do **not** correspond to actual files in this repository and are provided for demonstration purposes only.

```bash
Demo.exe -d 5 \
  --base <PATH_TO_INPUT_DATASET> \
  --variant sba \
  --gn \
  --no-robust \
  --report <PATH_TO_OUTPUT_REPORT> \
  --pose <PATH_TO_OUTPUT_POSE> \
  --out3d <PATH_TO_OUTPUT_3D_POINTS>
