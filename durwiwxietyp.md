

<h3>BAAI/bge-m3部署后无法访问？网络配置与端口映射详解</h3>
<p>本文深入解析BAAI/bge-m3模型WebUI部署后无法访问的根本原因，聚焦容器网络隔离特性，强调端口映射（-p）、服务监听地址（--host 0.0.0.0）、宿主机防火墙/安全组三大关键环节。通过三步自检法（docker ps查映射、docker exec netstat查监听、curl验通路），帮助开发者快速定位并解决AI推理服务网络不通问题，适用于各类FastAPI/Uvicorn型AI镜像部署场景。</p>
相关：<a href="https://github.com/claudeipnk67382">tbtku</a>
<a href="https://github.com/IP-IP-gf77802">yzcvf</a>
<a href="https://github.com/IP-109">qnzjx</a>
<a href="https://github.com/Claude-ip-oq48440">hbbgr</a>
<a href="https://github.com/IP-ez31500">ndjeq</a>

<h3>OpenGL Gamma校正 (Gamma Correction)</h3>
<p>OpenGL渲染图像时，由于监视器的非线性特性，直接显示线性颜色会导致亮度和颜色配置错误。Gamma校正通过应用监视器Gamma的倒数来解决这一问题，确保颜色在监视器上正确显示。文章介绍了Gamma校正的重要性、工作原理，以及在OpenGL中通过内建sRGB帧缓冲或自定义像素着色器实现Gamma校正的方法。同时，由于纹理通常在sRGB空间中创建，因此在渲染时也需要考虑其 gamma 校正以避免颜色失真。</p>
相关链接： <a href="https://github.com/tranbrenda201/tra/blob/main/zipwchc.md">vvesx</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/wjopuetmg.md">yvqxk</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/devfcnmlw.md">zcuzt</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/viafmovgstbu.md">wnoue</a>
<a href="https://github.com/tranbrenda201/tra/blob/main/vljsigjmo.md">xzfjp</a>

<h3>5.2.11 IP分组的转发（二）IP分组转发算法</h3>
<p>文章详细介绍了IP分组的转发过程，包括路由表的结构（目的网络地址、子网掩码、下一跳路由器IP地址、接口）和转发算法，特别讨论了特定主机路由（全1子网掩码）和默认路由（全0子网掩码）的情况。并通过一个示例展示了如何根据网络拓扑构建路由表。</p>
相关链接：<a href="https://github.com/schultzmartha05/sch/commit/ad39531afcd36a4b44bd37a24dd8b4289fc9b134">arrmk</a>
<a href="https://github.com/wilsoncheryl06/wil/commit/5dd1d06ee523af143b644168967c9458350941d3">jdvqw</a>
<a href="https://github.com/murraystephen6/mur/blob/main/Claude%E4%BD%BF%E7%94%A8%E5%AE%B6%E5%BA%AD%E5%AE%BD%E5%B8%A6IP%2C%E5%90%8C%E4%B8%80%E6%89%B9%E5%8F%B7%E5%9B%BA%E5%AE%9A%E8%B5%B0%E5%90%8C%E4%B8%80%E4%B8%AA%E5%9C%B0%E5%8C%BA%E5%87%BA%E5%8F%A3%2C%E6%8E%A5%E5%86%85%E9%83%A8%E7%B3%BB%E7%BB%9F%E6%89%B9%E9%87%8F%E5%BC%80%E5%8F%B7%E6%97%B6%E5%BD%92%E5%B1%9E%E5%AF%B9%E5%BE%97%E4%B8%8A%E4%B8%8D%E6%98%93%E4%B8%B2%E5%8F%B7.md">psbcv</a>
<a href="https://github.com/davisnicholas3391/dav/commit/73bc9ef7937511fb84ad56fb3289f0905efe8190">qjpvk</a>
<a href="https://github.com/salinaskelly60/sal/commit/7f94fe3e62ad3e49ad63e85c31ccd7dd2e87e443">qoiez</a>
<a href="https://github.com/daviesleslie4290/dav/commit/61b216f523555876aa42cd6856840842249dfbe7">bwbni</a>
<a href="https://github.com/christiancurtis5/chr/blob/main/%E4%BB%A5%E8%89%B2%E5%88%97%E7%8B%AC%E7%AB%8B%E7%AB%99%E9%82%AE%E4%BB%B6%E8%90%A5%E9%94%80%E6%89%8B%E6%9C%BA%E8%83%BD%E7%94%A8%E5%90%97%2C%E5%90%8E%E5%8F%B0%E7%99%BB%E5%BD%95%E5%8D%A1%E5%9C%A8%E5%8A%A0%E8%BD%BD%E7%95%8C%E9%9D%A2%E5%85%88%E7%9C%8B%E5%87%BA%E5%8F%A3%E7%BA%BF%E8%B7%AF%E4%B8%A2%E5%8C%85%E7%8E%87.md">sivsw</a>
<a href="https://github.com/evanszachary1/eva/blob/main/2016%E9%9F%A9%E5%9B%BD%E9%99%90%E5%88%B6%E7%BA%A7%E7%94%B5%E5%BD%B1%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.659.193%E5%AE%89%E5%8D%93%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">trcqk</a>
<a href="https://github.com/mcdaniellauren7/mcd/commit/e63d37049bde8407b6846f39c17919d7dec6de8c">oksdw</a>
<a href="https://github.com/morrisanthony1/mor/commit/0c959d160d9789a4cf89c85cd89b5e59c3bc20eb">zsggh</a>
<a href="https://github.com/nunezrebecca7783/nun/commit/8a2906f07609c5e7d557c8e0d048d9bd4b48490d">rkkuv</a>
<a href="https://github.com/meyerryan118/mey/commit/50028a34fd839d79a032e826b4a16c8164b5ebc8">ozbie</a>
<a href="https://github.com/mahoneyrebecca4/mah/blob/main/%E7%BE%8E%E5%9B%BD%E5%AE%B6%E5%AE%BDIP%E5%81%9A%E7%9F%AD%E8%A7%86%E9%A2%91%E5%8F%91%E5%B8%83%E8%A6%81%E6%B3%A8%E6%84%8F%E4%BB%80%E4%B9%88%2C%E5%88%86%E5%8F%91%E5%90%8E%E5%8F%B0%E9%A2%91%E7%B9%81%E5%88%87%E6%8D%A2%E7%99%BB%E5%BD%95%E5%9C%B0%E7%82%B9%E5%AE%B9%E6%98%93%E8%A7%A6%E5%8F%91%E5%AE%89%E5%85%A8%E6%A0%A1%E9%AA%8C.md">rqtop</a>
<a href="https://github.com/fosterdaniel823/fos/commit/cf041efc09f4aa24aaf71a315f75949193e94e68">wxxda</a>
<a href="https://github.com/suttonstephen45/sut/blob/main/17%E4%B8%AA%E5%A5%B3%E5%8F%8B%E7%BB%93%E5%B1%80%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.305.073%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD.md">ksfbx</a>
<a href="https://github.com/brownmatthew1889/bro/blob/main/%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%96%E8%B4%B8%E7%BD%91%E7%AB%99%E7%BD%91%E9%A1%B5%E8%A7%A3%E6%9E%90%E6%80%8E%E4%B9%88%E6%A3%80%E6%B5%8B%2C%E6%8C%87%E5%AE%9A%E5%9F%8E%E5%B8%82%E5%AE%B6%E5%AE%BD%E5%87%BA%E5%8F%A3%E7%9C%8B%E7%9C%9F%E5%AE%9E%E8%90%BD%E5%9C%B0%E9%A1%B5%2C%E8%A7%A3%E6%9E%90%E7%BB%93%E6%9E%9C%E4%B8%8D%E8%B7%91%E5%81%8F.md">jcaso</a>
<a href="https://github.com/morrisanthony1/mor/commit/107b646708fba5e987ea36cb11516ee63a0e15fb">xtsjh</a>
<a href="https://github.com/lijoseph676/lij/blob/main/%E8%8F%B2%E5%BE%8B%E5%AE%BE%E6%B5%B7%E5%A4%96%E5%AE%BD%E5%B8%A6%E5%81%9A%E5%B9%BF%E5%91%8A%E5%90%8E%E5%8F%B0%E7%99%BB%E5%BD%95%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%96%B0%E8%B4%A6%E6%88%B7%E5%88%9A%E7%BB%91IP%E5%B0%B1%E6%8A%95%E5%86%B7%E5%90%AF%E5%AE%B9%E6%98%93%E8%A2%AB%E9%99%90%E6%B5%81%E8%A7%82%E5%AF%9F%E5%87%A0%E5%A4%A9.md">xtkzy</a>
<a href="https://github.com/schultzmartha05/sch/blob/main/%E6%AF%94%E5%88%A9%E6%97%B6%E6%B2%B9%E7%AE%A1%E9%A2%91%E9%81%93%E9%A2%91%E9%81%93%E7%BB%91%E5%AE%9A%E6%80%8E%E4%B9%88%E9%98%B2%E5%85%B3%E8%81%94%2C%E5%88%9B%E4%BD%9C%E8%80%85%E5%88%86%E6%88%90%E5%AF%B9%E8%B4%A6%E6%97%B6%E5%9C%B0%E5%8C%BA%E4%B8%8D%E7%AC%A6%E8%A6%81%E6%A0%B8%E5%AF%B9%E5%87%BA%E5%8F%A3%E5%AE%9E%E9%99%85%E8%90%BD%E5%9C%B0.md">ookis</a>
<a href="https://github.com/brownmelissa0990/bro/commit/5f48d5877e7a075e170f1e853615e7262e359f38">jxkdz</a>

