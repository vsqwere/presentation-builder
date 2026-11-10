---
name: "presentation-builder"
description: "Use when someone from HR, sales or any team asks for a presentation, deck or slides on any topic: asks one short round about style, audience and content, takes the user's content or writes it, and returns a studio-grade editable PowerPoint (.pptx) with photos and speaker notes."
---

# Presentation Builder

Робить презентацію рівня сильної дизайн-студії у форматі PowerPoint (.pptx) на будь-яку тему для HR, продажів чи іншої команди. Людина може дати лише тему, а може скинути готовий текст, файл чи нотатки. Файл відкривається в PowerPoint, Keynote і Google Slides, увесь текст живий і редагується.

Головне: людині має бути просто. Одне коло питань, далі робота без зайвих уточнень. Спілкуйся мовою користувача, презентацію пиши мовою запиту.

## Як виглядає «студійний» рівень

Цим принципам підпорядковано все нижче, і саме вони відрізняють сильну презентацію від шаблонної:
- **Велика типографіка.** Заголовки 40–96pt, жирні, з тісним трекінгом. Одна велика думка важить більше за п'ять пунктів.
- **Повітря і сітка.** 12 колонок, поля 0.6", асиметрія: заголовок ліворуч на 5 колонок, зміст праворуч на 7.
- **Один акцентний колір**, яким виділено одне слово в заголовку (`*слово*`), одну цифру, один стовпчик графіка.
- **Справжні фото** великими кадрами з округленими кутами або на весь слайд.
- **Ритм.** Сусідні слайди різні: велика думка → список → фото → цифри → кольоровий розділ.
- **Тиха службова лінія:** назва презентації зліва вгорі, `05 / 14` справа. Без логотипів-наклейок на кожному слайді.

## 1. Одне коло питань

Спершу прочитай усе, що дали: запит, вкладені файли (docx, pdf, pptx, xlsx, нотатки), посилання. Не питай того, що вже відомо.

Потім один AskUserQuestion, до 4 питань, перший варіант рекомендований:

1. **Контент.** «Візьми мій текст / файл» · «Напиши сам за темою» · «Мої тези, допиши решту». Якщо файл уже вкладений, пропусти.
2. **Стиль** (у description одним рядком, як виглядає):
   - **Swiss** (`swiss`): білий, чорна типографіка, електрично-синій акцент. Звіти, клієнти, стратегія.
   - **Studio** (`studio`): майже чорний фон, теплий білий текст, помаранчевий акцент. Пітчі, події, продукти.
   - **Color block** (`block`): кольорові поля томатний, жовтий, кобальт. Сміливо, для подій і креативу.
   - **Human** (`human`): білий, сливовий і теракотовий, теплі персикові панелі. HR, онбординг, культура.
   - **Editorial** (`editorial`): serif-заголовки, чорне з червоним. Кейси, лідерство, журнальний тон.
   Через «Other» можна дати свої кольори (hex), логотип або назву компанії.
3. **Для кого і навіщо.** «Продати або переконати клієнта» · «Навчити, онбординг» · «Звіт або план для керівництва» · «Подія чи новина для команди».
4. **Фото.** «Підібрати стокові (Unsplash)» · «Мої фото, надішлю» · «Без фото». Якщо людина вже прислала фото, пропусти.

Обсяг визнач сам за метою (продаж і подія 8–12 слайдів, навчання 12–18, звіт 8–10), якщо людина не назвала його.

Якщо відповіді немає, бери рекомендовані варіанти й одним рядком скажи, що взяв.

## 2. Контент

**Якщо контент дали.** Він головне джерело правди. Перебудуй його в історію, скороти, розбий на слайди, але не додавай фактів, яких там немає. Що не влізло, переноси в нотатки доповідача.

**Якщо пишеш сам.**
- Загальні факти про світ (ринок, тренди, закони, дослідження) шукай через WebSearch і вказуй джерело на слайді (`source`). Без джерела цифри не пишеш.
- Внутрішні дані компанії (цифри, імена, ціни, результати, відгуки) не вигадуй ніколи. Став видимий плейсхолдер: `[XX]%`, `[ім'я клієнта]`, `[ціна]`. У фінальному повідомленні перелічи всі плейсхолдери.

**Структура за метою** (основа, не клітка):
- **Продати:** проблема клієнта → що вона коштує → рішення → як це працює → докази → пакети → наступний крок.
- **Навчити, онбординг:** навіщо → що буде в кінці → кроки → хто допомагає → типові помилки → чек-лист → куди звертатись.
- **Звіт:** головний висновок першим → цифри → що спрацювало і що ні → ризики → рішення, потрібне від керівництва.
- **Подія для команди:** що сталося → чому це важливо → що змінюється для кожного → дати → питання.

