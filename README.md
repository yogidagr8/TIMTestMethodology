# TIMTestMethodology
My methodology for TIMs on my laptop
___

## Hardware
#### Lenovo Legion 5
- AMD Ryzen 7 5800H (95W Max)
- Nvidia RTX 3060 (115W + 15W Dynamic Boost)
- 16GB RAM
- 2 x 1TB PCIE 3.0 NVME SSD
- Windows 11 Version 22H2 (0S Build 22621.1778)

## Software

### Testing
- Cinebench R23.200 for CPU load application
- 3D Mark Port Royal for GPU load application

### Measuring
- HWiNFO 64 7.30-4870 for live logging 

##### Recorded Parameters

###### CPU Core temperatures
- CPU (Tct1/Tdie)
- CPU Core
- CPU SOC

###### CPU Core Clocks
- Core Clocks
- Core O Clock (perf #213)
- Core 1 Clock (perf #111)
- Core 2 Clock (perf #4/5)
- Core 3 Clock (perf #718)
- Core 4 Clock (perf #1/2)
- Core 5 Clock (perf #6/7)
- Core 6 Clock (perf #3/4)
- Core 7 Clock (perf #516)

###### CPU Core Voltages
- CPU core Voltage (SV12 TFN)
- SOC Voltage TFN)
- CPU core VID (Effective)

###### CPU Package Power
- CPU Package Power
- Core Powers
- Core 0 Power
- Core I Power
- Core 2 Power
- Core 3 Power
- Core 4 Power
- Core 5 Power
- Core 6 Power
- Core 7 Power
- CPU core Power (SV12 TFN)
- CPU SOC Power TFN)
- core+Soc Power (SV12 TEN)
- CPU PPT
- APU STAPM

###### GPU Temperature
- GPU Temperature
- GPU Hotspot Temperature

###### GPU Voltage
- GPU Core Voltage
- GPU Rail Voltages
- GPU FBVDD Input Voltage
- GPU 8-pin #1 Input voltage

###### GPU Power
- GPU Power
- GPU Rail Powers
- GPU Core (NVVDD) Input Power (sum)
- GPU FBVDD Input Power
- GPU 8-pin #1 Input Power
- GPU PCIe +3.3V Input Power (est)
- GPU Core (NWDD2) Input Power (sum)
- GPU Input PP Source Power (sum)
- GPU core (NVVDD) Output Power
- GPU core (NWDD) Output Power

###### GPU Clocks
- GPU Clock
- GPU Memory Clock
- GPU Video Clock
- GPU Effective Clock

## Testing Process
- Old TIM is removed using 99% ethanol and lint free wipes
- New TIM is applied using a spatula
- Heatsinks are cleaned using a soft bristle brush and a camera lens blower
- Heatsink assembly screws are tightened in a star pattern
- Laptop is put back together
- Performance of laptop is set to "Performance" (Highest power and fan speeds)
- Run all core cinebench r23 load for 1 hour to cure the TIM on CPU
- Port Royal is run for 1 hour on gpu to cure the TIM on GPU
- Ambient temp is recorded and logged along with thermal testing
- CPU and GPU tests are run separately one after the other for 30 minutes each.

>**NOTE**: The CPU and GPU loads are not applied simultaneously as i am trying to test the performance of the TIM not the cooling efficiency of my laptop.

- After initial testing the laptop is used intensively by me for 1 week with 2 hours of gaming loads per day on average at maximum performance modes
- Test process above is repeated after the completion of that 1 week to test for blatant pump outs
- Logged CSV are uploaded to this github repo in the TIM's respective folder