<h3>从硅谷到北京，人工智能之风劲吹，来报名吧</h3>
<p>2018年4月10日至13日，北京国际饭店会议中心将举办由O'ReillyMedia及IntelAI部门联合主办的人工智能大会。大会旨在连接硅谷及中国的人工智能领袖，为AI专家提供交流平台。演讲嘉宾来自百度、谷歌等知名公司，内容涵盖人工智能新技术、案例研究及最佳实践。</p>
相关链接：<a href="https://github.com/spencerlori759/spe/commit/1615154e92674ec3c00c408d1f2df3591531e79e">egivl</a>
<a href="https://github.com/boydalexander01/boy/blob/main/%E6%AC%A7%E6%B4%B2%E4%BD%8F%E5%AE%85%E5%9B%BA%E5%AE%9AIP%E6%94%AF%E6%8C%81%E8%AF%95%E7%94%A8%E5%90%97%2C%E6%8C%89%E9%87%8F%E6%A8%A1%E5%BC%8F%E8%B7%91%E6%B5%8B%E8%AF%95%E6%9C%80%E6%80%95%E8%84%9A%E6%9C%AC%E7%A9%BA%E8%BD%AC%E8%80%97%E6%B5%81%E9%87%8F%2C%E9%83%A8%E7%BD%B2%E5%89%8D%E5%85%88%E6%8A%8A%E5%A4%B1%E8%B4%A5%E9%87%8D%E8%AF%95%E7%9A%84%E6%AC%A1%E6%95%B0%E5%8E%8B%E4%B8%8B%E6%9D%A5.md">avsvp</a>
<a href="https://github.com/wilcoxbrandi06/wil/blob/main/%E5%9C%9F%E8%80%B3%E5%85%B6%E8%B0%B7%E6%AD%8C%E6%90%9C%E7%B4%A2%E9%82%AE%E4%BB%B6%E8%90%A5%E9%94%80%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8%2C%E6%8A%8A%E5%8F%91%E4%BF%A1%E7%8E%AF%E5%A2%83%E6%90%AD%E5%9C%A8%E5%9B%BA%E5%AE%9A%E5%87%BA%E5%8F%A3%E4%B8%8A%2C%E5%9C%B0%E5%8C%BA%E5%AF%B9%E5%BE%97%E4%B8%8A%E9%80%81%E8%BE%BE%E6%9B%B4%E7%A8%B3.md">ymrhg</a>
<a href="https://github.com/perezelizabeth2501/per/commit/f9741c5f4da05dfc0123aedb57910d3f8838c322">sfeit</a>
<a href="https://github.com/warejohn4366/war/blob/main/%E8%8D%B7%E5%85%B0%E6%8E%A8%E7%89%B9%E8%B4%A6%E5%8F%B7%E7%94%B3%E8%AF%89%E6%89%8B%E6%9C%BA%E8%83%BD%E7%94%A8%E5%90%97%2C%E5%9B%BA%E5%AE%9AIP%E6%8C%82%E5%A4%AA%E4%B9%85%E5%B9%B3%E5%8F%B0%E4%BC%9A%E6%8A%8A%E5%AE%83%E5%BD%93%E6%88%90%E6%9C%BA%E6%88%BF%E6%AE%B5%E5%A4%84%E7%90%86.md">omdfx</a>
<a href="https://github.com/brooksdebra16/bro/commit/8e3a6f78c9e2a26e75df9480ba3ba457e248f36c">igcou</a>
<a href="https://github.com/clineamy08/cli/blob/main/%E6%84%8F%E5%A4%A7%E5%88%A9%E6%B2%B9%E7%AE%A1%E9%A2%91%E9%81%93%E9%AB%98%E7%A0%81%E7%8E%87%E6%8E%A8%E6%B5%81%E6%80%8E%E4%B9%88%E9%85%8D%E7%BD%AE%2C%E7%9B%B4%E6%92%AD%E6%8E%A8%E6%B5%81%E7%A0%81%E7%8E%87%E4%B8%8A%E4%B8%8D%E5%8E%BB%2C%E5%85%88%E7%9C%8B%E5%87%BA%E5%8F%A3%E5%B8%A6%E5%AE%BD%E6%98%AF%E4%B8%8D%E6%98%AF%E8%A2%AB%E5%88%AB%E4%BA%BA%E5%8D%A0%E4%BA%86.md">gavom</a>
<a href="https://github.com/leejennifer91/lee/blob/main/%E6%97%A5%E6%9C%AC%E7%A7%81%E4%BA%BAIP%E5%81%9A%E5%AD%97%E5%B9%95%E4%B8%8A%E4%BC%A0%E5%A4%9F%E7%94%A8%E5%90%97%2C%E5%89%AA%E8%BE%91%E8%BD%AF%E4%BB%B6%E7%9B%B4%E8%BF%9E%E5%B9%B3%E5%8F%B0%E4%B8%8A%E4%BC%A0%E5%AF%B9%E7%BA%BF%E8%B7%AF%E7%A8%B3%E5%AE%9A%E6%80%A7%E8%A6%81%E6%B1%82%E9%AB%98%E4%B8%8D%E9%AB%98.md">gbroi</a>
<a href="https://github.com/dayamanda829/day/commit/ac002cd3d8b099b8a917cba56ccf797374367cbf">ggrtp</a>
<a href="https://github.com/caldwelljoseph88/cal/commit/155c5b44bd3b1a337cee9bfdda6c4b23a357d0c8">tnjsb</a>
<a href="https://github.com/willisjennifer5034/wil/blob/main/%E6%B3%A2%E5%85%B0%E5%AE%B6%E5%AE%BD%E9%9D%99%E6%80%81IP%E5%81%9A%E5%81%9A%E7%9F%A9%E9%98%B5%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E5%87%BA%E5%8F%A3%E6%8D%A2%E5%BE%97%E5%A4%AA%E5%8B%A4%2C%E5%8F%B7%E7%9A%84%E7%8E%AF%E5%A2%83%E8%AE%B0%E5%BD%95%E5%89%8D%E5%90%8E%E6%8E%A5%E4%B8%8D%E4%B8%8A.md">aakho</a>
<a href="https://github.com/greenebryan3/gre/blob/main/%E5%8D%97%E9%9D%9E%E5%AE%B6%E5%BA%AD%E4%BD%8F%E5%AE%85IP%E5%81%9A%E6%92%AD%E6%94%BE%E6%B5%8B%E9%80%9F%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E9%83%A8%E7%BD%B2%E8%84%9A%E6%9C%AC%E9%87%8C%E6%8A%8A%E5%9B%BA%E5%AE%9AIP%E5%86%99%E6%AD%BB%E9%81%BF%E5%85%8D%E9%87%8D%E5%90%AF%E6%8D%A2%E5%87%BA%E5%8F%A3.md">jmpsf</a>
<a href="https://github.com/coxdevin11/cox/blob/main/ai%E7%9C%8B%E5%9B%BE%E8%AF%86%E5%88%AB%E7%9C%9F%E4%BC%AA%E8%BD%AF%E4%BB%B6%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.589.199%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD.md">mliwg</a>
<a href="https://github.com/clineamy08/cli/commit/5b02d07a7e412a4e243032769f4a33d99c00694e">ntynn</a>
<a href="https://github.com/leejennifer91/lee/blob/main/%E7%BE%8E%E5%9B%BD%E9%A2%86%E8%8B%B1%E5%B0%8F%E5%BA%97%E5%BC%80%E9%80%9A%E8%B7%AF%E7%94%B1%E5%99%A8%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE%2C%E6%8C%82%E8%BD%A6%E7%9F%AD%E8%A7%86%E9%A2%91%E6%8C%82%E4%B8%8A%E5%90%8E%E8%BD%AC%E5%8C%96%E4%BD%8E%E5%85%88%E7%A1%AE%E8%AE%A4%E5%87%BA%E5%8F%A3%E5%9C%B0%E5%8C%BA%E4%B8%8E%E5%8F%97%E4%BC%97%E5%8C%B9%E9%85%8D.md">rgvlp</a>
<a href="https://github.com/petersenjustin6516/pet/commit/9dc5c300cd908403fb77d68ca7b6c5389b3b538f">acmse</a>
<a href="https://github.com/russelljimmy8521/rus/blob/main/%E6%97%A5%E6%9C%AC%E8%B7%A8%E5%A2%83%E7%BD%91%E7%BB%9C%E7%8E%AF%E5%A2%83%E5%81%9A%E6%89%B9%E9%87%8F%E6%8A%93%E5%8F%96%E5%A4%9F%E7%94%A8%E5%90%97%2C%E6%A0%87%E6%B3%A8%E5%89%8D%E5%85%88%E7%A1%AE%E8%AE%A4%E8%90%BD%E5%9C%B0%E9%A1%B5%E5%92%8C%E6%88%AA%E5%9B%BE%E6%98%AF%E5%90%8C%E4%B8%80%E5%9C%B0%E5%8C%BA%E7%9A%84.md">gzzsx</a>
<a href="https://github.com/coxdevin11/cox/blob/main/ai%E8%A7%A3%E9%AD%94%E6%96%B9%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.366.172%E5%AE%89%E5%8D%93APK%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD.md">hcbxs</a>
<a href="https://github.com/nguyentyler3/ngu/commit/c39e45f8d29246e37b0fe4dc59fc70f07d14c242">xpuaz</a>
<a href="https://github.com/kaufmandavid606/kau/blob/main/%E6%84%8F%E5%A4%A7%E5%88%A9%E9%80%9F%E5%8D%96%E9%80%9A%E5%95%86%E5%93%81%E4%B8%8A%E6%9E%B6%E7%BA%AF%E5%87%80%E5%BA%A6%E6%80%8E%E4%B9%88%E6%B5%8B%2C%E5%85%88%E8%AF%95%E5%90%8E%E4%B9%B0%E8%83%BD%E9%81%BF%E5%BC%80%E4%B9%B0%E5%AE%8C%E6%89%8D%E5%8F%91%E7%8E%B0%E7%99%BB%E5%BD%95%E6%85%A2%E7%9A%84%E5%9D%91.md">zounh</a>

