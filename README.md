
<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text">
<themed-picture data-catalyst-inline="true" data-catalyst=""><picture>
  <source media="(prefers-color-scheme: dark)" srcset="/livekit/agents/raw/main/.github/banner_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="/livekit/agents/raw/main/.github/banner_light.png">
  <img style="visibility:visible;max-width:100%;" alt="LiveKit 图标、存储库的名称和后台中的一些示例代码。" src="https://raw.githubusercontent.com/livekit/agents/main/.github/banner_light.png" _mstalt="3945760" _msthash="252">
</picture></themed-picture>


<p dir="auto"><br><br><font _mstmutation="1" _msttexthash="44044741" _msthash="253">正在寻找 JS/TS 库？了解 <a href="https://github.com/livekit/agents-js" _mstmutation="1" _istranslated="1">AgentsJS</a></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="30407598" _msthash="254">✨ [新] OpenAI 实时 API 支持</h2><a id="user-content--new-openai-realtime-api-support" class="anchor" aria-label="永久链接：✨[NEW] OpenAI Realtime API 支持" href="#-new-openai-realtime-api-support" _mstaria-label="3549442" _msthash="255"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="1694551300" _msthash="256">我们正在与 OpenAI 合作开发 Agents 框架中的新 API。此类完全包装了 OpenAI 的实时 API，抽象出原始有线协议，并在 GPT-4o 和用户设备之间提供超低延迟的 WebRTC 传输。同样的堆栈为 ChatGPT 应用程序中的 Advanced Voice 提供支持。</font><code>MultimodalAgent</code></p>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="72002398" _msthash="257">在我们的 <a href="https://playground.livekit.io/" rel="nofollow" _mstmutation="1" _istranslated="1">Playground</a> 中试用实时 API [<a href="https://github.com/livekit-examples/realtime-playground" _mstmutation="1" _istranslated="1">代码</a></font>]</li>
<li _msttexthash="199650061" _msthash="258">查看我们的<a href="https://docs.livekit.io/agents/openai" rel="nofollow" _istranslated="1">指南</a>，了解如何使用此新 API 构建您的第一个应用程序</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="24040575" _msthash="259">什么是代理？</h2><a id="user-content-what-is-agents" class="anchor" aria-label="永久链接：什么是 Agents？" href="#what-is-agents" _mstaria-label="533845" _msthash="260"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="3077183720" _msthash="261">代理框架允许您构建可以实时查看、听到和说话的 AI 驱动型服务器程序。您的代理通过 LiveKit 会话与最终用户设备连接。在该会话期间，您的代理可以处理来自用户设备的文本、音频、图像或视频流，并让 AI 模型生成这些相同模态的任意组合作为输出，并将它们流式传输回用户。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5209451" _msthash="262">特征</h2><a id="user-content-features" class="anchor" aria-label="永久链接：功能" href="#features" _mstaria-label="370552" _msthash="263"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="177448635" _msthash="264">适用于常用 LLM、转录和文本转语音服务以及 RAG 数据库的插件</li>
<li _msttexthash="384935681" _msthash="265">用于构建具有自动轮次检测、中断处理、函数调用和转录功能的语音代理或助手的高级抽象</li>
<li _msttexthash="270497227" _msthash="266">与 LiveKit 的<a href="https://github.com/livekit/sip" _istranslated="1">电话堆栈</a>兼容，允许您的座席拨打电话或从电话接听电话</li>
<li _msttexthash="327772484" _msthash="267">集成的负载平衡系统，通过基于边缘的调度、监控和透明故障转移来管理代理池</li>
<li _msttexthash="186816136" _msthash="268">在 localhost、<a href="https://github.com/livekit/livekit" _istranslated="1">自托管</a>和 <a href="https://cloud.livekit.io" rel="nofollow" _istranslated="1">LiveKit Cloud</a> 环境中运行代理是相同的</li>
</ul>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5773755" _msthash="269">安装</h2><a id="user-content-installation" class="anchor" aria-label="永久链接：安装" href="#installation" _mstaria-label="519259" _msthash="270"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="115240814" _msthash="271">要安装核心 Agents 库，请执行以下操作：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install livekit-agents</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install livekit-agents" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4427670" _msthash="272">插件</h2><a id="user-content-plugins" class="anchor" aria-label="永久链接： 插件" href="#plugins" _mstaria-label="339846" _msthash="273"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="974480338" _msthash="274">该框架包含各种插件，可以轻松处理流式输入或生成输出。例如，有一些插件用于将文本转换为语音或使用流行的 LLM 运行推理。以下是安装插件的方法：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install livekit-plugins-openai</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install livekit-plugins-openai" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="38385919" _msthash="275">以下插件现已推出：</p>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="4427670" _msthash="276">插件</th>
<th _msttexthash="5209451" _msthash="277">特征</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-anthropic/" rel="nofollow" _msttexthash="16268772" _msthash="278">livekit-plugins-人类</a></td>
<td _msttexthash="11532118" _msthash="279">LLM</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-azure/" rel="nofollow" _msttexthash="479297" _msthash="280">livekit-plugins-azure</a></td>
<td _msttexthash="1662830" _msthash="281">STT、TTS</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-deepgram/" rel="nofollow" _msttexthash="9536150" _msthash="282">Livekit-插件-deepgram</a></td>
<td _msttexthash="14870856" _msthash="283">短期试验</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-cartesia/" rel="nofollow" _msttexthash="24043747" _msthash="284">livekit-plugins-笛卡尔</a></td>
<td _msttexthash="26091" _msthash="285">TTS</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-elevenlabs/" rel="nofollow" _msttexthash="678197" _msthash="286">livekit-plugins-elevenlabs</a></td>
<td _msttexthash="26091" _msthash="287">TTS</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-playht/" rel="nofollow" _msttexthash="518557" _msthash="288">livekit-plugins-playht</a></td>
<td _msttexthash="26091" _msthash="289">TTS</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-google/" rel="nofollow" _msttexthash="19602843" _msthash="290">livekit-plugins-谷歌</a></td>
<td _msttexthash="1662830" _msthash="291">STT、TTS</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-nltk/" rel="nofollow" _msttexthash="440674" _msthash="292">livekit-plugins-nltk</a></td>
<td _msttexthash="46277972" _msthash="293">用于处理文本的实用程序</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-rag/" rel="nofollow" _msttexthash="10652967" _msthash="294">livekit-plugins-rag 的</a></td>
<td _msttexthash="41240771" _msthash="295">用于执行 RAG 的实用程序</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-openai/" rel="nofollow" _msttexthash="510627" _msthash="296">livekit-plugins-openai</a></td>
<td _msttexthash="39015236" _msthash="297">LLM、STT、TTS、助手 API、实时 API</td>
</tr>
<tr>
<td><a href="https://pypi.org/project/livekit-plugins-silero/" rel="nofollow" _msttexthash="517023" _msthash="298">livekit-plugins-silero</a></td>
<td _msttexthash="7187037" _msthash="299">VAD系列</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14023256" _msthash="300">文档和指南</h2><a id="user-content-documentation-and-guides" class="anchor" aria-label="永久链接： 文档和指南" href="#documentation-and-guides" _mstaria-label="979394" _msthash="301"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="124375589" _msthash="302">有关该框架及其使用方法的文档，<a href="https://docs.livekit.io/agents" rel="nofollow" _istranslated="1">请点击此处</a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11165921" _msthash="303">示例代理</h2><a id="user-content-example-agents" class="anchor" aria-label="永久链接：示例代理" href="#example-agents" _mstaria-label="556062" _msthash="304"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="141033347" _msthash="305">使用 STT、LLM 和 TTS 管道的基本语音代理 [<a href="https://kitt.livekit.io" rel="nofollow" _mstmutation="1" _istranslated="1">演示</a> |<a href="https://github.com/livekit/agents/blob/main/examples/voice-pipeline-agent/minimal_assistant.py" _mstmutation="1" _istranslated="1">code</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="115663548" _msthash="306">使用新 OpenAI Realtime API 的语音代理 [<a href="https://playground.livekit.io" rel="nofollow" _mstmutation="1" _istranslated="1">演示</a> |<a href="https://github.com/livekit-examples/realtime-playground" _mstmutation="1" _istranslated="1">code</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="183652157" _msthash="307">使用 Cerebras 托管的 Llama 3.1 的超快速语音代理 [<a href="https://cerebras.vercel.app" rel="nofollow" _mstmutation="1" _istranslated="1">演示</a> |<a href="https://github.com/dsa/fast-voice-assistant/" _mstmutation="1" _istranslated="1">法典</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="105633450" _msthash="308">使用 Cartesia 的 Sonic 模型的语音代理 [<a href="https://cartesia-assistant.vercel.app/" rel="nofollow" _mstmutation="1" _istranslated="1">演示</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="22918935" _msthash="309">通过函数调用 [<a href="https://github.com/livekit/agents/blob/main/examples/voice-pipeline-agent/function_calling_weather.py" _mstmutation="1" _istranslated="1">code</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="80861131" _msthash="310">执行基于 RAG 的查找的语音代理 [<a href="https://github.com/livekit/agents/tree/main/examples/voice-pipeline-agent/simple-rag" _mstmutation="1" _istranslated="1">code</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="58567405" _msthash="311">发布 RGB 帧流的视频代理 [<a href="https://github.com/livekit/agents/tree/main/examples/simple-color" _mstmutation="1" _istranslated="1">代码</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="109382923" _msthash="312">从用户的语音生成文本字幕的转录代理 [<a href="https://github.com/livekit/agents/tree/main/examples/speech-to-text" _mstmutation="1" _istranslated="1">代码</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="230846941" _msthash="313">您可以发短信的聊天代理，该代理将使用生成的语音进行回复 [<a href="https://github.com/livekit/agents/tree/main/examples/text-to-speech" _mstmutation="1" _istranslated="1">代码</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="48101404" _msthash="314">Localhost 多坐席电话会议 [<a href="https://github.com/dsa/multi-agent-meeting" _mstmutation="1" _istranslated="1">code</a></font>]</li>
<li><font _mstmutation="1" _msttexthash="135414721" _msthash="315">使用 Hive 检测垃圾内容/滥用视频的审核代理 [<a href="https://github.com/dsa/livekit-agents/tree/main/hive-moderation-agent" _mstmutation="1" _istranslated="1">代码</a></font>]</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6354283" _msthash="316">贡献</h2><a id="user-content-contributing" class="anchor" aria-label="永久链接： 贡献" href="#contributing" _mstaria-label="521066" _msthash="317"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1681654039" _msthash="318">代理框架正在一个快速发展的领域中积极开发。我们欢迎并感谢任何形式的贡献，无论是反馈、错误修复、功能、新插件和工具，还是更好的文档。您可以在此存储库下提交问题、打开 PR 或在 LiveKit 的 <a href="https://livekit.io/join-slack" rel="nofollow" _istranslated="1">Slack 社区</a>中与我们聊天。</p>

