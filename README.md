<div align="center">

# Henry Zhang  &nbsp;·&nbsp;  *CyberWizard*

<p>
Independent researcher &nbsp;·&nbsp; Hangzhou &nbsp;·&nbsp; currently at <a href="https://modelbest.cn">ModelBest / MiniCPM</a>
</p>

<h3>One person. Six modalities. Five layers.</h3>

<p><em>Theory &rarr; Tools &rarr; Runtime &rarr; Product &rarr; Culture.</em><br>
The whole stack, owned.</p>

<!-- identity badges -->
<p>
<a href="https://doi.org/10.5281/zenodo.19626829"><img alt="TRB DOI" src="https://img.shields.io/badge/Paper%201%3A%20TRB-10.5281%2Fzenodo.19626829-3b82f6?style=flat-square"></a>
<a href="https://doi.org/10.5281/zenodo.19587024"><img alt="SFP DOI" src="https://img.shields.io/badge/Paper%202%3A%20SFP-10.5281%2Fzenodo.19587024-3b82f6?style=flat-square"></a>
<a href="https://github.com/HenryZ838978?tab=repositories"><img alt="Public repos" src="https://img.shields.io/badge/public%20repos-19-22c55e?style=flat-square"></a>
<a href="https://www.npmjs.com/package/pgattn"><img alt="npm" src="https://img.shields.io/badge/npm-pgattn-cb3837?style=flat-square"></a>
<a href="https://github.com/HenryZ838978/pocketclaw/releases/latest"><img alt="APK released" src="https://img.shields.io/badge/PocketClaw-APK%20v0.4.1-6366f1?style=flat-square"></a>
<a href="https://space.bilibili.com/188066555"><img alt="Bilibili" src="https://img.shields.io/badge/bilibili-100k%20view-ec407a?style=flat-square"></a>
</p>

<!-- domains covered -->
<p>
<img alt="" src="https://img.shields.io/badge/-Representation%20Geometry-3b82f6?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-RL%20Alignment-ef4444?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-RepEng%20%2F%20Personality-ec4899?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Satellite%20VLM-06b6d4?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Video%20Generation-f97316?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-ATC%20Speech-14b8a6?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Full--Duplex%20Voice-10b981?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Voice%20Cloning-22d3ee?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Music%20%C3%97%20AI-f59e0b?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Edge%20NPU-7c3aed?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Apple%20Silicon-111827?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-Mobile%20Agent-6366f1?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-AI%20Coding-16a34a?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-KV%20Compression-dc2626?style=flat-square">
<img alt="" src="https://img.shields.io/badge/-PDF%20Workflow-64748b?style=flat-square">
</p>

</div>

---

## How it gets built

<table align="center"><tr>
<td valign="middle" align="center" width="300">
<pre>
           H
          / \
         /   \
        /     \
       A ─────G
</pre>
</td>
<td valign="middle">
<sub>

**H** &mdash; asks, doesn&rsquo;t stop at the first plausible answer.<br>
**A** &mdash; pattern-completes, surfaces adjacencies.<br>
**G** &mdash; append-only memory; rollback when a branch is wrong.

<em>The matrix below isn&rsquo;t a persona. It&rsquo;s what this loop outputs when it runs continuously.</em>

</sub>
</td>
</tr></table>

---

## The Matrix

<sub>*What I actually ship, across every layer of the stack &mdash; in the open where I can, on commercial deployments where I can&rsquo;t.*</sub>

<table>
<thead>
<tr>
  <th align="left">&nbsp;</th>
  <th align="left">Science</th>
  <th align="left">Open-source Tools</th>
  <th align="left">Runtime / Models</th>
  <th align="left">Products / Deploy</th>
  <th align="left">Content / IP</th>
</tr>
</thead>
<tbody>

