# The Contrary Grimoire: Light Magic

A Week 10–11 Doodle by Mina. This interactive science spellbook uses red, green, and blue light to help learners explore additive color mixing.

## Run and play

Download index.html from this repository and open it in a modern browser. The HTML, CSS, and JavaScript are embedded in that one file; no installation or account is required. The hosted preview requires sign-in, so the downloadable file is the reliable version for the teaching team.

1. Explore two different nonzero RGB mixtures.
2. Discover the yellow, cyan, and magenta light recipes.
3. Predict what will create bright white light, test the prediction, and write an explanation in the field notes.

Moving the sliders changes the preview; clicking **Cast light** records an experiment. Download the field notes before refreshing or leaving the page.

## AI learning and design process

**AI tool:** ChatGPT, including coding assistance for the HTML, CSS, JavaScript, and rule tests.

Selected prompts from the actual conversation:

- “给我提供一些灵感” — I asked for ideas for a small expressive interaction.
- “我觉得魔法书不错，就按照这个做。我觉得可以结合一些教育背景，让咒语能结合一些科学知识” — I selected the magic book and asked to connect its spells with science and learning.
- “这个设计不错，按照它和作业要求制作” — I approved the RGB light-mixing concept and asked for an implementation aligned with the assignment.
- “很好玩，把魔法书画得更像书一点，表情也可以更生动” — After trying the prototype, I requested a more book-like appearance and more expressive reactions.

AI helped translate these choices into a working program and check the logic. My role was to choose and refine the concept, evaluate the experience, and ask for changes. The [full design, code logic, and reflection](https://docs.google.com/document/d/1pNFrh1aVkq7_J_-0aZYAW-BzLo6-P2ahjrfN5hYNn5M/edit) are in the accompanying Google Doc. The [actual AI conversation](https://chatgpt.com/share/6b021063-ade8-83ea-9da3-40d105cddb08?ogimg=plain) records the process.

## Reflection

I predicted that balanced red, green, and blue channels would produce white light. The experiment produced white light, supporting my prediction. No particular combination surprised me because I was already familiar with additive light mixing. This shifted my attention to how a new learner might notice the pattern instead of only following a recipe.

If I revised the book further, I would add more recipes, including intermediate hues and different brightness levels. Predicting and comparing a wider range of mixtures could help learners build intuition about how each RGB channel changes the resulting color.

## Scope

This is a simplified screen RGB model, not a calibrated optics simulation or a model of mixing paint. Slider percentages are screen channel settings, not measured physical light intensity. The glow and beams are decorative. See the University of Arizona's [Color Mixing](https://wp.optics.arizona.edu/oscoutreach/color-mixing/) outreach demonstration for the science background.
