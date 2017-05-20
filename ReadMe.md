# OpenHPSDR-PowerSDR beta releases
# Official Releases are located at https://github.com/tapr

Latest Beta Release v3.3.19 May 19, 2017
# 3.3.19 (2017-5-19)
- Swaped places with XIT and RIT controls on the console.
- Added 4 CAT Commands
 -- ZZAP Audio Peak Filter On/Off
 -- ZZAT APF Tune
 -- ZZAB APB Bandwidth
 -- ZZAA APF Gain

# 3.3.18 (2017-5-16)
- Corrects a compatibility issue with DDUtil
- Corrects the 10x watt meter reading for the Anan-10/10E transceivers

# 3.3.17 (2017-5-15)
- Single side-band Full Carrier (SSBFC)
- Continuous Frequency Compressor (CFC) audio tools

# 3.3.16 (2017-5-14)
- Corrects sporadic HIGH SWR message found in v3.3.14 & v3.3.15
- Chris, W2PA added support for the Behringer CMD Micro and CMD PL-1 MIDI controllers in the Midi2Cat interface. More information can be found in the BehringerMods_Midi2Cat_v2.pdf located in the PowerSDR working directory.
- Chris, W2PA added a RIT/XIT sync feature to the console that increments RIT and XIT the same amount when adjusting either of the values.
- Corrected an issue with the 'Limit Stitched Receivers' feature not updating when using the 8000DLE.
- Added 200W Meter Trim range for the 8000DLE.
