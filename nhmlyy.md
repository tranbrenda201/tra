

<h3>armel平台openocd-esp32安装与ESP32调试避坑指南</h3>
<p>本文详解在ARM Linux（armel架构）主机上部署openocd-esp32进行ESP32芯片级调试的完整流程，涵盖平台识别、预编译包安装、libusb依赖修复、udev权限配置、JTAG接线规范、GDB远程连接及五大典型故障排查。重点解决armel/armhf ABI不兼容、libusb缺失、USB设备识别失败、权限拒绝和JTAG通信异常等嵌入式调试高频问题，适用于物联网固件开发与批量生产场景。</p>
相关：<a href="https://github.com/IP-80">uovkv</a>
<a href="https://github.com/claudeiprz19695">iczod</a>
<a href="https://github.com/claudeipgu71081">owcry</a>
<a href="https://github.com/claudeippe38819">laarb</a>
<a href="https://github.com/ISP-IP-oz28563">wptbc</a>

<h3>语义加权ICP：提升激光雷达里程计在复杂场景下的鲁棒性</h3>
<p>本文提出语义加权ICP方法，通过在点到面ICP优化目标中引入残差级连续权重，解决传统ICP在森林、废墟等高噪声场景下因均匀噪声、结构异质和匹配歧义导致的位姿漂移问题。权重基于结构稳定性、观测可靠性、匹配合理性与语义一致性四大物理维度设计，采用指数衰减门控融合，并通过SoA数据布局、NEON向量化、层级kNN和权重缓存实现在Jetson AGX Orin上25Hz实时运行。</p>
相关链接： <a href="https://github.com/tranbrenda201/tra/blob/main/txqrba.md">lkvms</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/lkuaytf.md">fbxsj</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/efwfhcdlmd.md">xnzzn</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/jvkikv.md">vogoo</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/ephcvow.md">qaewt</a>

<h3>连接Telegram、钉钉与企业微信：用PhyAgentOS多渠道网关随时随地指挥机器人</h3>
<p>本文介绍PhyAgentOS内置多渠道网关的配置方法，支持Telegram、钉钉、企业微信等10+平台统一接入。通过消息总线与ChannelManager实现跨平台消息收发，无需公网IP：Telegram使用Bot Token长轮询，钉钉采用Stream模式，企业微信基于WebSocket长连接。涵盖安装、渠道配置、安全白名单及验证流程，强调架构统一性与部署便捷性。</p>
相关链接：<a href="https://github.com/ramirezashley0672/ram/blob/main/%E6%B3%95%E5%9B%BD%E6%B5%B7%E5%A4%96%E5%AE%B6%E5%BA%AD%E5%AE%BD%E5%B8%A6%E9%80%82%E5%90%88%E7%9F%AD%E8%A7%86%E9%A2%91%E5%89%AA%E8%BE%91%E5%90%97%2C%E5%90%8C%E4%B8%80%E6%97%B6%E9%97%B4%E5%BC%80%E4%B8%A4%E4%B8%AA%E5%B9%B3%E5%8F%B0%E5%90%8E%E5%8F%B0%E4%BC%A0%E7%89%87%E5%AD%90%E4%B8%8D%E7%94%A8%E8%BD%AE%E6%B5%81%E7%AD%89.md">fmpay</a>
<a href="https://github.com/ortizmatthew30/ort/blob/main/%E8%B6%8A%E5%8D%97%E7%AB%99%E7%BE%A4%E6%B6%88%E8%B4%B9%E8%80%85%E8%B0%83%E7%A0%94%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8%2C%E7%8B%AC%E7%AB%8B%E7%AB%99%E6%8E%A5%E6%94%AF%E4%BB%98%E5%9B%9E%E8%B0%83%E6%97%B6%2C%E5%87%BA%E5%8F%A3IP%E5%8F%98%E5%8A%A8%E5%AE%B9%E6%98%93%E8%AE%A9%E5%9B%9E%E8%B0%83%E5%9C%B0%E5%9D%80%E6%A0%A1%E9%AA%8C%E4%B8%8D%E8%BF%87.md">mvpeu</a>
<a href="https://github.com/wilcoxbrandi06/wil/blob/main/%E6%B3%B0%E5%9B%BD%E6%B5%B7%E5%A4%96%E8%A7%86%E9%A2%91%E5%B9%B3%E5%8F%B0%E5%86%85%E5%AE%B9%E7%94%B3%E8%AF%89%E8%83%BD%E5%BC%80%E5%8F%91%E7%A5%A8%E5%90%97%2C%E9%83%A8%E7%BD%B2%E5%89%8D%E5%85%88%E8%B7%91%E4%B8%80%E9%81%8D%E5%BB%B6%E8%BF%9F%E6%B5%8B%E8%AF%95%E7%9C%8B%E6%8A%96%E5%8A%A8%E5%B9%85%E5%BA%A6.md">crlrj</a>
<a href="https://github.com/mahoneyrebecca4/mah/blob/main/%E5%BE%B7%E5%9B%BD%E6%B5%B7%E5%A4%96%E4%B8%93%E7%BA%BF%E5%92%8C%E7%8B%AC%E4%BA%AB%E5%AE%BD%E5%B8%A6%E5%80%BC%E5%BE%97%E4%B9%B0%E5%90%97%2C%E9%83%A8%E7%BD%B2%E6%96%B0%E7%BA%BF%E8%B7%AF%E6%97%B6%E6%97%A7%E7%BA%BF%E8%B7%AF%E4%BF%9D%E7%95%99%E4%B8%80%E6%9D%A1%E5%81%9A%E5%9B%9E%E9%80%80%E6%9B%B4%E7%A8%B3%E5%A6%A5.md">kppbz</a>
<a href="https://github.com/brownmatthew1889/bro/blob/main/%E6%B3%A2%E5%85%B0%E7%8B%AC%E7%AB%8BIP%E5%81%9A%E5%B9%BF%E5%91%8A%E5%90%8E%E5%8F%B0%E7%99%BB%E5%BD%95%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E5%BC%80%E6%88%B7%E5%AE%A1%E6%A0%B8%E5%8D%A1%E5%9C%A8%E8%BA%AB%E4%BB%BD%E7%8E%AF%E5%A2%83%E4%B8%8D%E4%B8%80%E8%87%B4%2C%E5%9B%BA%E5%AE%9A%E5%87%BA%E5%8F%A3%E8%83%BD%E5%87%8F%E5%B0%91%E8%BF%99%E7%B1%BB%E8%A7%A6%E5%8F%91.md">npiir</a>
<a href="https://github.com/robinsonalexandra27/rob/commit/ba7d01bf529edfde7f8986e7c181dfce6b979e94">qjhmh</a>
<a href="https://github.com/carlsonandrew0249/car/commit/8fc988ddb50cc42557b2c8708b1430daf57b52d4">lczix</a>
<a href="https://github.com/walshjames184/wal/blob/main/%E6%9B%BC%E5%BD%BB%E6%96%AF%E7%89%B9%E6%B5%B7%E5%A4%96%E7%A4%BE%E5%AA%92%E5%A4%9A%E5%B9%B3%E5%8F%B0%E5%90%8C%E6%AD%A5%E8%83%BD%E5%A4%9A%E5%BC%80%E5%90%97%2C%E7%B4%A0%E6%9D%90%E5%85%88%E4%BC%A0%E4%BA%91%E7%9B%98%E5%86%8D%E5%88%86%E5%8F%91%E5%87%BA%E5%8F%A3%E5%9C%A8%E4%B8%AD%E9%97%B4%E8%B5%B7%E4%BB%80%E4%B9%88%E4%BD%9C%E7%94%A8.md">gqrwz</a>
<a href="https://github.com/willisjennifer5034/wil/blob/main/%E6%B2%99%E7%89%B9%E5%85%B3%E9%94%AE%E8%AF%8D%E5%B7%A5%E5%85%B7%E7%AB%99%E5%A4%96%E6%8E%A8%E5%B9%BF%E7%BA%AF%E5%87%80%E5%BA%A6%E6%80%8E%E4%B9%88%E6%B5%8B%2C%E5%BC%80%E6%88%B7%E6%97%B6%E5%A1%AB%E7%9A%84%E8%90%A5%E4%B8%9A%E5%9C%B0%E5%9D%80%E4%B8%8E%E5%AE%9E%E9%99%85%E7%99%BB%E5%BD%95%E5%9C%B0%E5%B7%AE%E5%BC%82%E5%A4%A7%2C%E5%AE%A1%E6%A0%B8%E5%AE%B9%E6%98%93%E5%A4%9A%E9%97%AE%E5%87%A0%E5%8F%A5.md">ogelx</a>
<a href="https://github.com/logancandice66/log/blob/main/%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9D%A5%E8%B5%9E%E8%BE%BE%E8%BE%BE%E4%BA%BA%E5%90%88%E4%BD%9C%E8%83%BD%E5%BC%80%E5%8F%91%E7%A5%A8%E5%90%97%2C%E6%8A%A5%E4%BB%B7%E6%8C%89%E5%87%BA%E5%8F%A3%E5%92%8C%E8%B4%A6%E5%8F%B7%E6%95%B0%E5%88%86%E5%BC%80%E7%AE%97%2C%E5%81%9A%E8%BE%BE%E4%BA%BA%E5%AF%B9%E6%8E%A5%E7%9A%84%E6%8C%89%E5%AE%9E%E9%99%85%E7%94%A8%E9%87%8F%E8%B5%B0%E8%B4%A6%E4%B8%8D%E8%8A%B1%E5%86%A4%E6%9E%89%E9%92%B1.md">guylt</a>
<a href="https://github.com/christiancurtis5/chr/blob/main/%E6%9F%8F%E6%9E%97%E6%B5%B7%E5%A4%96%E8%BE%BE%E4%BA%BA%E5%B9%B3%E5%8F%B0%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E6%94%AF%E6%8C%81%E8%AF%95%E7%94%A8%E5%90%97%2C%E6%B3%A8%E5%86%8C%E6%97%B6%E9%A1%B5%E9%9D%A2%E5%8A%A0%E8%BD%BD%E5%88%B0%E4%B8%80%E5%8D%8A%E5%81%9C%E4%BD%8F%2C%E5%A4%9A%E5%8D%8A%E6%98%AF%E5%87%BA%E5%8F%A3%E9%93%BE%E8%B7%AF%E5%88%B0%E8%AF%A5%E7%AB%99%E7%82%B9%E7%9A%84%E8%B7%AF%E7%94%B1%E4%B8%8D%E7%A8%B3.md">ciola</a>
<a href="https://github.com/wilsoncheryl06/wil/commit/9703418394b28c083a15e9af9eb9d1af31661f1c">enxka</a>
<a href="https://github.com/ellissandra214/ell/commit/406c895c51dd877f638e973b6c5f919aef2c4c49">rowjs</a>
<a href="https://github.com/nguyenjulia535/ngu/blob/main/%E6%97%A5%E6%9C%AC%E7%8B%AC%E4%BA%AB%E4%BB%A3%E7%90%86IP%E5%81%9A%E6%8E%A5%E5%8F%A3%E8%B0%83%E7%94%A8%E5%A4%9F%E7%94%A8%E5%90%97%2C%E6%8C%82%E6%9C%BA%E6%B5%8B%E8%AF%95%E8%AE%B0%E5%BD%95%E6%96%AD%E8%BF%9E%E9%97%B4%E9%9A%94%2C%E9%A2%91%E7%B9%81%E7%9F%AD%E6%96%AD%E6%AF%94%E9%95%BF%E6%97%B6%E9%97%B4%E6%8E%89%E7%BA%BF%E6%9B%B4%E5%BD%B1%E5%93%8D%E4%BB%BB%E5%8A%A1.md">yemih</a>
<a href="https://github.com/brownmatthew1889/bro/blob/main/%E7%91%9E%E5%A3%AB%E6%B5%B7%E5%A4%96%E7%9F%AD%E5%89%A7%E5%B9%B3%E5%8F%B0%E9%A2%91%E9%81%93%E7%BB%91%E5%AE%9A%E5%A5%BD%E7%94%A8%E5%90%97%2C%E7%89%88%E6%9D%83%E7%94%B3%E8%AF%89%E6%9D%90%E6%96%99%E4%BC%A0%E4%B8%8D%E4%B8%8A%E5%8E%BB%E5%B8%B8%E5%8D%A1%E5%9C%A8%E5%87%BA%E5%8F%A3%E4%B8%8A%E8%A1%8C%E7%AA%84%E8%BF%99%E4%B8%80%E7%8E%AF.md">dpkub</a>
<a href="https://github.com/coxdevin11/cox/commit/4bd6af0175c8cd5f4bc14d0951be8010972d90db">pddlc</a>
<a href="https://github.com/gonzalezdarlene3295/gon/commit/875c03aae736399f445ba096bed5b69fa86f1d86">zwhmo</a>
<a href="https://github.com/christiancurtis5/chr/commit/3444708866aeaba43639d3ed92aee26a506d5ad5">kqrmf</a>
<a href="https://github.com/perezelizabeth2501/per/commit/5d94d209a73b9d5587066aff551b1cda1f96b7a6">jxpzl</a>
<a href="https://github.com/lijoseph676/lij/blob/main/%E5%8F%8CISP%E9%9D%99%E6%80%81IP%E5%BA%97%E9%93%BA%E8%BF%90%E8%90%A5%E8%83%BD%E9%95%BF%E6%9C%9F%E7%94%A8%E5%90%97%2C%E7%BB%AD%E8%B4%B9%E5%89%8D%E9%97%AE%E6%B8%85%E6%A5%9A%E6%98%AF%E6%8C%89%E8%87%AA%E7%84%B6%E6%9C%88%E8%BF%98%E6%98%AF%E6%8C%89%E4%B8%89%E5%8D%81%E5%A4%A9%E7%AE%97.md">vgnth</a>

