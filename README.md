# 📱 Telegram & WhatsApp 专用接码平台 (Global SMS Bot)

专门针对社交平台优化的真实实体卡资源，注册不封号，短信秒到。

### 🌟 业务亮点
- **社交专线：** 独家真实号段，完美通过 Telegram 和 WhatsApp 的环境检测。
- **极速响应：** 全自动化系统，无需等待，验证码即收即用。
- **全球覆盖：** 100+ 国家任选，轻松注册海外社交账号。

---

### 🔗 立即开始 (Official Link)
👉 **官方接码平台：[https://glcn.uk/](https://glcn.uk/)**
💬 **Telegram 客服：** [点击跳转联系](https://t.me/AK00091)

---

### 🛠 开发者 API 集成
```python
# 集成示例：连接社交接码网关
print("Connecting to Social SMS Gateway...")
print("Line Status: Ready")
# 🤖 Telegram & WhatsApp 自动化集成 SDK (Sms-Bot-V2)

本项目是针对 [glcn.uk](https://glcn.uk) 平台开发的社交平台专用接码 SDK，支持 Telegram 和 WhatsApp 的批量注册与自动化验证。

## 🌟 核心优势
- **社交专线**：内置高权重 Real SIM 实体号段，完美通过 TG/WA 环境检测。
- **全自动轮询**：针对社交平台收码慢的痛点，优化了 API 轮询机制。
- **极速响应**：支持高并发调用，适合工作室批量起号场景。

## 🚀 Python 集成示例
```python
from glcn_bot_sdk import TelegramBot

# 初始化
bot = TelegramBot(api_key="YOUR_API_KEY")

# 申请 TG 专线号码 (以英国 +44 为例)
phone = bot.request_number(country="uk", service="tg")
print(f"正在申请号码: {phone}")

# 监听验证码
code = bot.wait_for_code()
print(f"收到 Telegram 验证码: {code}")
