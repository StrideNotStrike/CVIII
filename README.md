<div align="center">
  
  <span lang="zh-hans">简体中文</span> | <span lang="zh-hant">[繁體中文](README.zh-hant.md)</span> | [English](README.en.md) 
  # CVIII：内容与呈现 AI 辅助指数
  ![CVIII-*1](https://img.shields.io/badge/CVIII-*1-D9A295)

</div>

> [!NOTE]  
> **注：** 当前方案为基于 IIIA 修正案，仅供参考。  
> 本方案目前未被原作者正式采用，但原作者也未作出回应。如原作者对此做出回应，此方案将视情况更新。在本方案未废止的情况下，若 IIIA 出现修订更新，本方案将同步跟进。

[「AI 参与指数」](https://github.com/ErSanSan233/IIIA)（Indice d'implication de l'intelligence artificielle, IIIA）曾尝试提出一套区分网络视频中 AI 参与度的详细等级标准，旨在帮助视频创作者、观众以及相关行业人员清晰地界定和理解视频在制作过程中 AI 参与的程度。

这一标准的出现，为创作过程中人工智能辅助参与程度的量化提供了可行性。然而，该理论仍存在一定漏洞，且该作者长期未能更新这一标准，故本人在 IIIA 基础上稍加优化、完善，提出本方案。

「内容与呈现 AI 辅助指数」（Content and Visualization with Intelligence Involved Index, CVIII）将 AI（人工智能）参与度的详细等级标准适用范围扩大到文章、视频等全体网络内容，旨在帮助网络文章、视频创作者、读者与观众以及相关行业人员清晰地界定和理解视频在制作过程中 AI 参与的程度。 

## 原始标准 IIIA 潜在问题 | Problems with IIIA
IIIA 在制定时认为文案的 AI 成分和呈现效果的 AI 成分是一样的，若两者有差距，则取 AI 成分较大的部分作为整体指数。

但当核心内容与呈现方式的 AI 成分差异较大时，问题明显暴露：一部视频由人工智能编写剧本（对应核心内容等级 4），但全部使用真人拍摄，一切素材也均为真人创作（对应内容呈现等级 0），按照原标准应填 4，但得出的结果容易引起「这部视频的实拍画面『也是人工智能生成的』」的误解。

为此，本人在 IIIA 参考标准基础上稍加优化、完善，对潜在问题进行深层考虑和修正，如果在使用 IIIA 标准时，如果因为遇到上述问题而不知所措，不妨尝试使用本修正案。
  
## 等级介绍（简略表格）| Simplified level table
当核心内容与内容呈现的 AI 成分差异不大时，或仅仅包含两者中的一个，CVIII 等级可以仅由一位数构成，此时该数字直接对应 AI 辅助参与情况，具体含义基本同 IIIA.

如：本修正案基于的原始参考标准 IIIA 仅仅涉及核心内容，而在内容呈现方面没有明显涉及 AI，基本保持原标准评级 `IIIA-1*`，故本方案的 CVIII 等级为 `CVIII-*1` 或其简写 `CV-*1`。

 | 分类 | 等级 | 含义 | 
 | ---------- | -------- | ------------------------------ | 
 | 未经 AI 制作 | 0        | 完全未使用 AI | 
 | 未经 AI 制作 | 1        | AI 仅提供参考，并未参与视频制作     | 
 | AI 参与制作  | 2        | 人类主导，AI用于提升效果            | 
 | AI 参与制作  | 3        | 人类审核和筛查过视频全部内容        | 
 | AI 参与制作  | 4        | 存在未经人类审核的内容              | 
 | 由 AI 制作   | 5        | 完全由 AI 制作                      | 
 | AI 主题      | \*       | 视频本身谈论 AI，仅包含核心内容部分 | 
  
## 等级判定（详细表格）| Detailed level table
若核心内容与内容呈现的等级差异过大，则 CVIII 的等级部分以两位数表示。第一位表示核心内容的 AI 辅助参与程度，第二位表示内容呈现的 AI 辅助参与程度。

如：张三用人工智能编写剧本（对应核心内容等级 4），但是全部使用真人拍摄，背景音乐等素材也均为真人创作（对应视频内容等级 0），故在本标准下的等级为 `CVIII-40`，或使用其简写 `CV-40`。

 | 等级 | 核心内容（观点、脚本、逻辑） | 内容呈现（视频制作中的素材生成、剪辑）| 
 | -------- | --------------------------------------------------- | --------------------------------------------------- | 
 | 0        | 完全由人类完成。观点、脚本、逻辑链均由人工构思，全程无 AI 参与。 | 完全由人类完成。所有图片／音乐／视频素材均为人工创作或实拍，剪辑完全手动，全程无 AI 参与。 | 
 | 1        | 完全由人类完成，AI 仅作为工具启发创作灵感作为参考（如头脑风暴关键词、热点分析），不直接生成观点。 | 完全由人类完成，AI 仅作为工具提供辅助性灵感（如图片搜索建议、音乐片段推荐）。 | 
 | 2        | 主要由人类完成，AI 进行基础辅助工作（如语法检查、简单文本润色、事实核对提示）。 | 主要由人类完成，AI 局部生成少量素材（如背景图、虚拟场景）。人工完成素材整合与核心剪辑。 | 
 | 3        | AI 完成大量内容模块（如分镜脚本、观点论据、脚本初稿），但经过人工深度修改、审核、核实事实并最终定稿。人类保留关键决策权。 | AI 完成部分关键素材（如主要配图、背景音乐、部分视频片段），但所有素材均经过人工严格筛选、编辑或整合。 | 
 | 4        | AI 主导内容生产完整逻辑链（如新闻评论的论点推演、故事线设计），人工仅进行有限润色或局部调整（如修改不当表述）。 | AI 主导创作，生成大部分或全部素材，人工仅进行抽查式审核。 | 
 | 5        | AI 独立产出完整内容，无人工干预创作过程。 | AI 全流程自主完成所有素材生成、选择、编辑与剪辑。人类无任何创作干预，仅执操作（如上传、发布）。 | 
 | \*       | 修正选项，对于主题围绕 AI 展开的视频，在核心内容等级前加星号，如「\*1 级」 | — | 
  
## 使用说明 | Note
创作者在发布网络内容时，可以根据实际 AI 辅助制作情况，参考本等级标准明确标注 AI 辅助等级，以「AI 辅助指数：`{等级}`」或「CVIII: `{level}`」字样标注，或展示相应等级贴纸，让观众更清晰地了解视频的创作过程。 
  
如果您的项目带有 `README.md` 文件，可以使用以下徽章来展示您项目的 CVIII. 

| 核心内容＼内容呈现 | 0 | 1 | 2 | 3 | 4 | 5 |
|------------------|---|---|---|---|---|---|
| 0  | ![CVIII-00](https://img.shields.io/badge/CVIII-00-FAB689)  | ![CVIII-01](https://img.shields.io/badge/CVIII-01-FAB689)  | ![CVIII-02](https://img.shields.io/badge/CVIII-02-FAB689)  | ![CVIII-03](https://img.shields.io/badge/CVIII-03-FAB689)  | ![CVIII-04](https://img.shields.io/badge/CVIII-04-FAB689)  | ![CVIII-05](https://img.shields.io/badge/CVIII-05-FAB689)  |
| 0* | ![CVIII-*00](https://img.shields.io/badge/CVIII-*00-FAB689)| ![CVIII-*01](https://img.shields.io/badge/CVIII-*01-FAB689)| ![CVIII-*02](https://img.shields.io/badge/CVIII-*02-FAB689)| ![CVIII-*03](https://img.shields.io/badge/CVIII-*03-FAB689)| ![CVIII-*04](https://img.shields.io/badge/CVIII-*04-FAB689)| ![CVIII-*05](https://img.shields.io/badge/CVIII-*05-FAB689)|
| 1  | ![CVIII-10](https://img.shields.io/badge/CVIII-10-D9A295)  | ![CVIII-11](https://img.shields.io/badge/CVIII-11-D9A295)  | ![CVIII-12](https://img.shields.io/badge/CVIII-12-D9A295)  | ![CVIII-13](https://img.shields.io/badge/CVIII-13-D9A295)  | ![CVIII-14](https://img.shields.io/badge/CVIII-14-D9A295)  | ![CVIII-15](https://img.shields.io/badge/CVIII-15-D9A295)  |
| 1* | ![CVIII-*10](https://img.shields.io/badge/CVIII-*10-D9A295)| ![CVIII-*11](https://img.shields.io/badge/CVIII-*11-D9A295)| ![CVIII-*12](https://img.shields.io/badge/CVIII-*12-D9A295)| ![CVIII-*13](https://img.shields.io/badge/CVIII-*13-D9A295)| ![CVIII-*14](https://img.shields.io/badge/CVIII-*14-D9A295)| ![CVIII-*15](https://img.shields.io/badge/CVIII-*15-D9A295)|
| 2  | ![CVIII-20](https://img.shields.io/badge/CVIII-20-B97CAC)  | ![CVIII-21](https://img.shields.io/badge/CVIII-21-B97CAC)  | ![CVIII-22](https://img.shields.io/badge/CVIII-22-B97CAC)  | ![CVIII-23](https://img.shields.io/badge/CVIII-23-B97CAC)  | ![CVIII-24](https://img.shields.io/badge/CVIII-24-B97CAC)  | ![CVIII-25](https://img.shields.io/badge/CVIII-25-B97CAC)  |
| 2* | ![CVIII-*20](https://img.shields.io/badge/CVIII-*20-B97CAC)| ![CVIII-*21](https://img.shields.io/badge/CVIII-*21-B97CAC)| ![CVIII-*22](https://img.shields.io/badge/CVIII-*22-B97CAC)| ![CVIII-*23](https://img.shields.io/badge/CVIII-*23-B97CAC)| ![CVIII-*24](https://img.shields.io/badge/CVIII-*24-B97CAC)| ![CVIII-*25](https://img.shields.io/badge/CVIII-*25-B97CAC)|
| 3  | ![CVIII-30](https://img.shields.io/badge/CVIII-30-A865B3)  | ![CVIII-31](https://img.shields.io/badge/CVIII-31-A865B3)  | ![CVIII-32](https://img.shields.io/badge/CVIII-32-A865B3)  | ![CVIII-33](https://img.shields.io/badge/CVIII-33-A865B3)  | ![CVIII-34](https://img.shields.io/badge/CVIII-34-A865B3)  | ![CVIII-35](https://img.shields.io/badge/CVIII-35-A865B3)  |
| 3* | ![CVIII-*30](https://img.shields.io/badge/CVIII-*30-A865B3)| ![CVIII-*31](https://img.shields.io/badge/CVIII-*31-A865B3)| ![CVIII-*32](https://img.shields.io/badge/CVIII-*32-A865B3)| ![CVIII-*33](https://img.shields.io/badge/CVIII-*33-A865B3)| ![CVIII-*34](https://img.shields.io/badge/CVIII-*34-A865B3)| ![CVIII-*35](https://img.shields.io/badge/CVIII-*35-A865B3)|
| 4  | ![CVIII-40](https://img.shields.io/badge/CVIII-40-9370DB)  | ![CVIII-41](https://img.shields.io/badge/CVIII-41-9370DB)  | ![CVIII-42](https://img.shields.io/badge/CVIII-42-9370DB)  | ![CVIII-43](https://img.shields.io/badge/CVIII-43-9370DB)  | ![CVIII-44](https://img.shields.io/badge/CVIII-44-9370DB)  | ![CVIII-45](https://img.shields.io/badge/CVIII-45-9370DB)  |
| 4* | ![CVIII-*40](https://img.shields.io/badge/CVIII-*40-9370DB)| ![CVIII-*41](https://img.shields.io/badge/CVIII-*41-9370DB)| ![CVIII-*42](https://img.shields.io/badge/CVIII-*42-9370DB)| ![CVIII-*43](https://img.shields.io/badge/CVIII-*43-9370DB)| ![CVIII-*44](https://img.shields.io/badge/CVIII-*44-9370DB)| ![CVIII-*45](https://img.shields.io/badge/CVIII-*45-9370DB)|
| 5  | ![CVIII-50](https://img.shields.io/badge/CVIII-50-4D6BFE)  | ![CVIII-51](https://img.shields.io/badge/CVIII-51-4D6BFE)  | ![CVIII-52](https://img.shields.io/badge/CVIII-52-4D6BFE)  | ![CVIII-53](https://img.shields.io/badge/CVIII-53-4D6BFE)  | ![CVIII-54](https://img.shields.io/badge/CVIII-54-4D6BFE)  | ![CVIII-55](https://img.shields.io/badge/CVIII-55-4D6BFE)  |
| 5* | ![CVIII-*50](https://img.shields.io/badge/CVIII-*50-4D6BFE)| ![CVIII-*51](https://img.shields.io/badge/CVIII-*51-4D6BFE)| ![CVIII-*52](https://img.shields.io/badge/CVIII-*52-4D6BFE)| ![CVIII-*53](https://img.shields.io/badge/CVIII-*53-4D6BFE)| ![CVIII-*54](https://img.shields.io/badge/CVIII-*54-4D6BFE)| ![CVIII-*55](https://img.shields.io/badge/CVIII-*55-4D6BFE)|

若符合等级介绍中的第一种情况，则可以直接使用包含一位数等级的以下徽章展示 CVIII：  
 - [![CVIII-0](https://img.shields.io/badge/CVIII-0-FAB689)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*0](https://img.shields.io/badge/CVIII-*0-FAB689)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-1](https://img.shields.io/badge/CVIII-1-D9A295)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*1](https://img.shields.io/badge/CVIII-*1-D9A295)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-2](https://img.shields.io/badge/CVIII-2-B97CAC)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*2](https://img.shields.io/badge/CVIII-*2-B97CAC)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-3](https://img.shields.io/badge/CVIII-3-A865B3)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*3](https://img.shields.io/badge/CVIII-*3-A865B3)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-4](https://img.shields.io/badge/CVIII-4-9370DB)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*4](https://img.shields.io/badge/CVIII-*4-9370DB)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-5](https://img.shields.io/badge/CVIII-5-4D6BFE)](https://github.com/StrideNotStrike/CVIII) 
 - [![CVIII-*5](https://img.shields.io/badge/CVIII-*5-4D6BFE)](https://github.com/StrideNotStrike/CVIII) 
  
读者（观众）在浏览网络文章（或视频）时，可以查看创作者标注的等级，从而判断网络内容在创作与呈现方面 AI 的参与程度。 
  
## 贡献 | Contribution
如果您认为本等级标准存在不完善的地方，或者有更好的建议，欢迎通过提交 Issue 或 Pull request 等方式参与贡献。 
  
## 许可 | License
本等级标准库采用 MIT License 许可，您可以在遵循许可协议的前提下自由使用和传播。

## 参考资料 | Reference
[IIIA (Indice d'implication de l'intelligence artificielle)](https://github.com/ErSanSan233/IIIA) by ErSanSan233
