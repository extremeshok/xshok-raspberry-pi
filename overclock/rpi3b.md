# RPI 3B OVERCLOCKING
```
# Set the dedicated video memory from the available ram
gpu_mem=16 # Default 128

# Force Turbo Mode, Disable power savings
#force_turbo=1 # save the planet... leave disabled

# Turbo at boot for 1minute
initial_turbo=60

# Minimum frequency of the dynamic clock (Defaults are 600 and 250)
arm_freq_min=900 # Default 600
core_freq_min=325 # Default 250

# Overheat protection. Sets clocks and voltages to default when the SoC reaches this Celsius value
temp_limit=80 # Default 85

# CPU & GPU
arm_freq=1350 # Default 1200
core_freq=500 # Default 400
gpu_freq=500 # Default 400
over_voltage=3

# RAM
sdram_freq=600 # Default 450
sdram_schmoo=0x02000020
over_voltage_sdram_p=4
over_voltage_sdram_i=3
over_voltage_sdram_c=3

# SD Card
boot_delay=1
dtparam=sd_overclock=100
dtoverlay=sdtweak,overclock_50=100
```
