# Клипы Google Flow

Стандарт: `knowledge/google_flow_guide.md` §3–4. Писать только после готового `02_vera_costume_reference_prompt.md`.
Модель по умолчанию: Veo 3.1 Fast · Ingredients · 9:16 · 8 с (ingredients у Veo — только 8 с; 10 с — только Omni Flash; Veo Quality — без ingredients).

**Как прикреплять референсы (для каждого клипа):** режим Ingredients → прикрепить из проекта персонажа `Vera EPNN` (если создан в Characters) **или** лицо (`vera_face_reference.png`) + костюмный кадр (`refs/costume.png`); + локацию при необходимости. Не более 3 ingredients. Листы A/B не прикреплять. В промпте заменить метки `@…` на имена, которые Flow показывает после ввода `@`.
Рабочие метки: `@vera_face`, `@vera_EPNN_costume`, `@loc_…` (соответствие — в `09_continuity.md`).

| № | Таймкод | Длит. | Модель/режим | Фраза | План |
|---|---|---|---|---|---|
| 01 | 0:00–0:0_ | 8 с | Veo 3.1 Fast · Ingredients | | |

---
## Клип 01
1. **Номер / длительность / таймкод:** 01 · 8 с (в монтаже 0:00–0:0_) · модель/режим: ___
2. **Цель и эмоция:**
3. **Фраза озвучки:** «…»
4. **Референсы (что прикрепить):** REF_CHARACTER_FACE (`@vera_face`), REF_EPISODE_COSTUME (`@vera_EPNN_costume`) — или персонаж `@Vera EPNN`; REF_LOCATION (`@loc_…`); REF_PREVIOUS_SHOT — только в режиме Frames
5. **Промпт:**
```
[SCENE ROLE] …
[REFERENCES] Use @vera_face as the exact identity and @vera_EPNN_costume as the exact outfit of the woman (Vera). Keep her face, age, eye shape, grey-green eyes, mole under the eye, freckles, dark-brown shoulder-length wavy hair and natural adult proportions identical.
[SUBJECT & ACTION] …
[SETTING & ERA] …
[BACKGROUND] …
[CAMERA] … vertical 9:16 composition …
[LIGHT & PALETTE] …
[START/END] Starts with … Ends with …
[AUDIO] She does not speak; no dialogue; natural ambient sound: …
[STYLE] Semi-realistic cinematic 3D/2.5D animation with a subtle painterly texture, natural adult proportions, expressive but realistic facial acting, detailed materials (skin texture, wool, linen, leather, wood, stone, metal, smoke, snow, mud), natural motivated lighting, atmospheric depth, historically plausible props and architecture. Not cartoonish, not childlike, not photorealistic. No on-screen text, no subtitles, no logos, no watermarks.
[AVOID] No text, no logos, no watermarks, no extra limbs or fingers, no face changes, no outfit changes, no modern objects, no chaotic camera.
```
6. **Камера:**
7. **Действие Веры / фон:**
8. **Исторические детали, свет, атмосфера:**
9. **Начало / конец для склейки:**
10. **Риски и запасной вариант** (тоже полный самодостаточный промпт: меньше действия, статичнее камера):
```
(полный упрощённый промпт со всеми блоками, включая [REFERENCES], [STYLE], [AVOID])
```
