# Your AI memory

**English** · [Русский](#русский) · [עברית](#עברית)

An assistant that remembers you. It is the AI you already talk to — ChatGPT, Claude or Grok —
with rules that make it keep your notes, your health and your documents in your own Notion,
show you and ask before it sends, buys or deletes anything, and check its facts. You set it up
from your phone.

This page is a template: you make your own private copy of it once. Your copy holds your
settings and takes each new release of the engine; your AI reads its rules from the release
your instructions name.

## What you need

- a GitHub account (free);
- a Notion account;
- one of: ChatGPT (the Plus plan; in beta), Claude (the Pro plan) or Grok.

## Four steps on your phone

Use your phone's browser, on the full GitHub site.

1. **Your copy.** At the top of this page: «Use this template» → «Create a new repository».
   Owner: your own account, not an organisation. Name: anything, for example `my-memory`.
   Choose **Private** and press «Create repository from template». Add nothing to it before
   step 3: the first setup runs only on a fresh copy.
2. **One setting.** In your new repository: **Settings** (on a phone it may be under «…») →
   **Actions** → **General** → under «Workflow permissions» tick **«Allow GitHub Actions to create
   and approve pull requests»** → **Save**. Your copy needs it to save your settings and to take
   its updates.
3. **Setup.** **Actions** → **setup** → **Run workflow**. Fill in the form:
   - **Your AI** — choose it;
   - **Your language** — as a code: `ru`, `en`, `he`, `uk`, `de`, `pt-BR`;
   - **Your country** — two letters: `IL`, `DE`, `US`;
   - **Your time zone** — `Asia/Jerusalem`, `Europe/Berlin`, `America/New_York`;
   - **Your name** — as your AI will call you: a name, up to five words;
   - **For the grammar of your language** — female or male;
   - **Other languages you work in** — codes, comma-separated, such as `en,he`; or leave it empty.

   Press **Run workflow**. In a minute or two an Issue appears: **«Your assistant's
   instructions»**.
4. **Your AI.** Do what the Issue says: paste the text into your AI's settings, connect Notion,
   send the first message. Your AI sets up your Notion with you.

If setup stops with an error, its run says why and what to change; then start it again with
**Run workflow**.

## Good to know

- Your notes stay in your Notion. Your repository holds your settings and the rules: keep it
  private.
- Your copy looks for a new release every week and takes it no sooner than a week after it is
  published, once its checks pass. An update that changes the workflows themselves it cannot
  apply: it opens an Issue instead, and for now such an update needs someone who can apply it
  by hand.
- Your AI keeps the instructions you pasted until you paste new ones. When a release changes
  them, your copy tells you, usually within a day: an Issue **«Your assistant's instructions»** with the
  new text, and GitHub notifies you of it. Paste it over the old one; until you do, your AI goes
  on with the rules of the release it has. If a check finds a mistake in your copy, the new text
  waits until that is put right; the alarm says what is wrong.
- How GitHub tells you is yours to choose: by e-mail — in GitHub's notification settings — or
  on your phone — in the GitHub app: Profile, the gear, Notifications, «Direct mentions». With
  neither, the page still waits in your copy.
- To change your settings — your AI, language, country, time zone, name, the grammar or your
  work languages: **Actions** → **settings** → **Run workflow**. Every answer there already stands
  on «keep as it is» — the lists on their first item, the text fields empty: change what you need,
  all of it in one run, and press **Run workflow**. Usually within a few minutes — at the latest
  after the night's check — a new Issue **«Your assistant's instructions»** brings the text to
  paste; answers that are your settings already bring no new Issue, only a note on the one you
  have. You edit no file. The run's own page under **Actions** says what it did; if no Issue has
  come by the next day, look there, then run it again.
- The checks run in your repository on GitHub Actions, from your GitHub account's free monthly
  allowance for private repositories.

---

## Русский

**Память вашего ИИ.** Помощник, который вас помнит. Это тот ИИ, с которым вы уже разговариваете, —
ChatGPT, Claude или Grok — с правилами: он ведёт ваши заметки, здоровье и документы в вашем
собственном Notion, показывает и спрашивает, прежде чем что-то отправить, купить или удалить, и
проверяет факты. Настраивается с телефона.

Эта страница — шаблон: вы один раз делаете с неё свою закрытую копию. Копия хранит ваши настройки
и принимает каждый новый выпуск движка; ваш ИИ читает правила того выпуска, который назван в его
инструкциях.

Кнопки и поля GitHub — на английском; ниже они названы так, как выглядят на экране.

### Что нужно

- учётная запись GitHub (бесплатная);
- учётная запись Notion;
- одно из: ChatGPT (тариф Plus; бета), Claude (тариф Pro) или Grok.

### Четыре шага с телефона

Откройте GitHub в браузере телефона, полную версию сайта.

1. **Ваша копия.** Вверху этой страницы: «Use this template» → «Create a new repository».
   Owner — ваша собственная учётная запись, не организация. Имя любое, например `my-memory`.
   Выберите **Private** и нажмите «Create repository from template». До шага 3 ничего в копию
   не добавляйте: первая установка идёт только на свежей копии.
2. **Одна настройка.** В новой копии: **Settings** (на телефоне может быть под «…») →
   **Actions** → **General** → в разделе «Workflow permissions» отметьте **«Allow GitHub Actions to
   create and approve pull requests»** → **Save**. Без этого копия не сможет сохранить ваши
   настройки и принимать обновления.
3. **Установка.** **Actions** → **setup** → **Run workflow**. Заполните форму:
   - **Your AI** — выберите свой ИИ;
   - **Your language** — ваш язык кодом: `ru`, `en`, `he`, `uk`, `de`, `pt-BR`;
   - **Your country** — страна двумя буквами: `IL`, `DE`, `US`;
   - **Your time zone** — часовой пояс: `Asia/Jerusalem`, `Europe/Berlin`, `America/New_York`;
   - **Your name** — имя, как ИИ будет к вам обращаться: до пяти слов;
   - **For the grammar of your language** — female или male: для грамматики вашего языка;
   - **Other languages you work in** — другие языки, на которых вы работаете, кодами через
     запятую, например `en,he`; или оставьте пустым.

   Нажмите **Run workflow**. Через минуту-две появится страница (Issue) **«Your assistant's
   instructions»**.
4. **Ваш ИИ.** Сделайте то, что написано на этой странице: вставьте текст в настройки ИИ,
   подключите Notion, отправьте первое сообщение. ИИ настроит Notion вместе с вами. Страница
   написана по-английски; дальше ИИ говорит с вами на вашем языке.

Если установка остановилась с ошибкой, в её записи сказано, почему и что изменить; затем
запустите её снова кнопкой **Run workflow**.

### Полезно знать

- Ваши записи остаются в вашем Notion. В копии лежат ваши настройки и правила: держите её
  закрытой.
- Копия каждую неделю ищет новый выпуск и принимает его не раньше чем через неделю после выхода,
  когда пройдут её проверки. Обновление, которое меняет сами задачи GitHub (workflows), она
  поставить не может: вместо этого открывает Issue, и пока такому обновлению нужен кто-то, кто
  поставит его вручную.
- Ваш ИИ держит те инструкции, которые вы вставили, пока вы не вставите новые. Когда выпуск их
  меняет, копия сообщает об этом, обычно в течение суток: открывает Issue **«Your assistant's
  instructions»** с новым текстом, а GitHub присылает уведомление. Вставьте новый текст вместо
  старого; до тех пор ИИ работает по правилам прежнего выпуска. Если проверка находит в копии
  ошибку, новый текст ждёт, пока её исправят; в тревоге сказано, что не так.
- Как GitHub вам сообщает, выбираете вы: письмом — в настройках уведомлений GitHub — или на
  телефон — в приложении GitHub: Profile, шестерёнка, Notifications, «Direct mentions». Если не
  включено ни то ни другое, страница всё равно ждёт в вашей копии.
- Чтобы поменять настройки — ИИ, язык, страну, часовой пояс, имя, грамматический род или рабочие
  языки: **Actions** → **settings** → **Run workflow**. Там всё уже стоит на «keep as it is»
  («оставить как есть») — в списках выбран первый пункт, текстовые поля пустые: измените то, что
  нужно, всё за один запуск, и нажмите **Run workflow**. Обычно через несколько минут, самое позднее
  после ночной проверки, появится новое Issue **«Your assistant's instructions»** с текстом для
  вставки; если ответы совпали с уже действующими настройками, нового Issue не будет — только
  заметка в прежнем. Файлы руками править не нужно. Что сделал запуск, написано на его странице в
  разделе **Actions**; если к следующему дню Issue не появилось, посмотрите там и запустите форму
  снова.
- Проверки идут в вашей копии на GitHub Actions, за счёт бесплатной месячной нормы вашей учётной
  записи для закрытых репозиториев.

---

## עברית

<div dir="rtl">

**הזיכרון של ה-AI שלכם.** עוזר שזוכר אתכם. זה אותו AI שאתם כבר מדברים איתו — ChatGPT, Claude או
Grok — עם כללים: הוא שומר את הפתקים, את נתוני הבריאות ואת המסמכים שלכם ב-Notion האישי שלכם, מראה
לכם ושואל אתכם לפני שהוא שולח, קונה או מוחק משהו, ובודק את העובדות שלו. את כל ההתקנה עושים מהטלפון.

הדף הזה הוא תבנית: יוצרים ממנו פעם אחת עותק פרטי משלכם. העותק שומר את ההגדרות שלכם ומקבל כל
גרסה חדשה של המנוע; ה-AI שלכם קורא את הכללים מהגרסה שמופיעה בהוראות שלו.

הכפתורים והשדות ב-GitHub כתובים באנגלית, ולכן כאן הם מופיעים בדיוק כמו על המסך.

### מה צריך

- חשבון GitHub (חינמי);
- חשבון Notion;
- אחד מאלה: ChatGPT (מנוי Plus; עדיין בבטא), Claude (מנוי Pro) או Grok.

### ארבעה צעדים מהטלפון

פתחו את GitHub בדפדפן של הטלפון, באתר המלא.

1. **העותק שלכם.** בראש הדף הזה לחצו «Use this template», ואז «Create a new repository».
   Owner: החשבון האישי שלכם, לא ארגון. שם: מה שתרצו, למשל `my-memory`. בחרו **Private** ולחצו
   «Create repository from template». אל תוסיפו לעותק שום דבר לפני צעד 3: ההתקנה הראשונה פועלת
   רק על עותק נקי.
2. **הגדרה אחת.** בעותק החדש: **Settings** (בטלפון ייתכן שתמצאו אותו תחת «…»), ואז **Actions**,
   ואז **General**; תחת «Workflow permissions» סמנו **«Allow GitHub Actions to create and approve
   pull requests»** ולחצו **Save**. בלי זה העותק לא יוכל לשמור את ההגדרות שלכם או לקבל עדכונים.
3. **התקנה.** **Actions**, ואז **setup**, ואז **Run workflow**. מלאו את הטופס:
   - בשדה **Your AI** בחרו את ה-AI שלכם;
   - בשדה **Your language** — השפה שלכם, כקוד: `ru`, `en`, `he`, `uk`, `de`, `pt-BR`;
   - בשדה **Your country** — המדינה, בשתי אותיות: `IL`, `DE`, `US`;
   - בשדה **Your time zone** — אזור הזמן: `Asia/Jerusalem`, `Europe/Berlin`, `America/New_York`;
   - בשדה **Your name** — השם שבו ה-AI יפנה אליכם: עד חמש מילים;
   - בשדה **For the grammar of your language** — female (נקבה) או male (זכר), כדי שה-AI יפנה
     אליכם בלשון הנכונה;
   - בשדה **Other languages you work in** — שפות נוספות שאתם עובדים בהן, בקודים עם פסיק ביניהם,
     למשל `en,he`; או השאירו את השדה ריק.

   לחצו **Run workflow**. תוך דקה-שתיים יופיע בעותק דף חדש מסוג Issue, בשם **«Your assistant's
   instructions»**.
4. **ה-AI שלכם.** עשו מה שכתוב ב-Issue הזה: הדביקו את הטקסט בהגדרות של ה-AI, חברו אליו את Notion
   ושלחו את ההודעה הראשונה. ה-AI יגדיר איתכם את ה-Notion שלכם. ה-Issue כתוב באנגלית; מכאן והלאה
   ה-AI ידבר איתכם בשפה שלכם.

אם ההתקנה נעצרת בגלל שגיאה, בהרצה שלה ב-**Actions** כתוב למה זה קרה ומה לשנות; אחר כך הפעילו
אותה שוב בלחיצה על **Run workflow**.

### טוב לדעת

- הפתקים שלכם נשארים ב-Notion שלכם. בעותק נמצאים ההגדרות שלכם והכללים: השאירו אותו פרטי.
- העותק מחפש פעם בשבוע גרסה חדשה, ומקבל אותה רק כשעבר לפחות שבוע מאז שפורסמה, ורק אחרי
  שהבדיקות שלו עברו בהצלחה. העותק לא יכול להתקין עדכון שמשנה את קובצי ה-workflow עצמם: במקום
  זה הוא פותח Issue, וכרגע עדכון כזה צריך מישהו שיודע להתקין אותו ידנית.
- ה-AI שלכם עובד לפי ההוראות שהדבקתם, עד שתדביקו חדשות. כשגרסה חדשה משנה אותן, העותק מודיע לכם,
  בדרך כלל תוך יום: הוא פותח Issue בשם **«Your assistant's instructions»** עם הטקסט החדש,
  ו-GitHub שולח לכם התראה. הדביקו את הטקסט החדש במקום הישן; עד שתעשו את זה, ה-AI ממשיך לפי
  הכללים של הגרסה שכבר יש לו. אם בדיקה מוצאת טעות בעותק, הטקסט החדש מחכה עד שהיא תתוקן, והאזהרה
  מסבירה מה לא בסדר.
- איך GitHub יודיע לכם — אתם בוחרים. במייל: בהגדרות ההתראות באתר GitHub. בטלפון: באפליקציית
  GitHub היכנסו ל-Profile, ואז לגלגל השיניים, ואז ל-Notifications, ושם הפעילו את
  «Direct mentions». גם אם לא תבחרו באף אחת מהדרכים, ה-Issue מחכה לכם בעותק.
- כדי לשנות את ההגדרות שלכם — ה-AI, השפה, המדינה, אזור הזמן, השם, לשון הפנייה או שפות העבודה:
  **Actions**, ואז **settings**, ואז **Run workflow**. שם הכול כבר עומד על «keep as it is» (להשאיר
  כמו שזה): ברשימות נבחרה האפשרות הראשונה, ושדות הטקסט ריקים. שנו את מה שצריך, הכול בהרצה אחת,
  ולחצו **Run workflow**. בדרך כלל תוך כמה דקות, ולכל המאוחר אחרי הבדיקה הלילית, ייפתח בעותק Issue
  חדש בשם **«Your assistant's instructions»** עם הטקסט שצריך להדביק; אם התשובות זהות להגדרות
  שכבר קיימות, לא ייפתח Issue חדש — רק תתווסף הערה ב-Issue הקיים. אין צורך לערוך אף קובץ. מה
  שההרצה עשתה כתוב בדף שלה ב-**Actions**; אם עד למחרת ה-Issue עדיין לא נפתח, בדקו שם ואז הפעילו
  את **settings** שוב.
- הבדיקות רצות בעותק שלכם ב-GitHub Actions, ומנצלות את המכסה החודשית החינמית שיש לחשבון
  ה-GitHub שלכם עבור מאגרים פרטיים.

</div>