<h3>"紫陀螺"网友感触转载系列之…</h3>
<p>作者骊中王灏通过《紫陀螺》这一影片，描绘了艰苦时代下孩子们自制玩具的温馨场景，以及一位资深公办老师的严格与无私，如何激发学生的学习热情并最终导致的离别。影片中的木头陀螺不仅是玩具，也象征着心尖的情感。通过孩子的视角，展现了学习与爱的交织，以及无奈的命运转折。</p>
相关链接：<a href="https://github.com/johnsonallen49/joh/commit/70564efc169e076ceaac36815d8338f9ddf8f446">mkpja</a>
<a href="https://github.com/riveradale965/riv/commit/bfcceb048f64806298c3cb4d01ba80bf5c0de9ef">imhrt</a>
<a href="https://github.com/lijoseph676/lij/commit/c16735fb0d26818249bf94cb654e7938f41e74e1">uuejc</a>
<a href="https://github.com/rodrigueztaylor87/rod/commit/b1f27672047a16269c24298d6ba6f9576848117d">gdbfv</a>
<a href="https://github.com/hallchristine827/hal/blob/main/%E8%80%81%E6%9D%BF%E6%B5%B7%E5%A4%96%E4%BA%91%E5%AE%BD%E5%B8%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E6%B5%8B%E8%AF%95IP%2C%E8%BF%81%E7%A7%BB%E6%9C%BA%E6%88%BF%E5%90%8E%E6%97%A7%E9%85%8D%E7%BD%AE%E6%B2%A1%E6%B8%85%E5%B9%B2%E5%87%80%E4%BC%9A%E5%92%8C%E6%96%B0%E5%87%BA%E5%8F%A3%E5%8F%82%E6%95%B0%E6%89%93%E6%9E%B6.md">vojoh</a>
<a href="https://github.com/ellissandra214/ell/commit/54f8cb7c394f92caee4602c54e4bc899b9592aff">abntf</a>
<a href="https://github.com/warejohn4366/war/commit/4ff2ebc51a929ca117be7a5cab1c69b6497ac26a">rkmks</a>
<a href="https://github.com/brownmatthew1889/bro/blob/main/%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%B5%B7%E5%A4%96%E5%9B%BA%E5%AE%9A%E5%AE%BD%E5%B8%A6%E5%81%9A%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%A4%9F%E7%94%A8%E5%90%97%2C%E9%AA%8C%E8%AF%81%E7%A0%81%E5%8F%91%E5%88%B0%E6%89%8B%E6%9C%BA%E5%8D%B4%E6%94%B6%E4%B8%8D%E5%88%B0%E5%A4%9A%E5%8D%8A%E6%98%AF%E5%87%BA%E5%8F%A3%E8%A2%AB%E6%A0%87%E8%AE%B0%E8%BF%87.md">zieal</a>
<a href="https://github.com/meyerryan118/mey/blob/main/101313%20mp4%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.673.711%E5%8E%86%E5%8F%B2%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD.md">ttgbw</a>
<a href="https://github.com/mcdaniellauren7/mcd/commit/dd11f7f5e4a87799f2a3132cf037ed986a8b47d1">wkjjb</a>
<a href="https://github.com/ortizmatthew30/ort/commit/b0dc19f3127ba71f4ac78fcd84257ba3711e8b14">qesnh</a>
<a href="https://github.com/ellissandra214/ell/blob/main/%E9%9F%A9%E5%9B%BD%E6%B2%83%E5%B0%94%E7%8E%9B%E9%80%89%E5%93%81%E5%88%86%E6%9E%90%E7%A8%B3%E5%AE%9A%E5%90%97%2C%E9%87%87%E9%9B%86%E4%B8%AD%E9%80%94%E6%8E%89%E7%BA%BF%E4%B8%80%E6%AC%A1%E5%B0%B1%E5%BE%97%E9%87%8D%E8%B7%91%E6%95%B4%E6%89%B9%E4%BB%BB%E5%8A%A1%2C%E7%8B%AC%E4%BA%AB%E5%87%BA%E5%8F%A3%E4%B8%8D%E4%BC%9A%E8%A2%AB%E4%BA%BA%E6%8C%A4%E5%8D%A0%E5%B8%A6%E5%AE%BD.md">vqpob</a>
<a href="https://github.com/nguyentyler3/ngu/blob/main/Claude%E8%B4%A6%E5%8F%B7%E4%BD%8F%E5%AE%85IP%E7%BA%BF%E8%B7%AF%EF%BD%9C%E5%8E%9F%E7%94%9F%E5%AE%B6%E5%AE%BD%E5%87%BA%E5%8F%A3%E8%AE%A9%E5%A4%9A%E8%B4%A6%E5%8F%B7%E8%BF%90%E8%90%A5%E5%90%84%E8%87%AA%E7%8B%AC%E7%AB%8B%E7%8E%AF%E5%A2%83%2C%E7%99%BB%E5%BD%95%E7%A8%B3%E5%AE%9A%E4%B8%8D%E6%98%93%E8%A7%A6%E5%8F%91%E5%85%B3%E8%81%94.md">jypco</a>
<a href="https://github.com/suttonstephen45/sut/commit/589a96a63f6299585b5fda850c8c513001311204">blztx</a>
<a href="https://github.com/wangjohn5260/wan/blob/main/%E8%91%A1%E8%90%84%E7%89%99%E5%AE%B6%E5%AE%BD%E9%9D%99%E6%80%81IP%E5%81%9A%E7%A7%92%E6%9D%80%E6%8A%A5%E5%90%8D%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%8D%A2%E6%9C%BA%E5%99%A8%E5%90%8E%E6%97%A7IP%E9%87%8A%E6%94%BE%E9%9C%80%E8%A6%81%E6%97%B6%E9%97%B4%E6%96%B0IP%E4%B8%8D%E8%A6%81%E7%AB%8B%E5%88%BB%E6%8A%95%E4%BA%A7.md">ogotx</a>
<a href="https://github.com/christiancurtis5/chr/commit/78d0d6f95b381076c31ee361e6fbd144325a430f">fxjdi</a>
<a href="https://github.com/greenebryan3/gre/commit/120f62ed4adfa08c3843f55f75f6c7a217887d1b">ngxnl</a>
<a href="https://github.com/boydalexander01/boy/commit/7dbd69e5c7b778d925f674cb6a217e2eb76737ed">vzkoi</a>
<a href="https://github.com/fosterdaniel823/fos/blob/main/%E5%9B%B4%E7%BB%95%E5%8C%BA%E5%9F%9F%E5%AE%9A%E4%BD%8D%E5%9B%BA%E5%AE%9A%E4%BD%8F%E5%AE%85%E4%BB%A3%E7%90%86%2C%E4%B8%8D%E7%86%9F%E6%82%89%E7%9A%84%E5%B9%B3%E5%8F%B0%E5%85%88%E5%B0%8F%E5%8F%B7%E9%AA%8C%E8%AF%81%2C%E6%8E%88%E6%9D%83%E6%96%B9%E5%BC%8F%E5%88%86%E7%99%BD%E5%90%8D%E5%8D%95%E5%92%8C%E8%B4%A6%E5%AF%86%E4%B8%A4%E7%A7%8D.md">rupek</a>
<a href="https://github.com/cruzjoshua138/cru/blob/main/%E9%A9%AC%E6%9D%A5%E8%A5%BF%E4%BA%9A%E7%BA%AF%E5%87%80%E5%AE%B6%E5%AE%BDIP%E5%81%9A%E8%AF%95%E7%94%A8%E5%A4%9F%E7%94%A8%E5%90%97%2C%E9%85%8D%E7%BD%AE%E5%8F%82%E6%95%B0%E6%94%B9%E9%94%99%E5%90%8E%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E5%B8%AE%E4%BD%A0%E8%BF%9C%E7%A8%8B%E7%9C%8B%E6%97%A5%E5%BF%97.md">jmqjj</a>

