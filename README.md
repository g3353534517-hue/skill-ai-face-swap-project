# AI 虚拟形象换脸视频 / AI Face Swap Video Project

![分类](https://img.shields.io/badge/分类-创意工具-green)

## 简介 / Overview

AI虚拟形象换脸视频项目——复刻推特爆款案例，三层脸叠加架构，从0到完整视频

## 详细说明 / Details

## 项目目标

复刻推特爆款案例：用AI生成的"假小孩"作为博主人设，制作该小孩变身成不同名人/角色的短视频。全流程AI脸，真人不露面。

## 原案例

推特上有个账号，用AI生成的小孩脸做博主，每期视频"变身"成不同名人，平均播放量超百万，赚了几万美元。观众以为是个天才小孩，实际上整个博主都是AI。

- 热门推文: x.com//status/2051326660297789806 (❤️900, 👁22.9万)
- 详细版本: x.com//status/2053112758804357428 (❤️118, 👁3.8万)

## 技术架构：三层脸叠加

```
真人脸部 → AI小孩脸(固定人设) → 名人/角色脸(每期目标)
```

1. **第一层**：真人换成AI小孩（建立人设）
2. **第二层**：AI小孩换成目标名人（变脸效果）
3. 全程观众看到的"博主"是AI小孩，真人从未出现

## 具体技术栈

### 1. 生成AI小孩人设脸

- **工具**：GPT Image 2（用户最熟悉）或 Midjourney
- **要求**：正面照、均匀光照、中性表情、背景干净、14岁左右
- 生成后固定使用，不要每期换，**一致性是整个项目的基础**
- 建议生成多张，挑最自然、最适合反复换脸的那张
- 保存高清版本，这是整个项目的核心资产

### 2. 换脸引擎

- **主力**：FaceFusion（开源，ONNX模式，RTX 3060可跑）
  - 适合离线视频渲染，效果可精细调节
  - GitHub: https://github.com/facefusion/facefusion
  - 安装：`pip install facefusion` 或 clone后安装
- **实时方案**（如需直播）：DeepLiveCam
  - 适合实...

## 功能特性 / Features

- AI虚拟形象换脸视频项目
- 项目目标
- 原案例
- 技术架构：三层脸叠加
- 具体技术栈
- 关键难点和注意事项
- 环境信息
- 用户背景
- 下一步行动

## 使用示例 / Usage Examples

```
真人脸部 → AI小孩脸(固定人设) → 名人/角色脸(每期目标)
```

## 文件结构 / File Structure

```
SKILL.md
```

## 作者 / Author

Hermes Agent Community

## 许可证 / License

MIT License

---

更多技能请访问：[github.com/g3353534517-hue?tab=repositories](https://github.com/g3353534517-hue?tab=repositories)
