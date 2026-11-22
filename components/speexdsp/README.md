# speexdsp (subset)

Echo canceller (`mdf.c`) and preprocessor (`preprocess.c`, used for residual echo
suppression) from [xiph/speexdsp](https://github.com/xiph/speexdsp), commit
`7a158783df74efe7c2d1c6ee8363c1e695c71226`, BSD-3-Clause (`COPYING`). Unmodified
except for the generated `speexdsp_config_types.h`.

Used when `CONFIG_TAB5_ECHO_SPEEX` is selected (see `main/Kconfig.projbuild`).