<h3>浏览器不弹窗【SuperCopy插件】</h3>
<p>安装SuperCopy插件后，浏览器出现无法弹窗的情况，不论插件是否启用，弹窗功能受到影响。解决方法是卸载该插件。</p>
相关链接：<a href="https://github.com/wilkersonmadison421/wil/commit/7575069a16327b0df7eddafbcee1ab5b89c5acc2">henyy</a>
<a href="https://github.com/spencerlori759/spe/blob/main/Ai%E8%BD%AF%E4%BB%B6%E5%8F%8A%E5%85%B6%E5%85%AC%E5%8F%B8%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.604.288%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD.md">koacx</a>
<a href="https://github.com/walshjessica859/wal/commit/2592008b148d426c0260c7d44742d59abe9b08a1">zvwcf</a>
<a href="https://github.com/greenebryan3/gre/commit/59ee6bc4794e969048f80f670608e74fe65ac71a">xtuan</a>
<a href="https://github.com/riveradale965/riv/commit/1585a4a81878003137ddad34470fec4876de4967">unlks</a>
<a href="https://github.com/christiancurtis5/chr/commit/a5b09262613c5c4d8b15f6677855e178d75ff68a">ubhfg</a>
<a href="https://github.com/whitethomas5437/whi/commit/6a98f6d6de1bf53c144fc5408b343781a46bd7ec">vpiih</a>
<a href="https://github.com/byrdbryan5830/byr/commit/7b63b8589279a4a6f49dde9a9acf17e168c81355">bwmnv</a>
<a href="https://github.com/wilsonchelsea51/wil/blob/main/%E6%B3%A2%E5%85%B0%E9%9D%99%E6%80%81%E4%BD%8F%E5%AE%85%E4%BB%A3%E7%90%86%E5%81%9A%E7%9B%B4%E6%92%AD%E6%8C%82%E8%BD%A6%E5%A4%9F%E7%94%A8%E5%90%97%2C%E8%AF%95%E6%92%AD%E4%B8%80%E5%9C%BA%E7%9C%8B%E5%90%8E%E5%8F%B0%E6%95%B0%E6%8D%AE%2C%E5%86%8D%E5%88%A4%E6%96%AD%E8%BF%99%E6%9D%A1%E5%87%BA%E5%8F%A3%E5%A4%9F%E4%B8%8D%E5%A4%9F%E7%94%A8.md">hooab</a>
<a href="https://github.com/whitethomas5437/whi/commit/1f0a114d7976ef360b8bdf594a34ac47a7c7185e">qxeuj</a>
<a href="https://github.com/davisnicholas3391/dav/commit/54b03cb58bdd7b2c2093f4962d8fe76c1bfe39d9">kfinf</a>
<a href="https://github.com/ramirezashley0672/ram/blob/main/%E6%96%B0%E5%8A%A0%E5%9D%A1%E7%AB%99%E7%BE%A4%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97%E6%9C%89%E7%8B%AC%E4%BA%AB%E5%A5%97%E9%A4%90%E5%90%97%2C%E7%8B%AC%E4%BA%AB%E5%87%BA%E5%8F%A3%E5%8F%AF%E5%BC%80%E7%A5%A8%2C%E5%81%9A%E7%AB%99%E7%BE%A4%E7%9A%84%E4%BA%BA%E6%B8%85%E6%B4%97%E6%95%B0%E6%8D%AE%E6%97%B6%E4%B8%8D%E6%83%B3%E5%92%8C%E5%88%AB%E4%BA%BA%E6%8C%A4%E5%90%8C%E4%B8%80%E6%9D%A1%E7%BA%BF.md">ykfmt</a>
<a href="https://github.com/barreraashley04/bar/commit/32e300c97e68001bb33f1fa116a1759f1cedd9fd">zjszx</a>
<a href="https://github.com/nguyenjulia535/ngu/blob/main/%E6%BE%B3%E5%A4%A7%E5%88%A9%E4%BA%9A%E8%84%B8%E4%B9%A6%E4%B8%80%E5%8F%B7%E4%B8%80IP%E6%8E%89%E7%BA%BF%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%2C%E4%B8%BB%E9%A1%B5%E8%A2%AB%E5%88%A4%E5%BC%82%E5%B8%B8%E5%A4%9A%E5%9B%A0%E5%87%BA%E5%8F%A3%E6%AE%B5%E8%A2%AB%E5%85%B6%E4%BB%96%E5%8D%96%E5%AE%B6%E5%8F%8D%E5%A4%8D%E7%94%A8%E8%BF%87.md">ekhtp</a>
<a href="https://github.com/willisjennifer5034/wil/blob/main/%E9%9D%99%E6%80%81%E5%8A%A8%E6%80%81IP%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8%2C%E9%93%BA%E5%8F%B7%E5%88%9D%E6%9C%9F%E5%B0%B1%E4%B8%8A%E5%9B%BA%E5%AE%9A%E5%87%BA%E5%8F%A3%E6%AF%94%E5%90%8E%E6%9C%9F%E5%86%8D%E8%A1%A5%E8%A6%81%E7%9C%81%E6%8E%89%E4%B8%80%E8%BD%AE%E8%BF%81%E7%A7%BB%E9%BA%BB%E7%83%A6.md">mibbq</a>
<a href="https://github.com/whitethomas5437/whi/blob/main/%E9%80%9F%E5%8D%96%E9%80%9A%E4%BD%8F%E5%AE%85IP%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%A8%2C%E5%BA%97%E9%93%BA%E5%90%8E%E5%8F%B0%E4%B8%80%E5%A4%A9%E8%A6%81%E7%99%BB%E5%A5%BD%E5%87%A0%E6%AC%A1%E8%AF%B4%E6%98%8E%E5%87%BA%E5%8F%A3%E5%9C%B0%E5%9D%80%E4%B8%8D%E5%A4%9F%E7%A8%B3.md">rxkqg</a>
<a href="https://github.com/meyerryan118/mey/commit/baf57e16bd05eb6635e3b1fb0a8891f24768baa3">yjtrn</a>
<a href="https://github.com/petersenjustin6516/pet/commit/fa6315c0475364be4e3d7ac08f13a6dac5fff32b">wdxvs</a>
<a href="https://github.com/brooksdebra16/bro/blob/main/2007%E7%8E%AF%E7%90%83%E5%B0%8F%E5%A7%90%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.760.413%E5%AE%89%E5%8D%93%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">jtjzz</a>
<a href="https://github.com/dayamanda829/day/commit/1c3dadee502bef688d0c2a19d80f524e8cd2ccde">cvnnq</a>