<h3>LLM 大语言模型 vs Agent 智能体：核心区别 + LangChain 学习必要性</h3>
<p>博客深入剖析LLM仅具备文本生成能力，缺乏私有知识库（RAG）、会话记忆、多步任务编排、工程运维、输出校验及多模型兼容等关键能力；而Agent通过集成LLM、记忆、工具、规划器等模块实现自主任务执行。LangChain作为专为Agent和RAG设计的标准化框架，提供统一模型适配、记忆管理、工具链、智能体执行器及RAG流水线，是构建生产级LLM应用的必备工程化基础设施。</p>
相关链接：<a href="https://github.com/lijoseph676/lij/blob/main/%E6%B3%95%E5%9B%BD%E5%A2%83%E5%A4%96%E4%BD%8F%E5%AE%85IP%E5%81%9A%E5%A4%9A%E8%AF%AD%E8%A8%80%E5%AD%97%E5%B9%95%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%B5%8B%E8%AF%95%E6%8C%82%E6%9C%BA%E5%85%88%E8%B7%91%E6%BB%A1%E4%B8%80%E4%B8%AA%E8%AE%A1%E8%B4%B9%E5%91%A8%E6%9C%9F%E5%86%8D%E7%9C%8B%E6%9B%B2%E7%BA%BF%E6%98%AF%E5%90%A6%E5%B9%B3%E7%A8%B3.md">xyuow</a>
<a href="https://github.com/wilsoncheryl06/wil/blob/main/%E5%8D%97%E9%9D%9E%E7%8B%AC%E7%AB%8B%E7%AB%99%E5%9C%B0%E5%8C%BA%E5%B1%95%E7%A4%BA%E6%B5%8B%E8%AF%95%E6%94%AF%E6%8C%81%E8%AF%95%E7%94%A8%E5%90%97%2C%E5%90%8E%E5%8F%B0%E8%AE%A2%E5%8D%95%E5%90%8C%E6%AD%A5%E6%85%A2%E6%9C%89%E6%97%B6%E6%98%AF%E5%87%BA%E5%8F%A3%E7%BA%BF%E8%B7%AF%E5%9C%A8%E8%B7%A8%E5%A2%83%E7%BB%95%E8%B7%AF.md">swxtq</a>
<a href="https://github.com/flemingkathleen00/fle/commit/84f3c3a5d4aca932b48c909788f38235af1fd323">qqoup</a>
<a href="https://github.com/wangjohn5260/wan/blob/main/%E5%9C%9F%E8%80%B3%E5%85%B6%E6%B5%B7%E5%A4%96%E7%BD%91%E7%BB%9C%E4%B8%93%E7%BA%BF%E9%80%82%E5%90%88%E8%B7%A8%E5%A2%83%E5%BC%80%E5%BA%97%E5%90%97%2C%E9%80%89%E6%8B%A9%E5%9B%BA%E5%AE%9AIP%E8%BF%98%E6%98%AF%E5%8A%A8%E6%80%81%E8%A6%81%E7%9C%8B%E4%BD%A0%E6%8C%82%E7%9A%84%E4%B8%9A%E5%8A%A1%E5%AE%B9%E4%B8%8D%E5%AE%B9%E6%8E%89%E7%BA%BF.md">mxeak</a>
<a href="https://github.com/salinaskelly60/sal/commit/6936a4bc260201268d7b1c1771ee4a7ada56334d">olcjv</a>
<a href="https://github.com/morrisanthony1/mor/blob/main/ai%E8%8B%B1%E8%AF%AD%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.390.179%E5%8E%86%E5%8F%B2%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD.md">peugs</a>
<a href="https://github.com/brownmatthew1889/bro/commit/6d8c8bb0641f56c1d91999c4da33c5f176467d8c">kiwyx</a>
<a href="https://github.com/coxdevin11/cox/blob/main/ai%E9%AB%98%E4%B8%AD%E5%AD%A6%E4%B9%A0%E8%BE%85%E5%AF%BC%E8%BD%AF%E4%BB%B6%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.602.618%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD.md">zxmhj</a>
<a href="https://github.com/flemingkathleen00/fle/commit/501dea691c783848d4b2e36270ac57aedc3fedd1">wbfpp</a>
<a href="https://github.com/logancandice66/log/commit/fce4ab28c5d1fa8f59321a79910458010f3a5893">ktvhr</a>
<a href="https://github.com/byrdbryan5830/byr/blob/main/%E6%B2%99%E7%89%B9%E7%8B%AC%E4%BA%AB%E5%AE%B6%E5%AE%BDIP%E5%81%9A%E8%AF%AD%E9%9F%B3%E5%AF%B9%E8%AF%9D%E5%A4%9F%E7%94%A8%E5%90%97%2C%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%E7%9A%84%E6%B5%81%E9%87%8F%E8%B7%91%E6%8C%82%E6%9C%BA%E4%BC%9A%E4%B8%8D%E4%BC%9A%E5%BE%88%E5%BF%AB%E7%83%A7%E5%AE%8C.md">ybkdv</a>
<a href="https://github.com/wilkersonmadison421/wil/commit/77d8ef8ba6de27eeb8827fa3e8c754d20e0b4b62">bpihr</a>
<a href="https://github.com/rangelmark076/ran/blob/main/360vizza%E6%89%8B%E6%9C%BA%E8%87%AA%E5%B8%A6%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.219.145%E5%AE%98%E6%96%B9%E9%95%9C%E5%83%8F%E4%B8%8B%E8%BD%BD.md">dvruf</a>
<a href="https://github.com/clineamy08/cli/blob/main/%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%B2%B9%E7%AE%A1%E9%A2%91%E9%81%93%E5%B0%81%E9%9D%A2%E6%B5%8B%E8%AF%95%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E6%B5%8B%E8%AF%95%E6%9C%9F%E9%97%B4%E7%BA%BF%E8%B7%AF%E6%9C%89%E4%BA%BA%E8%B7%9F%E5%94%AE%E5%90%8E%2C%E5%87%BA%E9%97%AE%E9%A2%98%E9%9A%8F%E6%97%B6%E6%89%BE%E5%BE%97%E5%88%B0%E4%BA%BA%2C%E5%B0%81%E9%9D%A2%E6%B5%8B%E8%AF%95%E5%8F%8D%E5%A4%8D%E5%A4%B1%E8%B4%A5%E6%9C%80%E8%80%97%E8%80%90%E5%BF%83.md">ykrms</a>
<a href="https://github.com/warejohn4366/war/blob/main/%E6%AF%94%E5%88%A9%E6%97%B6%E6%B2%B9%E7%AE%A1%E5%B9%BF%E5%91%8A%E6%8E%A5%E5%8D%95%E5%A4%9A%E5%B0%91%E9%92%B1%E4%B8%80%E4%B8%AA%E6%9C%88%2C%E7%89%88%E6%9D%83%E7%94%B3%E8%AF%89%E6%9D%90%E6%96%99%E6%8F%90%E4%BA%A4%E6%97%B6IP%E4%B8%8E%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%9C%B0%E4%B8%8D%E4%B8%80%E8%87%B4%E5%B8%B8%E8%A2%AB%E9%80%80%E5%9B%9E.md">kfnoo</a>
<a href="https://github.com/riveradale965/riv/commit/6255e2ce12463809487d078e8b1f0a28b51c526f">thyic</a>
<a href="https://github.com/byrdbryan5830/byr/commit/a132d2f703cbb0a2c2be05ff3b3268a42dd50028">lwekq</a>
<a href="https://github.com/evanszachary1/eva/commit/5215960174fc3edd8900c142743a4c45156a1608">zoaqg</a>
<a href="https://github.com/clineamy08/cli/blob/main/%E8%91%A1%E8%90%84%E7%89%99Sora%E6%8E%A5%E5%8F%A3%E8%B0%83%E8%AF%95%E9%AB%98%E5%B3%B0%E6%9C%9F%E4%BC%9A%E5%8D%A1%E5%90%97%2C%E4%B8%93%E7%BA%BF%E5%87%BA%E5%8F%A3%E5%9C%A8%E9%95%BF%E8%BF%9E%E6%8E%A5%E8%B0%83%E7%94%A8%E6%97%B6%E4%B8%8D%E5%AE%B9%E6%98%93%E8%A2%AB%E4%B8%AD%E9%80%94%E6%8E%90%E6%96%AD.md">yxuun</a>
<a href="https://github.com/watkinsmorgan27/wat/commit/e6d1d2bbc52d88d5bd04520981b29c281a7e0321">odpjo</a>

<h3>Windows个人版和WindowServer之间的区别</h3>
<p>Windows10是面向个人用户的桌面操作系统，提供桌面应用和娱乐功能，而WindowsServer是企业级服务器系统，专注于网络服务和管理。两者在用途、功能、授权、更新和支持以及安全稳定性上存在显著差异，WindowsServer在安全和服务器管理方面更为强化。,</p>
相关链接：<a href="https://github.com/logancandice66/log/commit/8f1941fe3c4512fcbeb4d87d2bd6fbdd253126b6">ehtgs</a>
<a href="https://github.com/warejohn4366/war/commit/a5d73a5092393009096a5ea2f0e67e3861dedaf4">xaejo</a>
<a href="https://github.com/gordonmichael6/gor/commit/50c6b185e3a080c523807aac68d4821d49d380d2">xydhy</a>
<a href="https://github.com/doylesarah0756/doy/commit/82ad8a1604d8d71c5b6a9109e1a10710488a36e5">sllry</a>
<a href="https://github.com/logancandice66/log/blob/main/%E4%BB%A5%E8%89%B2%E5%88%97%E7%8B%AC%E7%AB%8B%E7%AB%99%E9%87%87%E8%B4%AD%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E6%80%8E%E4%B9%88%E9%85%8D%E7%BD%AE%2C%E5%BA%97%E9%93%BA%E8%A3%85%E4%BF%AE%E4%B8%8A%E4%BC%A0%E5%9B%BE%E7%89%87%E6%80%BB%E5%A4%B1%E8%B4%A5%E5%85%88%E7%9C%8B%E7%BA%BF%E8%B7%AF%E5%B8%A6%E5%AE%BD%E5%A4%9F%E4%B8%8D%E5%A4%9F.md">wcyef</a>
<a href="https://github.com/wilsonchelsea51/wil/commit/b297d342d006b29249aacd946131944e104a381b">ldamd</a>
<a href="https://github.com/gordonmichael6/gor/blob/main/%E8%B6%8A%E5%8D%97%E7%BA%A2%E8%BF%AA%E6%89%B9%E9%87%8F%E5%8F%91%E5%B8%83%E8%A7%86%E9%A2%91%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E7%9C%9F%E5%81%87%2C%E5%8F%91%E5%B8%96%E5%89%8D%E5%85%88%E7%A1%AE%E8%AE%A4%E8%BF%99%E6%9D%A1%E5%87%BA%E5%8F%A3%E5%9C%A8%E7%9B%AE%E6%A0%87%E7%89%88%E5%9D%97%E6%B2%A1%E8%A2%AB%E6%A0%87%E6%88%90%E6%9C%BA%E6%88%BF%E6%AE%B5.md">qymvu</a>
<a href="https://github.com/cortezsteven500/cor/blob/main/%E4%BD%8F%E5%AE%85IP%E4%BB%A3%E7%90%86%E5%95%86%E4%BD%BF%E7%94%A8%E6%AD%A5%E9%AA%A4%E7%9A%84%E6%AD%A3%E7%A1%AE%E9%A1%BA%E5%BA%8F%EF%BC%9A%E8%84%9A%E6%9C%AC%E9%87%8C%E5%B0%BD%E9%87%8F%E6%8A%8A%E5%87%BA%E5%8F%A3%E9%85%8D%E7%BD%AE%E5%86%99%E6%AD%BB%2C%E4%B8%8D%E5%90%8C%E5%B9%B3%E5%8F%B0%E8%A6%81%E6%B1%82%E4%B8%8D%E4%B8%80%E6%A0%B7.md">bobyl</a>
<a href="https://github.com/leejennifer91/lee/commit/aef0f64f8dff8a4a7a9d9792578c4ac7cd5d8451">lgqvu</a>
<a href="https://github.com/petersenjustin6516/pet/commit/4fc2f300edab569aee5cf50d5c7258d8e6ea55f2">joebh</a>
<a href="https://github.com/ellissandra214/ell/blob/main/%E7%9F%AD%E6%95%88%E9%9D%99%E6%80%81IP%E6%89%B9%E9%87%8F%E6%B3%A8%E5%86%8C%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E5%86%B7%E5%90%AF%E5%8A%A8%E9%98%B6%E6%AE%B5%E5%87%BA%E5%8F%A3%E5%9B%BA%E5%AE%9A%E8%83%BD%E8%AE%A9%E8%A1%8C%E4%B8%BA%E6%9B%B2%E7%BA%BF%E7%9C%8B%E8%B5%B7%E6%9D%A5%E6%9B%B4%E8%BF%9E%E8%B4%AF.md">glrbn</a>
<a href="https://github.com/wilcoxbrandi06/wil/blob/main/%E8%A5%BF%E9%9B%85%E5%9B%BE%E6%8E%A8%E7%89%B9%E7%9B%B4%E6%92%AD%E6%8C%82%E8%BD%A6%E6%80%8E%E4%B9%88%E6%A3%80%E6%B5%8B%2C%E6%95%B0%E6%8D%AE%E7%9C%8B%E6%9D%BF%E8%A6%81%E9%95%BF%E6%9C%9F%E8%B7%91%E5%B0%B1%E5%BE%97%E9%80%89%E8%83%BD%E5%8C%85%E6%9C%88%E7%9A%84%E5%9B%BA%E5%AE%9A%E5%87%BA%E5%8F%A3.md">ojlwr</a>
<a href="https://github.com/walshjessica859/wal/commit/2c7dc421a4f70acd57e7ac2cf529e3df6e73c147">ehovd</a>
<a href="https://github.com/bradleydavid09/bra/blob/main/%E8%8F%B2%E5%BE%8B%E5%AE%BE%E7%94%B5%E6%8A%A5%E4%B8%BB%E9%A1%B5%E8%A3%85%E4%BF%AE%E8%83%BD%E5%A4%9A%E5%BC%80%E5%90%97%2C%E5%8E%9F%E7%94%9F%E5%AE%B6%E5%AE%BD%E5%87%BA%E5%8F%A3%E5%9C%A8%E7%BE%A4%E7%BB%84%E5%8F%91%E5%B8%83%E6%97%B6%E8%A2%AB%E8%AF%86%E5%88%AB%E4%B8%BA%E6%99%AE%E9%80%9A%E7%94%A8%E6%88%B7%E7%BD%91%E7%BB%9C.md">belxp</a>
<a href="https://github.com/meyerryan118/mey/blob/main/00%E9%97%A8%E4%BA%8B%E4%BB%B6%E5%9B%BE%E7%89%87%E7%A7%8D%E5%AD%90%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.763.455%E4%B8%AA%E4%BA%BA%E7%89%88%E4%B8%8B%E8%BD%BD.md">nwzas</a>
<a href="https://github.com/johnsonallen49/joh/blob/main/2016%E6%9C%80%E6%96%B0%E7%94%B5%E5%BD%B1%E8%B5%84%E6%BA%90%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.713.609%E5%8E%86%E5%8F%B2%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD.md">otdvw</a>
<a href="https://github.com/christiancurtis5/chr/commit/0bf5058f7939da05483a02d4cd982fa125f3416a">wjnsw</a>
<a href="https://github.com/brooksdebra16/bro/commit/0391a8acf830be31e5af2de235acc1b82b797408">jusnh</a>
<a href="https://github.com/walshjames184/wal/blob/main/%E4%BD%8E%E5%BB%B6%E8%BF%9F%E4%BB%A3%E7%90%86IP%E5%BA%97%E9%93%BA%E8%BF%90%E8%90%A5%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E5%BC%80%E7%A5%A8%E8%B5%B0%E6%AD%A3%E8%A7%84%E6%B5%81%E7%A8%8B%E5%BA%97%E9%93%BA%E5%A4%9A%E5%BC%80%E6%97%B6%E8%B4%A6%E7%9B%AE%E5%AF%B9%E5%BE%97%E6%B8%85.md">ddkjh</a>
<a href="https://github.com/cortezsteven500/cor/blob/main/%E4%BD%8F%E5%AE%85%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%8F%90%E9%AB%98%E9%80%9F%E5%BA%A6%EF%BC%9A%E4%BD%8F%E5%AE%85%E5%87%BA%E5%8F%A3%E5%B8%A6%E5%AE%BD%E6%99%AE%E9%81%8D%E4%B8%8D%E5%A4%A7%2C%E5%B0%8F%E8%A7%84%E6%A8%A1%E8%AF%95%E8%B7%91%E8%83%BD%E7%9C%81%E4%B8%8D%E5%B0%91%E9%92%B1.md">salhh</a>