<!-- Row 1 : LLM / Text -->
<tr>
<td valign="top"><sub><strong>LLM&nbsp;/&nbsp;Text</strong></sub></td>
<td valign="top"><sub>
&bull; <a href="https://doi.org/10.5281/zenodo.19626829"><strong>TRB</strong></a> Paper 1 &mdash; <em>Representation Bandwidth</em><br>
&bull; <a href="https://doi.org/10.5281/zenodo.19587024"><strong>SFP v2</strong></a> Paper 2 &mdash; phased-array probe<br>
&bull; <a href="https://github.com/HenryZ838978/rl-drift">rl-drift</a> &mdash; RLHF manifold compression
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/spectral-flow-probe"><strong>spectral-flow-probe</strong></a> &mdash; 20-min scan, where your RL went too far<br>
&bull; <a href="https://github.com/HenryZ838978/turboquant-pytorch">turboquant-pytorch</a> &mdash; Google ICLR&rsquo;26 reimpl.<br>
&bull; <a href="https://github.com/HenryZ838978/RepEngvLLM">RepEngvLLM</a> &mdash; RepEng&times;vLLM, MiniCPM4.1
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/nano-vllm-with-TurboQuant">nano-vllm + TurboQuant</a> &mdash; 5&times; KV compression<br>
&bull; <a href="https://github.com/HenryZ838978/flash-attn-blackwell">flash-attn-blackwell</a> &mdash; FA wheels, sm_120
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/claude-code">claude-code</a> (fork)<br>
&bull; open-code-agent &mdash; AI coding runtime
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/superpowers-cn">superpowers-cn</a><br>
&nbsp;&nbsp;10&#8239;k&#x2B50; skills framework &middot; CN
</sub></td>
</tr>

<!-- Row 2 : Vision / VLA -->
<tr>
<td valign="top"><sub><strong>Vision&nbsp;/&nbsp;VLA</strong></sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/RepSNI">RepSNI report</a> &mdash; 14 models, 6&#8239;k gens, SNI<br>
&bull; TRB &sect;VLA &mdash; why VLA fails, from geometry
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/SDE">SDE</a> &mdash; Semantic DarkSpace Expression<br>
&bull; <a href="https://github.com/HenryZ838978/Joi">Joi</a> &mdash; personality drift engine
</sub></td>
<td valign="top"><sub>
&bull; minicpmv_onnx &mdash; MiniCPM-V ONNX toolchain<br>
&bull; multi-image async VLM on QNN
</sub></td>
<td valign="top"><sub>
&bull; <strong>AVIA &mdash; Satellite VLM</strong><br>
&nbsp;&nbsp;libtorch C++, MiniCPM-4V, on-board payload
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/Seedance2.0-Storyboard-Planner"><strong>Seedance&nbsp;2.0 Planner</strong></a><br>
&nbsp;&nbsp;44&#x2B50; &middot; storyboard for ByteDance video gen
</sub></td>
</tr>

<!-- Row 3 : Speech / Audio -->
<tr>
<td valign="top"><sub><strong>Speech&nbsp;/&nbsp;Audio</strong></sub></td>
<td valign="top"><sub>&mdash;</sub></td>
<td valign="top"><sub>
&bull; dereverb_audio &mdash; internal DSP toolchain
</sub></td>
<td valign="top"><sub>
&bull; VoxCPM &mdash; voice-clone runtime<br>
&bull; Omni &mdash; MiniCPM-o 4.5 gguf / llama.cpp-omni port
</sub></td>
<td valign="top"><sub>
&bull; <strong>AVIA &mdash; ATC ASR</strong> &middot; Apple Silicon<br>
&nbsp;&nbsp;<strong>RTF&nbsp;&gt;&nbsp;3</strong> &middot; <strong>mem&nbsp;&lt;&nbsp;2&#8239;GB</strong><br>
&bull; <a href="https://github.com/HenryZ838978/CallCenter-VoiceAgent">CallCenter-VA</a><br>
&bull; <a href="https://github.com/HenryZ838978/Hybrid-VoiceAgent">Hybrid-VA</a> (full-duplex)<br>
&bull; <a href="https://github.com/HenryZ838978/Voiceagent-MacApp">Voiceagent-Mac</a>
</sub></td>
<td valign="top"><sub>
&bull; <strong>PixelSynesthesia</strong> &mdash; music &rarr; pixel<br>
&bull; <a href="https://www.bilibili.com/video/BV1U42wBvEFz"><strong>&laquo;&#26538;&#20853;&#39042;&raquo; AI MV</strong></a> &middot; 100&#8239;k views &middot; 7.1&#8239;k likes
</sub></td>
</tr>