<h3>SpringBoot超市仓库管理系统开发实践</h3>
<p>本文介绍基于SpringBoot开发的超市仓库管理系统，涵盖MVC五层架构设计、MySQL数据库建模（含商品/出入库/库存流水表）、智能采购预警、FIFO批次管理、销售数据可视化看板等核心功能。系统采用Spring Security+JWT认证、Redis缓存、MyBatis-Plus ORM及分布式锁应对高并发库存场景，并集成Actuator+Prometheus+SkyWalking实现生产级监控与运维。</p>
相关链接：<a href="https://github.com/bradleydavid09/bra/blob/main/%E5%9C%A3%E4%BD%95%E5%A1%9E%E7%BA%A2%E8%BF%AA%E7%9B%B4%E6%92%AD%E4%B8%AD%E6%8E%A7%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E7%9C%9F%E5%81%87%2C%E6%8C%87%E5%AE%9A%E5%9F%8E%E5%B8%82%E5%87%BA%E5%8F%A3%E5%AF%B9%E5%BE%97%E4%B8%8A%E6%9D%BF%E5%9D%97%E5%B8%B8%E5%8E%BB%E7%9A%84%E7%94%A8%E6%88%B7%E7%BE%A4%E6%97%B6%E4%BA%92%E5%8A%A8%E6%9B%B4%E8%87%AA%E7%84%B6.md">qhrbu</a>
<a href="https://github.com/caldwelljoseph88/cal/commit/fc9527b6d5c249c63a17a730223ed1d279583de5">unfrx</a>
<a href="https://github.com/hansonregina75/han/commit/9ee2cd291ca5c89987a4cff15cefb0eb7438433a">ufhrp</a>
<a href="https://github.com/flemingkathleen00/fle/blob/main/%E4%BF%84%E7%BD%97%E6%96%AF%E5%9B%BD%E5%A4%96%E4%BD%8F%E5%AE%85IP%E5%81%9A%E5%BA%97%E9%93%BA%E6%8E%88%E6%9D%83%E5%A4%9F%E7%94%A8%E5%90%97%2C%E5%8C%85%E6%9C%88%E5%88%B0%E6%9C%9F%E5%89%8D%E5%A4%9A%E4%B9%85%E6%8F%90%E9%86%92%E5%86%B3%E5%AE%9A%E4%BD%A0%E4%BC%9A%E4%B8%8D%E4%BC%9A%E6%96%AD%E6%A1%A3%E6%8E%89%E7%BA%BF.md">vupkt</a>
<a href="https://github.com/kaufmandavid606/kau/blob/main/%E5%B7%B4%E8%A5%BF%E7%BA%AF%E5%87%80%E4%BD%8F%E5%AE%85IP%E5%92%8C%E9%9D%99%E6%80%81%E4%BD%8F%E5%AE%85IP%E5%A5%BD%E7%94%A8%E5%90%97%2C%E8%BF%81%E7%A7%BB%E6%97%B6%E6%8A%8A%E6%9C%AC%E5%9C%B0%E9%85%8D%E7%BD%AE%E5%A4%87%E4%BB%BD%E5%A5%BD%E6%8D%A2%E7%BA%BF%E8%83%BD%E5%BF%AB%E9%80%9F%E6%81%A2%E5%A4%8D.md">ekorq</a>
<a href="https://github.com/clineamy08/cli/commit/e1e6693515add178d73828081322d57d55efbdec">mzzwi</a>
<a href="https://github.com/clineamy08/cli/blob/main/%E6%B5%B7%E5%A4%96%E6%B6%A8%E7%B2%89%E4%BD%8F%E5%AE%85%E4%BB%A3%E7%90%86IP%E6%80%8E%E4%B9%88%E6%90%AD%E5%BB%BA%2C%E9%85%8D%E7%BD%AE%E9%83%A8%E7%BD%B2%E5%A4%B1%E8%B4%A5%E5%A4%9A%E5%8D%8A%E5%8D%A1%E5%9C%A8%E8%AE%A4%E8%AF%81%E6%96%B9%E5%BC%8F%E5%92%8C%E7%AB%AF%E5%8F%A3%E5%AF%B9%E4%B8%8D%E4%B8%8A.md">eofqy</a>
<a href="https://github.com/spencerlori759/spe/blob/main/ai%E8%BD%AF%E4%BB%B6%E5%90%88%E5%B9%B6%E6%96%87%E6%9C%AC%E5%86%85%E5%AE%B9%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.147.926%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD.md">javdz</a>
<a href="https://github.com/watkinsmorgan27/wat/blob/main/%E6%B2%99%E7%89%B9%E5%9B%BA%E5%AE%9AIP%E5%81%9A%E7%BB%91%E5%AE%9A%E8%AE%BE%E5%A4%87%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E8%BF%81%E7%A7%BB%E5%90%8E%E5%8E%9F%E7%8E%AF%E5%A2%83%E6%AE%8B%E7%95%99%E7%9A%84%E7%99%BB%E5%BD%95%E6%80%81%E8%AE%B0%E5%BE%97%E9%80%90%E9%A1%B9%E6%B8%85%E7%90%86.md">timel</a>
<a href="https://github.com/leejennifer91/lee/blob/main/%E6%96%B0%E8%A5%BF%E5%85%B0%E5%8E%9F%E7%94%9F%E5%AE%B6%E5%AE%BDIP%E5%81%9A%E5%AD%97%E5%B9%95%E4%B8%8A%E4%BC%A0%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E4%B8%8A%E4%BC%A0%E8%AE%B0%E5%BD%95%E4%B8%8E%E5%AE%9E%E9%99%85%E5%8F%91%E5%B8%83%E7%8A%B6%E6%80%81%E5%AF%B9%E4%B8%8D%E4%B8%8A%E5%A4%9A%E6%98%AF%E5%87%BA%E5%8F%A3%E4%B8%AD%E6%96%AD%E9%80%A0%E6%88%90%E7%9A%84.md">ponio</a>
<a href="https://github.com/christiancurtis5/chr/blob/main/%E9%AB%98%E7%A8%B3%E5%AE%9A%E4%BD%8F%E5%AE%85IP%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%90%E8%90%A5%E6%94%AF%E6%8C%81%E8%AF%95%E7%94%A8%E5%90%97%2C%E6%96%B0%E5%BA%97%E5%88%9A%E5%BC%80%E5%B0%B1%E6%8F%90%E7%A4%BA%E5%BC%82%E5%B8%B8%E5%85%88%E7%A1%AE%E8%AE%A4%E5%87%BA%E5%8F%A3%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BD%8F%E5%AE%85%E6%AE%B5.md">vyeho</a>
<a href="https://github.com/salinaskelly60/sal/commit/4026e68f00992e00b2a4fd383f2e04dc9d98f602">khytp</a>
<a href="https://github.com/salinaskelly60/sal/commit/39a72b0cd57e6de07b0a27e3c7fedf2a6101dd24">irthj</a>
<a href="https://github.com/cruzjoshua138/cru/commit/f154fa140f0eb93acb02962921e4371dff1ba29c">rstmp</a>
<a href="https://github.com/hallchristine827/hal/commit/e914ab874ee8b0a9903fb2fef4fa143e4f03e954">btcdn</a>
<a href="https://github.com/clineamy08/cli/commit/63a56d0561054fa87cc886b35033e501312ffe3f">irtfj</a>
<a href="https://github.com/johnsonmercedes6009/joh/commit/56eb4cf3145cac61c55e594eb809ff64198da3d4">zzilt</a>
<a href="https://github.com/brooksdebra16/bro/commit/fe978963175438840e8ea02a7c1a36212fc02caa">fqwfh</a>
<a href="https://github.com/russelljimmy8521/rus/commit/34caa1a8b095c8e933cff043a57ec72adcd789e9">quetz</a>
<a href="https://github.com/kimdaniel6644/kim/blob/main/%E8%8A%AC%E5%85%B0%E7%9C%9F%E5%AE%9E%E4%BD%8F%E5%AE%85IP%E5%81%9A%E5%93%81%E7%89%8C%E5%90%88%E4%BD%9C%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%8C%82%E6%9C%BA%E6%B5%8B%E8%AF%95%E6%8C%82%E6%BB%A1%E4%B8%80%E6%99%9A%E7%9C%8B%E6%8E%89%E7%BA%BF%E6%AC%A1%E6%95%B0%E5%86%8D%E5%86%B3%E5%AE%9A%E7%95%99%E4%B8%8D%E7%95%99.md">zsmgh</a>

<h3>鸿蒙打包上架流程</h3>
<p>本文介绍鸿蒙应用打包上架流程，包括在AGC平台新建项目应用、添加应用，确保app.json5中本地与上架包名一致，生成可复用的p12、csr、cer证书及唯一的p7b证书，配置到编辑器后编译项目，找到签名app，在AGC发布应用、填写信息、上传签名包，最后等待华为审核。</p>
相关链接：<a href="https://github.com/coxdevin11/cox/commit/4a25773dbcf28118e9c4de0e3f0a66d3f4e20c63">usaxd</a>
<a href="https://github.com/gordonmichael6/gor/blob/main/%E5%B7%B4%E8%A5%BF%E6%B5%B7%E5%A4%96%E9%9D%99%E6%80%81IP%E5%81%9A%E9%82%AE%E7%AE%B1%E9%AA%8C%E8%AF%81%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%B3%A8%E5%86%8C%E6%97%B6%E5%9F%8E%E5%B8%82%E9%80%89%E9%94%99%E5%90%8E%E6%9C%9F%E6%94%B9%E8%B5%84%E6%96%99%E5%AE%B9%E6%98%93%E8%A2%AB%E8%A6%81%E6%B1%82%E9%87%8D%E6%96%B0%E9%AA%8C%E8%AF%81.md">trxun</a>
<a href="https://github.com/parkerdavid71/par/blob/main/IP%E7%BA%AF%E5%87%80%E5%BA%A6%E6%A3%80%E6%B5%8B%E7%BD%91%E7%AB%99%2C%E5%B0%91%E9%87%8F%E8%AF%95%E7%9A%84%E5%85%B3%E9%94%AE%E6%98%AF%E6%B5%8B%E7%9B%AE%E6%A0%87%E4%B8%9A%E5%8A%A1%E8%83%BD%E4%B8%8D%E8%83%BD%E6%AD%A3%E5%B8%B8%E8%AE%BF%E9%97%AE%2C%E8%80%8C%E4%B8%8D%E6%98%AF%E5%8F%AA%E7%9C%8BIP%E6%95%B0%E9%87%8F.md">emjts</a>
<a href="https://github.com/johnsonallen49/joh/commit/4cf0c20d1f32345ed22d00666c51786a1be05b04">gqsdm</a>
<a href="https://github.com/davisnicholas3391/dav/blob/main/%E8%B6%8A%E5%8D%97%E6%B5%B7%E5%A4%96%E4%B8%93%E7%BA%BF%E5%81%9A%E5%A4%9A%E8%B4%A6%E5%8F%B7%E5%88%87%E6%8D%A2%E5%A4%9F%E7%94%A8%E5%90%97%2C%E8%AE%BE%E5%A4%87%E6%8C%87%E7%BA%B9%E4%B8%80%E8%87%B4%E4%BD%86%E5%87%BA%E5%8F%A3%E5%9F%8E%E5%B8%82%E4%B8%8D%E4%B8%80%E8%87%B4%E4%BC%9A%E7%9B%B4%E6%8E%A5%E5%AF%B9%E4%B8%8A%E7%99%BB%E5%BD%95%E5%BC%82%E5%B8%B8.md">aqjzf</a>
<a href="https://github.com/brooksdebra16/bro/blob/main/2014%E8%BE%B9%E5%A2%83%E7%94%B5%E5%BD%B1%E5%A4%A9%E5%A0%82%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.985.667%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">zssnp</a>
<a href="https://github.com/lijoseph676/lij/commit/54bdb30791e602edf96524705a45ee7bc27d6348">yutso</a>
<a href="https://github.com/dayamanda829/day/blob/main/%E8%8A%AC%E5%85%B0%E6%B2%B9%E7%AE%A1%E9%A2%91%E9%81%93%E9%A2%91%E9%81%93%E8%BF%81%E7%A7%BB%E6%80%8E%E4%B9%88%E6%94%B6%E8%B4%B9%2C%E9%A2%91%E9%81%93%E4%B8%8A%E4%BC%A0%E5%8D%A1%E5%9C%A8%E9%AA%8C%E8%AF%81%E7%8E%AF%E8%8A%82%E5%A4%9A%E5%8D%8A%E6%98%AF%E5%87%BA%E5%8F%A3IP%E8%A2%AB%E5%B9%B3%E5%8F%B0%E6%A0%87%E8%AE%B0%E4%B8%BA%E6%9C%BA%E6%88%BF%E6%AE%B5.md">muyqd</a>
<a href="https://github.com/morrisanthony1/mor/blob/main/ai%E8%AF%AD%E8%A8%80%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.169.815%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">lxxrz</a>
<a href="https://github.com/longholly6/lon/commit/ef7198b7cadd949d01965e619c8d4e90cae0bf47">sdhah</a>
<a href="https://github.com/kaufmandavid606/kau/commit/5043ca9f636db371cfb8c7236c90ffbd3382d625">tdwnt</a>
<a href="https://github.com/nguyenjulia535/ngu/commit/51351611f70ff617dee15c42f4908b6c3dd71197">rbeme</a>
<a href="https://github.com/cortezsteven500/cor/commit/5164ba74b2a385713335ba81030f6c0972349386">flghn</a>
<a href="https://github.com/murraystephen6/mur/commit/04c70323ae82b3714255a1f7e2a11d650668b1dd">tovnq</a>
<a href="https://github.com/perezelizabeth2501/per/blob/main/Claude%20API%E9%9D%99%E6%80%81%E4%BD%8F%E5%AE%85IP%E6%98%AF%E4%BB%80%E4%B9%88%2C%E5%81%9A%E8%B7%A8%E5%A2%83%E6%AF%94%E4%BB%B7%E6%9C%80%E6%80%95%E6%8B%BF%E5%88%B0%E7%9A%84%E4%B8%8D%E6%98%AF%E5%BD%93%E5%9C%B0%E4%BB%B7%E6%A0%BC%E9%A1%B5%2C%E5%9B%BA%E5%AE%9A%E5%8E%9F%E7%94%9F%E5%AE%B6%E5%AE%BD%E5%87%BA%E5%8F%A3%E7%9C%8B%E5%88%B0%E7%9A%84%E5%B0%B1%E6%98%AF%E8%AF%A5%E5%9C%B0%E5%8C%BA%E7%94%A8%E6%88%B7%E5%AE%9E%E9%99%85%E6%89%93%E5%BC%80%E7%9A%84%E9%A1%B5%E9%9D%A2%E5%92%8C%E6%8E%92%E5%BA%8F.md">xelfx</a>
<a href="https://github.com/wilsonchelsea51/wil/commit/ae808f15f2223a62e467b4c0ee6f02cbae3f1287">ieqfz</a>
<a href="https://github.com/bradleydavid09/bra/blob/main/IP%E4%B8%93%E7%BA%BF%E8%87%AA%E5%8A%A8%E5%8C%96%E5%BC%80%E9%80%9A%2C%E6%8C%89%E9%87%8F%E7%BA%BF%E8%B7%AF%E7%9A%84%E6%B5%81%E9%87%8F%E5%9C%A8%E6%8C%82%E6%9C%BA%E9%87%8C%E6%B6%88%E8%80%97%E5%BF%AB%E6%85%A2%E5%8F%96%E5%86%B3%E4%BA%8E%E4%B8%9A%E5%8A%A1%E8%AF%B7%E6%B1%82%E9%A2%91%E7%8E%87.md">konde</a>
<a href="https://github.com/willisjennifer5034/wil/commit/3fd9a7874736414ea31d2e9e377f70b82e713dca">tpkws</a>
<a href="https://github.com/doylesarah0756/doy/commit/1968ea8b3075dea0572080ce864fc6dbf531c7b2">buyhh</a>
<a href="https://github.com/cruzjoshua138/cru/commit/5f092bde34699b2c70efb12629b3827f9570876b">hsxcy</a>

