MuseScore内置的[node:278660,title="合成器"]中提供的音频回放，其中收录了大量包含打击乐器以及声音效果的 __虚拟乐器__ 。

MuseScore支持以下两种格式的虚拟乐器：

* [SoundFont](#soundfonts) (.sf2/.sf3)：包含一个或多个乐器的单个文件。
* [SFZ](#sfz) (.sfz)：包含一个或多个乐器的一整套音频及定义文件。

### 音色 {#soundfonts}

MuseScore自带GM音色（[General MIDI](http://en.wikipedia.org/wiki/General_MIDI)）和 __MuseScore_General.sf3__ 音色包——囊括了超过128种乐器、音效及不同的鼓/打击乐器套件。

GM (General MIDI) 是一个通用格式，一旦您的乐谱正确配置并使用MuseScore的自带音色，您应该可以将其以特定的[node:278612, title="格式"][node:278643,fragment="export",title="导出"]并在他人计算机上播放。

互联网上有许多不同的音色可用：有免费版，也有收费版。下文列出[免费音色列表](#list).。

#### 加载一个音色 {#install}

找到并解压一个[音色](#list)之后，请双击打开。绝大多数情况下，音色文件类型已经与MuseScore关联，此时 MuseScore将启动，之后弹出一个对话框，询问您是否要加载音色。偶尔有别的软件会把音色文件类型关联，倘若是这种情况，您就需要右击（Mac：control+单击）文件，在菜单中的打开方式中进行设置来使文件在MuseScore中打开。不管遇到上述哪种情况，当对话框询问您是否要加载音色，请单击"是"以将音色文件的 _副本_ 加载到的音色目录下。这个目录的路径可在MuseScore的偏好设置中查看或更改。默认路径为：

- Windows: `%HOMEPATH%\Documents\MuseScore3\Soundfonts`

- macOS与Linux: `~/Documents/MuseScore3/Soundfonts`

与用户所添加的音色文件不同的是，MuseScore自带的音色文件位于系统目录，仅可置于此，_不得更改_。音色文件的默认目录为：

- Windows (32位): `%ProgramFiles%\MuseScore 3\sound\MuseScore_General.sf3` 
- Windows (64位): `%ProgramFiles(x86)%\MuseScore 3\sound\MuseScore_General.sf3`

- macOS: `/Applications/MuseScore 3.app/Contents/Resources/sound/MuseScore_General.sf3`

- Linux (Ubuntu): `/usr/share/mscore-xxx/sounds/MuseScore_General.sf3`（当中的`xxx`是MuseScore的版本）

#### 卸载 {#uninstall}

要卸载音色，只需打开音色的安装文件夹，并将其删除。

### SFZ  {#sfz}

SFZ是WAV或FLAC格式的文件和目录、SFZ文件和一堆实际声音文件的集合。其中SFZ文件是一个文本文件，基本描述了相关音色样本文件的位置以及用于什么乐器和音高范围。

#### 装载SFZ {#install-sfz}

在下载一个SFZ文件之后(见[下文](#list))，您需要手动解压属于SFZ的所有文件 （包括SFZ文件本身及所有子目录）并放入[上文](#install)列出来的目录。请保持子目录及其内容的原样。

#### 卸载 {#uninstall-sfz}

要卸载SFZ，只需打开[音色的安装文件夹](#install)，并将其悉数删除。

### 合成器 {#synthesizer}

__合成器__ 是MuseScore音频输出的中控台。只要音色被[装载](#install)，就需要加载入合成器以使MuseScore播放。要默认设置不同的音色，在合成器中加载并单击<kbd><samp class="button">设为默认</samp></kbd>。

要显示合成器，请前往<samp class="menu">视图</samp> &rarr; <samp class="menuitem">合成器</samp>。欲知详情，请参阅[node:278660,title="合成器"]。

[inline:Synthesizer_zh-hans.png=Synthesizer] 
 
### 可下载的音色列表 {#list}

#### GM 音色 {#gm_soundfonts}

下列音色库使用了General MIDI (GM2) 标准。该规格使您拥有一套128种虚拟乐器，外加打击乐器组合。

- [GeneralUser GS](http://schristiancollins.com/soundfonts/GeneralUser_GS_1.442-MuseScore.zip)（29.8 MB ，未经压缩）
  蒙[S. Christian Collins](http://schristiancollins.com/generaluser.php)之允。
- [Magic Sound Font，2.0版](http://www.personalcopy.com/sfarkfonts1.htm)（67.8 MB，未经压缩）
- [Arachno SoundFont，1.0版](http://www.arachnosoft.com/main/download.php?id=soundfont-sf2)（148MB，未经压缩）
  蒙[Maxime Abbey](http://www.arachnosoft.com)之允。
- MuseScore 1附带[TimGM6mb](http://sourceforge.net/p/mscore/code/HEAD/tree/trunk/mscore/share/sound/TimGM6mb.sf2?format=raw)（5.7 MB，未经压缩）
  许可：GNU GPL第二版
  蒙[Tim Brechbill](http://ocmnet.com/saxguru/Timidity.htm#sf2)之允。
- MuseScore 2（最高版本2.1）附带[`FluidR3Mono_GM.sf3`](https://github.com/musescore/MuseScore/raw/2.1/share/sound/FluidR3Mono_GM.sf3) (13.8 MB).
- MuseScore 2（截至2.2版）和3附带[`MuseScore_General.sf3`](ftp://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General.sf3) (35.9 MB) ([SF2版本](ftp://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General.sf2) (208 MB)).
  许可：依照[MIT许可]发布。(https://github.com/musescore/MuseScore/blob/master/share/sound/FluidR3Mono_License.md)
  蒙[S. Christian Collins](/user/62809)之允。
- [Timbres of Heaven, version 3.2](http://midkar.com/soundfonts/)（369 MB，未经压缩）
  蒙Don Allen之允。

#### 管弦乐团音色 {#orchestral-soundfiles}

- Sonatina Symphonic Orchestra（503MB，未经压缩）  
  下载地址：[SoundFont](http://ftp.osuosl.org/pub/musescore/soundfont/Sonatina_Symphonic_Orchestra_SF2.zip) | [SFZ format](http://sso.mattiaswestlund.net)  
  许可：Creative Commons Sampling Plus 1.0
- [Aegean Symphonic Orchestra](https://sites.google.com/view/hed-sounds/aegean-symphonic-orchestra)
  蒙[Ziya Mete Demircan](/user/230181)（352 MB ，未经压缩）之允。

#### 钢琴音色 {#specialised}

##### SF2钢琴音色 {#sf2_piano}

- [Acoustic三角钢琴，发布于2016-08-04](http://freepats.zenvoid.org/Piano/YDP-GrandPiano/grand-piano-YDP-20160804.tar.bz2)
  详情：Yamaha Disklavier Pro三角钢琴、sf2格式、压缩后36MiB、解压后113MiB、121个采样、5力度层
  详情见：[http://freepats.zenvoid.org/](http://freepats.zenvoid.org/) 包含其他音色。
  许可：知识共享署名3.0
  蒙[Roberto Gordo Saez](http://freepats.zenvoid.org/sf2/acoustic_grand_piano_ydp_20080910.txt)之允
- [Salamander C5 Light](https://sites.google.com/view/hed-sounds/salamander-c5-light)
  蒙[Ziya Mete Demircan](/user/230181)之允（24.5 MB，未经压缩）

##### SFZ钢琴音色 {#sf2_piano}

- Salamander三角钢琴
  下载地址：[第二版](http://download.linuxaudio.org/lau/SalamanderGrandPianoV2/) | [第三版](http://freepats.zenvoid.org/Piano/acoustic-grand-piano.html)  
  详情：Yamaha C5、48kHz、24bit、16力度层、80 MB ～ 1.9 GB （未经压缩）
  许可：知识共享署名3.0
  蒙Alexander Holm之允
- [Detuned Piano](http://download.linuxaudio.org/musical-instrument-libraries/sfz/detuned_piano.tar.7z)（未压缩时244 MB）
  许可：Creative Commons Attribution-ShareAlike 3.0
- [Plucked Piano Strings](http://download.linuxaudio.org/musical-instrument-libraries/sfz/plucked_piano_strings.tar.7z)
  详情：44.1kHz、16bit、双声道、168MB、未经压缩
  许可：Creative Commons Attribution-ShareAlike 3.0
- [The City Piano](http://bigcatinstruments.blogspot.ca/2015/09/all-keyboard-instruments.html)
  详情：Baldwin Baby Grand、4力度层，696MB，未经压缩
  许可：公共领域
  蒙Big Cat Instruments之允
- [Kawai立式钢琴，发布于2017-01-28](http://freepats.zenvoid.org/Piano/acoustic-grand-piano.html#KawaiUpright)
  详情：68个样本、44KHz、24bit、双声道、2力度层、58MiB、未经压缩
  许可：GNU通用公开许可第三版或更新版，附带一个[特殊例外](http://freepats.zenvoid.org/licenses.html#GPL_exception)
  蒙Gonzalo and Roberto之允

#### 解压下载的音色 {#compressed-file-formats}

由于音色文件较大，他们通常都是一些压缩文件的格式，包括.zip、.sfArk、以及.ta您需要在使用前解压这些文件。

- ZIP是一种受大多数操作系统支持的压缩文件格式。

- sfArk是一种压缩格式，专为压缩SoundFont文件而设计。要解压缩它，请使用跨平台软件[Polyphone](https://www.polyphone-soundfonts.com/)或此在线服务：https://cloudconvert.com/sfark-to-sf2

- .tar.gz是Linux上普遍使用的压缩文件格式。Windows用户可使用[7-Zip](http://www.7-zip.org); Mac用户可使用 [The Unarchiver](http://unarchiver.c3.cx/unarchiver)或macOS内置的_归档实用工具_。请注意，若您使用7-Zip，您将解压两次——一次解压GZip，一次解压TAR。

### 疑难杂症 {#troubleshooting}

若工具栏的播放面板为灰色，或者不见了，请按照下列指令来恢复声音的播放：

1. 右键单击菜单栏，并确保<samp class="menuitem">播放设置</samp>菜单项旁有一个勾号。若本步骤无法解决您的问题，请前往第2步。
2. 若在更改音色后，播放面板消失，请前往<samp class="menu">编辑</samp> &rarr; <samp class="menuitem">偏好设置...</samp> &rarr; <samp class="tab">I/O</samp>标签页，然后不要做任何改动，直接点OK。 重启MuseScore后，播放面板应该会重新出现。

若您是首次配置音色库，请使用以上列出的任意一个SoundFont。

若播放卡顿，那么您的电脑可能无法很好的处理所使用的音色库。下列建议可能对您有裨益：
* 通过使用体积更小的音色库来减少MuseScore对运存的使用量。见上方的[列表](#list)。
* 退出除了MuseScore之外的应用程序，以为MuseScore增加可用的运存数量。若依旧存在问题同时又有必要使用大型音色库，请考虑为您的计算机添加更多RAM内存。

### 参阅 {#see-also}

- [node:278660,title="合成器"]
- [node:278583,title="混音器"]

### 外链 {#external-links}

- [node:50721,title="如何更改或添加音色"]
- [SFZ格式](http://www.sfzformat.com/legacy/)（有关sfz规范的详细信息）