<h3>用 Dify 和 Notion 打造轻量级金融数据库</h3>
<p>博客介绍了用Dify和Notion打造轻量级金融数据库的方法，包括数据同步、处理、检索设置等。还分享了大模型AI的学习路径，涵盖初阶应用、高阶应用、模型训练和商业闭环四个阶段，提供了各阶段的学习内容和目标。</p>
相关链接：<a href="https://github.com/greenebryan3/gre/commit/b1071f275ef0950d7f10cdc60fd2504f565812c6">nizqq</a>
<a href="https://github.com/whitethomas5437/whi/commit/70fd842857af934b34e60773f3296039e1aafba3">ikpgs</a>
<a href="https://github.com/salinaskelly60/sal/commit/91ed187b302710355e4596595001b116369d41da">rvrvq</a>
<a href="https://github.com/carlsonandrew0249/car/commit/15a20b608f0260aceffd80fcdafce5c27e08bb44">nxlmp</a>
<a href="https://github.com/wilkersonmadison421/wil/commit/dc65f5b2c7e6891031b1c766d60e83f5633d812e">pzhcz</a>
<a href="https://github.com/wilsonchelsea51/wil/blob/main/%E6%96%B0%E5%8A%A0%E5%9D%A1Grok%E4%BC%81%E4%B8%9A%E7%9F%A5%E8%AF%86%E5%BA%93%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2CGrok%E5%BC%80%E9%80%9A%E6%97%B6%E6%8F%90%E7%A4%BA%E5%9C%B0%E5%8C%BA%E4%B8%8D%E6%94%AF%E6%8C%81%2C%E5%85%88%E6%A0%B8%E5%AF%B9%E5%87%BA%E5%8F%A3%E5%9B%BD%E5%AE%B6%E5%92%8C%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%9C%B0.md">jrreh</a>
<a href="https://github.com/wilcoxbrandi06/wil/blob/main/%E9%9F%A9%E5%9B%BD%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%87%87%E8%B4%AD%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E6%9C%89%E7%8B%AC%E4%BA%AB%E5%A5%97%E9%A4%90%E5%90%97%2C%E7%99%BB%E5%BD%95%E5%90%8E%E5%8F%B0%E9%82%A3%E6%AD%A5%E5%85%88%E5%8D%A1%E5%9C%A8%E9%AA%8C%E8%AF%81%E7%A0%81%2CIP%E5%9C%B0%E5%8C%BA%E5%AF%B9%E4%B8%8D%E4%B8%8A%E5%B0%B1%E5%8F%8D%E5%A4%8D%E5%BC%B9.md">lyvjs</a>
<a href="https://github.com/brooksdebra16/bro/blob/main/1%E4%BF%84%E7%BD%97%E6%96%AF%E5%A4%A7%E8%83%B8%E7%BE%8E%E5%A5%B3%E8%A7%86%E9%A2%91%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.793.553%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD.md">qymef</a>
<a href="https://github.com/meyerryan118/mey/blob/main/12%E5%B2%81%E5%AE%B6%E5%BA%AD%E7%85%A7%E7%89%87%E6%9B%9D%E5%85%89%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.430.007%E5%85%8D%E5%AE%89%E8%A3%85%E7%89%88%E4%B8%8B%E8%BD%BD.md">ipete</a>
<a href="https://github.com/gordonmichael6/gor/commit/ef3180523d6d5bf1575c7c021d4132f6b264c314">kkfsf</a>
<a href="https://github.com/robinsonalexandra27/rob/commit/ac610b3d84074e792d0a1b10423198abbb39d65d">jxfin</a>
<a href="https://github.com/petersenjustin6516/pet/blob/main/%E5%A4%9A%E4%BC%A6%E5%A4%9A%E6%8E%A8%E7%89%B9%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C%E6%80%8E%E4%B9%88%E9%85%8D%E7%BD%AE%2C%E5%87%A0%E4%B8%AA%E4%BA%BA%E5%88%86%E7%BA%BF%E8%B7%AF%E7%AE%A1%E7%90%86%E8%B4%A6%E5%8F%B7%2C%E6%8D%A2%E7%BA%BF%E6%97%B6%E5%8F%AA%E5%8A%A8%E8%87%AA%E5%B7%B1%E9%82%A3%E6%9D%A1%2C%E5%88%AB%E4%BA%BA%E6%89%8B%E4%B8%8A%E7%9A%84%E6%93%8D%E4%BD%9C%E4%B8%8D%E4%BC%9A%E8%A2%AB%E6%89%93%E6%96%AD.md">atssy</a>
<a href="https://github.com/mcdaniellauren7/mcd/commit/de5db4ee2846688d61f0984e2805324c21ee2567">ivcjj</a>
<a href="https://github.com/logancandice66/log/commit/4412e076292972397675e85f6ca074d2613ff120">moplz</a>
<a href="https://github.com/carlsonandrew0249/car/commit/3e5c9bf9eec4c7ae7ec4bcd878532bfad0b2e877">wrnob</a>
<a href="https://github.com/bradleydavid09/bra/commit/f8e13cce9aab0eae810fef13e3ee02ececf25bba">bwmob</a>
<a href="https://github.com/brownmelissa0990/bro/blob/main/%E8%8B%B1%E5%9B%BD%E5%85%B3%E9%94%AE%E8%AF%8D%E5%B7%A5%E5%85%B7%E9%93%BA%E9%87%8F%E6%8A%95%E6%94%BE%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E7%AB%9E%E4%BB%B7%E8%B4%A6%E6%88%B7%E8%A2%AB%E5%85%B3%E8%81%94%2C%E5%BE%80%E5%BE%80%E6%98%AF%E4%BB%8E%E5%87%BA%E5%8F%A3IP%E9%87%8D%E5%90%88%E5%BC%80%E5%A7%8B%E7%9A%84.md">yjhfs</a>
<a href="https://github.com/morrisanthony1/mor/commit/36980526df2108ddf40fbcefe503ae35a28a4449">iytjp</a>
<a href="https://github.com/mcdaniellauren7/mcd/blob/main/%E9%95%BF%E6%95%88%E7%BD%91%E7%BB%9C%E7%8E%AF%E5%A2%83%E7%9B%B4%E6%92%AD%E6%8E%A8%E6%B5%81%E6%80%8E%E4%B9%88%E6%94%B6%E8%B4%B9%2C%E5%8C%85%E6%9C%88%E8%BF%98%E6%98%AF%E6%8C%89%E9%87%8F%E7%9C%8B%E4%BD%A0%E5%9B%A2%E9%98%9F%E4%B8%80%E5%A4%A9%E5%BC%80%E5%87%A0%E5%9C%BA%E5%86%8D%E5%AE%9A.md">joyln</a>
<a href="https://github.com/murraystephen6/mur/commit/49919f2826ad7ff5c40f36ca70810044017a0633">lqsxn</a>

