
# 🚀 مشروع بشار المجالي التقني | Bashar's Tech Lab

أنا **بشار المجالي** من الأردن، أعمل كـ **Validator** (موثّق) و **Miner** (عدّان) في شبكة Pi. هذا المستودع هو معملي الخاص لتوثيق تجارب الذكاء الاصطناعي ومصادر العملات الرقمية.

---

## 🥧 قسم عملة Pi (Pi Network Resources)
* **[Pi Blockexplorer](https://minepi.com/blockexplorer/):** لمتابعة معاملات البلوكشين مباشرة.
* **[Pi Whitepaper](https://minepi.com/white-paper/):** المصدر الرسمي لفهم اقتصاد الشبكة.
* **[Pi Apps GitHub](https://github.com/pi-apps):** الأكواد الرسمية لتطبيقات النظام البيئي.

---

## 🤖 قسم الذكاء الاصطناعي (AI Tools)
### 📊 تحليل البيانات والعملات
* **Arkham Intelligence:** لتتبع المحافظ والتدفقات المالية الرقمية.
* **Token Metrics:** لتحليل اتجاهات السوق والعملات الناشئة.

### 🎨 صناعة المحتوى والتصميم
* **Midjourney:** لإنشاء صور احترافية بجودة سينمائية.
* **Luma Dream Machine:** لتحويل الصور الثابتة إلى فيديوهات واقعية.

### 💻 أدوات المطورين (Coding)
* **GitHub Copilot:** مساعدك الذكي لكتابة الأكواد داخل المستودع.
* **Cursor AI:** أفضل محرر أكواد برمجية مدعوم بالكامل بالـ AI.

---

## 📱 تجارب محلية (Mobile LLMs)
* توثيق تشغيل موديلات مثل **Llama 3.2** و **Gemma** مباشرة على الهاتف المحمول.

---
*تم إنشاء هذا الدليل لعام 2026 ليكون المرجع التقني الشامل لمشاريعي.*
# كود تجريبي لاختبار الذكاء الاصطناعي - بشار المجالي
def ai_assistant(user_input):
    responses = {
        "hi": "Hello Bashar! How can I help you today?",
        "pi": "Pi Network is the future of social cryptocurrency.",
        "llama": "Llama 3.2 is running perfectly on your mobile device!"
    }
    
    # الرد بناءً على الكلمة المفتاحية أو رد افتراضي
    return responses.get(user_input.lower(), "That's an interesting point! Tell me more.")

# تجربة الكود
user_say = "pi" 
print("AI Response:", ai_assistant(user_say))
def ai_assistant(user_input):
    # تحويل النص لمدخلات صغيرة لضمان التعرف على الكلمات مهما كانت طريقة كتابتها
    user_input = user_input.lower()
    
    responses = {
        "hi": "Hello Bashar! How can I help you today?",
        "pi": "Pi Network is the future of social cryptocurrency.",
        "llama": "Llama 3.2 is running perfectly on your mobile device!"
    }
    
    # الرد الافتراضي في حال كانت الكلمة غير موجودة
    return responses.get(user_input, "I'm still learning about that! Try asking about Pi or Llama.")

# تجربة الكود
user_say = "pi"
print("AI Response:", ai_assistant(user_say))