**Текст на слайдах**
- Заголовок це висновок, а не тема: «Новачки з бадді лишаються довше», а не «Бадді-програма». До 10 слів.
- В одному заголовку на слайд можна виділити ключове слово акцентом: `"MVP за *12 тижнів*, а не за рік"`.
- До 5 пунктів, формат `Коротка назва :: пояснення до 12 слів`. Деталі в нотатки.
- Нотатки доповідача для кожного змістовного слайда (2–4 речення).
- Без AI-прийомів: без довгого тире (кома, крапка або дужки), без «це не просто X, а Y», без трійок за звичкою, без «революційний», «безшовний», «трансформуйте», «unlock», «elevate», без емодзі.
- Цифри лише справжні й з джерелом. Без даних не будуй графік, краще `stats` з плейсхолдерами.

Покажи людині план (назви слайдів одним списком) і одразу будуй, якщо вона не просила погоджувати.

## 3. Фото

Фото це половина студійного вигляду. Плануй 4–8 кадрів на презентацію: обкладинка, 1–2 слайди `bullets` з фото, `quote` з портретом, `gallery`, `image` на весь слайд.

- **Свої фото людини** мають пріоритет. Клади їх у `img/` і посилайся шляхом.
- **Unsplash**, якщо людина дозволила. Знайди через WebSearch (`unsplash.com/photos <тема англійською>`), відкрий сторінку фото через WebFetch і перевір, що ліцензія безкоштовна Unsplash License (не Unsplash+). Звідти ж візьми автора й id `photo-…`. Завантаж: `curl -sL -o img/назва.jpg "https://images.unsplash.com/photo-…?w=2000&q=85&fm=jpg"`. Автора й посилання запиши в нотатки слайда.
- Одна мова зйомки на всю презентацію: денне світло, справжні люди за роботою, без постановочних рукостискань і усмішок у камеру.
- Не генеруй людей, команду, клієнтів і «до/після». Не видавай сток за фото компанії: у нотатках напиши, що це ілюстрація.
- Без фото презентація теж працює: обкладинка тоді з великою кольоровою формою, а ритм тримають `statement`, `section` і `stats`.

## 4. Збірка

Інструмент лежить у цьому файлі нижче. Витягни його скриптом, не передруковуючи. `SKILL_MD` це шлях до цього файлу в теці скіла:

