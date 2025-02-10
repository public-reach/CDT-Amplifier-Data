# CDT Amplifier Dataset
CDT Amplifier Dataset consists of gain spectrum measurements of two types of Erbium-Doped Fiber Amplifier (EDFA), namely, booster amplifier and pre-amplifier. These readings are taken with the help of optical channel monitors (OCMs). This dataset consists of measurements taken on booster amplifier with ten gain settings from 15 to 25 dB in the step size of 1 dB, while the measurements on pre-amplifier are taken with eleven gain settings from 20 to 35 dB in the step size of 1.5 dB. At each of these gain settings, the channel loadings and input power levels are varied.

# Terminologies -
CDT: Collected Dataset from Testbed
EDFA: Erbium-Doped Fiber Amplifier
ROADM: Reconfigurable Optical Add-Drop Multiplexer
WSS: Wavelength Selective Switch
MUX/DEMUX: Multiplexer / Demultiplexer

# Header Description of dataset files -
1. timestamp: Time at which reading is taken
2. key: It is unique for each row in the dataset. It is a combination of three values - total gain value, step of attenuation and channel loading index (E.g. g33.5.0_s6_r8 represents that total gain value of 33.5 dB is set on EDFA device, channel loading used="[1,3,5,7,10,13,15,17,21,25,27,31,33]" and wss attenuation set index is 6).
3. input_ch_powers - Channel Powers at the input of EDFA (in dBm).
4. total_input_power - Total input power of EDFA (in dBm).
5. total_output_power - Total output power of EDFA (in dBm).
6. total_gain - Total gain value set on EDFA (in dB).
7. output_ch_powers - Channel Powers at the output of EDFA (in dBm).