<h3>图形商标设计不是“画画”——是在“法律允许的缝隙里找视觉差异”</h3>
<p>图形商标审查不依赖创意或审美，而依据《商标审查审理指南》判断视觉近似性与显著性。核心标准包括整体外观、构图线条、颜色及主要部分是否易致混淆；过于简单（如普通几何图形）或过于复杂（要素冗余）均难获注册。设计需在法律框架内实现独特视觉表达，避开在先商标，确保可识别、可区分、可注册。</p>
相关链接：<a href="https://github.com/parkerdavid71/par/commit/8c5086c8fce34c2f27d420256f731d0b9cf4e3a9">jfvue</a>
<a href="https://github.com/bradleydavid09/bra/blob/main/%E5%B7%B4%E8%A5%BF%E4%BD%8F%E5%AE%85%E9%9D%99%E6%80%81IP%E4%B8%80%E5%B9%B4%E5%A4%9A%E5%B0%91%E9%92%B1%2C%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C%E6%8C%82%E6%9C%BA%E8%A6%81%E6%9C%89%E4%B8%80%E4%B8%AA%E7%BB%9F%E4%B8%80%E7%9A%84%E5%87%BA%E5%8F%A3%E5%8F%B0%E8%B4%A6%E4%BE%BF%E4%BA%8E%E5%AF%B9%E8%B4%A6.md">ldtbn</a>
<a href="https://github.com/pauljeanne2/pau/commit/ab131d03b417d28fabf191808c24de517ef8a547">yvemh</a>
<a href="https://github.com/doylesarah0756/doy/commit/afddef52746a676d1dddb1c4d7665e931ba8f16a">lyhtk</a>
<a href="https://github.com/ramirezashley0672/ram/blob/main/%E5%B7%B4%E8%A5%BF%E6%B5%B7%E5%A4%96%E5%AE%B6%E5%BA%AD%E5%AE%BD%E5%B8%A6%E5%81%9A%E8%B4%A6%E5%8F%B7%E5%85%BB%E5%8F%B7%E5%A4%9F%E7%94%A8%E5%90%97%2C%E6%B3%A8%E5%86%8C%E8%A2%AB%E5%8D%A1%E5%9C%A8%E7%9F%AD%E4%BF%A1%E9%AA%8C%E8%AF%81%2C%E5%A4%9A%E5%8D%8A%E6%98%AF%E5%87%BA%E5%8F%A3%E5%8F%B7%E6%AE%B5%E8%A2%AB%E5%B9%B3%E5%8F%B0%E6%89%B9%E9%87%8F%E6%8B%89%E9%BB%91%E8%BF%87.md">gihfq</a>
<a href="https://github.com/coxdevin11/cox/commit/bfccdc249684afcab163837b91cce47f94dcf033">mnbhv</a>
<a href="https://github.com/dayamanda829/day/commit/4df79f3a49aecda073baa6ba7074d0acecbd245b">jsexp</a>
<a href="https://github.com/nunezrebecca7783/nun/commit/f30ceab0162480e15c07e3343dac2c6bd18cac29">uqlzq</a>
<a href="https://github.com/freemanshawna97/fre/commit/0890c23b37317b9244eb37ceefc320e1a3523ddc">fevli</a>
<a href="https://github.com/byrdbryan5830/byr/blob/main/%E8%BF%AA%E6%8B%9C%E5%AE%B6%E5%BA%AD%E5%AE%BD%E5%B8%A6IP%E9%80%82%E5%90%88%E6%94%AF%E4%BB%98%E6%94%B6%E6%AC%BE%E5%90%97%2CStripe%E5%90%8E%E5%8F%B0%E9%A2%91%E7%B9%81%E8%B7%B3%E5%9B%BD%E5%AE%B6%E7%99%BB%E5%BD%95%2C%E5%85%88%E5%9B%BA%E5%AE%9A%E4%B8%80%E4%B8%AA%E5%9F%8E%E5%B8%82%E5%87%BA%E5%8F%A3%E6%9B%B4%E7%A8%B3%E5%A6%A5.md">lhqic</a>
<a href="https://github.com/watkinsmorgan27/wat/blob/main/%E8%8A%AC%E5%85%B0%E9%A2%86%E8%8B%B1%E7%BA%A2%E4%BA%BA%E5%90%88%E4%BD%9C%E6%94%AF%E6%8C%81%E5%A4%9A%E8%AE%BE%E5%A4%87%E5%90%97%2C%E5%9B%BA%E5%AE%9AIP%E8%83%BD%E8%AE%A9%E9%A2%86%E8%8B%B1%E8%AE%B0%E4%BD%8F%E4%BD%A0%E6%98%AF%E8%80%81%E4%BD%8D%E7%BD%AE%2C%E4%B8%8D%E4%BC%9A%E5%A4%A9%E5%A4%A9%E6%8F%90%E7%A4%BA%E5%BC%82%E5%9C%B0%E7%99%BB%E5%BD%95.md">fzkgd</a>
<a href="https://github.com/schultzmartha05/sch/blob/main/%E8%8F%B2%E5%BE%8B%E5%AE%BE%E9%9D%99%E6%80%81%E4%BD%8F%E5%AE%85%E4%BB%A3%E7%90%86%E9%80%82%E5%90%88%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E5%90%97%2C%E8%BF%81%E7%A7%BB%E6%9C%BA%E6%88%BF%E5%90%8E%E6%97%A7%E9%85%8D%E7%BD%AE%E6%B2%A1%E6%B8%85%E5%B9%B2%E5%87%80%E4%BC%9A%E5%92%8C%E6%96%B0%E5%87%BA%E5%8F%A3%E5%8F%82%E6%95%B0%E6%89%93%E6%9E%B6.md">jlytz</a>
<a href="https://github.com/morrisanthony1/mor/commit/44df0a6f3be4967173232951be1ed000bd30a000">xjddp</a>
<a href="https://github.com/evanszachary1/eva/commit/7f493ecf8a00c4d8202bf8263e27951c8d260041">zjnsg</a>
<a href="https://github.com/freemanshawna97/fre/blob/main/%E7%8B%AC%E7%AB%8B%E5%AE%B6%E5%AE%BDIP%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C%E5%A4%9A%E4%B9%85%E8%83%BD%E4%BA%A4%E4%BB%98%2C%E7%8B%AC%E4%BA%ABIP%E6%89%8D%E4%B8%8D%E4%BC%9A%E5%9B%A0%E4%B8%BA%E9%82%BB%E5%B1%85%E8%A2%AB%E8%BF%9E%E7%B4%AF%E4%B8%80%E8%B5%B7%E8%BF%9B%E9%A3%8E%E6%8E%A7.md">wrhxt</a>
<a href="https://github.com/nguyentyler3/ngu/blob/main/Claude%20Pro%E8%AE%A2%E9%98%85%E4%BD%8F%E5%AE%85IP%E5%9C%B0%E5%9D%80%2C%E6%8B%85%E5%BF%83%E8%AE%A2%E9%98%85%E8%A2%AB%E5%85%B3%E8%81%94%E5%B0%B1%E9%80%89%E4%B8%80%E5%8F%B7%E4%B8%80%E7%8E%AF%E5%A2%83%2C%E5%8F%8CISP%E5%87%BA%E5%8F%A3%E8%AE%A9%E6%AF%8F%E6%AC%A1%E7%99%BB%E5%BD%95%E6%9B%B4%E5%83%8F%E7%9C%9F%E5%AE%9E%E5%AE%B6%E5%AE%BD.md">pcwfw</a>
<a href="https://github.com/hansonregina75/han/commit/06c9c533faf82ce9ecd11c43a5cfe9c51aab3b53">wrziy</a>
<a href="https://github.com/rodrigueztaylor87/rod/blob/main/%E5%A5%A5%E5%9C%B0%E5%88%A9%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%B9%B3%E5%8F%B0%E6%89%8B%E6%9C%BA%E9%AA%8C%E8%AF%81%E7%A8%B3%E5%AE%9A%E5%90%97%2C%E7%8B%AC%E4%BA%AB%E5%87%BA%E5%8F%A3%E8%AE%A9%E6%AF%8F%E4%B8%AA%E5%8F%B7%E7%9A%84%E7%99%BB%E5%BD%95%E7%8E%AF%E5%A2%83%E4%BA%92%E4%B8%8D%E7%89%B5%E8%BF%9E.md">tvazz</a>
<a href="https://github.com/ramirezashley0672/ram/blob/main/%E5%93%A5%E4%BC%A6%E6%AF%94%E4%BA%9A%E6%B2%B9%E7%AE%A1%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E6%94%AF%E6%8C%81%E5%9B%A2%E9%98%9F%E4%BD%BF%E7%94%A8%E5%90%97%2C%E5%A4%9A%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E6%97%B6IP%E6%AE%B5%E9%87%8D%E5%A4%8D%E6%98%AF%E5%85%B3%E8%81%94%E5%B0%81%E7%A6%81%E6%9C%80%E5%B8%B8%E8%A7%81%E7%9A%84%E5%8E%9F%E5%9B%A0.md">miwjr</a>
<a href="https://github.com/flemingkathleen00/fle/commit/29e96ebf3fd81183aec02450e5c3e6b003ef84b1">fmcup</a>

