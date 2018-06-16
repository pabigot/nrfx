# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2018-2019 Peter A. Bigot

mdk_inc = include_directories('.')
if 'NRF51' == device
  arm_startup_s = files('arm_startup_nrf51.s')
  gcc_startup_s = files('gcc_startup_nrf51.S')
  iar_startup_s = files('iar_startup_nrf51.s')
  system_c = files('system_nrf51.c')
elif device.startswith('NRF52810')
  arm_startup_s = files('arm_startup_nrf52810.s')
  gcc_startup_s = files('gcc_startup_nrf52810.S')
  iar_startup_s = files('iar_startup_nrf52810.s')
  system_c = files('system_nrf52810.c')
elif device.startswith('NRF52811')
  arm_startup_s = files('arm_startup_nrf52811.s')
  gcc_startup_s = files('gcc_startup_nrf52811.S')
  iar_startup_s = files('iar_startup_nrf52811.s')
  system_c = files('system_nrf52811.c')
elif device.startswith('NRF52832')
  arm_startup_s = files('arm_startup_nrf52.s')
  gcc_startup_s = files('gcc_startup_nrf52.S')
  iar_startup_s = files('iar_startup_nrf52.s')
  system_c = files('system_nrf52.c')
elif device.startswith('NRF52840')
  arm_startup_s = files('arm_startup_nrf52840.s')
  gcc_startup_s = files('gcc_startup_nrf52840.S')
  iar_startup_s = files('iar_startup_nrf52840.s')
  system_c = files('system_nrf52840.c')
else
  error('Unsupported device: ' + device)
endif
