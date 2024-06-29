# rb.f_1

![keyboard](https://drive.google.com/uc?id=1FSsnuG9wuVsLoMuD6AxEJ7aLmVjcnm7L)

## virtual environment

If running with a python virtual environment, run this:

```sh
source ~/software/zephyrproject/.venv/bin/activate
```
<<<<<<< Updated upstream
||||||| constructed merge base
west build -p always -b nice_nano_v2 -- -DSHIELD=rbf0_left -DZMK_CONFIG="/home/rob/keyboard/keyboard_rb.f_0/config" -DZMK_EXTRA_MODULES="/home/rob/keyboard/keyboard_rb.f_0"
=======
west build -p always -b nice_nano_v2 -- -DSHIELD=rbf1 -DZMK_CONFIG="/home/rob/keyboard/keyboard_rb.f_1/config" -DZMK_EXTRA_MODULES="/home/rob/keyboard/keyboard_rb.f_1"
>>>>>>> Stashed changes

## build

```
west build -p always -b nice_nano_v2 -- -DSHIELD=rbf0_left -DZMK_CONFIG="/Users/rob/keyboard/keyboard_rb.f_0/config" -DZMK_EXTRA_MODULES="/Users/rob/keyboard/keyboard_rb.f_0"
```