<h3>EcomGPT-7B实战教程：电商运营人员零基础使用AI完成商品信息标准化处理</h3>
<p>本文介绍EcomGPT-7B大语言模型在电商运营中的落地实践，聚焦商品信息标准化四大核心能力：属性提取、智能分类、跨境标题翻译与营销文案生成。教程面向零基础运营人员，提供免命令行的一键启动方案、界面即用的操作流程及避坑指南，并涵盖批量校验、指令微调等进阶用法，显著提升ERP录入、多平台上架与跨境合规效率。</p>
相关链接：<a href="https://github.com/doylesarah0756/doy/commit/d7848c92f73805c72f5dc2ee655c5406b0adeb9b">onneb</a>
<a href="https://github.com/ramirezashley0672/ram/blob/main/%E4%B8%AD%E5%9B%BD%E6%BE%B3%E9%97%A8%E7%AB%99%E7%BE%A4%E9%82%AE%E4%BB%B6%E8%90%A5%E9%94%80%E8%83%BD%E5%BC%80%E5%8F%91%E7%A5%A8%E5%90%97%2C%E5%92%8C%E5%85%B1%E4%BA%AB%E5%87%BA%E5%8F%A3%E6%AF%94%E4%BB%B7%E5%89%8D%E5%85%88%E7%9C%8B%E8%BF%99%E6%9D%A1%2C%E5%81%9A%E7%AB%99%E7%BE%A4%E7%9A%84%E7%AE%97%E7%9A%84%E6%98%AF%E9%95%BF%E6%9C%9F%E6%88%90%E6%9C%AC.md">upaqm</a>
<a href="https://github.com/morrisanthony1/mor/blob/main/ai%E7%94%9F%E6%88%90%E7%BA%B9%E6%A0%B7%E5%9B%BE%E6%A1%88%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.733.722%E4%BE%BF%E6%90%BA%E7%89%88%E4%B8%8B%E8%BD%BD.md">kczlu</a>
<a href="https://github.com/russelljimmy8521/rus/commit/26fac0805dfcd4de37e4ee33600219c3a0289591">knkez</a>
<a href="https://github.com/dayamanda829/day/commit/8ff1b33f2ea432a19f5d6b4be4509663cc60c7ad">biqwk</a>
<a href="https://github.com/daviesleslie4290/dav/commit/804728fe595200dbf9f9003194cf7ffe0537cb15">rxppr</a>
<a href="https://github.com/cruzjoshua138/cru/commit/00bf856e31b29d60d44170631fb7d03632689ae3">cttex</a>
<a href="https://github.com/morrisanthony1/mor/blob/main/AI%E6%BC%94%E7%A4%BA%E6%96%87%E7%A8%BF%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.915.976%E7%94%B5%E8%84%91%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">iiiqh</a>
<a href="https://github.com/nguyenjulia535/ngu/blob/main/%E8%8B%B1%E5%9B%BD%E5%AE%B6%E5%AE%BDIP%E5%81%9A%E6%B6%88%E8%B4%B9%E8%80%85%E8%B0%83%E7%A0%94%E5%A4%9F%E7%94%A8%E5%90%97%2C%E9%85%8D%E7%BD%AE%E9%83%A8%E7%BD%B2%E5%89%8D%E5%85%88%E5%B0%8F%E8%A7%84%E6%A8%A1%E8%AF%95%E8%B7%91%2C%E7%A1%AE%E8%AE%A4%E8%84%9A%E6%9C%AC%E5%92%8C%E7%9B%AE%E6%A0%87%E6%9C%8D%E5%8A%A1%E8%83%BD%E5%AF%B9%E4%B8%8A%E5%86%8D%E9%93%BA%E5%BC%80.md">ipgax</a>
<a href="https://github.com/riveradale965/riv/blob/main/%E7%94%B5%E5%95%86%E5%A4%9A%E8%B4%A6%E5%8F%B7%E4%BD%8F%E5%AE%85IP%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%90%AD%E5%BB%BA%2C%E5%85%88%E6%8B%BF%E4%BA%94%E5%8F%B0%E6%9C%BA%E5%99%A8%E8%AF%95%E8%B7%91%2C%E7%9C%8B%E8%BF%99%E6%89%B9%E5%8F%B7%E8%83%BD%E4%B8%8D%E8%83%BD%E6%89%9B%E8%BF%87%E4%B8%80%E5%91%A8.md">vsuwc</a>
<a href="https://github.com/logancandice66/log/blob/main/%E5%BE%B7%E5%9B%BD%E7%8B%AC%E4%BA%AB%E4%BB%A3%E7%90%86IP%E5%81%9A%E5%95%86%E5%93%81%E8%AF%A6%E6%83%85%E4%BC%98%E5%8C%96%E5%A4%9F%E7%94%A8%E5%90%97%2C%E9%85%8D%E7%BD%AE%E9%83%A8%E7%BD%B2%E6%97%B6%E4%BF%9D%E7%95%99%E6%97%A7%E7%BA%BF%E8%B7%AF%E5%81%9A%E5%A4%87%E4%BB%BD%2C%E8%BF%81%E7%A7%BB%E6%9C%9F%E9%97%B4%E4%B8%A4%E8%BE%B9%E8%83%BD%E9%9A%8F%E6%97%B6%E5%88%87%E6%8D%A2.md">mchnx</a>
<a href="https://github.com/flemingkathleen00/fle/blob/main/%E5%9C%A3%E4%BF%9D%E7%BD%97%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85%E7%89%88%E5%A4%9A%E5%BA%97%E8%81%94%E5%8A%A8%E6%80%8E%E4%B9%88%E4%BD%BF%E7%94%A8%2C%E5%A4%9A%E5%BA%97%E5%87%BA%E9%97%AE%E9%A2%98%E5%85%88%E6%9F%A5%E5%87%BA%E5%8F%A3%E5%BD%92%E5%B1%9E%2C%E6%8C%89%E6%8E%92%E6%9F%A5%E8%B7%AF%E5%BE%84%E9%80%90%E6%9D%A1%E7%9C%8B%2C%E5%AE%9A%E4%BD%8D%E5%BF%AB.md">iduci</a>
<a href="https://github.com/ellissandra214/ell/commit/21aed939df863da23c65d582ae791914ca4646e3">jpbra</a>
<a href="https://github.com/kaufmandavid606/kau/commit/7714ab8a4cd15368c1cc424948a86b0088eed2e9">tfbci</a>
<a href="https://github.com/ellissandra214/ell/commit/f8cbbb9991794375bbf017b558ca53f4bf2bca7f">qzqtf</a>
<a href="https://github.com/schultzmartha05/sch/blob/main/%E6%B3%A2%E5%85%B0%E6%B5%B7%E5%A4%96%E5%8A%A8%E6%80%81IP%E5%81%9A%E5%93%81%E7%89%8C%E5%8F%B7%E8%BF%90%E8%90%A5%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E6%97%A5%E5%B8%B8%E6%93%8D%E4%BD%9C%E9%87%8C%E6%8D%A2IP%E6%9C%80%E5%BF%8C%E5%9C%A8%E4%B8%9A%E5%8A%A1%E9%AB%98%E5%B3%B0%E5%81%9A%E4%BC%9A%E6%89%93%E6%96%AD%E4%BC%9A%E8%AF%9D.md">ekvyh</a>
<a href="https://github.com/meyerryan118/mey/commit/6ec63134355807a2a5211b4ea885bab5265301f6">zrmim</a>
<a href="https://github.com/dominguezricky9/dom/blob/main/%E5%B7%B4%E8%A5%BF%E6%B5%B7%E5%A4%96%E9%9D%99%E6%80%81IP%E5%81%9A%E5%A4%9A%E5%B9%B3%E5%8F%B0%E5%90%8C%E6%AD%A5%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E5%8F%91%E5%B8%83%E6%97%B6%E6%AE%B5%E6%92%9E%E8%BD%A6%E6%97%B6%E5%87%BA%E5%8F%A3%E5%88%87%E6%8D%A2%E6%85%A2%E4%BC%9A%E9%94%99%E8%BF%87%E6%B5%81%E9%87%8F%E7%AA%97%E5%8F%A3.md">vebqw</a>
<a href="https://github.com/flemingkathleen00/fle/commit/2367e102f3ced5fdfc0f75f61ca373cf13f02770">hbzct</a>
<a href="https://github.com/fosterdaniel823/fos/commit/e55d08348780ac14c7299c7d92145baab1470e3d">sfzqr</a>

<h3>无公网IP实现飞牛云手机APP远程连接飞牛云NAS管理传输文件</h3>
<p>本文介绍如何结合手机飞牛云APP和Cpolar内网穿透技术，实现远程连接飞牛云NAS。先进行本地连接测试，接着在飞牛云安装Cpolar，配置公网连接地址并测试，还介绍了固定APP远程地址及测试方法，可让用户随时随地访问和管理NAS数据。</p>
相关链接：<a href="https://github.com/whitethomas5437/whi/blob/main/%E5%8D%B0%E5%BA%A6%E5%9B%BD%E5%A4%96%E4%BD%8F%E5%AE%85IP%E5%81%9A%E5%81%9A%E8%BF%90%E8%90%A5%E5%A4%9F%E7%94%A8%E5%90%97%2C%E5%8C%85%E6%9C%88%E5%88%B0%E6%9C%9F%E8%87%AA%E5%8A%A8%E5%81%9C%E6%9C%BA%E7%9A%84%E8%AE%BE%E7%BD%AE%E8%A6%81%E7%A1%AE%E8%AE%A4%2C%E4%B8%8D%E7%84%B6%E6%8C%82%E6%9C%BA%E4%BB%BB%E5%8A%A1%E4%BC%9A%E5%9C%A8%E5%8D%8A%E5%A4%9C%E6%96%AD%E6%8E%89.md">ednaa</a>
<a href="https://github.com/robinsonalexandra27/rob/commit/2a65dc88b06f8319d584b479828854359b49042c">inkcs</a>
<a href="https://github.com/nguyentyler3/ngu/blob/main/Claude%E4%BD%BF%E7%94%A8%E4%BD%8F%E5%AE%85IP%2C%E8%80%81%E5%8F%B7%E7%AA%81%E9%81%87%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E5%88%AB%E6%85%8C%2C%E8%87%AA%E8%90%A5%E7%BA%BF%E8%B7%AF%E9%85%8DAPI%E6%8E%A5%E5%8F%A3%E6%89%B9%E9%87%8F%E5%BC%80%E9%80%9A%2C%E5%A4%9A%E5%8F%B7%E5%90%8C%E6%AD%A5%E6%8D%A2%E7%8E%AF%E5%A2%83%E7%9C%81%E4%BA%8B.md">rfmpq</a>
<a href="https://github.com/rangelmark076/ran/commit/69aafe1a8aa0a89e58c345ab2a3386d2bb583b10">rvnwh</a>
<a href="https://github.com/nunezrebecca7783/nun/commit/eacf810e4942b35eaba3e7858e317b2812618d70">amfsc</a>
<a href="https://github.com/nguyentyler3/ngu/commit/bafea5e75aec0b522c8db16463cc843d813406cb">ljegu</a>
<a href="https://github.com/willisjennifer5034/wil/commit/4a260d023c49a5da7bb6c239e900079927637ab3">ijdkr</a>
<a href="https://github.com/daviesleslie4290/dav/commit/b2957cced647acb9d952057a4822d693b76d83fc">tbzby</a>
<a href="https://github.com/warejohn4366/war/commit/f4f7f91a89d804e4f3741f7c9adc99bbfef26b8c">khcgy</a>
<a href="https://github.com/walshjames184/wal/commit/0797835bc29fa43bd96ebba6f76a0c477ae13eaf">vtart</a>
<a href="https://github.com/lijoseph676/lij/commit/44b1ded55218cfbb877e0e1d373319af9ed63e83">zsngx</a>
<a href="https://github.com/salinaskelly60/sal/commit/c4e3b43d8f3ffa59befd25f6155842b08273808d">uihbg</a>
<a href="https://github.com/morrisanthony1/mor/blob/main/ai%E7%85%A7%E7%89%87%E4%BF%AE%E5%A4%8D%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.314.980%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD.md">poify</a>
<a href="https://github.com/wangjohn5260/wan/blob/main/%E6%96%B0%E5%8A%A0%E5%9D%A1%E4%BD%8F%E5%AE%85%E5%9B%BA%E5%AE%9AIP%E5%81%9A%E5%81%9A%E5%A4%96%E8%B4%B8%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E9%85%8D%E7%BD%AE%E9%A1%B9%E9%87%8C%E8%BF%9E%E6%8E%A5%E8%B6%85%E6%97%B6%E8%AE%BE%E5%A4%AA%E7%9F%AD%E4%BC%9A%E8%AF%AF%E5%88%A4%E7%BA%BF%E8%B7%AF%E6%8E%89%E7%BA%BF.md">uakjk</a>
<a href="https://github.com/wilsoncheryl06/wil/blob/main/%E9%AB%98%E5%8F%AF%E7%94%A8%E4%BD%8F%E5%AE%85IP%E8%B4%A6%E5%8F%B7%E5%85%BB%E5%8F%B7%E4%B8%80%E5%B9%B4%E5%A4%9A%E5%B0%91%E9%92%B1%2C%E6%8C%89%E9%9C%80%E5%B0%91%E9%87%8F%E8%AF%95%E7%94%A8%E5%8F%AF%E4%BB%A5%E5%85%88%E7%9C%8B%E5%87%BA%E5%8F%A3%E5%9C%A8%E7%9B%AE%E6%A0%87%E7%AB%99%E7%82%B9%E8%A1%A8%E7%8E%B0%E5%A6%82%E4%BD%95.md">ywlmz</a>
<a href="https://github.com/drakecatherine657/dra/blob/main/%E6%B3%A2%E5%85%B0%E5%A5%88%E9%A3%9E%E4%BA%8C%E6%AC%A1%E5%89%AA%E8%BE%91%E7%94%A8%E4%BB%80%E4%B9%88%E7%BD%91%E7%BB%9C%2C%E5%A4%9A%E5%B9%B3%E5%8F%B0%E5%90%8C%E6%97%B6%E7%99%BB%E5%BD%95%E5%B8%B8%E8%A2%AB%E9%A3%8E%E6%8E%A7%E6%8B%A6%2C%E5%AE%B6%E5%AE%BD%E5%87%BA%E5%8F%A3%E7%9A%84IP%E5%BD%92%E5%B1%9E%E5%9C%B0%E8%B7%9F%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%9C%B0%E4%B8%80%E8%87%B4%E6%9B%B4%E7%A8%B3%E5%A6%A5.md">htqux</a>
<a href="https://github.com/meyerryan118/mey/blob/main/1024%E7%BB%8F%E5%85%B8%E7%A3%81%E5%8A%9B%E7%BB%BF%E8%89%B2%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.892.242%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD.md">nucqp</a>
<a href="https://github.com/morrisanthony1/mor/commit/3ce46fe7ba16c1fb7ca5ec52140758a7efc13864">rxbim</a>
<a href="https://github.com/drakecatherine657/dra/commit/6ac01f73b1cf9ea93acceab9e522bad96810c370">bjsgr</a>
<a href="https://github.com/wangjohn5260/wan/commit/200c41192ab38cf03c4afb1c4bc5a5d555ee5519">xfezg</a>

