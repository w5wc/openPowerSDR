# OpenHPSDR-PowerSDR

Latest Release v3.3.16 May 14, 2017
# 3.3.16 (2017-5-14)
- Corrects sporadic HIGH SWR meassage found in v3.3.14 & v3.3.15
- Chris, W2PA added support for the Behringer CMD Micro and CMD PL-1 MIDI controllers in the Midi2Cat interface. More information can be found in the BehringerMods_Midi2Cat_v2.pdf located in the PowerSDR working directory.
- Chris, W2PA added a RIT/XIT sync feature to the console that increaments both RIT and XIT the same amount when adjusting either of the values.
- Corrected an issue with the 'Limit Stitched Receivers' feature not updating when using the 8000DLE.
- Added 200W Meter Trim range for the 8000DLE.


# 3.3.15 (2017-3-31)
- Corrected sporadic HIGH SWR message found in v3.3.14

# 3.3.14 (2017-3-26)
- PureSignal updated to v2.0.
- Add capibities for the ANAN-8000DLE transceiver.
- Bryan, W4WMT added a bug fix to the VAC feature that dramatically reduced buffer overruns     when using smaller buffers.
- Corrected out of band errors for the Japan region
- Fixed CTUN so that the settings would be restored correctly after restarting the program.
- Added NR2 and SNB to the DSP menu when in the Collapsed mode.
- Added the following CAT Commands:
  - ZZLI - Sets or Reads the PureSignal (PS-A) button status
  - ZZNS - Sets or Reads the RX1 NR2 button status
  - ZZNV - Sets or Reads the RX2 NR button status
  - ZZNW - Sets or Reads the RX2 NR2 button status