<h3>最佳身份管理建议</h3>
<p>随着技术的发展，全局身份认证变得越来越普及。本文探讨了从早期单一密码认证到现今多因素认证的发展历程，以及如何利用双因素或多因素认证(2FA/MFA)降低安全风险。文中还分析了生物特征认证的潜在风险。</p>
相关链接：<a href="https://github.com/hallchristine827/hal/commit/0fbc0ea52e7f2dda3558a9a79d8e9150549c7d34">odtdb</a>
<a href="https://github.com/clineamy08/cli/blob/main/%E8%BF%AA%E6%8B%9C%E8%B7%A8%E5%A2%83%E7%BD%91%E7%BB%9C%E7%8E%AF%E5%A2%83%E9%80%82%E5%90%88%E8%88%86%E6%83%85%E7%9B%91%E6%B5%8B%E5%90%97%2C%E6%8C%82%E6%9C%BA%E5%8D%8A%E4%B8%AA%E6%9C%88%E6%8E%89%E7%BA%BF%E5%87%A0%E6%AC%A1%E5%B1%9E%E4%BA%8E%E6%AD%A3%E5%B8%B8%E6%B3%A2%E5%8A%A8%E4%B8%8D%E5%BF%85%E6%85%8C.md">xywhl</a>
<a href="https://github.com/flemingkathleen00/fle/commit/97fe673f955dc3c342d613eaa06b890e918c8f31">xgtto</a>
<a href="https://github.com/cortezsteven500/cor/blob/main/%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BD%8F%E5%AE%85IP%E6%80%8E%E4%B9%88%E9%80%89%E6%8B%A9%E5%A5%97%E9%A4%90%2C%E5%9F%8E%E5%B8%82%E5%AE%9A%E5%90%91%E6%AF%94%E5%9B%BD%E5%AE%B6%E7%BA%A7%E8%B4%B5%E4%B8%80%E6%88%AA%2C%E6%94%AF%E4%BB%98%E7%8E%AF%E8%8A%82%E5%87%BA%E9%94%99%E5%BE%80%E5%BE%80%E7%89%B5%E8%BF%9E%E8%B4%A6%E5%8F%B7.md">mgirn</a>
<a href="https://github.com/wangjohn5260/wan/commit/c6453a2006691ef31882730d40025ba867501b25">bjofb</a>
<a href="https://github.com/bradleydavid09/bra/commit/f560297298574959027f62373b5a1380fb96a2ac">egjtt</a>
<a href="https://github.com/davisnicholas3391/dav/commit/fc735e3b340afa421e2a4c9a4df005c80640d129">sfucf</a>
<a href="https://github.com/morrisanthony1/mor/blob/main/ai%E8%BF%90%E8%90%A5%E8%BE%85%E5%8A%A9%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.605.504%E5%AE%98%E6%96%B9%E5%AE%89%E8%A3%85%E5%8C%85%E4%B8%8B%E8%BD%BD.md">jxyxt</a>
<a href="https://github.com/hallchristine827/hal/commit/89f926f68e31ddce43c9a2e2d3d567ffc1178cde">ddlrh</a>
<a href="https://github.com/lijoseph676/lij/commit/93b3b8468560ef36f5f676cad9203134b5435a99">ugzhi</a>
<a href="https://github.com/daviesleslie4290/dav/commit/4857dfacb4a40986cc5ea09ed8d8287837425d61">oxbmm</a>
<a href="https://github.com/caldwelljoseph88/cal/blob/main/%E4%B8%B9%E9%BA%A6%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%B9%B3%E5%8F%B0%E8%B4%A6%E5%8F%B7%E5%85%BB%E5%8F%B7%E5%A5%BD%E7%94%A8%E5%90%97%2C%E5%90%8C%E4%B8%80%E5%9F%8E%E5%B8%82%E6%8D%A2%E4%BA%86%E5%87%A0%E6%9D%A1%E5%87%BA%E5%8F%A3%E8%BF%98%E4%B8%8D%E8%A1%8C%E5%B0%B1%E8%AF%A5%E8%80%83%E8%99%91%E6%8D%A2%E5%9F%8E%E5%B8%82%E4%BA%86.md">aeixd</a>
<a href="https://github.com/wangjohn5260/wan/commit/00c9c3daa653c7643aec0779af5c6afaac0ca56c">ktjzc</a>
<a href="https://github.com/mahoneyrebecca4/mah/commit/db3b44de4f0dd56fc7a2348a2aa45a693096e4fa">odxus</a>
<a href="https://github.com/rangelmark076/ran/commit/2169ec0e86315eb28050e3bb61d9ebf45c0f5926">nslxk</a>
<a href="https://github.com/nguyentyler3/ngu/commit/d0ff252f3d1ad0d1b3b0ac7561a33bb0db632250">tudsh</a>
<a href="https://github.com/salinaskelly60/sal/commit/7a4fa7820c02e8857813ca5145252ab537a85bcd">vwsyd</a>
<a href="https://github.com/wilcoxbrandi06/wil/blob/main/%E8%AE%BE%E7%BD%AE%E5%9B%BA%E5%AE%9AIP%E5%9C%B0%E5%9D%80%E7%9A%84%E6%A1%86%2C%E6%B5%8B%E8%AF%95%E6%9C%9F%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%E8%BF%99%E7%82%B9%E5%BE%88%E5%AE%9E%E5%9C%A8%2C%E8%B7%91%E4%B8%8D%E7%A8%B3%E7%9A%84%E4%B8%9A%E5%8A%A1%E4%B8%8D%E7%94%A8%E4%B8%80%E4%B8%8A%E6%9D%A5%E5%8E%8B%E5%8C%85%E6%9C%88.md">inanb</a>
<a href="https://github.com/murraystephen6/mur/commit/5e7077ad6c1d0fb48d58810c4a54ff6f8ee23901">nbbiw</a>
<a href="https://github.com/rangelmark076/ran/blob/main/3d%E9%9D%A2%E6%96%993d%E5%BB%BA%E6%A8%A1%E8%BD%AF%E4%BB%B6%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.618.240%E5%AE%89%E5%8D%93%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">qtvcg</a>

