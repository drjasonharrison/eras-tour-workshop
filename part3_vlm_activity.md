# The Eras Tour of Computer Vision
## Era 3: The Vision-Language Era (Workshop Edition)

For the first time in this tour, you get an answer *with an explanation*. On your laptop, open
any free chat assistant that accepts image uploads (Claude, ChatGPT, Gemini — your choice), and
try this on the images below.

## The prompt

Use the same wording for each image so your results are comparable:

```
Look at this photo and answer in exactly this format, with nothing else:

PREDICTION: yes or no — is there a coffee mug visible anywhere in this image?
REASONING: one or two sentences on what visual evidence led to that answer.
```

## Try these five images

Download these from the `data/` folder in this repo (or grab them straight from GitHub):

1. `mugs/ambiguous_01.jpg` — a mug repurposed as a pen holder
2. `mugs/ambiguous_06.jpg` — a toy/miniature mug
3. `distractors/pitcher_01.jpg` — not a mug, but close
4. `distractors/travel_tumbler_01.jpg` — also not a mug, also close
5. `mugs/texture_context_06.jpg` — backlit, tricky lighting

## While you try it, think about

- **Is the reasoning actually consistent with the image**, even when the yes/no answer is right?
  A model can get lucky with a bad reason, or be wrong for an almost-right one.
- **Compare notes with your neighbor** if they used a different chat assistant than you did —
  did the answer change? Did the *reasoning* change?
- Which of the five images gave the vision-language model the most trouble? Was it the same one
  that gave the rule-based detector or the classifier trouble in Eras 1 and 2 — or a different
  one entirely?

## Bring one example to the group

Pick your most interesting result (a surprising success, a confident wrong answer, anything that
made you go "huh") — we'll go around the room before the AMA.
