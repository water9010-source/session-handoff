# 對話接續交接 Session Handoff — Claude Skill

對話越長，AI 每回一句都要把前面全部再算一次，越來越花 token。這個 Claude Skill 讓 AI 在對話變得不划算時，把目前進度整理成一份短交接檔，開一個新的對話視窗接著做原本的工作。

## 怎麼用
- 你說「交接」「換視窗」：AI 直接寫交接檔、開新視窗接續。
- 你說「我要睡覺了」：AI 當作你整晚不會回應，判定不划算時自己交接、自己開新視窗。需要你本人確認的事（帳號、密碼、花錢、刪檔）不做，留到你醒來。
- 其他時候：AI 自己發現對話太長，會先寫好交接檔，再提出開新視窗，你按了才開。

## 限制
- 只在 Claude Code 桌面版測過。
- AI 看不到精確的 token 數，只能看跡象判斷。
- 一晚只能自動換一次視窗；說「我要睡覺了」之後同一視窗自己開新視窗，還沒實測。
- Skill 內容是繁體中文；不保證能省多少 token。

## 取得
購買：https://aquaquest23.gumroad.com/l/ncrbbh

## 開發者
LI WEI，「治理系統 Pro」的開發者。這個 Skill 是在治理系統 Pro 的七步流程下製作，並經過另一個 AI 對話獨立檢查。

**使用條件**
可以自己使用、可以修改。修改後的版本，或提供給別人時，必須保留 LICENSE.txt 與「原始創作者：LI WEI」這行字，不得刪除或改成別人的名字。

---

English: A Claude Skill (Traditional Chinese) that writes a short handoff file and continues the task in a fresh conversation when the current one becomes token-expensive. Tested only on Claude Code desktop. Get it on Gumroad: https://aquaquest23.gumroad.com/l/ncrbbh. Developer: LI WEI, creator of 治理系統 Pro (Governance System Pro). You may use and modify it; any modified or shared copy must keep LICENSE.txt and the line "Original author: LI WEI".
