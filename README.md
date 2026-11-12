# saudi-legal

[العربية](#العربية) · [English](#english)

---

## العربية

مهارة (Skill) لـ Claude تُنتج تحليلاً نظامياً سعودياً: تكييف الواقعة، ردّها إلى نصّها، الاستشهاد بأرقام المواد، تحديد الجهة القضائية المختصة والمواعيد النظامية، ثم تقدير المركز النظامي. تجيب بالعربية أو الإنجليزية حسب لغة المستخدم.

### ماذا تفعل

- **جامعة:** تعمل على أي نظام أو لائحة سعودية، وتنقل النص من المصدر الرسمي متى توفر البحث.
- **اشرح المادة:** لكل مادة بطاقة فيها حالتها (سارية/معدّلة/ملغاة وما حلّ محلها)، نصها، خلاصتها، ما يدخل فيها، ما يُستثنى منها، والمواد المرتبطة.
- **مستشار تحاوره:** يجاوب أولاً ثم يعلّل، يسأل عن الوقائع المفصلية، ويكلّمك بلغتك.
- **لا تختلق مادة:** كل استشهاد موسوم بدرجة يقينه.

### ماذا تغطي

| الملف | الموضوع |
|---|---|
| `SKILL.md` | المنهج، وقاعدة «لا تُختلق مادة أبداً»، ودرجات اليقين في الاستشهاد |
| `references/kharitat-al-anzimah.md` | خريطة الأنظمة السعودية |
| `references/madani.md` | المعاملات المدنية |
| `references/tijari.md` | التجاري والشركات |
| `references/jazai.md` | الجزائي |
| `references/ijraat.md` | الإجراءات والمرافعات والمواعيد |
| `references/qawaleb.md` | قوالب الصياغة |

### التثبيت

```bash
npx skills add Sulaimannnnnn/saudi-legal-skill
```

أو انسخ مجلد `skills/saudi-legal` إلى مجلد المهارات عندك (`~/.claude/skills/`)، أو ارفعه مضغوطاً من إعدادات المهارات في Claude.

### انضباط الاستشهاد

المهارة تَسِم كل استشهاد بدرجة يقينه، وتضع تنبيه **[يلزم التحقق من رقم المادة]** متى لم يكن الرقم مؤكداً. المواضع الموسومة بـ«تحقق» داخل الملفات مقصودة: راجعها على المصدر الرسمي [laws.boe.gov.sa](https://laws.boe.gov.sa) قبل الاعتماد عليها.

### إخلاء مسؤولية

هذه المهارة أداة مساعدة للبحث والصياغة، وليست استشارة قانونية ولا تغني عن محامٍ مرخّص. الأنظمة تُعدَّل، فتحقق دائماً من النص الساري في مصدره الرسمي قبل الاستناد إليه أمام أي جهة.

### المساهمة

التصحيحات مرحّب بها عبر Issues أو Pull Requests، بشرط إرفاق رابط المصدر الرسمي لأي رقم مادة.

---

## English

A Claude Skill for Saudi law: it characterizes the facts (تكييف), ties them to the governing text, cites article numbers, identifies the competent court and the statutory deadlines, and then assesses the legal position. It answers in Arabic or English, following the language the user writes in.

### What it does

- **All Saudi laws:** works on any Saudi law or regulation, and takes the text from the official source whenever search is available.
- **Explain an article:** one card per article with its status (in force / amended / repealed, and what replaced it), its text, a plain summary, what falls under it, what is excepted, and related articles.
- **A counsel you talk to:** answers first, then gives the reasons, asks for the decisive facts, and speaks your language.
- **Never invents an article:** every citation carries its certainty grade.

### What it covers

| File | Subject |
|---|---|
| `SKILL.md` | The method, the "never invent an article" rule, and the certainty grades for citations |
| `references/kharitat-al-anzimah.md` | Map of Saudi laws and regulations |
| `references/madani.md` | Civil transactions |
| `references/tijari.md` | Commercial and companies law |
| `references/jazai.md` | Criminal law |
| `references/ijraat.md` | Procedure, pleadings and deadlines |
| `references/qawaleb.md` | Drafting templates |

The skill files themselves are written in Arabic, the language of the Saudi laws they map.

### Install

```bash
npx skills add Sulaimannnnnn/saudi-legal-skill
```

Or copy the `skills/saudi-legal` folder into your skills folder (`~/.claude/skills/`), or upload it zipped from the skills settings in Claude.

### Citation discipline

The skill grades every citation by how certain it is, and adds a **[article number must be verified]** flag whenever the number is not certain. The places marked «تحقق» (verify) inside the files are intentional: check them against the official source, [laws.boe.gov.sa](https://laws.boe.gov.sa), before relying on them.

### Disclaimer

This skill is a research and drafting aid. It is not legal advice and does not replace a licensed lawyer. Laws are amended, so always check the text in force at its official source before relying on it before any authority. The Arabic text of a Saudi law governs; any English rendering is unofficial.

### Contributing

Corrections are welcome through Issues or Pull Requests, provided each article number comes with a link to its official source.