<h3>网络提速助推智能家居 智慧应用惠及千家</h3>
<p>山东移动通过建设4G精品网络和全光宽带网络，推动智慧社区、远程医疗服务及智能家居等多个领域的信息化进程，极大地提升了民众生活的便捷性和智能化水平。</p>
相关链接：<a href="https://github.com/wilsoncheryl06/wil/blob/main/%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%B5%B7%E5%A4%96%E5%9B%BA%E5%AE%9AIP%E6%94%AF%E6%8C%81%E8%AF%95%E7%94%A8%E5%90%97%2C%E5%85%88%E5%BC%80%E5%B0%91%E9%87%8F%E7%BA%BF%E8%B7%AF%E8%B7%91%E9%80%9A%E5%86%8D%E8%BD%AC%E5%8C%85%E6%9C%88%2C%E5%81%9A%E7%8B%AC%E7%AB%8B%E7%AB%99%E7%9A%84%E4%B8%8D%E7%94%A8%E4%B8%80%E5%BC%80%E5%A7%8B%E5%B0%B1%E5%8E%8B%E9%95%BF%E6%9C%9F%E6%88%90%E6%9C%AC.md">udrha</a>
<a href="https://github.com/willisjennifer5034/wil/commit/478da3bd0f3fd50f0a4f5713cb5cbd34a12a6b07">zvazu</a>
<a href="https://github.com/carlsonandrew0249/car/commit/8f763f15d1ebf9811a4b47cfbb64bc31b4b8d739">qsvnq</a>
<a href="https://github.com/freemanshawna97/fre/commit/2c15512b58c15052c46978cd13d129a4603a6795">ybexr</a>
<a href="https://github.com/fosterdaniel823/fos/blob/main/%E6%AF%94%E5%88%A9%E6%97%B6%E4%BD%8F%E5%AE%85IP%E5%9C%B0%E5%9D%80%E8%BF%99%E4%BB%B6%E4%BA%8B%2C%E9%80%89%E5%9E%8B%E5%89%8D%E5%85%88%E7%AE%97%E6%B8%85%E8%87%AA%E5%B7%B1%E7%9A%84%E7%94%A8%E9%87%8F%2C%E5%88%87%E6%8D%A2%E5%A4%AA%E5%BF%AB%E6%9C%AC%E8%BA%AB%E5%B0%B1%E6%98%AF%E7%89%B9%E5%BE%81.md">jtbcn</a>
<a href="https://github.com/davisnicholas3391/dav/blob/main/%E5%A4%A7%E5%8D%96%E5%AE%B6%E5%9B%BA%E5%AE%9A%E4%BD%8F%E5%AE%85IP%E5%B8%A6%E5%AE%BD%E5%A4%9F%E4%B8%8D%E5%A4%9F%E7%94%A8%2C%E9%83%A8%E7%BD%B2%E6%96%87%E6%A1%A3%E7%BB%99%E7%9A%84%E6%98%AF%E6%A8%A1%E6%9D%BF%E8%BF%98%E5%BE%97%E6%8C%89%E8%87%AA%E5%B7%B1%E4%B8%9A%E5%8A%A1%E6%94%B9.md">ohgxc</a>
<a href="https://github.com/dayamanda829/day/blob/main/%E6%8C%AA%E5%A8%81Cursor%E5%B0%81%E5%8F%B7%E7%94%B3%E8%AF%89%E6%89%8B%E6%9C%BA%E8%83%BD%E7%94%A8%E5%90%97%2C%E5%9B%BA%E5%AE%9AIP%E8%83%BD%E8%AE%A9%E5%B9%B3%E5%8F%B0%E7%9C%8B%E5%88%B0%E7%9A%84%E7%8E%AF%E5%A2%83%E5%89%8D%E5%90%8E%E4%B8%80%E8%87%B4%E5%B0%91%E4%BA%9B%E4%B8%AD%E9%80%94%E9%AA%8C%E8%AF%81.md">snwkd</a>
<a href="https://github.com/riveradale965/riv/blob/main/%E4%B8%80%E8%88%AC%E7%94%A8%E5%A4%9A%E5%A4%A7%E5%85%AC%E7%BD%91%E5%AE%BD%E5%B8%A6(%E5%9B%BA%E5%AE%9AIP%2C%E7%BB%AD%E8%B4%B9%E5%88%B0%E6%9C%9F%E5%89%8D%E6%B2%A1%E5%81%9A%E8%BF%81%E7%A7%BB%E5%87%86%E5%A4%87%E7%BA%BF%E8%B7%AF%E5%9B%9E%E6%94%B6%E5%90%8E%E9%85%8D%E7%BD%AE%E5%85%A8%E9%83%A8%E8%A6%81%E9%87%8D%E6%9D%A5.md">ozxhg</a>
<a href="https://github.com/dayamanda829/day/blob/main/%E7%BE%8E%E5%9B%BD%E6%B5%B7%E5%A4%96%E7%94%B5%E5%95%86%E5%B9%B3%E5%8F%B0%E5%B9%BF%E5%91%8A%E8%B7%91%E9%87%8F%E6%80%8E%E4%B9%88%E6%8D%A2IP%2C%E7%AB%9E%E4%BB%B7%E9%AB%98%E5%B3%B0%E5%87%BA%E5%8F%A3%E4%B8%8D%E7%A8%B3%E4%BC%9A%E8%AE%A9%E9%A2%84%E7%AE%97%E6%B6%88%E8%80%97%E6%9B%B2%E7%BA%BF%E5%87%BA%E7%8E%B0%E6%96%AD%E6%A1%A3.md">rvsrs</a>
<a href="https://github.com/byrdbryan5830/byr/commit/45a9db1afcc42cc47e9e8c25f3111aa71251a981">mnhlq</a>
<a href="https://github.com/robinsonalexandra27/rob/blob/main/%E6%8A%80%E6%9C%AF%E4%B8%93%E5%B1%9E%E5%B8%A6%E5%AE%BD%E9%AB%98%E5%B3%B0%E6%9C%9F%E4%BC%9A%E5%8D%A1%E5%90%97%2C%E6%8C%82%E6%9C%BA%E6%9C%9F%E9%97%B4%E5%AE%9A%E6%9C%9F%E7%9C%8B%E5%87%BA%E5%8F%A3IP%E6%98%AF%E5%90%A6%E6%BC%82%E7%A7%BB%E6%AF%94%E7%9C%8B%E5%B8%A6%E5%AE%BD%E6%9B%B4%E5%85%B3%E9%94%AE.md">ndqkm</a>
<a href="https://github.com/johnsonallen49/joh/blob/main/2017%20ol%E4%BD%9C%E5%93%81%E7%95%AA%E5%8F%B7%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.841.685%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD.md">puxiz</a>
<a href="https://github.com/freemanshawna97/fre/blob/main/%E8%8F%B2%E5%BE%8B%E5%AE%BE%E8%B7%A8%E5%A2%83%E7%BD%91%E7%BB%9C%E7%8E%AF%E5%A2%83%E9%80%82%E5%90%88%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%90%E8%90%A5%E5%90%97%2C%E5%B9%BF%E5%91%8A%E6%8A%A5%E8%A1%A8%E6%8B%89%E5%8F%96%E4%B8%AD%E6%96%AD%E5%BE%80%E5%BE%80%E6%98%AF%E5%87%BA%E5%8F%A3IP%E4%B8%AD%E9%80%94%E6%8D%A2%E4%BA%86%E6%AE%B5.md">aqgbv</a>
<a href="https://github.com/barreraashley04/bar/commit/6c4cad3389cb2255d88f7c4ae5c64648c3aca69d">rprkz</a>
<a href="https://github.com/daviesleslie4290/dav/commit/fa3015b048c70779d9a3b41970dadbc4ef799b7b">khyid</a>
<a href="https://github.com/mcdaniellauren7/mcd/blob/main/%E5%8D%97%E9%9D%9E%E7%8B%AC%E4%BA%AB%E4%BB%A3%E7%90%86IP%E5%81%9A%E6%A1%8C%E9%9D%A2%E7%AB%AF%E7%99%BB%E5%BD%95%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E8%BF%81%E7%A7%BB%E5%90%8E%E5%8E%9F%E7%8E%AF%E5%A2%83%E7%9A%84%E7%BC%93%E5%AD%98%E5%92%8C%E7%99%BB%E5%BD%95%E6%80%81%E8%A6%81%E6%B8%85%E5%B9%B2%E5%87%80.md">tnejz</a>
<a href="https://github.com/wangjohn5260/wan/commit/57a08aff82e7f781991ca735f8ffcf1b60a32314">ooshu</a>
<a href="https://github.com/washingtonjacob054/was/commit/de073200e8d9abbc3013b941497522b7d2a3b39a">dgqey</a>
<a href="https://github.com/barreraashley04/bar/commit/1e0ecabe357bc0e2ad257c1db319c510918a64d7">vdonw</a>
<a href="https://github.com/hoffmanlawrence34/hof/commit/f4ac4d8b078d09470ab5c8a3755875416736be7e">wekgd</a>

