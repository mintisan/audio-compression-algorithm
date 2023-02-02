# audio-compression-algorithm

- [A comparison of Internet audio compression formats](https://sericyb.com.au/audio.html)
- [Audio Formats Comparison](https://stsaz.github.io/fmedia/audio-formats/)
- [CODEC Considerations](https://www.embedded.com/codec-considerations/)
- [Lossless comparison](https://wiki.hydrogenaud.io/index.php?title=Lossless_comparison)
- [Comparative Analysis of Modern Formats of Lossy Audio Compression](https://ceur-ws.org/Vol-2654/paper25.pdf)
- [Lossy audio formats comparison](https://www.bobulous.org.uk/misc/lossy_audio_2006.html)
- [19种音频格式介绍及音质压缩比的比较](https://blog.csdn.net/nimeghbia/article/details/79084063)
- [有損音訊壓縮格式大比拼─MP3、Ogg、AAC、HE-AAC、HE-AACv2、Opus究竟誰才是王者？](https://magiclen.org/acoustics)

## ST 

- [STSW-STM32022](https://www.st.com/en/embedded-software/stsw-stm32022.html) : The ADPCM algorithm in STM32F1xx and STM32L1xx microcontrollers【ADPCM】
- [STM32-AUDIO100A](https://www.st.com/en/embedded-software/stm32-audio100a.html) : STM32 Audio processing SW library【】
- [X-CUBE-AUDIO](https://www.st.com/en/embedded-software/x-cube-audio.html) : Audio effects software expansion for STM32Cube【MP3】
- [X-CUBE-OPUS](https://www.st.com/en/embedded-software/x-cube-opus.html) : Opus evaluation and profiling software expansion for STM32Cube【Opus】
- [FP-AUD-SMARTMIC1](https://www.st.com/content/st_com/en/products/embedded-software/mcu-mpu-embedded-software/stm32-embedded-software/stm32-ode-function-pack-sw/fp-aud-smartmic1.html) : STM32Cube function pack for MEMS microphone acquisition, advanced audio processing and audio output
- [FP-AUD-BVLINKWB1](https://www.st.com/en/embedded-software/fp-aud-bvlinkwb1.html) : STM32Cube function pack for STM32WB MCU featuring full-duplex audio streaming over Bluetooth 5.0 using Opus codec【Opus】


## ADPCM : 

- ratio
- computation time
- ROM/RAM
- https://devzone.nordicsemi.com/cfs-file/__key/communityserver-discussions-components-files/4/nRF-ready-Smart-Remote-3-for-nRF52-Series-software-files.zip
- [The ADPCM algorithm in STM32F1xx and STM32L1xx microcontrollers](https://www.st.com/en/embedded-software/stsw-stm32022.html)


### Tutorial

- [Dialogic ADPCM Algorithm](http://www.mp3-tech.org/programmer/docs/adpcm.pdf)
- [IMA-ADPCM 算法 by 云风](https://www.codingnow.com/text/adpcm.htm)
- [Continuously Variable Slope Delta Modulation : A Tutorial](https://www.raffia.ch/content/datasheets/volume01/Tutorial_DeltaMod_CVSD_MxCom.pdf)
- [Encoders and Decoders by elprocus](https://www.elprocus.com/encoders-and-decoders/)
- [Pulse Code Modulation and Demodulation by elprocus](https://www.elprocus.com/pulse-code-modulation-and-demodulation/)
- [Differential Pulse Code Modulation Working and Application by elprocus](https://www.elprocus.com/differential-pulse-code-modulation-working-application/)
- [Adaptive Differential Pulse Code Modulation – ADPCM by elprocus](https://www.elprocus.com/adaptive-differential-pulse-code-modulation-adpcm/)
- [G.726 Adaptive Differential Pulse Code Modulation(ADPCM) on the TMS320C54x DSP](https://www.ti.com/lit/an/spra118/spra118.pdf)
- [Adaptive Differential Pulse Code Modulation using PICmicro™ Microcontrollers](https://ww1.microchip.com/downloads/en/AppNotes/00643b.pdf)

## OPUS : https://opus-codec.org/

> Opus是一个有损音频压缩的数字音频编码格式，由Xiph.Org基金会开发，之后由互联网工程任务组进行标准化，目标是希望用单一格式包含声音和语音，取代Speex和Vorbis，且适用于网络上低延迟的即时声音传输，标准格式定义于RFC 6716文件。Opus格式是一个开放格式，使用上没有任何专利或限制。
Opus集成了两种声音编码的技术：以语音编码为导向的SILK和低延迟的CELT。Opus可以无缝调节高低比特率。在编码器内部它在较低比特率时使用线性预测编码在高比特率时候使用变换编码。Opus具有非常低的算法延迟，非常适合用于低延迟语音通话的编码，像是网络上的即时声音流、即时同步声音旁白等等，此外Opus也可以透过降低编码比特率，达成更低的算法延迟，最低可以到5 ms。在多个听觉盲测中，Opus都比MP3、AAC、HE-AAC等常见格式，有更低的延迟和更好的声音压缩率。
https://artsandculture.google.com/entity/m0gvvjrm?hl=zh

- ratio
- computation time
- ROM/RAM
- code : https://www.st.com/en/evaluation-tools/stm32-nucleo-expansion-boards.html
- https://devzone.nordicsemi.com/cfs-file/__key/communityserver-discussions-components-files/4/nRF-ready-Smart-Remote-3-for-nRF52-Series-software-files.zip
- [Opus 音频编码格式](https://chenliang.org/2020/03/15/opus-format/)

## Vorbis : https://xiph.org/vorbis/

- [xiph/vorbis](https://github.com/xiph/vorbis)
- [Ogg Vorbis decoding with STM32F103RE works!](https://community.st.com/s/question/0D50X00009Xki7bSAB/ogg-vorbis-decoding-with-stm32f103re-works)

## [FLAC](https://xiph.org/flac/)

## [Low Complexity Communication Codec](https://www.bluetooth.org/DocMan/handlers/DownloadDoc.ashx?doc_id=502107&vId=542963)
- [google/liblc3](https://github.com/google/liblc3)
- [zephyrproject-rtos/liblc3codec](https://github.com/zephyrproject-rtos/liblc3codec)

## MP3

## Other

- [Simple Lossless Audio Compressor](https://github.com/dbry/slac)
- [WavPack](https://www.wavpack.com/index.html) : WavPack is a completely open audio compression format providing lossless, high-quality lossy, and a unique hybrid compression mode. 
- [Quite OK Audio Format](https://github.com/phoboslab/qoa)
  - [Time Domain Audio Compression at 3.2 bits per Sample](https://phoboslab.org/log/2023/02/qoa-time-domain-audio-compression)
