(َََََ
# 🚀 مشروع بشار  التقني | Bashar's Tech Lab

أنا **بشار ** من الأردن، أعمل كـ **Validator** (موثّق) و **Miner** (عدّان) في شبكة Pi. هذا المستودع هو معملي الخاص لتوثيق تجارب الذكاء الاصطناعي ومصادر العملات الرقمية.

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
# كود تجريبي لاختبار الذكاء الاصطناعي - بشار 
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
# تعريف الدالة أولاً
def ai_assistant(user_input):
    # تحويل النص لمدخلات صغيرة لضمان التعرف على الكلمات
    user_input = user_input.lower()
    
    responses = {
        "hi": "Hello Bashar! How can I help you?",
        "pi": "Pi Network is the first digital currency you can mine on your phone.",
        "llama": "Llama 3.2 is running locally on your device!"
    }
    
    # البحث عن الكلمة المفتاحية أو رد افتراضي في حال عدم وجودها
    return responses.get(user_input, "I'm not sure how to respond to that.")

# تجربة الكود
user_say = "pi"
print("AI Response:", ai_assistant(user_say))
def ai_assistant(user_input):
    # تحويل النص لمدخلات صغيرة لضمان التعرف على الكلمات
    user_input = user_input.lower()
    
    # القاموس الذي يحتوي على الردود
    responses = {
        "hi": "Hello Bashar! How can I help you?",
        "pi": "Pi Network is the first digital currency you can mine on your phone.",
        "llama": "Llama 3.2 is running locally on your device!"
    }
    
    # البحث عن الكلمة، وإذا لم توجد يعطي رداً افتراضياً
    return responses.get(user_input, "عذراً، لا أملك إجابة لهذه الكلمة حالياً.")

# حلقة تكرار (Loop) لجعل البرنامج يعمل باستمرار
print("--- مرحباً بك في مساعدك البرمجي (اكتب 'exit' للخروج) ---")

while True:
    # طلب المدخلات من المستخدم حياً
    user_say = input("اسألني عن شيء (hi, pi, llama): ")
    
    # شرط للخروج من البرنامج
    if user_say.lower() == "exit":
        print("وداعاً! أتمنى لك يوماً سعيداً.")
        break
        
    # استدعاء الدالة وطباعة النتيجة
    result = ai_assistant(user_say)
    print("AI Response:", result)
    print("-" * 30)
def ai_assistant(user_input, name):
    user_input = user_input.lower()
    
    responses = {
        "hi": f"Hello {name}! كيف يمكنني مساعدتك اليوم؟",
        "pi": "Pi Network هي أول عملة رقمية يمكنك تعدينها من هاتفك.",
        "llama": "Llama 3.2 يعمل الآن محلياً على جهازك!"
    }
    
    return responses.get(user_input, "عذراً، لا أعرف هذه الكلمة بعد.")

# الخطوة الجديدة: طلب الاسم قبل بدء الحلقة
user_name = input("مرحباً! ما هو اسمك؟ ")
print(f"أهلاً بك يا {user_name} في مساعدك الذكي.")
print("--- (اكتب 'exit' للخروج) ---")

while True:
    user_say = input(f"\n[{user_name}]: اسأل عن شيء: ")
    
    if user_say.lower() == "exit":
        print(f"وداعاً يا {user_name}! نراك لاحقاً.")
        break
        
    result = ai_assistant(user_say, user_name)
    print("AI Response:", result)
def ai_assistant(user_input, name):
    user_input = user_input.lower()
    
    # القاموس الذكي (إجابات مفصلة)
    responses = {
        "hi": f"أهلاً بك يا {name}! أنا مساعدك البرمجي، كيف أخدمك؟",
        "pi": "عملة Pi Network هي مشروع عملة رقمية تهدف للتعدين عبر الهاتف المحمول.",
        "llama": "Llama 3.2 هو نموذج ذكاء اصطناعي قوي جداً يمكن تشغيله محلياً.",
        "code": "البرمجة هي لغة المستقبل، وأنت الآن تسير في الطريق الصحيح!"
    }

    # محرك البحث الجزئي (الذكاء في فهم الجملة)
    for key in responses:
        if key in user_input: # يبحث إذا كانت الكلمة موجودة داخل جملتك
            return responses[key]
            
    return "هذه معلومة جديدة عليّ، سأحاول تعلمها يا " + name

# واجهة المستخدم داخل تطبيقك
user_name = input("ما اسمك؟ ")
print(f"مرحباً {user_name}، أنا أسمعك الآن...")

while True:
    user_say = input(f"\n[{user_name}]: ")
    
    if user_say.lower() in ["exit", "خروج"]:
        print(f"وداعاً يا {user_name}")
        break
        
    result = ai_assistant(user_say, user_name)
    print("AI Response:", result)