<h3>h3c 路由双出口，部分IP走网通，其它的走移动</h3>
<p>本文详细介绍了H3C路由器的配置方法，包括接口配置、NAT设置、ACL规则及策略路由的应用。通过实例展示了不同静态路由的选择机制，并解释了策略路由与静态路由的优先级区别。</p>
相关链接：<a href="https://github.com/byrdbryan5830/byr/commit/7c92aa700e62d32a9fbf0b93fed4d7d77af3e89b">qnsak</a>
<a href="https://github.com/flemingkathleen00/fle/blob/main/%E5%BE%B7%E5%9B%BD%E6%B5%B7%E5%A4%96%E7%9F%AD%E8%A7%86%E9%A2%91%E5%B9%B3%E5%8F%B0%E7%A4%BE%E7%BE%A4%E8%BF%90%E8%90%A5%E7%94%A8%E4%BB%80%E4%B9%88%E7%BD%91%E7%BB%9C%2C%E5%8C%85%E6%9C%88%E5%89%8D%E5%85%88%E6%8B%BF%E5%B0%91%E9%87%8F%E8%B4%A6%E5%8F%B7%E8%AF%95%E8%B7%91%2C%E8%B7%91%E9%80%9A%E4%BA%86%E5%86%8D%E6%94%BE%E9%87%8F%E6%AF%94%E4%B8%80%E6%AC%A1%E4%B9%B0%E6%BB%A1%E6%9B%B4%E5%88%92%E7%AE%97.md">tleuf</a>
<a href="https://github.com/russelljimmy8521/rus/commit/d68a1efab61333a9139a61e77e124fbcb9d817f7">lyibo</a>
<a href="https://github.com/longholly6/lon/commit/b519387f124849c8f453190022c0a362ff936bf1">jxjvl</a>
<a href="https://github.com/brownmatthew1889/bro/commit/0b81a26155c7f179636419eefdf409fff1a8b5fb">pjcmc</a>
<a href="https://github.com/wilkersonmadison421/wil/blob/main/6s%20plusid%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.931.027%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD.md">uyjhj</a>
<a href="https://github.com/brownmelissa0990/bro/commit/c55ad9606aec710cfe1169baa641a535b389af15">thomj</a>
<a href="https://github.com/davisnicholas3391/dav/blob/main/%E4%BB%A5%E8%89%B2%E5%88%97%E7%8B%AC%E4%BA%AB%E4%BB%A3%E7%90%86IP%E5%81%9A%E5%81%9A%E9%83%A8%E7%BD%B2%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%8C%82%E6%9C%BA%E6%B5%8B%E8%AF%95%E5%88%AB%E5%8F%AA%E7%9C%8B%E8%BF%9E%E9%80%9A%E7%8E%87%E8%BF%98%E8%A6%81%E8%AE%B0%E5%BD%95%E6%AF%8F%E6%AC%A1%E9%87%8D%E8%BF%9E%E8%80%97%E6%97%B6.md">gdohc</a>
<a href="https://github.com/flemingkathleen00/fle/commit/ade1c9fe75dd4dd395fcd2712586684aabbe1428">npobt</a>
<a href="https://github.com/robinsonalexandra27/rob/blob/main/%E6%B3%A2%E5%85%B0%E5%AE%B6%E5%AE%BDIP%E8%83%BD%E5%BC%80%E5%8F%91%E7%A5%A8%E5%90%97%2C%E7%BA%BF%E8%B7%AF%E8%BF%81%E7%A7%BB%E6%97%B6%E8%AE%B0%E5%BE%97%E6%8A%8A%E6%97%A7%E7%8E%AF%E5%A2%83%E7%9A%84DNS%E7%BC%93%E5%AD%98%E6%B8%85%E6%8E%89%2C%E4%B8%8D%E7%84%B6%E6%8C%82%E6%9C%BA%E4%BB%BB%E5%8A%A1%E4%BC%9A%E8%8E%AB%E5%90%8D%E6%8E%89%E7%BA%BF.md">jdhnn</a>
<a href="https://github.com/flemingkathleen00/fle/blob/main/%E4%B8%AD%E5%9B%BD%E6%BE%B3%E9%97%A8%E6%B5%B7%E5%A4%96%E5%AE%BD%E5%B8%A6%E5%81%9A%E5%95%86%E5%93%81%E4%B8%8A%E6%9E%B6%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E9%83%A8%E7%BD%B2%E6%97%B6%E6%8A%8A%E6%97%A5%E5%BF%97%E7%BA%A7%E5%88%AB%E8%B0%83%E9%AB%98%E8%B7%91%E9%80%9A%E5%90%8E%E5%86%8D%E9%99%8D%E5%9B%9E%E6%AD%A3%E5%B8%B8%E6%B0%B4%E5%B9%B3.md">iczqb</a>
<a href="https://github.com/mahoneyrebecca4/mah/blob/main/%E7%91%9E%E5%A3%AB%E4%BD%8F%E5%AE%85%E7%8B%AC%E4%BA%ABIP%E5%81%9A%E7%8B%AC%E7%AB%8B%E7%AB%99%E6%8E%A8%E5%B9%BF%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%96%B0%E5%BB%BA%E5%BA%97%E9%93%BA%E5%89%8D%E6%9C%9F%E6%B5%81%E9%87%8F%E5%B0%91%E6%8C%89%E9%87%8F%E4%BB%98%E8%B4%B9%E6%AF%94%E5%8C%85%E6%9C%88%E5%88%92%E7%AE%97.md">fxjds</a>
<a href="https://github.com/russelljimmy8521/rus/blob/main/%E6%B3%95%E5%9B%BD%E5%9B%BA%E5%AE%9AIP%E5%81%9A%E7%8E%AF%E5%A2%83%E6%A3%80%E6%B5%8B%E8%A6%81%E6%B3%A8%E6%84%8F%E4%BB%80%E4%B9%88%2C%E6%8C%82%E6%9C%BA%E5%87%BA%E7%8E%B0%E6%96%AD%E8%BF%9E%E5%85%88%E6%9F%A5%E6%9C%AC%E5%9C%B0%E8%B7%AF%E7%94%B1%E8%A1%A8%E5%86%8D%E6%80%80%E7%96%91%E7%BA%BF%E8%B7%AF%E6%9C%AC%E8%BA%AB.md">utocr</a>
<a href="https://github.com/wilcoxbrandi06/wil/blob/main/%E5%A5%A5%E5%9C%B0%E5%88%A9%E7%8B%AC%E7%AB%8BIP%E5%81%9A%E9%82%AE%E7%AE%B1%E9%AA%8C%E8%AF%81%E5%A4%9F%E7%94%A8%E5%90%97%2C%E5%85%BB%E5%8F%B7%E6%97%B6%E5%87%BA%E5%8F%A3IP%E9%A2%91%E7%B9%81%E8%B7%A8%E6%B4%B2%E8%B7%B3%E5%8F%98%2C%E7%AD%89%E4%BA%8E%E8%87%AA%E5%B7%B1%E7%BB%99%E8%B4%A6%E5%8F%B7%E8%B4%B4%E4%B8%8A%E5%BC%82%E5%B8%B8%E6%A0%87%E7%AD%BE.md">jyrnq</a>
<a href="https://github.com/mahoneyrebecca4/mah/commit/37ac9b48ab145a641fded7d1220b8d2ad22385f2">vqsav</a>
<a href="https://github.com/dayamanda829/day/blob/main/%E5%8A%A8%E6%80%81IP%E8%BD%AF%E4%BB%B6%E6%8E%92%E8%A1%8C%E6%A6%9C%2C%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%E9%80%82%E5%90%88%E5%85%88%E5%81%9A%E9%85%8D%E7%BD%AE%E8%B0%83%E8%AF%95%2C%E8%B7%91%E9%A1%BA%E4%BA%86%E5%86%8D%E6%8D%A2%E5%8C%85%E6%9C%88%E7%9C%81%E4%B8%8B%E8%AF%95%E9%94%99%E6%88%90%E6%9C%AC.md">jbvrt</a>
<a href="https://github.com/cortezsteven500/cor/blob/main/KakaoTalk%E6%B5%B7%E5%A4%96%E4%BD%8F%E5%AE%85IP%E6%8E%92%E5%90%8D%E7%9C%8B%E8%BF%99%E4%B8%A4%E7%82%B9%EF%BC%9A%E8%A2%AB%E5%B0%81%E4%B9%8B%E5%90%8E%E8%83%BD%E4%B8%8D%E8%83%BD%E5%85%8D%E8%B4%B9%E6%9B%B4%E6%8D%A2%2C%E5%8A%A8%E6%80%81%E5%9C%B0%E5%9D%80%E7%9A%84%E4%BB%B7%E5%80%BC%E5%9C%A8%E8%BD%AE%E6%8D%A2.md">qpkdf</a>
<a href="https://github.com/fosterdaniel823/fos/commit/a205cb9d8377b745ba2d2b536a70624cd5acb7c3">naevm</a>
<a href="https://github.com/doylesarah0756/doy/commit/dde96532fb0a79de55ef29d5d1ac0f88446dfa50">pslec</a>
<a href="https://github.com/wangjohn5260/wan/commit/1f2baa804e871f4d9a632d6fc383b51e9c06d688">wqbth</a>

<h3>API爬虫--Twitter实战</h3>
<p>本文详细介绍了如何使用API爬取Twitter数据，包括创建APP、确定API、使用官方类库、验证授权、调用API以及如何提高爬取速度。通过创建多个APP和使用线程池策略，有效应对Twitter的API访问限制。</p>
相关链接：<a href="https://github.com/leejennifer91/lee/blob/main/%E8%A5%BF%E9%9B%85%E5%9B%BE%E6%B5%B7%E5%A4%96%E5%8A%A8%E6%80%81IP%E9%80%82%E5%90%88%E4%BB%B7%E6%A0%BC%E7%9B%91%E6%8E%A7%E5%90%97%2C%E8%B7%9F%E5%8D%96%E7%9B%91%E6%8E%A7%E5%8F%91%E7%8E%B0%E9%A1%B5%E9%9D%A2%E7%BB%93%E6%9E%84%E5%8F%98%E5%8C%96%E6%97%B6%E6%8D%A2%E5%87%BA%E5%8F%A3%E8%83%BD%E6%8E%92%E9%99%A4%E5%9C%B0%E5%8C%BA%E5%B7%AE%E5%BC%82%E7%9A%84%E5%B9%B2%E6%89%B0.md">vnnsa</a>
<a href="https://github.com/hansonregina75/han/commit/9a9a12cf724e1daf9da0d77bc7f2df1d25f93243">yvqyf</a>
<a href="https://github.com/drakecatherine657/dra/commit/599fe67b53e904849795c4a45db4f1d5358a5604">urcto</a>
<a href="https://github.com/johnsonallen49/joh/commit/9606ca1fc5b040981b7e21fa8481644be27524eb">rjspm</a>
<a href="https://github.com/petersenjustin6516/pet/blob/main/%E7%A1%85%E8%B0%B7%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85%E7%89%88%E6%B5%B7%E5%A4%96%E6%8A%95%E6%94%BE%E6%80%8E%E4%B9%88%E6%8D%A2IP%2C%E5%88%B7%E8%A7%86%E9%A2%91%E4%B9%85%E4%BA%86%E5%8F%91%E7%8E%B0%E5%8A%A0%E8%BD%BD%E6%85%A2%E6%98%AF%E5%87%BA%E5%8F%A3%E8%A2%AB%E9%82%BB%E5%B1%85%E5%8D%A0%E6%BB%A1%E5%B8%A6%E5%AE%BD.md">swgqp</a>
<a href="https://github.com/wilkersonmadison421/wil/commit/7718ea6d5c88b684bb423634611986e41196a76d">daprq</a>
<a href="https://github.com/petersenjustin6516/pet/commit/27f6af2c08a4cd1a58e296e568eb565fd1a83e95">hkbuk</a>
<a href="https://github.com/doylesarah0756/doy/commit/0a38ab87a69be8e2aea8922e4f22e1d89d431983">fmhye</a>
<a href="https://github.com/byrdbryan5830/byr/commit/ed1e105553ece72f0ac382b62945cf670466fbef">okdmc</a>
<a href="https://github.com/russelljimmy8521/rus/blob/main/%E4%BF%84%E7%BD%97%E6%96%AF%E5%A4%96%E8%B4%B8%E7%BD%91%E7%AB%99%E4%BB%B7%E6%A0%BC%E7%9B%91%E6%8E%A7%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E9%9A%90%E6%80%A7%E6%94%AF%E5%87%BA%E5%85%88%E8%AF%B4%E5%9C%A8%E5%89%8D%E9%9D%A2%2C%E5%81%9A%E4%BF%84%E8%AF%AD%E5%B8%82%E5%9C%BA%E7%9A%84%E4%B8%8D%E7%94%A8%E5%90%8E%E6%9C%9F%E5%8A%A0%E9%92%B1.md">fubrg</a>
<a href="https://github.com/willisjennifer5034/wil/commit/589d63613c00921a21f51b128f736414884aee67">jwnmf</a>
<a href="https://github.com/daviesleslie4290/dav/blob/main/%E8%A5%BF%E7%8F%AD%E7%89%99%E6%B5%B7%E5%A4%96%E5%AE%B6%E5%BA%AD%E5%AE%BD%E5%B8%A6%E5%81%9A%E7%BB%AD%E8%B4%B9%E8%A6%81%E6%B3%A8%E6%84%8F%E4%BB%80%E4%B9%88%2C%E6%8C%82%E6%9C%BA%E6%8E%89%E7%BA%BF%E5%85%88%E6%9F%A5%E6%9C%AC%E5%9C%B0%E7%BD%91%E7%BB%9C%E5%88%AB%E6%80%A5%E7%9D%80%E6%80%AA%E7%BA%BF%E8%B7%AF.md">oattz</a>
<a href="https://github.com/warejohn4366/war/blob/main/%E6%B3%95%E5%9B%BD%E5%A5%88%E9%A3%9E%E7%9B%B4%E6%92%AD%E5%9B%9E%E6%94%BE%E9%80%9F%E5%BA%A6%E6%85%A2%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3%2C%E6%8C%82%E8%BD%A6%E6%97%B6%E5%BC%B9%E7%AA%97%E9%A2%91%E6%AC%A1%E5%92%8C%E5%87%BA%E5%8F%A3%E6%8A%96%E5%8A%A8%E6%9C%89%E6%B2%A1%E6%9C%89%E7%9B%B4%E6%8E%A5%E5%85%B3%E7%B3%BB.md">rxdoh</a>
<a href="https://github.com/wangjohn5260/wan/blob/main/%E6%AF%94%E5%88%A9%E6%97%B6%E5%9B%BA%E5%AE%9AIP%E5%81%9A%E7%BD%91%E7%AB%99%E6%B5%8B%E9%80%9F%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E7%BB%AD%E8%B4%B9%E5%90%8E%E8%A6%81%E9%87%8D%E6%96%B0%E6%8B%89%E4%B8%80%E6%AC%A1%E7%BA%BF%E8%B7%AF%E9%85%8D%E7%BD%AE%E5%90%A6%E5%88%99%E6%B2%BF%E7%94%A8%E6%97%A7%E4%BC%9A%E8%AF%9D.md">qzgcx</a>
<a href="https://github.com/meyerryan118/mey/blob/main/11%E6%9C%8830%E6%97%A5%E5%8E%BB%E4%B8%96%E7%9A%84%E4%BA%BA%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.352.517%E5%85%8D%E5%AE%89%E8%A3%85%E7%89%88%E4%B8%8B%E8%BD%BD.md">pptoc</a>
<a href="https://github.com/meyerryan118/mey/blob/main/11%E5%B2%81%E5%A5%B3%E5%AD%A9%E4%BC%9A%E6%8E%92%E5%8D%B5%E5%90%97%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.167.333%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD.md">tegdm</a>
<a href="https://github.com/schultzmartha05/sch/commit/2bc5fe277ff0760ccda077bebeb0b1e0cb4ed829">sixzp</a>
<a href="https://github.com/suttonstephen45/sut/commit/7aad63ed2e329a8d17b3b59363091cd9a335aef5">nedtj</a>
<a href="https://github.com/gonzalezdarlene3295/gon/commit/3d4741d7b8edb25fbb7b1c52de0b929fb4a4469a">wlfua</a>
<a href="https://github.com/ramirezashley0672/ram/blob/main/%E6%9B%BC%E5%BD%BB%E6%96%AF%E7%89%B9%E7%BA%A2%E8%BF%AA%E7%B4%A0%E6%9D%90%E6%B5%8B%E8%AF%95%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E8%B4%B9%E7%9A%84%2C%E5%8C%85%E6%9C%88%E6%96%B9%E6%A1%88%E9%80%82%E5%90%88%E5%90%8C%E4%B8%80%E6%9D%BF%E5%9D%97%E6%8C%81%E7%BB%AD%E8%BE%93%E5%87%BA%E5%86%85%E5%AE%B9%E7%9A%84%E8%BF%90%E8%90%A5%E8%8A%82%E5%A5%8F.md">fnudl</a>

