ПОЛНЫЙ PIPELINE: AI-ВИДЕО С КОНСИСТЕНТНЫМИ ПЕРСОНАЖАМИ

Назначение: Пошаговое создание видео-анимаций с консистентными персонажами/объектами от идеи до финала
Целевая аудитория: Новички и начинающие практики
Версия: 2.0 EXTENDED | Дата: 2026-02-25
Охват: Видео 1-2 мин (20-40 кадров) и 3-5 мин (50-80 кадров)
📑 НАВИГАЦИЯ ПО PIPELINE
🎬 ОСНОВНЫЕ БЛОКИ

БЛОК #0 → Выбор визуального стиля
БЛОК #1 → Сценарий и shot list
БЛОК #2 → Сбор референсов
БЛОК #3 → Создание базового персонажа
БЛОК #4 → Карта консистентности персонажа
БЛОК #5 → Генерация изображений сцен
БЛОК #6 → Апскейл и очистка
БЛОК #7 → Анимация (image-to-video)
БЛОК #8 → Звук, музыка, озвучка
БЛОК #9 → Финальный монтаж
🔒 СПЕЦИАЛИЗИРОВАННЫЕ БЛОКИ КОНСИСТЕНТНОСТИ

КОНСИСТЕНТНОСТЬ-1 → Консистентность персонажей (методы)
КОНСИСТЕНТНОСТЬ-2 → Консистентность последовательности кадров
КОНСИСТЕНТНОСТЬ-3 → Консистентность объектов/субъектов
КОНСИСТЕНТНОСТЬ-4 → Консистентность дизайна/цвета
📊 ДОПОЛНИТЕЛЬНЫЕ РАЗДЕЛЫ

ВРЕМЕННАЯ ОЦЕНКА → Сколько времени на каждый блок
СТРАТЕГИЯ ЛИМИТОВ → Как эффективно использовать бесплатные тарифы
ТИПИЧНЫЕ ОШИБКИ → Частые проблемы и их решения
ФИНАЛЬНЫЙ ЧЕК-ЛИСТ → Проверка готовности проекта
БЛОК #0: ВЫБОР ВИЗУАЛЬНОГО СТИЛЯ ("СТИЛЬ-КУХНЯ")
🎯 Цель блока

Определить визуальную эстетику проекта до начала генерации изображений. Выбранный стиль станет основой всех промптов.
📚 Популярные стили и их характеристики
Стиль 1: COWBOY BEBOP + STAR WARS: CLONE WARS BAD BATCH (гибрид)

Характеристики:

    Cowboy Bebop: Реалистичные пропорции, приглушённые цвета (коричневый, тёмно-синий, оранжевый), детализированные фоны, киношная композиция, ретро-футуризм 90-х
    Bad Batch: Стилизованные лица с угловатыми чертами, яркие акценты (неоновые линии, маркировки), военный Tech-Noir, динамичные позы, чёткие контуры

Промпт-формула для этого стиля:
Code

[Тип плана] of [персонаж/объект], 
[описание внешности/деталей],
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic proportions, muted color palette with [основные цвета],
angular facial features, detailed background with [элементы окружения],
cinematic composition, tech-noir lighting,
high quality, 4K, cel-shaded with sharp outlines

ПРИМЕР ПРОМПТА (персонаж):
Code

Full body shot of male bounty hunter character,
wearing worn brown leather jacket with orange accents, dark cargo pants, utility belt,
holstered blaster on hip, short black hair with grey streaks,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic proportions, muted color palette with browns, dark blues, and orange highlights,
angular facial features with sharp jawline, detailed background with industrial spaceship hangar,
cinematic composition with dramatic side lighting, tech-noir atmosphere,
high quality, 4K, cel-shaded with sharp black outlines

РАЗБОР ПРОМПТА:
Часть промпта	Что делает	Почему важно
Full body shot	Определяет тип плана	Нужен полный силуэт для создания базового референса
male bounty hunter character	Роль персонажа	Задаёт архетип (bounty hunter = грубый, практичный дизайн)
worn brown leather jacket with orange accents	Детали одежды	Специфические элементы для консистентности
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch	Стилевой микс	Ключевая часть — AI смешивает две эстетики
realistic proportions	Контроль анатомии	Избегаем чиби/SD-деформаций
muted color palette with browns, dark blues, orange	Цветовая схема	Задаём точную палитру Bebop
angular facial features	Стиль лица	Черта Bad Batch (угловатость)
cinematic composition, tech-noir lighting	Киношность	Атмосфера neo-noir
cel-shaded with sharp black outlines	Техника	Чёткие контуры = anime look

ВАРИАЦИИ ПРОМПТА:

Вариация 1 (больше Bebop, меньше Bad Batch):
Code

[...same character details...],
anime style inspired by Cowboy Bebop with subtle Star Wars Clone Wars influences,
realistic human proportions, hand-drawn aesthetic,
muted retro-futuristic color palette,
[...rest same...]

Вариация 2 (больше Bad Batch, меньше Bebop):
Code

[...same character details...],
anime style inspired by Star Wars Clone Wars Bad Batch with Cowboy Bebop color tones,
stylized angular features, bold cel-shading,
saturated colors with neon accents,
[...rest same...]

Вариация 3 (для сцены, не персонажа):
Code

Wide establishing shot of abandoned industrial spaceport at sunset,
rusted metal structures, flickering neon signs in Japanese characters,
parked beat-up spacecraft,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
cinematic composition, warm orange and cool blue contrast,
detailed background painting, atmospheric perspective,
high quality, 4K, no characters

Стиль 2: PIXAR (3D мультипликационный)

Характеристики:

    Мягкое освещение (soft ambient lighting)
    Яркие насыщенные цвета
    Округлые формы, большие выразительные глаза
    Глянцевые материалы (plastic-like shaders)
    Высокая детализация текстур

Промпт-формула:
Code

[Тип плана] of [персонаж/объект],
[описание внешности],
Pixar animation style, 3D rendered character,
vibrant saturated colors, soft ambient lighting,
large expressive eyes, rounded shapes,
smooth plastic-like shader, detailed textures,
Disney Pixar quality, 8K render, octane render

ПРИМЕР:
Code

Medium shot of young female engineer character,
wearing blue overalls with tool patches, short curly red hair, freckles, friendly smile,
Pixar animation style, 3D rendered character,
vibrant saturated colors with primary blue and red, soft ambient lighting from above,
large expressive green eyes, rounded face proportions,
smooth plastic-like shader on clothing, detailed fabric textures,
Disney Pixar quality, 8K render, octane render,
workshop background with colorful tools

РАЗБОР:

    Pixar animation style — ключевое слово, активирует базу данных Pixar-эстетики в AI
    3D rendered — отличает от 2D anime
    vibrant saturated colors — яркость Pixar vs приглушённые тона Bebop
    large expressive eyes — signature Pixar (vs реалистичные глаза)
    octane render — технический термин для фотореалистичного 3D-рендеринга

ВАРИАЦИИ:

Вариация 1 (больше реализма):
Code

[...same...],
Pixar style with realistic textures,
subsurface scattering on skin, physically-based rendering,
[...rest...]

Вариация 2 (стилизация под конкретный фильм):
Code

[...same...],
Pixar animation style similar to "The Incredibles",
retro-futuristic 1960s aesthetic,
[...rest...]

Стиль 3: CYBERPUNK ANIME (Akira, Ghost in the Shell)

Характеристики:

    Неоновая подсветка (neon lights)
    Тёмные тени, высокий контраст
    Дождливые улицы, мокрый асфальт (rain-slicked streets)
    Технологический детализм (cybernetic implants)
    Цвета: фиолетовый, синий, розовый неон

Промпт-формула:
Code

[Тип плана] of [персонаж],
[детали внешности],
cyberpunk anime style similar to Akira and Ghost in the Shell,
neon-lit urban environment, dark shadows with high contrast,
rain-slicked streets reflecting neon lights,
detailed cybernetic implants, futuristic tech details,
color palette: deep purples, electric blues, hot pinks,
atmospheric fog, cinematic night scene,
high detail, 4K

ПРИМЕР:
Code

Full body shot of female hacker character,
wearing black tactical jacket with glowing circuit patterns, cybernetic arm with exposed wiring,
short white hair with pink highlights, augmented reality visor over one eye,
cyberpunk anime style similar to Ghost in the Shell,
neon-lit Tokyo alleyway background, dark shadows with high contrast,
rain-slicked streets reflecting pink and blue neon signs,
detailed cybernetic implants on neck and arms, holographic interface floating nearby,
color palette: deep purples, electric blues, hot pinks, black,
atmospheric fog, cinematic night scene, lens flare from neon,
high detail, 4K, anime cel-shading

РАЗБОР:

    similar to Akira and Ghost in the Shell — конкретные референсы (AI знает эти фильмы)
    neon-lit urban environment — ключевая черта киберпанка
    rain-slicked streets reflecting — фирменный визуал (отражения = глубина)
    cybernetic implants — технологические детали персонажа
    deep purples, electric blues, hot pinks — точная киберпанк-палитра

ВАРИАЦИИ:

Вариация 1 (больше Akira):
Code

[...same...],
cyberpunk anime style similar to Akira,
gritty hand-drawn aesthetic, motion blur effects,
red neon dominance,
[...rest...]

Вариация 2 (больше Ghost in the Shell):
Code

[...same...],
cyberpunk anime style similar to Ghost in the Shell,
philosophical atmosphere, cold blue tones,
minimalist composition,
[...rest...]

Стиль 4: MECHA SCI-FI ANIME (Gundam, Evangelion)

Характеристики:

    Механические детали (mechanical details)
    Технические чертежи в фоне (technical schematics)
    Металлические текстуры (metallic shaders)
    Военный реализм (military realism)
    Масштабные сцены (epic scale)

Промпт-формула:
Code

[Тип плана] of [меха/пилот],
[технические детали],
mecha sci-fi anime style similar to Gundam/Evangelion,
detailed mechanical design, panel lines and rivets,
metallic shaders with weathering and scratches,
technical schematic overlays in background,
military realism, epic scale,
dynamic action pose,
color scheme: [военные цвета],
high detail, 4K

ПРИМЕР (меха):
Code

Full body shot of humanoid mecha robot,
white and blue armor plating, shoulder-mounted missile pods, beam saber in right hand,
red monoeye sensor in head, angular joints with exposed hydraulics,
mecha sci-fi anime style similar to Gundam,
detailed mechanical design with panel lines and rivets visible,
metallic shaders with battle damage weathering and scratches,
technical schematic overlays in background showing specifications,
military realism, epic scale standing on ruined battlefield,
dynamic standing pose with saber raised,
color scheme: white primary, blue accents, red sensor,
high detail, 4K, anime cel-shading with realistic mecha textures

ПРИМЕР (пилот):
Code

Medium shot of teenage male mecha pilot,
wearing white plugsuit with blue stripes, neural interface headset,
determined expression, short dark hair,
mecha sci-fi anime style similar to Evangelion,
cockpit interior background with holographic displays,
dramatic lighting from control panels,
realistic human proportions,
color scheme: white suit, blue accents, orange emergency lights,
high detail, 4K

РАЗБОР:

    panel lines and rivets — реалистичные механические детали (важно для mecha)
    metallic shaders with weathering — текстурная реалистичность
    technical schematic overlays — стилистический элемент жанра
    military realism — отличает от супер-робота (более грубый дизайн)

Стиль 5: CINEMATIC REALISTIC (художественный кинематографичный)

Характеристики:

    Фотореалистичность (photorealistic)
    Киношное освещение (cinematic lighting)
    Глубина резкости (depth of field, bokeh)
    Естественные цвета (natural color grading)
    Кинематографичная композиция (rule of thirds)

Промпт-формула:
Code

[Тип плана] of [персонаж],
[реалистичные детали],
cinematic realistic style, photorealistic rendering,
shot on [камера/объектив] with shallow depth of field,
natural lighting with [тип освещения],
film grain, color grading similar to [фильм],
detailed skin textures and fabric materials,
8K, unreal engine render

ПРИМЕР:
Code

Medium close-up shot of middle-aged male detective,
wearing grey trench coat, 5 o'clock shadow, tired eyes, rain droplets on face,
cinematic realistic style, photorealistic rendering,
shot on Arri Alexa with 50mm lens, shallow depth of field with bokeh background,
natural lighting with harsh side light from neon sign creating dramatic shadows,
film grain, color grading similar to Blade Runner 2049 (desaturated with orange and teal),
detailed skin textures with pores visible, wet fabric materials on coat,
rain-soaked city street background out of focus,
8K, unreal engine 5 render

РАЗБОР:

    shot on Arri Alexa with 50mm lens — симулирует реальную камеру (AI понимает характеристики)
    shallow depth of field with bokeh — размытие фона = киношность
    film grain — текстура плёнки (добавляет органичность)
    color grading similar to Blade Runner 2049 — конкретный цветовой эталон
    detailed skin textures with pores visible — гиперреализм
    unreal engine 5 render — технический термин для реалистичной графики

ВАРИАЦИИ:

Вариация 1 (больше noir):
Code

[...same...],
black and white noir cinematography, high contrast,
venetian blind shadows, smoke atmosphere,
[...rest...]

Вариация 2 (естественное освещение):
Code

[...same...],
natural daylight through window, soft shadows,
warm color temperature, intimate atmosphere,
[...rest...]

🛠 ИНСТРУМЕНТЫ ДЛЯ ТЕСТИРОВАНИЯ СТИЛЕЙ
100% БЕСПЛАТНЫЕ (без регистрации или unlimited)

✅ Bing Image Creator (DALL-E 3)

    Ссылка: https://www.bing.com/images/create
    Free tier: 15 быстрых генераций/день (потом медленнее, но unlimited)
    Для чего: Быстрое тестирование промптов на разных стилях
    Плюсы: Понимает сложные стилевые запросы ("blend of X and Y"), высокое качество
    Минусы: Не поддерживает img2img, фильтр NSFW
    Рекомендация: Используйте для первичных экспериментов со стилями

✅ Playground AI

    Ссылка: https://playgroundai.com
    Free tier: 500 генераций/день (модели SDXL)
    Для чего: Сравнение стилей на разных SD-моделях
    Плюсы: Большой выбор моделей (есть anime-специализированные), img2img
    Минусы: Интерфейс сложнее для новичков
    Рекомендация: Используйте для тестирования anime/Pixar стилей с разными моделями

✅ Craiyon (бывший DALL-E mini)

    Ссылка: https://www.craiyon.com
    Free tier: Unlimited (медленная генерация, с рекламой)
    Для чего: Черновые наброски стилей
    Плюсы: Нет лимитов, не нужна регистрация
    Минусы: Низкое качество vs DALL-E 3/SDXL
    Рекомендация: Для быстрого визуального брейншторминга идей

FREE TIER (требуется регистрация, есть лимиты)

✅ Leonardo.AI

    Ссылка: https://leonardo.ai
    Free tier: 150 токенов/день (~30-50 изображений)
    Для чего: Тестирование специализированных моделей (Leonardo Anime XL, Leonardo Vision XL)
    Плюсы: Модели заточены под конкретные стили, img2img, ControlNet
    Минусы: Лимит токенов
    Рекомендация: Используйте для финальных тестов стиля перед основной работой

✅ Tensor.Art

    Ссылка: https://tensor.art
    Free tier: 100 кредитов/день (~20-40 генераций)
    Для чего: Anime-стили (огромная библиотека anime-моделей)
    Плюсы: Специализация на anime, много community-моделей
    Минусы: Азиатский интерфейс, медленная загрузка
    Рекомендация: Идеален для Cyberpunk Anime, Mecha стилей

✅ SeaArt.AI

    Ссылка: https://www.seaart.ai
    Free tier: 200 кредитов/день
    Для чего: Быстрая генерация anime-стилей
    Плюсы: Простой интерфейс, быстрая генерация
    Минусы: Китайская платформа
    Рекомендация: Для Pixar/anime стилей

✅ Ideogram

    Ссылка: https://ideogram.ai
    Free tier: 100 генераций/месяц (медленная очередь — unlimited)
    Для чего: Реалистичные стили (Cinematic Realistic)
    Плюсы: Отличная работа с текстом в изображениях, реализм
    Минусы: Лимит быстрых генераций
    Рекомендация: Для Cinematic/Realistic стилей

✅ Gemini (Google AI Studio)

    Ссылка: https://aistudio.google.com (или https://gemini.google.com)
    Free tier: Imagen 3 доступен бесплатно с лимитами
    Для чего: Генерация изображений + создание сеток ракурсов
    Плюсы: Интеграция с текстовым Gemini для создания промптов
    Минусы: Качество варьируется, экспериментальная функция
    Рекомендация: Для экспериментов с гибридными стилями

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #0

    Выбран основной стиль проекта (из 5+ вариантов)
    Протестированы 3-5 промптов в выбранном стиле на 2-3 инструментах
    Определены ключевые слова стиля для всех будущих промптов
    Сохранены 2-3 лучших тестовых изображения как референсы стиля
    Записана итоговая промпт-формула стиля в текстовый файл

БЛОК #1: СЦЕНАРИЙ И SHOT LIST
🎯 Цель блока

Создать детализированный сценарий и shot list (список кадров) с описанием каждой сцены.
📝 Шаги
Шаг 1.1: Генерация базовой истории

Действие: Открыть AI-сервис, описать идею видео, запросить генерацию истории.

ПРОМПТ-ФОРМУЛА:
Code

Create a story for a [длительность] animated video about [тема/концепт].

Story should include:
- Main character: [краткое описание]
- Setting: [место и время]
- Conflict: [проблема/цель]
- Key event: [центральное событие]
- Resolution: [как заканчивается]