<p dir="auto"><br></p><p dir="auto"></p><markdown-accessiblity-table data-catalyst=""><table>
<thead><tr><th colspan="2" _msttexthash="24173721" _msthash="319">LiveKit 生态系统</th></tr></thead>
<tbody>
<tr><td _msttexthash="4878198" _msthash="320">实时 SDK</td><td _msttexthash="403482144" _msthash="321"><a href="https://github.com/livekit/client-sdk-js" _istranslated="1">浏览器</a> ·<a href="https://github.com/livekit/client-sdk-swift" _istranslated="1">iOS/macOS/visionOS</a> 软件 ·<a href="https://github.com/livekit/client-sdk-android" _istranslated="1">安卓</a> ·<a href="https://github.com/livekit/client-sdk-flutter" _istranslated="1">扑动</a> ·<a href="https://github.com/livekit/client-sdk-react-native" _istranslated="1">React Native 反应原生</a> ·<a href="https://github.com/livekit/rust-sdks" _istranslated="1">锈</a> ·<a href="https://github.com/livekit/node-sdks" _istranslated="1">Node.js</a> ·<a href="https://github.com/livekit/python-sdks" _istranslated="1">python</a> ·<a href="https://github.com/livekit/client-sdk-unity" _istranslated="1">团结</a> ·<a href="https://github.com/livekit/client-sdk-unity-web" _istranslated="1">Unity （WebGL）</a></td></tr><tr></tr>
<tr><td _msttexthash="7219901" _msthash="322">服务器 API</td><td _msttexthash="194971556" _msthash="323"><a href="https://github.com/livekit/node-sdks" _istranslated="1">Node.js</a> ·<a href="https://github.com/livekit/server-sdk-go" _istranslated="1">Golang</a> ·<a href="https://github.com/livekit/server-sdk-ruby" _istranslated="1">红宝石</a> ·<a href="https://github.com/livekit/server-sdk-kotlin" _istranslated="1">Java/Kotlin</a> ·<a href="https://github.com/livekit/python-sdks" _istranslated="1">蟒蛇</a> ·<a href="https://github.com/livekit/rust-sdks" _istranslated="1">锈</a> ·<a href="https://github.com/agence104/livekit-server-sdk-php" _istranslated="1">PHP（社区）</a></td></tr><tr></tr>
<tr><td _msttexthash="6440031" _msthash="324">UI 组件</td><td _msttexthash="86365513" _msthash="325"><a href="https://github.com/livekit/components-js" _istranslated="1">反应</a> ·<a href="https://github.com/livekit/components-android" _istranslated="1">Android 编写</a> ·<a href="https://github.com/livekit/components-swift" _istranslated="1">斯威夫特用户界面</a></td></tr><tr></tr>
<tr><td _msttexthash="11501451" _msthash="326">代理框架</td><td _msttexthash="18479760" _msthash="327"><b _istranslated="1">蟒蛇</b> ·<a href="https://github.com/livekit/agents-js" _istranslated="1">Node.js</a> ·<a href="https://github.com/livekit/agent-playground" _istranslated="1">操场</a></td></tr><tr></tr>
<tr><td _msttexthash="6939881" _msthash="328">服务业</td><td _msttexthash="42624582" _msthash="329"><a href="https://github.com/livekit/livekit" _istranslated="1">LiveKit 服务器</a> ·<a href="https://github.com/livekit/egress" _istranslated="1">出口</a> ·<a href="https://github.com/livekit/ingress" _istranslated="1">入口</a> ·<a href="https://github.com/livekit/sip" _istranslated="1">啜</a></td></tr><tr></tr>
<tr><td _msttexthash="6234540" _msthash="330">资源</td><td _msttexthash="90134590" _msthash="331"><a href="https://docs.livekit.io" rel="nofollow" _istranslated="1">文档</a> ·<a href="https://github.com/livekit-examples" _istranslated="1">示例应用</a> ·<a href="https://livekit.io/cloud" rel="nofollow" _istranslated="1">云</a> ·<a href="https://docs.livekit.io/home/self-hosting/deployment" rel="nofollow" _istranslated="1">自托管</a> ·<a href="https://github.com/livekit/livekit-cli" _istranslated="1">命令行界面</a></td></tr>
</tbody>
</table></markdown-accessiblity-table>

</article></div>