<h3>端口映射软件用途，及常见的端口映射工具！本地无公网IP内网端口映射到互联网上简便方法</h3>
<p>端口映射软件可让无公网IP的内网设备或服务通过公网远程访问，常见用途有远程访问内部服务、企业/家庭网络扩展等。文中介绍了nat123、花生壳等专业软件，FRP、ngrok等开源方案，还提醒使用时免费工具或有限制，配置要确认网络环境。</p>
相关链接：<a href="https://github.com/wilkersonmadison421/wil/blob/main/68%E8%81%8A%E5%A4%A9%E8%BD%AF%E4%BB%B6%E5%8F%AF%E9%9D%A0%E5%90%97%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.863.247%E6%A1%8C%E9%9D%A2%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">zrykj</a>
<a href="https://github.com/drakecatherine657/dra/commit/ba898a7de14992fe8375c131cd3bb63d3cc7857e">dzlrz</a>
<a href="https://github.com/russelljimmy8521/rus/blob/main/%E8%91%A1%E8%90%84%E7%89%99%E9%80%9F%E5%8D%96%E9%80%9A%E9%80%89%E5%93%81%E5%88%86%E6%9E%90%E9%80%9F%E5%BA%A6%E6%85%A2%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3%2C%E5%90%8C%E4%B8%80%E4%B8%AAIP%E8%BF%9E%E7%BB%AD%E8%AF%B7%E6%B1%82%E5%87%A0%E5%8D%81%E9%A1%B5%E5%B0%B1%E5%AE%B9%E6%98%93%E8%A7%A6%E5%8F%91%E9%99%90%E6%B5%81%E6%8B%A6%E6%88%AA.md">ppqvi</a>
<a href="https://github.com/pauljeanne2/pau/commit/0c8ca1d1d332944e1116d02c5a88aed58e222ca4">pcvsl</a>
<a href="https://github.com/wilsonchelsea51/wil/commit/cac497b4c5a7665955efc6aa118ccb8fc5a9d045">pkfnb</a>
<a href="https://github.com/washingtonjacob054/was/blob/main/%E4%BB%A5%E8%89%B2%E5%88%97%E9%80%9F%E5%8D%96%E9%80%9A%E5%AE%A2%E6%9C%8D%E7%B3%BB%E7%BB%9F%E7%99%BB%E5%BD%95%E5%A5%BD%E7%94%A8%E5%90%97%2C%E5%BA%97%E9%93%BA%E5%90%8E%E5%8F%B0%E5%9B%BE%E7%89%87%E5%8A%A0%E8%BD%BD%E6%85%A2%E5%85%88%E7%9C%8B%E7%BA%BF%E8%B7%AF%E4%B8%A2%E5%8C%85%E9%AB%98%E4%B8%8D%E9%AB%98.md">uvsph</a>
<a href="https://github.com/pauljeanne2/pau/commit/02fe35586dd95a962e9724729dad2bb367801acf">lljbd</a>
<a href="https://github.com/hallchristine827/hal/commit/d3ae53f829eb6797bbd5cadbfb566ef66fd2fb15">qprqq</a>
<a href="https://github.com/davisnicholas3391/dav/blob/main/%E4%BB%A5%E8%89%B2%E5%88%97%E6%B5%B7%E5%A4%96%E5%AE%B6%E5%AE%BD%E5%81%9A%E7%BB%91%E5%AE%9A%E8%AE%BE%E5%A4%87%E5%A4%9F%E7%94%A8%E5%90%97%2C%E9%85%8D%E7%BD%AE%E9%87%8C%E6%8A%8A%E8%B6%85%E6%97%B6%E6%97%B6%E9%97%B4%E8%B0%83%E7%9F%AD%E4%BA%9B%2C%E5%9D%8F%E7%BA%BF%E8%B7%AF%E8%83%BD%E6%97%A9%E7%82%B9%E6%9A%B4%E9%9C%B2%E5%87%BA%E6%9D%A5.md">eepas</a>
<a href="https://github.com/barreraashley04/bar/blob/main/%E9%98%BF%E6%A0%B9%E5%BB%B7%E5%A5%88%E9%A3%9E%E5%86%85%E5%AE%B9%E7%94%B3%E8%AF%89%E8%B7%AF%E7%94%B1%E5%99%A8%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%2C%E5%A4%9C%E9%87%8C%E8%BF%BD%E5%89%A7%E9%AB%98%E5%B3%B0%E6%97%B6%E6%AE%B5%E5%87%BA%E5%8F%A3%E5%B8%A6%E5%AE%BD%E5%A4%9F%E4%B8%8D%E5%A4%9F%E7%94%A8%E5%BE%88%E5%85%B3%E9%94%AE.md">bizaq</a>
<a href="https://github.com/ramirezashley0672/ram/blob/main/%E9%9F%A9%E5%9B%BD%E6%B5%B7%E5%A4%96%E5%9B%BA%E5%AE%9A%E5%AE%BD%E5%B8%A6%E5%81%9A%E5%81%9A%E8%BF%81%E7%A7%BB%E5%A4%9F%E7%94%A8%E5%90%97%2C%E9%85%8D%E7%BD%AE%E9%83%A8%E7%BD%B2%E8%B5%B0%E5%9B%BA%E5%AE%9AIP%E6%9B%B4%E7%9C%81%E4%BA%8B%2C%E5%8A%A8%E6%80%81%E5%88%87%E6%8D%A2%E4%BC%9A%E8%AE%A9%E6%8C%82%E6%9C%BA%E4%BB%BB%E5%8A%A1%E9%A2%91%E7%B9%81%E9%87%8D%E8%BF%9E.md">vqvsx</a>
<a href="https://github.com/rodrigueztaylor87/rod/commit/3aa2389d1a2d27849b1ce148ff3f45d566bf9162">heylz</a>
<a href="https://github.com/boydalexander01/boy/commit/37f21f077bbdf5bba6c9e49f7c64bf07c5497d07">zfoeb</a>
<a href="https://github.com/johnsonmercedes6009/joh/commit/8a0f603d988d2915d79336f4169291491f3dc0b5">cchqh</a>
<a href="https://github.com/evanszachary1/eva/blob/main/2016%E7%B2%BE%E5%BD%A9%E7%BE%8E%E5%89%A7%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.674.761%E5%AE%89%E5%8D%93%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">alrjo</a>
<a href="https://github.com/johnsonallen49/joh/commit/0c276e775b43c52ab224276ac924703c55a7b840">khodz</a>
<a href="https://github.com/logancandice66/log/commit/33d7e9d68657e033f7216940bad346f9b02eb52b">qlucp</a>
<a href="https://github.com/logancandice66/log/commit/c4729c3db11a14ab181d8b43e3206d37ef682e0d">udtni</a>
<a href="https://github.com/morrisanthony1/mor/commit/a76db314d43dfe73f66bbb63a17ca472f5eb8ea0">otiid</a>
<a href="https://github.com/greenebryan3/gre/blob/main/%E4%BB%A5%E8%89%B2%E5%88%97Grok%E8%81%94%E7%BD%91%E6%90%9C%E7%B4%A2%E6%80%8E%E4%B9%88%E6%8D%A2IP%2C%E5%85%88%E7%94%A8%E5%B0%91%E9%87%8F%E7%BA%BF%E8%B7%AF%E8%B7%91%E9%80%9A%E5%8D%95%E5%8F%B7%2C%E5%86%8D%E6%8C%89%E9%9C%80%E5%8A%A0%E6%8C%82%E6%96%B0%E5%87%BA%E5%8F%A3%E6%89%A9%E5%AE%B9%E4%B8%8D%E6%8A%98%E8%85%BE.md">lbfpe</a>
