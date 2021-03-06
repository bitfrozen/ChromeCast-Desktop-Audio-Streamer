# Desktop Audio Streamer

This tool captures the audio from your desktop and streams it to a ChromeCast Audio device.

You can download an installer from the [releases](https://github.com/SamDel/ChromeCast-Desktop-Audio-Streamer/releases).
After running setup.exe you can run the installed program from `C:\Program Files (x86)\Desktop Audio Streamer\Desktop Audio Streamer\ChromeCast.Desktop.AudioStreamer.exe`.
- On the first run Windows will ask you to configure the firewall and this must be enabled for your home-network type (public or private) for audio to play.
- If the application doesn't find your devices please read [troubleshooting](https://github.com/SamDel/ChromeCast-Desktop-Audio-Streamer/wiki#troubleshooting).

Please read the [wiki](https://github.com/SamDel/ChromeCast-Desktop-Audio-Streamer/wiki) page for further information, and the [developers](https://github.com/SamDel/ChromeCast-Desktop-Audio-Streamer/wiki/Developers) page to get it to work in Visual Studio.



# Dependencies

- [NAudio](https://github.com/naudio/NAudio)
- [NAudio.Lame](https://github.com/Corey-M/NAudio.Lame)
- [CSCore](https://github.com/filoe/cscore)
- [Protocol Buffers](https://github.com/google/protobuf)
- [Tmds.MDns](https://github.com/tmds/Tmds.MDns)
- [protobuf-csharp-port](https://github.com/jskeet/protobuf-csharp-port)
- [Microsoft Visual Studio Installer Projects (Visual Studio 2017, 2019)](https://marketplace.visualstudio.com/items?itemName=VisualStudioClient.MicrosoftVisualStudio2017InstallerProjects)
- [Multilingual App Toolkit v4.0 (VS 2017)](https://marketplace.visualstudio.com/items?itemName=MultilingualAppToolkit.MultilingualAppToolkit-18308)

# Learned from

- [Google Home Local Api](https://github.com/rithvikvibhu/GHLocalApi)
- [node-castv2](https://github.com/thibauts/node-castv2)
- [node-castv2-client](https://github.com/thibauts/node-castv2-client)
- [chromecast-audio-stream](https://github.com/acidhax/chromecast-audio-stream)

It's inspired by [acidhax/chromecast-audio-stream](https://github.com/acidhax/chromecast-audio-stream), and has basically the same functionality.
