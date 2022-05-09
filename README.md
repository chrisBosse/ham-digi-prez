<!-- Software Names -->
<!-- cSpell:ignore ardop digi Digimode Echolink microcontroller mobilink NBEMS Sabrent soundcard Thingiverse WinLink -->
<!-- Modes -->
<!-- cSpell:ignore APRS BPSK CONTESTI Contestia FreeDV FREQCAL FSKH FSTV GMDSS IRLP JTMS MFSK MSKMS OFDM pactor QPSK RTTY SSTV THRB WSJT WSPR -->
<!-- Terms -->
<!-- cSpell:ignore Baofeng POTA prowords -->
<!-- Comments to throw off Grammar Check -->
<!-- cSpell:ignore iwou -->
<!-- wg:iwou = write good: is wordy or unneeded -->
<!-- wg:cwm = write good: can weaken meaning -->
<!-- wg:iac = write good: is a cliche -->
# Digital Amateur Radio Survey

A cursory glance at digital amateur radio modes, what to use, and how to do
them.

## What is Digital?

2 : composed of data in the form of especial<!-- wg:cwm -->ly binary digits <https://www.merriam-webster.com/dictionary/digital>

## Digital Revolution

The Digital Revolution (also known as the Third Industrial Revolution) is the shift from mechanical and analogue electronic technology to digital electronics which began in the latter half of the 20th century, with the adoption and proliferation of digital computers and digital record-keeping, that continues to the present day. <https://en.wikipedia.org/wiki/Digital_Revolution>

## Is CW a Digital Mode?

Yes, and No. I discovered the philosophical argument depends on perspective.

- On/Off (2 symbols)
- Dit/Dah/intra-character-space/inter-character-space/word-space (5 symbols)
- Dit-with-trailing-space/Dah-with-trailing-space/character-space(minus trailing space)/word-space(minus trailing space) (4 symbols)
- ~26-alpha/~10-numeric/some-odd-punctuation/some-odd-prowords (~45 symbols)

## Digital in Amateur Radio

- Modes
  - OOK (On Off Keying)
    - CW (and predecessors)
  - FSK (Frequency Shift Keying)
    - RTTY
  - PSK (Phase Shift Keying)
  - MFSK (Multi<!-- wg:iwou -->ple Frequency Shift Keying)
    - RTTY
  - OFDM (Orthogonal Frequency Division Multiplexing)
    - Vara
  - Error Detection and Error Correction
    - Parity
    - Checksum
    - FEC (Forward Error Correction)
  - Text and Packets
  - Digital Audio Codecs
  - Digital Video???
  - etc..
- Modulation and Demodulation (Modem)
  - Pactor modems
  - Software Modems
    - Software-defined decoding of existing modes
    - Weak Signal Modes
      - FT8
      - JT65
    - Esoteric Modes
