### 2. The Theory File

```markdown
---
tags: [theory, security, linux]
---

# Non-Interactive Shell

## 🧐 What is it?

Non-interactive shell ဆိုတာ user တစ်ယောက်ကို command prompt (terminal) သုံးခွင့် မပေးတာ ဖြစ်ပါတယ်။ Linux မှာ ပုံမှန်အားဖြင့် user တွေက `/bin/bash` ကို သုံးပေမဲ့ service account တွေအတွက် shell ကို ပိတ်ထားသင့်ပါတယ်။

## 🛡 Why use it? (Security Perspective)

- **Attack Surface Reduction:** အကယ်၍ account ရဲ့ password ပေါက်ကြားသွားရင်တောင် attacker က server ထဲမှာ command တွေ ရိုက်လို့မရတော့ဘူး။
- **System Accounts:** Service တွေ (Backup, Database, Web Server) သည် program run ရန်သာ လိုအပ်ပြီး လူကိုယ်တိုင် login ဝင်ရန် မလိုပါ။

## 📂 Common Shells

1. **`/sbin/nologin`**: Login တားဆီးပြီး "This account is currently not available" ဆိုတဲ့ message ပြပေးတယ်။
2. **`/usr/bin/false`**: ဘာမှမပြောဘဲ login ကို ချက်ချင်း reject လုပ်တယ်။

---

## 🔗 Related

- [[server-hardening]]
- [[linux-user-basics]]
```
