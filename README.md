<p align="center"><img src="https://d7team.com/icon-512.png" width="88" alt="Delta Seven"></p>
<h1 align="center">Advanced BossMenu</h1>
<p align="center"><b>FiveM Boss Menu for QBCore, QBox & CFW</b></p>
<p align="center"><a href="#english">English</a> · <a href="#arabic">العربية</a></p>

<p align="center"><a href="https://d7team.com/products/advanced-bossmenu"><img src="https://d7team.com/product-previews/advanced-bossmenu.webp" alt="Advanced BossMenu" width="860"></a></p>

<a id="english"></a>

## Advanced BossMenu — FiveM Boss Menu for QBCore, QBox & CFW

FiveM boss menu for every job on QBCore, QBox & CFW: hiring, ranks, duty tracking, points with auto promotion, salaries, society funds and wings.

Advanced BossMenu is a clean tablet for running a job: employees, ranks, wings, points, duty tracking, salaries, the society account and permissions, without bloated UI or unnecessary workflows.

> This repository is documentation only. The resource is sold on our store and downloaded from the Client Area after you redeem your code.

[Website](https://d7team.com/products/advanced-bossmenu) · [Installation guide](https://d7team.com/guides/advanced-bossmenu) · [Store](https://store.d7team.com/advanced-bossmenu/p1095032724) · [Discord](https://discord.gg/d-7)

### At a glance

| | |
|---|---|
| **Works with** | QBCore and QBox servers, CFW included |
| **Jobs** | Every job — police, EMS, businesses and more |
| **Opening** | Tablet item, /bosstablet command or a key |
| **Interaction** | Target, Interact or marker |
| **Money** | The job's society account |

### Features

#### Employees

- Members list with grade, call sign, on-duty status, duty time and points.
- Hire a nearby player — they get an offer to accept or decline — or hire by citizen ID.
- Promote, demote and fire, limited by grade.
- A detail page for each employee.

#### Duty and points

- Clock in and out, with lifetime and weekly duty time and an activity chart.
- Points earned per hour on duty.
- Points needed for each grade, with automatic promotion and demotion.
- Add or remove points for one employee or for everyone.

#### Salaries and finance

- Automatic pay for time on duty, optionally paid from the society account.
- Society balance, deposit and withdraw.
- Pay a bonus to all employees at once.

#### Manager tools

- Bonus multiplier — x2 or x3 points — for a set number of hours.
- Weekly reset of duty hours.
- Wings: assign or remove units such as SWAT or Air Unit, each with its own label and minimum grade.

#### Configuration and logs

- One profile per job, with its own name, logo and society account — no data mixed between jobs.
- Turn each feature on or off per job: employees, duty, points, finance, hire, rank, fire, wings, manager, bonus and pay.
- A grade permission for each tool.
- Discord logs for hiring, ranks, points, finance, bonus, manager tools and wings.
- Points and wings are read by Advanced MDT.

### Requirements

- A QBCore or QBox server, CFW included
- oxmysql
- An Advanced BossMenu licence or the scripts subscription

### Installation

1. Buy Advanced BossMenu or the scripts subscription on our store.
2. Sign in at panel.d7team.com with Discord.
3. Client Area → Redeem Code: enter the code and your server's public IP.
4. Download d7-bossmenu from the Client Area and put it in resources.
5. Add the departmentlaptop item to your inventory's items.
6. Add a profile for each job in config/config.lua.
7. In server.cfg, start it after your database and framework:

   ```cfg
   ensure oxmysql
   ensure qb-core
   ensure d7-bossmenu
   ```

8. Restart the server.

Configuration, first start, updates and every console message explained: [Installation guide](https://d7team.com/guides/advanced-bossmenu)

### Pricing

- **$34.99** — One-time purchase of this script
- **$7.99 / month** — Scripts subscription (Advanced MDT and Advanced BossMenu): every script, free IP change during the subscription, and free updates

[Store](https://store.d7team.com/advanced-bossmenu/p1095032724)

### FAQ

<details>
<summary><b>Which servers does Advanced BossMenu work on?</b></summary>

QBCore and QBox servers, CFW included.

</details>

<details>
<summary><b>Does it work for every job?</b></summary>

Yes. Every job gets its own profile with its own data, features, grade permissions and logs — police, EMS, businesses or anything else.

</details>

<details>
<summary><b>How does automatic promotion work?</b></summary>

Employees earn points for time on duty. Each grade needs a number of points, and an employee who reaches or drops below it is promoted or demoted automatically. It can be switched off.

</details>

<details>
<summary><b>Does it pay salaries?</b></summary>

Yes. It pays employees for time on duty on a set interval, and can take the money from the job's society account.

</details>

<details>
<summary><b>How much does it cost?</b></summary>

$34.99 once, or $7.99 a month with the scripts subscription, which covers Advanced BossMenu and Advanced MDT together.

</details>

### Support

Support is on our Discord: [discord.gg/d-7](https://discord.gg/d-7). Issues are closed on this repository so no request waits unread.

### More from Delta Seven

- [Delta Panel](https://github.com/d7teamdev/delta-panel) — FiveM Admin Panel for QBCore, QBox & CFW Servers
- [Advanced MDT](https://github.com/d7teamdev/advanced-mdt) — FiveM Police MDT for QBCore, QBox & CFW
- [Add-on FiveM cars](https://d7team.com/cars)

---

<a id="arabic"></a>

<div dir="rtl">

## Advanced BossMenu — سكربت بوس منيو فايف ام لـ QBCore و QBox و CFW

بوس منيو فايف ام لكل الوظائف في QBCore و QBox و CFW: التوظيف، الرتب، تتبع الدوام، النقاط والترقية التلقائية، الرواتب، حساب السوسايتي والونقات.

Advanced BossMenu تابلت نظيف لإدارة الوظيفة: الموظفين والرتب والونقات والنقاط وتتبع الساعات والرواتب وحساب السوسايتي والصلاحيات، بدون تعقيد أو واجهات زائدة.

> هذا المستودع للتعريف والشرح فقط. الريسورس يُباع في متجرنا، وتحمّله من منطقة العميل بعد ما تفعّل الكود

[الموقع](https://d7team.com/ar/products/advanced-bossmenu) · [شرح التثبيت](https://d7team.com/ar/guides/advanced-bossmenu) · [المتجر](https://store.d7team.com/advanced-bossmenu/p1095032724) · [الدسكورد](https://discord.gg/d-7)

### نظرة سريعة

| | |
|---|---|
| **يشتغل مع** | سيرفرات QBCore و QBox، ومعها CFW |
| **الوظائف** | كل الوظائف — الشرطة، الإسعاف، المطاعم وغيرها |
| **طريقة الفتح** | آيتم التابلت، أمر ⁦/bosstablet⁩، أو زر |
| **التفاعل** | Target أو Interact أو ماركر |
| **الفلوس** | حساب الوظيفة (السوسايتي) |

### المميزات

#### الموظفين

- قائمة الأعضاء بالرتبة والكول ساين وحالة الدوام وساعات الديوتي والنقاط
- توظيف لاعب قريب — يوصله عرض يقبله أو يرفضه — أو توظيف برقم المواطن
- ترقية وتخفيض وفصل، محصورة حسب الرتبة
- صفحة تفاصيل لكل موظف

#### الديوتي والنقاط

- دخول وخروج من الدوام، مع إجمالي الساعات والأسبوعي ورسم للنشاط
- نقاط تنكسب على كل ساعة دوام
- نقاط مطلوبة لكل رتبة، مع ترقية وتخفيض تلقائي
- إضافة أو خصم نقاط لموظف واحد أو للكل

#### الرواتب والمالية

- راتب تلقائي على وقت الدوام، ويقدر ينصرف من حساب السوسايتي
- رصيد السوسايتي، إيداع وسحب
- صرف مكافأة لكل الموظفين مرة وحدة

#### أدوات الإدارة

- مضاعف بونص — نقاط x2 أو x3 — لعدد ساعات محدد
- تصفير أسبوعي لساعات الدوام
- الونقات: إعطاء أو إزالة وحدات مثل SWAT أو الجوية، كل وحدة باسمها وأقل رتبة لها

#### الإعداد واللوقات

- بروفايل لكل وظيفة باسمها وشعارها وحساب السوسايتي — بدون خلط بيانات بين الوظائف
- تفعيل أو تعطيل كل ميزة لكل وظيفة: الموظفين، الديوتي، النقاط، المالية، التوظيف، الرتب، الفصل، الونقات، الإدارة، البونص والرواتب
- صلاحية رتبة لكل أداة
- لوقات دسكورد للتوظيف والرتب والنقاط والمالية والبونص وأدوات الإدارة والونقات
- النقاط والونقات يقراها Advanced MDT

### المتطلبات

- سيرفر QBCore أو QBox، ومعها CFW
- oxmysql
- ترخيص Advanced BossMenu أو اشتراك السكربتات

### التثبيت

1. اشترِ Advanced BossMenu أو اشتراك السكربتات من متجرنا.
2. سجّل دخولك في panel.d7team.com عن طريق دسكورد.
3. منطقة العميل ← تفعيل كود: اكتب الكود وآيبي سيرفرك العام.
4. حمّل d7-bossmenu من منطقة العميل وحطه في مجلد resources حقك.
5. أضف آيتم departmentlaptop لآيتمات الإنفنتري حقك.
6. أضف في config/config.lua بروفايل لكل وظيفة.
7. في server.cfg، شغّله بعد قاعدة البيانات والفريم وورك:

</div>

```cfg
ensure oxmysql
ensure qb-core
ensure d7-bossmenu
```

<div dir="rtl">

8. سوّ ريستارت للسيرفر.

الإعدادات، أول تشغيل، التحديثات، وشرح كل رسالة بالكونسول: [شرح التثبيت](https://d7team.com/ar/guides/advanced-bossmenu)

### الأسعار

- **⁦$34.99⁩** — شراء هذا السكربت مرة وحدة
- **⁦$7.99⁩ بالشهر** — اشتراك السكربتات (Advanced MDT و Advanced BossMenu): كل السكربتات، تغيير الآيبي مجاناً خلال مدة الاشتراك، وتحديثات مجانية

[المتجر](https://store.d7team.com/advanced-bossmenu/p1095032724)

### الأسئلة الشائعة

<details>
<summary><b>على أي سيرفرات يشتغل Advanced BossMenu؟</b></summary>

سيرفرات QBCore و QBox، ومعها CFW

</details>

<details>
<summary><b>يشتغل لكل الوظائف؟</b></summary>

إيه. كل وظيفة لها بروفايل ببياناتها ومميزاتها وصلاحيات رتبها ولوقاتها — الشرطة، الإسعاف، المطاعم أو أي وظيفة ثانية.

</details>

<details>
<summary><b>كيف تشتغل الترقية التلقائية؟</b></summary>

الموظف يكسب نقاط على وقت الدوام. كل رتبة لها عدد نقاط، والي يوصله أو ينزل عنه يترقى أو ينخفض تلقائياً. وتقدر تطفيها.

</details>

<details>
<summary><b>يصرف رواتب؟</b></summary>

إيه. يصرف للموظفين على وقت الدوام كل فترة محددة، ويقدر يسحبها من حساب السوسايتي للوظيفة.

</details>

<details>
<summary><b>كم سعره؟</b></summary>

⁦$34.99⁩ مرة وحدة، أو ⁦$7.99⁩ بالشهر مع اشتراك السكربتات الي يشمل Advanced BossMenu و Advanced MDT مع بعض.

</details>

### الدعم

الدعم على الدسكورد حقنا: [discord.gg/d-7](https://discord.gg/d-7). الـ Issues مقفلة بهذا المستودع عشان ما يضيع أي طلب بدون رد

### منتجات ثانية من دلتا سفن

- [لوحة تحكم دلتا](https://github.com/d7teamdev/delta-panel) — لوحة تحكم سيرفرات فايف ام لـ QBCore و QBox و CFW
- [Advanced MDT](https://github.com/d7teamdev/advanced-mdt) — سكربت MDT للشرطة في فايف ام لـ QBCore و QBox و CFW
- [سيارات فايف ام مضافة](https://d7team.com/ar/cars)

</div>

---

<p align="center">© Delta Seven (D7 Team) · <a href="https://d7team.com">d7team.com</a></p>