- ADC and DAC (Analog to Digital Converters and Digital to Analog Converters)
  - at Audio Frequencies
    - Freakishly sharp filters and sensitive detectors (freakishly is not a technical term)
    - FFT (Fast Fourier Transforms)
    - Software defined
  - at RF
    - HF (Mountain Topper, Flex Radio, SDR)
    - VHF/UHF (Baofeng UV-5R, RTL-SDR, FT-3DR)
    - Microwave (up to 8GHz <https://en.wikipedia.org/wiki/List_of_software-defined_radios>)
- Logging software
  - Contesting
  - Online log submission
- internet
  - IRLP - Internet Relay Linking Project
  - EchoLink
  - WinLink (also stand-alone mode)
  - DMR, D-Star, System Fusion
  - Resources
    - YouTube
    - Manuals
    - Online Groups
      - Long Island CW Club
      - CWOps Academy
      - Ham Radio Crash<!-- wg:iac --> Course
      - POTA
    - Discord, Twitch
    - Software, GitHub, GitLab
    - 3D Printing, Thingiverse

## Whiteboard Notes

Figure out Audience

Figure out Goal

- Digi talk perspective
  - Who - Experienced Hams trying something new
- Overview on Terms ?
- What is it?
  - Is it worth it? Give reasons.
- What do I need to get started?
  - It depends
    - Sound and Trans<!-- wg:iwou -->mit control

I real<!-- wg:cwm -->ly want to give a Survey of Digital Modes, but that is showing off. KEEP IT SHORT!!!

Leave time at end to give 1 or 2 modes a deeper dive.

Print out notes - in-depth notes?

Tie in stories:

- Dale and J Taylor
- Chris and Harry Bloomberg W3YJ and NBEMS

Purpose:

- EmComm - List of names + Supplies
- Asynchronous Communications
- Send Files and Links
- Relays

## Concepts

- CAT Control - Computer Aided Transceiver Control
- Serial Protocol RS-232
  - Voltage standards 15 V vs. 5 V vs. 3.3 V
  - Connectors 9 pin vs. 15 pin vs. 23 pin (Most use 2 or 3 pins: TX Data, RX Data, CTS/RTS)
    - Clear to Send or Ready to Send
  - Universal Serial Bus
    - Allows dozens of "channels"; over one medium interface
- VOX - Voice on X-mit (Trans<!-- wg:iwou -->mit)
- Over-driving audio
- USB vs. LSB (always USB for digital)
- Modem - Modulation / Demodulation
  - Sound Modem
  - Signal over... HF (USB) vs. VHF/UHF (FM) vs. Direct Frequency Control?
- Dumb terminal
- Baud rate vs. bit rate vs. character rate
- Encoding vs. Encryption
- Error Detection (and Correction)
  - Parity
  - Checksum
  - FEC - Forward Error Correction
- Power level to use
- Frequencies to use

## Hardware

- Modems
  - DigiRig
  - SignalLink
  - RigBlaster (old)
  - Digimode
  - Soundcard
    - PC Soundcard
    - USB Soundcard
      - Sabrent USB Audio
    - Radio internal Soundcard
      - IC-7300
  - Mobilink
    - With and without Terminal Emulator
    - with and without PTT control (without use VOX)
  - Pactor Modem
- "Computers"
  - Desktops
  - Laptops
  - Tablets
  - Cellphones
    - Android
    - Apple
  - SBC - Single Board Computers
    - Raspberry Pi (variants)
    - Intel NUK
  - Microcontroller
    - Arduino

## Who am I and What are my Interests?

I like mixing computers and Amateur radio.

My major interest in Amateur radio is "When all else fails."

I do not give much time to internet-enabled or internet-required Amateur radio.

- DMR
- D-STAR
- System Fusion

- IRLP - Internet Radio Linking Project
- EchoLink
- Remote Ham Shack

I do not give much time to contesting and awards.

- RTTY
- FT8

I do not give much time to sending pictures, video, or digital audio.

- SSTV
- FSTV
- Codec 2 - Open Source Speech codec  <https://www.rowetel.com/wordpress/?page_id=452>
- FreeDV - Open Source Amateur Digital Voice <https://freedv.org/>
- M17 - new digital radio protocol for data and voice <https://m17project.org/>

I do not give much time to esoteric operating, weak signal modes, nor antenna testing.

- Earth-Moon-Earth EME
- Whisper - WSPR <https://www.wsprnet.org/drupal/wsprnet/map>

## Popular

Modes over last 2 hours

| Mode     | Count     |
| :--      |       --: |
| FT8      | 2,058,602 |
| FT4      |    38,476 |
| WSPR     |    24,290 |
| JS8      |     7,009 |
| CW       |     3,840 |
| PSK31    |        63 |
| FSKH105  |        42 |
| OPERA    |        34 |
| FST4     |        17 |
| PI4      |        16 |
| JT65     |        14 |
| RTTY     |        14 |
| MSK144   |        12 |
| CONTESTI |         7 |
| FST4W    |         6 |
| ROS      |         5 |
| JT9      |         4 |
| SSB      |         3 |
| Q65      |         3 |
| Q65B     |         2 |
| THOR16   |         2 |
| THOR11   |         2 |
| PSK63    |         2 |
| OLIVIA 4 |         2 |

Pulled 2022-05-05T2258L  
<https://pskreporter.info/cgi-bin/pskstats.pl>

## Modes

Sortable Table? with properties?

- is Proprietary
- Popularity (popular, rare, waning, waxing, regional, niche)
- is Current
- Start date
- Software to use
- Hardware to use
- is Voice capable
- is Text capable
- is keyboard to keyboard
- is Data capable
- Baud rate

- CW
- APRS - Amateur Packet Reporting System (no longer Position)
- RTTY
- psk31
- BPSK
- MFSK
- Contestia
- Winlink
- Ardop
- VARA HF
- VARA VHF
- FLamp
- JS8
- wiresX
- Fusion
- DMR
- D-STAR
- IRLP
- Echolink
- Ham Phone
- FT8
- WSPR - Whisper
- JT8
- Packet
- Weather Fax
- SSTV - Slow Scan Television
- ALE - Automatic Link Establishment
- WiFi - Ham channel (no encryption, use call sign in MAC address to identify)
- 3.5 GHz Ham network (No longer, no encryption)

## Online Resources

- W1HKJ home of FlDigi <http://www.w1hkj.com/>
  - Sights and Sounds <http://www.w1hkj.com/modes/index.htm>
  - Android App <http://www.w1hkj.com/files/AndFlmsg/>
  - NBEMS <http://www.arrl.org/nbems>
- APRS.fi <https://aprs.fi/>
- PSK Reporter <https://pskreporter.info/pskmap.html>
  - all modes
  - FT8
  - FT4
  - CW
  - PSK
  - PSK31
  - JS8
  - JT65
  - JT
  - OLIVIA 8
  - OPERA
  - WSPR
  - CONTESTI
  - JT9
  - ROS
  - MSK144
  - PI4
  - RTTY
  - OLIVIA
  - PSK63
  - FST4W
  - Q65
  - SSB
  - THOR
  - OLIVIA 1
  - PSK125
  - MFSK16
  - FST4
  - FM
  - FSK441
  - SSTV
  - OLIVIA 3
  - JT65B
  - JTMS
  - FREQCAL
  - SIM31
  - Q65A
  - HELL
  - RTTY-45
  - FREEDV
  - OLIVIA-1
  - Q65C
  - Q65B
  - THOR16
  - THOR8
  - OFDM500F
  - PKT
  - DOMINO
  - OLIVIA-8
  - JT4
  - JT6M
  - THOR11
  - G8BCG
  - EM
  - THOR22
  - PSK63F
  - PSK125RC
  - GMDSS
  - B
  - PSK32
  - THRB
  - DL5AKF
  - QPSK31
  - MFSK32
  - MSKMS
  - MFSK8
  - FSKH105
  - OLIVIA 4
  - -F-T8

- WSJT-X
- VARA
- Winlink
- KM4ACK Build-a-Pi

## Acronyms

- AM - Amplitude Modulation
- ASK - Audio Shift Keying
- CAT - Computer Aided Transceiver
- Codec - coder/decoder, a device or computer program which encodes or decodes a data stream or signal <https://en.wikipedia.org/wiki/Codec>
- EME - Earth-Moon-Earth, moon bounce
- FEC - Forward Error Correction
- FM - Frequency Modulation
- FSK - Frequency Shift Keying
- IP - Ingress Protection (dust/water)
- IP - Internet Protocol
- LSB - Lower Side Band
- MAC - Machine Access Control, 6 byte identifier for network hardware 41:43:31:45:51:20 ("AC1EO ")
- MFSK - Multi<!-- wg:iwou -->ple Frequency Shift Keying
- NBEMS - Narrow Band Emergency Messaging Software <http://www.arrl.org/nbems>
- OOK - On-Off Keying
- PSK - Phase Shift Keying
- SSB - Single Side Band
- USB - Universal Serial Bus
- USB - Upper Side Band
- VoIP - Voice Over IP (Internet Protocol)
- VOX - Voice on X-mit (Trans<!-- wg:iwou -->mit)
