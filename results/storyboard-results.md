# AI Storyboard Results

This file compares the results generated using four different prompting approaches.

## Task

Create a short animated film about a teenager who dreams of becoming an artist.

---

## 1. Bad Prompt Result

### Prompt

Придумай мне анимационный мультфильм про подростка.

### Result

Главный герой — подросток по имени Артём, который любит рисовать. 
Он мечтает стать художником, но сталкивается с трудностями. 
После нескольких неудач он не сдаётся и продолжает заниматься искусством.

### Evaluation

The result is understandable, but too generic.

**Problems:**
- weak character development;
- no clear visual direction;
- no detailed scene structure;
- no specific emotional climax.

---

## 2. Improved Prompt Result

### Prompt

Придумай короткий анимационный мультфильм про подростка, который мечтает стать художником, но боится критики окружающих.

### Result

Артём любит рисовать, но никому не показывает свои работы. 
Однажды он решает принять участие в школьной выставке...

### Evaluation

The result is more specific because the prompt contains:
- character motivation;
- conflict;
- target audience;
- story structure.

However, the visual style and output format are still not clearly defined.

---

## 3. Structured Prompt Result

### Result

The AI generated the story as a sequence of 8 scenes with information about:

- events;
- emotions;
- dialogue;
- visual environment;
- camera movement.

### Evaluation

The structured prompt provides much more control over the output.

The AI understands:
- what role it should play;
- what it needs to create;
- who the audience is;
- what limitations exist;
- how the final answer should be formatted.

---

## 4. Few-shot Prompt Result

### Result

The AI generated 8 scenes following the same structure as the provided example.

Each scene included:

- what happens;
- emotion;
- dialogue;
- visual description;
- camera direction.

### Evaluation

The few-shot prompt produced the most consistent output format.

The example helped the AI understand not only **what** information to provide, but also **how** that information should be presented.

---

# Final Comparison

| Prompt | Context | Structure | Example | Control |
|---|---|---|---|---|
| Bad | Low | No | No | Low |
| Improved | Medium | No | No | Medium |
| Structured | High | Yes | No | High |
| Few-shot | High | Yes | Yes | Very High |

## Conclusion

The experiment demonstrates that prompt quality can significantly affect the structure, relevance and consistency of AI-generated results.

The biggest improvements came from:

1. Adding context.
2. Defining constraints.
3. Structuring the instruction.
4. Providing an example of the desired output.
