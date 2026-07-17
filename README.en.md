# Fangyu Xiaohei: Put Content in Color. Make It Move.

🌐 **Language:** [中文](README.md) · [English](README.en.md)

`fangyu-xiaohei-character` is a reusable visual Skill for turning articles, ideas, project retrospectives, event workflows, product stories, and personal experiences into expressive Xiaohei scenes.

> Small black cat-eared characters wear different colored work shirts, enter a real-object scene, and seriously perform one strange but accurate physical task.

## Give It a Star

If you like character-driven visual storytelling, please support the project with a Star:

**[Star `fangyu-xiaohei-character`](https://github.com/fuxiworkspace-lgtm/fangyu-xiaohei-character)**

Stars help this character system grow with more clothing colors, scene anchors, and narrative patterns.

## What It Does

- Turns abstract ideas into concrete physical actions.
- Uses clothing colors as stable semantic roles instead of decorative color changes.
- Produces restrained 16:9 editorial scenes, collaborative scenes, 3:1 story scrolls, and 4:5 social cards.
- Includes character locking, semantic color routing, multi-character orchestration, prompt templates, visual anchors, and QA checks.
- Inherits the original Xiaohei Scenes discipline: real objects, physical contact, one core action, sparse handwritten labels, and generous whitespace.

## The Fixed Character Family

All characters share the same black cat-eared body:

- solid matte-black body
- almost-round oversized head
- two small triangular ears
- white oval eyes with tiny black pupils
- compact torso and thin short limbs
- blank, calm, serious expression
- no realistic animal details, no tail, no whiskers, no paw pads

The distinction comes from the work shirt, never from changing body color. Shirts are simple, matte, low-saturation, logo-free, text-free, and pattern-free.

## Five Shirt Roles

| Character | Shirt | Meaning | Typical action |
| --- | --- | --- | --- |
| Xiaohei | ink black | main narrative, default operator, everyday absurdity | pushing, carrying, sorting |
| Xiaohong | terracotta red | alarm, conflict, risk, emotional peak, China market up | pulling an alarm cord, blocking, bracing |
| Xiaolv | moss green | repair, recovery, connection, China market down | reconnecting, taping, supporting |
| Xiaolan | slate blue | systems, tools, data, AI workflows, rational operation | turning dials, calibrating, wiring |
| Xiaohuang | mustard yellow | opportunity, reminder, warm-up, launch, illumination | opening, lighting, handing over a clue |

Color is selected from the meaning of the input. It is never used only to make the image richer.

## Intelligent Character Routing

The Skill adds a routing layer before image generation. It decides:

1. Who is the main character and what single physical action do they perform?
2. Does the article actually require supporting characters?
3. What independent action does each supporting character perform?
4. What real object, cable, force, or result keeps the characters connected?
5. Who owns the visual center, and who belongs at the tool, force, obstacle, or result end?
6. Which colors are deliberately excluded, and why?

If the article has no clear multi-party relationship, the default is one Xiaohei. The Skill must never force all five characters into a lineup just to display the family.

Useful collaboration patterns include:

- **Xiaohei + Xiaohong:** current task meets a sudden risk or alarm.
- **Xiaolan + Xiaolv:** upstream system work flows into downstream repair through the same cable or machine.
- **Xiaohei + Xiaohuang:** the current task encounters a real opportunity that changes the next action.
- **Xiaolan + Xiaohong:** system operation meets an alert or failure.
- **Xiaohong + Xiaolv:** tension appears, then is physically repaired or stabilized.

Every character must touch an object and perform a necessary action. Characters must not stand beside the metaphor as mascots.

## Visual Anchors

These images are official quality and character anchors. They guide silhouette, shirt relationships, object realism, action clarity, and whitespace. They are not layouts to copy.

### Fixed Color Family

![The fixed Fangyu Xiaohei clothing family](assets/examples/color-character-family-cat-clothing.png)

The five characters keep the same black body and cat-ear silhouette while wearing black, red, green, blue, and yellow work shirts.

### Collaboration and Layout Anchors

![Red alarm scene](assets/examples/anchors/red-alert-16x9.png)

![Blue and green collaboration](assets/examples/anchors/blue-green-collaboration-16x9.png)

![Long-scroll color routing](assets/examples/anchors/colored-clothing-long-scroll-3x1.png)

![Yellow opportunity scene](assets/examples/anchors/yellow-opportunity-4x5.png)

## Output Modes

### Standard 16:9

One clear scene, one real main object, one core physical action, and usually one character. Use two characters only when the input contains a clear division of labor. Three is exceptional.

### 3:1 Story Scroll

For event workflows, project retrospectives, product evolution, and personal journeys. Use a winding route and 5-8 real-object nodes. Xiaohei stays as the narrative anchor; colors change only at real semantic turns.

### 4:5 Social Card

For a single strong moment such as an opportunity, alarm, repair, or emotional peak. Keep the same clothing-first character canon and avoid turning the card into a poster or infographic.

## Core Creative Rules

- Start from the reader's situation, not from a list of objects.
- Translate the idea into contact, force, pulling, blocking, repairing, dragging, or being affected by an object.
- The character must perform the core action; deleting the character should break the metaphor.
- Keep the expression blank, calm, serious, and slightly clumsy.
- Use short handwritten Chinese labels only when they sharpen the reading.
- Keep the background clean and light with restrained contact shadows.
- Preserve whitespace and object realism.
- Do not copy an anchor's exact object combination, spatial topology, pose, or label positions.

## Reference Files

- [`SKILL.md`](SKILL.md): complete Chinese execution workflow.
- [`SKILL.en.md`](SKILL.en.md): English execution workflow.
- [`references/xiaohei-character-lock.md`](references/xiaohei-character-lock.md): fixed character IP rules.
- [`references/character-routing.md`](references/character-routing.md): intelligent role selection, collaboration, continuity, and layout.
- [`references/color-characters.md`](references/color-characters.md): shirt semantics and color discipline.
- [`references/prompt-template.md`](references/prompt-template.md): standard and long-scroll prompt templates.
- [`references/qa-checklist.md`](references/qa-checklist.md): generation and delivery QA.
- [`assets/examples/`](assets/examples/): visual anchors and quality masters.

## Original Workflow Heritage

This Skill inherits the original [ian-xiaohei-scenes](https://github.com/helloianneo/ian-xiaohei-scenes) workflow and expressive constraints: Xiaohei + real objects + physical action + short Chinese labels + whitespace narrative. Fangyu Xiaohei changes the fixed character IP to a black cat-eared body with semantic colored work shirts; the original action logic, restraint, and scene discipline remain.

## License and Use

Use the repository as a reusable prompt and visual-system foundation. Keep the fixed character canon, credit the source when sharing derivatives, and do not turn the characters into unrelated mascots, factions, superheroes, or costume variants.
