# 音频编码标准

[原文地址](http://www.52im.net/thread-243-1-1.html)

目前传统视频通讯过程中主要采用的是**G.711、G.722、G.721、G.728**等音频标准，音频宽度仅有**50Hz－7KHz**单声道，而人耳所能感知的自然界的频响能力可以达到**20Hz－20KHz。**

### 实时音频通讯编码标准：G.711 <a id="4"></a>

  
类型：Audio  
制定者：ITU-T  
所需频宽：64Kbps  
特性：算法复杂度小，音质一般  
优点：算法复杂度低，压缩比小（CD音质&gt;400kbps），编解码延时最短（相对其它技术）  
缺点：占用的带宽较高  
备注：70年代CCITT公布的G.711 64kb/s脉冲编码调制PCM。  


### 实时音频通讯编码标准：G.721 <a id="5"></a>

  
制定者：ITU-T  
所需带宽：32Kbps  
音频频宽：3.4KHZ  
特性：相对于PCMA和PCMU，其压缩比较高，可以提供2：1的压缩比。  
优点：压缩比大  
缺点：声音质量一般  
备注：子带ADPCM（SB-ADPCM）技术。G.721标准是一个代码转换系统。它使用ADPCM转换技术，实现64 kb/s A律或μ律PCM速率和32 kb/s速率之间的相互转换。  


### 实时音频通讯编码标准：G.722 <a id="6"></a>

  
制定者：ITU-T  
所需带宽：64Kbps  
音频宽度：7KHZ  
特性：G722能提供高保真的语音质量  
优点：音质好  
缺点：带宽要求高  
备注：子带ADPCM（SB-ADPCM）技术  


### 实时音频通讯编码标准：G.722.1 <a id="7"></a>

  
制定者：ITU-T  
所需带宽：32Kbps/24Kbps  
音频宽度：7KHZ  
特性：可实现比G.722 编解码器更低的比特率以及更大的压缩。目标是以大约一半的比特率实现  G.722 大致相当的质量。  
优点：音质好  
缺点：带宽要求高  
备注：目前大多用于电视会议系统。  


### 实时音频通讯编码标准：G.721附录C <a id="8"></a>

  
制定者：ITU-T  
所需带宽：48Kbps/32Kbps/4Kbps  
音频宽度：14KHZ  
特性：采用自Polycom 的Siren™14 专利算法，与早先的宽频带音频技术相比具有突破性的优势，提供了低时延的14 kHz 超宽频带音频，而码率不到MPEG4 AAC-LD 替代编解码器的一半，同时要求的运算能力仅为十分之一到二十分之一，这样就留出了更多的处理器周期来提高视频质量或者运行因特网应用程序，并且移动设备上的电池续航时间也可延长。  
优点：音质更为清晰，几乎可与CD 音质媲美，在视频会议等应用中可以降低听者的疲劳程度。  
缺点：是Polycom的专利技术。  
备注：目前大多用于电视会议系统  


### 实时音频通讯编码标准：G.723\(低码率语音编码算法\) <a id="9"></a>

  
制定者：ITU-T  
所需带宽：5.3Kbps/6.3Kbps  
音频宽度：3.4KHZ  
特性：语音质量接近良，带宽要求低，高效实现，便于多路扩展，可利用C5402片内16kRAM实现53coder。达到ITU-TG723要求的语音质量，性能稳定。可用于IP电话语音信源编码或高效语音压缩存储。  
优点：码率低，带宽要求较小。并达到ITU-TG723要求的语音质量，性能稳定。  
缺点：声音质量一般  
备注：G.723语音编码器是一种用于多媒体通信，编码速率为5.3kbits/s和6.3kbit/s的双码率编码方案。G.723标准是国际电信联盟（ITU）制定的多媒体通信标准中的一个组成部分，可以应用于IP电话等系统中。其中，5.3kbits/s码率编码器采用多脉冲最大似然量化技术（MP－MLQ），6.3kbits/s码率编码器采用代数码激励线性预测技术。  


### 实时音频通讯编码标准：G.723.1\(双速率语音编码算法\) <a id="10"></a>

  
制定者：ITU-T  
所需带宽：5.3Kbps\(29\)  
音频宽度：3.4KHZ  
特性：能够对音乐和其他音频信号进行压缩和解压缩，但它对语音信号来说是最优的。G.723.1采用了执行不连续传输的静音压缩，这就意味着在静音期间的比特流中加入了人为的噪声。除了预留带宽之外，这种技术使发信机的调制解调器保持连续工作，并且避免了载波信号的时通时断。  
优点：码率低，带宽要求较小。并达到ITU-TG723要求的语音质量，性能稳定,避免了载波信号的时通时断。  
缺点：语音质量一般  
备注：G.723.1算法是ITU-T建议的应用于低速率多媒体服务中语音或其它音频信号的压缩算法，其目标应用系统包括H.323、H.324等多媒体通信系统 。目前该算法已成为IP电话系统中的必选算法之一。  


### 实时音频通讯编码标准：G.728 <a id="11"></a>

  
制定者：ITU-T  
所需带宽：16Kbps/8Kbps  
音频宽度：3.4KHZ  
特性：用于IP电话、卫星通信、语音存储等多个领域。G.728是一种低时延编码器，但它比其它的编码器都复杂，这是因为在编码器中必须重复做50阶LPC分析。G.728还采用了自适应后置滤波器来提高其性能。  
优点：后向自适应，采用自适应后置滤波器来提高其性能  
缺点：比其它的编码器都复杂  
备注：G.728 16kb/s短延时码本激励线性预测编码（LD-CELP）。1996年ITU公布了G.728 8kb/s的CS－ACELP算法，可以用于IP电话、卫星通信、语音存储等多个领域。16 kbps G.728低时延码激励线性预测。  
  
G.728是低比特线性预测合成分析编码器（G.729和G.723.1）和后向ADPCM编码器的混合体。G.728是LD-CELP编码器，它一次只处理5个样点。对于低速率（56~128 kbps）的综合业务数字网（ISDN）可视电话，G.728是一种建议采用的语音编码器。由于其后向自适应特性，因此G.728是一种低时延编码器，但它比其它的编码器都复杂，这是因为在编码器中必须重复做50阶LPC分析。G.728还采用了自适应后置滤波器来提高其性能。  


### 实时音频通讯编码标准：G.729 <a id="12"></a>

  
制定者：ITU-T  
所需带宽：8Kbps  
音频宽度：3.4KHZ  
特性：在良好的信道条件下要达到长话质量，在有随机比特误码、发生帧丢失和多次转接等情况下要有很好的稳健性等。这种语音压缩算法可以应用在很广泛的领域中，包括ＩＰ电话、无线通信、数字卫星系统和数字专用线路。  
  
G.729算法采用“共轭结构代数码本激励线性预测编码方案”（CS-ACELP）算法。这种算法综合了波形编码和参数编码的优点，以自适应预测编码技术为基础，采用了矢量量化、合成分析和感觉加权等技术。  
  
G.729编码器是为低时延应用设计的，它的帧长只有10ms，处理时延也是10ms，再加上5ms的前视，这就使得G.729产生的点到点的时延为25ms，比特率为8 kbps。  
优点：语音质量良，应用领域很广泛，采用了矢量量化、合成分析和感觉加权，提供了对帧丢失和分组丢失的隐藏处理机制。  
缺点：在处理随机比特错误方面性能不好。  
备注：国际电信联盟（ITU-T）于1995年11月正式通过了G.729。ITU-T建议G.729也被称作“共轭结构代数码本激励线性预测编码方案”\(CS-ACELP\)，它是当前较新的一种语音压缩标准。G.729是由美国、法国、日本和加拿大的几家著名国际电信实体联合开发的。  


### 实时音频通讯编码标准：G.729A <a id="13"></a>

  
制定者：ITU-T  
所需带宽：8Kbps\(34.4\)  
音频宽度：3.4KHZ  
特性：复杂性较G.729低，性能较G.729差。  
优点：语音质量良，降低了计算的复杂度以便于实时实现，提供了对帧丢失和分组丢失的隐藏处理机制  
缺点：性能较G.729差  
备注：96年ITU-T又制定了G.729的简化方案G.729A，主要降低了计算的复杂度以便于实时实现，因此目前使用的都是G.729A。  


### 实时音频通讯编码标准：MPEG-1 audio layer 1 <a id="14"></a>

  
制定者：MPEG  
所需带宽：384kbps（压缩4倍）  
音频宽度：  
特性：编码简单，用于数字盒式录音磁带，2声道，VCD中使用的音频压缩方案就是MPEG-1层Ⅰ。  
优点：压缩方式相对时域压缩技术而言要复杂得多，同时编码效率、声音质量也大幅提高，编码延时相应增加。可以达到“完全透明”的声音质量（EBU音质标准）  
缺点：频宽要求较高  
备注：MPEG-1声音压缩编码是国际上第一个高保真声音数据压缩的国际标准，它分为三个层次：  
--层1\(Layer 1\)：编码简单，用于数字盒式录音磁带  
--层2\(Layer 2\)：算法复杂度中等，用于数字音频广播\(DAB\)和VCD等  
--层3\(Layer 3\)：编码复杂，用于互联网上的高质量声音的传输，如MP3音乐压缩10倍  


### 实时音频通讯编码标准：MPEG-1 audio layer 2，即MP2 <a id="15"></a>

  
制定者：MPEG  
所需带宽：256～192kbps（压缩6～8倍）  
音频宽度：  
特性：算法复杂度中等，用于数字音频广播\(DAB\)和VCD等，2声道，而MUSICAM由于其适当的复杂程度和优秀的声音质量，在数字演播室、DAB、DVB等数字节目的制作、交换、存储、传送中得到广泛应用。  
优点：压缩方式相对时域压缩技术而言要复杂得多，同时编码效率、声音质量也大幅提高，编码延时相应增加。可以达到“完全透明”的声音质量（EBU音质标准）  
缺点：无记录  
备注：同MPEG-1 audio layer 1  


### 实时音频通讯编码标准：MPEG-1 audio layer 3\(MP3\) <a id="16"></a>

  
制定者：MPEG  
所需带宽：128～112kbps（压缩10～12倍）  
音频宽度：无记录  
特性：编码复杂，用于互联网上的高质量声音的传输，如MP3音乐压缩10倍，2声道。MP3是在综合MUSICAM和ASPEC的优点的基础上提出的混合压缩技术，在当时的技术条件下，MP3的复杂度显得相对较高，编码不利于实时，但由于MP3在低码率条件下高水准的声音质量，使得它成为软解压及网络广播的宠儿。  
优点：压缩比高，适合用于互联网上的传播  
缺点：MP3在128KBitrate及以下时，会出现明显的高频丢失  
备注：同MPEG-1 audio layer 1  


### 实时音频通讯编码标准：MPEG-2 audio layer <a id="17"></a>

  
制定者：MPEG  
所需带宽：与MPEG-1层1，层2，层3相同  
音频宽度：无记录  
特性：MPEG-2的声音压缩编码采用与MPEG-1声音相同的编译码器，层1, 层2和层3的结构也相同，但它能支持5.1声道和7.1声道的环绕立体声。  
优点：支持5.1声道和7.1声道的环绕立体声  
缺点： 无记录  
备注：MPEG-2的声音压缩编码采用与MPEG-1声音相同的编译码器，层1, 层2和层3的结构也相同，但它能支持5.1声道和7.1声道的环绕立体声。  


### 实时音频通讯编码标准：AAC-LD \(Advanced Audio Coding，先进音频编码\) <a id="18"></a>

  
制定者：MPEG  
所需带宽：48-64 kbps  
音频宽度：22KHZ  
特性：提供高质量的低延时的音频编码标准，以其20ms的算法延时提供更高的比特率和各种声音信号的高质量音频。  
缺点：无记录  
备注：超宽带编解码器技术支持高达48KHz采样率的语音传输，与传统的窄带与宽带语音编解码器相比大幅提高了音质。该技术可提供接近CD音质的音频，数据速率高达48–64kbps，不仅提高了IP语音与视频应用的清晰度，而且支持电话音乐传输功能。高清语音通道支持更高的采样率，配合音频编解码器的高保真音效，显著丰富并扩展了频谱两端的音质范围，有效改善了语音回响性能，提高了清晰度。

