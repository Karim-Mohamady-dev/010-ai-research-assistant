# Sourcewell — 010-ai-research-assistant

يجمع Sourcewell المصادر، ويتحقق مما تتفق عليه، ويكتب تقريرا موثقا يمكنك تسليمه لصاحب القرار.

## ما هذا المشروع؟

صفحة هبوط ثنائية اللغة (العربية RTL والإنجليزية LTR) لـ Sourcewell. Sourcewell collects sources, checks what they agree on, and writes a sourced report you can hand to a decision maker.

## التشغيل محليا

```bash
npm install
npm run dev
npm run build
```

## المزايا

- مبدل لغة ظاهر، والتفضيل محفوظ في localStorage
- الترجمات في `locales/en/common.json` و `locales/ar/common.json`
- نموذج تجربة مجانية مع تحقق من البريد
- أقسام: البطل، المزايا، كيف يعمل، آراء نموذجية، الأسعار، الأسئلة الشائعة، الدعوة الأخيرة
- قسم كشف الشعار (tagline reveal) مع تحريك كلمة بكلمة
- الأسعار غير المؤكدة تظهر كعناصر نائبة `{{price}}`

## ملاحظات

- البيانات المعروضة تجريبية وموسومة كعينات.
- لا توجد أرقام أو شهادات مخترعة.
