<div align="center">

# Crewly

**Team & operations hub for multi-store small businesses · Interactive demo**

*Clock-ins, schedules, shift swaps and weekly hours, with one record that the owner, managers, staff and accounting all share.*

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open-CF6A3C?style=for-the-badge)](https://sf-ryanyan.github.io/Crewly/)
[![Roles](https://img.shields.io/badge/Roles-4-123A3C?style=for-the-badge)](https://sf-ryanyan.github.io/Crewly/)
[![Industries](https://img.shields.io/badge/Industries-4-123A3C?style=for-the-badge)](https://sf-ryanyan.github.io/Crewly/)
[![Languages](https://img.shields.io/badge/English_%2F_中文-Bilingual-123A3C?style=for-the-badge)](#中文)

### ▶ **[Open the live demo](https://sf-ryanyan.github.io/Crewly/)**

**English** · [中文](#中文)

</div>

---

## What this is

Most small businesses can run one store from memory. At the second or third store, **people become the hardest thing to manage**. Clock-ins are on paper, the schedule lives in a group chat, shift swaps get agreed in private messages, and on payday nobody's numbers match.

Crewly is a working demo of one system that covers the whole loop: **who is working → who actually showed up → who changed what → what the hours are → what goes to payroll.**

**It is not a mockup and not a slide deck.** When a staff member clocks in on the store tablet, the manager sees it right away. When a manager edits a punch, the employee is asked to confirm it. When both stores approve the week, accounting can lock it and export it. Four roles, one shared set of data.

---

## 🎯 The problems it solves

| What it looks like today | What it costs you |
|---|---|
| Paper time cards, or "I'll text you when I get in" | Late arrivals and early exits are invisible. Hours get rounded in someone's favor |
| A manager quietly fixes a punch | No record of who changed it or why. Disputes become one word against another |
| The schedule is a photo in a group chat | People miss updates, two people show up for one shift, and nobody is on the next one |
| Shift swaps and days off are agreed in private messages | The manager finds out when someone doesn't show up |
| Hours are added up at the end of the pay period | Missing punches, surprise overtime, and the accountant chasing three people for answers |
| The owner has to call each store to know what's going on | Problems reach the owner days late, after they've already cost money |
| Permits, certificates and training expire quietly | Found during an inspection, not before it |

**If three of these seven sound familiar, this system pays for itself.**

---

## ⚙️ How it solves them

### 🏪 Store tablet: one time clock per store
- Staff clock in with a **4-digit PIN** on a tablet that stays in the store
- Clock-in opens **15 minutes before** the shift. Late arrivals are flagged automatically, and clock-ins with no scheduled shift go to the manager to confirm
- The tablet shows **today's team**: who is on the clock, who hasn't arrived yet, who starts later
- Leaving tablet mode needs the **manager's PIN**

### 👔 Owner: every store on one screen
- Who is on the clock right now, late arrivals, hours this week, and requests waiting for approval
- **Store comparison**: on-time rate, hours, pending approvals, and whether last week's hours are approved and next week's schedule is published
- A live **"today on the floor"** chart comparing the schedule with actual clock-ins, for each store
- Alerts for expiring permits, overdue training, overdue tasks and flagged receipts
- The owner can step in and approve anything, at any store

### 🧑‍💼 Store manager: run the store, not the paperwork
- **Scheduling**: add shifts in bulk, copy last week, click a cell to edit or hand a shift to someone else, then **publish** so the team is notified
- Built-in checks: **short-staffed days**, **overtime**, and **less than 10 hours between shifts**
- **One approvals inbox** for punch fixes, shift swaps, shift changes, days off and questions
- **Every punch edit is kept on record** with who made it, why, and the old and new times. The employee confirms it or asks a question
- A day off or a deactivated employee turns the shift into **"needs cover"**, and the manager fills it in two clicks
- Approves the week's hours when the week is done
- Each manager **only sees their own store**

### 🙋 Staff: everything on their phone
- Clock in or out (store Wi-Fi), see this week's hours, and see upcoming shifts
- **Swap**: ask a coworker to cover a shift. The coworker accepts first, then the manager approves
- **Change**: move a shift to another day, change the hours, or ask for the day off
- Send a **punch fix** if they forgot to clock in or out
- Confirm or question any change the manager made to their punches
- Tasks, store checklists, short training courses with quizzes, and signing for items like uniforms or keys

### 🧾 Accountant: clean numbers, locked in place
- Sees the approval progress for both stores at a glance
- **Locks the week** once both managers have approved. After that, no one can change those punches unless accounting unlocks it with a written reason
- **Exports the timesheet** (regular hours, overtime, edited and incomplete punches) for the payroll provider
- Reviews company-card receipts and flags the ones that don't match the card charge
- Sees the full punch-change history

---

## 🔁 One request, end to end

> **Kevin** can't make his Monday shift.

1. Kevin opens **My schedule** → taps **Swap** → picks **Sam** → adds a note
2. **Sam** gets the request on his home screen → taps **Accept**
3. The **manager** sees it in Approvals, already agreed by both people → **Approve**
4. The schedule updates and **both people are notified**. Everything is recorded
5. At the end of the week, the manager **approves the hours** → accounting **locks** the week → **exports** it for payroll

The same chain works for punch fixes, days off, schedule changes and new hires.

---

## ▶ Try it in 5 minutes

**[Open the demo](https://sf-ryanyan.github.io/Crewly/)**. No sign-up; the sample accounts are already filled in.

1. **Pick an industry**: Juice & Tea, Bakery, Restaurant, or Retail & Grocery. Each has its own shift times, checklists, tasks and training
2. **Sign in as the Owner**, then use **Skip ahead** in the demo bar to jump to 5:00 PM. The rest of the team keeps working: people clock in, someone runs late, checklists get done
3. **Open the store tablet** from the login page or the manager's screen, and clock someone in with a PIN (tap **Demo PINs** to see them)
4. **Switch to Staff** → **My schedule** → **Swap** a shift with a coworker → pick that coworker in the demo bar → **Accept**
5. **Switch to Manager** → **Approvals** → approve it. Then try **Schedule**, **Attendance** (edit a punch) and **Team** (add or deactivate someone)
6. **Switch to Accountant** → **Timesheets** → **Last week**. Lock it after Riverside's manager approves, then export

**Demo PINs (every industry):** Store 1 manager `1357` · Store 2 manager `2580` · the first staff member `2468`

The demo clock always starts at **8:00 AM today**. **Reset demo** clears everything and starts over. The **"Try this"** button lists suggested steps for each role.

---

## 🧭 Design principles

- **Nothing is changed silently.** Every punch edit has a name, a reason and a time, and the employee is told about it
- **Two keys for the money.** Managers approve hours; accounting locks them. A locked week can only be reopened with a written reason
- **Everyone sees only what they need.** A manager can't see the other store; staff see their own records; certain documents are owner-only
- **The store tablet comes first, the phone second.** Clock-ins happen in the store, so there's no need to track anyone's location

**Left out on purpose:** GPS tracking, fingerprints and face scans, Social Security numbers, and pay calculation. These carry the most legal and privacy risk, and they vary by state and company. Pay is calculated in the payroll provider you already use; Crewly gives it clean, approved hours.

---

## 🔧 From demo to production

Everything in this demo runs on sample stores, sample people and sample rules.

A real deployment is built around your business:

- Your own locations, positions, shift patterns, break and overtime rules, and approval steps
- Real accounts and sign-in, with data stored securely on a server instead of in the browser
- Connected to the tools you already use: payroll, POS, accounting
- Extended when you need it: more stores, more roles, inventory, ordering, reporting

**It can start small**, for example just clock-ins and scheduling for one store. Prove it works, then widen it.

---

## Technical notes

- One self-contained HTML file. No install, no build step, no backend
- Works on phone, tablet and desktop
- English and Chinese, switchable at any time
- 4 industries · 2 stores · 4 roles · 12 people
- Demo data is saved only in your own browser, and nothing is uploaded. **Reset demo** clears it

---

## About

**Designed and built by Ryan Yan** · Data Analyst

Requirements, workflow design, interface and interaction were all done by me.

This is one of several working demos built the same way: a system people can actually click through first, so a business owner can see it before we talk about building it.

---

## Disclaimer

This is a **demonstration build**. Every business, brand, store, address, person, supplier, schedule, punch and receipt in it is **fictional sample data** and represents no real business or person. "Crewly" and the store brands shown are fictional names used for this demo.

The break, overtime and attendance rules are **examples only**. They are not legal, HR or payroll advice. Real rules should be set to match your company policy and local law. Nothing shown here is a commercial offer.

---

## Copyright

**© 2026 Ryan Yan. All rights reserved.**

This repository is shared for viewing and for trying the live demo. No license is granted: the code, design, text and graphics may not be copied, modified, redistributed or used commercially without written permission from the author.

---
---

<div align="center">

# 中文

**多门店员工与运营管理系统 · 演示版**

*打卡、排班、换班和每周工时，老板、店长、员工、会计共用一份记录。*

### ▶ **[打开在线演示](https://sf-ryanyan.github.io/Crewly/)**

[English](#crewly) · **中文**

</div>

---

## 这是什么

一家店，老板靠记性就能管。开到第二、第三家店，**最难管的就变成了人**：打卡靠纸，排班靠群聊，换班私下说好，到了发工资那天，谁的数都对不上。

Crewly 是一套能真实操作的演示系统，把**谁上班 → 谁真的到了 → 谁改了什么 → 工时是多少 → 交给工资系统**这一整圈走通了。

**它不是截图，也不是方案书。** 员工在门店平板上打卡，店长马上就能看到；店长修改了打卡，员工会被要求确认；两家店都审批完这一周，会计就可以锁定并导出。四个角色，共用一份数据。

---

## 🎯 它解决的痛点

| 现实中的样子 | 造成什么后果 |
|---|---|
| 纸质打卡，或者“到了我发消息给你” | 迟到早退看不见，工时怎么算全凭人说 |
| 店长私下帮人改打卡 | 没有记录，不知道谁改的、为什么改，出了纠纷各说各的 |
| 排班表是群里的一张照片 | 有人没看到更新，一个班来了两个人，下一个班没人 |
| 换班、请假私下说好 | 店长要等到有人没来才知道 |
| 发工资前才开始算工时 | 漏打卡、意外加班，会计要追着三个人问 |
| 老板要挨个打电话问各店情况 | 问题传到老板那里时已经晚了几天，损失已经发生 |
| 证照、证书、培训悄悄过期 | 检查的时候才发现 |

**这七条里中了三条，这套系统就值得做。**

---

## ⚙️ 它怎么解决

### 🏪 门店平板：每家店一台打卡机
- 员工用 **4 位 PIN 码**在门店平板上打卡，平板一直放在店里
- 班次开始前 **15 分钟**才能打卡；迟到自动标记；没有排班的打卡会交给店长确认
- 平板上显示**今日员工**：谁在上班，谁还没到，谁几点来
- 退出平板模式需要**店长 PIN**

### 👔 老板：所有门店一屏看完
- 此刻在岗人数、今日迟到、本周工时、待审批事项
- **门店对比**：准时率、工时、待审批数量、上周工时有没有审批、下周排班有没有发布
- 每家店的**“今日在岗”**实时图，排班和实际打卡放在一起对比
- 证照到期、培训逾期、任务逾期、收据有问题都会提醒
- 老板可以直接介入，审批任何一家店的事项

### 🧑‍💼 店长：管店，不是管表格
- **排班**：批量添加班次、复制上周、点格子修改或把班交给别人；确认后**发布**，员工会收到通知
- 自动检查：**人手不够**、**加班**、**两个班间隔不足 10 小时**
- **一个审批入口**：补卡、换班、调班、请假和员工的疑问都在这里
- **每一次修改打卡都留记录**：谁改的、为什么改、改前改后的时间；员工确认，或者提出疑问
- 请假或停用员工后，空出来的班次会变成**“需补人”**，店长点两下就能安排人
- 一周结束后审批工时
- 每位店长**只能看到自己的店**

### 🙋 员工：手机上全部搞定
- 上下班打卡（门店 Wi-Fi），看本周工时和接下来的班次
- **换班**：请同事代班，同事先同意，再由店长批准
- **调班**：换到另一天、改时间，或者请一天假
- 忘记打卡可以提交**补卡**
- 对店长修改的打卡，可以确认或提出疑问
- 任务、门店清单、带小测验的短培训课程，以及制服、钥匙等物品的签收

### 🧾 会计：数字干净，锁定不变
- 一眼看到两家店的审批进度
- 两位店长都审批后，**锁定这一周**；锁定后，除非会计写明原因解锁，谁都不能再改这周的打卡
- **导出工时表**（正常工时、加班、修改过的打卡、不完整的打卡），交给工资系统
- 审核公司卡收据，金额和刷卡对不上的可以标记出来
- 查看完整的打卡修改记录

---

## 🔁 一个申请，从头走到尾

> **Kevin** 周一的班来不了。

1. Kevin 打开**我的排班** → 点**换班** → 选 **Sam** → 写一句说明
2. **Sam** 的首页收到请求 → 点**同意代班**
3. **店长**在待审批里看到这条申请，双方都已同意 → **批准**
4. 排班自动更新，**两个人都会收到通知**，全程有记录
5. 一周结束，店长**审批工时** → 会计**锁定** → **导出**交给工资系统

补卡、请假、调班、新员工入职，都是同样的流程。

---

## ▶ 5 分钟体验路线

**[打开演示](https://sf-ryanyan.github.io/Crewly/)**，不用注册，演示账号已经填好。

1. **选一个行业**：果汁茶饮、烘焙、餐厅、零售超市。每个行业的班次时间、清单、任务和培训都不一样
2. **以老板身份登录**，用演示栏里的**快进时间**跳到 17:00。其他员工会照常运作：有人打卡，有人迟到，清单陆续完成
3. **打开门店平板**（登录页或店长页面都能打开），用 PIN 帮员工打卡（点**演示 PIN 码**可以看到）
4. **切换到员工** → **我的排班** → 和同事**换班** → 在演示栏切换到这位同事 → **同意代班**
5. **切换到店长** → **待审批** → 批准。再试试**排班**、**考勤**（修改一次打卡）、**团队**（添加或停用员工）
6. **切换到会计** → **工时表** → **上周**。等 Riverside 的店长审批后锁定，再导出

**演示 PIN（所有行业通用）：** 第一家店店长 `1357` · 第二家店店长 `2580` · 第一位员工 `2468`

演示时间每次都从**今天早上 8:00** 开始。点**重置演示**会清空所有数据，从头开始。右下角的**“试试这些”**列出了每个角色可以尝试的操作。

---

## 🧭 设计原则

- **任何修改都不会悄悄发生。** 每次修改打卡都有人名、原因和时间，员工也会收到通知
- **跟钱有关的事，两道关。** 店长审批工时，会计锁定；锁定后只有写明原因才能重新打开
- **每个人只看到自己需要的。** 店长看不到另一家店，员工只看自己的记录，部分文件只有老板能看
- **门店平板为主，手机为辅。** 打卡在店里完成，不需要追踪任何人的位置

**故意不做的功能：** GPS 定位、指纹和人脸识别、社会安全号码（SSN）、工资计算。这几项的法律和隐私风险最大，而且每个州、每家公司的规定都不一样。工资交给你现在用的工资系统来算，Crewly 负责提供干净、已审批的工时。

---

## 🔧 从演示到正式上线

这个演示里的门店、人员和规则都是示例。

正式版会围绕你的生意来做：

- 你自己的门店、岗位、班次模式、休息和加班规则、审批流程
- 真实账号登录，数据安全地存在服务器上，而不是浏览器里
- 接入你已经在用的工具：工资系统、POS 收银、记账软件
- 需要时再扩展：更多门店、更多角色、库存、订货、报表

**可以从小做起**，比如先在一家店只用打卡和排班。验证有效之后，再逐步扩大。

---

## 技术说明

- 单个 HTML 文件，不用安装，不用打包，没有服务器
- 手机、平板、电脑都能用
- 中英文随时切换
- 4 个行业 · 2 家门店 · 4 个角色 · 12 个人
- 演示数据只保存在你自己的浏览器里，不会上传。点**重置演示**即可清空

---

## 关于作者

**由 Ryan Yan 设计与开发** · 数据分析师

需求梳理、流程设计、界面和交互都由我完成。

这是我用同样方式做的几个演示系统之一：先做出一个能真正点进去用的系统，让老板先看到效果，再谈怎么为他搭建。

---

## 免责声明

这是一个**演示版本**。里面所有的公司、品牌、门店、地址、人员、供应商、排班、打卡和收据都是**虚构的示例数据**，不代表任何真实的公司或个人。“Crewly”以及演示中出现的门店品牌，都是为这个演示虚构的名称。

休息、加班和考勤规则**仅为示例**，不构成法律、人事或工资方面的建议。实际规则应按贵公司政策和当地法律设定。本页面内容不构成任何商业要约。

---

## 版权

**© 2026 Ryan Yan. All rights reserved.**

本仓库仅供浏览和在线试用演示，不授予任何使用许可。未经作者书面许可，不得复制、修改、重新发布或商业使用本项目的代码、设计、文字和图形。