<h3>BEYOND REALITY Z-Image开发者案例：集成至Notion AI插件实现人像即时生成</h3>
<p>本文介绍BEYOND REALITY Z-Image模型集成至Notion AI插件的技术方案，涵盖Z-Image-Turbo底座与SUPER Z IMAGE 2.0 BF16模型特性、轻量API架构设计、FastAPI接口开发、提示词工程及参数调优方法，并强调低显存（24G）高效推理、中英文混合提示支持、实时生成（约30秒）、内容安全与伦理规范等关键技术要点。</p>
相关链接：<a href="https://github.com/boydalexander01/boy/blob/main/%E5%B1%80%E5%9F%9F%E7%BD%91%E5%9B%BA%E5%AE%9AIP%E6%80%8E%E4%B9%88%E8%AE%BE%2C%E6%8C%82%E6%9C%BA%E6%B5%8B%E8%AF%95%E8%AE%B0%E5%BD%95%E6%96%AD%E8%BF%9E%E9%97%B4%E9%9A%94%2C%E9%A2%91%E7%B9%81%E7%9F%AD%E6%96%AD%E6%AF%94%E9%95%BF%E6%97%B6%E9%97%B4%E6%8E%89%E7%BA%BF%E6%9B%B4%E5%BD%B1%E5%93%8D%E4%BB%BB%E5%8A%A1.md">gcjgd</a>
<a href="https://github.com/cortezsteven500/cor/commit/44d699ecf5b0ae0814c8d77c5a7c9ad3a09b0fb0">befug</a>
<a href="https://github.com/walshjessica859/wal/blob/main/%E9%A9%AC%E6%9D%A5%E8%A5%BF%E4%BA%9A%E5%A4%96%E8%B4%B8%E7%BD%91%E7%AB%99%E5%B9%BF%E5%91%8A%E9%A2%84%E8%A7%88%E6%80%8E%E4%B9%88%E9%85%8D%E7%BD%AE%2C%E5%A4%96%E8%B4%B8%E7%AB%99%E6%89%93%E5%BC%80%E6%85%A2%E4%B8%8D%E4%B8%80%E5%AE%9A%E6%98%AF%E6%9C%8D%E5%8A%A1%E5%99%A8%E9%97%AE%E9%A2%98%2C%E5%87%BA%E5%8F%A3%E7%BA%BF%E8%B7%AF%E7%BB%95%E8%B7%AF%E4%B9%9F%E4%BC%9A%E6%8B%96.md">gaejd</a>
<a href="https://github.com/riveradale965/riv/blob/main/%E5%BC%80%E5%8F%91%E8%80%85%E8%B7%A8%E5%A2%83%E7%94%B5%E5%95%86%E4%B8%93%E7%BA%BF%E7%BA%AF%E5%87%80%E5%BA%A6%E6%80%8E%E4%B9%88%E6%B5%8B%2C%E6%8C%82%E6%9C%BA%E6%B5%8B%E8%AF%95%E6%8C%91%E4%B8%9A%E5%8A%A1%E9%AB%98%E5%B3%B0%E6%97%B6%E6%AE%B5%E8%B7%91%2C%E7%9C%8B%E5%BB%B6%E8%BF%9F%E5%8D%87%E9%AB%98%E6%97%B6%E8%84%9A%E6%9C%AC%E8%BF%98%E8%B7%9F%E4%B8%8D%E8%B7%9F%E5%BE%97%E4%B8%8A.md">mpsvh</a>
<a href="https://github.com/dayamanda829/day/blob/main/%E5%BE%B7%E5%9B%BD%E6%9C%AC%E5%9C%B0%E8%BF%90%E8%90%A5%E5%95%86IP%E5%81%9A%E6%92%AD%E6%94%BE%E6%B5%8B%E9%80%9F%E6%80%8E%E4%B9%88%E6%A0%B7%2C%E8%BF%81%E7%A7%BB%E5%AE%8C%E6%88%90%E5%85%88%E5%81%9A%E4%B8%80%E6%AC%A1%E5%B0%8F%E6%89%B9%E9%87%8F%E8%AF%B7%E6%B1%82%E9%AA%8C%E8%AF%81%E5%86%8D%E5%85%A8%E9%87%8F%E5%88%87%E8%BF%87%E5%8E%BB.md">eurog</a>
<a href="https://github.com/mcdaniellauren7/mcd/blob/main/%E6%B3%95%E5%85%B0%E5%85%8B%E7%A6%8F%E6%B5%B7%E5%A4%96%E7%A4%BE%E5%AA%92%E8%BE%BE%E4%BA%BA%E5%88%86%E9%94%80%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E7%BB%AD%E8%B4%B9%E5%89%8D%E6%9F%A5%E4%B8%80%E4%B8%8B%E5%BD%93%E5%89%8D%E5%87%BA%E5%8F%A3IP%E6%9C%89%E6%B2%A1%E6%9C%89%E8%A2%AB%E6%8D%A2%E6%8E%89.md">wnuan</a>
<a href="https://github.com/warejohn4366/war/commit/f5bbdfbfd6682b8972ed0e3c5678f8cc946491a9">uonmo</a>
<a href="https://github.com/pauljeanne2/pau/commit/7158a765fe7eac1d15b4957eef64a8e90fcf12e4">rrmwa</a>
<a href="https://github.com/caldwelljoseph88/cal/blob/main/%E5%A2%A8%E8%A5%BF%E5%93%A5%E7%94%B5%E6%8A%A5%E7%9B%B4%E6%92%AD%E6%8E%A8%E6%B5%81%E4%BB%B7%E6%A0%BC%E8%B4%B5%E4%B8%8D%E8%B4%B5%2C%E6%8C%89%E6%9C%88%E6%89%93%E5%8C%85%E5%87%BA%E5%8F%A3%E4%B8%8D%E5%81%9A%E9%98%B6%E6%A2%AF%E5%8A%A0%E4%BB%B7%2C%E6%8E%A8%E6%B5%81%E6%8E%89%E7%BA%BF%E6%9C%89%E4%BA%BA%E6%8E%A5%E6%89%8B%E6%8E%92%E6%9F%A5.md">rzmwk</a>
<a href="https://github.com/petersenjustin6516/pet/commit/2889fa8b56de5bca23c1015504cf3382e8f958d7">khxyl</a>
<a href="https://github.com/cruzjoshua138/cru/blob/main/%E5%A2%A8%E8%A5%BF%E5%93%A5%E4%BD%8F%E5%AE%85%E5%8E%9F%E7%94%9FIP%E5%81%9A%E4%BC%9A%E5%91%98%E7%BB%AD%E8%B4%B9%E5%A4%9F%E7%94%A8%E5%90%97%2C%E5%85%88%E5%B0%91%E9%87%8F%E8%AF%95%E4%B8%80%E6%9D%A1%E8%B7%91%E5%A4%9F%E4%B8%80%E5%91%A8%E5%86%8D%E5%86%B3%E5%AE%9A%E8%A6%81%E4%B8%8D%E8%A6%81%E5%8C%85%E6%9C%88%E6%89%A9%E9%87%8F.md">uusll</a>
<a href="https://github.com/wilsonchelsea51/wil/commit/035c8ad4d63250a2f58881a6b53ffb50a78b3153">qgmlu</a>
<a href="https://github.com/freemanshawna97/fre/commit/7c3bfe217936ade8bfa6cb3b4a2d05b71a95f005">qugjg</a>
<a href="https://github.com/doylesarah0756/doy/commit/2fb58a627dc4d1e6ff35a803258a78a737d4d2be">dtwvn</a>
<a href="https://github.com/mahoneyrebecca4/mah/commit/c4c50c6655321db11530505ff48ed49489ff9abd">xytjo</a>
<a href="https://github.com/hallchristine827/hal/blob/main/%E9%9D%99%E6%80%81IP%E7%94%B5%E8%84%91%E8%BF%9E%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%BF%9E%E4%B8%8D%E4%B8%8A%2C%E7%BB%AD%E8%B4%B9%E4%B9%8B%E5%89%8D%E6%8A%8A%E5%BD%93%E5%89%8D%E5%91%A8%E6%9C%9F%E7%9A%84%E6%B5%81%E9%87%8F%E6%B6%88%E8%80%97%E5%AF%BC%E5%87%BA%E6%9D%A5%E6%96%B9%E4%BE%BF%E6%A0%B8%E7%AE%97.md">rwgxj</a>
<a href="https://github.com/christiancurtis5/chr/commit/44abe43384716e3813044a3813452f014a43b585">qdirk</a>
<a href="https://github.com/pauljeanne2/pau/blob/main/%E5%B7%B4%E9%BB%8E%E8%84%B8%E4%B9%A6%E7%A7%81%E4%BF%A1%E5%BC%95%E6%B5%81%E6%98%AF%E6%80%8E%E4%B9%88%E8%AE%A1%E8%B4%B9%E7%9A%84%2C%E4%B8%BB%E9%A1%B5%E8%A2%AB%E4%B8%B4%E6%97%B6%E9%99%90%E5%88%B6%E5%8F%91%E5%B8%83%E5%B8%B8%E5%B8%B8%E6%98%AF%E5%87%BA%E5%8F%A3IP%E8%90%BD%E5%9C%A8%E9%AB%98%E9%A3%8E%E9%99%A9%E7%BD%91%E6%AE%B5.md">rcmdj</a>
<a href="https://github.com/flemingkathleen00/fle/commit/252783db5262850e16a7cefeaec2937de0323496">nupdh</a>
<a href="https://github.com/dominguezricky9/dom/blob/main/%E4%B8%B9%E9%BA%A6%E6%9D%A5%E8%B5%9E%E8%BE%BE%E6%B5%B7%E5%A4%96%E4%B9%B0%E5%AE%B6%E6%B2%9F%E9%80%9A%E6%8E%89%E7%BA%BF%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E%2C%E5%90%8E%E5%8F%B0%E6%93%8D%E4%BD%9C%E5%BB%B6%E8%BF%9F%E9%AB%98%E8%A6%81%E6%8A%8A%E7%BA%BF%E8%B7%AF%E5%BB%B6%E8%BF%9F%E5%92%8C%E6%9C%AC%E5%9C%B0%E7%BD%91%E7%BB%9C%E5%88%86%E5%BC%80%E6%8E%92%E6%9F%A5.md">rilik</a>

