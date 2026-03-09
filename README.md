# Awesome Broadcasting [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 443,833 | 🐛 75 | 📅 2026-03-04 with stars

A curated list of amazingly awesome open source resources for broadcasters.

* [Awesome Broadcasting](#awesome-broadcasting-)
  * [Animation, Graphics & Video Playout](#animation-graphics--video-playout)
  * [Clocks & Studio Screens](#clocks--studio-screens)
  * [Codecs](#codecs)
  * [Communication](#communication)
  * [Companion Screens](#companion-screens)
  * [Connected TVs](#connected-tvs)
  * [Control Systems](#control-systems)
  * [Distributed Media Processing](#distributed-media-processing)
  * [Documentation](#documentation)
  * [DVB & WiFi](#dvb--wifi)
  * [Hybrid Radio](#hybrid-radio)
  * [LiveIP](#liveip)
  * [Media Players](#media-players)
  * [Metadata](#metadata)
  * [Monitoring & Quality Control](#monitoring--quality-control)
  * [Multimedia content processing](#multimedia-content-processing)
  * [Network & Storage Testing](#network--storage-testing)
  * [NMOS](#nmos)
  * [Podcasting](#podcasting)
  * [Radio Production](#radio-production)
  * [Rundown Automation](#rundown-automation)
  * [SCTE-35 & SCTE-104](#scte-35--scte-104)
  * [Software-defined radio](#software-defined-radio)
  * [Streaming](#streaming)
  * [Subtitling](#subtitling)
  * [Video Production](#video-production)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Websites](#websites)
* [Contributing](#contributing)

## Animation, Graphics & Video Playout

* [ffplayout](https://github.com/ffplayout/ffplayout) ⚠️ Archived - Rust and FFmpeg based playout from folder or playlists.
* [Sofie - TV Automation](https://github.com/Sofie-Automation/Sofie-TV-automation) ⭐ 412 | 🐛 2 | 📅 2025-12-16 - MOS-driven automation system for news casts, with many libraries for e.g. device control.
* [SPX - Graphics Controller](https://github.com/TuomoKu/SPX-GC) ⭐ 399 | 🐛 28 | 🌐 JavaScript | 📅 2026-02-14 - Graphics control client for live video productions and live streams.
* [Open Playout Automation](https://github.com/jaskie/PlayoutAutomation) ⭐ 210 | 🐛 13 | 🌐 C# | 📅 2026-02-17 - A CasparCG-based MCR play-out system.
* [Aurena](https://github.com/thaytan/aurena) ⭐ 131 | 🐛 5 | 🌐 C | 📅 2019-10-31 - A network distributed media playback system.
* [Macadam](https://github.com/Streampunk/macadam) ⭐ 119 | 🐛 13 | 🌐 C++ | 📅 2023-07-18 - Blackmagic Node.js bindings that support HTML/CSS (via [Electron](https://www.electronjs.org/)) and SVG (via [Sevruga](https://github.com/Streampunk/sevruga) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2019-02-14) graphics.
* [Bridge](https://github.com/svt/bridge) ⭐ 67 | 🐛 7 | 🌐 JavaScript | 📅 2026-02-28 - Next generation graphics control software, with extension support.
* [OGraf](https://github.com/ebu/ograf) ⭐ 60 | 🐛 21 | 🌐 JavaScript | 📅 2026-03-05 - Open specification for HTML based Graphics, used in live television and post production workflows.
* [Studio TV Player](https://github.com/jaskie/StudioTVPlayer) ⭐ 56 | 🐛 10 | 🌐 C++ | 📅 2026-03-08 - Simple TV studio player with SDI, NDI and MPEG TS outputs.
* [StreamShapers - Ferryman](https://github.com/Streamshapers/StreamShapers-Ferryman) ⭐ 25 | 🐛 6 | 🌐 JavaScript | 📅 2025-10-09 - Web App to generate HTML-Graphics from Lottie.JSON files / from Adobe AfterEffects.
* [Blender](https://projects.blender.org/blender/blender) - 3D creation suite supporting 3D modelling, animation, motion tracking, video editing, and more (overview [here](https://developer.blender.org/)).
* [CasparCG](http://www.casparcg.com/) - A professional graphics and video play-out software, proven in 24/7 broadcasts since 2006.
* [Nebula](https://github.com/nebulabroadcast) - Media asset management and broadcast automation system.
* [NodeCG](https://www.nodecg.dev/) - Broadcast graphics rendered in a browser using Node.js.
* [ossia](https://ossia.io/) - A free and open-source intermedia sequencer.

## Clocks & Studio Screens

* [OnAirScreen](https://github.com/saschaludwig/OnAirScreen) ⭐ 113 | 🐛 4 | 🌐 Python | 📅 2026-01-20 - Cross-platform "OnAir Lamp" solution targeted for use in professional broadcast environments.
* [PiClock](https://github.com/simonhyde/PiClock) ⭐ 33 | 🐛 5 | 🌐 C++ | 📅 2025-12-05 - Customisable network based displays of clocks, on-air, mic live and other studio indicators.
* [PiRSClock-Full](https://github.com/jdgwarren/pirsclockfull) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2014-03-22 - Radio Studio Clock with studio indicators for mics, telephones etc.
* [PiClock Advanced](https://github.com/ael/piclock_advanced) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-03-20 - Improved version of PiRSClock-Full with changed layout, added timers and network capabilities.
* [OATIS](https://github.com/jamiehull/OATIS) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-02-15 - Server Based Studio Clock and Tally system, supporting messaging, physical GPI's and OSC triggering.

## Codecs

* [FLAC](https://www.xiph.org/flac/) - Free Lossless Audio Coding, used by some broadcasters for audio exchange, storage.
* [Lame](https://lame.sourceforge.io/) - A high quality MPEG Audio Layer III (MP3) encoder.
* [opencore-amr](https://sourceforge.net/projects/opencore-amr/) - Audio codecs extracted from Android Open Source Project, including AAC.
* [Opus](https://www.opus-codec.org/) - A totally open, royalty-free, highly versatile audio codec.
* [Turing Codec](https://github.com/bbc/turingcodec) ⭐ 156 | 🐛 9 | 🌐 C++ | 📅 2017-11-13 - An H.265/HEVC open source software encoder designed for fast and efficient video compression.
* [TwoLame](https://www.twolame.org/) - An MPEG Audio Layer 2 (MP2) encoder.

## Communication

* [DYI intercom](https://github.com/matiaspl/intercom) ⭐ 74 | 🐛 2 | 🌐 JavaScript | 📅 2024-05-08 - Hardware + software intercom solution built around Murmur server and headless Mumble clients based on Rasperry Pi.
* [Intercom Manager](https://github.com/Eyevinn/intercom-manager) ⭐ 65 | 🐛 16 | 🌐 TypeScript | 📅 2026-03-05 + [Intercom Frontend](https://github.com/Eyevinn/intercom-frontend) ⭐ 54 | 🐛 45 | 🌐 TypeScript | 📅 2026-03-05 - Intercom system based on built by Eyevinn for SVT.

## Companion Screens

* [pydvbcss](https://github.com/BBC/pydvbcss) ⭐ 31 | 🐛 3 | 🌐 Python | 📅 2018-07-16 - Implementation of the DVB Companion Screens and Streams protocols for synchronised media playback.
* [dvbcss-synctiming](https://github.com/BBC/dvbcss-synctiming) ⭐ 22 | 🐛 4 | 🌐 Python | 📅 2017-05-19 - A system for measuring how accurately a TV or companion are synchronised.
* [dvbcss-synckit-ios](https://github.com/bbc/dvbcss-synckit-ios) ⭐ 11 | 🐛 1 | 🌐 Objective-C | 📅 2017-11-22 - iOS libraries for companion screen applications that are synchronised frame-accurately to a TV.
* [dial-discovery-ios](https://github.com/bbc/dial-discovery-ios) ⭐ 3 | 🐛 1 | 🌐 Objective-C | 📅 2017-11-22 - A library for the discovery of devices via the DIAL protocol on the iOS platform.

## Connected TVs

* [HbbPlayer](https://github.com/Samsung/HbbPlayer) ⭐ 61 | 🐛 4 | 🌐 CSS | 📅 2018-06-26 - An HbbTV and W3C specifications compliant application that can playback media from a URL.
* [CPA Authorization Provider](https://github.com/ebu/cpa-auth-provider) - Reference implementation for linking media devices with online identities ([related repos](https://tech.ebu.ch/code) here).
* [TAL](http://bbc.github.io/tal/) - The TV Application Layer (TAL) is an open source library for building applications for Connected TV devices.

## Control Systems

* [Bitfocus Companion](https://github.com/bitfocus/companion) ⭐ 2,098 | 🐛 308 | 🌐 TypeScript | 📅 2026-03-08 - Enables the Elgato Streamdeck and other controllers to be a shotbox surface for an [increasing amount of broadcast equipment](https://bitfocus.io/connections).
* [MIDIMonster](https://github.com/cbdevnet/midimonster) ⭐ 580 | 🐛 49 | 🌐 C | 📅 2024-06-24 - Lightweight adapter tool for common show control protocols.
* [Lawo EmberPlus](https://github.com/Lawo/ember-plus) ⭐ 133 | 🐛 37 | 🌐 C++ | 📅 2025-10-22 - Ember Plus - open protocol for interfacing to / from broadcast control systems.
* [BUG](https://bbc.github.io/bug/) - Broadcast Universal Gateway - Control a wide range of broadcast and network equipment from your browser.

## Distributed Media Processing

* [StormCV](https://github.com/sensorstorm/StormCV) ⭐ 172 | 🐛 3 | 🌐 Java | 📅 2016-12-20 - Apache Storm + OpenCV = large scale distributed image and video analysis.

## Documentation

* [Kronekeeper](https://github.com/nick-prater/kronekeeper) ⭐ 14 | 🐛 20 | 🌐 Perl | 📅 2021-01-09 - A web based application for recording and managing Krone frame records.

## DVB & WiFi

* [Opencaster](https://github.com/aventuri/opencaster) ⭐ 73 | 🐛 16 | 🌐 C | 📅 2024-05-04 - A free and open source MPEG2 transport stream data generator and packet manipulator.
* [DTT 2 IP](https://github.com/ebu/dtt2ip) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2016-03-21 - Broadcast to IP conversion for Wifi indoor coverage.
* [dvbshout](https://github.com/njh/dvbshout) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2021-07-29 - Tool to send DVB audio to a shoutcast server or a RTP stream.
* [ts2mpa](https://github.com/njh/ts2mpa) ⭐ 5 | 🐛 4 | 🌐 C | 📅 2021-07-29 - Simple tool to extract MPEG Audio from a MPEG Transport Stream (TS).
* [DVB Inspector](https://sourceforge.net/projects/dvbinspector/) - An open-source DVB analyzer.
* [DVBlast](https://www.videolan.org/projects/dvblast.html) - A simple and powerful MPEG-2/TS demux and streaming application.
* [Project X](https://sourceforge.net/projects/project-x/) - DVB demux tool.
* [TSDuck](https://tsduck.github.io/) - Extensible toolkit for MPEG/DVB transport streams testing, monitoring, integration, debugging, and more.
* [WiFiBroadcast](https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/) - Analog-like transmission of live video data.

## Hybrid Radio

* [RadioVIS Demo](https://github.com/bbc/RadioVisDemo) ⭐ 28 | 🐛 4 | 🌐 Python | 📅 2025-05-08 - RadioVIS client application in Python.
* [RadioDNS Manager](https://github.com/ebu/radiodns-manager) ⚠️ Archived - Platform to manage Hybrid Radio services, e.g. RadioVIS, RadioEPG and Service Following.
* [RadioVIS Html Player](https://github.com/ebu/radiovis-html5player) ⭐ 14 | 🐛 2 | 🌐 JavaScript | 📅 2023-03-10 - RadioVIS Player using WebSocket.
* [RadioVIS Stomp Server](https://github.com/bbc/node-radiovis-stomp-server) ⭐ 12 | 🐛 6 | 🌐 JavaScript | 📅 2024-11-27 - RadioVIS STOMP server written in node.js.
* [RadioDNS for Node.js](https://github.com/bbc/node-radiodns) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2024-11-27 - Perform RadioDNS resolutions and service lookups in node.js.
* [RadioTag.js](https://github.com/ebu/radiotag.js) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2015-09-09 - RadioTag client library in JavaScript.

## LiveIP

*Audio/Video over IP & Streaming*

* [EBU LIST](https://github.com/ebu/pi-list) ⭐ 126 | 🐛 12 | 🌐 C++ | 📅 2026-03-03 - Live IP Software Toolkit to assist EBU members in the implementation of IP based facilities.
* [VideoIPath-Automation-Tool](https://github.com/SWR-MoIP/VideoIPath-Automation-Tool) ⭐ 11 | 🐛 7 | 🌐 Python | 📅 2026-03-02 - A Python package for automating VideoIPath configuration workflows.
* [IRIS Broadcast](https://github.com/IrisBroadcast/irisbroadcast.github.io/) ⭐ 10 | 🐛 0 | 📅 2021-03-08 - A project founded in Sweden to publish Open Source software for professional radio broadcasts.
* [butt](https://danielnoethen.de/) - broadcast using this tool (butt) is an easy to use, multi OS streaming tool. It supports SHOUTcast and Icecast.
* [Cool Mic](https://coolmic.net/) - Android audio livestreaming Icecast source client app.
* [DarkIce](http://www.darkice.org/) - Live audio streamer that records and encodes from an audio interface and sends to a streaming server.
* [Icecast](https://icecast.org/) - Streaming media (audio/video) server which supports Ogg (Vorbis and Theora), Opus, WebM and MP3.
* [Kamailio](http://www.kamailio.org/) - Open SIP server, commonly used for Audio contribution over IP using SIP (EBU ACIP).
* See the [NMOS](#nmos) list for the AMWA Networked Media Open Specifications and open source implementations and tools.
* [OpenOB](https://jamesharrison.github.io/openob/) - Open Outside Broadcast project for radio contribution links and studio-transmitter links based on Opus.
* [PJSIP](https://www.pjsip.org/) - Open Source multimedia library implementing SIP, SDP, RTP, STUN, TURN, and ICE.
* [trx](https://www.pogo.org.uk/~mark/trx/) - A simple toolset for broadcasting live audio from Linux.

## Media Players

* [Kodi](https://github.com/xbmc/xbmc) ⭐ 20,505 | 🐛 385 | 🌐 C++ | 📅 2026-03-08 - A software media player and entertainment hub for digital media.
* [rx-player](https://github.com/canalplus/rx-player) ⭐ 928 | 🐛 73 | 🌐 TypeScript | 📅 2026-03-06 - HTML5/Javascript video player that supports MPEG-DASH and SmoothStreaming.
* [Dash.js](https://github.com/ebu/dash.js) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2016-01-08 - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers.
* [Media4DPlayer](https://github.com/ebu/media4Dplayer) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2016-11-03 - HTML5 player focused on accessibility.
* [GPAC](https://gpac.io/) - Multimedia player, packager and tools.
* [IDJC](https://idjc.sourceforge.io/) - A GTK+ Shoutcast/Icecast client with two main media players.
* [MPD](https://www.musicpd.org/) - A flexible, powerful, server-side application for playing music.
* [mpg123](https://www.mpg123.de/) - A fast console MPEG Audio Player and decoder library.
* [Mixxx](https://mixxx.org/) - A free, open source DJ software.
* [Peaks.js](https://codeberg.org/chrisn/peaks.js) - Browser-based audio waveform visualisation.
* [VLC](https://www.vlc.org) - Simple, fast and powerful media player.

## Metadata

* [libklvanc](https://github.com/stoth68000/libklvanc) ⭐ 69 | 🐛 3 | 🌐 C | 📅 2025-11-26 - C library for ancillary data extraction from SDI and SMPTE ST 2110-40 (CEA-708, AFD, SCTE-104, etc.).
* [libadm](https://github.com/ebu/libadm) ⭐ 50 | 🐛 41 | 🌐 C++ | 📅 2025-12-04 - Audio Definition Model (ITU-R BS.2076) handling C++11 library.
* [BMXlib](https://github.com/ebu/bmx) ⭐ 33 | 🐛 4 | 🌐 C++ | 📅 2026-02-12 - Library and utilities to read and write broadcasting media files. Primarily supports the MXF file format.
* [EBUCore](https://github.com/ebu/ebucore) ⭐ 25 | 🐛 3 | 📅 2026-01-30 - The Github for maintenance of the [EBUCore schema](https://tech.ebu.ch/docs/tech/tech3293.pdf).
* [MAJ API](https://github.com/AMWA-TV/maj) ⭐ 19 | 🐛 14 | 🌐 HTML | 📅 2022-07-25 - Pure Java library for reading and writing MXF and AAF files.
* [SDPoker](https://github.com/AMWA-TV/sdpoker) ⭐ 19 | 🐛 28 | 🌐 JavaScript | 📅 2026-01-24 - CLI tool and library for testing SMPTE ST2110 SDP files.
* [TV-Anytime](https://github.com/ebu/tvanytime) ⭐ 16 | 🐛 3 | 📅 2020-08-29 - The TV-Anytime schema github maintenance page.
* [jebu-core](https://github.com/mikrosimage/jebu-core) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2018-06-13 - Java port of [EBU Tech 3293](https://tech.ebu.ch/publications/tech3293) EBU Core metadata, including the [Audio Definition Model](https://tech.ebu.ch/publications/tech3364).

## Monitoring & Quality Control

* [VMAF](https://github.com/Netflix/vmaf) ⭐ 5,281 | 🐛 101 | 🌐 Python | 📅 2026-03-02 - Perceptual video quality assessment based on multi-method fusion.
* [QCTools](https://github.com/bavc/qctools) ⭐ 360 | 🐛 80 | 🌐 C++ | 📅 2026-02-11 - Quality Control tools for video preservation to analyse digitized video files.
* [Photon](https://github.com/Netflix/photon) ⭐ 248 | 🐛 36 | 🌐 Java | 📅 2026-02-24 - Implementation of the SMPTE Interoperable Master Format (IMF) standard.
* [Pi Audio Monitor](https://github.com/martim01/pam) ⭐ 177 | 🐛 20 | 🌐 C++ | 📅 2026-02-25 - Audio Monitoring for Raspberry Pi, supports S/PDIF, AES3, AES67, Livewire and Ravenna.
* [BeaqleJS](https://github.com/HSU-ANT/beaqlejs) ⭐ 94 | 🐛 10 | 🌐 JavaScript | 📅 2019-03-09 - A framework to create browser based listening tests for subjective audio quality assessment.
* [LTC-tools](https://github.com/x42/ltc-tools) ⭐ 85 | 🐛 7 | 🌐 C | 📅 2023-10-24 - A collection of tools to handle Linear Timecode (LTC) and convert to MIDI Timecode (MTC).
* [Rotter](https://github.com/njh/rotter) ⭐ 55 | 🐛 13 | 🌐 C | 📅 2021-07-29 - Recording of Transmissions / Audio Logger for JACK.
* [MXF Inspect](https://github.com/Myriadbits/MXFInspect) ⭐ 50 | 🐛 2 | 🌐 C# | 📅 2026-02-11 - A Windows tool to display the internal structure of an MXF (Material eXchange Format) file.
* [Jack Meter](https://github.com/njh/jackmeter) ⭐ 46 | 🐛 3 | 🌐 C | 📅 2021-07-29 - Text console based DPM (Digital Peak Meter) for JACK.
* [silan](https://github.com/x42/silan) ⭐ 39 | 🐛 7 | 🌐 C | 📅 2018-05-13 -  Audiofile silence analyzer.
* [SilentJack](https://github.com/njh/silentjack) ⭐ 24 | 🐛 4 | 🌐 C | 📅 2024-06-28 - Dead-air / Silence detector for JACK.
* [Wisual](https://github.com/MarcAntoine-Arnaud/wisual) ⭐ 24 | 🐛 4 | 🌐 CSS | 📅 2015-06-01 - A web service for Visual Quality Assessment, which supports PSNR, SSIM, VQM, etc.
* [a\_Multiview](https://github.com/Bencosterton/a_MultiView) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-22 - A web based multiview for HLS and Youtube links.
* [Jmeters](http://kokkinizita.linuxaudio.org/linuxaudio/downloads/index.html) - A collection of graphical audio meters for JACK, including VU, PPM and [EBU R 128](https://tech.ebu.ch/publications/r128) Loudness meters.
* [MediaConch](https://mediaarea.net/MediaConch) - Implementation checker, policy checker, & reporter for Matroska, FFV1, & PCM.
* [MediaInfo](https://mediaarea.net/en/MediaInfo) - A convenient unified display of the most relevant technical and tag data for video and audio files.
* [Sonic Visualiser](https://www.sonicvisualiser.org/) - An application for viewing and analysing the contents of music audio files.

## Multimedia content processing

* [OBS-Studio](https://github.com/obsproject/obs-studio) ⭐ 70,801 | 🐛 1,065 | 🌐 C | 📅 2026-03-08 - Software for live streaming and screen recording.
* [Flowblade](https://github.com/jliljebl/flowblade) ⭐ 3,026 | 🐛 63 | 🌐 Python | 📅 2026-02-27 - A multitrack non-linear video editor.
* [MP4Box.js](https://github.com/gpac/mp4box.js) ⭐ 2,400 | 🐛 52 | 🌐 TypeScript | 📅 2026-03-06 - JavaScript library to process MP4 files in the browser (and in NodeJS).
* [Bento4](https://github.com/axiomatic-systems/Bento4) ⭐ 2,394 | 🐛 574 | 🌐 C++ | 📅 2026-01-30 - Full-featured MP4 format and MPEG DASH C++ class library and tools.
* [VideoContext](https://github.com/bbc/videocontext) ⭐ 1,354 | 🐛 39 | 🌐 JavaScript | 📅 2023-07-18 - Experimental HTML5/WebGL library for creating interactive and responsive web videos.
* [LibAV](https://github.com/libav/libav) ⭐ 1,146 | 🐛 9 | 🌐 C | 📅 2021-05-22 - Open source audio and video processing tools.
* [Brave](https://github.com/bbc/brave) ⭐ 687 | 🐛 24 | 🌐 Python | 📅 2023-09-01 - Basic Real-time AV Editor - lets you preview, mix, and route live audio and video streams on the cloud.
* [Voctomix](https://github.com/voc/voctomix) ⭐ 629 | 🐛 97 | 🌐 Python | 📅 2025-12-11 - Customizable conference recording/mixing/streaming software based on Python and GStreamer.
* [Libebur128](https://github.com/jiixyj/libebur128) ⭐ 470 | 🐛 38 | 🌐 C | 📅 2023-06-25 - A library that implements the EBU R 128 standard for loudness normalisation.
* [Beam Coder](https://github.com/Streampunk/beamcoder) ⭐ 417 | 🐛 63 | 🌐 C++ | 📅 2023-12-13 - Node.js native bindings to FFmpeg, with support for asynchronous processing via promises and streams.
* [SVT Encore](https://github.com/svt/encore) ⭐ 319 | 🐛 20 | 🌐 Kotlin | 📅 2025-10-21 - Selfhosted video transcoding platform, built around FFmpeg.
* [L-SMASH](https://github.com/l-smash/l-smash/) ⭐ 247 | 🐛 39 | 🌐 C | 📅 2024-05-06 - A rigidly spec-compliant ISOBMFF library, which has full DASH muxing support.
* [FFmbc](https://github.com/bcoudurier/FFmbc) ⭐ 200 | 🐛 2 | 🌐 C | 📅 2020-07-19 - FFmpeg customized for broadcast and professional usage.
* [TuttleOFX](https://github.com/tuttleofx/TuttleOFX) ⭐ 186 | 🐛 112 | 🌐 C++ | 📅 2020-08-13 - An open source image processing framework based on OpenFX plugin standard.
* [AvTranscoder](https://github.com/avTranscoder/avTranscoder) ⭐ 166 | 🐛 26 | 🌐 C++ | 📅 2023-09-22 - FFmpeg/LibAV-based high-level API to re-wrap or transcode media, with bindings for Java and Python.
* [rtmp](https://github.com/c-bata/rtmp) ⚠️ Archived - Server implementation of Adobe's RTMP 1.0 protocol in Go.
* [Codem-isoboxer](https://github.com/Dash-Industry-Forum/codem-isoboxer) ⭐ 119 | 🐛 5 | 🌐 JavaScript | 📅 2024-09-30 A small browser-based MPEG-4 (ISOBMFF) parser.
* [EBU ADM Renderer](https://github.com/ebu/ebu_adm_renderer) ⭐ 95 | 🐛 16 | 🌐 Python | 📅 2026-02-11 - Reference implementation of the EBU ADM Renderer ([EBU Tech 3388](https://tech.ebu.ch/publications/tech3388))
* [rgain3](https://github.com/chaudum/rgain3) ⭐ 57 | 🐛 17 | 🌐 Python | 📅 2023-07-21 - Tools and Python3 library to read, write and calculate Replay Gain - fork of the original by Felix Krull.
* [Dynamorse](https://github.com/Streampunk/node-red-contrib-dynamorse-core) ⭐ 48 | 🐛 2 | 🌐 JavaScript | 📅 2018-12-06 - IT swiss army knife - a Node-RED media pipeline builder, adding professional media processing nodes.
* [libbw64](https://github.com/ebu/libbw64) ⭐ 40 | 🐛 8 | 🌐 C++ | 📅 2024-04-13 – Header-only Broadcast Wave 64 (ITU-R BS.2088) C++11 library.
* [libear](https://github.com/ebu/libear) ⭐ 37 | 🐛 14 | 🌐 C++ | 📅 2024-04-10 - A C++11 library to render ADM content according to Recommendation ITU-R BS.2127.
* [Kelvinadon](https://github.com/Streampunk/kelvinadon) ⭐ 19 | 🐛 6 | 🌐 JavaScript | 📅 2022-04-08 - Node.JS pure Javascript module for streaming MXF files to and from JSON.
* [Loudness Validator](https://github.com/mikrosimage/loudness_validator) ⭐ 16 | 🐛 13 | 🌐 C++ | 📅 2022-06-09 - A set of applications to analyse, visualise and correct the loudness.
* [UPipe](https://github.com/cmassiot/upipe/) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2025-09-22 - Primarily designed to be the core of a multimedia player, transcoder or streamer.
* [FFmpeg](https://ffmpeg.org) - A cross-platform solution to record, convert and stream audio and video. Supports SMPTE ST 2110.
* [GStreamer](https://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components.
* [KFR](https://www.kfrlib.com/) - Fast, modern C++ DSP framework, DFT/FFT, Audio resampling, FIR/IIR, Biquad, EBU R 128.
* [MXFLib](https://sourceforge.net/projects/mxflib/) - A multi-platform C++ library for reading and writing MXF files.
* [Open Broadcast Encoder](https://github.com/ob-encoder) - Broadcast encoder built from Open Source components.
* [Snowmix](https://sourceforge.net/projects/snowmix/) - Live Video Mixer.
* [SoX](https://sourceforge.net/projects/sox/) - The Swiss Army knife of sound processing programs.

## Network & Storage Testing

* [Fio](https://github.com/axboe/fio) ⭐ 6,122 | 🐛 231 | 🌐 C | 📅 2026-03-04 - Flexible I/O Tester
* [SMPTE 2110-20 Analyzer](https://github.com/ebu/smpte2110-analyzer) ⭐ 87 | 🐛 3 | 🌐 Python | 📅 2020-05-01 - Analyzer to inspect network packets generated in accordance with SMPTE ST 2110.
* [Examples of SMPTE ST 2110 pcap files](https://github.com/NEOAdvancedTechnology/ST2110_pcap_zoo) ⭐ 24 | 🐛 2 | 📅 2022-08-17
* [Wireshark dissectors for Video Routers](https://github.com/roddypratt/router_dissectors) ⭐ 16 | 🐛 1 | 🌐 Lua | 📅 2025-12-02 - Analyzers for various video router/matrix protocols.
* [Wireshark dissector for TSL UMD protocol V3.1, V4](https://github.com/roddypratt/tslumd-wireshark) ⭐ 6 | 🐛 1 | 🌐 Lua | 📅 2022-01-14 - Analyzers for TSL UMD (under-monitor display) protocol V3.1 and V4.
* [BBC Media Storage Meter](https://sourceforge.net/projects/msmeter/) - An application for the testing of network attached  (professional media) storage.
* [iPerf3](https://iperf.fr/) - The TCP, UDP and SCTP network bandwidth measurement tool.

## NMOS

The [Networked Media Open Specifications](https://specs.amwa.tv/nmos/) are themselves open source.

* [nmos-cpp](https://github.com/sony/nmos-cpp) ⭐ 179 | 🐛 75 | 🌐 C++ | 📅 2026-03-05 - An implementation of the AMWA Networked Media Open Specifications in C++, including an NMOS Registry and a toolkit and example of building an NMOS Node.
* [Easy-NMOS](https://github.com/rhastie/easy-nmos) ⭐ 82 | 🐛 13 | 🌐 Shell | 📅 2023-01-31 - A starter kit that allows the user to launch a simple NMOS setup with minimal installation steps, composed of three Docker containers: an NMOS Registry, a virtual NMOS Node, and the AMWA NMOS Testing Tool.
* [nmos-js](https://github.com/sony/nmos-js) ⭐ 40 | 🐛 11 | 🌐 JavaScript | 📅 2026-03-05 - A simple browser-based NMOS Client/Controller with an IS-04 Registry browser and IS-05 Connection Management.
* [NVIDIA NMOS Library](https://github.com/NVIDIA/nvnmos) ⭐ 19 | 🐛 1 | 🌐 C++ | 📅 2025-07-30 (NvNmos) - A simple-to-use C/C++ library for adding an NMOS Node to your application, with support for IS-04, IS-05, BCP-002-01, BCP-002-02, BCP-004-01, etc.
* [BBC NMOS Joint Reference Implementation](https://github.com/bbc/nmos-joint-ri) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2019-11-22 - A Vagrant provisioning to build 4 virtual machines, an IS-04/IS-05 Node, IS-04 Registry, BCP-003-02 Authorisation Server, and the NMOS Testing Tool.
* [nmos-device-control-mock](https://github.com/AMWA-TV/nmos-device-control-mock) ⭐ 9 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-05 - A mock device implementation of the NMOS Control & Monitoring suite (IS-12, BCP-008-01, BCP-008-02), written in Typescript and running on the NodeJS stack.
* [DELTACAST IP Virtual Card NMOS samples](https://github.com/deltacasttv/nmos-ipvc-samples) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2024-10-02 - A demonstration of the integration of several NMOS standards with the DELTACAST IP Virtual Card through [nmos-cpp](https://github.com/sony/nmos-cpp) ⭐ 179 | 🐛 75 | 🌐 C++ | 📅 2026-03-05.
* [AMWA NMOS Testing Tool](https://specs.amwa.tv/nmos-testing/) - Automated test suites for the AMWA NMOS family of specifications, as used in the [JT-NM Tested](https://www.jt-nm.org/jt-nm-tested) programme
* [NVIDIA NMOS Docker](https://hub.docker.com/r/rhastie/nmos-cpp) - Docker container with Registry and Controller, IS-04/05/08/07/09, BCP-003-01

## Podcasting

* [AntennaPod](https://github.com/AntennaPod/AntennaPod) ⭐ 7,708 | 🐛 353 | 🌐 Java | 📅 2026-03-08 - A podcast manager for Android ([antennapod.org](https://antennapod.org/)).
* [Castopod](https://github.com/ad-aures/castopod) ⭐ 827 | 🐛 0 | 🌐 PHP | 📅 2026-03-01 - Podcast Hosting and Broadcasting ([castopod.org](https://castopod.org/)).
* [Anytime Podcast Player](https://github.com/amugofjava/anytime_podcast_player) ⭐ 587 | 🐛 29 | 🌐 Dart | 📅 2026-02-26 - Free and easy to use podcast player for Android and iOS ([anytimeplayer.app](https://anytimeplayer.app/)).
* [Podlove Publisher](https://github.com/podlove/podlove-publisher) ⭐ 304 | 🐛 188 | 🌐 PHP | 📅 2026-03-07 - Podcast Publisher for WordPress.
* [Podlove Web Player](https://github.com/podlove/podlove-ui) ⭐ 90 | 🐛 53 | 🌐 TypeScript | 📅 2026-01-30 - Podcast-optimized, HTML5-based video and audio player.
* [gPodder](https://gpodder.github.io/) - Media aggregator and podcast client.
* [Ultraschall](https://github.com/Ultraschall) - Suite of Plugins and UI tweaks to use with the DAW [Reaper](https://www.reaper.fm/) tailored towards Podcasters ([ultraschall.fm](https://ultraschall.fm/))

## Radio Production

* [AzuraCast](https://github.com/AzuraCast/AzuraCast) ⭐ 3,746 | 🐛 95 | 🌐 PHP | 📅 2026-03-08 - A self-hosted web radio management suite.
* [Liquidsoap](https://github.com/savonet/liquidsoap) ⭐ 1,626 | 🐛 296 | 🌐 OCaml | 📅 2026-03-08 - A Swiss army knife for multimedia streaming ([documentation](https://www.liquidsoap.info/doc.html)).
* [Airtime](https://github.com/sourcefabric/airtime) ⭐ 628 | 🐛 7 | 🌐 PHP | 📅 2021-07-14 - Radio management application for remote broadcast automation (via web-based schedule).
* [Rivendell](https://github.com/ElvishArtisan/rivendell) ⭐ 232 | 🐛 239 | 🌐 C++ | 📅 2026-03-06 - Complete radio broadcast automation solution, translated to many languages and used worldwide.
* [RAAR](https://github.com/radiorabe/raar) ⭐ 21 | 🐛 3 | 🌐 Ruby | 📅 2026-02-17 - A ruby application to manage and browse an audio archive.
* [Ardour](https://ardour.org/) - A digital audio workstation.
* [Audacity](https://www.audacityteam.org/) - Cross-platform software for recording and editing sounds.
* [LibreTime](https://libretime.org/) - Radio broadcast & automation platform (fork of Airtime).
* [OpenBroadcaster](https://www.openbroadcaster.com/) Open Source LPFM IPTV Broadcast Automation. [Server and Player code here](https://github.com/openbroadcaster).

## Rundown Automation

* [OnTime](https://github.com/cpvalente/ontime) ⭐ 851 | 🐛 34 | 🌐 TypeScript | 📅 2026-03-08 - Web based time keeping system for live events with a broadcast clock view.
* [SuperConductor](https://github.com/SuperFlyTV/SuperConductor) ⭐ 325 | 🐛 75 | 🌐 TypeScript | 📅 2025-09-23 - Rundown/playout controller for CasparCG Server, BMD ATEM, OBS Studio, vMix, OSC-compatible devices, HTTP (REST)-compatible devices among others.

## SCTE-35 & SCTE-104

* [threefive](https://github.com/superkabuki/threefive_is_scte35) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2026-03-09 - SCTE-35 Parser and Encoder for MPEGTS.
* [x9k3](https://github.com/superkabuki/x9k3) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2026-03-07 - Adaptive Bit Rate HLS Segmenter and SCTE-35 Injector.
* [wireshark-scte](https://github.com/m1tk4/wireshark-scte) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-01-14 - SCTE-104 protocol dissector for Wireshark.

## Software-defined radio

* [GNU Radio](https://www.gnuradio.org/) - A software development toolkit that provides signal processing blocks to implement software radios.
* [Gqrx SDR](https://www.gqrx.dk/) - An open source software defined radio receiver (SDR).
* [ODR-mmbTools](https://www.opendigitalradio.org) - Fork of CRC-mmbTools. Adds live, DAB+, associated data, distributed infrastructure, SFN.
* [rtl-sdr](https://osmocom.org/projects/rtl-sdr/wiki/rtl-sdr) - Turns a Realtek RTL2832 based DVB dongle into a SDR receiver.
* [welle.io](https://www.welle.io/) - An open source DAB and DAB+ software defined radio (SDR) with support for airspy and rtlsdr.

## Streaming

* [PeerTube](https://github.com/Chocobozzz/PeerTube) ⭐ 14,571 | 🐛 698 | 🌐 TypeScript | 📅 2026-03-05 - ActivityPub-federated video streaming platform using P2P directly in your web browser. (<https://joinpeertube.org/>)
* [Owncast](https://github.com/owncast/owncast) ⭐ 10,998 | 🐛 188 | 🌐 Go | 📅 2026-03-09 - Selfhosted video streaming platform (<https://owncast.online/>)

## Subtitling

* [ttconv](https://github.com/sandflow/ttconv) ⭐ 226 | 🐛 32 | 🌐 Python | 📅 2026-03-08 - Subtitle conversion library and CLI tool. Converts between STL, SRT, TTML, SCC, TTML and WebVTT files.
* [imscJS](https://github.com/sandflow/imscJS) ⭐ 89 | 🐛 26 | 🌐 JavaScript | 📅 2026-03-02 - JavaScript library for rendering IMSC1 Text and Image Profile documents to HTML5.
* [Timed Text Toolkit (ttt)](https://github.com/skynav/ttt) ⭐ 80 | 🐛 92 | 🌐 Java | 📅 2022-11-22 - Tools that support/use the W3C Timed Text Markup Language (TTML).
* [Subtitling Conversion Framework (SCF)](https://github.com/Irt-Open-Source/scf) ⭐ 58 | 🐛 12 | 🌐 XSLT | 📅 2020-11-16 - Modules for converting subtitle formats, incl. EBU STL and EBU-TT files.
* [EBU-TT Live Interoperability Toolkit](https://github.com/ebu/ebu-tt-live-toolkit) ⭐ 27 | 🐛 104 | 🌐 Python | 📅 2023-10-11 - Components for generating, testing and distributing [EBU-TT Live](https://tech.ebu.ch/publications/tech3370) subtitles.
* [GStreamer TTML subtitling package](https://github.com/BBC-archive/gst-ttml-subtitles) ⚠️ Archived - A means for GStreamer pipelines to parse and render EBU-TT-D (TTML) subtitles.
* [IRT EBU-TT-D Application Samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples) ⭐ 13 | 🐛 0 | 📅 2017-02-28 - EBU-TT-D sample files, PNG images and mp4 videos as rendering references.
* [EBU-TT-D Subtitling within dash.js](https://github.com/ebu/dash.js/tree/ebu-subtitling-dev) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2016-01-08 - dash.js fork with EBU-TT-D subtitles in HTML/CSS overlay. Later added to [dash.js](https://github.com/ebu/dash.js) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2016-01-08.
* [EBU-TT-D W3C XML Schema](https://github.com/ebu/ebu-tt-d-xsd/) ⭐ 9 | 🐛 4 | 📅 2021-07-13 - Informative EBU-TT-D XML Schema to support the implementation of EBU Tech 3380.
* [CCExtractor](https://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.
* [Subtitle Edit](https://www.nikse.dk/SubtitleEdit) - An editor for subtitles.

## Video Production

* [MOS-connection](https://github.com/Sofie-Automation/sofie-mos-connection) ⭐ 25 | 🐛 5 | 🌐 TypeScript | 📅 2026-03-02 - A JavaScript library for connection and MOS messaging either as MOS device or NRCS.
* [AutoMix](https://github.com/InsanityRadio/automix/) ⭐ 9 | 🐛 1 | 🌐 HTML | 📅 2017-12-24 - Web-based control surface for ATEM vision mixers with automated camera switching, designed for visualised radio.
* [vMix-EmberPlus](https://github.com/mattlamb99/vMix-EmberPlus) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-12 - vMix to EmberPlus gateway. Control vMix from any EmberPlus broadcast controller like Lawo's VSM or EVS's Cerebrum.
* [Open Lighting Architecture (OLA)](https://www.openlighting.org/ola/) - Travel adaptor for the lighting industry, for interconnecting DMX-512, IP and USB.
* [Q Light Controller+ (QLC+)](https://www.qlcplus.org/) - Cross-platform control of DMX or analogue lighting systems (heads, dimmers, etc.).
* [QPrompt Teleprompter App](https://qprompt.app) - Convergent teleprompter software that works with studio teleprompters, tablet teleprompters, webcams, and phones.
* [TallyArbiter](https://tallyarbiter.com/) - Cross-platform Tally interfacer & tally lights for any camera via phones or low-cost hardware.

# Resources

Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [BBC News Labs](https://github.com/BBC-News-Labs) - Open Source projects from BBC News Labs.
* [BBC R\&D](https://www.bbc.co.uk/rd) - BBC Research and Development. Checkout the weekly notes.
* [3D CineCast](http://3dcinecast.blogspot.com/) - A curation about new media technologies.
* [Canal+](https://developers.canal-plus.com/) - CANAL+ Open Source Community.
* [IRT Lab](https://web.archive.org/web/20210830075332/https://lab.irt.de/) - IRT blog posting developments and demos for all digital audiovisual media technology.
* [The Netflix Tech Blog](https://netflixtechblog.com/) - A Netflix blog focused on technology and technology issues.

## Websites

# Contributing

Please see [CONTRIBUTING](https://github.com/ebu/awesome-broadcasting/blob/master/CONTRIBUTING.md) ⭐ 1,683 | 🐛 2 | 📅 2026-03-08 for details.
