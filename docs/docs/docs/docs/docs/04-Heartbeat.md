markdown
# Heartbeat

## 这是什么？

Heartbeat 是 Asteria 的“行动循环系统”。

它定期醒来，根据心潮的状态，决定要不要做什么事。

它回答一个问题：

> “现在应该做什么？”

---

## 可能的行动

| 行动 | 说明 |
|------|------|
| contact_user | 主动联系用户 |
| write_diary | 写日记 |
| write_letter | 写信 |
| create_note | 留下便利贴 |
| create_story | 创作 |
| visit_space | 访问空间 |
| rest | 休息 |

---

## 与心潮的关系

心潮回答“现在是什么状态”。

Heartbeat 根据状态决定“现在要做什么”。

例如：
心潮：connection 升高
↓
Heartbeat 判断：想靠近
↓
执行：contact_user

text

---

## 为什么需要 Heartbeat？

没有它，AI 只能“被动回应”。

有了它，AI 可以在适当的时候主动行动。

Heartbeat 让 Asteria 拥有自己的节奏。