```sh
pip install -q python-pptx pillow 2>/dev/null || pip install -q --break-system-packages python-pptx pillow
python3 - "$SKILL_MD" <<'EOF'
import re,sys,os
s=open(sys.argv[1]).read()
for p,c in re.findall(r"```\w*\n(?://|/\*|#) file: (\S+)[^\n]*\n(.*?)```",s,re.S):
    os.makedirs(os.path.dirname(p) or '.',exist_ok=True); open(p,'w').write(c); print(p)
EOF
```

Отримаєш `tools/deck.py` і `tools/render.sh`. Далі пишеш лише `deck.json` і запускаєш:

```sh
python3 tools/deck.py deck.json "Назва.pptx"
bash tools/render.sh "Назва.pptx"
```

**`deck.json`**

```json
{
  "theme": "swiss",
  "footer": "Pecode × Acme · пропозиція",
  "colors": {"accent": "#2B50FF", "alt": ["#2B50FF", "#0A0A0A"]},
  "slides": [ { "layout": "title", "meta": "Листопад 2026", "title": "MVP за *12 тижнів*", "subtitle": "…", "image": "img/cover.jpg" } ]
}
```

`footer` це назва в службовій лінії. `colors` (bg, surface, ink, muted, line, accent, on_accent, alt) і `fonts` ({"head", "body"}) необов'язкові: так задають бренд компанії поверх стилю. `alt` це кольори заливних розділів по черзі.

**Макети** (у кожного є `notes`; `*слово*` у заголовку фарбується акцентом):
| layout | поля | для чого |
|---|---|---|
| `title` | title, subtitle, meta, image? | обкладинка: гігантський заголовок, фото праворуч або кольорова форма |
| `section` | title, number?, subtitle? | заливний розділ з великим номером частини |
| `statement` | title, subtitle? | одна велика думка на весь слайд |
| `bullets` | title, items[] (до 5), image? | заголовок ліворуч, нумеровані рядки з лініями праворуч; з image фото на пів слайда |
| `cards` | title, cards[{tag, title, text}] (2–4) | пакети, переваги, напрями; перша картка кольорова |
| `two_col` | title, columns[{heading, items[] або text}] | порівняння «було / стало», «вони / ми»; друга колонка темна |
| `stats` | title, stats[{value, label}] (2–4), source | великі цифри з вертикальними лініями |
| `chart` | title, kind (bar/hbar/line/pie), categories[], series{назва: [числа]}, highlight?, takeaway?, source | редагований графік, один стовпчик акцентом |
| `process` | title, steps[{title, text}] (3–5) | етапи з великими номерами |
| `table` | title, header[], rows[[]], highlight? (індекс колонки) | мінімалістична таблиця з лініями |
| `quote` | quote, author, image? | справжній відгук, з портретом чи без |
| `gallery` | title, images[] (1–3) | мозаїка фото |
| `image` | image, title, caption? | фото на весь слайд з карткою-підписом |
| `closing` | title, items[], contact | темний фінал: наступні кроки й контакти |

**Ритм.** Не більше двох однакових макетів підряд. Після двох текстових слайдів постав `statement`, `stats`, `image` чи `section`. Розділи довші за 4 слайди починай з `section`. Обкладинка й фінал завжди.

**Шрифти.** Лише ті, що є всюди: Arial, Calibri, Cambria (вони вже в стилях). Інші шрифти на чужому комп'ютері підміняться. Якщо компанія має свій шрифт, впиши його у `fonts` і попередь, що він має бути встановлений у тих, хто відкриватиме файл.

## 5. Перевірка перед відправкою

1. `tools/deck.py` друкує `УВАГА`, якщо текст не влазить. Скороти текст або розбий слайд.
2. `tools/render.sh` робить `qa/sheet.png` з усіма слайдами. Переглянь один раз:
   - текст ніде не вилазить і не налазить на фото;
   - заголовки читаються як висновки й не переносять одне слово на окремий рядок;
   - поруч немає двох однакових макетів;
   - є хоча б 3 «великі» слайди (statement, section, stats, image);
   - жодного вигаданого факту, плейсхолдери на місці.
3. Виправ через `deck.json`, збери ще раз. Одне коло правок, далі віддавай.

## 6. Віддати

Надішли `.pptx` і `qa/sheet.png` через SendUserFile. У повідомленні 3–6 рядків:
- скільки слайдів і яка логіка, одним реченням;
- стиль і звідки фото (з авторами в нотатках);
- що заповнити: список плейсхолдерів `[...]`;
- джерела фактів, якщо шукав;
- що можна попросити далі: «додай слайд про…», «коротше», «стиль studio», «англійською».

Правки роби в тому самому `deck.json` і збирай заново.

## Завжди

- Не вигадуй цифри, відгуки, клієнтів, імена й ціни.
- Не копіюй чужі презентації, тексти й логотипи.
- Не вставляй картинки з текстом: увесь текст живий.
- Якщо просять Google Slides, дай цей .pptx і скажи: Google Drive → Створити → Завантажити файл → відкрити в Google Slides.

## Інструмент

```python
# file: tools/deck.py — python3 tools/deck.py deck.json out.pptx ; збирає .pptx зі специфікації
import json, sys, math, os, re
from pptx import Presentation
from pptx.util import Pt
from pptx.dml.color import RGBColor
from pptx.enum.shapes import MSO_SHAPE
from pptx.enum.text import PP_ALIGN, MSO_ANCHOR
from pptx.chart.data import CategoryChartData
from pptx.enum.chart import XL_CHART_TYPE, XL_LEGEND_POSITION, XL_LABEL_POSITION
from pptx.oxml.ns import qn

# Стилі. alt = кольори для «заливних» слайдів по черзі (section, statement, closing).
THEMES = {
  'swiss':  dict(bg='FFFFFF', surface='F2F2F0', ink='0A0A0A', muted='5C5C5C', line='D9D9D6', accent='2B50FF', on_accent='FFFFFF',
                 alt=['2B50FF', '0A0A0A'], head='Arial', body='Arial', track=-0.035),
  'studio': dict(bg='0E0E0E', surface='1B1B1B', ink='F4F2EE', muted='A3A09A', line='343434', accent='FF6B2C', on_accent='0E0E0E',
                 alt=['FF6B2C', 'F4F2EE'], head='Arial', body='Arial', track=-0.035),
  'block':  dict(bg='FFFFFF', surface='F4F1EC', ink='111111', muted='55524D', line='DDD8D0', accent='FF4F3A', on_accent='111111',
                 alt=['FF4F3A', 'FFC93C', '2D5BFF'], head='Arial', body='Arial', track=-0.03),
  'human':  dict(bg='FFFFFF', surface='FFE6D8', ink='2B1B2E', muted='6E5B6B', line='EED3C4', accent='E2552E', on_accent='FFFFFF',
                 alt=['2B1B2E', 'E2552E'], head='Arial', body='Arial', track=-0.03),
  'editorial': dict(bg='FFFFFF', surface='F3F1EC', ink='111111', muted='5A5A5A', line='D8D5CE', accent='C8102E', on_accent='FFFFFF',
                 alt=['111111', 'C8102E'], head='Cambria', body='Calibri', track=-0.02),
}
W, H = 12192000, 6858000
def inch(x): return int(x * 914400)
M = inch(0.6); TOP = inch(0.55)
COL = (W - 2 * M) / 12            # 12 колонок (без проміжків, для простоти)
def cx(c): return int(M + COL * c)
def cw(n): return int(COL * n)
def rgb(h): return RGBColor.from_string(h.lstrip('#').upper())
def lum(h):
    h = h.lstrip('#'); r, g, b = (int(h[i:i + 2], 16) / 255 for i in (0, 2, 4))
    f = lambda c: c / 12.92 if c <= .03928 else ((c + .055) / 1.055) ** 2.4
    return .2126 * f(r) + .7152 * f(g) + .0722 * f(b)
def on(bg, dark='111111', light='FFFFFF'): return dark if lum(bg) > .35 else light

WARN = []
def fit(paras, w, h, size, spacing, font, minsize=12):
    ratio = 0.5 if font in ('Calibri', 'Cambria') else 0.56
    wpt, hpt = w / 12700, h / 12700
    while True:
        per = max(1, int(wpt / (size * ratio)))
        lines = sum(max(1, math.ceil(len(re.sub(r'\*', '', p)) / per)) for p in paras)
        need = lines * size * 1.18 * spacing + (len(paras) - 1) * size * 0.6
        if need <= hpt: return size
        if size <= minsize: break
        size -= 1
    WARN.append(f'не влазить: «{paras[0][:40]}…» — скороти текст або розбий слайд')
    return size

class Deck:
    def __init__(self, spec):
        t = dict(THEMES[spec.get('theme', 'swiss')])
        for k, v in spec.get('colors', {}).items(): t[k] = [x.lstrip('#') for x in v] if isinstance(v, list) else v.lstrip('#')
        t.update(spec.get('fonts', {}))
        self.t, self.spec = t, spec
        self.prs = Presentation(); self.prs.slide_width, self.prs.slide_height = W, H
        self.blank = self.prs.slide_layouts[6]; self.n = 0; self.alt_i = 0
        self.total = len(spec['slides']); self.name = spec.get('footer', '')

    # ---------- примітиви
    def slide(self, bg=None):
        s = self.prs.slides.add_slide(self.blank); self.n += 1
        s.background.fill.solid(); s.background.fill.fore_color.rgb = rgb(bg or self.t['bg']); s._bg = bg or self.t['bg']
        return s
    def fill_color(self):
        c = self.t['alt'][self.alt_i % len(self.t['alt'])]; self.alt_i += 1; return c
    def rect(self, s, x, y, w, h, color, shape=MSO_SHAPE.RECTANGLE, radius=None):
        r = s.shapes.add_shape(shape, x, y, w, h); r.fill.solid(); r.fill.fore_color.rgb = rgb(color)
        r.line.fill.background(); r.shadow.inherit = False
        st = r._element.find(qn('p:style'))
        if st is not None: r._element.remove(st)
        if radius is not None and shape == MSO_SHAPE.ROUNDED_RECTANGLE: r.adjustments[0] = radius
        return r
    def line(self, s, x, y, w, color=None, weight=0.75):
        ln = s.shapes.add_connector(1, x, y, x + w, y); ln.line.color.rgb = rgb(color or self.t['line']); ln.line.width = Pt(weight); return ln
    def vline(self, s, x, y, h, color=None):
        ln = s.shapes.add_connector(1, x, y, x, y + h); ln.line.color.rgb = rgb(color or self.t['line']); ln.line.width = Pt(0.75); return ln
    def text(self, s, x, y, w, h, paras, size, color=None, font=None, bold=False, align='l', anchor='t', spacing=1.0, track=0, accent=None, minsize=12):
        """paras: str або список абзаців. *слово* фарбується в accent."""
        paras = paras if isinstance(paras, list) else [paras]
        font = font or self.t['body']
        size = fit(paras, w, h, size, spacing, font, minsize)
        tb = s.shapes.add_textbox(x, y, w, h); tf = tb.text_frame; tf.word_wrap = True
        tf.margin_left = tf.margin_right = tf.margin_top = tf.margin_bottom = 0
        tf.vertical_anchor = {'t': MSO_ANCHOR.TOP, 'm': MSO_ANCHOR.MIDDLE, 'b': MSO_ANCHOR.BOTTOM}[anchor]
        for i, ptxt in enumerate(paras):
            p = tf.paragraphs[0] if i == 0 else tf.add_paragraph()
            p.alignment = {'l': PP_ALIGN.LEFT, 'c': PP_ALIGN.CENTER, 'r': PP_ALIGN.RIGHT}[align]
            p.line_spacing = spacing
            if i: p.space_before = Pt(size * 0.55)
            for j, chunk in enumerate(re.split(r'\*', ptxt)):
                if not chunk: continue
                r = p.add_run(); r.text = chunk; f = r.font
                f.size = Pt(size); f.bold = bold; f.name = font
                f.color.rgb = rgb((accent or self.t['accent']) if j % 2 else (color or self.t['ink']))
                if track: r._r.get_or_add_rPr().set('spc', str(int(size * track * 100)))
        return tb
    def head(self, s, x, y, w, h, txt, size, color=None, anchor='t', accent=None):
        return self.text(s, x, y, w, h, txt, size, color, self.t['head'], True, anchor=anchor, spacing=0.92, track=self.t['track'], accent=accent, minsize=20)
    def chrome(self, s, color=None):
        """Тонка службова лінія: назва зліва, номер справа."""
        c = color or self.t['muted']
        if self.name: self.text(s, M, inch(0.28), inch(7), inch(0.3), self.name, 12, c)
        self.text(s, W - M - inch(1.5), inch(0.28), inch(1.5), inch(0.3), f'{self.n:02d} / {self.total:02d}', 12, c, align='r')
    def notes(self, s, sd):
        if sd.get('notes'): s.notes_slide.notes_text_frame.text = sd['notes']
    def picture(self, s, path, x, y, w, h, radius=None):
        from PIL import Image
        iw, ih = Image.open(path).size
        pic = s.shapes.add_picture(path, x, y, w, h)
        fr, ir = w / h, iw / ih
        if ir > fr: c = (1 - fr / ir) / 2; pic.crop_left = pic.crop_right = c
        else: c = (1 - ir / fr) / 2; pic.crop_top = pic.crop_bottom = c
        if radius:
            pic.auto_shape_type = MSO_SHAPE.ROUNDED_RECTANGLE
            geom = pic._element.spPr.find(qn('a:prstGeom')); av = geom.find(qn('a:avLst'))
            if av is None: av = geom.makeelement(qn('a:avLst'), {}); geom.append(av)
            gd = av.makeelement(qn('a:gd'), {'name': 'adj', 'fmla': f'val {int(radius * 100000)}'}); av.append(gd)
        return pic
    def media_or_block(self, s, sd, x, y, w, h, radius=0.04):
        if sd.get('image'): self.picture(s, sd['image'], x, y, w, h, radius)
        else: self.rect(s, x, y, w, h, self.t['surface'], MSO_SHAPE.ROUNDED_RECTANGLE, radius)

    # ---------- макети
    def L_title(self, sd):
        t = self.t; s = self.slide()
        if sd.get('image'):
            self.picture(s, sd['image'], cx(6.4), M, W - cx(6.4) - M, H - 2 * M, 0.035)
            tw = cw(6)
        else:
            c = t['alt'][0]; d = inch(5.6)
            self.rect(s, W - inch(4.2), H - inch(4.4), d, d, c, MSO_SHAPE.OVAL)
            tw = cw(9.5)
        if sd.get('meta'): self.text(s, M, TOP, cw(6), inch(0.4), sd['meta'], 14, t['muted'])
        self.head(s, M, inch(1.4), tw, inch(4.3), sd['title'], 88, anchor='b')
        if sd.get('subtitle'): self.text(s, M, inch(5.95), min(tw, cw(6.5)), inch(0.9), sd['subtitle'], 20, t['muted'], spacing=1.15)
        self.notes(s, sd)
    def L_section(self, sd):
        t = self.t; bg = self.fill_color(); fg = on(bg); s = self.slide(bg)
        if sd.get('number'): self.text(s, M, TOP, cw(6), inch(2.6), sd['number'], 150, fg, t['head'], True, track=-0.05, spacing=0.85, minsize=60)
        self.head(s, M, inch(3.4), cw(10), inch(2.6), sd['title'], 72, fg, anchor='b', accent=fg)
        if sd.get('subtitle'): self.text(s, M, inch(6.2), cw(7), inch(0.7), sd['subtitle'], 18, fg)
        self.notes(s, sd)
    def L_statement(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.3), cw(11), inch(4.6), sd['title'], 66, anchor='m')
        if sd.get('subtitle'):
            self.line(s, M, inch(6.25), cw(3), t['ink'], 1.5)
            self.text(s, M, inch(6.4), cw(8), inch(0.6), sd['subtitle'], 16, t['muted'])
        self.notes(s, sd)
    def L_bullets(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        items = sd['items'][:5]
        if sd.get('image'):
            self.picture(s, sd['image'], cx(7), M, W - cx(7) - M, H - 2 * M, 0.035)
            self.head(s, M, inch(1.1), cw(6.3), inch(1.9), sd['title'], 40)
            lx, lw, ly = M, cw(6.3), inch(3.25)
        else:
            self.head(s, M, inch(1.1), cw(4.6), inch(4.8), sd['title'], 46)
            lx, lw, ly = cx(5.4), cw(6.6), inch(1.15)
        rh = (H - ly - inch(0.7)) / len(items)
        for i, it in enumerate(items):
            y = int(ly + i * rh)
            self.line(s, lx, y, lw)
            hd, _, rest = it.partition(' :: ')
            self.text(s, lx, y + inch(0.16), inch(0.6), inch(0.4), f'{i + 1:02d}', 14, t['accent'], bold=True)
            self.text(s, lx + inch(0.65), y + inch(0.12), lw - inch(0.65), int(rh * 0.42), hd, 22, None, t['head'], True, spacing=1.0)
            if rest: self.text(s, lx + inch(0.65), y + int(rh * 0.46), lw - inch(0.65), int(rh * 0.48), rest, 16, t['muted'], spacing=1.15)
        self.notes(s, sd)
    def L_cards(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(9), inch(1.6), sd['title'], 46)
        cards = sd['cards'][:4]; n = len(cards); gap = inch(0.22); w = (W - 2 * M - gap * (n - 1)) // n
        y = inch(2.95); h = H - y - M
        for i, c in enumerate(cards):
            x = M + i * (w + gap); bg = t['alt'][i % len(t['alt'])] if i == 0 else t['surface']; fg = on(bg, t['ink'], 'FFFFFF') if i == 0 else t['ink']
            self.rect(s, x, y, w, h, bg, MSO_SHAPE.ROUNDED_RECTANGLE, 0.05)
            if c.get('tag'): self.text(s, x + inch(0.3), y + inch(0.3), w - inch(0.6), inch(0.4), c['tag'], 14, fg if i == 0 else t['muted'])
            self.text(s, x + inch(0.3), y + h - inch(2.3), w - inch(0.6), inch(1.0), c['title'], 24, fg, t['head'], True, anchor='b', spacing=0.95, track=t['track'])
            if c.get('text'): self.text(s, x + inch(0.3), y + h - inch(1.2), w - inch(0.6), inch(0.95), c['text'], 15, fg if i == 0 else t['muted'], spacing=1.15)
        self.notes(s, sd)
    def L_two_col(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(10), inch(1.6), sd['title'], 46)
        gap = inch(0.22); w = (W - 2 * M - gap) // 2; y = inch(2.95); h = H - y - M
        for i, col in enumerate(sd['columns'][:2]):
            x = M + i * (w + gap); bg = t['ink'] if i == 1 else t['surface']; fg = t['bg'] if i == 1 else t['ink']
            mu = t['line'] if i == 1 else t['muted']
            self.rect(s, x, y, w, h, bg, MSO_SHAPE.ROUNDED_RECTANGLE, 0.04)
            self.text(s, x + inch(0.4), y + inch(0.35), w - inch(0.8), inch(0.9), col['heading'], 30, fg, t['head'], True, spacing=0.95, track=t['track'])
            body = col.get('items') or [col.get('text', '')]
            self.text(s, x + inch(0.4), y + inch(1.45), w - inch(0.8), h - inch(1.8), body, 17, fg if i == 1 else t['ink'], spacing=1.2)
        self.notes(s, sd)
    def L_stats(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(9), inch(1.6), sd['title'], 46)
        st = sd['stats'][:4]; n = len(st); w = (W - 2 * M) // n; y = inch(3.0)
        for i, it in enumerate(st):
            x = M + i * w
            if i: self.vline(s, x, y, inch(3.3))
            px = x + (inch(0.35) if i else 0)
            vs = int(min(110, (w - inch(0.5)) / 12700 / (max(len(it['value']), 2) * 0.64)))
            self.text(s, px, y, w - inch(0.5), inch(1.9), it['value'], vs, t['accent'] if i == 0 else t['ink'], t['head'], True, anchor='b', spacing=0.85, track=-0.05, minsize=40)
            self.text(s, px, y + inch(2.05), w - inch(0.6), inch(1.2), it['label'], 17, t['muted'], spacing=1.15)
        if sd.get('source'): self.text(s, M, H - inch(0.55), cw(10), inch(0.3), 'Джерело: ' + sd['source'], 12, t['muted'])
        self.notes(s, sd)
    def L_chart(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(4.4), inch(3.2), sd['title'], 40)
        if sd.get('takeaway'): self.text(s, M, inch(4.4), cw(4), inch(1.8), sd['takeaway'], 18, t['muted'], spacing=1.2)
        kind = sd.get('kind', 'bar')
        xt = {'bar': XL_CHART_TYPE.COLUMN_CLUSTERED, 'hbar': XL_CHART_TYPE.BAR_CLUSTERED, 'line': XL_CHART_TYPE.LINE_MARKERS, 'pie': XL_CHART_TYPE.DOUGHNUT}[kind]
        cd = CategoryChartData(); cd.categories = sd['categories']
        for name, vals in sd['series'].items(): cd.add_series(name, vals)
        gf = s.shapes.add_chart(xt, cx(5), inch(1.0), W - cx(5) - M, H - inch(1.0) - inch(0.6), cd); ch = gf.chart
        ch.has_title = False; ch.font.size = Pt(14); ch.font.name = t['body']; ch.font.color.rgb = rgb(t['muted'])
        ch.has_legend = len(sd['series']) > 1 or kind == 'pie'
        if ch.has_legend: ch.legend.position = XL_LEGEND_POSITION.BOTTOM; ch.legend.include_in_layout = False
        plot = ch.plots[0]; hi = sd.get('highlight', len(sd['categories']) - 1)
        if kind == 'pie':
            pal = [t['accent'], t['ink'], t['muted'], t['line']]
            for i, pt in enumerate(plot.series[0].points): pt.format.fill.solid(); pt.format.fill.fore_color.rgb = rgb(pal[i % 4])
        else:
            if kind != 'line': plot.gap_width = 45
            for si, se in enumerate(plot.series):
                if kind == 'line':
                    se.format.line.color.rgb = rgb(t['accent'] if si == 0 else t['muted']); se.format.line.width = Pt(3.5); se.smooth = False
                else:
                    se.format.fill.solid(); se.format.fill.fore_color.rgb = rgb(t['line'] if len(sd['series']) == 1 else (t['accent'] if si == 0 else t['muted']))
                    if len(sd['series']) == 1:
                        pt = se.points[hi]; pt.format.fill.solid(); pt.format.fill.fore_color.rgb = rgb(t['accent'])
            plot.has_data_labels = True; dl = plot.data_labels; dl.font.size = Pt(16); dl.font.bold = True; dl.font.color.rgb = rgb(t['ink'])
            if kind != 'line': dl.position = XL_LABEL_POSITION.OUTSIDE_END
            ch.value_axis.has_major_gridlines = False; ch.value_axis.visible = False
            ch.category_axis.format.line.color.rgb = rgb(t['line']); ch.category_axis.tick_labels.font.size = Pt(14)
        if sd.get('source'): self.text(s, M, H - inch(0.55), cw(5), inch(0.3), 'Джерело: ' + sd['source'], 12, t['muted'])
        self.notes(s, sd)
    def L_process(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(9), inch(1.6), sd['title'], 46)
        st = sd['steps'][:5]; n = len(st); gap = inch(0.22); w = (W - 2 * M - gap * (n - 1)) // n; y = inch(3.0)
        for i, it in enumerate(st):
            x = M + i * (w + gap)
            self.rect(s, x, y, w, inch(0.06), t['accent'] if i == 0 else t['ink'])
            self.text(s, x, y + inch(0.25), w, inch(1.2), f'{i + 1:02d}', 64, t['accent'] if i == 0 else t['line'], t['head'], True, track=-0.05, spacing=0.85, minsize=30)
            self.text(s, x, y + inch(1.55), w - inch(0.15), inch(0.9), it['title'], 21, None, t['head'], True, spacing=0.98, track=t['track'])
            if it.get('text'): self.text(s, x, y + inch(2.45), w - inch(0.15), H - y - inch(2.45) - M + inch(0.2), it['text'], 15, t['muted'], spacing=1.18)
        self.notes(s, sd)
    def L_quote(self, sd):
        t = self.t; bg = t['surface']; s = self.slide(bg); self.chrome(s)
        if sd.get('image'):
            self.picture(s, sd['image'], M, inch(1.0), cw(3.4), cw(3.4) * 5 // 4, 0.04); qx = cx(4.2)
        else: qx = M
        self.text(s, qx, inch(0.75), inch(1.5), inch(1.6), '\u201C', 130, t['accent'], t['head'], True, spacing=0.8, minsize=100)
        self.head(s, qx, inch(1.9), W - qx - M, inch(3.6), sd['quote'], 44)
        self.text(s, qx, inch(5.85), cw(6), inch(0.9), sd.get('author', ''), 16, t['muted'], spacing=1.2)
        self.notes(s, sd)
    def L_table(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(9), inch(1.5), sd['title'], 44)
        rows = [sd['header']] + sd['rows']; nr, nc = len(rows), len(rows[0])
        y0 = inch(2.8); rh = min(inch(0.7), (H - y0 - M) // nr); cwid = (W - 2 * M) // nc
        size = 17 if nr <= 6 else 14
        for r, row in enumerate(rows):
            y = y0 + r * rh
            self.line(s, M, y + rh, W - 2 * M, t['ink'] if r == 0 else t['line'], 1.25 if r == 0 else 0.75)
            for c, val in enumerate(row):
                hl = sd.get('highlight') == c and r > 0
                self.text(s, M + c * cwid, y + inch(0.12), cwid - inch(0.2), rh - inch(0.15), str(val), 14 if r == 0 else size,
                          t['muted'] if r == 0 else (t['accent'] if hl else t['ink']), None, r > 0 and (c == 0 or hl), anchor='m')
        self.notes(s, sd)
    def L_image(self, sd):
        t = self.t; s = self.slide('111111')
        self.picture(s, sd['image'], 0, 0, W, H)
        cwid = cw(7); ch_ = inch(2.5); y = H - M - ch_
        self.rect(s, M, y, cwid, ch_, t['bg'], MSO_SHAPE.ROUNDED_RECTANGLE, 0.06)
        self.head(s, M + inch(0.4), y + inch(0.35), cwid - inch(0.8), ch_ - inch(0.9), sd['title'], 40, anchor='t')
        if sd.get('caption'): self.text(s, M + inch(0.4), y + ch_ - inch(0.5), cwid - inch(0.8), inch(0.3), sd['caption'], 12, t['muted'])
        self.notes(s, sd)
    def L_gallery(self, sd):
        t = self.t; s = self.slide(); self.chrome(s)
        self.head(s, M, inch(1.0), cw(9), inch(1.5), sd['title'], 44)
        imgs = sd['images'][:3]; n = len(imgs); gap = inch(0.2); y = inch(2.8)
        ws = {1: [12], 2: [7, 5], 3: [5, 3.5, 3.5]}[n]; x = M
        for i, (path, k) in enumerate(zip(imgs, ws)):
            w = cw(k) - (gap if i < n - 1 else 0)
            self.picture(s, path, x, y, w, H - y - M, 0.04); x += w + gap
        self.notes(s, sd)
    def L_closing(self, sd):
        t = self.t; bg = t['ink']; fg = t['bg']; s = self.slide(bg)
        self.head(s, M, inch(1.0), cw(11), inch(3.4), sd['title'], 96, fg, anchor='b', accent=t['accent'])
        y = inch(4.9)
        self.line(s, M, y, W - 2 * M, t['muted'])
        if sd.get('items'): self.text(s, M, y + inch(0.3), cw(7), inch(1.6), sd['items'], 18, fg, spacing=1.2)
        if sd.get('contact'): self.text(s, cx(8), y + inch(0.3), cw(4), inch(1.6), sd['contact'], 18, fg, align='r', spacing=1.25)
        self.notes(s, sd)

    def build(self, out):
        for sd in self.spec['slides']: getattr(self, 'L_' + sd['layout'])(sd)
        self.prs.save(out)

if __name__ == '__main__':
    spec = json.load(open(sys.argv[1], encoding='utf-8'))
    Deck(spec).build(sys.argv[2]); print('ok', sys.argv[2], len(spec['slides']), 'слайдів')
    for w in WARN: print('УВАГА:', w)
```

```sh
# file: tools/render.sh — bash tools/render.sh out.pptx ; PDF + лист мініатюр qa/sheet.png
set -e
mkdir -p qa && soffice --headless --convert-to pdf --outdir qa "$1" >/dev/null 2>&1
pdf="qa/$(basename "${1%.*}").pdf"; rm -f qa/s-*.png; pdftoppm -r 45 -png "$pdf" qa/s
python3 - <<'PY'
from PIL import Image; import glob
ims=[Image.open(p) for p in sorted(glob.glob('qa/s-*.png'))]
w,h=ims[0].size; c=4; r=(len(ims)+c-1)//c
o=Image.new('RGB',(c*w+(c-1)*10,r*h+(r-1)*10),'#777')
for i,im in enumerate(ims): o.paste(im,((i%c)*(w+10),(i//c)*(h+10)))
o.save('qa/sheet.png'); print('qa/sheet.png', len(ims), 'слайдів')
PY
```
