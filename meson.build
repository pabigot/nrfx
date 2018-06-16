# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2018-2021 Peter A. Bigot

# See: https://github.com/pabigot/nrfx

project('nrfx', 'c',
        version: '2.4.0-pabigot',
        license: 'BSD-3-Clause & Apache-2.0')
device = get_option('device')

# The subdirectory defines these values:
# * mdk_inc Include object providing path to headers in mdk directory
# * arm_startup_s File object identifying ARM toolchain startup assembly source for device
# * gcc_startup_s File object identifying GNUC toolchain startup assembly source for device
# * iar_startup_s File object identifying IAR toolchain startup assembly source for device
# * system_c File object identifying device startup source file

subdir('mdk')
