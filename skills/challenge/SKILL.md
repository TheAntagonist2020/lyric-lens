---
name: challenge
description: Pressure-test an interpretation of song lyrics. The user offers their own reading of a line or a whole song, and Claude tests it against the text (its strongest form, the lines that support it, the lines that resist it), gives a clear verdict, and revises its own earlier reading if the user is right. Use when the user disagrees with a lyric analysis, proposes a counter-reading or a double meaning, asks "couldn't it also mean...", or wants a reading of a lyric stress-tested.
argument-hint: "<your reading of a line or of the song>"
---

# Challenge a reading

The user has a reading of a lyric. Test it honestly. Do not agree with it to be pleasant, and do not defend an earlier reading to save face.

The reading to test: $ARGUMENTS

If that is empty, use the user's latest message.

## Inputs

- **The reading** to test (above).
- **The lyrics.** Use the text already in the conversation. If there is none, ask the user to paste the section in question, with enough around it to judge the context.
- **Any earlier close reading** in the conversation. Keep its line numbers, so the citations stay consistent.

## Steps

1. **State the reading at its strongest.** Restate it in 1-2 sentences, in its best form. If it is vague, make it precise, and check with the user that you have it right.
2. **Find the support.** Cite the lines that support it, including lines the user did not mention.
3. **Find the resistance.** Cite the lines that work against it. Test the whole song: does the reading still work in the hook, the bridge, and the last lines? A reading that explains one line but breaks three others is weak.
4. **Check the context.** If a source bears on the reading, bring it in with its tier. See [the sources guide](../close-read/references/sources.md).
5. **Give a verdict.** Pick one and give the line-level reason:
   - **Holds:** the text supports it as well as the alternatives, or better.
   - **Holds as a second layer:** it works alongside another reading. Say whether the double meaning looks deliberate (the wording, the rhyme, or the placement points both ways) or accidental.
   - **Partly holds:** it works for some lines, not all. Name which.
   - **Does not hold:** the text resists it. Name the lines.
6. **Revise in the open.** If the user's reading is stronger than an earlier reading in this conversation, say so plainly and revise. If it is weaker, keep the earlier reading and give the reason.
7. **End with one sharper question:** the next thing worth testing.

## Rules

- Use the same evidence rules as `/lyric-lens:close-read`: cite lines, label points [Text], [Context], or [Inference], keep quotes to a few words, and invent nothing.
- Weigh the argument, not the person. The user's confidence is not evidence, and neither is yours.
- Do not split the difference by reflex. "Both readings work" is a verdict only when the text supports both.
