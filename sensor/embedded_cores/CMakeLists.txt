# Makefile - Embedded Cores
#
# Copyright (c) 2025 STMicroelectronics
#
# SPDX-License-Identifier: Apache-2.0

zephyr_include_directories(./)

if(CONFIG_USE_ST_MEMS_ISPU)
  set(EXAMPLE_PATH st-mems-ispu/examples/)

  # ism330is_lsm6dso16is
  set(ISM330IS_LSM6DSO16IS_PATH ${EXAMPLE_PATH}/ism330is_lsm6dso16is/)

  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/printf/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/crc8/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/pedometer/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/mag_calibration/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/standing_vs_sitting/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/tap_detection/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/wrist_tilt/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/sensor_fusion_9x/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/gyr_calibration/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/sdft/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/wake_up/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/norm/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/sensor_fusion_6x/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/crc32/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/fall_detection/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/acc_calibration/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/inclinometer/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/fitness_activity/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/vibration_severity/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/filter/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/free_fall/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/activity_wrist/output)
  zephyr_include_directories(${ISM330IS_LSM6DSO16IS_PATH}/detect_6d/output)

endif()