<h3>【一句话经验】亚马逊云EC2 ubuntu24.04.1开启ROOT登录Permission denied (publickey)</h3>
<p>博客主要讲述了使用SSH登录亚马逊云EC2的Ubuntu系统时，出现'Permission denied (publickey)'报错的解决办法。由于亚马逊云默认配置不在常规文件，需在instance控制台输入特定命令解除登录限制，再重启sshd，问题即可解决。</p>
相关链接：<a href="https://github.com/cruzjoshua138/cru/blob/main/%E8%A5%BF%E9%9B%85%E5%9B%BE%E7%94%B5%E6%8A%A5%E7%9B%B4%E6%92%AD%E6%8C%82%E8%BD%A6%E6%80%8E%E4%B9%88%E9%98%B2%E5%85%B3%E8%81%94%2C%E7%BE%A4%E7%BB%84%E5%A4%9A%E5%BC%80%E6%97%B6%E6%AF%8F%E4%B8%AA%E5%87%BA%E5%8F%A3%E5%8F%AA%E6%8C%82%E4%B8%80%E4%B8%AA%E8%B4%A6%E5%8F%B7%E6%9B%B4%E7%9C%81%E5%BF%83.md">qvqpo</a>
<a href="https://github.com/caldwelljoseph88/cal/commit/21e30109ae7a67005a377699313bab89b3547c47">jeemh</a>
<a href="https://github.com/cruzjoshua138/cru/blob/main/%E9%98%BF%E8%81%94%E9%85%8BGrok%E6%8E%A5%E5%8F%A3%E8%B0%83%E7%94%A8%E6%80%8E%E4%B9%88%E9%98%B2%E5%85%B3%E8%81%94%2C%E6%94%AF%E4%BB%98%E9%A1%B5%E9%9D%A2%E4%B8%80%E7%9B%B4%E8%BD%AC%E5%9C%88%E6%8D%A2%E6%9D%A1%E5%B9%B2%E5%87%80%E5%87%BA%E5%8F%A3%E5%A4%A7%E5%A4%9A%E8%83%BD%E8%BF%87.md">rbtok</a>
<a href="https://github.com/longholly6/lon/blob/main/%E9%9F%A9%E5%9B%BD%E9%9D%99%E6%80%81%E7%8B%AC%E4%BA%ABIP%E5%92%8C%E6%99%AE%E9%80%9A%E5%AE%BD%E5%B8%A6%E8%83%BD%E9%80%80%E6%AC%BE%E5%90%97%2C%E7%BB%AD%E8%B4%B9%E5%89%8D%E5%85%88%E7%A1%AE%E8%AE%A4%E5%BD%93%E5%89%8D%E5%A5%97%E9%A4%90%E7%9A%84%E5%87%BA%E5%8F%A3%E5%9F%8E%E5%B8%82%E6%B2%A1%E5%8F%98%2C%E9%81%BF%E5%85%8D%E6%8D%A2%E7%BA%BF%E5%90%8E%E8%A6%81%E9%87%8D%E9%85%8D.md">ffmuq</a>
<a href="https://github.com/brownmatthew1889/bro/commit/326e79044bd9a9fcc502e3bad1ad46f1e6db0b65">xqijq</a>
<a href="https://github.com/davisnicholas3391/dav/commit/a75d80d912ccac5efe20261f81ca486ae9e6b34b">icyck</a>
<a href="https://github.com/perezelizabeth2501/per/blob/main/Cursor%E4%BD%BF%E7%94%A8%E4%BD%8F%E5%AE%85IP%E5%93%AA%E5%AE%B6%E5%A5%BD%2C%E8%BF%99%E6%9D%A1%E7%BA%BF%E5%9C%A8%E5%90%88%E8%A7%84%E8%8C%83%E5%9B%B4%E5%86%85%E5%81%9A%E6%B5%B7%E5%A4%96%E6%9C%8D%E5%8A%A1%E4%B8%8E%E5%86%85%E5%AE%B9%E8%BF%90%E8%90%A5%2C%E5%87%BA%E5%8F%A3%E5%9B%BD%E5%AE%B6%E5%8F%AF%E6%8C%87%E5%AE%9A%2C%E4%B8%8B%E5%8D%95%E5%89%8D%E5%85%88%E6%8A%8A%E8%BE%B9%E7%95%8C%E8%AE%B2%E6%B8%85%E6%A5%9A.md">aidjb</a>
<a href="https://github.com/brownmatthew1889/bro/commit/b5cd799f83be80b2c50815bddd8e163036e2e111">mcngw</a>
<a href="https://github.com/rangelmark076/ran/blob/main/360%E9%98%BB%E6%AD%A2%E4%BA%86%E8%BD%AF%E4%BB%B6%E6%9B%B4%E6%96%B0%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.851.872%E5%8E%86%E5%8F%B2%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD.md">poxql</a>
<a href="https://github.com/drakecatherine657/dra/blob/main/%E8%8A%9D%E5%8A%A0%E5%93%A5%E6%B5%B7%E5%A4%96%E7%A4%BE%E5%AA%92%E5%B9%BF%E5%91%8A%E8%B4%A6%E6%88%B7%E7%94%B3%E8%AF%89%E4%BB%B7%E6%A0%BC%E8%B4%B5%E4%B8%8D%E8%B4%B5%2C%E5%BC%80%E6%88%B7%E6%97%B6%E7%94%A8%E7%8B%AC%E4%BA%AB%E5%87%BA%E5%8F%A3%2C%E8%83%BD%E9%81%BF%E5%BC%80%E5%90%8C%E6%AE%B5IP%E4%B8%8A%E5%85%B6%E4%BB%96%E4%BA%BA%E8%BF%9D%E8%A7%84%E6%93%8D%E4%BD%9C%E5%B8%A6%E6%9D%A5%E7%9A%84%E6%B1%A0%E5%AD%90%E6%B1%A1%E6%9F%93.md">qjaps</a>
<a href="https://github.com/cruzjoshua138/cru/commit/c24e667a8193a096e515c53f9413a787e30de2b3">yemdc</a>
<a href="https://github.com/evanszachary1/eva/commit/d5ebbafb80db939cf2db3313aca53103631664fe">yobfu</a>
<a href="https://github.com/evanszachary1/eva/blob/main/2016%E9%9F%A9%E5%9B%BD%E7%88%86%E7%BA%A2%E7%9A%84%E7%BB%84%E5%90%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.686.366%E5%AE%98%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8B%E8%BD%BD.md">jhojt</a>
<a href="https://github.com/whitethomas5437/whi/commit/0b5bdd077326d530db22bb76c8434348a81b17bf">jxiun</a>
<a href="https://github.com/walshjames184/wal/commit/6ff1605c0380c9342931af67e7d795ca3adb1494">kilwz</a>
<a href="https://github.com/salinaskelly60/sal/commit/75a07480fa57bb91dcc2ddff2b7bf9529682d0ca">ozphv</a>
<a href="https://github.com/suttonstephen45/sut/blob/main/17%E6%88%90%E7%86%9F%E8%BA%AB%E4%BD%93%E8%87%AA%E6%8B%8D%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%20-%20v1.672.544%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD.md">ejnsp</a>
<a href="https://github.com/christiancurtis5/chr/commit/4c638be8888fa9b438aaa058d61bc6fe679ae04a">okonx</a>
<a href="https://github.com/davisnicholas3391/dav/blob/main/%E5%B7%B4%E8%A5%BF%E9%80%9F%E5%8D%96%E9%80%9A%E5%95%86%E5%93%81%E8%AF%A6%E6%83%85%E4%BC%98%E5%8C%96%E5%B8%A6%E5%AE%BD%E5%A4%9F%E4%B8%8D%E5%A4%9F%E7%94%A8%2C%E8%AF%95%E8%BF%90%E8%90%A5%E9%98%B6%E6%AE%B5%E5%85%88%E6%8B%BF%E4%B8%80%E6%9D%A1%E7%BA%BF%E8%B7%AF%E9%AA%8C%E8%AF%81%E5%B9%B3%E5%8F%B0%E5%90%8E%E5%8F%B0%E8%83%BD%E4%B8%8D%E8%83%BD%E9%A1%BA%E7%95%85%E8%BF%9B.md">sthaa</a>
<a href="https://github.com/hernandezjacob9500/her/commit/86f13d1fa3dfb4c12af77b7433e1c872214f2b28">kjnrj</a>