<!-- Row 4 : Edge / Hardware -->
<tr>
<td valign="top"><sub><strong>Edge&nbsp;/&nbsp;Hardware</strong></sub></td>
<td valign="top"><sub>
&bull; MiniCPM cross-platform &mdash; benchmark suite
</sub></td>
<td valign="top"><sub>&mdash;</sub></td>
<td valign="top"><sub>
&bull; Qualcomm QNN &middot; MediaTek MTK &middot; Rockchip RKNN<br>
&bull; Intel NPU &middot; Apple Silicon
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/ScalEdgeClaw">EdgeClaw-audit</a><br>
&nbsp;&nbsp;on-device multi-tenant isolation review
</sub></td>
<td valign="top"><sub>&mdash;</sub></td>
</tr>

<!-- Row 5 : Agent / Workflow -->
<tr>
<td valign="top"><sub><strong>Agent&nbsp;/&nbsp;Workflow</strong></sub></td>
<td valign="top"><sub>
&bull; <strong>HAG Loop</strong> &mdash; Human-AI-Git framework
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/ScalEdgeClaw">ScalEdgeClaw</a> &mdash; multi-tenant EdgeClaw
</sub></td>
<td valign="top"><sub>
&bull; cursor-rts-audio &mdash; realtime audio for Cursor
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/pocketclaw"><strong>PocketClaw</strong> (APK)</a><br>
&nbsp;&nbsp;20&#x2B50; &middot; 19.4&#8239;k LoC Kotlin &middot; no server<br>
&bull; OmniAgent &mdash; Swift macOS / iOS / visionOS
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/OpenMAIC-VoiceSupport"><strong>OpenMAIC</strong></a><br>
&nbsp;&nbsp;THU multi-agent classroom &middot; voice-support
</sub></td>
</tr>

<!-- Row 6 : Meta / Tooling -->
<tr>
<td valign="top"><sub><strong>Meta&nbsp;/&nbsp;Tooling</strong></sub></td>
<td valign="top"><sub>&mdash;</sub></td>
<td valign="top"><sub>
&bull; <strong><a href="https://www.npmjs.com/package/pgattn">pgattn</a></strong> &mdash; <strong>the LM&rsquo;s native PDF-git</strong><br>
&nbsp;&nbsp;<em>&ldquo;vLLM pages KV for GPUs; pgattn pages attention for humans.&rdquo;</em>
</sub></td>
<td valign="top"><sub>
&bull; wechat-extract &mdash; WeChat chat-log ETL
</sub></td>
<td valign="top"><sub>
&bull; html-inbox &mdash; slide / doc staging
</sub></td>
<td valign="top"><sub>
&bull; <a href="https://github.com/HenryZ838978/wudai-fengyun">&#20116;&#20195;&#39118;&#20113;</a> &mdash; Five Dynasties interactive
</sub></td>
</tr>

</tbody>
</table>

---

## Read the papers first, if you&rsquo;re here for one thing

<table>
<tr>
<td valign="top" width="50%">
<h3>Paper&nbsp;1 &middot; <em>The Representation Bandwidth (TRB)</em></h3>
<p><sub>A conservation analysis under RL alignment.</sub></p>
<p>RL alignment is widely believed to compress the representational capacity of a pretrained transformer. <strong>It does not.</strong></p>
<p>Across Qwen / Yi / Mistral base &harr; instruct pairs, the singular-value spectrum of every weight matrix drifts below 0.5&nbsp;%, while the singular-vector bases rotate by 0.9&ndash;8 degrees. Alignment is consistent with a <strong>graph isometry</strong>: the spectrum is preserved, the bases rotate. What people call &ldquo;PR collapse&rdquo; is not capacity loss &mdash; it is a measurement artifact of angle.</p>
<p><sub><code>n = 644</code> &middot; <code>Pearson p = 7 &times; 10<sup>&minus;13</sup></code></sub></p>
<p><a href="https://doi.org/10.5281/zenodo.19626829">DOI: 10.5281/zenodo.19626829</a></p>
</td>
<td valign="top" width="50%">
<h3>Paper&nbsp;2 &middot; <em>Spectral Flow Probe v2 (SFP)</em></h3>
<p><sub>A measurement toolkit for Transformer representation bandwidth.</sub></p>
<p>Five components: <strong>SpectralProbe</strong> (deterministic 7-band bandwidth), <strong>RotationAnalyzer</strong> (weight-space SVD &amp; principal angles), <strong>BandwidthDiagnostic</strong> (pre-training data-mix audit), <strong>SpectralCallback</strong> (training-time monitor), and <strong>spectral_pr_loss</strong> (differentiable per-band regularizer).</p>
<p>Every measurement runs on a single consumer GPU. Reproducible to 10<sup>&minus;10</sup> across hardware.</p>
<p><sub><code>20 GPU-min / 7&nbsp;B pair</code> &middot; <code>MIT</code></sub></p>
<p><a href="https://doi.org/10.5281/zenodo.19587024">DOI: 10.5281/zenodo.19587024</a> &middot; <a href="https://github.com/HenryZ838978/spectral-flow-probe">github</a></p>
</td>
</tr>
</table>

