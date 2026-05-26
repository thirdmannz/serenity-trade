# Serenity Trade — Claude Code Skills Pack
# Serenity 交易思維 — Claude Code 技能包

> Distilled from @aleabitoreddit (Serenity) — former Reddit WSB trader, AI/Semi Supply Chain Analyst.  
> 提煉自 @aleabitoreddit（Serenity）— 前 Reddit WSB 交易者，AI/半導體供應鏈分析師。

---

## What is this? / 這是什麼？

A set of **Claude Code Skills** that encode [Serenity's (@aleabitoreddit)](https://x.com/aleabitoreddit) trading methodology — so that when you discuss stocks, supply chains, or trade decisions with Claude, it automatically applies his framework to your questions.

這是一套 **Claude Code Skills**，將 [Serenity (@aleabitoreddit)](https://x.com/aleabitoreddit) 的交易方法論寫入 Claude Code 的技能系統。當你在 Claude 裡討論選股、供應鏈研究或交易決策時，Claude 會自動套用他的框架來回答你的問題。

**Who is Serenity? / Serenity 是誰？**  
A former AI research scientist and Reddit r/WSB trader who migrated to X in July 2025. He reverse-engineers entire AI/semiconductor supply chains to find overlooked chokepoint stocks — before institutional money arrives. His YTD returns have reached +1,116% at peak during the 2025–2026 AI photonics supercycle.

前 AI 研究科學家、RISC-V Foundation 成員，2025 年 7 月從 Reddit 轉移至 X，目前在 X 擁有 17 萬以上粉絲。他的方法論是：逆向拆解整個 AI/半導體供應鏈，在機構資金進場前，找到市場忽視的關鍵瓶頸股票。AI 光子學超週期期間，其投資組合年化報酬最高達 +1,116%。

---

## Skills / 技能清單

| Skill | Triggers when... / 觸發時機 |
|---|---|
| `aleabit-chokepoint-thesis` | 尋找 AI/半導體供應鏈主題標的；問「為什麼不直接買 NVDA」 |
| `aleabit-rotation-map` | 問下一個 AI capex 輪動主題在哪；機構資金流向分析 |
| `aleabit-stock-selection` | 篩選個股；評估某檔是否符合 thesis 標準 |
| `aleabit-research-process` | 開始做某標的的 due diligence；問「怎麼研究這檔」 |
| `aleabit-position-sizing` | 決定買多少；問是否該全倉 |
| `aleabit-risk-management` | 問槓桿設定；地緣風險時如何對沖 |
| `aleabit-entry-exit` | 決定何時進場/加碼/出場；問持有多久 |
| `aleabit-psychology` | 持倉回調中動搖；被別人叫做「散戶追風」時 |

---

## Core Philosophy / 核心方法論

**The Strait of Hormuz Analogy / 荷莫茲海峽比喻**

> "Just as 20% of global oil passes through the Strait of Hormuz... I identify the biggest chokepoints in hyperscaler supply chains before anyone else. Then go long."  
> — @aleabitoreddit

Don't buy the obvious beneficiary (NVDA, MSFT, META). Buy what they **must** depend on — the narrow, concentrated node that the entire buildout cannot route around.

不要買顯而易見的受益者（NVDA、MSFT）。要買他們**必須依賴**的東西 — 那個整個 AI 建設無法繞過的關鍵瓶頸節點。

**The Rotation Sequence / 輪動順序 (as of mid-2026)**

```
Phase 1: HBM/Memory          ← complete (機構已進場)
Phase 2: Optical Transceivers ← mostly done (尾聲)
Phase 3: ELS / SiPh / Glass Core ← NOW (現在主攻)
Phase 4: 800V DC Power Infra  ← emerging (剛開始)
```

---

## Installation / 安裝方式

Copy the `skills/` folder to your Claude Code global skills directory:

將 `skills/` 資料夾複製到你的 Claude Code 全域 skills 目錄：

**Windows**
```powershell
xcopy /E /I skills "%USERPROFILE%\.claude\skills"
```

**macOS / Linux**
```bash
cp -r skills/ ~/.claude/skills/
```

Skills auto-trigger based on your question context — no slash commands needed.  
技能會根據你的問題自動觸發，不需要手動輸入指令。

---

## Usage Examples / 使用範例

Open a new Claude Code session and try questions like:  
開啟新的 Claude Code session，試著問：

```
"I'm looking at $SIVE — is this an aleabit-style chokepoint play?"
→ triggers: chokepoint-thesis + stock-selection + research-process

"Photonics has already run. What's the next rotation?"
→ triggers: rotation-map

"I bought $LPK at 30% of my portfolio. Am I too concentrated?"
→ triggers: position-sizing + risk-management

"My thesis is right but the stock is down 25% on no news. Hold or cut?"
→ triggers: psychology + entry-exit
```

---

## Data Sources / 資料來源

Skills built from:
- [Inside the Mind of Serenity](https://singularityresearchfund.substack.com/p/inside-the-mind-of-serenity-aleabitoreddit) — Singularity Research Fund Substack
- [Serenity Background Profile](https://www.moomoo.com/community/feed/here-s-the-backstory-on-the-twitter-account-aleabitoreddit-x-116401268326405) — Moomoo Community
- [Serenity's AXTI Trade](https://capitalblueprint.substack.com/p/serenitys-axti-trade-when-a-tiny) — Capital Blueprint
- [The Photonics Valuation Problem](https://www.archetype-research.com/p/the-photonics-valuation-problem-sive) — Archetype Research
- Direct tweet quotes from @aleabitoreddit (via search excerpts), April–May 2026

Last refreshed: **May 2026**

---

## Disclaimer / 免責聲明

These skills encode one trader's **methodology and thinking framework** — not financial advice.  
All investment decisions carry risk. Past performance does not guarantee future results.  
Always do your own research before making any trade.

本技能包僅記錄一位交易者的**方法論與思維框架**，不構成任何投資建議。  
所有投資決策均有風險，過去表現不代表未來結果。  
做任何交易前請自行做完整研究。

---

*Built with [Claude Code](https://claude.ai/code) — for educational and research purposes.*