Tone: [драматичный/комедийный/экшен]
Target length: [20-40 shots / 50-80 shots]
Style reference: [выбранный стиль из Блока #0]

ПРИМЕР ПРОМПТА:
Code

Create a story for a 2-minute animated video about a lone bounty hunter tracking a rogue AI in a cyberpunk city.

Story should include:
- Main character: Veteran bounty hunter, age 45, cynical but skilled, wears worn tactical gear
- Setting: Neon-lit megacity, night, rain-soaked streets, year 2157
- Conflict: Must capture rogue AI controlling city's defense systems before it causes mass casualties
- Key event: Final confrontation in abandoned data center, hunter must choose between destroying AI or understanding its motives
- Resolution: Hunter spares AI after learning it was protecting citizens from corrupt government, they form uneasy alliance

Tone: Dark, philosophical, action-packed
Target length: 30-35 shots
Style reference: Blend of Cowboy Bebop and Blade Runner aesthetics

РАЗБОР ПРОМПТА:
Элемент	Функция	Почему важно
2-minute animated video	Определяет масштаб	AI поймёт, что нужна короткая история, не эпопея
lone bounty hunter tracking rogue AI	Жанр и концепт	Конкретная завязка (vs "история про будущее")
Main character: Veteran...	Характер	Создаёт визуальный образ (возраст, одежда)
Setting: Neon-lit megacity, night, rain	Атмосфера	Конкретные визуальные детали для будущих сцен
Conflict: Must capture...before...	Стейки	"Before X happens" = срочность
Key event: Final confrontation in data center	Структура	Задаёт кульминацию
Resolution: Hunter spares AI...	Моральная дилемма	Глубина истории (не просто "победил врага")
Target length: 30-35 shots	Технические рамки	AI структурирует историю под нужное количество сцен

ВАРИАЦИИ ПРОМПТА:

Вариация 1 (для комедийной истории):
Code

Create a story for a 90-second comedic animated video about a clumsy robot chef trying to impress food critics.

Story should include:
- Main character: Enthusiastic but malfunctioning robot chef, speaks in broken English, prone to kitchen disasters
- Setting: High-end futuristic restaurant, daytime, floating kitchen
- Conflict: Must prepare perfect meal for three snobbish food critics or restaurant gets shut down
- Key event: Kitchen catches fire during dessert preparation, robot improvises with fire extinguisher foam as ingredient
- Resolution: Critics love the "deconstructed foam dessert", robot accidentally becomes famous

Tone: Slapstick comedy, lighthearted
Target length: 25 shots
Style reference: Pixar animation style

Вариация 2 (для экшен-видео на 5 минут):
Code

Create a story for a 5-minute action-packed animated video about mecha pilot defending colony from alien invasion.

Story should include:
- Main character: Young female rookie pilot, age 19, nervous but brave
- Setting: Mars colony under siege, red desert landscape, year 2280
- Conflict: Aliens broke through outer defenses, she's the only pilot remaining to protect evacuation ships
- Key event: Final battle against alien flagship, her mecha is damaged but she uses clever tactics
- Resolution: Destroys flagship by sacrificing mecha, ejects at last second, becomes colony hero

Tone: Heroic, intense, emotional
Target length: 60-70 shots
Style reference: Gundam-style mecha anime

Куда вставить промпт:

    ChatGPT / Claude / Gemini (бесплатные версии)

Ожидаемый результат:
Текст истории 300-800 слов с завязкой, развитием, кульминацией, развязкой.
Шаг 1.2: Преобразование истории в сценарий

Действие: Скопировать полученную историю, вставить в AI-сервис с новым запросом на создание сценария.

ПРОМПТ-ФОРМУЛА:
Code

Transform this story into a detailed screenplay/script format.

[ВСТАВИТЬ ИСТОРИЮ ИЗ ШАГА 1.1]

Format each scene as:
- SCENE NUMBER
- LOCATION (interior/exterior, time of day)
- ACTION (what happens visually)
- DIALOGUE (if any, with character names)

Include camera direction notes where important (e.g., CLOSE-UP, WIDE SHOT).
Focus on visual storytelling.

ПРИМЕР ПРОМПТА:
Code

Transform this story into a detailed screenplay/script format.

[История про bounty hunter и AI из примера выше]

Format each scene as:
- SCENE NUMBER
- LOCATION (interior/exterior, time of day)
- ACTION (what happens visually)
- DIALOGUE (if any, with character names)

Include camera direction notes where important (e.g., CLOSE-UP, WIDE SHOT).
Focus on visual storytelling. Each scene should be 3-8 seconds long for animation.

Ожидаемый результат:
Code

SCENE 1 - ESTABLISHING SHOT
EXT. MEGACITY SKYLINE - NIGHT, RAIN

Neon signs flicker across towering skyscrapers. Rain pours down. Camera pans down from sky to street level.

---

SCENE 2 - INTRODUCE HUNTER
EXT. ALLEYWAY - NIGHT

WIDE SHOT: HUNTER (45, weathered face, tactical gear) walks through rain-slicked alley. Neon lights reflect in puddles. He checks holographic wrist display.

HUNTER (mutters):
"Sector 7. This better be worth the credits."

---

SCENE 3 - AI DETECTION
INT. HUNTER'S VISOR HUD - NIGHT

CLOSE-UP: Hunter's visor display. AR interface shows heat signatures. One signature blinks RED - "ROGUE AI DETECTED".

HUNTER:
"Got you."

[И так далее...]

ВАРИАЦИИ:

Вариация 1 (без диалогов, только визуал):
Code

Transform this story into a visual-only screenplay (no dialogue, pure visual storytelling like a silent film).

[История]

Each scene should describe:
- What character does
- Camera angle
- Emotion conveyed through action

Вариация 2 (с тайм-кодами):
Code

Transform this story into a screenplay with timecodes.

[История]

Format:
- [00:00-00:05] SCENE 1 - Description
- [00:05-00:12] SCENE 2 - Description
Target total duration: [1 min / 2 min / 5 min]

Шаг 1.3: Создание shot list (список кадров)

Действие: Взять сценарий, попросить AI разбить на конкретные кадры с техническими деталями.

ПРОМПТ-ФОРМУЛА:
Code

Create a detailed shot list from this screenplay.

[ВСТАВИТЬ СЦЕНАРИЙ ИЗ ШАГА 1.2]

For each shot, provide:
1. Shot number
2. Shot type (establishing shot / wide shot / medium shot / close-up / extreme close-up)
3. Subject (what/who is in frame)
4. Action (what happens)
5. Duration (estimated seconds)
6. Camera movement (static / pan / tilt / zoom / dolly)
7. Notes (lighting, mood, important details)

Format as table or numbered list.
Total target: [20-40 shots for 1-2 min / 50-80 shots for 3-5 min]

ПРИМЕР ПРОМПТА:
Code

Create a detailed shot list from this screenplay.

[Сценарий bounty hunter из шага 1.2]

For each shot, provide:
1. Shot number
2. Shot type (establishing shot / wide shot / medium shot / close-up / extreme close-up)
3. Subject (what/who is in frame)
4. Action (what happens)
5. Duration (estimated seconds)
6. Camera movement (static / pan / tilt / zoom / dolly)
7. Notes (lighting, mood, important details)

Format as table.
Total target: 30-35 shots for 2-minute video
Style reference: Cowboy Bebop + Blade Runner (for lighting and composition notes)

Ожидаемый результат (таблица):
#	Type	Subject	Action	Duration	Camera	Notes
1	Establishing	Megacity skyline	Neon signs flicker, rain falls	5s	Pan down	Dark, moody, orange/blue neon contrast
2	Wide	Hunter in alley	Walks toward camera, checks wrist device	4s	Dolly in	Backlit by neon, rain visible
3	Close-up	Hunter's visor HUD	AR interface shows "ROGUE AI DETECTED"	3s	Static	Green HUD glow on face
4	Medium	Hunter draws blaster	Pulls weapon from holster, aims ahead	3s	Static	Side lighting, dramatic
...	...	...	...	...	...	...

РАЗБОР:
Колонка	Зачем нужна	Как использовать позже
Shot type	Определяет композицию	В Блоке #5 (генерация) вставим в промпт: "Wide shot of..."
Subject	Что в кадре	Основа промпта: "Hunter in alley..."
Action	Что происходит	Для motion prompt в Блоке #7 (анимация)
Duration	Хронометраж	Для монтажа в Блоке #9 (знаем длину клипа)
Camera movement	Динамика	Для motion prompt: "Camera pans down..."
Notes	Атмосфера	Освещение/цвет добавим в промпт: "Dark moody lighting..."

ВАРИАЦИИ:

Вариация 1 (упрощённый shot list для новичков):
Code

Create a simple shot list from this screenplay.

[Сценарий]

For each shot:
- Number
- Description (one sentence: who, what, where)
- Shot type

Keep it simple and clear.

Вариация 2 (детализированный для сложных сцен):
Code

Create an ultra-detailed shot list with storyboard descriptions.

[Сценарий]

For each shot include:
- Shot number
- Shot type
- Framing (rule of thirds position, what's in foreground/background)
- Lens simulation (wide-angle / normal / telephoto effect)
- Lighting setup (key light, fill light, rim light positions)
- Color palette (specific hex codes if possible)
- Reference films/shows for composition

This will be used for precise AI image generation.

Шаг 1.4: Организация в таблицу

Действие: Скопировать shot list в Google Sheets или Excel, добавить колонки для трекинга прогресса.

Структура таблицы:
Shot #	Type	Description	Duration	Camera	Style Notes	Status	Image Link	Video Link
1	Establishing	Megacity skyline at night	5s	Pan down	Dark, neon	⬜ Not started		
2	Wide	Hunter in alley	4s	Dolly in	Backlit	⬜ Not started		

Колонки для добавления:

    Status: ⬜ Not started / 🟨 In progress / ✅ Complete
    Image Link: Ссылка на сгенерированное изображение (Блок #5)
    Video Link: Ссылка на анимированный клип (Блок #7)

Инструменты:

✅ Google Sheets

    Ссылка: https://sheets.google.com
    Плюсы: Облачное хранение, доступ с любого устройства, совместная работа
    Минусы: Нужен Google аккаунт
    Как использовать: Файл → Создать → Таблица → Вставить shot list

✅ Notion

    Ссылка: https://notion.so
    Плюсы: Встроенные базы данных, галереи изображений, возможность прикрепить файлы
    Минусы: Более сложный интерфейс для новичков
    Как использовать: Создать Database → Table view → Добавить свойства (Shot #, Type, Status и т.д.)

✅ Airtable

    Ссылка: https://airtable.com
    Free tier: Unlimited bases, 1200 записей/base
    Плюсы: Гибридная база данных/таблица, attachment fields для изображений
    Минусы: Лимит записей в free tier

✅ Excel Online (Microsoft)

    Ссылка: https://www.office.com/launch/excel
    Плюсы: Бесплатно с Microsoft аккаунтом, знакомый интерфейс
    Минусы: Менее удобен для совместной работы vs Google Sheets

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #1
100% БЕСПЛАТНЫЕ AI-СЕРВИСЫ ДЛЯ ТЕКСТА

✅ ChatGPT 3.5 (OpenAI)

    Ссылка: https://chat.openai.com
    Free tier: Unlimited запросы (может быть медленнее в пик)
    Для чего: Генерация истории, сценария, shot list
    Плюсы: Отличное понимание структуры сценариев, может работать с длинными текстами
    Минусы: GPT-4 платный ($20/мес), 3.5 иногда делает клишированные диалоги
    Рекомендация: Основной инструмент для новичков

✅ Claude 3 Haiku (Anthropic, через Claude.ai)

    Ссылка: https://claude.ai
    Free tier: ~40-50 сообщений/день (модель Haiku бесплатна)
    Для чего: Структурирование сложных сценариев, создание shot list
    Плюсы: Отлично работает с таблицами и списками, лучше ChatGPT в деталях
    Минусы: Лимит сообщений в день
    Рекомендация: Используйте для shot list (лучше форматирует таблицы)

✅ Google Gemini 2.0 Flash

    Ссылка: https://gemini.google.com
    Free tier: Unlimited (бесплатная модель Flash)
    Для чего: Генерация историй, альтернатива ChatGPT
    Плюсы: Бесплатный доступ, интеграция с Google Sheets (можно напрямую создать таблицу)
    Минусы: Иногда менее креативен в диалогах vs ChatGPT
    Рекомендация: Для быстрого создания черновиков

✅ Perplexity AI

    Ссылка: https://www.perplexity.ai
    Free tier: Unlimited базовые запросы
    Для чего: Исследование референсов для истории (например, "Как структурирован сценарий Cowboy Bebop эпизода?")
    Плюсы: Даёт ссылки на источники, полезно для изучения стиля
    Минусы: Не специализирован на креативном письме
    Рекомендация: Для research перед написанием сценария

✅ HuggingChat

    Ссылка: https://huggingface.co/chat
    Free tier: Unlimited (open-source модели)
    Для чего: Альтернатива ChatGPT без регистрации
    Плюсы: Не требует аккаунта, несколько моделей на выбор
    Минусы: Качество ниже ChatGPT/Claude
    Рекомендация: Для быстрых экспериментов без регистрации

FREE TIER СЕРВИСЫ

✅ Claude 3.5 Sonnet (через API или Claude.ai Pro trial)

    Ссылка: https://claude.ai
    Free tier: 5$ бесплатных API кредитов при регистрации (хватит на ~100 запросов)
    Для чего: Максимально детальные shot lists
    Плюсы: Лучшая модель Anthropic для структурирования
    Минусы: API требует настройки, trial ограничен
    Рекомендация: Для финального shot list, если базовые модели не дали нужной детализации

✅ Poe (платформа с доступом к нескольким AI)

    Ссылка: https://poe.com
    Free tier: 3000 сообщений/день к бесплатным ботам (GPT-3.5, Claude Haiku)
    Для чего: Доступ к нескольким AI в одном месте
    Плюсы: Можно переключаться между моделями для сравнения
    Минусы: Премиум-модели (GPT-4, Claude Opus) платные
    Рекомендация: Если хотите протестировать разные AI для одного промпта

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #1

    История создана и содержит конфликт, мотивацию персонажей, развязку
    Сценарий разбит на сцены с описанием локаций и действий
    Shot list содержит 20-40 кадров (для 1-2 мин) или 50-80 (для 3-5 мин)
    Каждый кадр в shot list имеет: тип плана, описание, действие, длительность
    Диалоги звучат естественно (не клишированно) — перечитать вслух
    Shot list организован в Google Sheets/Notion с колонками Status, Image Link, Video Link
    Все промпты сохранены в текстовый файл для будущих итераций

Следующий блок: БЛОК #2: Сбор референсов под выбранный стиль
БЛОК #2: СБОР РЕФЕРЕНСОВ ПОД ВЫБРАННЫЙ СТИЛЬ
🎯 Цель блока

Собрать 3-7 высококачественных референсных изображений, которые визуально определяют стиль проекта (выбранный в Блоке #0).
📝 Шаги
Шаг 2.1: Поиск стилевых референсов

Действие: Найти изображения из существующих работ (аниме, фильмы, арты), которые точно соответствуют желаемой эстетике.

Критерии отбора:

    ✅ Чёткое освещение: Видны источники света, тени, контраст
    ✅ Узнаваемый стиль линий: Cel-shading (аниме), мягкие края (Pixar), жёсткие контуры (комикс)
    ✅ Характерная цветовая палитра: Приглушённая (Bebop), яркая (Pixar), неоновая (Cyberpunk)
    ✅ Минимум текста: Избегать изображений с субтитрами, водяными знаками
    ✅ Высокое разрешение: Минимум 1024px по короткой стороне (для качественной загрузки в AI)

Где искать:

Для Cowboy Bebop + Bad Batch стиля:

    Google Images:
        Запрос: "Cowboy Bebop" screenshot 1080p -wallpaper
        Запрос: "Star Wars Clone Wars Bad Batch" character design
        Фильтры: Размер → Большой (Large)

    Pinterest:
        Запрос: Cowboy Bebop aesthetic или Bad Batch art style
        Создать доску "Project Style Refs"

    ArtStation:
        Запрос: Cowboy Bebop fan art или Star Wars Clone Wars
        Фильтр: Sort by Popular

    AnimeShotDB (база скриншотов аниме):
        Ссылка: https://www.sakugabooru.com
        Поиск по тегу: cowboy_bebop

Для Pixar стиля:

    Официальные арты Pixar:
        Google: Pixar concept art [название фильма] (например, "Pixar concept art Incredibles")
        Сайт: https://pixar.com (раздел Art Gallery)

    ArtStation:
        Запрос: Pixar style character design

Для Cyberpunk Anime:

    Google: Akira screenshot 4K, Ghost in the Shell cityscape
    Pinterest: Cyberpunk anime aesthetic
    Behance: Cyberpunk character design

Для Mecha Sci-Fi:

    Google: Gundam mecha design, Evangelion Unit-01
    Gundam Wiki: https://gundam.fandom.com (много официальных артов)

Для Cinematic Realistic:

    Cinematography websites:
        Shotdeck: https://shotdeck.com (кадры из фильмов с описанием камеры/освещения)
        Film-grab: https://film-grab.com (скриншоты из фильмов в высоком качестве)

    Google: Blade Runner 2049 cinematography, Dune 2021 screenshot

Шаг 2.2: Подготовка референсов для AI

Действие: Сохранить отобранные изображения в высоком разрешении, очистить от текста/водяных знаков (если нужно).

Инструкция:

    Сохранение изображений:
        ПКМ → Сохранить изображение как... → выбрать формат PNG или JPG
        Имя файла: ref_style_[номер].png (например, ref_style_01.png)

    Проверка разрешения:
        Открыть файл → Свойства → Детали → Размер
        Если <1024px по короткой стороне → искать версию большего размера

    Удаление водяных знаков (если есть):

100% БЕСПЛАТНЫЕ ИНСТРУМЕНТЫ:

✅ Cleanup.pictures

    Ссылка: https://cleanup.pictures
    Free tier: Unlimited (с водяным знаком на выходе — но его можно обрезать) или ограниченный без знака
    Как использовать:
        Загрузить изображение
        Кистью закрасить водяной знак/текст
        Нажать Remove
        Скачать результат
    Плюсы: AI автоматически заполняет фон
    Минусы: Иногда оставляет артефакты

✅ Magic Eraser (MagicStudio)

    Ссылка: https://magicstudio.com/magiceraser
    Free tier: Unlimited (небольшая реклама)
    Как использовать: Аналогично Cleanup.pictures
    Плюсы: Более быстрая обработка

✅ Photopea (веб-Photoshop)

    Ссылка: https://www.photopea.com
    Free tier: Полностью бесплатно (с рекламой)
    Как использовать:
        Открыть изображение
        Инструмент Clone Stamp (S) или Healing Brush (J)
        Alt+клик на чистом участке рядом с водяным знаком → закрасить знак
    Плюсы: Профессиональный контроль
    Минусы: Требует навыков ретуши

FREE TIER:

✅ Pixelcut Cleanup

    Ссылка: https://pixelcut.ai/cleanup
    Free tier: 5 изображений/день
    Плюсы: Высокое качество AI-удаления

Шаг 2.3: Создание референс-борда

Действие: Собрать все референсы в одном месте для быстрого доступа и загрузки в AI-генераторы.

100% БЕСПЛАТНЫЕ ИНСТРУМЕНТЫ:

✅ PureRef

    Ссылка: https://www.pureref.com
    Free tier: Полностью бесплатно (но можно задонатить разработчикам)
    Платформы: Windows, Mac, Linux
    Как использовать:
        Скачать и установить PureRef
        Запустить → откроется пустой холст
        Перетащить (drag-and-drop) все референсы на холст
        Расположить изображения: можно масштабировать, накладывать друг на друга, группировать
        Сохранить: File → Save → project_style_refs.pur
    Плюсы:
        Сохраняет изображения в исходном качестве (не сжимает)
        Бесконечный холст (можно добавлять сколько угодно референсов)
        Работает оффлайн
        Можно добавлять заметки (ПКМ → Add note)
    Минусы: Desktop-приложение (не веб)
    Рекомендация: Лучший инструмент для работы с референсами в AI-проектах

✅ Figma (Free tier)

    Ссылка: https://figma.com
    Free tier: 3 проекта, unlimited files
    Как использовать:
        Создать аккаунт
        New Design File
        Перетащить референсы на холст
        Добавить фреймы (F) для группировки
        Добавить текстовые аннотации (T)
    Плюсы:
        Веб-платформа (работает в браузере)
        Совместная работа (можно поделиться ссылкой)
        Комментарии
    Минусы: Требует регистрацию, лимит проектов в free tier

✅ Milanote (Free tier)

    Ссылка: https://milanote.com
    Free tier: 100 элементов (изображений/заметок)
    Как использовать:
        Создать board "Style References"
        Drag-and-drop изображения
        Добавить заметки с описанием стиля
    Плюсы: Визуально красивый интерфейс, удобен для мудбордов
    Минусы: Лимит 100 элементов в free tier

✅ Google Drive + Google Slides (100% free)

    Ссылка: https://drive.google.com
    Free tier: 15 GB бесплатно
    Как использовать:
        Создать папку "Project Style Refs"
        Загрузить все изображения
        (Опционально) Создать Google Slides презентацию, вставить изображения на слайды для визуального обзора
    Плюсы: Облачное хранение, доступ с любого устройства
    Минусы: Менее удобен для визуального сравнения vs PureRef

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #2
Источники референсов (100% бесплатные)

✅ Google Images — https://images.google.com
✅ Pinterest — https://pinterest.com (нужна регистрация)
✅ ArtStation — https://www.artstation.com
✅ Behance — https://www.behance.net
✅ Shotdeck (кинематография) — https://shotdeck.com (некоторые кадры бесплатны)
✅ Film-grab (скриншоты из фильмов) — https://film-grab.com
✅ Sakugabooru (аниме-скриншоты) — https://www.sakugabooru.com
✅ Unsplash (для реалистичных стилей) — https://unsplash.com
Инструменты организации (100% бесплатные)

✅ PureRef — https://www.pureref.com (лучший для AI-работы)
✅ Figma — https://figma.com
✅ Milanote — https://milanote.com
✅ Google Drive — https://drive.google.com
Удаление водяных знаков (100% бесплатные)

✅ Cleanup.pictures — https://cleanup.pictures
✅ Magic Eraser — https://magicstudio.com/magiceraser
✅ Photopea — https://www.photopea.com
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #2

    Собрано 3-7 референсных изображений в высоком разрешении (>1024px)
    Референсы отражают выбранный стиль (цвет, линии, освещение, композиция)
    Изображения без водяных знаков и текста (или очищены через Cleanup.pictures)
    Все референсы организованы в PureRef или папке с понятными названиями
    Созданы текстовые заметки к каждому референсу: "Что важно в этом изображении" (цветовая палитра, тип освещения и т.д.)

Следующий блок: БЛОК #3: Создание базового персонажа
БЛОК #3: СОЗДАНИЕ БАЗОВОГО ПЕРСОНАЖА (HERO ASSET)
🎯 Цель блока

Сгенерировать ОДНО идеальное изображение персонажа в высоком разрешении с чёткими отличительными чертами. Это изображение станет основой консистентности для всех последующих сцен.
📝 Шаги
Шаг 3.1: Написание промпта для персонажа

Действие: Создать детальное текстовое описание персонажа с учётом выбранного стиля.

ПРОМПТ-ФОРМУЛА ДЛЯ БАЗОВОГО ПЕРСОНАЖА:
Code

[Тип плана] of [роль персонажа],
[гендер, возраст],
[причёска и цвет волос],
[одежда с деталями],
[аксессуары и экипировка],
[поза],
[выражение лица/эмоция],
[стиль из Блока #0 — полная формула],
[фон],
[технические параметры качества]

ПРИМЕР ПРОМПТА (Cowboy Bebop + Bad Batch стиль):
Code

Full body shot of veteran bounty hunter character,
male, age 45,
short dark hair with grey streaks at temples, 5 o'clock shadow beard,
wearing worn brown leather jacket with orange shoulder patches, dark grey tactical pants, utility belt with pouches, holstered blaster pistol on right hip, scuffed combat boots,
metal wrist device on left arm (holographic display interface),
standing in neutral relaxed pose, hands at sides, weight on one leg,
tired but alert expression, slight frown, eyes scanning surroundings,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic human proportions, muted color palette with browns, dark blues, orange accents,
angular facial features with defined cheekbones and jawline,
clean white background for character reference,
cinematic lighting with soft key light from upper left, subtle rim light on right side,
high quality, 4K, cel-shaded with sharp black outlines,
character design sheet quality

РАЗБОР ПРОМПТА ПО ЧАСТЯМ:
Часть промпта	Функция	Почему критично для консистентности
Full body shot	Тип плана	Нужен полный силуэт (голова до ног) для будущих референсов
veteran bounty hunter	Архетип	Задаёт визуальную концепцию (грубый, практичный, изношенный стиль)
male, age 45	Демография	Определяет пропорции лица, седину, морщины
short dark hair with grey streaks at temples	КЛЮЧЕВАЯ ЧЕРТА #1	Уникальная деталь для узнавания персонажа на всех кадрах
5 o'clock shadow beard	КЛЮЧЕВАЯ ЧЕРТА #2	Дополнительная черта лица
worn brown leather jacket with orange shoulder patches	КЛЮЧЕВАЯ ЧЕРТА #3	Цвет + деталь = визуальная подпись
dark grey tactical pants, utility belt	Дополнительная одежда	Завершает силуэт
holstered blaster pistol on right hip	Аксессуар	Характеризует профессию
metal wrist device on left arm	Уникальный элемент	Tech-деталь (важна для стиля)
standing in neutral relaxed pose	Поза	Простая поза = легче воспроизвести консистентно
tired but alert expression	Эмоция	Задаёт характер (циник, уставший)
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch	СТИЛЕВОЙ ЯКОРЬ	Главное — AI понимает микс двух эстетик
realistic human proportions	Контроль анатомии	Избегаем SD-деформаций (гигантские глаза, крошечные руки)
muted color palette with browns, dark blues, orange	Цветовая схема	Критично — эти цвета должны повторяться на всех кадрах
angular facial features	Стиль лица	Черта Bad Batch (vs мягкие черты Bebop)
clean white background	Фон	Белый фон = персонаж в центре внимания, легко вырезать для композитинга
cinematic lighting with soft key light from upper left	Освещение	Создаёт объём, профессиональный вид
cel-shaded with sharp black outlines	Техника	Anime look (vs реалистичный рендер)
character design sheet quality	Финальный штрих	AI понимает: это не кадр из сцены, а референсный лист

ВАРИАЦИИ ПРОМПТА:

Вариация 1 (для женского персонажа):
Code

Full body shot of skilled mechanic character,
female, age 28,
long black hair tied in practical ponytail, streak of engine grease on left cheek,
wearing dark blue mechanic jumpsuit (unzipped to waist, tied at hips), white tank top underneath, oil-stained work gloves tucked in belt, steel-toed boots,
welding goggles pushed up on forehead, multi-tool on utility belt,
standing with hands on hips, confident stance, weight on both legs,
slight smirk, sharp intelligent eyes,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic human proportions, muted color palette with blues, whites, metallic greys,
angular facial features with high cheekbones,
clean white background for character reference,
cinematic lighting with soft key light from upper right,
high quality, 4K, cel-shaded with sharp black outlines,
character design sheet quality

Вариация 2 (для Pixar стиля):
Code

Full body shot of young inventor character,
male, age 12,
curly orange hair (messy, Einstein-like), large round glasses,
wearing oversized white lab coat with colorful chemical stains, blue t-shirt with science pun, cargo shorts with multiple pockets, sneakers with LED lights,
holding clipboard with blueprints, mechanical pen behind ear,
standing in excited pose, one arm raised pointing upward (eureka moment),
big enthusiastic smile, bright curious eyes,
Pixar animation style, 3D rendered character,
vibrant saturated colors (orange hair, white coat, blue shirt),
soft ambient lighting from above, subtle subsurface scattering on skin,
large expressive eyes (Pixar signature),
rounded friendly proportions,
clean gradient background (light blue to white),
smooth plastic-like shader on clothing,
Disney Pixar quality, 8K render, octane render,
character turnaround sheet quality

Вариация 3 (для Cyberpunk Anime стиля):
Code

Full body shot of elite hacker character,
female, age 24,
short white hair with neon pink underlighting, one side shaved,
wearing black tactical jacket with glowing cyan circuit patterns along seams, dark cargo pants with holographic brand logos, augmented reality visor over right eye (glowing interface), cybernetic left arm (chrome finish with exposed wiring at elbow),
fingerless gloves with embedded LED strips, combat boots with magnetic soles,
standing in casual but alert pose, hand on hip, other hand adjusting visor,
confident smirk, heterochromia (left eye blue natural, right eye glowing pink from augment),
cyberpunk anime style similar to Ghost in the Shell,
realistic human proportions with slight stylization,
color palette: blacks, chromes, neon pinks, cyan blues,
angular facial features with sharp makeup (dark eyeliner),
dark background with subtle neon glow (pink and blue),
dramatic rim lighting from neon sources,
high detail, 4K, anime cel-shading with realistic textures,
character reference sheet quality

Шаг 3.2: Генерация первой версии

Действие: Открыть AI-генератор, загрузить стилевые референсы (если поддерживается), вставить промпт, сгенерировать 4-9 вариантов.

ИНСТРУКЦИЯ ПО ГЕНЕРАЦИИ:

Шаг A: Выбрать инструмент из списка ниже (начать с 100% бесплатных)

Шаг B: Если инструмент поддерживает image reference (загрузку референсов):

    Нажать кнопку "Upload image" / "Add reference"
    Загрузить 1-3 стилевых референса из Блока #2
    Настроить "image strength" / "influence" на 30-50% (чтобы AI брал стиль, но не копировал)

Шаг C: Вставить промпт из Шага 3.1

Шаг D: Настроить параметры:

    Разрешение: 1024x1024 (квадрат) или 1024x1536 (портрет)
    Количество вариантов: 4 (Bing/Leonardo) или 9 (если есть опция сетки 3x3)
    Стиль/модель: Anime (для Bebop/Cyberpunk), General/Universal (для Pixar/Realistic)

Шаг E: Нажать Generate / Create

Шаг F: Дождаться результата (30 сек - 3 мин)

Шаг G: Оценить результаты:

    ✅ Если 1-2 изображения близки к желаемому → перейти к Шагу 3.3 (итерация)
    ❌ Если все 4-9 изображений далеки от концепции → изменить промпт (см. частые проблемы ниже)

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #3
100% БЕСПЛАТНЫЕ AI-ГЕНЕРАТОРЫ ИЗОБРАЖЕНИЙ

✅ Bing Image Creator (DALL-E 3)

    Ссылка: https://www.bing.com/images/create
    Free tier: 15 быстрых генераций/день (потом медленнее, но unlimited)
    Для чего: Универсальная генерация персонажей любого стиля
    Как использовать:
        Перейти по ссылке (нужен Microsoft аккаунт)
        Вставить промпт в поле
        Нажать Create
        Получить 4 варианта
    Плюсы:
        Очень высокое качество (DALL-E 3)
        Хорошо понимает сложные промпты на английском
        Отлично работает с anime/realistic стилями
    Минусы:
        НЕ поддерживает загрузку референсных изображений (только текст)
        Фильтр контента (блокирует NSFW, оружие иногда)
        Лимит 15 быстрых генераций (потом медленная очередь)
    Рекомендация: Начать отсюда для новичков — самый простой интерфейс

✅ Craiyon (бывший DALL-E mini)

    Ссылка: https://www.craiyon.com
    Free tier: Unlimited (медленная генерация, с рекламой)
    Для чего: Черновые наброски персонажей
    Плюсы: Нет лимитов, не нужна регистрация
    Минусы: Очень низкое качество (vs DALL-E 3/SDXL)
    Рекомендация: Только для быстрого тестирования концепции (потом переходить на Bing)

FREE TIER (с регистрацией, есть лимиты)

✅ Leonardo.AI

    Ссылка: https://leonardo.ai
    Free tier: 150 токенов/день (~30-50 изображений при разрешении 1024x1024)
    Для чего: Генерация с использованием специализированных моделей
    Как использовать:
        Создать аккаунт
        AI Image Generation
        Выбрать модель:
            Leonardo Anime XL — для Cowboy Bebop, Cyberpunk Anime стилей
            Leonardo Kino XL — для Cinematic Realistic
            Leonardo Vision XL — универсальная (Pixar работает хорошо)
        (Опционально) Image Guidance → загрузить референс, strength 0.3-0.5
        Вставить промпт
        Настроить: Resolution = 1024x1024, Number of Images = 4
        Generate
    Плюсы:
        Image-to-image поддержка (можно загрузить референс)
        Специализированные модели (anime-модели дают лучшее качество для anime)
        ControlNet (продвинутая функция для контроля поз — см. Консистентность Блок #1)
    Минусы:
        Лимит 150 токенов/день (израсходуется за 30-50 генераций)
        Требует регистрацию
    Рекомендация: Использовать для финального базового персонажа после тестов на Bing

✅ Playground AI

    Ссылка: https://playgroundai.com
    Free tier: 500 генераций/день (модели SDXL)
    Для чего: Эксперименты с разными SD-моделями
    Как использовать:
        Зарегистрироваться
        Create → Image
        Выбрать модель из списка:
            SDXL Base — универсальная
            Anime Diffusion — для anime
            Realistic Vision — для фотореализма
        (Опционально) Image to Image → загрузить референс
        Вставить промпт
        Настроить: Width=1024, Height=1024, Images=4
        Generate
    Плюсы:
        Огромный выбор моделей (можно тестировать разные)
        500 генераций/день = много экспериментов
        Image-to-image
    Минусы:
        Интерфейс сложнее vs Bing/Leonardo
        Качество зависит от модели (нужно экспериментировать)
    Рекомендация: Для продвинутых пользователей, которые хотят контроль над моделью

✅ Tensor.Art

    Ссылка: https://tensor.art
    Free tier: 100 кредитов/день (~20-40 генераций)
    Для чего: Специализация на anime-стилях
    Как использовать:
        Зарегистрироваться
        Create → выбрать модель из библиотеки:
            Искать: "Cowboy Bebop" / "90s anime" / "Cyberpunk anime"
        Загрузить промпт
        (Опционально) Image to Image
        Generate
    Плюсы:
        Огромная библиотека anime-моделей (community-made)
        Можно найти модели, специально обученные на конкретных стилях
        img2img, ControlNet
    Минусы:
        Азиатская платформа (иногда медленная загрузка)
        Лимит 100 кредитов/день
        Интерфейс частично на китайском (но есть английский)
    Рекомендация: Идеален для Cyberpunk Anime, Mecha стилей

✅ SeaArt.AI

    Ссылка: https://www.seaart.ai
    Free tier: 200 кредитов/день
    Для чего: Быстрая генерация anime-персонажей
    Плюсы:
        Простой интерфейс
        Быстрая генерация
        Специализация на anime
    Минусы:
        Китайская платформа (может быть недоступна в некоторых регионах)
        Меньше контроля vs Leonardo
    Рекомендация: Альтернатива Tensor.Art для anime

✅ Ideogram

    Ссылка: https://ideogram.ai
    Free tier: 100 генераций/месяц быстрых, unlimited медленных (очередь)
    Для чего: Реалистичные стили (Cinematic Realistic)
    Плюсы:
        Отлично работает с текстом в изображениях (если нужны надписи на одежде/знаках)
        Высокое качество реализма
    Минусы:
        Лимит 100 быстрых генераций/месяц
        Не специализирован на anime
    Рекомендация: Для Cinematic Realistic стиля

✅ Gemini (Google AI Studio / Gemini App)

    Ссылка: https://aistudio.google.com или https://gemini.google.com
    Free tier: Imagen 3 доступен бесплатно (лимиты варьируются)
    Для чего: Генерация + создание сеток ракурсов (см. Блок #4)
    Как использовать:
        В Gemini App: просто написать промпт после "Generate image:"
        В AI Studio: использовать Imagen 3 model
    Плюсы:
        Интеграция с текстовым Gemini (можно попросить улучшить промпт)
        Может создавать сетки 3x3 (полезно для Блока #4)
    Минусы:
        Качество варьируется (не всегда предсказуемо)
        Экспериментальная функция
    Рекомендация: Для экспериментов с гибридными стилями

СТРАТЕГИЯ ВЫБОРА ИНСТРУМЕНТА

Для новичков (простота > контроль):

    Bing Image Creator — начать здесь (15 быстрых генераций для тестов)
    Если результат хорош → перейти к Leonardo.AI для финального базового персонажа (с загрузкой референсов)

Для практиков (контроль > простота):

    Leonardo.AI — сразу начать здесь (модели + img2img)
    Если нужно больше генераций → добавить Playground AI (500/день)

Для специфических стилей:

    Anime (Bebop, Cyberpunk, Mecha): Leonardo Anime XL → Tensor.Art → SeaArt
    Pixar: Bing Creator → Leonardo Vision XL
    Cinematic Realistic: Ideogram → Leonardo Kino XL

Шаг 3.3: Итерация и уточнение промпта

Действие: Если первая генерация не идеальна — проанализировать результат, уточнить промпт, регенерировать.

ЧАСТЫЕ ПРОБЛЕМЫ И РЕШЕНИЯ:
Проблема	Причина	Решение (как изменить промпт)
Персонаж выглядит generic (без уникальных черт)	Промпт слишком общий	Добавить 3-5 уникальных деталей: "scar over left eye", "asymmetrical hairstyle", "mismatched gloves"
Неправильный стиль (realistic вместо anime)	AI не понял стилевой якорь	Усилить стилевые слова: вместо "anime style" → "cel-shaded anime style with thick black outlines, similar to [конкретное аниме]"
Одежда слишком простая/не та	Недостаточно деталей одежды	Расширить описание: "brown jacket" → "worn brown leather jacket with orange shoulder patches, zipper half-open, frayed cuffs"
Фон не белый (городской/природный)	AI игнорирует "white background"	Усилить: "clean white studio background, no environment, character reference sheet" + добавить в negative prompt: "background details, scenery"
Пропорции неправильные (гигантские глаза/крошечные руки)	SD-модели склонны к деформациям	Добавить: "anatomically correct, realistic human proportions, no deformities" + negative prompt: "distorted, bad anatomy"
Цвета слишком яркие/тусклые	Не указана палитра	Явно указать: "color palette: [перечислить 3-5 цветов], muted tones / vibrant saturated colors"
Персонаж в неправильной позе (сидит/бежит вместо стоя)	AI интерпретировал действие	Чётко указать: "standing in neutral T-pose / standing straight with arms at sides"
Артефакты (лишние руки, размытость)	Случайный шум модели	Регенерировать 4-9 раз, выбрать лучший. Добавить в промпт: "high quality, detailed, sharp focus"

ПРИМЕР ИТЕРАЦИИ:

Промпт v1 (первая попытка):
Code

Full body shot of bounty hunter,
wearing jacket and pants,
anime style,
white background

❌ Результат: Generic персонаж, непонятная одежда, нет уникальных черт

Промпт v2 (после анализа проблем):
Code

Full body shot of veteran male bounty hunter character, age 45,
short dark hair with grey streaks, 5 o'clock shadow,
wearing worn brown leather jacket with orange shoulder patches, dark grey tactical pants, utility belt, holstered blaster pistol,
standing in relaxed neutral pose,
tired but alert expression,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics, realistic proportions, cel-shaded with black outlines,
clean white studio background,
high quality, 4K

✅ Результат: Улучшенная детализация, уникальные черты (седина, оранжевые нашивки)

Промпт v3 (финальная версия с максимальной спецификацией):
Code

[Полный промпт из Шага 3.1 — см. выше]

✅✅ Результат: Идеальный базовый референс персонажа
Шаг 3.4: Сохранение базового референса

Действие: Выбрать ЛУЧШЕЕ изображение из всех сгенерированных, сохранить в максимальном разрешении.

ИНСТРУКЦИЯ:

    Оценить все варианты:
        Открыть все 4-9 сгенерированных изображений
        Сравнить по критериям:
            ✅ Анатомия корректна (нет деформаций)
            ✅ Одежда соответствует описанию
            ✅ Уникальные черты видны (причёска, цвета, аксессуары)
            ✅ Стиль соответствует выбранному (anime/Pixar/realistic)
            ✅ Нет артефактов (размытости, лишних конечностей)
        Выбрать ТОП-1 изображение

    Скачать в максимальном качестве:
        ПКМ → Сохранить изображение как...
        Имя файла: Character_Base_Reference.png
        Формат: PNG (без потери качества)
        Место: Папка проекта (например, Project/References/)

    Проверить разрешение:
        Открыть файл → Свойства → Детали
        Если <1024px по короткой стороне → попробовать скачать через правый клик → "Open image in new tab" → сохранить оттуда
        Минимум: 1024x1024
        Оптимально: 2048x2048 или выше

    Сохранить промпт:
        Скопировать итоговый промпт (v2 или v3)
        Создать текстовый файл Character_Prompts.txt
        Вставить:
        Code

        === BASE CHARACTER PROMPT ===
        Tool used: [Bing / Leonardo / etc.]
        Date: [2026-02-25]

        [ПРОМПТ]

        === NOTES ===
        Key features: grey streaks in hair, orange shoulder patches, blaster on right hip
        Color palette: browns, dark blues, orange
        Style: Cowboy Bebop + Bad Batch

    Добавить в PureRef:
        Открыть PureRef (из Блока #2)
        Перетащить Character_Base_Reference.png на холст
        Добавить рядом текстовую заметку (ПКМ → Add note):
        Code

        BASE CHARACTER REFERENCE
        Use this for ALL scene generations
        Key features:
        - Grey streaks in hair
        - Orange shoulder patches
        - Brown jacket

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #3

    Базовое изображение персонажа создано и сохранено как Character_Base_Reference.png
    Персонаж имеет 3-5 уникальных отличительных черт (цвет волос, детали одежды, аксессуары)
    Изображение в высоком разрешении (минимум 1024x1024, оптимально 2048x2048)
    Промпт персонажа сохранён в Character_Prompts.txt с датой и инструментом
    Анатомия персонажа корректна (нет деформаций, пропорции правильные)
    Стиль соответствует выбранному в Блоке #0 (Bebop/Pixar/Cyberpunk/и т.д.)
    Фон чистый (белый или нейтральный) — персонаж легко вырезать
    Базовый референс добавлен в PureRef с текстовой заметкой

Следующий блок: БЛОК #4: Карта консистентности персонажа

(Из-за ограничений длины ответа, материал будет продолжен в следующем сообщении. Текущий объём: ~30,000 символов)

[⏸ МАТЕРИАЛ ПРОДОЛЖАЕТСЯ — БЛОКИ #4-#9 + КОНСИСТЕНТНОСТЬ-БЛОКИ + ФИНАЛЬНЫЕ СЕКЦИИ В СЛЕДУЮЩЕМ СООБЩЕНИИ]
You said: продолжи
продолжи
Copilot said: ## БЛОК #4: КАРТА КОНСИСТЕНТНОСТИ ПЕРСОНАЖА (9-ПАНЕЛЬНАЯ
БЛОК #4: КАРТА КОНСИСТЕНТНОСТИ ПЕРСОНАЖА (9-ПАНЕЛЬНАЯ СЕТКА)
🎯 Цель блока

Создать 9-панельную сетку (3x3 grid) с базовым персонажем, снятым с 9 разных ракурсов. Эта сетка научит AI "анатомии" персонажа, обеспечивая консистентность на всех будущих кадрах.
📐 Что такое Character Storyboard (сетка ракурсов)

Character Storyboard — техническая сетка изображений, показывающая персонажа с критических углов обзора:
Панель	Ракурс	Зачем нужен
1	Front view (анфас)	Основной вид лица, пропорции
2	3/4 turn (три четверти)	Объём лица, профиль носа
3	Side profile (профиль)	Форма головы сбоку, причёска
4	Back view (вид сзади)	Затылок, одежда сзади
5	High angle (сверху вниз)	Пропорции при взгляде сверху
6	Low angle (снизу вверх)	Пропорции при взгляде снизу
7	Facial close-up (крупный план лица)	Детали лица (глаза, морщины, шрамы)
8	Full body shot (полный рост)	Силуэт, рост, пропорции тела
9	Action pose (экшен-поза)	Персонаж в движении
📝 Шаги
Шаг 4.1: Подготовка промпта для сетки ракурсов

Действие: Создать специализированный промпт, который попросит AI сгенерировать сетку 3x3 с одним персонажем на 9 панелях.

ПРОМПТ-ФОРМУЛА ДЛЯ CHARACTER STORYBOARD:
Code

Create a 3x3 character reference sheet (9 panels in grid layout) showing the same character from different angles.

Character description:
[ВСТАВИТЬ ОПИСАНИЕ ПЕРСОНАЖА ИЗ БЛОКА #3 — внешность, одежда, аксессуары]

Grid layout (9 panels):
1. Front view (face forward, neutral expression)
2. 3/4 turn view (head turned 45 degrees to side)
3. Side profile view (complete side view)
4. Back view (view from behind)
5. High angle view (camera looking down at character)
6. Low angle view (camera looking up at character)
7. Facial close-up (detailed face shot, shoulders visible)
8. Full body shot (head to toe, standing neutral pose)
9. Action pose (character in [specific action related to role])

Each panel shows THE SAME CHARACTER with consistent:
- [Key feature 1 from Блок #3, e.g., "grey streaks in dark hair"]
- [Key feature 2, e.g., "brown leather jacket with orange shoulder patches"]
- [Key feature 3, e.g., "5 o'clock shadow beard"]

[Стиль из Блока #0 — полная формула]

Format: 3x3 grid layout, each panel clearly separated, white background behind character in each panel, labels under each panel (Panel 1: Front View, etc.)

High quality, 4K, character design sheet

ПРИМЕР ПРОМПТА (Cowboy Bebop + Bad Batch стиль):
Code

Create a 3x3 character reference sheet (9 panels in grid layout) showing the same character from different angles.

Character description:
Veteran male bounty hunter, age 45, short dark hair with grey streaks at temples, 5 o'clock shadow beard, wearing worn brown leather jacket with orange shoulder patches, dark grey tactical pants, utility belt with pouches, holstered blaster pistol on right hip, metal wrist device on left arm with holographic display interface, scuffed combat boots.

Grid layout (9 panels):
1. Front view (face forward, neutral tired expression, hands at sides)
2. 3/4 turn view (head turned 45 degrees to right, body facing forward)
3. Side profile view (complete right side view, blaster visible on hip)
4. Back view (view from behind, jacket back visible with wear marks)
5. High angle view (camera looking down at character from 45-degree angle above)
6. Low angle view (camera looking up at character from 45-degree angle below)
7. Facial close-up (detailed face shot from chest up, wrist device visible)
8. Full body shot (head to toe, standing in relaxed neutral pose)
9. Action pose (character drawing blaster from holster, dynamic stance)

Each panel shows THE SAME CHARACTER with consistent:
- Grey streaks in dark hair at temples
- Brown leather jacket with orange shoulder patches
- 5 o'clock shadow beard
- Holstered blaster on right hip
- Metal wrist device on left arm

Anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic human proportions, muted color palette with browns, dark blues, orange accents,
angular facial features with defined cheekbones and jawline,
cel-shaded with sharp black outlines,
cinematic lighting (soft key light from upper left in each panel for consistency),
white background behind character in each panel,
labels under each panel (Panel 1: Front View, Panel 2: 3/4 Turn, etc.),
character turnaround sheet quality,
high quality, 4K

РАЗБОР ПРОМПТА:
Часть	Функция	Критичность для консистентности
3x3 character reference sheet (9 panels in grid layout)	Явно указывает формат	КРИТИЧНО — без этого AI может создать 9 отдельных изображений вместо сетки
showing the same character from different angles	Инструкция консистентности	КРИТИЧНО — ключевое слово "same character"
Character description: [детали из Блока #3]	Визуальная база	Должно быть ТО ЖЕ описание, что в Блоке #3
Grid layout (9 panels): [перечисление]	Точные инструкции для каждой панели	Высокая — AI понимает, что нужно на каждой панели
Each panel shows THE SAME CHARACTER with consistent: [ключевые черты]	Усиление консистентности	КРИТИЧНО — повторение ключевых черт заставляет AI сохранять их
labels under each panel	Читабельность	Средняя — помогает идентифицировать панели при использовании
white background behind character in each panel	Чистота изображения	Высокая — позволяет легко вырезать персонажа для композитинга
character turnaround sheet quality	Профессиональный стандарт	Высокая — AI понимает формат (reference sheet для анимации)

ВАРИАЦИИ ПРОМПТА:

Вариация 1 (для Pixar стиля):
Code

Create a 3x3 character turnaround sheet (9 panels grid) showing the same 3D character from different angles.

Character description:
Young female inventor, age 12, curly orange hair (messy, Einstein-like), large round glasses, wearing oversized white lab coat with colorful chemical stains, blue t-shirt, cargo shorts, LED sneakers, holding clipboard.

Grid layout (9 panels):
1. Front view (smiling, glasses reflecting light)
2. 3/4 turn view (head turned right 45 degrees)
3. Side profile view (clipboard visible under arm)
4. Back view (lab coat back with stain patterns visible)
5. High angle view (looking down, top of curly hair visible)
6. Low angle view (looking up, heroic pose)
7. Facial close-up (big smile, eyes magnified by glasses)
8. Full body shot (standing with one arm raised pointing up)
9. Action pose (jumping excitedly, clipboard flying)

Each panel shows THE SAME CHARACTER with consistent:
- Curly orange hair
- Large round glasses
- White lab coat with specific colorful stains
- Blue t-shirt underneath

Pixar animation style, 3D rendered character,
vibrant saturated colors (orange hair, white coat, blue shirt),
soft ambient lighting from above in each panel,
large expressive eyes (Pixar signature),
rounded friendly proportions,
clean gradient background (light blue to white) in each panel,
smooth plastic-like shader,
labels under each panel,
Disney Pixar character sheet quality,
8K render, octane render

Вариация 2 (для Cyberpunk Anime стиля):
Code

Create a 3x3 cyberpunk character reference sheet (9 panels grid) with the same character from multiple angles.

Character description:
Female elite hacker, age 24, short white hair with neon pink underlighting (one side shaved), wearing black tactical jacket with glowing cyan circuit patterns along seams, dark cargo pants, augmented reality visor over right eye (glowing pink interface), cybernetic left arm (chrome finish with exposed wiring at elbow), fingerless gloves with LED strips.

Grid layout (9 panels):
1. Front view (confident expression, visor glowing)
2. 3/4 turn view (cybernetic arm visible)
3. Side profile view (visor profile, hair asymmetry clear)
4. Back view (circuit patterns on jacket back glowing)
5. High angle view (camera above, neon hair underlighting visible)
6. Low angle view (camera below, dramatic lighting)
7. Facial close-up (heterochromia visible: left eye blue, right covered by visor)
8. Full body shot (standing casual but alert, hand on hip)
9. Action pose (typing on holographic keyboard, cybernetic arm extended)

Each panel shows THE SAME CHARACTER with consistent:
- Short white hair with neon pink underlighting
- Asymmetrical hairstyle (one side shaved)
- Black jacket with cyan glowing circuit patterns
- Cybernetic left arm (chrome)
- AR visor over right eye

Cyberpunk anime style similar to Ghost in the Shell,
realistic human proportions with slight stylization,
color palette: blacks, chromes, neon pinks, cyan blues,
angular facial features,
dark background with subtle neon glow (pink and blue) in each panel,
dramatic rim lighting from neon sources,
labels under each panel,
high detail, 4K, anime cel-shading with realistic textures,
character reference sheet quality

Вариация 3 (упрощённая для новичков):
Code

3x3 grid showing same character from 9 different angles.

Character: [краткое описание из Блока #3]

Angles needed:
- Front, 3/4 turn, side profile
- Back, high angle, low angle
- Face close-up, full body, action pose

Same features in all panels:
- [ключевая черта 1]
- [ключевая черта 2]
- [ключевая черта 3]

[Стиль из Блока #0]

White background, labels, high quality

Шаг 4.2: Генерация мультиракурсной сетки

Действие: Загрузить базовый референс персонажа (из Блока #3) в AI-генератор как image reference, вставить промпт, сгенерировать сетку.

ИНСТРУКЦИЯ ПО ГЕНЕРАЦИИ:

Метод 1: С использованием image-to-image (рекомендуется)

    Открыть AI-генератор с поддержкой img2img:
        Leonardo.AI (Image Guidance)
        Playground AI (Image to Image)
        Tensor.Art (img2img)

    Загрузить базовый референс:
        Нажать "Upload Image" / "Add Reference"
        Выбрать Character_Base_Reference.png из Блока #3
        Настроить Strength/Influence: 0.4-0.6 (средняя сила — берём черты, но позволяем создать разные ракурсы)

    Вставить промпт из Шага 4.1

    Настроить параметры:
        Разрешение: 1024x1024 (для квадратной сетки) или 1536x1024 (для широкой сетки)
        Модель: Anime (для anime-стилей) / General (для Pixar/Realistic)
        Количество генераций: 1 (сразу вся сетка) или 4 (выбрать лучшую)

    Нажать Generate

    Дождаться результата (1-3 минуты)

Метод 2: Без image-to-image (если функция недоступна)

    Открыть AI-генератор:
        Bing Image Creator
        Gemini (Google AI Studio)

    Модифицировать промпт — добавить ВСЕ детали внешности персонажа в текст промпта (поскольку нет загрузки референса, AI опирается только на текст)

    Усилить промпт фразами:
    Code

    IMPORTANT: All 9 panels must show the EXACT SAME CHARACTER.
    Consistent features across all panels:
    - [черта 1]
    - [черта 2]
    - [черта 3]
    DO NOT change character appearance between panels.

    Генерировать несколько раз (3-5 попыток) — без img2img консистентность ниже, нужно выбрать лучший результат

Метод 3: Использование Gemini 2.0 для сеток (экспериментально)

Gemini умеет создавать сетки изображений — можно попробовать специфический подход:

    Открыть: https://aistudio.google.com или https://gemini.google.com

    Загрузить базовый референс (если в Google AI Studio):
        Upload → Character_Base_Reference.png

    Промпт для Gemini:
    Code

    Using this reference image, generate a 3x3 character turnaround sheet showing this character from 9 different angles:

    [Вставить промпт из Шага 4.1]

    Maintain EXACT character features from reference image:
    - Hair color and style
    - Clothing details
    - Facial features
    - Accessories

    Нажать Generate

Плюсы Gemini:

    Иногда лучше понимает задачу "сетка с одним персонажем"
    Бесплатный доступ

Минусы:

    Качество варьируется (экспериментальная функция)
    Не всегда создаёт ровную сетку 3x3

Шаг 4.3: Проверка консистентности сетки

Действие: Визуально проверить сгенерированную сетку — совпадают ли ключевые черты персонажа на всех 9 панелях.

ЧЕК-ЛИСТ ПРОВЕРКИ КОНСИСТЕНТНОСТИ:
Элемент	Что проверять	Критерий успеха
Причёска	Цвет волос, длина, стиль (прямые/кудрявые), уникальные детали (чёлка, проборы, седина)	7+ панелей из 9 имеют идентичную причёску
Лицо	Форма лица, черты (форма носа, глаз, губ), шрамы, морщины, растительность (борода)	7+ панелей имеют узнаваемое лицо
Одежда (цвета)	Основные цвета одежды (куртка коричневая, штаны серые)	8+ панелей имеют правильные цвета
Одежда (детали)	Уникальные элементы (оранжевые нашивки, карманы, молнии, потёртости)	6+ панелей имеют видимые детали (на дальних ракурсах детали могут быть мельче)
Аксессуары	Оружие, гаджеты, украшения (бластер на правом бедре, наручное устройство)	7+ панелей имеют аксессуары на правильных местах
Пропорции тела	Рост, комплекция (худой/мускулистый), длина конечностей	Все 9 панелей имеют одинаковые пропорции (нет деформаций)
Стиль рисовки	Толщина контуров, cel-shading, цветовая гамма	Все 9 панелей в едином стиле

ФОРМУЛА ОЦЕНКИ:
Code

Консистентность = (Количество консистентных панелей) / 9

Если консистентность ≥ 77% (7 из 9 панелей) → Сетка ГОДНА
Если консистентность < 77% → РЕГЕНЕРИРОВАТЬ

КАК ПРОВЕРЯТЬ (пошагово):

    Открыть сгенерированную сетку в полном размере

    Проверить причёску:
        Панель 1 (Front): Тёмные волосы с седыми прядями ✅
        Панель 2 (3/4): Тёмные волосы с седыми прядями ✅
        Панель 3 (Side): Седина видна ✅
        Панель 4 (Back): ...и так далее
        Результат: 8 из 9 панелей ✅ → причёска консистентна

    Проверить одежду (основные цвета):
        Все панели: Куртка коричневая? ✅ / ✅ / ✅ / ❌ (на панели 4 куртка синяя)
        Результат: 8 из 9 ✅ → приемлемо

    Проверить уникальные детали (оранжевые нашивки):
        Панель 1: Нашивки видны ✅
        Панель 2: Нашивки видны ✅
        Панель 4 (Back): Нашивок нет (вид сзади) — это ОК, они на плечах спереди
        Результат: На всех применимых ракурсах есть → консистентно

    Подсчитать общую консистентность:
        Причёска: 8/9
        Лицо: 9/9
        Цвета одежды: 8/9
        Детали одежды: 7/9
        Аксессуары: 7/9
        Пропорции: 9/9
        Средняя: (8+9+8+7+7+9)/6 = 8/9 = 89% консистентность ✅ ГОДНА

ЕСЛИ КОНСИСТЕНТНОСТЬ <77% (менее 7 панелей):

Проблема 1: Разные причёски на панелях

    Решение: Усилить промпт:
    Code

    CRITICAL: Hair must be IDENTICAL in all 9 panels: [точное описание].
    SAME hair color, SAME hairstyle, SAME length in every single panel.

Проблема 2: Разные цвета одежды

    Решение: В промпте явно указать цвета в HEX:
    Code

    Jacket color: #8B4513 (saddle brown), NEVER change this color across panels

Проблема 3: Персонаж выглядит как разные люди на разных панелях

    Решение 1: Увеличить image strength в img2img до 0.7-0.8 (сильнее привязка к референсу)
    Решение 2: Использовать другой инструмент (Leonardo.AI → Playground AI)
    Решение 3: Генерировать по 1-2 панели отдельно, потом склеить в Photopea (см. ниже)

АЛЬТЕРНАТИВНЫЙ МЕТОД: Генерация панелей по отдельности + склейка

Если AI не может создать консистентную сетку за раз, генерировать каждый ракурс отдельно:

Промпт-формула для одной панели:
Code

[Тип ракурса] of [полное описание персонажа из Блока #3],
[стиль],
white background,
character reference sheet panel,
high quality

Примеры для каждой панели:

Панель 1 (Front view):
Code

Front view portrait of veteran male bounty hunter, age 45,
short dark hair with grey streaks at temples, 5 o'clock shadow beard,
wearing worn brown leather jacket with orange shoulder patches,
face forward, neutral tired expression,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch,
white background, character reference sheet panel, high quality

Панель 2 (3/4 turn):
Code

3/4 view portrait of veteran male bounty hunter, age 45,
[...same description...],
head turned 45 degrees to right,
[...same style...],
white background, character reference sheet panel, high quality

Панель 3-9: Аналогично, меняя только тип ракурса.

После генерации всех 9 панелей — склеить в сетку:

Инструмент: Photopea (100% бесплатно)

    Открыть https://www.photopea.com
    Файл → Создать → 3072x3072 px (3 панели × 1024px)
    Перетащить все 9 изображений на холст
    Расположить в сетке 3x3 (используя Move Tool — V)
    Выровнять: Select → All → Layer → Align → Horizontal Centers + Top Edges
    Экспорт → Сохранить как PNG

Шаг 4.4: Сохранение карты консистентности

Действие: Сохранить сетку в высоком разрешении, добавить в PureRef рядом с базовым референсом.

ИНСТРУКЦИЯ:

    Скачать сетку:
        ПКМ → Сохранить изображение как...
        Имя файла: Character_Consistency_Map_3x3.png
        Место: Папка проекта Project/References/

    Проверить разрешение:
        Минимум: 1024x1024 (если сетка квадратная)
        Оптимально: 2048x2048 или выше

    Добавить в PureRef:
        Открыть PureRef (из Блока #2)
        Перетащить Character_Consistency_Map_3x3.png рядом с Character_Base_Reference.png
        Добавить текстовую заметку (ПКМ → Add note):
        Code

        CONSISTENCY MAP (9 angles)
        USE together with Base Reference for ALL scene generations

        Panels:
        1-Front, 2-3/4, 3-Side, 4-Back,
        5-High, 6-Low, 7-Face, 8-Full, 9-Action

        Check: Hair, clothes, accessories MATCH Base Reference

    Сохранить PureRef проект:
        File → Save → Project_References.pur

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #4
100% БЕСПЛАТНЫЕ (для создания сеток без img2img)

✅ Bing Image Creator

    Ссылка: https://www.bing.com/images/create
    Для чего: Генерация сеток text-only (без загрузки референса)
    Плюсы: Высокое качество DALL-E 3, unlimited (медленная очередь после 15 быстрых)
    Минусы: Нет img2img → консистентность ниже

✅ Gemini (Google AI Studio)

    Ссылка: https://aistudio.google.com
    Для чего: Генерация сеток с загрузкой базового референса
    Плюсы: Может загружать референс, бесплатно
    Минусы: Экспериментальная функция, качество варьируется

✅ Photopea (для склейки панелей)

    Ссылка: https://www.photopea.com
    Для чего: Склейка 9 отдельных панелей в сетку 3x3
    Плюсы: Полноценный редактор (аналог Photoshop) в браузере, бесплатно
    Минусы: Нужен интернет

✅ GIMP (для склейки офлайн)

    Ссылка: https://www.gimp.org
    Для чего: Альтернатива Photopea (desktop app)
    Плюсы: Работает офлайн, бесплатно
    Минусы: Нужна установка

FREE TIER (с img2img — рекомендуется)

✅ Leonardo.AI ⭐ (ЛУЧШИЙ для консистентности)

    Ссылка: https://leonardo.ai
    Free tier: 150 токенов/день
    Для чего: Генерация сетки с Image Guidance (загрузка базового референса)
    Как использовать:
        AI Image Generation
        Выбрать модель: Leonardo Anime XL (для anime) / Leonardo Vision XL (для др.)
        Image Guidance → Upload Character_Base_Reference.png
        Strength: 0.5-0.6
        Вставить промпт из Шага 4.1
        Resolution: 1024x1024
        Generate
    Плюсы:
        Image Guidance = высокая консистентность
        Специализированные anime-модели
        Можно генерировать 4 варианта, выбрать лучший
    Минусы: Лимит 150 токенов/день (хватит на 5-10 попыток сетки)
    Рекомендация: НАЧАТЬ ОТСЮДА — лучшее соотношение качества и консистентности

✅ Playground AI

    Ссылка: https://playgroundai.com
    Free tier: 500 генераций/день
    Для чего: Альтернатива Leonardo с img2img
    Как использовать:
        Create → Image
        Image to Image → Upload base reference
        Strength: 0.5
        Выбрать модель: SDXL Base / Anime модель
        Вставить промпт
        Generate
    Плюсы: Много генераций (500/день), img2img
    Минусы: Качество зависит от выбранной модели (нужно экспериментировать)

✅ Tensor.Art

    Ссылка: https://tensor.art
    Free tier: 100 кредитов/день
    Для чего: Anime-специализация с img2img
    Плюсы:
        Огромная библиотека anime-моделей
        img2img
        ControlNet (продвинутый контроль — см. Консистентность Блок #1)
    Минусы: Лимит 100 кредитов, интерфейс сложнее

✅ Fal.ai Flux (экспериментально)

    Ссылка: https://fal.ai/models/flux
    Free tier: Ограниченный (проверить актуальные лимиты)
    Для чего: Flux модели с высокой детализацией
    Плюсы: Очень высокое качество (Flux Pro)
    Минусы: Строгие лимиты в free tier

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #4

    Создана сетка 3x3 с 9 ракурсами персонажа (Front, 3/4, Side, Back, High, Low, Face, Full, Action)
    Консистентность ≥ 77% (минимум 7 из 9 панелей имеют совпадающие ключевые черты)
    Ключевые черты совпадают: причёска, цвета одежды, аксессуары, пропорции
    Сетка сохранена в высоком разрешении (минимум 1024x1024) как Character_Consistency_Map_3x3.png
    Сетка добавлена в PureRef рядом с базовым референсом с текстовой заметкой
    Промпт сетки сохранён в Character_Prompts.txt (для повторной генерации если нужно)

БЛОК #5: ГЕНЕРАЦИЯ ИЗОБРАЖЕНИЙ СЦЕН ПО SHOT LIST
🎯 Цель блока

Создать изображение для каждого кадра из shot list (20-40 кадров для видео 1-2 мин, 50-80 кадров для 3-5 мин), используя базовый референс и карту консистентности.
📝 Шаги
Шаг 5.1: Подготовка промптов для каждого кадра

Действие: Взять shot list из Блока #1, для каждого кадра создать детальный промпт, комбинируя: тип плана + описание сцены + персонаж + стиль.

ПРОМПТ-ФОРМУЛА ДЛЯ СЦЕНЫ:
Code

[Тип плана из shot list] of [персонаж с ключевыми чертами],
[действие персонажа из shot list],
[локация и окружение из shot list],
[стиль из Блока #0],
[освещение и атмосфера],
[технические параметры]

АВТОМАТИЗАЦИЯ через AI (рекомендуется для новичков):

Вместо ручного написания 20-80 промптов, использовать ChatGPT/Claude для генерации:

Промпт для ChatGPT:
Code

I have a shot list for my video. For each shot, create a detailed image generation prompt.

Use this formula:
[Shot type] of [character description],
[action from shot list],
[location and environment],
[style: anime blend of Cowboy Bebop and Bad Batch, cel-shaded, etc.],
[lighting and mood],
high quality, 4K

Character description (use in ALL prompts):
- Male bounty hunter, age 45
- Short dark hair with grey streaks at temples
- 5 o'clock shadow beard
- Brown leather jacket with orange shoulder patches
- Dark grey pants, utility belt, holstered blaster on right hip

Style (use in ALL prompts):
Anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch, realistic proportions, muted color palette (browns, dark blues, orange accents), angular features, cel-shaded with sharp black outlines

Here's my shot list:

[ВСТАВИТЬ SHOT LIST ИЗ БЛОКА #1]

Generate prompts for each shot. Format as:

Shot 1 Prompt:
[промпт]

Shot 2 Prompt:
[промпт]

...

Ожидаемый результат:

ChatGPT/Claude создаст промпты для всех кадров, которые можно скопировать и использовать.

ПРИМЕР (ручное создание промпта для одного кадра):

Исходные данные из shot list (Блок #1):
Shot #	Type	Description	Duration	Camera
2	Wide shot	Hunter in alley	4s	Dolly in

Промпт для Shot #2:
Code

Wide shot of veteran male bounty hunter walking through rain-soaked alley,
character age 45 with short dark hair (grey streaks at temples), 5 o'clock shadow beard,
wearing worn brown leather jacket with orange shoulder patches visible, dark grey tactical pants, utility belt, holstered blaster on right hip,
walking toward camera with determined expression, right hand near blaster holster,
neon-lit cyberpunk alleyway background with flickering signs in Japanese characters, puddles reflecting pink and blue neon lights, wet asphalt,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic human proportions, muted color palette with browns, blues, pinks from neon,
angular facial features, cel-shaded with sharp black outlines,
cinematic backlighting from neon sign behind character creating rim light effect, atmospheric rain, moody night scene,
camera angle: low angle looking slightly up at character (heroic framing),
high quality, 4K, detailed background

РАЗБОР ПРОМПТА:
Часть	Из какого источника	Зачем
Wide shot	Из shot list (Type)	Определяет композицию кадра
veteran male bounty hunter walking	Из shot list (Description) + роль персонажа	Основное действие
age 45, short dark hair with grey streaks...	Из Блока #3 (базовый персонаж)	Консистентность — повторяем ключевые черты
brown leather jacket with orange shoulder patches	Из Блока #3 (ключевая черта #3)	Визуальная подпись персонажа
walking toward camera, hand near holster	Из shot list (Action) + дополнительная деталь	Динамика сцены
neon-lit alleyway, puddles, wet asphalt	Из shot list (Notes: lighting, mood) + расширение	Атмосфера локации
anime style blend of Cowboy Bebop and Bad Batch	Из Блока #0 (стиль проекта)	Стилевая консистентность
cinematic backlighting, rain, moody night	Из shot list (Notes)	Освещение и настроение
camera angle: low angle looking up	Из shot list (Camera) или художественное решение	Кинематографичность

ВАРИАЦИИ ПРОМПТА:

Вариация 1 (для establishing shot — кадр без персонажа):

Данные shot list:
Shot #	Type	Description
1	Establishing	Megacity skyline at night

Промпт:
Code

Wide establishing shot of futuristic megacity skyline at night,
towering skyscrapers with neon signs in Japanese and English characters, flying vehicles with light trails between buildings,
rain falling heavily, storm clouds, distant lightning,
no characters in frame, focus on cityscape,
anime style blend of Cowboy Bebop and Blade Runner aesthetics,
muted color palette with dark blues, oranges, pinks from neon lights,
cinematic composition with atmospheric perspective (distant buildings hazier),
dramatic lighting from neon signs and lightning,
high detail, 4K, establishing shot quality

Вариация 2 (для close-up с эмоцией):

Данные shot list:
Shot #	Type	Description
15	Close-up	Hunter's face, tired expression

Промпт:
Code

Close-up shot of veteran male bounty hunter's face,
age 45, short dark hair with grey streaks at temples, 5 o'clock shadow beard,
tired but alert expression, slight frown, eyes with dark circles underneath, sweat droplet on temple,
wearing collar of brown leather jacket visible at bottom of frame,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic facial proportions, angular features with defined cheekbones and jawline,
cel-shaded with sharp black outlines,
dramatic side lighting from left (neon sign glow), half face in shadow,
shallow depth of field (background out of focus),
high detail on face (skin texture, stubble, wrinkles), 4K

Разбор: Close-up требует больше деталей лица — добавляем "sweat droplet", "dark circles", "skin texture".

Вариация 3 (для action shot — сложная сцена):

Данные shot list:
Shot #	Type	Description
48	Medium	Hunter draws blaster, aims

Промпт:
Code

Medium shot of veteran male bounty hunter in dynamic action pose,
age 45, short dark hair with grey streaks, 5 o'clock shadow,
wearing brown leather jacket with orange shoulder patches (visible on right shoulder), dark grey pants,
drawing blaster pistol from holster on right hip with right hand (motion blur on hand), left arm extended forward for balance, intense focused expression,
industrial warehouse background with metal crates and dim overhead lights, sparks flying from damaged electrical panel,
anime style blend of Cowboy Bebop and Star Wars Clone Wars Bad Batch aesthetics,
realistic proportions, muted colors with orange and blue accents,
angular features, cel-shaded with sharp outlines,
dramatic lighting with strong key light from upper right creating hard shadows, motion lines behind drawing arm (anime speed effect),
camera angle: slightly low angle looking up (heroic), slight dutch angle (15 degrees tilt for dynamism),
high detail, 4K, action scene quality

Разбор: Action shots требуют указания:

    motion blur on hand — AI создаст эффект движения
    motion lines behind arm — anime-эффект скорости
    sparks flying — дополнительная динамика
    dutch angle — наклон камеры для драматизма

Шаг 5.2: Генерация сцен с референсами

Действие: Для каждого кадра: загрузить базовый референс + карту консистентности (если генератор поддерживает multiple images), вставить промпт, сгенерировать 4-9 вариантов, выбрать лучший.

ИНСТРУКЦИЯ ПО ГЕНЕРАЦИИ ОДНОЙ СЦЕНЫ:

Метод 1: С dual-reference (базовый + сетка 3x3) — максимальная консистентность

Поддерживают: Leonardo.AI, Playground AI (частично)

    Открыть Leonardo.AI:
        AI Image Generation

    Выбрать модель:
        Leonardo Anime XL — для anime-стилей (Bebop, Cyberpunk, Mecha)
        Leonardo Vision XL — для Pixar/Universal
        Leonardo Kino XL — для Cinematic Realistic

    Загрузить референсы (2 изображения):
        Image Guidance → Upload:
            Image 1: Character_Base_Reference.png (Strength: 0.5-0.6)
            Image 2: Character_Consistency_Map_3x3.png (Strength: 0.3-0.4)

    Почему 2 изображения:
        Base Reference = общий облик персонажа
        Consistency Map = детали с разных ракурсов (если кадр показывает персонажа сбоку, AI возьмёт панель #3 из сетки)

    Вставить промпт для этого кадра (из Шага 5.1)

    Настроить параметры:
        Resolution:
            Если кадр горизонтальный (wide shot, establishing) → 1344x768 или 1536x896
            Если кадр портретный (close-up стоящего персонажа) → 768x1344
            Если квадратный (medium shot) → 1024x1024
        Number of Images: 4 (чтобы выбрать лучший)
        Guidance Scale: 7-10 (чем выше = точнее следует промпту)

    Generate → дождаться результата (30-90 сек)

    Оценить 4 варианта:
        ✅ Персонаж узнаваем (ключевые черты на месте)
        ✅ Действие соответствует shot list
        ✅ Локация соответствует описанию
        ✅ Нет артефактов (лишние руки, деформации)

    Выбрать лучший вариант → скачать

    Сохранить:
        Имя файла: Shot_[номер]_[краткое описание].png
        Пример: Shot_02_Hunter_Alley.png
        Место: Папка Project/Shots_Raw/

    Добавить ссылку в shot list таблицу:
        Открыть Google Sheets (Блок #1)
        В колонку "Image Link" для Shot #2 вставить путь к файлу или прямую ссылку (если загружено в облако)
        Статус: ⬜ → 🟨 In progress → ✅ Complete

Метод 2: С single-reference (только базовый референс)

Если инструмент не поддерживает 2 изображения или у вас нет сетки:

1-9: Те же шаги, но загружать только Character_Base_Reference.png (Strength: 0.6-0.7 — повысить, чтобы компенсировать отсутствие сетки)

Метод 3: Text-only (без референсов)

Если используете Bing Image Creator (нет img2img):

    Открыть: https://www.bing.com/images/create

    Модифицировать промпт — добавить ВСЕ детали персонажа:
    Code

    [Промпт сцены]

    CRITICAL CHARACTER DETAILS (must be exact):
    - Age 45 male
    - Short dark hair with grey streaks at temples (IMPORTANT)
    - 5 o'clock shadow beard
    - Brown leather jacket with orange shoulder patches (KEY FEATURE)
    - Dark grey tactical pants
    - Holstered blaster on RIGHT hip
    - Worn combat boots

    These features must be IDENTICAL to previous images of this character.

    Generate → получить 4 варианта

    Проблема: Без img2img консистентность ниже — персонаж может выглядеть иначе

    Решение: Генерировать 3-5 раз, выбирать вариант, наиболее близкий к базовому референсу

ОПТИМИЗАЦИЯ ПРОЦЕССА: Генерация пакетами

Вместо генерации 1 кадр → оценка → следующий, генерировать пакетами по 5-10 кадров, потом оценивать все сразу:

День 1:

    Сгенерировать Shots 1-10 (все establishing shots и wide shots без персонажа)
    Использовать один базовый промпт, меняя только локацию

День 2:

    Сгенерировать Shots 11-25 (все кадры с персонажем в полный рост)
    Загрузить референсы 1 раз, генерировать серией

День 3-5:

    Close-ups, action shots (требуют больше итераций)

Шаг 5.3: Создание сеток вариантов (опционально)

Зачем: Для ключевых сцен (кульминация, важные диалоги) полезно создать сетку 3x3 с разными композициями одного кадра, чтобы выбрать лучший ракурс камеры.

Промпт-формула для сетки вариантов сцены:
Code

3x3 grid showing 9 different camera angles of the same scene:

[Описание сцены с персонажем]

Grid layout (9 different compositions of this scene):
1. Wide shot (full environment visible, character small)
2. Medium shot (character from waist up, some environment)
3. Close-up (character face and shoulders only)
4. Over-the-shoulder angle (camera behind character looking at environment)
5. Low angle (camera looking up at character)
6. High angle (camera looking down at character)
7. Dutch angle (camera tilted 30 degrees, dynamic)
8. Extreme close-up (character eyes only)
9. Establishing shot (environment only, character barely visible)

[Стиль]

Same character, same location, same moment — ONLY camera angle changes between panels.

Когда использовать:

    Не уверены, какой ракурс лучше для кульминационной сцены
    Важная диалоговая сцена (тестируете close-up vs medium shot)
    Action-сцена (тестируете dutch angle vs low angle для драматизма)

Ограничение: Генерация сетки = 1 полная генерация (тратите токены), но получаете 9 вариантов вместо 1 → экономия времени на итерации.
Шаг 5.4: Управление файлами

Действие: Организовать все сгенерированные изображения с понятными названиями, обновлять shot list таблицу.

СТРУКТУРА ПАПОК:
Code

Project/
├── References/
│   ├── Character_Base_Reference.png
│   ├── Character_Consistency_Map_3x3.png
│   └── Style_Refs/ (референсы стилей из Блока #2)
├── Shots_Raw/ (сюда сохраняем все сгенерированные изображения)
│   ├── Shot_001_Establishing_City.png
│   ├── Shot_002_Hunter_Alley.png
│   ├── Shot_003_Hunter_Visor_HUD.png
│   └── ...
├── Shots_Final/ (сюда после апскейла в Блоке #6)
├── Videos_Raw/ (после анимации в Блоке #7)
└── Character_Prompts.txt (все промпты)

Правило именования файлов:
Code

Shot_[номер из shot list]_[краткое описание действия].png

Примеры:
Shot_001_Establishing_City.png
Shot_002_Hunter_Alley.png
Shot_015_Hunter_Face_Tired.png
Shot_048_Hunter_Draws_Blaster.png

Обновление shot list таблицы (Google Sheets):
Shot #	Type	Description	Status	Image Link
1	Establishing	City skyline	✅ Complete	Shots_Raw/Shot_001_Establishing_City.png
2	Wide	Hunter in alley	✅ Complete	Shots_Raw/Shot_002_Hunter_Alley.png
3	Close-up	Visor HUD	🟨 In progress	

Если используете облачное хранилище (Google Drive):

    Загрузить все изображения в Google Drive папку Project/Shots_Raw/
    Для каждого изображения: ПКМ → Получить ссылку → Скопировать
    Вставить ссылку в колонку "Image Link" в shot list таблице
    Настроить доступ: "Все, у кого есть ссылка, могут просматривать"

Преимущества:

    Доступ с любого устройства
    Ссылки кликабельны в таблице (быстрый просмотр)
    Автобэкап

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #5
AI-генераторы (те же, что в Блоке #3 и #4)

Рекомендуемая стратегия: Ротация инструментов для экономии лимитов.

✅ Leonardo.AI — ОСНОВНОЙ (150 токенов/день = ~15-30 изображений)

    Использовать для: Кадры с персонажем (требуют консистентности)
    Функция: Image Guidance с dual-reference

✅ Playground AI — ДОПОЛНИТЕЛЬНЫЙ (500 генераций/день)

    Использовать для: Establishing shots, локации без персонажа
    Функция: Высокий лимит генераций

✅ Bing Image Creator — РЕЗЕРВНЫЙ (unlimited медленные)

    Использовать для: Когда исчерпаны Leonardo + Playground
    Ограничение: Нет img2img (консистентность ниже)

✅ Tensor.Art — ДЛЯ ANIME (100 кредитов/день)

    Использовать для: Anime-стили (Bebop, Cyberpunk, Mecha)
    Функция: Специализированные anime-модели

✅ Ideogram — ДЛЯ REALISTIC (100 быстрых/месяц, unlimited медленные)

    Использовать для: Cinematic Realistic стиль
    Функция: Высокое качество реализма

Автоматизация промптов

✅ ChatGPT — https://chat.openai.com (создание промптов для всех кадров сразу)
✅ Claude — https://claude.ai (альтернатива, лучше форматирует таблицы)
Организация файлов

✅ Google Drive — https://drive.google.com (облачное хранилище, 15 GB бесплатно)
✅ Dropbox — https://www.dropbox.com (2 GB бесплатно)
✅ Mega.nz — https://mega.nz (20 GB бесплатно)
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #5

    Промпты созданы для ВСЕХ кадров shot list (20-40 или 50-80)
    Промпты содержат: тип плана + персонаж с ключевыми чертами + действие + локация + стиль
    Сгенерированы изображения для всех кадров shot list
    Персонаж консистентен на всех кадрах (одежда, причёска, лицо совпадают с базовым референсом)
    Каждое изображение соответствует описанию в shot list (правильное действие, локация)
    Изображения организованы в папке Shots_Raw/ с понятными названиями (Shot_XXX_Description.png)
    Shot list таблица обновлена: статусы ✅ Complete, ссылки на файлы добавлены
    Все промпты сохранены в Shot_Prompts.txt (для будущей регенерации при необходимости)

Следующий блок: БЛОК #6: Апскейл и удаление артефактов
БЛОК #6: АПСКЕЙЛ И УДАЛЕНИЕ АРТЕФАКТОВ
🎯 Цель блока

Увеличить разрешение всех изображений до минимум 1920x1080 (Full HD) для качественной анимации и удалить артефакты (текст, деформации, размытость).
📝 Шаги
Шаг 6.1: Отбор изображений для обработки

Действие: Открыть папку Shots_Raw/, просмотреть все изображения, проверить разрешение, отметить изображения с артефактами.

ИНСТРУКЦИЯ:

    Проверить разрешение всех изображений:

    Windows:
        Выделить все файлы в папке Shots_Raw/ → ПКМ → Свойства → Детали → Размеры

    Mac:
        Выделить все файлы → Cmd+I → Размеры

    Критерий:
        ✅ Если изображение ≥ 1920x1080 (или 1080x1920 для вертикальных) → Апскейл не нужен (пропустить)
        ❌ Если <1920x1080 → Нужен апскейл

    Проверить артефакты:

    Открыть каждое изображение, искать:
        Текстовые артефакты: Случайные буквы/цифры (AI иногда генерирует "псевдо-текст" на знаках, одежде)
        Деформации: Лишние пальцы/руки, искажённые лица, анатомические ошибки
        Размытость: Не резкость (мягкий фокус), а явные пятна размытия
        Дубликаты объектов: Два бластера вместо одного, лишние аксессуары

    Критерий:
        ✅ Артефактов нет или они минимальны (в неприметных местах) → OK
        ❌ Артефакты заметны (на лице, руках, оружии) → Нужна очистка

    Создать список для обработки:

    В блокноте или Google Sheets:
    Файл	Разрешение	Нужен апскейл?	Артефакты?	Действия
    Shot_001.png	1024x1024	Да (↑ до 2048)	Нет	Апскейл 2x
    Shot_002.png	768x1344	Да (↑ до 1536x2688)	Текст на знаке	Апскейл 2x + очистка
    Shot_015.png	2048x2048	Нет	Лишний палец	Только очистка

Шаг 6.2: Апскейл изображений до 2K-4K

Действие: Загрузить изображения в AI-апскейлер, выбрать масштаб 2x или 4x, скачать результат.

РЕКОМЕНДУЕМАЯ СТРАТЕГИЯ АПСКЕЙЛА:
Исходное разрешение	Целевое разрешение	Множитель	Инструмент
512x512	2048x2048	4x	Upscayl / ImgUpscaler
768x768	1536x1536	2x	Upscayl / Pixelcut
1024x1024	2048x2048	2x	Upscayl (быстро)
1024x1536	2048x3072	2x	Upscayl

ИНСТРУКЦИЯ ПО АПСКЕЙЛУ:

Метод 1: Upscayl (100% бесплатно, локально, ЛУЧШИЙ)

Upscayl — open-source AI-апскейлер, работает на вашем ПК (не нужен интернет после установки).

    Скачать и установить:
        Ссылка: https://www.upscayl.org
        Платформы: Windows, Mac, Linux
        Скачать последнюю версию (.exe для Windows, .dmg для Mac)
        Установить (процесс стандартный)

    Запустить Upscayl

    Настроить:
        Select Image: Нажать → выбрать изображение из Shots_Raw/ ИЛИ Batch Upscale → выбрать всю папку
        Upscaling Type: Выбрать модель:
            General Photo (Real-ESRGAN) — для реалистичных стилей
            Digital Art — для anime/Pixar стилей ⭐ РЕКОМЕНДУЕТСЯ
            Sharpen — если изображение размыто
        Upscale Factor: 2x (для 1024→2048) или 4x (для 512→2048)
        Output Folder: Выбрать папку Shots_Final/

    Нажать Upscale:
        Процесс займёт:
            С GPU (видеокарта NVIDIA/AMD): 5-15 секунд на изображение
            Без GPU (CPU only): 30-90 секунд на изображение

    Результат:
        Апскейленные изображения сохранены в Shots_Final/ с суффиксом _upscayl_2x.png

Плюсы Upscayl:

    ✅ 100% бесплатно, open-source
    ✅ Работает локально (не нужен интернет, приватность)
    ✅ Batch processing (можно обработать 50-80 изображений за раз)
    ✅ Высокое качество (модель Real-ESRGAN — индустриальный стандарт)

Минусы:

    ❌ Требует установки (но это 1 раз)
    ❌ Без GPU медленнее (но всё равно работает)

Метод 2: Онлайн-апскейлеры (если нет возможности установить Upscayl)

✅ Pixelcut Image Upscaler

    Ссылка: https://www.pixelcut.ai/upscale-image
    Free tier: 5 апскейлов/день без регистрации
    Как использовать:
        Открыть ссылку
        Drag-and-drop изображение или Upload
        Выбрать Upscale Factor: 2x или 4x
        Нажать Upscale
        Скачать результат (Download)
    Плюсы: Быстро (10-20 сек), не требует установки
    Минусы: Лимит 5/день (для 20-40 кадров нужно несколько дней)

✅ ImgUpscaler

    Ссылка: https://imgupscaler.com
    Free tier: 3 изображения/день без регистрации
    Как использовать: Аналогично Pixelcut
    Плюсы: Хорошее качество
    Минусы: Лимит 3/день

✅ Upscale.media

    Ссылка: https://www.upscale.media
    Free tier: 3 изображения/неделю
    Плюсы: Очень высокое качество (AI модели)
    Минусы: Строгий лимит (только для ключевых кадров)

✅ Deep-Image.ai

    Ссылка: https://deep-image.ai
    Free tier: 5 кредитов (= 5 апскейлов) при регистрации
    Плюсы: Профессиональное качество
    Минусы: Требует регистрацию, лимит

СТРАТЕГИЯ ИСПОЛЬЗОВАНИЯ ЛИМИТОВ:

Если 20-40 кадров:

    День 1: Upscayl (установить) → обработать все за 1 сессию (batch)
    ИЛИ День 1-4: Pixelcut (5/день) × 4 дня = 20 кадров
    ИЛИ День 1-8: ImgUpscaler (3/день) × 8 дней = 24 кадра

Если 50-80 кадров:

    Рекомендуется: Upscayl (единственный realistic вариант для такого объёма бесплатно)
    Альтернатива: Комбинация:
        Ключевые кадры (close-ups, action) → Upscale.media / Deep-Image (высокое качество)
        Остальные → Upscayl batch

Шаг 6.3: Удаление артефактов

Действие: Для изображений с артефактами (текст, деформации) использовать AI-инструмент удаления объектов или ручную ретушь.

ТИПЫ АРТЕФАКТОВ И МЕТОДЫ УДАЛЕНИЯ:
Артефакт	Пример	Метод удаления	Инструмент
Текстовые символы	Случайные буквы на знаке/одежде	AI-удаление кистью	Cleanup.pictures / Magic Eraser
Лишние конечности	6 пальцев, 3 руки	AI-удаление + inpainting	Cleanup.pictures + Photopea
Деформации лица	Кривой нос, несимметричные глаза	Регенерация кадра (проще, чем чинить)	Вернуться к Блоку #5, регенерировать
Размытость локальная	Размытое лицо при чёткой одежде	Sharpen filter	Photopea / GIMP
Дубликаты объектов	Два бластера вместо одного	AI-удаление	Cleanup.pictures

ИНСТРУКЦИЯ ПО УДАЛЕНИЮ АРТЕФАКТОВ:

Метод 1: AI-удаление (100% бесплатно)

✅ Cleanup.pictures — ЛУЧШИЙ

    Открыть: https://cleanup.pictures

    Загрузить изображение:
        Drag-and-drop файл из Shots_Raw/ или Shots_Final/ (если уже апскейлили)
        ИЛИ Click to upload

    Выделить артефакт:
        Инструмент Brush (кисть) в левом меню
        Настроить размер кисти (Brush Size)
        Закрасить артефакт (например, случайный текст на знаке)
        Кисть будет выделять красным

    Удалить:
        Нажать Erase (или Remove)
        AI автоматически заполнит область, удалив артефакт
        Процесс: 5-15 секунд

    Проверить результат:
        Если артефакт удалён хорошо → OK
        Если остались следы → повторить шаги 3-4 (закрасить остатки, erase снова)

    Скачать:
        Download → сохранить в Shots_Final/ с именем Shot_XXX_Clean.png

Плюсы:

    ✅ Unlimited (бесплатно, но с водяным знаком — можно обрезать в Photopea)
    ✅ Высокое качество AI-заполнения
    ✅ Простой интерфейс

Минусы:

    ❌ Водяной знак (но в углу, легко обрезать)
    ❌ Иногда оставляет артефакты при сложных текстурах

✅ Magic Eraser (MagicStudio)

    Ссылка: https://magicstudio.com/magiceraser
    Free tier: Unlimited (небольшая реклама)
    Как использовать: Аналогично Cleanup.pictures (upload → brush → erase)
    Плюсы: Нет водяного знака, быстрая обработка
    Минусы: Качество чуть ниже Cleanup.pictures

Метод 2: Ручная ретушь (для сложных случаев)

Если AI-удаление не справилось (остались следы артефакта):

✅ Photopea (веб-редактор, аналог Photoshop)

    Открыть: https://www.photopea.com

    Открыть изображение:
        File → Open → выбрать файл

    Инструмент Clone Stamp (S):
        Выбрать инструмент Clone Stamp в левом меню
        Alt + Click на чистом участке рядом с артефактом (выбираете источник клонирования)
        Click на артефакте (закрашиваете его, копируя чистую текстуру)
        Повторять до полного удаления

    Инструмент Healing Brush (J):
        Альтернатива Clone Stamp (автоматически смешивает текстуры)
        Закрасить артефакт кистью
        Photopea автоматически сгладит

    Сохранить:
        File → Export as → PNG → Download

Плюсы:

    ✅ Профессиональный контроль
    ✅ Работает в браузере (не требует установки)

Минусы:

    ❌ Требует навыков ретуши (но базовый уровень легко освоить за 10 минут)
    ❌ Занимает больше времени vs AI-удаление

КОГДА ПРОЩЕ РЕГЕНЕРИРОВАТЬ, ЧЕМ ЧИНИТЬ:

Регенерировать (вернуться к Блоку #5), если:

    ❌ Лицо персонажа деформировано (кривые глаза, нос)
    ❌ Критические анатомические ошибки (6 пальцев на крупном плане руки)
    ❌ Персонаж не узнаваем (волосы другого цвета, нет ключевых черт)

Чинить артефакты, если:

    ✅ Лицо/анатомия OK, но есть мелкие дефекты (текст, лишний объект в фоне)
    ✅ Артефакт в неприметном месте (угол кадра, размытый фон)
    ✅ Регенерация заняла бы больше времени (уже потрачено 5 попыток, текущий вариант лучший)

Шаг 6.4: Сохранение финальных изображений

Действие: Все обработанные (апскейленные + очищенные) изображения сохранить в папку Shots_Final/ с теми же названиями.

СТРУКТУРА:
Code

Shots_Raw/ (оригиналы, не трогать)
├── Shot_001_City.png (1024x1024)
├── Shot_002_Hunter_Alley.png (768x1344)
└── ...

Shots_Final/ (обработанные)
├── Shot_001_City.png (2048x2048, апскейл 2x)
├── Shot_002_Hunter_Alley.png (1536x2688, апскейл 2x + очистка)
└── ...

ПРАВИЛО: Имена файлов в Shots_Final/ должны совпадать с Shots_Raw/ (без суффиксов _upscayl, _clean) для упрощения навигации.

Если Upscayl добавил суффикс _upscayl_2x.png:

    Переименовать вручную или через batch rename (Windows: выделить все → F2 → find/replace)

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #6
AI-апскейлеры (100% бесплатные)

✅ Upscayl ⭐ — https://www.upscayl.org (ЛУЧШИЙ, локальный, unlimited)
✅ Pixelcut — https://www.pixelcut.ai/upscale-image (5/день)
✅ ImgUpscaler — https://imgupscaler.com (3/день)
✅ Upscale.media — https://www.upscale.media (3/неделю, высокое качество)
AI-удаление артефактов (100% бесплатные)

✅ Cleanup.pictures ⭐ — https://cleanup.pictures (unlimited с водяным знаком)
✅ Magic Eraser — https://magicstudio.com/magiceraser (unlimited, без знака)
Ручная ретушь (100% бесплатные)

✅ Photopea — https://www.photopea.com (веб-редактор, аналог Photoshop)
✅ GIMP — https://www.gimp.org (desktop app, open-source)
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #6

    Все изображения проверены на разрешение (<1920x1080 = нужен апскейл)
    Все изображения апскейлены до минимум 1920x1080 (оптимально 2048+)
    Текстовые артефакты удалены (случайные буквы, символы)
    Явные деформации удалены или кадры регенерированы
    Изображения сохранены в папку Shots_Final/ с теми же названиями, что в Shots_Raw/
    Качество изображений проверено (нет размытия, блоков, артефактов)
    Shot list таблица обновлена: статусы кадров = ✅ Complete после обработки

(Из-за ограничений длины, материал будет продолжен в следующем сообщении. Текущий объём: ~50,000 символов. Остаются: Блоки #7-9 + 4 Консистентность-блока + Финальные секции)

[⏸ МАТЕРИАЛ ПРОДОЛЖАЕТСЯ — БЛОКИ #7-9 + КОНСИСТЕНТНОСТЬ-БЛОКИ + ФИНАЛЬНЫЕ СЕКЦИИ В СЛЕДУЮЩЕМ СООБЩЕНИИ]
You said: продолжи
продолжи
Copilot said: ## БЛОК #7: АНИМАЦИЯ (IMAGE-TO-VIDEO) ### 🎯 Цель
БЛОК #7: АНИМАЦИЯ (IMAGE-TO-VIDEO)
🎯 Цель блока

Превратить статичные изображения из Shots_Final/ в 3-10-секундные видеоклипы с движением камеры и/или персонажей.
📝 Шаги
Шаг 7.1: Подготовка motion prompts (промптов движения)

Действие: Для каждого кадра написать motion prompt — описание того, что должно двигаться в видео и как движется камера.

ПРОМПТ-ФОРМУЛА ДЛЯ MOTION PROMPT:
Code

[Что движется: камера/персонаж/объекты],
[Тип движения: медленно/быстро/плавно],
[Направление движения],
[Дополнительные эффекты: частицы, свет],
[Что остаётся статичным]

ТИПЫ ДВИЖЕНИЯ ПО КАТЕГОРИЯМ КАДРОВ:
Тип кадра	Рекомендуемое движение	Motion prompt пример
Establishing shot (пейзаж без персонажа)	Медленное движение камеры	Slow camera pan from left to right, no character movement, atmospheric particles drifting
Static scene (персонаж стоит)	Минимальное движение (дыхание, волосы)	Character remains still, slight breathing motion, wind gently moves hair and jacket, camera static
Walking scene	Персонаж идёт + камера следует	Character walks forward toward camera, steady pace, camera slowly dollies back, background parallax
Action scene (драка, бег)	Быстрое движение + эффекты	Character draws weapon with quick motion, camera zooms in slightly, motion blur on arm, sparks in background
Close-up face	Микродвижения лица + свет	Slow camera push in on face, character eyes move left to right scanning, subtle facial muscle tension, flickering neon light on face
Vehicle/object motion	Объект движется, камера статична или следует	Spaceship flies past camera from left to right, engine glow trails, camera remains static, stars in background slowly drift

АВТОМАТИЗАЦИЯ: Генерация motion prompts через ChatGPT

Промпт для ChatGPT:
Code

I have a shot list with 40 scenes. For each scene, create a motion prompt for AI video generation (image-to-video).

Motion prompt should describe:
1. What moves (camera / character / objects)
2. Speed (slow / medium / fast)
3. Direction (left to right / forward / zoom in / pan)
4. Additional effects (wind, particles, lighting changes)
5. What stays static

Use this formula:
[Movement subject], [speed], [direction], [effects], [static elements]

Here's my shot list with scene descriptions:

[ВСТАВИТЬ SHOT LIST ИЗ БЛОКА #1 — колонки: Shot #, Type, Description, Action]

Generate motion prompts for each shot. Format:

Shot 1 Motion Prompt:
[промпт]

Shot 2 Motion Prompt:
[промпт]
...

Ожидаемый результат:

ChatGPT создаст motion prompts для всех кадров, адаптированные под тип сцены.

ПРИМЕРЫ MOTION PROMPTS ДЛЯ РАЗНЫХ СЦЕН:

Пример 1: Establishing shot (город ночью)

Исходный кадр из shot list:
Shot #	Type	Description
1	Establishing	Megacity skyline at night, rain, neon signs

Motion Prompt:
Code

Slow camera pan from left to right across cityscape,
rain falling steadily with visible droplets,
neon signs flickering and glowing,
no character movement,
atmospheric fog drifting in foreground,
camera movement speed: very slow (5-second pan across frame),
buildings remain static, only lights and rain animate

РАЗБОР:
Элемент	Функция	Почему важно
Slow camera pan from left to right	Тип движения камеры	Establishing shots традиционно используют pan для показа масштаба
rain falling steadily with visible droplets	Эффект окружения	Добавляет атмосферу, AI анимирует дождь
neon signs flickering	Детализация движения	Конкретизирует, что мигают именно знаки (не весь кадр)
no character movement	Явное указание статики	Предотвращает галлюцинации AI (иногда AI "видит" персонажей где их нет)
camera movement speed: very slow	Контроль скорости	Чем медленнее = более кинематографично

Вариация (для более динамичного establishing):
Code

Camera starts with slow zoom out from single neon sign,
reveals full cityscape as camera pulls back,
rain intensifies (more droplets visible) as camera moves,
lightning flashes in distance at 2-second mark,
flying vehicles pass in mid-ground with light trails

Пример 2: Static scene (персонаж стоит в переулке)

Исходный кадр:
Shot #	Type	Description	Action
2	Wide shot	Hunter in alley	Walks toward camera

Motion Prompt:
Code

Character walks forward toward camera at steady pace,
slight sway in shoulders (natural walking motion),
right hand near holster (subtle movement, fingers flex),
camera slowly dollies backward maintaining distance,
puddles on ground reflect neon lights (reflections shimmer as character steps near),
wind blows jacket slightly at 3-second mark,
background remains static (buildings, signs),
camera movement speed: medium (matches character walking speed)

РАЗБОР:
Элемент	Функция
walks forward toward camera at steady pace	Основное действие — AI фокусируется на походке
slight sway in shoulders	Детализация походки — добавляет реализм (vs роботоподобная ходьба)
right hand near holster, fingers flex	Микродвижение — показывает напряжение персонажа
camera slowly dollies backward	Классический кинематографичный приём (камера отступает, персонаж идёт — эффект преследования)
puddles reflect neon, reflections shimmer	Детализация окружения — AI будет анимировать отражения
wind blows jacket at 3-second mark	Timing-эффект — добавляет динамику в конкретный момент

Вариация (более драматичная):
Code

Character walks forward slowly, each step deliberate,
camera low angle looking up (heroic framing),
rain falls around character, droplets hit shoulders,
character pauses at 4-second mark, hand grips blaster handle,
camera zooms in slightly on face during pause,
neon sign flickers out behind character as they pass

Пример 3: Close-up face (эмоциональная сцена)

Исходный кадр:
Shot #	Type	Description
15	Close-up	Hunter's face, tired expression

Motion Prompt:
Code

Slow camera push in on character's face (starts medium close-up, ends extreme close-up),
character's eyes move slowly from right to left (scanning surroundings),
slight frown deepens at 2-second mark,
breathing visible (chest rises and falls subtly in bottom of frame),
sweat droplet rolls down left temple,
neon light flickers on right side of face (cyan to pink),
camera movement speed: very slow (creates tension),
background out of focus, bokeh lights gently shimmer

РАЗБОР:

Close-up требует микродвижений лица — AI часто делает лица слишком статичными или наоборот, гипер-анимированными. Промпт должен указать конкретные мышцы/элементы лица.
Элемент	Функция
eyes move slowly from right to left	Конкретное движение глаз — AI знает куда направить взгляд
slight frown deepens	Микроэмоция — постепенное изменение выражения
breathing visible, chest rises	Показывает что персонаж живой (не застывший)
sweat droplet rolls	Детализация — добавляет напряжение
neon light flickers on face	Динамическое освещение — меняет атмосферу
slow camera push in	Создаёт напряжение (классический thriller приём)

Пример 4: Action scene (персонаж выхватывает оружие)

Исходный кадр:
Shot #	Type	Description	Action
48	Medium shot	Hunter in warehouse	Draws blaster, aims forward

Motion Prompt:
Code

Character draws blaster from holster with fast motion (0.5-second draw),
motion blur on right arm during draw,
anime-style speed lines appear behind arm,
left arm extends forward for balance (slower motion),
character's coat flares outward from movement,
camera slight dutch angle (tilts 15 degrees clockwise) for dynamism,
sparks fly from damaged electrical panel in background at 2-second mark,
camera zooms in 10% during blaster draw,
after draw: character holds aim steady, breathing heavily,
camera stabilizes, only character's hand micro-adjusts aim

РАЗБОР:

Action scenes требуют комбинации быстрых и медленных элементов для драматизма.
Элемент	Функция
fast motion (0.5-second draw)	Чёткий timing — AI знает длительность действия
motion blur on arm	Эффект скорости — делает движение правдоподобным
anime-style speed lines	Стилистический эффект (если стиль аниме)
coat flares outward	Вторичное движение (secondary animation) — реалистичная физика
dutch angle tilt 15 degrees	Кинематографический приём — добавляет напряжение
sparks fly at 2-second mark	Фоновая динамика — отвлекает внимание на долю секунды, потом фокус возвращается на персонажа
camera zooms in 10%	Усиливает фокус на действии
after draw: holds steady	Контраст — после быстрого движения статика создаёт паузу

Вариация (замедленная съёмка эффект):
Code

Character draws blaster in slow motion (2-second draw stretched),
every detail visible: fingers gripping handle, hammer cocking, barrel clearing holster,
camera orbits character 45 degrees (from right to center) during draw,
background blurs (speed ramping effect),
brass shell ejects from blaster in slow-mo, spins in air,
time resumes normal speed at 4-second mark as character finishes aiming

Пример 5: Vehicle/object motion (космический корабль)

Исходный кадр:
Shot #	Type	Description
22	Wide shot	Spaceship flying past camera

Motion Prompt:
Code

Spaceship enters frame from left at high speed,
flies past camera (left to right trajectory),
engines glowing bright blue with particle trail,
camera remains static (locked position),
spaceship exits frame right at 3-second mark,
background stars slowly drift right-to-left (parallax effect),
lens flare from engine glow at 2-second mark when ship is closest,
sound design note: doppler effect (pitch change as ship passes)

РАЗБОР:
Элемент	Функция
enters frame from left at high speed	Чёткая траектория — AI понимает путь объекта
camera remains static	Контраст — объект движется быстро, камера неподвижна (эффект пролёта)
particle trail	Детализация движения — показывает направление и скорость
stars drift right-to-left (parallax)	Эффект глубины — дальние объекты движутся медленнее
lens flare at 2-second mark	Timing-эффект — добавляет кинематографичность
Шаг 7.2: Генерация видео через AI image-to-video сервисы

Действие: Для каждого кадра: загрузить финальное изображение из Shots_Final/, вставить motion prompt, выбрать длительность, сгенерировать видео.

ИНСТРУКЦИЯ ПО ГЕНЕРАЦИИ ВИДЕО (универсальная для всех сервисов):

Шаг A: Выбрать инструмент

(см. таблицу сервисов ниже — начать с того, у кого больше бесплатных кредитов)

Шаг B: Загрузить изображение

    Открыть выбранный сервис (например, Kling AI)
    Найти кнопку "Image to Video" / "Animate Image"
    Нажать Upload → выбрать файл из Shots_Final/ (например, Shot_002_Hunter_Alley.png)
    Дождаться загрузки (5-15 сек)

Шаг C: Вставить motion prompt

    Найти поле "Prompt" / "Describe motion"
    Вставить motion prompt для этого кадра (из Шага 7.1)
    Оптимизация промпта для конкретного сервиса:

Сервис	Особенности промптов	Пример адаптации
Kling AI	Понимает сложные промпты, любит детали	Использовать полный промпт без сокращений
Luma Dream Machine	Предпочитает краткие промпты (1-2 предложения)	Сократить до: "Character walks toward camera, wind blows jacket, slow dolly back"
Pika Labs	Хорошо работает с camera movement keywords	Усилить camera keywords: "Camera: slow dolly backward. Subject: character walks forward."
Runway Gen-3	Понимает кинематографические термины	Можно использовать: "Dutch angle", "whip pan", "rack focus"
Pixverse	Anime-специализация, понимает anime-эффекты	Добавить: "anime motion lines", "cel-shaded animation"

Шаг D: Настроить параметры

    Duration (длительность):
        Для Establishing shots: 5-10 сек (долгие планы)
        Для Action shots: 3-5 сек (быстрые движения)
        Для Close-ups: 4-6 сек (средние планы)
        Для Dialogue: Зависит от длины реплики (см. Блок #8)

    Quality/Mode:
        Standard/Fast — для тестов (быстрая генерация, ниже качество)
        High/Pro — для финальных кадров (медленнее, выше качество)
        В free tier обычно доступен только Standard

    Camera movement intensity (если есть слайдер):
        Low (0.3-0.5) — для тонких движений (дыхание, ветер)
        Medium (0.5-0.7) — для нормальной ходьбы, camera pans
        High (0.7-1.0) — для быстрых действий (бег, драка)

Шаг E: Генерировать

    Нажать Generate / Create / Animate
    Дождаться генерации:
        Быстрая очередь (paid/credits): 1-3 минуты
        Медленная очередь (free tier): 5-15 минут
    Если сервис генерирует несколько вариантов (например, Pika даёт 2-4) → просмотреть все, выбрать лучший

Шаг F: Оценить результат

Критерии качества видео:

    ✅ Персонаж узнаваем (лицо, одежда соответствуют базовому референсу)
    ✅ Движение плавное (нет "слоу-моушен супа" или рывков)
    ✅ Действие соответствует motion prompt (если промпт "идёт вперёд" — персонаж действительно идёт, а не стоит)
    ✅ Нет артефактов:
        ❌ Морфинг лица (лицо "плавится")
        ❌ Лишние конечности (появляются/исчезают руки)
        ❌ Фон "дышит" (здания деформируются)
        ❌ Одежда меняет цвет/паттерн
    ✅ Камера движется так, как указано (если промпт "pan left" — камера действительно панорамирует влево)

Если результат хороший (6+ критериев ✅):

    Скачать видео
    Перейти к Шагу G

Если результат плохой (<6 критериев):

    Регенерировать (попробовать 2-3 раза)
    Если после 3 попыток результат не улучшается → изменить стратегию:

Проблема	Решение
Персонаж морфит	Упростить motion prompt (меньше движений), попробовать другой сервис
Движение не соответствует промпту	Переписать промпт более просто ("walk forward" вместо "walk with deliberate steps")
Фон "дышит"	Добавить в промпт: "background remains static"
Одежда меняется	Проблема изображения (вернуться к Блоку #5, регенерировать изображение с более чётким описанием одежды)

Шаг G: Скачать и сохранить

    Нажать Download / Save
    Формат: обычно MP4 (H.264 codec)
    Разрешение: зависит от сервиса (720p - 1080p в free tier)
    Имя файла: Video_[номер кадра]_[описание].mp4
        Пример: Video_002_Hunter_Alley_Walk.mp4
    Место: Папка Project/Videos_Raw/

Шаг H: Обновить shot list таблицу

    Открыть Google Sheets (из Блока #1)
    Найти строку Shot #2
    Колонка "Video Link": вставить путь к файлу Videos_Raw/Video_002_Hunter_Alley_Walk.mp4
    Колонка "Status": ✅ Complete

Шаг 7.3: Стратегия для сложных сцен (микро-шаги)

Проблема: AI video генераторы (по состоянию на 2026 год) не могут создавать сложные последовательности действий в одном видео.

Пример того, что НЕ работает:

❌ Плохой промпт:
Code

Character runs forward, jumps over obstacle, draws sword mid-air, lands and strikes enemy

Результат: AI создаст "суп" — размытое видео где персонаж морфит между действиями, движения нечёткие.

Решение: Разбить сложную сцену на микро-шаги

Формула:
Code

1 сложное действие = 3-5 простых действий = 3-5 отдельных видео → склеить в монтаже

ПРИМЕР ДЕКОМПОЗИЦИИ: Сцена боя мечом

Исходная задача из shot list:
Shot #	Type	Description
55	Action sequence	Character fights enemy with sword: draws sword, parries attack, counterattacks

Разбивка на микро-шаги:

Микро-шаг 1: Выхватывание меча

Изображение 1 (создать в Блоке #5):
Code

Medium shot of character, hand reaching for sword hilt on back, tense expression

Motion prompt 1:
Code

Character draws sword from back sheath with fast upward motion (1 second),
motion blur on sword blade,
anime speed lines behind sword,
camera static

Длительность видео: 2-3 секунды
Файл: Video_055a_Sword_Draw.mp4

Микро-шаг 2: Удар врага (которого персонаж блокирует)

Изображение 2:
Code

Close-up of two swords clashing, sparks flying, character's sword blocking enemy blade (enemy blade entering from top-right)

Motion prompt 2:
Code

Enemy sword swings down from top-right,
character's sword moves up to block,
swords clash at 0.5-second mark with bright sparks,
camera slight shake on impact (impact frame),
after clash: both swords tremble from force

Длительность: 2 секунды
Файл: Video_055b_Sword_Clash.mp4

Микро-шаг 3: Контратака персонажа

Изображение 3:
Code

Wide shot of character in mid-swing, sword arcing toward right side of frame, dynamic pose

Motion prompt 3:
Code

Character swings sword in horizontal arc from left to right,
fast motion with motion blur on blade,
body rotates with swing (follow-through),
camera pans slightly right following sword trajectory,
sword exits frame right at 1.5-second mark

Длительность: 2-3 секунды
Файл: Video_055c_Counter_Swing.mp4

Микро-шаг 4: Результат удара (враг отступает)

Изображение 4:
Code

Medium shot of enemy staggering backward, holding wounded shoulder, expression of pain

Motion prompt 4:
Code

Enemy stumbles backward (away from camera),
hand clutches left shoulder,
face grimaces in pain,
camera slowly zooms in on face,
enemy falls to one knee at 2-second mark

Длительность: 3 секунды
Файл: Video_055d_Enemy_Hit.mp4

Итого для сложной сцены боя:

    4 отдельных изображения (созданы в Блоке #5)
    4 отдельных видео (анимированы в Блоке #7)
    Общая длительность после монтажа: 9-11 секунд (с обрезкой лишних кадров)
    Склейка: В Блоке #9 (монтаж) эти 4 клипа будут объединены с переходами (cuts) + добавлены sound effects (звук мечей)

ПОЧЕМУ ЭТО РАБОТАЕТ:
Проблема AI	Решение через микро-шаги
AI не может анимировать последовательность 3+ действий	Каждое видео = 1 действие
AI путается в сложных движениях	Каждое движение простое (draw / clash / swing / stagger)
AI теряет консистентность персонажа в длинных видео	Короткие видео (2-3 сек) = меньше времени на ошибки
AI создаёт "суп" при сложных промптах	Простые промпты = чёткие инструкции

ДРУГИЕ ПРИМЕРЫ СЦЕН, ТРЕБУЮЩИХ МИКРО-ШАГОВ:

Сцена "Персонаж бежит и прыгает через препятствие":

    Видео 1: Бег (3 сек) — Character runs forward, camera tracks alongside
    Видео 2: Прыжок (2 сек) — Character jumps upward, legs curl under body, camera tilts up following jump
    Видео 3: Приземление (2 сек) — Character lands in crouch, camera lands with them (slight shake)

Сцена "Персонаж входит в комнату, осматривается, видит что-то":

    Видео 1: Вход (3 сек) — Character opens door, steps through, camera follows
    Видео 2: Осмотр (4 сек) — Character head turns left to right scanning room, camera static
    Видео 3: Реакция (2 сек) — Character eyes widen, expression changes to surprise, camera zooms in on face

Шаг 7.4: Организация видеофайлов

Действие: Все сгенерированные видео сохранить в папку Videos_Raw/ с понятными названиями.

СТРУКТУРА ПАПОК (обновлённая):
Code

Project/
├── References/
│   ├── Character_Base_Reference.png
│   └── Character_Consistency_Map_3x3.png
├── Shots_Raw/ (оригинальные изображения из генератора)
├── Shots_Final/ (апскейленные + очищенные изображения)
├── Videos_Raw/ ← ЗДЕСЬ все видео
│   ├── Video_001_Establishing_City.mp4
│   ├── Video_002_Hunter_Alley_Walk.mp4
│   ├── Video_055a_Sword_Draw.mp4
│   ├── Video_055b_Sword_Clash.mp4
│   ├── Video_055c_Counter_Swing.mp4
│   ├── Video_055d_Enemy_Hit.mp4
│   └── ...
└── Audio/ (будет создана в Блоке #8)
    ├── Voice/
    ├── Music/
    └── SFX/

Правило именования для микро-шагов:
Code

Video_[Shot#][Подномер]_[Описание].mp4

Примеры:
Video_055a_Sword_Draw.mp4
Video_055b_Sword_Clash.mp4
Video_055c_Counter_Swing.mp4

Обновление shot list для микро-шагов:
Shot #	Type	Description	Status	Video Links
55	Action	Fight scene	✅ Complete	Video_055a.mp4, Video_055b.mp4, Video_055c.mp4, Video_055d.mp4
🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #7
AI VIDEO ГЕНЕРАТОРЫ (Image-to-Video)

Критерии сравнения:
Сервис	Free tier	Длительность	Разрешение	Качество	Скорость	Для какого стиля
Kling AI	66 кредитов/день (~6-8 видео)	5-10 сек	720p (1080p платно)	⭐⭐⭐⭐⭐	Средняя (2-5 мин)	Универсал, отлично для anime
Luma Dream Machine	30 видео/месяц	5 сек	720p	⭐⭐⭐⭐	Быстрая (1-2 мин)	Реалистичные стили
Pika Labs	30 видео/месяц	3-5 сек	720p	⭐⭐⭐⭐	Средняя (2-4 мин)	Хорошо для персонажей
Runway Gen-3	Trial (несколько видео)	5-10 сек	1080p	⭐⭐⭐⭐⭐	Быстрая (1-3 мин)	Кинематографический
Pixverse	300 кредитов/день (~20-30 видео)	4 сек	720p	⭐⭐⭐	Быстрая (1 мин)	Anime-специализация
Haiper AI	Unlimited (медленная очередь)	4 сек	720p	⭐⭐⭐	Медленная (5-15 мин)	Универсал
100% БЕСПЛАТНЫЕ (или с очень щедрым free tier)

✅ Pixverse ⭐ — ЛУЧШИЙ ДЛЯ ОБЪЁМА

    Ссылка: https://pixverse.ai
    Free tier: 300 кредитов/день = ~20-30 видео по 4 сек
    Для чего: Генерация БОЛЬШОГО количества клипов (идеально для 50-80 кадров)
    Как использовать:
        Регистрация → Dashboard
        Create → Image to Video
        Upload изображение из Shots_Final/
        Вставить motion prompt
        (Опционально) Включить Anime Mode (галочка справа) для anime-стилей
        Duration: 4 секунды (фиксированная)
        Generate
    Плюсы:
        Огромный лимит (300 кредитов/день)
        Специальный Anime Mode (улучшает качество для anime)
        Быстрая генерация (1-2 мин)
    Минусы:
        Фиксированная длительность (только 4 сек)
        Качество ниже Kling/Runway
        Иногда "слоу-моушен суп" (нужно регенерировать)
    Рекомендация: ОСНОВНОЙ ИНСТРУМЕНТ для генерации массива клипов за счёт огромного лимита

✅ Haiper AI

    Ссылка: https://haiper.ai
    Free tier: Unlimited (медленная очередь, 5-15 мин ожидания) + 100 кредитов/месяц (быстрая очередь)
    Для чего: Альтернатива Pixverse когда кредиты закончились
    Плюсы:
        Unlimited (технически можно генерировать бесконечно, но медленно)
        Не требует кредитной карты
    Минусы:
        Качество ниже топовых сервисов
        Медленная очередь в free tier (до 15 мин на видео)
    Рекомендация: Резервный инструмент

FREE TIER (с лимитами, но высокое качество)

✅ Kling AI 1.6 ⭐⭐ — ЛУЧШЕЕ КАЧЕСТВО В FREE TIER

    Ссылка: https://klingai.com
    Free tier: 66 кредитов/день = ~6-8 видео по 5 сек (Standard mode)
    Для чего: Генерация КЛЮЧЕВЫХ сцен (close-ups, action, сложные движения)
    Как использовать:
        Регистрация → Image to Video
        Upload изображение
        Prompt: вставить motion prompt
        Mode: Standard (Pro платный, 1080p)
        Duration: 5 или 10 сек (10 сек = 2x кредитов)
        Generate
    Плюсы:
        Высочайшее качество среди бесплатных (лучше Pika/Luma в некоторых сценах)
        Хорошо понимает сложные промпты
        Отлично работает с anime-стилями (Bebop, Cyberpunk)
        Можно выбрать длительность (5 или 10 сек)
    Минусы:
        Лимит 66 кредитов/день (~6-8 видео)
        Standard mode = 720p (1080p только в Pro)
        Генерация 2-5 минут
    Рекомендация: Использовать для ключевых 20-30% сцен (close-ups персонажа, важные action scenes, эмоциональные моменты)

✅ Luma Dream Machine

    Ссылка: https://lumalabs.ai/dream-machine
    Free tier: 30 генераций/месяц (обновляется ежемесячно)
    Для чего: Реалистичные стили (Cinematic Realistic), естественные движения камеры
    Как использовать:
        Sign Up → Dream Machine
        Image to Video
        Upload image + motion prompt
        Generate (фиксированная длительность 5 сек)
    Плюсы:
        Очень быстрая генерация (1-2 минуты)
        Высокое качество для реалистичных сцен
        Хорошо работает с camera movements (pans, dollies)
    Минусы:
        Лимит 30/месяц (для 50-80 кадров недостаточно)
        Фиксированная длительность 5 сек
        Хуже работает с anime vs Kling
    Рекомендация: Для реалистичных стилей или когда Kling кредиты закончились

✅ Pika Labs (Pika 2.0)

    Ссылка: https://pika.art
    Free tier: 30 видео/месяц (~250 кредитов, обновляется ежемесячно)
    Для чего: Анимация персонажей (хорошо работает с лицами)
    Как использовать:
        Sign Up → Create
        Upload image
        Motion prompt (Pika предпочитает короткие промпты)
        Duration: 3 или 5 сек
        Generate
    Плюсы:
        Хорошо анимирует лица (микроэмоции, движения глаз)
        Понимает camera keywords ("Camera: pan left", "Subject: walks")
        Можно задать camera movement отдельно от subject movement
    Минусы:
        Лимит 30/месяц
        Короткие видео (3-5 сек)
        Не специализирован на anime (лучше для semi-realistic)
    Рекомендация: Для close-ups лиц, диалоговых сцен

✅ Runway Gen-3 Alpha (Trial)

    Ссылка: https://runwayml.com
    Free tier: Trial (несколько бесплатных генераций при регистрации, потом платно)
    Для чего: Тестирование ВЫСОЧАЙШЕГО качества (если нужны референсы топ-уровня)
    Плюсы:
        Лучшее качество среди всех сервисов (1080p, профессиональный уровень)
        Понимает кинематографические термины ("rack focus", "whip pan")
        Используется в Голливуде
    Минусы:
        Trial ограничен (3-5 генераций)
        Платная подписка дорогая ($12-15/месяц)
    Рекомендация: Использовать trial для 3-5 КЛЮЧЕВЫХ сцен (кульминация, важный close-up)

СТРАТЕГИЯ РОТАЦИИ ДЛЯ 50-80 КАДРОВ

Цель: Сгенерировать все видео за 7-10 дней, используя бесплатные тарифы.

План:

День 1-5: Pixverse (основной массив)

    300 кредитов/день × 5 дней = 1500 кредитов = ~100-150 видео
    Достаточно для всех 50-80 кадров (даже с учётом регенераций)
    Задача: Сгенерировать ВСЕ establishing shots, wide shots, medium shots (80% кадров)

День 1-5 параллельно: Kling AI (ключевые сцены)

    66 кредитов/день × 5 дней = 330 кредитов = ~30-40 видео
    Задача: Сгенерировать close-ups персонажей, action scenes, эмоциональные сцены (20% кадров)

Резерв (если нужно):

    Luma: 30 видео/месяц → для особо важных сцен
    Pika: 30 видео/месяц → для диалоговых close-ups
    Haiper: Unlimited медленные → если всё остальное исчерпано

Итого: За 5-7 дней можно сгенерировать 50-80 видео (с запасом на регенерации) полностью бесплатно.
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #7

    Motion prompts созданы для ВСЕХ кадров shot list (20-40 или 50-80)
    Motion prompts содержат: что движется, скорость, направление, эффекты, статичные элементы
    Все кадры анимированы (видео созданы для каждого изображения из Shots_Final/)
    Длительность видео соответствует типу сцены (3-10 сек)
    Каждое видео соответствует motion prompt (движение правильное)
    Персонаж консистентен в видео (лицо, одежда не морфят)
    Нет критических артефактов (нет "слоу-моушен супа", лишних конечностей, морфинга фона)
    Сложные сцены разбиты на микро-шаги (3-5 отдельных видео для одной сложной сцены)
    Видео сохранены в папку Videos_Raw/ с названиями Video_XXX_Description.mp4
    Shot list таблица обновлена: Video Links добавлены, Status = ✅ Complete

Следующий блок: БЛОК #8: Звуковой дизайн (музыка, VO, SFX)

(Продолжение следует: Блоки #8-9 + Консистентность-блоки + Финальные секции. Текущий объём: ~85,000 символов)

[⏸ ПРОДОЛЖЕНИЕ В СЛЕДУЮЩЕМ СООБЩЕНИИ]
You said: продолжи
продолжи
Copilot said: ## БЛОК #8: ЗВУКОВОЙ ДИЗАЙН (МУЗЫКА, VO,
БЛОК #8: ЗВУКОВОЙ ДИЗАЙН (МУЗЫКА, VO, SFX)
🎯 Цель блока

Создать все аудиокомпоненты проекта: голоса персонажей (voice-over), фоновую музыку, звуковые эффекты (SFX — sound effects).

Принцип: 50% восприятия видео = звук. Хороший звук компенсирует средний визуал, плохой звук убивает отличный визуал.
📝 Шаги
Шаг 8.1: Генерация голосов персонажей (Voice-Over)

Действие: Для каждой диалоговой реплики из сценария (Блок #1) создать аудиофайл с AI-голосом.

ПОДГОТОВКА: Извлечение диалогов из сценария

    Открыть сценарий из Блока #1
    Скопировать все реплики персонажей в отдельный документ
    Формат:

Code

Character: [Имя персонажа]
Line 1: [Текст реплики 1]
Line 2: [Текст реплики 2]
...

Пример:
Code

Character: Hunter (male, 45, tired voice)
Line 1: You read the brief?
Line 2: Good. Let's move.
Line 3: (muttering) This better be worth the credits...

Character: AI (female, synthetic, calm)
Line 1: Warning: Unauthorized access detected.
Line 2: Initiating lockdown protocol.

ГЕНЕРАЦИЯ ГОЛОСОВ: Пошаговая инструкция

Метод 1: ElevenLabs (рекомендуется, лучшее качество)

    Открыть: https://elevenlabs.io

    Регистрация/Вход:
        Sign Up (если первый раз)
        Free tier: 10,000 символов/месяц (~10-15 минут аудио)

    Выбрать голос для персонажа:

    Навигация: Library → Voices → Browse

    Фильтры:
        Gender: Male / Female
        Age: Young / Middle Aged / Old
        Accent: American / British / Australian и др.
        Use case: Narration / Characters / Conversational

    Для Hunter (мужчина 45, уставший):
        Фильтр: Male, Middle Aged, American
        Искать голоса с описанием: "Deep", "Gravelly", "Tired"
        Прослушать несколько (кнопка Play рядом с именем голоса)
        Выбрать подходящий (например, "Marcus" или "Liam")

    Перейти в генерацию:

    Speech Synthesis → Text to Speech

    Настроить параметры:

    Voice: Выбрать голос из п.3 (например, "Marcus")

    Model: Eleven Multilingual v2 (поддерживает эмоции)

    Voice Settings:
        Stability: 0.5-0.7 (средняя = естественность)
        Similarity: 0.7-0.8 (высокая = ближе к оригиналу голоса)
        Style Exaggeration: 0.3-0.5 (средняя = умеренная эмоциональность)

    Вставить текст реплики:

    В поле текста вставить одну реплику (не все сразу):
    Code

    You read the brief?

    Добавить emotion tags (теги эмоций):

    ElevenLabs понимает теги в формате (эмоция):

    Примеры тегов:
        (tired) — уставший
        (angry) — злой
        (whispering) — шёпот
        (shouting) — крик
        (sad) — грустный
        (excited) — взволнованный
        (sarcastic) — саркастичный

    Применение:

    Вставить тег перед словами или фразой:
    Code

    (tired) You read the brief?

    Для сложных эмоций:
    Code

    (muttering, annoyed) This better be worth the credits...

    Генерировать:

    Нажать Generate → дождаться (5-15 сек)

    Прослушать результат:

    Кнопка Play появится под текстовым полем

    Если НЕ устраивает:
        Изменить emotion tag (попробовать другую эмоцию)
        Изменить Voice Settings (например, увеличить Style Exaggeration до 0.7 для большей эмоциональности)
        Регенерировать (Generate снова)

    Скачать:

    Кнопка Download → выбрать формат MP3 или WAV

    Имя файла: VO_Hunter_Line01.mp3

    Место: Папка Project/Audio/Voice/

    Повторить для всех реплик:

    Каждая реплика = отдельный аудиофайл

    Почему отдельно: В монтаже (Блок #9) нужно точно синхронизировать каждую реплику с видео, проще работать с отдельными файлами.

ОПТИМИЗАЦИЯ: Batch generation (для множественных реплик)

Если реплик много (20+), можно генерировать пакетами:

    Вставить несколько реплик через Enter:
    Code

    (tired) You read the brief?
    [PAUSE: 0.5]
    (calm) Good. Let's move.
    [PAUSE: 0.5]
    (muttering, annoyed) This better be worth the credits...

    [PAUSE: X] — тег паузы (X секунд между репликами)

    Генерировать → получить один аудиофайл со всеми репликами

    В монтаже (Блок #9) разрезать файл на отдельные реплики

Минус подхода: Меньше контроля над каждой репликой (сложнее регенерировать одну).

Метод 2: Play.ht (альтернатива ElevenLabs)

✅ Play.ht

    Ссылка: https://play.ht
    Free tier: 12,500 символов (~10 минут аудио)
    Отличия от ElevenLabs:
        Больше голосов (900+ vs 50+ у ElevenLabs)
        Поддержка большего количества языков
        Интерфейс проще
    Недостаток: Эмоциональность ниже vs ElevenLabs (emotion tags работают хуже)

Как использовать:

    https://play.ht → Sign Up
    Text to Speech
    Выбрать голос из библиотеки (фильтры: Gender, Language, Style)
    Вставить текст
    (Опционально) Emotion tags в формате <emotion>текст</emotion>:
    Code

    <tired>You read the brief?</tired>

    Generate → Download

Метод 3: Uberduck (бесплатно, но ниже качество)

✅ Uberduck

    Ссылка: https://uberduck.ai
    Free tier: Бесплатно с лимитами
    Особенность: AI voices + celebrity voices (для пародий/мемов)
    Качество: Ниже ElevenLabs/Play.ht

Рекомендация: Использовать только если ElevenLabs и Play.ht лимиты исчерпаны.

ТАБЛИЦА СРАВНЕНИЯ VOICE ГЕНЕРАТОРОВ:
Критерий	ElevenLabs	Play.ht	Uberduck
Качество	⭐⭐⭐⭐⭐	⭐⭐⭐⭐	⭐⭐⭐
Эмоциональность	⭐⭐⭐⭐⭐	⭐⭐⭐	⭐⭐
Количество голосов	50+	900+	5000+ (celebrity)
Free tier	10,000 символов/мес	12,500 символов/мес	Лимитированный
Языки	29	142	Английский + базовый multilingual
Рекомендация	ОСНОВНОЙ (лучшее качество)	РЕЗЕРВ (когда ElevenLabs кончился)	ПОСЛЕДНИЙ ВАРИАНТ
Шаг 8.2: Генерация фоновой музыки

Действие: Создать 2-4 музыкальных трека для разных частей видео (вступление, напряжение, экшен, развязка).

СТРАТЕГИЯ МУЗЫКАЛЬНОГО ДИЗАЙНА:

Для видео 1-2 минуты:

    1 трек (фоновый, сквозной) — играет почти всё время
    1 трек (кульминация) — для ключевой сцены (драка/погоня)

Для видео 3-5 минут:

    Трек 1: Opening (вступление, 0:00-0:30) — атмосферный, знакомство с миром
    Трек 2: Tension (напряжение, 0:30-2:00) — нарастающее беспокойство
    Трек 3: Action (экшен, 2:00-4:00) — интенсивный, быстрый темп
    Трек 4: Resolution (развязка, 4:00-5:00) — успокаивающийся или триумфальный

ГЕНЕРАЦИЯ МУЗЫКИ: Пошаговая инструкция

Метод 1: Suno AI (рекомендуется, лучшее качество)

✅ Suno AI

    Ссылка: https://suno.ai
    Free tier: 50 кредитов/день = ~10 песен по 2 минуты (каждая песня = 5 кредитов)
    Особенность: Создаёт профессиональную музыку (инструментальную или с вокалом)

Инструкция:

    Открыть: https://suno.ai → Sign Up (Google/Discord/Email)

    Перейти в Create:

    Кнопка Create в верхнем меню

    Выбрать режим:

    Custom Mode (кнопка справа) — даёт контроль над стилем и текстом

    vs Simple Mode (автоматический) — AI сам решает

    Написать промпт для музыки:

ПРОМПТ-ФОРМУЛА ДЛЯ МУЗЫКИ:
Code

[Жанр], [Настроение], [Инструменты], [Темп BPM], [Дополнительные характеристики]

ПРИМЕРЫ ПРОМПТОВ ДЛЯ РАЗНЫХ СЦЕН:

Пример 1: Opening track (Cowboy Bebop style)
Code

Genre: Jazz fusion, blues rock
Mood: Laid-back, melancholic, atmospheric
Instruments: Saxophone lead, electric bass, jazz drums, muted trumpet
Tempo: 85 BPM, slow groove
Style: Cowboy Bebop soundtrack inspired, 90s anime aesthetic, smooth
Length: 2 minutes
Vibe: Urban night, neon lights, rain-soaked streets

Разбор:

    Jazz fusion, blues rock — жанр (Cowboy Bebop фирменный стиль)
    Saxophone lead — главный инструмент (узнаваемый элемент Bebop)
    85 BPM, slow groove — темп (медленный = атмосферный)
    Cowboy Bebop soundtrack inspired — прямая референсная точка для AI

Пример 2: Tension track (нарастающее напряжение)
Code

Genre: Dark ambient, cinematic orchestral
Mood: Tense, suspenseful, foreboding
Instruments: Low strings (cellos, double bass), subtle synth pads, sparse percussion, distant piano notes
Tempo: 70 BPM, slow build-up
Style: Hans Zimmer inspired, minimalist tension
Length: 2 minutes
Progression: Starts quiet, gradually adds layers, crescendo at 1:30 mark
Vibe: Something bad is coming, unease

Разбор:

    Dark ambient, cinematic orchestral — жанр для напряжения
    Low strings — создают давящую атмосферу
    Slow build-up — музыка нарастает постепенно
    Crescendo at 1:30 — пик напряжения в конкретный момент

Пример 3: Action track (боевая сцена)
Code

Genre: Electronic rock, industrial metal
Mood: Aggressive, intense, adrenaline-pumping
Instruments: Distorted electric guitars, heavy drums, aggressive synth bass, electronic glitches
Tempo: 140 BPM, fast-paced
Style: Prodigy meets Daft Punk, cyberpunk action
Length: 2 minutes
Energy: High energy throughout, no breaks, relentless
Vibe: Chase scene, fight sequence, life-or-death stakes

Разбор:

    140 BPM, fast-paced — быстрый темп = экшен
    Heavy drums, distorted guitars — агрессивность
    No breaks, relentless — постоянная интенсивность (vs волнообразная динамика)

Пример 4: Resolution track (развязка, триумф)
Code

Genre: Epic orchestral, post-rock
Mood: Triumphant, hopeful, emotional release
Instruments: Full orchestra (strings, brass, timpani), piano, soaring violins, choir (wordless vocals)
Tempo: 95 BPM, moderate, gradually slowing at end
Style: Two Steps From Hell inspired, cinematic climax
Length: 2 minutes
Progression: Starts powerful, peaks at 1:00, gentle outro from 1:45
Vibe: Hero's victory, emotional payoff, sunset ride into horizon

    Вставить промпт:

    В поле Style of Music вставить промпт (например, Opening track промпт)

    Настроить параметры:

    Instrumental: Включить галочку (если не нужен вокал)

    vs Vocal: Если хотите песню с текстом (тогда заполнить поле Lyrics)

    Title: Название трека (например, "Neon Nights Opening")

    Генерировать:

    Нажать Create → дождаться (30-90 секунд)

    Suno создаст 2 варианта (версии A и B) — прослушать оба, выбрать лучший

    Прослушать и оценить:

    Кнопка Play рядом с каждой версией

    Критерии оценки:
        ✅ Настроение соответствует промпту
        ✅ Инструменты слышны (если просили саксофон — он действительно есть)
        ✅ Темп правильный (не слишком быстро/медленно)
        ✅ Длина ~2 минуты (или как указано)

    Если НЕ устраивает:
        Изменить промпт (уточнить жанр, добавить референс)
        Регенерировать (Create снова, Suno даст другой результат)

    Скачать:

    Три точки (⋯) рядом с треком → Download → Audio (MP3)

    Имя файла: Music_Opening_Neon_Nights.mp3

    Место: Папка Project/Audio/Music/

    Повторить для остальных треков:

    Создать 2-4 трека (в зависимости от длины видео) с разными промптами

РАСШИРЕННАЯ ТЕХНИКА: Extending tracks (продление треков)

Если Suno создал отличный трек 2 минуты, но нужно 3-4 минуты:

    Открыть трек
    Кнопка Extend (справа от Play)
    Опции:
        Continue — продлить музыку в том же стиле
        Add Section — добавить новую часть (можно задать новый промпт для вариации)
    Generate → получить продлённую версию

Метод 2: Udio (альтернатива Suno)

✅ Udio

    Ссылка: https://udio.com
    Free tier: 1200 кредитов/месяц = ~30-40 треков
    Отличие от Suno: Больше контроля над структурой трека (Intro-Verse-Chorus-Outro)

Как использовать:

    https://udio.com → Sign Up
    Create
    Промпт: аналогично Suno (жанр, настроение, инструменты)
    Настройка: можно задать структуру (Intro 20 сек, Verse 40 сек, Chorus 30 сек, Outro 20 сек)
    Generate → Download

Преимущество: Можно точнее контролировать, где будет кульминация трека.

Метод 3: Soundraw (ограниченный free tier)

✅ Soundraw

    Ссылка: https://soundraw.io
    Free tier: Пробный период (ограниченное количество скачиваний)
    Особенность: Не генерирует музыку с нуля, а комбинирует готовые паттерны

Рекомендация: Использовать только если Suno и Udio не подходят.

ТАБЛИЦА СРАВНЕНИЯ МУЗЫКАЛЬНЫХ AI:
Критерий	Suno AI	Udio	Soundraw
Качество	⭐⭐⭐⭐⭐	⭐⭐⭐⭐⭐	⭐⭐⭐
Креативность	⭐⭐⭐⭐⭐	⭐⭐⭐⭐	⭐⭐ (паттерны)
Контроль структуры	⭐⭐⭐	⭐⭐⭐⭐⭐	⭐⭐⭐⭐
Free tier	50 кредитов/день	1200 кредитов/мес	Пробный период
Длина треков	2-4 мин (с extend)	2-15 мин	1-5 мин
Рекомендация	ОСНОВНОЙ	РЕЗЕРВ (для длинных треков)	НЕ РЕКОМЕНДУЕТСЯ
Шаг 8.3: Поиск/генерация звуковых эффектов (SFX)

Действие: Собрать все звуковые эффекты для видео (шаги, оружие, окружение, технологические звуки).

СОСТАВЛЕНИЕ СПИСКА НУЖНЫХ SFX

    Открыть shot list (Блок #1)
    Для каждого кадра записать все звуки, которые должны быть слышны
    Формат:

Code

Shot #2: Hunter walks in alley
SFX needed:
- Footsteps on wet pavement (slow pace)
- Rain ambient (light rain)
- Distant traffic noise
- Neon sign buzzing

Shot #48: Hunter draws blaster
SFX needed:
- Weapon draw (metal scraping)
- Blaster power-up sound
- Character grunt (effort sound)
- Sparks from electrical panel

Типичные категории SFX для sci-fi/cyberpunk видео:
Категория	Примеры звуков
Footsteps (шаги)	Concrete, metal grating, puddles, grass
Weapons (оружие)	Blaster shot, sword swing, blade unsheath, gun reload
Ambience (окружение)	City traffic, rain, wind, crowd walla (фоновые голоса)
Technology	Hologram activation, computer beep, door hiss, engine hum
Impacts (удары)	Punch, body fall, metal clang, explosion
Foley (одежда/движение)	Jacket rustle, belt clink, breathing

ИСТОЧНИКИ БЕСПЛАТНЫХ SFX

Метод 1: Freesound.org (рекомендуется, огромная библиотека)

✅ Freesound.org

    Ссылка: https://freesound.org
    Free tier: Полностью бесплатно (нужна регистрация)
    Библиотека: 600,000+ звуков
    Лицензии: Creative Commons (большинство разрешают коммерческое использование с атрибуцией)

Инструкция:

    Регистрация: https://freesound.org/home/register/

    Поиск звука:

    Поле поиска → ввести название на английском (например, "footsteps concrete")

    Советы по поиску:
        Используйте простые термины: "rain" вместо "atmospheric precipitation"
        Добавляйте материал: "footsteps metal", "door wood"
        Для sci-fi: добавляйте "sci-fi" или "futuristic" (например, "sci-fi blaster")

    Фильтры:

    Левая панель:
        Duration: Фильтр по длине (например, 0-5 сек для коротких SFX)
        License: Выбрать "Creative Commons 0" (самая свободная, не требует атрибуции) или "Attribution" (требует указать автора в титрах)
        Channels: Stereo (для пространственного звука)

    Прослушать:

    Кнопка Play рядом с каждым звуком

    Оценить:
        ✅ Качество записи (нет шумов, треска)
        ✅ Соответствие (звук действительно похож на нужный)
        ✅ Длина подходит (не слишком длинный/короткий)

    Скачать:

    Кнопка Download → выбрать качество (обычно самое высокое = лучшее)

    Имя файла: Переименовать в понятное (например, SFX_Footsteps_Concrete_Wet.wav)

    Место: Папка Project/Audio/SFX/

    Записать атрибуцию (если требуется лицензией):

    Если лицензия "Attribution":
        Скопировать имя автора и ссылку на звук
        Создать файл SFX_Credits.txt в папке Audio
        Формат:
        Code

        Footsteps Concrete Wet by [Author Name]
        https://freesound.org/people/[username]/sounds/[ID]/
        License: CC BY 4.0

    Повторить для всех SFX из списка

Метод 2: Pixabay Sound Effects (без регистрации)

✅ Pixabay Sound Effects

    Ссылка: https://pixabay.com/sound-effects/
    Free tier: Полностью бесплатно (БЕЗ регистрации)
    Библиотека: 100,000+ звуков
    Лицензия: Pixabay License (royalty-free, можно использовать коммерчески без атрибуции)

Инструкция:

    Перейти по ссылке → Search (поиск)
    Ввести название звука (например, "rain")
    Фильтры: Duration, Category
    Прослушать → Download (MP3 или WAV)
    Сохранить в Project/Audio/SFX/

Преимущества vs Freesound:

    Не нужна регистрация
    Не нужна атрибуция

Недостатки:

    Меньше звуков (100K vs 600K)
    Качество варьируется (больше любительских записей)

Метод 3: Zapsplat (высокое качество, лимит скачиваний)

✅ Zapsplat

    Ссылка: https://www.zapsplat.com
    Free tier: Бесплатно с регистрацией, лимит ~15 скачиваний/день
    Библиотека: Профессиональные SFX (многие из кино/ТВ)

Рекомендация: Использовать для ключевых SFX (например, звук оружия, важные удары), когда Freesound/Pixabay не дали нужного качества.

Метод 4: AI-генерация SFX (экспериментально)

✅ ElevenLabs Sound Effects (в beta, доступ ограничен)

    Ссылка: https://elevenlabs.io/sound-effects (если доступно в вашем аккаунте)
    Как работает: Описываете звук текстом → AI создаёт
    Пример промпта: "Futuristic blaster shot, high-pitched electronic zap with echo"
    Статус: Beta (может быть недоступно в free tier)

Альтернатива AI-генерации:

    Audiobox (Meta): https://audiobox.metademolab.com (экспериментальный, бесплатный)
    Stable Audio: https://www.stableaudio.com (free tier ограничен)

Рекомендация: Пока AI-генерация SFX не достигла качества библиотек → использовать Freesound/Pixabay как основной источник.

ОРГАНИЗАЦИЯ SFX ФАЙЛОВ
Code

Project/Audio/SFX/
├── Ambience/
│   ├── Rain_Light.wav
│   ├── City_Traffic_Distant.wav
│   └── Wind_Gentle.wav
├── Footsteps/
│   ├── Concrete_Walk.wav
│   ├── Metal_Grating_Walk.wav
│   └── Puddle_Splash.wav
├── Weapons/
│   ├── Blaster_Shot.wav
│   ├── Sword_Draw.wav
│   └── Blade_Swing.wav
├── Technology/
│   ├── Hologram_Activate.wav
│   ├── Door_Hiss_Open.wav
│   └── Computer_Beep.wav
└── Impacts/
    ├── Punch_Heavy.wav
    ├── Body_Fall.wav
    └── Metal_Clang.wav

Преимущество структуры: Легко найти нужный звук в монтаже (Блок #9).
Шаг 8.4: Синхронизация губ с голосом (опционально, для диалогов)

Действие: Если в видео есть кадры крупным планом (close-up) с говорящим персонажем — синхронизировать движение губ с аудио голоса.

КОГДА НУЖНО:

    ✅ Close-up shot лица персонажа + диалог
    ✅ Medium shot с видимым лицом + длинная реплика (3+ секунды)

КОГДА НЕ НУЖНО:

    ❌ Wide shot (лицо слишком мелкое, губы не видны)
    ❌ Персонаж отвёрнут / в тени / шлем закрывает лицо
    ❌ Закадровый голос (voice-over commentary)

ИНСТРУМЕНТ: Hedra (AI lip-sync)

✅ Hedra

    Ссылка: https://hedra.com
    Free tier: Лимитированный (проверить актуальные лимиты на сайте, обычно ~10-20 видео/месяц)
    Как работает: Загружаете изображение лица + аудио → AI анимирует губы под речь
    Разрешение: До 1080p

Инструкция:

    Подготовить изображение лица:

    Взять кадр из Shots_Final/ где персонаж крупным планом (например, Shot_015_Hunter_Face.png)

    Требование: Лицо должно быть статичным (не из анимированного видео, а из изначального изображения)

    Если изображение уже анимировано (из Блока #7):
        Экспортировать первый кадр видео как изображение (в видеоредакторе: Export Frame)

    Подготовить аудио:

    Взять файл голоса из Project/Audio/Voice/ (например, VO_Hunter_Line01.mp3)

    Открыть Hedra:

    https://hedra.com → Sign Up/Login

    Создать видео:

    Create → Character Video

    Загрузить изображение:

    Upload Image → выбрать изображение лица

    Загрузить аудио:

    Upload Audio → выбрать аудиофайл голоса

    Настроить параметры (если доступны):
        Voice Emotion: Выбрать эмоцию (Neutral / Happy / Sad / Angry) — влияет на мимику
        Head Movement: Slight (лёгкие движения головы) / None (только губы)

    Генерировать:

    Generate → дождаться (1-3 минуты)

    Результат:

    Видео с анимированными губами, синхронизированными с аудио

    Оценить качество:

    Критерии:
        ✅ Губы двигаются в такт речи (не отстают/не опережают)
        ✅ Мимика естественная (не "роботоподобная")
        ✅ Нет артефактов (губы не "плавятся", зубы не деформируются)

    Если качество плохое:
        AI lip-sync (2026 год) всё ещё несовершенен
        Решение: Использовать микс Hedra + оригинального видео из Блока #7 (см. ниже)

    Скачать:

    Download → MP4

    Имя файла: Video_015_Hunter_Face_LipSync.mp4

    Место: Папка Project/Videos_Lipsync/ (отдельно от Videos_Raw)

СТРАТЕГИЯ МИКСА: Hedra + оригинальное видео

Проблема: Hedra создаёт хорошую синхронизацию губ, но часто:

    Лицо слишком статично (глаза не моргают, брови не двигаются)
    Фон застывший

Решение: Комбинировать в монтаже (Блок #9):

    Использовать оригинальное видео из Блока #7 (где персонаж живой, но губы не синхронизированы) для большей части кадра
    Вставить Hedra-видео (с синхронизированными губами) только на моменты, когда персонаж говорит (1-3 секунды)
    Быстрый cut (переход) между ними — зритель не заметит смену

Пример:
Code

Сцена диалога (6 секунд):

0:00-0:02 — Оригинальное видео (персонаж слушает, губы не двигаются) ✅
0:02-0:05 — Hedra-видео (персонаж говорит: "You read the brief?") ✅
0:05-0:06 — Оригинальное видео (персонаж замолкает, смотрит в сторону) ✅

Преимущество: Лучшее из обоих миров (динамичность оригинального видео + точная синхронизация губ от Hedra).

АЛЬТЕРНАТИВНЫЕ ИНСТРУМЕНТЫ LIP-SYNC:
Инструмент	Ссылка	Free tier	Качество
Hedra	https://hedra.com	Лимитированный	⭐⭐⭐⭐
D-ID	https://www.d-id.com	20 кредитов (trial)	⭐⭐⭐⭐
Synthesia	https://www.synthesia.io	Trial (несколько видео)	⭐⭐⭐⭐⭐ (но дорогой)
Wav2Lip (open-source)	https://github.com/Rudrabha/Wav2Lip	Бесплатно (нужен Python)	⭐⭐⭐

Рекомендация:

    Hedra — основной (баланс качества и доступности)
    D-ID — резерв (если Hedra лимиты закончились)
    Wav2Lip — для продвинутых пользователей (можно запустить локально, unlimited, но требует технических навыков)

🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #8
AI Voice генераторы (100% бесплатные с лимитами)

✅ ElevenLabs ⭐⭐ — https://elevenlabs.io (10,000 символов/мес, ЛУЧШЕЕ качество)
✅ Play.ht — https://play.ht (12,500 символов/мес, больше голосов)
✅ Uberduck — https://uberduck.ai (лимитированный, celebrity voices)
AI музыка генераторы (100% бесплатные с лимитами)

✅ Suno AI ⭐⭐ — https://suno.ai (50 кредитов/день = 10 песен, ЛУЧШЕЕ качество)
✅ Udio — https://udio.com (1200 кредитов/мес = 30-40 треков, больше контроля)
✅ Soundraw — https://soundraw.io (пробный период, паттерны)
Бесплатные библиотеки SFX (100% бесплатные)

✅ Freesound.org ⭐⭐ — https://freesound.org (600K+ звуков, нужна регистрация)
✅ Pixabay Sound Effects — https://pixabay.com/sound-effects/ (100K+ звуков, БЕЗ регистрации)
✅ Zapsplat — https://www.zapsplat.com (профессиональные SFX, ~15 скачиваний/день)
Lip-sync (синхронизация губ)

✅ Hedra ⭐ — https://hedra.com (лимитированный, до 1080p)
✅ D-ID — https://www.d-id.com (20 кредитов trial)
✅ Wav2Lip (open-source) — https://github.com/Rudrabha/Wav2Lip (unlimited, требует Python)
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #8

    Все диалоги озвучены (аудиофайлы в папке Audio/Voice/)
    Голоса подобраны под персонажей (возраст, пол, характер соответствуют)
    Emotion tags применены к репликам (эмоции слышны)
    Создано 2-4 музыкальных трека для разных частей видео (Opening, Tension, Action, Resolution)
    Музыка соответствует настроению сцен (атмосферная для спокойных, интенсивная для экшена)
    Собраны/скачаны все нужные SFX (минимум 10-20 звуков: шаги, окружение, оружие, технологии)
    SFX организованы в подпапки по категориям (Ambience, Footsteps, Weapons, Technology, Impacts)
    Для крупных планов персонажей применён lip-sync (если есть диалоги) — видео в Videos_Lipsync/
    Все аудиофайлы имеют понятные названия (не "audio_001.mp3", а "VO_Hunter_Line01.mp3")
    Создан файл SFX_Credits.txt с атрибуцией (если требуется лицензиями)

Следующий блок: БЛОК #9: Финальный монтаж и экспорт
БЛОК #9: ФИНАЛЬНЫЙ МОНТАЖ И ЭКСПОРТ
🎯 Цель блока

Объединить все элементы (видеоклипы из Videos_Raw/, аудио из Audio/) в единый финальный ролик с синхронизацией, переходами, балансировкой звука и цветокоррекцией.
📝 Шаги
Шаг 9.1: Выбор видеоредактора и создание проекта

Действие: Выбрать видеоредактор, установить (если нужно), создать новый проект.

ВЫБОР РЕДАКТОРА (критерии для новичков):
Редактор	Сложность	Возможности	Производительность	Рекомендация
CapCut Desktop	⭐ (простейший)	⭐⭐⭐⭐	⭐⭐⭐⭐⭐ (быстрый)	ДЛЯ НОВИЧКОВ
DaVinci Resolve	⭐⭐⭐⭐ (сложный)	⭐⭐⭐⭐⭐ (профессиональный)	⭐⭐⭐ (требует GPU)	ДЛЯ ОПЫТНЫХ
Kdenlive	⭐⭐⭐ (средний)	⭐⭐⭐⭐	⭐⭐⭐⭐	OPEN-SOURCE
Shotcut	⭐⭐ (простой)	⭐⭐⭐	⭐⭐⭐⭐⭐ (легковесный)	ДЛЯ СЛАБЫХ ПК

ИНСТРУКЦИЯ: Создание проекта (универсальная)

Для CapCut Desktop (рекомендуется для новичков):

    Скачать и установить:
        Ссылка: https://www.capcut.com
        Скачать версию для Desktop (Windows/Mac)
        Установить (процесс стандартный)

    Запустить CapCut

    Создать новый проект:
        Кнопка Create project (или New project)
        Появится пустой timeline (таймлайн — временная шкала для монтажа)

    Настроить параметры проекта:

    Settings (иконка шестерёнки) → Project Settings:
        Resolution: 1920x1080 (Full HD)
        Frame Rate: 24 FPS (кинематографический) или 30 FPS (стандартный)
        Aspect Ratio: 16:9 (горизонтальное видео) или 9:16 (вертикальное для соцсетей)

    Сохранить настройки

    Сохранить проект:

    File → Save Project → выбрать папку Project/ → имя: Final_Edit.capcut

Для DaVinci Resolve (для опытных):

    Скачать и установить:
        Ссылка: https://www.blackmagicdesign.com/products/davinciresolve
        Версия: DaVinci Resolve 19 Free
        Требования: 8GB RAM минимум, GPU желательна (NVIDIA/AMD)

    Запустить Resolve → Create New Project

    Настройки:
        File → Project Settings → Master Settings:
            Timeline resolution: 1920x1080
            Timeline frame rate: 24 или 30 fps
        Save

Шаг 9.2: Импорт всех медиафайлов

Действие: Загрузить в проект все видео, аудио, изображения.

ИНСТРУКЦИЯ (CapCut):

    Media Pool (панель слева в CapCut) → кнопка Import

    Выбрать папки:

    Навигация к проекту:
        Импортировать всю папку Videos_Raw/ (или выбрать отдельные файлы)
        Импортировать папку Audio/Voice/
        Импортировать папку Audio/Music/
        Импортировать папку Audio/SFX/

    Дождаться импорта:

    Все файлы появятся в Media Pool (левая панель)

    Организация в Media Pool (опционально):

    CapCut позволяет создавать папки:
        ПКМ в Media Pool → New Folder → "Videos"
        Перетащить все видео в папку "Videos"
        Повторить для "Voice", "Music", "SFX"

Преимущество: Легче найти нужный файл на таймлайне.

ИНСТРУКЦИЯ (DaVinci Resolve):

    Media Pool (верхняя левая панель)

    Import Media (ПКМ в Media Pool → Import Media → выбрать папки)

    Создать Bins (аналог папок):
        ПКМ → Create Bin → "Videos", "Voice", "Music", "SFX"
        Перетащить файлы в соответствующие bins

Шаг 9.3: Раскладка видео на таймлайне (черновая сборка)

Действие: Разложить все видеоклипы на таймлайне в порядке shot list.

ИНСТРУКЦИЯ:

    Открыть shot list (из Блока #1) в отдельном окне/мониторе для референса

    Перетащить первый клип на таймлайн:

    Из Media Pool взять Video_001_Establishing_City.mp4 → перетащить на Video Track 1 (видеодорожка 1)

    Timeline (таймлайн) — горизонтальная шкала внизу экрана, где будут все клипы

    Добавить следующий клип:

    Video_002_Hunter_Alley.mp4 → перетащить на Video Track 1 СРАЗУ после Video_001 (клипы должны быть вплотную друг к другу)

    Snap to Grid (привязка к сетке) — включить, чтобы клипы автоматически "прилипали" друг к другу без зазоров

    Повторить для всех клипов:

    Выстроить все 20-80 клипов в порядке shot list на Video Track 1

    Результат черновой сборки:

    Timeline выглядит как длинная цепочка клипов (каждый 3-10 сек) → общая длительность видео 1-5 минут

СОВЕТ: На этом этапе НЕ обрезать клипы, просто выстроить последовательность.
Шаг 9.4: Обрезка клипов (trimming) и настройка длительности

Действие: Для каждого клипа обрезать лишние части, оставить только нужные секунды.

ПРОБЛЕМА: AI-генераторы видео (Блок #7) создали клипы по 3-10 секунд, но часто:

    Первые 0.5 сек = статичный кадр (ничего не происходит)
    Последние 1-2 сек = движение замедляется или артефакты

РЕШЕНИЕ: Обрезать каждый клип, оставив только "чистое" движение.

ИНСТРУКЦИЯ ПО ОБРЕЗКЕ (CapCut):

    Выбрать клип на таймлайне:

    Клик на Video_001_Establishing_City.mp4

    Включить Preview (предпросмотр):

    Окно справа показывает текущий кадр клипа

    Определить точки обрезки:

    Воспроизвести клип (кнопка Play или Пробел):
        Отметить момент, когда движение начинается (например, 0:00:00.5)
        Отметить момент, когда движение заканчивается (например, 0:00:04.0)

    Обрезать начало клипа:

    Подвести курсор к левому краю клипа на таймлайне → курсор изменится на иконку обрезки (][)

    Перетащить край вправо до точки 0:00:00.5 → отпустить

    Результат: Первые 0.5 сек клипа удалены

    Обрезать конец клипа:

    Подвести курсор к правому краю клипа → перетащить влево до точки 0:00:04.0

    Результат: Клип теперь 3.5 сек вместо 5 сек

    Проверить:

    Воспроизвести обрезанный клип → убедиться что движение плавное, без лишних статичных кадров

    Повторить для всех клипов:

    Каждый клип обрезать индивидуально

РЕКОМЕНДУЕМАЯ ДЛИТЕЛЬНОСТЬ КЛИПОВ ПО ТИПАМ:
Тип сцены	Рекомендуемая длина (после обрезки)	Почему
Establishing shot	3-5 сек	Нужно время показать масштаб
Wide shot (персонаж идёт)	3-4 сек	Достаточно для действия
Medium shot	2-4 сек	Фокус на персонаже
Close-up (лицо)	2-3 сек	Эмоция считывается быстро
Action shot (драка, бег)	1-3 сек	Быстрая смена = динамика
Dialogue shot	Зависит от длины реплики	Минимум: длина аудио реплики + 0.5 сек

ПРАВИЛО: Чем быстрее действие в кадре → тем короче клип. Экшен-сцены = 1-2 сек на клип, диалоги = 3-5 сек.
Шаг 9.5: Добавление переходов между клипами

Действие: Между некоторыми клипами добавить transitions (переходы) для плавности или драматического эффекта.

ТИПЫ ПЕРЕХОДОВ:
Переход	Когда использовать	Эффект
Cut (резкая смена)	Между большинством клипов	Стандартный киношный переход, невидим
Dissolve (растворение)	Смена локации, переход времени	Плавное слияние двух кадров
Fade to Black	Конец главы, драматическая пауза	Затемнение в чёрный экран
Fade from Black	Начало видео, пробуждение	Появление из чёрного экрана
Wipe	Не рекомендуется для серьёзных проектов	"Старомодный" эффект (Star Wars стиль, но выглядит любительски в 2026)

ПО УМОЛЧАНИЮ: 90% переходов должны быть Cut (резкая смена без эффектов) — это профессиональный стандарт.

Dissolve/Fade — использовать только в 3-5 местах (начало видео, смена главы, финал).

ИНСТРУКЦИЯ: Добавление переходов (CapCut):

    Открыть библиотеку переходов:

    Панель слева → Transitions (иконка двух квадратов с стрелкой)

    Выбрать тип перехода:

    Для начала видео (Fade from Black):
        Найти "Fade" в списке
        Перетащить Fade на начало первого клипа на таймлайне
        Длительность: 0.5-1 сек (настраивается перетаскиванием краёв перехода)

    Между клипами (Dissolve):
        Найти "Dissolve" или "Cross Dissolve"
        Перетащить между двумя клипами (например, между Video_001 и Video_002)
        Длительность: 0.3-0.5 сек (короткий dissolve = плавнее)

    Для конца видео (Fade to Black):
        Перетащить "Fade" на конец последнего клипа
        Длительность: 1-2 сек

    Проверить:

    Воспроизвести места с переходами → убедиться что плавно, не дёргается

СОВЕТ: Меньше = лучше. Если не уверены нужен ли переход — оставьте Cut (резкую смену).
Шаг 9.6: Синхронизация аудио

Действие: Добавить все аудиофайлы (голоса, музыку, SFX) на таймлайн и синхронизировать с видео.

СТРУКТУРА АУДИОДОРОЖЕК:
Code

Timeline:
├── Video Track 1 [все видеоклипы]
├── Audio Track 1 [Музыка — фоновая]
├── Audio Track 2 [Диалоги/Voice-Over]
├── Audio Track 3 [SFX — окружение (дождь, ветер)]
├── Audio Track 4 [SFX — действия (шаги, оружие)]
└── Audio Track 5 [SFX — удары/эффекты]

ИНСТРУКЦИЯ: Добавление музыки

    Из Media Pool перетащить музыкальный трек:

    Music_Opening_Neon_Nights.mp3 → на Audio Track 1 под видеоклипами

    Поместить в начало (0:00:00)

    Выровнять музыку с видео:

    Если трек длиннее видео → обрезать конец (как обрезали видео в Шаге 9.4)

    Если трек короче → добавить второй трек (Music_Tension.mp3) сразу после первого

    Создать плавный переход между музыкальными треками:

    Crossfade (перекрёстное затухание):
        Наложить конец первого трека на начало второго (overlap на 2-3 секунды)
        Применить Fade Out на первый трек + Fade In на второй трек
        Результат: Музыка плавно переходит из одной композиции в другую

ИНСТРУКЦИЯ: Добавление диалогов

    Найти кадр с диалогом:

    Например, Video_015_Hunter_Face.mp4 (Hunter говорит: "You read the brief?")

    Найти соответствующий аудиофайл:

    VO_Hunter_Line01.mp3 из Audio/Voice/

    Перетащить аудио на Audio Track 2:

    Поместить точно в момент, когда персонаж должен начать говорить на видео

    Синхронизация:
        Воспроизвести видео с аудио
        Если голос опережает движение губ → сдвинуть аудио вправо (позже)
        Если голос отстаёт → сдвинуть аудио влево (раньше)
        Цель: Голос начинается ровно когда персонаж открывает рот

    Повторить для всех диалогов

СОВЕТ: Если использовали Hedra lip-sync (Блок #8, Шаг 8.4):

    Hedra-видео уже содержит синхронизированный звук
    НЕ добавлять аудио отдельно (звук уже в видеофайле)

ИНСТРУКЦИЯ: Добавление SFX

Принцип: Каждый звуковой эффект привязан к конкретному визуальному действию.

Пример 1: Шаги персонажа

    Найти кадр где Hunter идёт (Video_002_Hunter_Alley_Walk.mp4)

    Отметить момент каждого шага (watch видео, считать: left foot down at 0:00:01.0, right foot at 0:00:01.5, и т.д.)

    Взять SFX Footsteps_Concrete_Walk.wav → перетащить на Audio Track 4

    Выровнять: Каждый звук шага = момент когда нога касается земли на видео

    Если SFX-файл — это один шаг:
        Копировать файл несколько раз
        Расставить копии с интервалом (каждые 0.5 сек для медленной ходьбы, каждые 0.3 сек для бега)

Пример 2: Звук оружия

    Кадр: Hunter выхватывает бластер (Video_048_Hunter_Draws_Blaster.mp4)

    Момент действия: Рука начинает движение к кобуре at 0:00:00.5, оружие выходит из кобуры at 0:00:00.8

    SFX нужны:
        Weapon_Draw_Metal.wav → на момент 0:00:00.8 (звук металла о кожу кобуры)
        Blaster_PowerUp.wav → на момент 0:00:01.0 (звук зарядки оружия)

    Добавить оба SFX на Audio Track 4 в нужные моменты

СОВЕТ: Для быстрых действий (удары, выстрелы) точность критична — разница в 0.1 сек заметна.

ИНСТРУКЦИЯ: Добавление фоновых SFX (ambience)

Фоновые звуки (дождь, ветер, city traffic) играют непрерывно в течение всей сцены (не привязаны к конкретным действиям).

    Взять SFX_Rain_Light.wav → перетащить на Audio Track 3

    Растянуть на всю длину сцены (например, Video_001-Video_010 происходят под дождём → ambience должен играть все эти 30 секунд)

    Если SFX короче сцены:
        Найти loopable (зацикливаемый) SFX (у которого конец плавно переходит в начало)
        Копировать и вставить несколько раз подряд
        Применить short Crossfade (0.1 сек) на стыках → бесшовный луп

Шаг 9.7: Балансировка звука (audio mixing)

Действие: Настроить громкость каждой аудиодорожки так, чтобы диалоги были чётко слышны, музыка не заглушала, SFX добавляли атмосферу но не отвлекали.

ПРИНЦИП ИЕРАРХИИ ЗВУКА:
Code

1. Диалоги (Voice-Over) — САМОЕ ГРОМКОЕ (чётко слышны всегда)
2. SFX (важные действия) — Второе по громкости
3. SFX (фоновые) — Третье
4. Музыка — Фоновая (поддерживает, не доминирует)

РЕКОМЕНДУЕМЫЕ УРОВНИ ГРОМКОСТИ:
Элемент	Громкость (dB)	Почему
Диалоги	-6 до -3 dB	Комфортная громкость, чётко слышны
SFX (действия)	-10 до -6 dB	Заметны, но не перекрывают диалоги
SFX (фоновые)	-18 до -12 dB	Создают атмосферу, почти незаметны
Музыка	-18 до -12 dB	Поддерживает настроение, не мешает

ИСКЛЮЧЕНИЕ: Когда нет диалогов (action scene без слов) → музыка может быть громче (-10 до -6 dB).

ИНСТРУКЦИЯ: Настройка громкости (CapCut):

    Выбрать аудиотрек/клип:

    Клик на музыкальный трек на Audio Track 1

    Открыть Audio panel:

    Справа появится панель с настройками аудио

    Найти слайдер Volume:

    По умолчанию: 100% (0 dB)

    Уменьшить громкость:

    Для музыки: Передвинуть слайдер до 30-40% (примерно -12 до -18 dB)

    CapCut показывает проценты, не dB:
        100% = 0 dB (оригинальная громкость)
        50% ≈ -6 dB
        30% ≈ -12 dB
        20% ≈ -18 dB

    Повторить для других элементов:

    Диалоги (Audio Track 2): Оставить 100% (0 dB) или слегка увеличить до 110-120% (+1 до +2 dB)

    SFX действия (Audio Track 4): 50-60% (-6 до -10 dB)

    SFX фоновые (Audio Track 3): 20-30% (-18 до -12 dB)

    Проверить баланс:

    Воспроизвести участок с диалогом + музыкой + SFX

    Критерий: Диалог слышен чётко, музыка не мешает, SFX добавляют атмосферу

ДОПОЛНИТЕЛЬНАЯ ТЕХНИКА: Ducking (автоматическое понижение музыки при диалогах)

Ducking — когда персонаж говорит, музыка автоматически становится тише, после реплики — возвращается к исходной громкости.

CapCut: Функция Auto Ducking (в некоторых версиях)

DaVinci Resolve:

    Выбрать музыкальный трек
    Fairlight (аудио-страница) → Dynamics → Compressor
    Настроить Side-chain на диалоговую дорожку

Ручная альтернатива (CapCut):

    На музыкальном треке добавить keyframes (ключевые кадры):
        Момент начала диалога: Volume = 30%
        Момент окончания диалога: Volume = 50% (вернуть)
    CapCut создаст плавную анимацию громкости

ИНСТРУКЦИЯ: Fade In/Fade Out на музыке

Fade In — музыка плавно появляется (от тишины до нормальной громкости) в начале видео.

Fade Out — музыка плавно затихает в конце видео.

CapCut:

    Выбрать музыкальный трек
    Audio panel → Fade In (слайдер) → установить 1-2 секунды
    Fade Out (слайдер) → установить 2-3 секунды

Результат: Музыка не "врывается" резко, а мягко нарастает.
Шаг 9.8: Цветокоррекция и финальная полировка (опционально)

Действие: Применить цветокоррекцию для единого визуального стиля всех клипов.

ЗАЧЕМ: AI-генераторы видео (Блок #7) иногда создают клипы с разной цветовой температурой:

    Один клип теплее (оранжевый оттенок)
    Другой холоднее (синий оттенок) → При склейке выглядит несогласованно

РЕШЕНИЕ: Применить единую цветокоррекцию ко всем клипам.

МЕТОД 1: LUT (Look-Up Table) — простейший способ

LUT — предустановленный цветовой фильтр (аналог Instagram-фильтра, но профессиональный).

CapCut:

    Выбрать первый клип на Video Track 1

    Adjustments panel → Filters или LUTs

    Выбрать LUT из библиотеки:

    Для Cowboy Bebop + Bad Batch стиля:
        Искать LUT с названиями: "Cinematic", "Film", "Orange & Teal", "Moody"
        Примеры:
            "Cinematic Orange" — тёплые тона (оранжевый-коричневый)
            "Teal & Orange" — классический киношный контраст (синие тени, оранжевые светá)
            "Dark Moody" — приглушённые цвета, высокий контраст

    Применить LUT (клик на превью)

    Копировать LUT на все клипы:

    ПКМ на клипе с LUT → Copy → выделить все остальные клипы → ПКМ → Paste Adjustments

    Результат: Все клипы теперь имеют единый цветовой стиль

МЕТОД 2: Ручная цветокоррекция (для продвинутых)

DaVinci Resolve (профессиональный инструмент для цветокоррекции):

    Перейти на вкладку Color (внизу интерфейса)

    Выбрать клип

    Основные параметры:
        Lift (тени) — изменяет тёмные участки
        Gamma (средние тона) — изменяет средние участки
        Gain (света) — изменяет светлые участки
        Contrast (контраст) — разница между тёмным и светлым

    Для Cowboy Bebop стиля:
        Увеличить контраст (+10 до +20)
        Сдвинуть Lift в сторону синего (холодные тени)
        Сдвинуть Gain в сторону оранжевого (тёплые света)
        Немного снизить Saturation (насыщенность, -5 до -10) для "выцветшего" look

    Скопировать на все клипы: ПКМ на клипе → Copy Grade → выделить все → Paste Grade

ДОПОЛНИТЕЛЬНЫЕ ЭФФЕКТЫ (опционально):

Vignette (виньетирование) — затемнение по краям кадра.

CapCut: Adjustments → Effects → Vignette → Intensity (30-50%)

Зачем: Фокусирует внимание на центр кадра, добавляет драматизм.

Grain (зерно плёнки) — имитация плёночной текстуры.

CapCut: Effects → Film Grain → Amount (5-10%)

Зачем: Добавляет органичность (vs "слишком цифровой" вид AI-видео).

Sharpen (резкость) — увеличение чёткости.

CapCut: Adjustments → Sharpen (5-10%)

Зачем: AI-видео иногда слегка размыто → Sharpen компенсирует.

ВНИМАНИЕ: Не перебарщивать (>15% = артефакты, "хрустящий" вид).
Шаг 9.9: Добавление субтитров/титров (опционально)

Действие: Если нужны титры (opening credits, closing credits) или субтитры диалогов.

CapCut:

    Text panel (левая панель) → Add Text

    Выбрать стиль текста из библиотеки (или создать свой)

    Для opening credits:
        Текст: Название проекта / "A Film by [Your Name]"
        Шрифт: Bold, кинематографический (например, "Bebas Neue", "Montserrat Bold")
        Позиция: Центр экрана
        Анимация: Fade In (1 сек) → Hold (2 сек) → Fade Out (1 сек)

    Для субтитров диалогов:
        Текст: Реплика персонажа
        Шрифт: Простой, читаемый (Arial, Roboto)
        Позиция: Нижняя часть экрана (safe zone — не слишком близко к краю)
        Timing: Появление точно с началом реплики, исчезновение после конца
        Цвет: Белый с чёрной обводкой (или чёрный с белой обводкой) для читаемости на любом фоне

Шаг 9.10: Финальный просмотр и корректировка

Действие: Просмотреть весь проект от начала до конца, записать все проблемы, исправить.

ЧЕК-ЛИСТ ФИНАЛЬНОГО ПРОСМОТРА:

    Все клипы на месте (нет пропущенных кадров)
    Переходы между клипами плавные (нет резких "прыжков", если это не задумано)
    Диалоги синхронизированы с видео (голос совпадает с движением губ)
    Музыка не заглушает диалоги (диалоги чётко слышны)
    SFX синхронизированы с действиями (шаги, оружие звучат в момент действия)
    Нет тишины где должен быть звук (ambience играет на всех outdoor-сценах)
    Нет "дыр" в звуке (между клипами нет внезапной тишины)
    Цветовая гамма консистентна (клипы не сильно отличаются по цвету)
    Нет технических артефактов (чёрных экранов, заиканий)
    Общая длительность соответствует цели (1-2 мин или 3-5 мин)

Если нашли проблему:

    Записать таймкод (например, "0:01:23 — диалог отстаёт")
    Вернуться к этому моменту на таймлайне → исправить
    Повторить просмотр исправленного участка

Шаг 9.11: Экспорт финального видео

Действие: Render (рендер) проекта в финальный видеофайл MP4.

ИНСТРУКЦИЯ (CapCut):

    Кнопка Export (верхний правый угол)

    Настройки экспорта:

    Format: MP4 (универсальный, поддерживается везде)

    Resolution: 1920x1080 (Full HD)
        Если видео вертикальное (для TikTok/Instagram) → 1080x1920

    Frame Rate: Тот же, что в настройках проекта (24 или 30 FPS)

    Bitrate (качество):
        High (15-20 Mbps) — для YouTube, хранения ⭐ РЕКОМЕНДУЕТСЯ
        Medium (8-12 Mbps) — для соцсетей (Instagram, Facebook)
        Low (3-5 Mbps) — для быстрой загрузки (но видимая потеря качества)

    Codec: H.264 (стандартный, совместим с 99% платформ)
        Альтернатива: H.265 (HEVC) — меньший размер файла, но не все устройства поддерживают

    Название файла:

    Final_Anime_Project_v1.mp4

    Место сохранения:

    Папка Project/Final_Output/

    Нажать Export → дождаться рендера

Время рендера:

    1-2 мин видео → 5-15 минут рендера (зависит от ПК)
    3-5 мин видео → 15-40 минут

Прогресс-бар показывает процент завершения.

ИНСТРУКЦИЯ (DaVinci Resolve):

    Вкладка Deliver (внизу интерфейса)

    Render Settings:
        Format: MP4
        Codec: H.264
        Resolution: 1920x1080
        Frame Rate: 24 или 30
        Quality: Bitrate 15-20 Mbps (или "Best" preset)

    Output:
        Filename: Final_Anime_Project_v1.mp4
        Location: Project/Final_Output/

    Add to Render Queue → Render All

Шаг 9.12: Проверка финального файла

Действие: Открыть экспортированный MP4 файл, просмотреть полностью, убедиться что всё корректно.

ЧЕК-ЛИСТ ПРОВЕРКИ ФИНАЛЬНОГО ФАЙЛА:

    Файл открывается (не повреждён)
    Разрешение корректное (1920x1080)
    Нет "заиканий" или пропусков кадров
    Звук и видео синхронизированы (нет рассинхронизации)
    Качество приемлемое (нет сильного сжатия, пикселизации)
    Длительность соответствует ожиданиям
    Звук воспроизводится на всех устройствах (компьютер, телефон)

Если всё ✅ — проект завершён!
🛠 ЧЕК-ЛИСТ ИНСТРУМЕНТОВ ДЛЯ БЛОКА #9
Видеоредакторы (100% бесплатные)

✅ CapCut Desktop ⭐ — https://www.capcut.com (ЛУЧШИЙ для новичков, быстрый, простой)
✅ DaVinci Resolve 19 Free ⭐⭐ — https://www.blackmagicdesign.com/products/davinciresolve (профессиональный, цветокоррекция)
✅ Kdenlive — https://kdenlive.org (open-source, Windows/Mac/Linux)
✅ Shotcut — https://shotcut.org (легковесный, работает на слабых ПК)
Апскейл финального видео (опционально)

✅ Topaz Video AI (Trial, 30 дней) — https://www.topazlabs.com/topaz-video-ai (апскейл 720p→4K, после trial платно)
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ БЛОКА #9

    Все видеоклипы импортированы и выложены на таймлайн в правильном порядке
    Клипы обрезаны (удалены лишние статичные части в начале/конце)
    Длительность каждого клипа соответствует типу сцены (establishing 3-5 сек, action 1-3 сек, и т.д.)
    Переходы между клипами добавлены где нужно (Fade In/Out, Dissolve для смены глав)
    Музыка добавлена на Audio Track 1, выровнена с видео
    Диалоги добавлены на Audio Track 2, синхронизированы с моментами когда персонаж говорит
    SFX добавлены на Audio Track 3-5 (ambience, действия, удары), синхронизированы с визуальными действиями
    Звук сбалансирован: диалоги громче всего (-6 до -3 dB), музыка фоном (-18 до -12 dB), SFX между ними
    Fade In/Fade Out применены к музыке в начале и конце видео
    Цветокоррекция применена (LUT или ручная) для единого стиля всех клипов
    Финальный просмотр завершён, все проблемы исправлены
    Видео экспортировано в MP4 1080p с битрейтом 15-20 Mbps
    Финальный файл проверен (открывается, воспроизводится, звук синхронизирован)

(Продолжение: Специализированные блоки консистентности + Финальные секции следуют в следующем сообщении. Текущий объём: ~110,000 символов)

[⏸ ПРОДОЛЖЕНИЕ СЛЕДУЕТ]
You said: продолжи
продолжи
Copilot said: ## КОНСИСТЕНТНОСТЬ-БЛОК #1: МЕТОДЫ СОХРАНЕНИЯ КОНСИСТЕНТНОСТИ ПЕРСОНАЖЕЙ ###
КОНСИСТЕНТНОСТЬ-БЛОК #1: МЕТОДЫ СОХРАНЕНИЯ КОНСИСТЕНТНОСТИ ПЕРСОНАЖЕЙ
🎯 Цель блока

Изучить все доступные техники для поддержания консистентности персонажа (внешность, одежда, пропорции) на протяжении всех кадров проекта.
📚 Проблема консистентности персонажей

Суть проблемы: AI-генераторы изображений (DALL-E, Stable Diffusion, Midjourney) при каждой генерации создают новую интерпретацию текстового описания → персонаж выглядит по-разному на разных кадрах.

Примеры несоответствий:

    Кадр 1: Персонаж с коротким ёжиком → Кадр 2: Длинные волосы до плеч
    Кадр 1: Коричневая куртка → Кадр 2: Синяя куртка
    Кадр 1: Лицо 45-летнего → Кадр 2: Лицо 25-летнего

Последствие: Зритель не узнаёт персонажа → теряется нарратив.
🛠 Метод 1: Image-to-Image с базовым референсом (основной)

Принцип: Загружать базовый референс персонажа (из Блока #3) в каждую генерацию новой сцены как "якорь".

Уже применён в: Блоке #5 (Генерация сцен).

Эффективность: 70-85% консистентности (7-8 кадров из 10 узнаваемы).

Ограничения:

    Не работает на Bing Image Creator (нет img2img)
    Требует сервисы с img2img: Leonardo.AI, Playground AI, Tensor.Art

Оптимизация:

    Strength (сила референса): 0.5-0.7
        0.5 = больше свободы AI (разные позы, ракурсы) — риск потери деталей
        0.7 = жёсткая привязка (точнее черты) — риск статичности
    Рекомендация: 0.6 как баланс

🛠 Метод 2: Dual-Reference (базовый + сетка 3x3)

Принцип: Загружать 2 изображения одновременно:

    Базовый референс (полный рост, нейтральная поза)
    Сетка 3x3 с 9 ракурсами (из Блока #4)

Уже применён в: Блоке #5 (если сервис поддерживает multiple images).

Эффективность: 85-92% консистентности (8-9 кадров из 10).

Где работает:

    Leonardo.AI (Image Guidance позволяет 2+ изображения)
    Некоторые SD-интерфейсы (ComfyUI, Automatic1111 с расширениями)

Настройки:

    Базовый референс: Strength 0.6
    Сетка 3x3: Strength 0.3-0.4 (дополнительная подсказка)

Почему работает: AI видит персонажа с разных углов → понимает "анатомию" (форма носа сбоку, затылок, и т.д.).
🛠 Метод 3: LoRA (Low-Rank Adaptation) — продвинутый

Принцип: Обучить мини-модель (LoRA) на 10-20 изображениях базового персонажа → использовать эту модель для генерации всех сцен.

Эффективность: 95-99% консистентности (почти идеально).

Сложность: ⭐⭐⭐⭐⭐ (Требует технических навыков)

Требования:

    GPU с минимум 8GB VRAM (NVIDIA)
    Знание Python
    10-20 различных изображений персонажа (разные позы, освещение)
    Инструменты: Kohya_ss, EveryDream2

Процесс (упрощённо):

    Подготовка датасета:
        Создать 10-20 изображений персонажа (из Блока #5 или дополнительно сгенерировать)
        Требования: Разные позы, ракурсы, освещение; Одинаковая одежда, причёска

    Установка инструмента:
        Kohya_ss: https://github.com/bmaltais/kohya_ss
        Следовать инструкции установки (требует Anaconda, CUDA)

    Настройка параметров тренировки:
    Code

    Base model: sdxl_base_1.0 (или anime-модель, если anime-стиль)
    Rank: 16-32 (чем выше = точнее, но дольше)
    Steps: 1000-2000
    Learning rate: 1e-4

    Тренировка:
        Запустить скрипт → дождаться (2-6 часов на GPU)
        Результат: Файл .safetensors (~50-200 MB)

    Использование LoRA:
        В Stable Diffusion интерфейсе (ComfyUI/A1111): Load LoRA → выбрать файл
        В промпте добавить: <lora:character_name:0.8>
        Генерировать сцены — персонаж будет консистентен

Плюсы:

    Максимальная консистентность (99%)
    Можно генерировать бесконечно (не зависит от сервисных лимитов)

Минусы:

    Требует мощный ПК
    Сложная настройка (кривая обучения ~10-20 часов)
    Не работает с онлайн-сервисами (Bing, Leonardo) — только локальный SD

Рекомендация: Для опытных пользователей или проектов где критична консистентность (например, 100+ кадров, сериал).
🛠 Метод 4: IP-Adapter (Image Prompt Adapter) — средний уровень

Принцип: Расширение для Stable Diffusion, позволяющее использовать изображение как "стилевой промпт" для лица/персонажа.

Эффективность: 80-90% консистентности.

Сложность: ⭐⭐⭐ (Средняя — нужен локальный SD, но проще чем LoRA)

Где работает:

    ComfyUI (с расширением IPAdapter)
    Automatic1111 (с расширением IPAdapter)

Как использовать:

    Установить расширение:
        ComfyUI: https://github.com/cubiq/ComfyUI_IPAdapter_plus
        Следовать README инструкции

    Подготовить референс:
        Взять базовый референс персонажа (крупный план лица, если возможно)

    Настроить в интерфейсе:
        Load IPAdapter model
        Upload reference image (базовый референс)
        Weight: 0.7-0.9 (как сильно влияет на генерацию)

    Генерировать:
        Вставить обычный промпт сцены
        IPAdapter автоматически применит черты лица из референса

Плюсы:

    Проще чем LoRA (не нужна тренировка)
    Хорошо сохраняет черты лица
    Работает с любыми SD-моделями

Минусы:

    Требует локальный SD (не работает с онлайн-сервисами)
    Хуже сохраняет одежду (фокус на лице)

Рекомендация: Для практиков с локальным SD, когда нужна консистентность лиц без долгой тренировки LoRA.
🛠 Метод 5: Text Prompting — усиление текстовых промптов

Принцип: Если нет доступа к img2img (например, только Bing Creator), максимально усилить текстовое описание персонажа.

Эффективность: 50-65% консистентности (ниже img2img, но лучше чем ничего).

Техника: Промпт-анкеры

Стандартный промпт (слабая консистентность):
Code

Male bounty hunter, brown jacket, dark hair

❌ Результат: AI интерпретирует по-разному на каждой генерации.

Усиленный промпт с анкерами (улучшенная консистентность):
Code

CONSISTENT CHARACTER REFERENCE:
Male bounty hunter, EXACTLY 45 years old, 
EXACTLY short dark hair with GREY STREAKS at temples (CRITICAL FEATURE),
EXACTLY 5 o'clock shadow beard (no full beard, no clean shaven),
EXACTLY worn brown leather jacket with ORANGE SHOULDER PATCHES (KEY VISUAL IDENTIFIER),
EXACTLY dark grey tactical pants,
EXACTLY holstered blaster pistol on RIGHT hip (not left),
EXACTLY metal wrist device on LEFT arm with blue holographic display,
EXACTLY scuffed black combat boots.

THIS CHARACTER MUST LOOK IDENTICAL TO PREVIOUS IMAGES.
Same facial structure, same clothing colors, same proportions.
DO NOT change hair color, jacket color, or accessories between images.

Ключевые элементы усиления:
Элемент	Функция	Пример
EXACTLY	Усиление конкретности	EXACTLY 45 years old (не "middle-aged")
CRITICAL FEATURE	Маркировка ключевых черт	grey streaks (CRITICAL FEATURE)
KEY VISUAL IDENTIFIER	Уникальные детали	orange patches (KEY IDENTIFIER)
THIS CHARACTER MUST...	Явная инструкция	MUST LOOK IDENTICAL
DO NOT change...	Запреты	DO NOT change hair color
Конкретизация позиции	Избегает зеркалирования	blaster on RIGHT hip (not left)

Эффективность техники:

    С обычным промптом: 3-4 кадра из 10 консистентны
    С усиленным: 5-6 кадров из 10 консистентны
    Прирост: +50-100%

Ограничения:

    Всё равно ниже img2img методов
    Не гарантирует 100% совпадения
    AI может игнорировать часть инструкций

Рекомендация: Использовать ТОЛЬКО если нет доступа к img2img (Bing Creator). Если есть Leonardo/Playground — использовать img2img.
🛠 Метод 6: Face Swap (замена лиц постфактум)

Принцип: Генерировать сцены с любым персонажем → после генерации заменить лицо на лицо базового персонажа через AI face swap.

Эффективность: 90-95% консистентности лица (тело/одежда остаются из генерации).

Сложность: ⭐⭐ (Простая — веб-сервисы или скрипты)

Процесс:

Вариант A: Веб-сервис (для новичков)

    Сгенерировать сцену (даже если персонаж выглядит иначе)

    Открыть Face Swap сервис:

    ✅ Reface App (веб-версия)
        Ссылка: https://reface.ai (есть веб и мобильное приложение)
        Free tier: Ограниченный (несколько свапов бесплатно, потом платно)
        Как: Upload source face (базовый референс) + target image (сгенерированная сцена) → Swap

    ✅ Face Swapper by Icons8
        Ссылка: https://icons8.com/swapper
        Free tier: 5 свапов/день
        Процесс: Аналогично Reface

    Результат: Лицо персонажа из базового референса на теле из сгенерированной сцены

Вариант B: Open-source скрипт (для продвинутых)

✅ Roop (GitHub)

    Ссылка: https://github.com/s0md3v/roop
    Free tier: 100% бесплатно (open-source)
    Требования: Python 3.10, GPU желательна
    Процесс:
        Клонировать репозиторий
        Установить зависимости (pip install -r requirements.txt)
        Запустить: python run.py --source base_reference.png --target scene.png
        Результат: scene_swapped.png

Плюсы метода:

    Работает после генерации (не нужно бороться с AI во время)
    Лицо консистентно на 95%
    Можно применить к уже созданным кадрам ретроспективно

Минусы:

    Только лицо (одежда, тело могут отличаться)
    Иногда артефакты на границе лица/тела
    Веб-сервисы имеют лимиты (нужна ротация или локальный скрипт)

Рекомендация: Использовать как дополнение к img2img, если:

    Сгенерировали 10 кадров, 8 хороши, но у 2 лицо не то → face swap на эти 2
    Проект уже готов, но обнаружили несоответствия лиц → пост-обработка всех кадров

🛠 Метод 7: ControlNet (контроль позы/структуры)

Принцип: Задать AI не только изображение, но и структуру (позу скелета, edges контуров) → персонаж повторит позу референса, сохранив черты.

Эффективность: 85-95% (высокая при правильной настройке).

Сложность: ⭐⭐⭐⭐ (Требует локальный SD + понимание ControlNet)

Где работает:

    ComfyUI (с ControlNet нодами)
    Automatic1111 (с расширением ControlNet)
    Tensor.Art (упрощённая версия через веб-интерфейс)

Типы ControlNet для консистентности персонажей:
Тип ControlNet	Что контролирует	Когда использовать
OpenPose	Скелет (поза человека)	Нужно повторить позу референса
Canny Edge	Контуры объектов	Сохранить силуэт персонажа
Depth	Глубина сцены	Контроль пространственной структуры
Reference	Стиль изображения	Копирование общей эстетики

Пример: OpenPose для консистентности позы

Задача: Персонаж стоит с поднятой правой рукой. Нужно сгенерировать ту же позу, но другой фон.

    Подготовить референс:
        Взять базовое изображение персонажа в нужной позе

    Извлечь позу:
        В ComfyUI: Load ControlNet Preprocessor → OpenPose
        Результат: Скелетная схема (stickman) позы

    Генерировать с ControlNet:
        Load ControlNet model: control_v11p_sd15_openpose
        Input: Скелетная схема
        Prompt: Описание сцены с персонажем
        Weight: 0.7-1.0
        Generate

    Результат:
        Персонаж в точно той же позе, но в новой сцене
        Черты лица могут варьироваться (для лица комбинировать с IPAdapter)

Плюсы:

    Точный контроль позы (100% совпадение позы референса)
    Можно комбинировать несколько ControlNet (OpenPose + IPAdapter = контроль позы + лица)

Минусы:

    Требует локальный SD
    Сложная настройка (много параметров)
    Не подходит для новичков

Рекомендация: Для продвинутых пользователей, когда нужен максимальный контроль над позой персонажа.
📋 СРАВНИТЕЛЬНАЯ ТАБЛИЦА МЕТОДОВ
Метод	Эффективность	Сложность	Требует	Рекомендация
Image-to-Image (базовый)	70-85%	⭐	Онлайн-сервис с img2img	ОСНОВНОЙ для новичков
Dual-Reference (2 изображения)	85-92%	⭐⭐	Leonardo.AI или SD	РЕКОМЕНДУЕТСЯ если доступно
LoRA (обучение модели)	95-99%	⭐⭐⭐⭐⭐	GPU 8GB+, Python	Для опытных, долгие проекты
IP-Adapter	80-90%	⭐⭐⭐	Локальный SD	Для практиков с SD
Text Prompting (усиленный)	50-65%	⭐	Любой генератор	Резерв если нет img2img
Face Swap (пост-обработка)	90-95% (лицо)	⭐⭐	Веб-сервис или Python	Дополнение к основному методу
ControlNet	85-95%	⭐⭐⭐⭐	Локальный SD	Для продвинутых, точный контроль
🎯 РЕКОМЕНДУЕМАЯ СТРАТЕГИЯ (для проекта 50-80 кадров)

Этап 1: Базовая консистентность (Блоки #3-5)

    Метод: Image-to-Image с базовым референсом
    Инструмент: Leonardo.AI (основной) + Playground AI (резерв)
    Настройка: Strength 0.6
    Результат: 70-85% кадров консистентны

Этап 2: Усиление (если Этап 1 дал <70%)

    Метод: Dual-Reference (базовый + сетка 3x3)
    Инструмент: Leonardo.AI с Image Guidance
    Результат: 85-92% консистентны

Этап 3: Точечная коррекция (для оставшихся 10-15%)

    Метод: Face Swap для кадров где лицо не то
    Инструмент: Roop (локально) или Icons8 Face Swapper (онлайн)
    Результат: 95%+ финальная консистентность

Опциональный Этап 4: Максимум (если критична 99% консистентность)

    Метод: Обучить LoRA на базе 10-20 лучших кадров
    Инструмент: Kohya_ss
    Результат: 99% консистентности для всех будущих генераций

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ КОНСИСТЕНТНОСТЬ-БЛОКА #1

    Выбран основной метод консистентности (рекомендуется: Image-to-Image)
    Для основного метода настроены параметры (Strength 0.5-0.7)
    Протестированы 5-10 генераций с базовым референсом → консистентность ≥70%
    Если консистентность <70% → применён Dual-Reference или усиленные промпты
    Для проблемных кадров применён Face Swap (если нужно)
    Понимание ограничений выбранного метода (нет иллюзий что текст даст 99%)
    Определена стратегия на весь проект (какие методы использовать на каких этапах)

КОНСИСТЕНТНОСТЬ-БЛОК #2: КОНСИСТЕНТНОСТЬ ПОСЛЕДОВАТЕЛЬНОСТИ КАДРОВ
🎯 Цель блока

Обеспечить плавность перехода между кадрами (continuity) — чтобы действие логично продолжалось, а не "прыгало".
📚 Проблема continuity (непрерывности)

Суть: Каждый кадр генерируется независимо → между кадрами возникают разрывы:

    Кадр 1: Персонаж в куртке → Кадр 2: Куртка расстёгнута (хотя не было сцены расстёгивания)
    Кадр 1: Солнечный день → Кадр 2: Ночь (без объяснения)
    Кадр 1: Персонаж держит оружие в правой руке → Кадр 2: Оружие в левой

Последствие: "Киноляпы" (continuity errors) разрушают иммерсию.
🛠 Метод 1: Shot List детализация (превентивный)

Принцип: На этапе создания shot list (Блок #1) явно описать состояние объектов/персонажа в каждом кадре.

Стандартный shot list (слабая непрерывность):
Shot #	Description
10	Hunter stands in alley
11	Hunter walks forward

❌ Проблема: Не указано положение рук, одежды, аксессуаров → AI может изменить.

Детализированный shot list (сильная непрерывность):
Shot #	Description	Continuity Notes
10	Hunter stands in alley, hands at sides, jacket zipped, blaster in holster on right hip	State: Relaxed, weapon holstered
11	Hunter walks forward, hands still at sides (no change), jacket still zipped, blaster still holstered	Continuity: Same as Shot 10, only legs move

✅ Решение: Каждый кадр явно ссылается на предыдущий → промпты содержат continuity constraints.

Формула continuity notes:
Code

[Shot #X] Continuity Notes:
- Same as Shot [X-1]: [элементы без изменений]
- Changed from Shot [X-1]: [что изменилось и почему]
- New elements: [что появилось]

Пример:
Code

Shot #48: Hunter draws blaster
Continuity Notes:
- Same as Shot 47: Brown jacket, grey pants, facial hair
- Changed from Shot 47: Right hand now on blaster handle (was at side), blaster exiting holster
- New elements: Motion blur on right arm (indicates fast draw)

Применение: При создании промптов (Блок #5) копировать continuity notes → включать в промпт.
🛠 Метод 2: Video-to-Video (последовательная генерация)

Принцип: Вместо image-to-video для каждого кадра отдельно, использовать последний кадр предыдущего видео как first frame следующего видео.

Стандартный подход (слабая непрерывность):
Code

Image_10.png → [AI Video] → Video_10.mp4 (5 сек)
Image_11.png → [AI Video] → Video_11.mp4 (5 сек)

❌ Проблема: Video_10 и Video_11 не связаны → между ними может быть "прыжок" (персонаж телепортируется).

Video-to-Video подход (сильная непрерывность):
Code

Image_10.png → [AI Video] → Video_10.mp4 (last frame at 00:05)
                                ↓
                        Extract last frame → Image_10_end.png
                                ↓
Image_10_end.png + motion_prompt_11 → [AI Video] → Video_11.mp4

✅ Решение: Video_11 продолжает Video_10 (тот же кадр → плавное движение дальше).

Инструкция:

    Сгенерировать первый клип:
        Image_10.png + motion prompt → Video_10.mp4

    Экспортировать последний кадр:
        Открыть Video_10.mp4 в видеоредакторе (CapCut/DaVinci)
        Перейти к последнему кадру (00:05.00)
        Export Frame → сохранить как Image_10_end.png

    Использовать как базу следующего клипа:
        Загрузить Image_10_end.png в AI video generator
        Motion prompt для Shot #11 (но персонаж уже в конечной позиции Shot #10)
        Генерировать Video_11.mp4

    Повторить для всех кадров цепочки

Где работает:

    Kling AI (img2video принимает любое изображение)
    Runway Gen-3 (поддерживает video-to-video напрямую)
    Pika Labs (img2video)

Плюсы:

    Плавные переходы (нет телепортации)
    Консистентность движения (персонаж не "прыгает")

Минусы:

    Долго (нужно экспортировать кадры после каждого видео)
    Риск накопления артефактов (если Video_10 имеет искажение → оно перейдёт в Video_11)

Рекомендация: Использовать для ключевых последовательностей (5-10 связанных кадров экшена), не для всего проекта.
🛠 Метод 3: Storyboard Preview (визуальная проверка)

Принцип: Перед анимацией (Блок #7) выложить все изображения из Блока #5 в последовательности → визуально проверить continuity.

Инструмент: PureRef (из Блока #2)

Процесс:

    Открыть PureRef

    Разложить все изображения в порядке shot list:
    Code

    [Shot_01] [Shot_02] [Shot_03]
    [Shot_04] [Shot_05] [Shot_06]
    ...

    Визуальная проверка (для каждого соседнего кадра):

    Чек-лист continuity:
        Одежда одинакова? (цвет, застёжки, повреждения)
        Аксессуары на месте? (оружие, гаджеты, украшения)
        Окружение логично? (день/ночь, погода, локация)
        Поза переходит плавно? (если персонаж сидел, потом не должен стоять без вставания)
        Объекты в руках те же? (если держал меч, не должен вдруг держать пистолет)

    Если обнаружен разрыв:

    Пример:
        Shot_10: Куртка застёгнута
        Shot_11: Куртка расстёгнута

    Решения:
        A) Регенерировать Shot_11 с промптом "jacket zipped (same as previous shot)"
        B) Добавить промежуточный кадр Shot_10b: "Hunter unzips jacket" (микро-сцена)
        C) Изменить shot list (убрать необходимость расстёгивания, если не критично)

    Повторить проверку после исправлений

Рекомендация: Проводить в конце Блока #5 (до анимации) — проще исправить статичное изображение, чем переделывать видео.
🛠 Метод 4: 180-degree Rule (правило камеры)

Принцип: Киношное правило — камера не должна пересекать "ось действия" между соседними кадрами → зритель не теряет ориентацию.

Пример нарушения:
Code

Shot #20: Hunter talks to AI (Hunter on left, AI on right, camera facing them)
Shot #21: Reverse angle — suddenly Hunter on right, AI on left

❌ Результат: Зритель дезориентирован ("они поменялись местами?").

Правильное применение:

Ось действия: Воображаемая линия между двумя персонажами/объектами.

Правило: Камера остаётся по одну сторону оси в течение диалога/сцены.

Визуализация:
Code

        [AI]
         |
    (ось действия)
         |
      [Hunter]

Камера 1 (слева от оси):  🎥 → видим Hunter слева, AI справа
Камера 2 (справа от оси): 🎥 → видим Hunter справа, AI слева (НАРУШЕНИЕ, если сразу после Камеры 1)

Корректная альтернатива:
Камера 3 (слева, ближе):  🎥 → видим Hunter крупнее, но всё ещё слева от AI (OK)

Применение в AI-генерации:

В промптах shot list указывать:
Code

Shot #20: Wide shot, Hunter on LEFT side of frame, AI on RIGHT
Shot #21: Medium shot of Hunter, camera still on same side (Hunter left, AI right in background)
Shot #22: Close-up AI, camera STILL same side (AI right, Hunter left in background)

В motion prompts (Блок #7):
Code

Shot #20 motion: Camera static, characters face each other (Hunter left, AI right)
Shot #21 motion: Camera moves CLOSER to Hunter (not around), maintains left-right positions

Исключения (когда можно нарушать):

    Вставка установочного кадра (establishing shot) между диалогами — сбрасывает ось
    Намеренная дезориентация (персонаж теряется, хаос) — стилистический приём

Рекомендация: Следовать правилу в диалоговых сценах (Shots с двумя+ персонажами).
🛠 Метод 5: Match Cut (совпадение элементов)

Принцип: Переход между кадрами через общий визуальный элемент → создаёт плавность.

Типы:
A) Match on Action

Действие начинается в кадре A, завершается в кадре B.

Пример:
Code

Shot #45: Hunter reaches for door handle (hand moving toward handle)
Shot #46: Hand grabs handle, opens door (close-up of action)

Промпты:
Code

Shot #45:
Medium shot, Hunter's right hand reaching toward metal door handle, 
fingers extended, hand mid-motion (not yet touching)

Shot #46:
Close-up, Hunter's right hand gripping metal door handle, 
same hand position as end of Shot 45, handle turning

B) Graphic Match

Визуальная форма/цвет в кадре A совпадает с элементом в кадре B.

Пример:
Code

Shot #30: Close-up of circular holographic display (blue glow)
Shot #31: Wide shot of circular spacecraft window (same size/position in frame)

Промпты:
Code

Shot #30:
Extreme close-up, circular holographic interface, blue glow, centered in frame, 
diameter ~60% of frame width

Shot #31:
Wide shot, spacecraft window (circular, same size/position as Shot 30), 
stars visible through window, blue ambient light

Применение в AI-генерации:

    В shot list: Отметить пары кадров для match cut
    В промптах: Явно указать совпадающий элемент (форма, цвет, позиция)
    В генерации: Использовать img2img с низким strength (0.3-0.4) для Shot B, используя Shot A как референс → AI сохранит общие элементы

Рекомендация: Добавить 2-3 match cuts в проект → повышает кинематографичность.
📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ КОНСИСТЕНТНОСТЬ-БЛОКА #2

    Shot list содержит Continuity Notes для каждого кадра (что изменилось/не изменилось)
    Проведена визуальная проверка последовательности в PureRef (нет разрывов одежды, аксессуаров, окружения)
    Для ключевых последовательностей применён Video-to-Video (плавные переходы)
    180-degree Rule соблюдён в диалоговых сценах (камера не прыгает через ось)
    Добавлены 2-3 Match Cuts для плавности (совпадающие элементы между кадрами)
    Все обнаруженные continuity errors исправлены (регенерация кадров или добавление промежуточных)

КОНСИСТЕНТНОСТЬ-БЛОК #3: КОНСИСТЕНТНОСТЬ ОБЪЕКТОВ И СУБЪЕКТОВ
🎯 Цель блока

Обеспечить консистентность неодушевлённых объектов (оружие, транспорт, гаджеты) и второстепенных персонажей на протяжении проекта.
📚 Проблема объектной консистентности

Суть: AI генерирует объекты "с нуля" на каждом кадре → одно и то же оружие/транспорт выглядит по-разному.

Примеры:

    Кадр 10: Бластер серебристый с синими линиями → Кадр 20: Бластер чёрный с красными линиями
    Кадр 5: Космический корабль с 4 двигателями → Кадр 25: Тот же корабль с 2 двигателями
    Кадр 15: Робот-помощник с круглым корпусом → Кадр 40: Робот квадратный

Последствие: Зритель не узнаёт объекты, теряется нарратив.
🛠 Метод 1: Object Reference Library (библиотека объектов)

Принцип: Создать отдельные референсы для каждого ключевого объекта (как делали для персонажа в Блоке #3).

Процесс:

Шаг 1: Определить ключевые объекты

Из shot list выписать все объекты, которые появляются 2+ раза:

Пример (для Cowboy Bebop + Bad Batch проекта):
Code

Ключевые объекты:
1. Hunter's blaster pistol (появляется в Shots: 2, 15, 48, 55, 70)
2. Spaceship "Swordfish" (Shots: 1, 22, 80)
3. Holographic wrist device (Shots: 3, 20, 35, 60)
4. AI antagonist (robot) (Shots: 10, 30, 50, 75)

Шаг 2: Создать референс для каждого объекта

Промпт-формула для объекта:
Code

[Тип плана] of [объект],
[детальное описание: форма, цвет, материалы, уникальные детали],
[стиль из Блока #0],
clean white background,
object reference sheet quality,
high detail, 4K

ПРИМЕР ПРОМПТА (оружие):
Code

Close-up product shot of futuristic blaster pistol,
sleek design, silver-grey metallic body with blue energy lines along barrel,
rectangular grip with orange rubber texture, circular power cell (glowing blue) on left side of body,
angular muzzle with three vents, trigger guard integrated,
anime style blend of Cowboy Bebop and Star Wars aesthetics (tech-noir, realistic proportions),
clean white background, no hands holding it (standalone object),
studio lighting with soft shadows,
object reference sheet quality, all details visible,
high detail, 4K

ПРИМЕР ПРОМПТА (транспорт):
Code

Wide shot of futuristic single-pilot spacecraft,
compact design, white and blue color scheme, angular nose cone, 
two large main engines (glowing blue exhaust nozzles) on rear,
two smaller maneuvering thrusters on sides,
cockpit canopy (transparent) with pilot seat visible inside,
distinctive red stripe along fuselage,
anime style blend of Cowboy Bebop spaceship aesthetics (realistic tech, cel-shaded),
clean white background or space backdrop,
¾ angle view showing most details,
high detail, 4K, technical illustration quality

Шаг 3: Генерация

    Использовать те же инструменты что для персонажа (Leonardo.AI, Playground AI)
    Сгенерировать 4-9 вариантов → выбрать лучший
    Сохранить как Object_[название]_Reference.png (например, Object_Blaster_Reference.png)

Шаг 4: Добавить в PureRef

    Поместить все object references рядом с character references
    При генерации сцен (Блок #5) загружать соответствующий object reference вместе с character reference

Шаг 5: Применение в сценах

Метод A: Multi-Image Input (если сервис поддерживает)
Code

Inputs для Shot #48 (Hunter draws blaster):
1. Character_Base_Reference.png (strength 0.6)
2. Object_Blaster_Reference.png (strength 0.5)
3. Prompt: [описание сцены]

Метод B: Composite Prompting (если только text)
Code

Shot #48 Prompt:
Medium shot of Hunter drawing blaster pistol,
[персонаж описание],
blaster in right hand: EXACTLY same design as reference (silver-grey body, blue energy lines, orange grip, blue power cell on left side),
[остальная сцена]

CRITICAL: Blaster must match reference image EXACTLY. Same colors, same details.

🛠 Метод 2: Inpainting (замена объекта постфактум)

Принцип: Генерировать сцену → если объект выглядит неправильно → заменить только объект через inpainting, не трогая остальное.

Процесс:

Шаг 1: Идентификация проблемы
Code

Shot_48.png: Персонаж хорош, но бластер чёрный (должен серебристый)

Шаг 2: Подготовка маски

    Открыть изображение в редакторе (Photopea / GIMP)
    Выделить область объекта (бластер в руке)
    Создать маску (белый = inpaint область, чёрный = сохранить)

Шаг 3: Inpainting

Инструменты:

✅ Leonardo.AI (Canvas Editor с Inpaint)

    Upload изображение
    Mask area (кистью выделить бластер)
    Prompt: "Silver-grey blaster pistol with blue energy lines and orange grip, [описание из object reference]"
    Generate (inpaint only masked area)

✅ ClipDrop Cleanup (если просто удалить объект)

    https://clipdrop.co/cleanup
    Закрасить объект → удалить → вставить правильный объект в редакторе

✅ Stable Diffusion (локально, ComfyUI/A1111)

    Load image
    Inpaint mode
    Mask blaster
    Prompt + load object reference
    Generate

Шаг 4: Композитинг

    Сохранить inpaint результат
    Если нужна тонкая настройка (цвета/тени не совпадают) → Photopea: слои, blend modes, цветокоррекция

Рекомендация: Использовать для точечных исправлений (5-10 кадров где объект не тот), не для всех кадров.
🛠 Метод 3: ControlNet для объектов

Принцип: Аналогично ControlNet для персонажей (Консистентность-Блок #1), но для объектов.

Применимо для: Транспорт, роботы, крупные объекты со сложной формой.

Типы ControlNet:
Тип	Для чего	Пример
Canny Edge	Сохранение контуров объекта	Космический корабль (силуэт повторяется, детали варьируются)
Depth	Сохранение 3D-формы	Робот (объёмная структура)
Segmentation	Сохранение позиции объекта в кадре	Оружие в руке (всегда в том же месте руки)

Процесс (Canny Edge для корабля):

    Извлечь edges из object reference:
        Загрузить Object_Spaceship_Reference.png в ControlNet Preprocessor
        Тип: Canny Edge
        Результат: Контурная схема корабля

    Генерировать сцену с ControlNet:
        Input: Canny edges корабля
        Prompt: "Spaceship flying through asteroid field, [описание сцены]"
        ControlNet weight: 0.7-0.9
        Generate

    Результат:
        Корабль имеет тот же силуэт что референс
        Детали (цвета, текстуры) могут варьироваться слегка, но форма консистентна

Требования: Локальный Stable Diffusion (не работает на веб-сервисах).
🛠 Метод 4: Консистентность второстепенных персонажей

Проблема: Главный персонаж консистентен (Блок #3-4), но фоновые/второстепенные персонажи (враги, прохожие, NPC) выглядят по-разному.

Пример:
Code

Shot #30: Hunter сражается с врагом (враг в красной броне)
Shot #55: Hunter побеждает врага (враг вдруг в синей броне)

Решение A: Создать мини-референсы

Для каждого второстепенного персонажа с 2+ появлениями:

    Создать базовый референс (как для главного, но проще — 1 изображение, без сетки 3x3)
    Имя файла: Character_Secondary_[имя].png (например, Character_Secondary_Enemy01.png)
    При генерации сцен с этим персонажем — загружать его референс (strength 0.4-0.5, ниже чем главный)

Решение B: Текстовые анкеры (если персонаж появляется 2-3 раза)

Вместо создания референса, детально описать в промпте:
Code

Enemy soldier: male, age 30, bald head, red armor with white stripes, helmet with visor, holding rifle
THIS ENEMY MUST LOOK IDENTICAL in all shots (same armor color, same build)

Решение C: Copy-Paste в композитинге (для статичных фонов)

Если фоновый персонаж статичен (стоит, не двигается):

    Сгенерировать его один раз (Shot #10)
    В других кадрах (Shot #20, #30) — вырезать персонажа из Shot #10 → вставить в новую сцену через Photopea
    Adjust: тени, цветокоррекция под новое освещение

Рекомендация:

    Главные персонажи → полный референс + сетка 3x3 (Блок #3-4)
    Второстепенные (3+ появления) → базовый референс
    Эпизодические (1-2 появления) → текстовые анкеры

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ КОНСИСТЕНТНОСТЬ-БЛОКА #3

    Составлен список ключевых объектов (оружие, транспорт, гаджеты) с 2+ появлениями
    Создан object reference для каждого ключевого объекта (сохранён в References/Objects/)
    Object references добавлены в PureRef рядом с character references
    При генерации сцен (Блок #5) object references загружаются вместе с character (если сервис поддерживает)
    Для проблемных кадров применён inpainting (замена неправильных объектов)
    Второстепенные персонажи обработаны: либо мини-референсы, либо детальные текстовые анкеры
    Консистентность объектов проверена визуально в PureRef (объекты узнаваемы на всех кадрах)

КОНСИСТЕНТНОСТЬ-БЛОК #4: КОНСИСТЕНТНОСТЬ ДИЗАЙНА И ЦВЕТОВОЙ ПАЛИТРЫ
🎯 Цель блока

Обеспечить единообразие визуального стиля всего проекта: цветовая гамма, освещение, художественный стиль, детализация.
📚 Проблема визуальной несогласованности

Суть: AI-генераторы могут создавать кадры разного качества/стиля даже при одинаковых промптах:

    Кадр 1: Приглушённые цвета (Bebop aesthetic) → Кадр 10: Яркие насыщенные цвета (anime modern)
    Кадр 5: Детализированный фон → Кадр 15: Размытый фон
    Кадр 20: Тёплое освещение (оранжевое) → Кадр 30: Холодное (синее)

Последствие: Проект выглядит как "сборная солянка", а не цельное произведение.
🛠 Метод 1: Color Palette Definition (определение палитры)

Принцип: Зафиксировать 3-5 основных цветов проекта → использовать их во всех промптах.

Процесс:

Шаг 1: Извлечение палитры из стилевых референсов

Использовать инструменты для анализа цветов изображения:

✅ Adobe Color (бесплатно)

    Ссылка: https://color.adobe.com/create/image
    Процесс:
        Upload один из стилевых референсов (из Блока #2)
        Adobe автоматически извлечёт 5 доминирующих цветов
        Получить HEX-коды (например, #8B4513, #1E3A5F)

✅ Coolors.co (Image Picker)

    Ссылка: https://coolors.co/image-picker
    Процесс: Аналогично Adobe Color

✅ Canva Color Palette Generator

    Ссылка: https://www.canva.com/colors/color-palette-generator/
    Процесс: Upload изображение → получить палитру

Шаг 2: Документирование палитры

Создать файл Color_Palette.txt в папке Project/:
Code

PROJECT COLOR PALETTE
Style: Cowboy Bebop + Bad Batch

PRIMARY COLORS (use in all prompts):
1. #8B4513 — Saddle Brown (jacket, warm tones)
2. #4A4A4A — Charcoal Grey (pants, shadows)
3. #FF8C42 — Vibrant Orange (accents, patches, neon signs)
4. #1E3A5F — Deep Navy Blue (night sky, shadows)
5. #87CEEB — Sky Blue (highlights, holographic displays)

USAGE RULES:
- Clothing: Browns (#8B4513) + Greys (#4A4A4A) + Orange accents (#FF8C42)
- Environment: Deep blues (#1E3A5F) + Orange/blue neon (#FF8C42, #87CEEB)
- Lighting: Warm (orange-tinted) for indoor, Cool (blue-tinted) for outdoor night

FORBIDDEN COLORS:
- Bright pure reds (#FF0000) — too vibrant for Bebop aesthetic
- Neon greens (#00FF00) — wrong genre
- Pastels — too soft for tech-noir

Шаг 3: Включение в промпты

Стандартный промпт (без палитры):
Code

Medium shot of Hunter in alley, brown jacket, dark pants

❌ Проблема: AI может сделать "brown" = светло-коричневый или тёмный, "dark pants" = чёрный или серый.

Промпт с палитрой:
Code

Medium shot of Hunter in alley,
wearing saddle brown leather jacket (HEX #8B4513), charcoal grey pants (HEX #4A4A4A), vibrant orange shoulder patches (HEX #FF8C42),
color palette: muted browns, greys, orange accents,
environment: deep navy blue night sky (HEX #1E3A5F), neon signs in orange and sky blue tones

✅ Решение: AI знает точные цвета → консистентная палитра.

Шаг 4: Проверка в PureRef

    Выложить все сгенерированные изображения (из Блока #5) в PureRef
    Визуально оценить: Цвета совпадают?
    Если кадр выбивается (слишком яркий/другая гамма) → регенерировать с усилением палитры в промпте

🛠 Метод 2: LUT Application (цветокоррекция через LUT)

Принцип: Применить одинаковый цветовой фильтр (LUT) ко всем кадрам в пост-продакшене (Блок #9).

Уже описано в: Блоке #9, Шаг 9.8 (Цветокоррекция).

Дополнение здесь: Создание кастомной LUT

Если готовые LUTs не дают нужного стиля → создать свою:

Процесс (DaVinci Resolve):

    Выбрать эталонный кадр:
        Из всех сгенерированных изображений выбрать 1 кадр с идеальной цветовой гаммой
        Например, Shot_015_Hunter_Face.png — идеальный баланс коричневого/синего

    Открыть в DaVinci Resolve:
        Импортировать эталонный кадр
        Перейти на вкладку Color

    Настроить цветокоррекцию вручную:
        Adjust Lift (тени), Gamma (средние тона), Gain (света)
        Цель: Достичь желаемой палитры
        Пример для Bebop:
            Lift: Сдвинуть в сторону синего (+10 blue)
            Gain: Сдвинуть в сторону оранжевого (+15 orange)
            Saturation: -10 (приглушить)

    Экспортировать LUT:
        ПКМ на ноде цветокоррекции → Export LUT → .cube формат
        Имя файла: Bebop_BadBatch_LUT.cube

    Применить ко всем кадрам:
        Импортировать все остальные изображения
        Load LUT → выбрать Bebop_BadBatch_LUT.cube
        Apply to All clips

Результат: Все кадры теперь имеют идентичную цветовую гамму как эталонный кадр.

Рекомендация: Комбинировать с Методом 1 (палитра в промптах) для максимальной консистентности:

    Промпты задают базовые цвета (80% правильно)
    LUT корректирует оставшиеся 20% расхождений

🛠 Метод 3: Lighting Consistency (консистентность освещения)

Проблема: Один кадр ярко освещён, следующий тёмный (хотя та же локация/время суток).

Решение: Lighting Notes в shot list

Добавить колонку в shot list:
Shot #	Description	Lighting
10	Hunter in alley	Night, neon signs (blue/orange glow), backlit, rim light on character
11	Hunter walks forward	Same as Shot 10: night, neon, backlit
12	Hunter enters building	Change: Indoor, warm overhead lights (yellow-orange), frontal key light

В промптах:
Code

Shot #10:
[описание сцены],
lighting: night scene, primary light sources are neon signs (blue and orange glow),
character backlit by neon sign creating rim light effect,
soft fill light on face from ambient neon,
cinematic moody lighting, high contrast

Shot #11:
[описание сцены],
lighting: SAME AS SHOT 10 (night, neon signs, backlit, rim light),
consistent illumination

Shot #12:
[описание сцены],
lighting: indoor scene, warm overhead fluorescent lights (yellow-orange color temperature),
frontal key light on character, minimal shadows,
different from outdoor (transition from cold blue neon to warm yellow indoor)

Ключевые параметры освещения для консистентности:
Параметр	Что указывать	Пример
Time of day	Day / Night / Dawn / Dusk	Night (consistent for outdoor scenes 1-20)
Light sources	Neon, sun, lamp, fire	Neon signs (blue/orange)
Direction	Front, back, side, top	Backlit (light behind character)
Quality	Hard / Soft	Soft (diffused by fog/rain)
Color temperature	Warm (orange) / Cool (blue)	Cool blue (tech-noir night)

Рекомендация: Группировать сцены по освещению:

    Сцены 1-30: Outdoor night, neon → одинаковое освещение
    Сцены 31-50: Indoor, warm lights → другое освещение
    Сцены 51-80: Final battle, dramatic red emergency lights → третий тип

🛠 Метод 4: Style Consistency Check (проверка стилевой согласованности)

Принцип: Периодически проверять что все кадры соответствуют выбранному стилю из Блока #0.

Чек-лист стилевой консистентности:

Для Cowboy Bebop + Bad Batch стиля:

    Линии: Чёткие контуры (cel-shading) на всех кадрах? (не размытые edges)
    Пропорции: Реалистичные (не чиби, не SD-деформации)?
    Цветовая гамма: Приглушённая (не яркие saturated anime-цвета)?
    Детализация фона: Средняя-высокая (не упрощённый flat фон)?
    Освещение: Кинематографичное (не flat равномерное)?
    Анатомия: Угловатые черты лица (Bad Batch signature)?

Для Pixar стиля:

    3D look: Объёмность (не плоские 2D-формы)?
    Shaders: Глянцевые материалы (plastic-like)?
    Глаза: Большие выразительные (Pixar signature)?
    Цвета: Яркие насыщенные (не приглушённые)?
    Освещение: Мягкое ambient (не жёсткие тени)?

Процесс проверки:

    В конце Блока #5 (после генерации всех изображений):
        Выложить все кадры в PureRef
        Рядом положить оригинальные стилевые референсы (из Блока #2)

    Для каждого кадра:
        Визуально сравнить с референсом
        Поставить метку: ✅ (соответствует стилю) / ⚠️ (частично) / ❌ (не соответствует)

    Для кадров с ⚠️ или ❌:
        Определить проблему (например, "слишком яркие цвета")
        Регенерировать с усилением стилевых ключевых слов:
        Code

        [промпт],
        CRITICAL STYLE: muted color palette (NOT vibrant), cel-shaded with black outlines (NOT soft edges),
        realistic proportions (NOT chibi), cinematic lighting (NOT flat)

    Повторить проверку после регенерации

Критерий готовности: 90%+ кадров имеют ✅ (соответствие стилю).
🛠 Метод 5: Batch Style Transfer (пост-обработка стиля)

Принцип: Если несколько кадров выбиваются из стиля, но хороши по композиции/действию → применить style transfer постфактум.

Инструменты:

✅ DeepArt.io (веб, бесплатный лимит)

    Ссылка: https://deepart.io
    Процесс:
        Upload content image (проблемный кадр)
        Upload style image (стилевой референс из Блока #2)
        Generate → AI переносит стиль референса на кадр
    Лимит: 3-5 изображений/месяц бесплатно

✅ Artbreeder (Collage + Splicer modes)

    Ссылка: https://www.artbreeder.com
    Free tier: Ограниченный
    Процесс: Mix content + style изображения

✅ Neural Style Transfer (локально, Python)

    GitHub: https://github.com/lengstrom/fast-style-transfer
    Free: 100% (open-source)
    Требования: Python, TensorFlow, GPU желательна
    Процесс:
    bash

    python evaluate.py --checkpoint model.ckpt \
      --in-path problem_shot.png \
      --out-path fixed_shot.png

Ограничения:

    Не заменяет правильную генерацию (качество ниже)
    Иногда артефакты (замыленность, неестественные цвета)
    Рекомендация: Использовать для 2-5 проблемных кадров, не для всех

📋 ЧЕК-ЛИСТ ЗАВЕРШЕНИЯ КОНСИСТЕНТНОСТЬ-БЛОКА #4

    Определена цветовая палитра проекта (3-5 основных цветов с HEX-кодами)
    Палитра документирована в Color_Palette.txt и используется во всех промптах
    Создана кастомная LUT (опционально) или выбрана готовая для применения ко всем кадрам
    В shot list добавлена колонка Lighting (консистентность освещения между кадрами)
    Проведена визуальная проверка стилевой согласованности (90%+ кадров соответствуют выбранному стилю)
    Проблемные кадры регенерированы с усилением стилевых ключевых слов
    Для неисправимых кадров применён style transfer (если нужно)
    Все кадры визуально согласованы (цвет, освещение, стиль) при просмотре в PureRef

ВРЕМЕННАЯ ОЦЕНКА ПО БЛОКАМ
📊 Реалистичные сроки для проектов разной длины

Условия оценки:

    Работа 2-3 часа/день
    Использование бесплатных инструментов (с учётом дневных лимитов)
    Средний опыт работы с AI-инструментами

Проект 1-2 минуты (20-40 кадров)
Блок	Задача	Время	Примечание
#0	Выбор стиля	1-2 часа	Поиск референсов, тестирование промптов
#1	Сценарий + Shot List	3-5 часов	Итерации сценария, детализация shot list
#2	Сбор референсов	1 час	Быстрый этап
#3	Базовый персонаж	2-3 часа	10-20 генераций для идеального варианта
#4	Карта консистентности (3x3)	2-3 часа	5-10 попыток для хорошей сетки
#5	Генерация 20-40 изображений	3-5 дней	По 8-15 кадров/день (лимиты Leonardo 150 токенов + Playground 500)
#6	Апскейл + очистка	3-4 часа	Batch в Upscayl (если GPU) или 2-3 дня онлайн (лимиты 5/день)
#7	Анимация 20-40 клипов	5-7 дней	Pixverse 20-30/день + Kling 6-8/день
#8	Звук (VO, музыка, SFX)	4-6 часов	Параллельно с другими блоками
#9	Монтаж	6-10 часов	Зависит от опыта в редакторе
Консистентность-блоки	Проверки и исправления	Встроены в основные блоки	+10-20% времени

ИТОГО для 1-2 минут: 12-15 календарных дней (2-3 часа работы/день)
Проект 3-5 минут (50-80 кадров)
Блок	Задача	Время	Примечание
#0	Выбор стиля	1-2 часа	Аналогично
#1	Сценарий + Shot List	5-8 часов	Больший объём
#2	Сбор референсов	1-2 часа	
#3	Базовый персонаж	2-3 часа	
#4	Карта консистентности	2-3 часа	
#5	Генерация 50-80 изображений	7-10 дней	Ротация Leonardo + Playground + Tensor + SeaArt
#6	Апскейл + очистка	6-8 часов	Batch обработка или 5-7 дней онлайн
#7	Анимация 50-80 клипов	10-14 дней	Pixverse (основной массив) + Kling (ключевые)
#8	Звук	6-10 часов	Больше диалогов, SFX
#9	Монтаж	10-15 часов	Длиннее timeline
Консистентность	Проверки	Встроены	+15-25% времени

ИТОГО для 3-5 минут: 20-25 календарных дней (2-3 часа работы/день)
Ускорение процесса (опции)
Метод	Экономия времени	Условия
Платные подписки	-40-50%	Leonardo Pro ($12/мес), Kling Pro ($10/мес) → больше генераций/день
Локальный Stable Diffusion	-30-40% на Блоке #5	GPU 8GB+, unlimited генерации
Упрощение сценария	-25-30%	Меньше кадров (30 вместо 50), простые сцены (без сложных экшенов)
Батчевая обработка	-20%	Upscayl (Блок #6), автоматизация промптов (Блок #5)
Команда 2 человека	-35-45%	Параллельная работа: один генерирует, другой монтирует
СТРАТЕГИЯ ИСПОЛЬЗОВАНИЯ БЕСПЛАТНЫХ ЛИМИТОВ
🎯 Цель: Сгенерировать 50-80 кадров за 10-14 дней без трат
Фаза 1: Генерация изображений (Блок #5)

Инструменты и лимиты:
Сервис	Лимит/день	Кадров/день	Ссылка
Leonardo.AI	150 токенов	~15-30	https://leonardo.ai
Playground AI	500 генераций	500	https://playgroundai.com
Tensor.Art	100 кредитов	~20-40	https://tensor.art
SeaArt	200 кредитов	~40-60	https://www.seaart.ai
Bing Creator	15 быстрых + unlimited медленных	~20-30	https://www.bing.com/images/create

ПЛАН (для 60 кадров):

День 1-2: Playground AI (основной массив)

    500 генераций/день × 2 дня = 1000 генераций
    С учётом регенераций (3-4 попытки/кадр) = ~40-50 финальных кадров
    Статус: 40-50/60 готовы

День 3-4: Leonardo.AI (ключевые сцены)

    150 токенов/день × 2 дня = 300 токенов = ~30-40 кадров
    Использовать для close-ups, action scenes (где нужна консистентность)
    Статус: 60/60 готовы

Резерв (если нужно больше):

    Tensor.Art: 100 кредитов/день → +20 кадров
    SeaArt: 200 кредитов/день → +40 кадров

Ключевой принцип: Не пытаться генерировать всё на одном сервисе → ротация для максимального использования лимитов.
Фаза 2: Анимация (Блок #7)

Инструменты и лимиты:
Сервис	Лимит	Видео/день	Ссылка
Pixverse	300 кредитов/день	~20-30 (4 сек)	https://pixverse.ai
Kling AI	66 кредитов/день	~6-8 (5 сек)	https://klingai.com
Haiper AI	Unlimited (медленная очередь)	~10-15	https://haiper.ai
Luma	30 видео/месяц	~1/день (если распределить)	https://lumalabs.ai
Pika Labs	30 видео/месяц	~1/день	https://pika.art

ПЛАН (для 60 клипов):

День 1-5: Pixverse (основной)

    300 кредитов/день × 5 дней = 1500 кредитов = ~100-150 видео
    Достаточно для 60 клипов с запасом на регенерации
    Стратегия: Генерировать все wide shots, establishing shots, medium shots (80% кадров)

Параллельно День 1-7: Kling AI (ключевые)

    66 кредитов/день × 7 дней = 462 кредита = ~40-55 видео
    Стратегия: Генерировать close-ups, action scenes, эмоциональные моменты (20% кадров)

Резерв:

    Haiper AI: Unlimited (медленно) → для досъёмок если что-то не получилось
    Luma + Pika: 60 видео/месяц суммарно → для САМЫХ важных 5-10 кадров (кульминация)

Ключевой принцип: Pixverse (огромный лимит) = рабочая лошадка, Kling (качество) = ключевые моменты.
Фаза 3: Звук (Блок #8)

Лимиты:
Сервис	Лимит	Хватит на	Ссылка
ElevenLabs	10,000 символов/мес	~10-15 мин аудио	https://elevenlabs.io
Play.ht	12,500 символов/мес	~10-15 мин	https://play.ht
Suno AI	50 кредитов/день = 10 песен	20-30 треков/месяц	https://suno.ai
Udio	1200 кредитов/мес	~30-40 треков	https://udio.com
Freesound.org	Unlimited	Все SFX	https://freesound.org

ПЛАН:

Voice-Over:

    ElevenLabs: 10,000 символов = все диалоги для видео 3-5 мин
    Если не хватит → Play.ht: +12,500 символов
    Итого: 22,500 символов = ~20-30 минут аудио (избыток)

Музыка:

    Suno AI: 50 кредитов/день × 3 дня = 150 кредитов = 30 треков (избыток)
    Нужно только 3-4 трека → хватит за 1 день

SFX:

    Freesound.org: Unlimited → все звуки бесплатно

Ключевой принцип: Звук — наименее ограниченная фаза (лимитов хватает с запасом).
ИТОГОВАЯ СТРАТЕГИЯ (60 кадров за 14 дней)
Code

НЕДЕЛЯ 1:
День 1-2: Блоки #0-4 (подготовка, референсы, персонаж)
День 3-5: Блок #5 (генерация изображений: Playground + Leonardo)
День 6-7: Блок #6 (апскейл через Upscayl batch)

НЕДЕЛЯ 2:
День 8-12: Блок #7 (анимация: Pixverse + Kling параллельно)
День 13: Блок #8 (звук: ElevenLabs + Suno)
День 14: Блок #9 (монтаж в CapCut)

ПАРАЛЛЕЛЬНЫЕ ЗАДАЧИ:
- Консистентность-проверки: в конце каждой фазы (встроены)
- Звук можно начать с Дня 10 (пока генерируются видео)

Критические точки (где могут быть задержки):

    Блок #5 (изображения): Если консистентность <70% → нужны регенерации (+1-2 дня)
    Блок #7 (анимация): Если AI создаёт "слоу-моушен суп" → регенерации (+2-3 дня)

Буфер: +3-5 дней на непредвиденные регенерации → реалистичный срок = 17-20 дней.
ТИПИЧНЫЕ ОШИБКИ И РЕШЕНИЯ
❌ Ошибка 1: Слишком амбициозный сценарий

Проявление:

    Shot list на 120 кадров для видео 2 минуты
    Сложные экшен-сцены в каждом втором кадре
    Множество уникальных локаций (15+ разных мест)

Последствия:

    Не хватает бесплатных генераций
    Проект затягивается на месяцы
    Выгорание исполнителя

Решение:

A) Упрощение на этапе Блока #1:
Markdown

Чек-лист реалистичности сценария:

ДЛЯ ВИДЕО 1-2 МИН (для новичков):
- [ ] Кадров: 20-40 (не больше)
- [ ] Локации: 2-4 (не 15)
- [ ] Персонажи: 1-2 главных + макс 2-3 второстепенных
- [ ] Экшен-сцены: 1-2 (не весь проект)
- [ ] Диалоги: 5-10 реплик (не 30)

ДЛЯ ВИДЕО 3-5 МИН (для опытных):
- [ ] Кадров: 50-80 (не 120)
- [ ] Локации: 4-6
- [ ] Персонажи: 2-3 главных + 5-7 второстепенных
- [ ] Экшен-сцены: 3-5
- [ ] Диалоги: 15-25 реплик

B) Правило "Start Small, Scale Up":
Code

Первый проект: 30-секундный тизер (10-15 кадров)
→ Освоить pipeline, понять узкие места
→ Если успешно за 5-7 дней

Второй проект: 1-минутная сцена (20-25 кадров)
→ Углубить навыки консистентности
→ Если успешно за 10-12 дней

Третий проект: 2-5 минут (50-80 кадров)
→ Полноценный короткометраж

❌ Ошибка 2: Игнорирование карты консистентности (Блок #4)

Проявление:

    Пропуск создания сетки 3x3
    "Я справлюсь с одним базовым референсом"

Последствия:

    Консистентность персонажа падает до 40-50%
    Приходится регенерировать 50% кадров
    Трата лимитов впустую

Решение:

ОБЯЗАТЕЛЬНО создать:

    Базовый референс (Блок #3)
    Сетку 3x3 (Блок #4)
    Object references для ключевых объектов (Консистентность-Блок #3)

Исключение: Можно пропустить сетку 3x3 ТОЛЬКО если:

    Видео <30 секунд (5-10 кадров)
    Персонаж всегда показан с одного ракурса (только анфас)
    Используется LoRA (Консистентность-Блок #1, Метод 3)

❌ Ошибка 3: Расплывчатые motion prompts

Проявление:
Code

Motion prompt: "Character moves"

Последствия:

    AI создаёт "слоу-моушен суп" (всё двигается медленно и размыто)
    Непонятно что именно движется

Решение:

Формула конкретного motion prompt:
Code

[ЧТО движется: персонаж/камера/объект],
[ТИП движения: идёт/бежит/поворачивается],
[СКОРОСТЬ: медленно/быстро/резко],
[НАПРАВЛЕНИЕ: вперёд/влево/вверх],
[ЧТО СТАТИЧНО],
[ЭФФЕКТЫ: ветер/частицы/свет],
[ДЛИТЕЛЬНОСТЬ действия]

Пример исправления:

❌ Плохо:
Code

Character moves

✅ Хорошо:
Code

Character walks forward toward camera at steady pace (not running),
arms swing naturally at sides,
camera slowly dollies backward maintaining distance,
background remains static (buildings don't move),
wind gently blows jacket at 3-second mark,
total action duration: 5 seconds

❌ Ошибка 4: Не ротация AI-инструментов

Проявление:

    Использование только одного сервиса (например, только Leonardo.AI)
    Исчерпание 150 токенов/день → остановка работы

Последствия:

    Проект затягивается (ждём завтра для новых токенов)
    Потеря импульса

Решение:

Создать "матрицу инструментов":
Markdown

## МОИ АККАУНТЫ (tracking)

ИЗОБРАЖЕНИЯ:
✅ Leonardo.AI — username@email.com — 150 токенов/день
✅ Playground AI — username@email.com — 500 генераций/день
✅ Tensor.Art — username@email.com — 100 кредитов/день
✅ Bing Creator — account@outlook.com — 15 быстрых + unlimited медленных

ВИДЕО:
✅ Pixverse — username@email.com — 300 кредитов/день
✅ Kling AI — username@email.com — 66 кредитов/день
✅ Haiper AI — username@email.com — unlimited (медленно)

СТРАТЕГИЯ:
День 1: Leonardo (30 кадров) → кончились токены → переключаюсь на Playground (ещё 20 кадров)
День 2: Playground (50 кадров) → переключаюсь на Tensor.Art (ещё 20)

Правило: Никогда не зависеть от одного сервиса → всегда иметь 2-3 резервных.
❌ Ошибка 5: Музыка громче диалогов

Проявление:

    Финальное видео: музыка "забивает" диалоги
    Зритель не слышит что говорят персонажи

Последствия:

    Потеря нарратива
    Непрофессиональный вид

Решение:

Правило иерархии звука (Блок #9, Шаг 9.7):
Code

1. Диалоги: -6 до -3 dB (100-120% в CapCut) ← САМОЕ ГРОМКОЕ
2. SFX (действия): -10 до -6 dB (50-60%)
3. SFX (фон): -18 до -12 dB (20-30%)
4. Музыка: -18 до -12 dB (30-40%) ← САМОЕ ТИХОЕ (фон)

Проверка:

    Экспортировать черновик видео
    Просмотреть с закрытыми глазами → слышны ли диалоги чётко?
    Если нет → снизить музыку ещё на 10-20%

Дополнительно: Ducking (автоматическое понижение музыки при диалогах) — см. Блок #9.
❌ Ошибка 6: Не сохранили промпты

Проявление:

    Сгенерировали отличный кадр
    Через неделю нужен похожий → не помним промпт
    Тратим час на воссоздание

Последствия:

    Потеря времени
    Невозможность воспроизвести результат

Решение:

Создать файл All_Prompts_Archive.txt:
Markdown

# PROJECT PROMPTS ARCHIVE

## CHARACTER BASE (Блок #3)
Date: 2026-02-20
Tool: Leonardo.AI, Model: Leonardo Anime XL
Settings: Resolution 1024x1024, Guidance 7

Prompt:

[полный промпт базового персонажа]
Code


Result: Character_Base_Reference.png
Quality: 9/10, used as final


## SHOT #15 (Hunter Face Close-up)
Date: 2026-02-22
Tool: Kling AI
Settings: img2img, Strength 0.6, Duration 5 sec

Image Prompt: Character_Base_Reference.png + Character_Consistency_Map.png

Text Prompt:

[промпт Shot #15]
Code


Motion Prompt:

[motion prompt Shot #15]
Code


Result: Video_015_Hunter_Face.mp4
Quality: 8/10, minor artifacts но приемлемо


[...остальные промпты...]

Правило: Сохранять промпт сразу после успешной генерации (не откладывать).
❌ Ошибка 7: Регенерация деформированного лица вместо нового кадра

Проявление:

    Shot #25: Лицо персонажа деформировано (кривой нос, асимметричные глаза)
    Попытка исправить inpainting'ом / регенерациями → потрачено 10 попыток, результат плохой

Последствия:

    Трата лимитов (10 генераций = 100 токенов Leonardo)
    Потеря времени (2-3 часа)

Решение:

Правило "3 попытки":
Code

IF (кадр имеет критическую ошибку: деформированное лицо/анатомия):
  Попытка 1: Регенерировать с тем же промптом
  Попытка 2: Регенерировать с усиленным промптом ("anatomically correct, no deformities")
  Попытка 3: Регенерировать на другом сервисе (Leonardo → Playground)
  
  IF (после 3 попыток всё ещё плохо):
    → ПРИНЯТЬ РЕШЕНИЕ:
      A) Изменить ракурс кадра (вместо close-up сделать medium shot — лицо меньше видно)
      B) Убрать кадр из shot list (если не критичен)
      C) Заменить на альтернативную сцену
  
  НИКОГДА не тратить >5 попыток на один проблемный кадр

Почему работает: AI-генераторы имеют случайность (seed) → иногда кадр "проклят" и не получится хорошо при текущих условиях. Проще изменить условия.
ФИНАЛЬНЫЙ ЧЕК-ЛИСТ ВСЕГО ПРОЕКТА
📋 Перед финальным экспортом (Блок #9, Шаг 9.11)
ДОКУМЕНТАЦИЯ

    Сценарий сохранён (Project/Scenario.txt)
    Shot list заполнен с ссылками на файлы (Project/Shot_List.xlsx)
    Все промпты архивированы (Project/All_Prompts_Archive.txt)

ВИЗУАЛЬНАЯ ЧАСТЬ

    Собраны 3-7 стилевых референсов (References/Style_Refs/)
    Создан базовый персонаж (References/Character_Base_Reference.png)
    Создана карта консистентности 3x3 (References/Character_Consistency_Map_3x3.png)
    Созданы object references для ключевых объектов (References/Objects/)
    Сгенерированы ВСЕ изображения для shot list (Shots_Raw/ — оригиналы)
    Изображения апскейлены до ≥1920x1080 (Shots_Final/)
    Текстовые артефакты удалены
    Все изображения анимированы (Videos_Raw/)

КОНСИСТЕНТНОСТЬ

    Персонажи: 85%+ кадров — персонаж узнаваем (одежда, лицо, пропорции совпадают)
    Continuity: Нет разрывов между кадрами (одежда не меняется внезапно, объекты на месте)
    Объекты: Ключевые объекты (оружие, транспорт) консистентны (цвет, форма повторяются)
    Стиль: 90%+ кадров соответствуют выбранному стилю (Bebop/Pixar/Cyberpunk/и т.д.)
    Цветовая палитра: Палитра задокументирована, использована во всех промптах

АУДИО

    Все диалоги озвучены (Audio/Voice/)
    Голоса подобраны под персонажей (возраст, характер)
    Emotion tags применены (эмоции слышны в репликах)
    Создано 2-4 музыкальных трека (Audio/Music/)
    Музыка соответствует настроению сцен
    Собраны ВСЕ нужные SFX (Audio/SFX/ — минимум 10-20 звуков)
    SFX организованы по категориям (Ambience, Footsteps, Weapons, и т.д.)
    Для диалоговых close-ups применён lip-sync (опционально, Videos_Lipsync/)

МОНТАЖ

    Все видеоклипы импортированы и выложены на таймлайн в правильном порядке
    Клипы обрезаны (удалены статичные части в начале/конце)
    Длительность клипов соответствует типу сцены (establishing 3-5 сек, action 1-3 сек)
    Переходы добавлены где нужно (Fade In/Out, Dissolve для смены глав)
    Музыка добавлена, выровнена с видео, Fade In/Out применены
    Диалоги синхронизированы (голос начинается когда персонаж открывает рот)
    SFX синхронизированы с визуальными действиями (шаги, оружие)
    Звук сбалансирован: диалоги -6 до -3 dB, музыка -18 до -12 dB, SFX между ними
    Цветокоррекция применена (LUT или ручная) для единого стиля

КАЧЕСТВО

    Финальный просмотр завершён (просмотрели видео от начала до конца)
    Нет технических артефактов (чёрных экранов, заиканий, рассинхронизации звука)
    Нет continuity errors (одежда не меняется, объекты не пропадают)
    Диалоги чётко слышны (музыка не заглушает)
    Длительность соответствует цели (1-2 мин или 3-5 мин ±10%)
    Видео экспортировано в MP4 1080p, битрейт 15-20 Mbps

ФИНАЛЬНЫЙ ФАЙЛ

    Файл открывается без ошибок
    Разрешение корректное (1920x1080 или указанное)
    Звук и видео синхронизированы на всех устройствах (компьютер, телефон)
    Качество приемлемое (нет сильного сжатия, артефактов кодирования)

Если ВСЕ пункты ✅ — проект ГОТОВ к публикации!
ЗАКЛЮЧЕНИЕ
🎉 Вы завершили полный pipeline создания AI-видео!

Что вы теперь умеете:

    ✅ Планировать проект (сценарий, shot list, стилевые решения)
    ✅ Создавать консистентных персонажей (базовый референс + карта 3x3)
    ✅ Генерировать изображения с сохранением консистентности (img2img, промпт-техники)
    ✅ Анимировать статичные изображения (motion prompts, video-to-video)
    ✅ Проектировать звук (AI voice, AI музыка, SFX-библиотеки)
    ✅ Монтировать финальное видео (синхронизация, балансировка, экспорт)
    ✅ Поддерживать консистентность на всех уровнях (персонажи, объекты, стиль, цвет)

🚀 Следующие шаги

Первый проект (рекомендуется):

    Длина: 30-60 секунд
    Кадров: 10-20
    Цель: Освоить все этапы pipeline без перегрузки
    Срок: 7-10 дней

После успешного первого проекта:

    Масштабировать до 1-2 минут (20-40 кадров)
    Экспериментировать с разными стилями (из Блока #0)
    Изучать продвинутые техники (LoRA, ControlNet)

📚 Дополнительные ресурсы

Сообщества:

    r/StableDiffusion (Reddit) — обсуждение AI-генерации изображений
    r/AI_Art (Reddit) — AI-арт showcase
    Civitai.com — модели, LoRA, туториалы
    YouTube каналы: "Olivio Sarikas", "Nerdy Rodent", "Sebastian Kamph" (AI video tutorials)

Документация инструментов:

    Leonardo.AI Docs — https://docs.leonardo.ai
    Stable Diffusion Wiki — https://wiki.civitai.com
    DaVinci Resolve Manual — https://www.blackmagicdesign.com/support

✨ Финальный совет

"Консистентность > Качество"

Лучше иметь все кадры в едином стиле средней детализации, чем:

    10 супер-детализированных кадров
    30 средних кадров
    20 низкокачественных кадров

Зритель простит небольшие огрехи качества, но не простит хаос стилей.

Удачи в создании вашего AI-видео! 🎬🤖✨

[📌 КОНЕЦ МАТЕРИАЛА]

Метаданные:

    Формат: Pipeline с встроенными чек-листами, инструкциями, консистентность-блоками
    Целевая аудитория: Новички и начинающие практики
    Детализация: Полная (примеры промптов, инструменты с ссылками, разбор каждого шага)
    Объём: ~150,000 символов (полный материал)
    Версия: 2.0 EXTENDED
    Дата: 2026-02-25
