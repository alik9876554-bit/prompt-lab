# AI Animated Film — Prompt Engineering Experiment

This example demonstrates how a prompt can be gradually improved using different Prompt Engineering techniques.

The task: create a short animated film about a teenager who dreams of becoming an artist.

---

## 1. Bad Prompt

Придумай мне анимационный мультфильм про подростка.

### Problem

The prompt is too general.

It does not specify:
- the target audience;
- the story structure;
- the character;
- the visual style;
- the duration;
- the desired output format.

---

## 2. Improved Prompt

Придумай короткий анимационный мультфильм про подростка, который мечтает стать художником, но боится критики окружающих.

История должна быть эмоциональной, понятной подросткам 12–16 лет и иметь:

- начало;
- конфликт;
- кульминацию;
- счастливый финал.

Мультфильм должен длиться около 1–2 минут.

### Improvement

The prompt now provides more context, constraints and a clear goal.

---

## 3. Structured Prompt

### ROLE

Ты — профессиональный сценарист и режиссёр короткометражных анимационных фильмов.

### TASK

Создай сценарий короткого анимационного мультфильма.

### CONTEXT

Главный герой — подросток, который мечтает стать художником, но боится показать свои работы другим людям из-за страха критики.

### AUDIENCE

Подростки 12–16 лет.

### STYLE

Современная 3D-анимация, кинематографичная визуальная подача, эмоциональная атмосфера, выразительные персонажи.

### CONSTRAINTS

- длительность 60–90 секунд;
- 8 сцен;
- должна быть эмоциональная кульминация;
- минимум диалогов;
- история должна быть понятна без сложных объяснений;
- финал должен оставлять положительное впечатление.

### OUTPUT

Представь сценарий в таблице:

| Сцена | Что происходит | Эмоция | Диалог | Визуал | Камера |
|---|---|---|---|---|---|

После сценария кратко опиши визуальный стиль главного героя и окружающего мира.

### Improvement

The prompt is divided into clear sections, making the task easier to understand and the expected output more specific.

---

## 4. Few-shot Prompt

### ROLE

Ты — профессиональный сценарист и режиссёр короткометражной анимации.

### TASK

Создай 8 сцен для моего анимационного мультфильма.

### CONTEXT

Главный герой — подросток, который мечтает стать художником, но боится показать свои работы другим людям.

### AUDIENCE

Подростки 12–16 лет.

### EXAMPLE OF THE DESIRED FORMAT

**Сцена:** 1

**Что происходит:**  
Подросток сидит в своей комнате и рисует. Услышав шаги за дверью, он быстро прячет рисунок.

**Эмоция:**  
Неуверенность и страх.

**Диалог:**  
— Ты опять рисуешь?  
— Нет... просто делаю домашнее задание.

**Визуал:**  
Тёмная комната, мягкий свет от окна, крупный план рисунка, который герой пытается спрятать.

**Камера:**  
Медленный переход от общего плана комнаты к крупному плану рисунка.

---

Теперь создай остальные 7 сцен, используя такой же формат, уровень детализации и эмоциональный стиль.

История должна постепенно развиваться от страха героя к моменту, когда он решается показать своё творчество другим.

В финальной сцене герой должен понять, что неудача и критика не означают, что ему нужно отказаться от своей мечты.

### Improvement

The prompt includes an example of the desired output format.

This demonstrates few-shot prompting: instead of only describing what we want, we provide an example that the AI can follow.

---

# Experiment Summary

| Prompt Type | Main Technique | Expected Result |
|---|---|---|
| Bad Prompt | Minimal instruction | Generic result |
| Improved Prompt | Context + constraints | More relevant result |
| Structured Prompt | Organized instructions | More controlled result |
| Few-shot Prompt | Example of desired output | More consistent format and style |

## Prompt Engineering Progression

**Bad → Improved → Structured → Few-shot**

The experiment demonstrates how adding context, structure, constraints and examples can improve the quality and consistency of AI-generated results.