---

## Partnerships

<sub>Brand badges link to each org&rsquo;s open-source home.</sub>

<p>
<a href="https://github.com/quic"><img alt="Qualcomm" src="https://img.shields.io/badge/Qualcomm-3253dc?style=for-the-badge"></a>
<a href="https://github.com/MediaTek-Labs"><img alt="MediaTek" src="https://img.shields.io/badge/MediaTek-ff5e00?style=for-the-badge"></a>
<a href="https://github.com/rockchip-linux"><img alt="Rockchip" src="https://img.shields.io/badge/Rockchip-2f2f2f?style=for-the-badge"></a>
<a href="https://github.com/intel"><img alt="Intel" src="https://img.shields.io/badge/Intel-0071c5?style=for-the-badge"></a>
<a href="https://github.com/apple"><img alt="Apple" src="https://img.shields.io/badge/Apple-111111?style=for-the-badge"></a>
<a href="https://github.com/huaweicloud"><img alt="Huawei" src="https://img.shields.io/badge/Huawei-f5270a?style=for-the-badge"></a>
<a href="https://github.com/bytedance"><img alt="ByteDance" src="https://img.shields.io/badge/ByteDance-000000?style=for-the-badge"></a>
<a href="https://github.com/OpenBMB"><img alt="OpenBMB" src="https://img.shields.io/badge/OpenBMB-0ea5e9?style=for-the-badge"></a>
<a href="https://github.com/THU-MAIC"><img alt="THU MAIC" src="https://img.shields.io/badge/THU%20MAIC-660874?style=for-the-badge"></a>
</p>

---

## Track record

|  |  |
|---|---|
| **Zenodo preprints** | 2 DOIs (TRB + SFP v2) &middot; download&nbsp;/&nbsp;view ratio &nbsp;**63&nbsp;%** and **87&nbsp;%** |
| **Public GitHub repos** | 19 &middot; spanning LLM / VLM / voice / mobile / edge hardware |
| **Shipped products** | Android APK, macOS&nbsp;/&nbsp;iOS&nbsp;/&nbsp;visionOS voice agents, MiniCPM on 5 silicon vendors |
| **Bilibili** | <a href="https://space.bilibili.com/188066555">space.bilibili.com/188066555</a> |

---

## About this page

<p>If a one-person full-stack AI lab sounds implausible &mdash; and you suspect most of it is filler &mdash; the fastest way to find out is to open the repos above. Each cell links to real code, a real DOI, or a real shipped binary.</p>

<p>If any of it overlaps with what you&rsquo;re building, happy to chat anytime: <a href="mailto:HenryZ838978@aliyun.com">HenryZ838978@aliyun.com</a>.</p>

---

<div align="center">

<sub>
&#128231; <a href="mailto:HenryZ838978@aliyun.com">HenryZ838978@aliyun.com</a>
&nbsp;&middot;&nbsp;
&#128187; <a href="https://github.com/HenryZ838978">github.com/HenryZ838978</a>
&nbsp;&middot;&nbsp;
&#128196; <a href="https://zenodo.org/search?q=creators.name%3A%22Zhang%2C+Jing%22">Zenodo record</a>
&nbsp;&middot;&nbsp;
&#128249; <a href="https://space.bilibili.com/188066555">Bilibili</a>
</sub>

<sub><em>Last updated: Apr 20, 2026</em></sub>

</div>
