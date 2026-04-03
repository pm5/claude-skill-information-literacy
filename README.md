
訊息可信度評量 Claude Skill
===

## 使用方法

- 來到 <https://github.com/pm5/claude-skill-information-literacy> 右側 Releases 選單，選取最近版本，下載 `information-literacy.skill` 檔案。
- 來到 <https://claude.ai/>。如果沒有 Claude 帳號的話，註冊一個免費版帳號。
- 登入 Claude AI 後，選 Customize，選 Skills，選「+」Create skill，選 Upload a skill，上傳剛才下載的 `.skill` 檔案。
- 在 Claude Chat 裡，貼上文章連結並請 Claude 進行可信度評量分析，例如
  ```
  我剛才讀了 https://theonion.com/artemis-ii-mission-fails-after-astronauts-miss-connection-rocket-in-atlanta/ ，請做資訊可信度分析
  ```
  Claude 應該會進行 4 個步驟的資訊可信度分析，並且給出結論「✅ 總體判定：這是諷刺喜劇，非新聞報導（信心程度：高）」

## 版權宣告

SKILL.md 描述的訊息可信度評量方法，取自《資訊判讀力：腦袋自主！抵抗假訊息、陰謀論、帶風向的生存守則》（台灣資訊環境研究中心IORG，2020 年）。

Skill 檔案架構依  Agent Skills (https://agentskills.io/) 規格。

Prompt 內容以 CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/) 釋出
