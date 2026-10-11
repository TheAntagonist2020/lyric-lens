---
name: close-read
description: Close-read song lyrics like poetry. Gives a line-cited reading of a song's thesis, motifs and metaphors, shifts in voice and tone, sound and form, and ambiguous endings, then checks the reading against what the artist and credible sources have said. Use when the user asks what a song or a lyric means, wants lyrics analyzed or broken down, asks about subtext, metaphors, wordplay or double meanings, or pastes lyrics and asks about them.
argument-hint: "\"<song>\" by <artist>, then paste the lyrics"
---

# Close-read a song

Read the lyrics the way a good critic reads a poem: closely, line by line, with every claim tied to the text. The goal is insight the listener did not already have. A summary of what the song is "about" is not the goal.

The song to read: $ARGUMENTS

## 1. Get the text

- Work from the lyrics the user pastes. They are the text of record.
- If the user names a song but does not paste the lyrics, ask them to paste the lyrics from an official source: liner notes, the artist's site, or a verified transcription. Do not rebuild lyrics from memory. Recalled lyrics are often wrong, and one misquote can break a reading. If the user cannot paste them, you can discuss the song in general terms, but label every point that depends on exact wording as unverified.
- Also collect, if the user has it: the release year, the album, and what they hear in the recording (tempo, delivery, where the voice strains, production choices). Do not hold up the reading for these. Note what is missing and continue.
- If the user asks a specific question ("what does the last line mean?"), answer it first and keep the rest short.

## 2. Map the song before you write

Do this silently. Do not print the map.

- Number the lines from the first line of the pasted text. Do not count blank lines or section labels such as `[Chorus]`. Cite with these numbers (L1, L14-16), and tell the user once how you counted.
- Mark the sections: verse, pre-chorus, hook, bridge, outro.
- Find the speaker and the addressee in each section. Note every change of pronoun or tense.
- List the images and words that repeat. Note where each one comes back and how it changes.
- Note the rhyme scheme, changes in line length, and each place where a pattern breaks. A break in the pattern is often where the meaning is.

## 3. Write the reading

Use this structure, in the shape of [the report template](references/report-template.md). Scale the length to the song: a short song gets a short reading. Leave out a section if there is nothing real to say in it.

1. **Thesis.** 2-3 sentences. State what the song does or argues, not its topic. "A breakup song" is a topic. "The speaker forgives the other person in the verses and takes the forgiveness back in the hook" is a thesis.
2. **Motifs and metaphors.** Track each important image across the song. Say where it starts, how it changes, and what the change means. Separate a sustained metaphor from a passing image.
3. **Voice, tone, and perspective.** Compare the verses, the hook, and the bridge. Who speaks to whom? Where does the tone turn? Does the hook mean something different on its last repeat than on its first?
4. **Sound and form.** Rhyme, cadence, line length, enjambment, repetition. Include a device only if it changes the meaning. Do not list devices for their own sake. See [the craft toolkit](references/craft-toolkit.md).
5. **The ending.** Read the closing lines closely. For each ambiguous line, give at least 2 readings, the lines that support each one, and which one the text supports more. If the ambiguity looks deliberate, say so and say what it does. Do not force one answer.
6. **Context check.** If you have a web search tool, use it now, before you write this section: look first for the artist's own statements about the song and for documented facts such as credits and samples. Then compare the reading with what the artist and credible sources have said. Follow [the sources guide](references/sources.md). Show where the text and the stated intent agree and where they part.
7. **Open questions.** 1-3 lines worth arguing about. Invite the user to push back, and tell them they can test their own reading with `/lyric-lens:challenge`.

## Rules

- **Cite the line for every claim.** Use the line number and, if it helps, a fragment of a few words. A claim with no line is an opinion: support it or cut it.
- **Label confidence.** Tag each point: *[Text]* when the words support it directly, *[Context]* when it rests on a sourced fact outside the text, *[Inference]* when it is your interpretation. Most of a good reading is Inference. That is fine, as long as the label says so.
- **Keep quotes short.** Do not print the lyrics back to the user, in full or in long passages. Quote only the few words a point needs. The user already has the text.
- **The speaker is not the artist.** Do not assume the "I" is the songwriter. Use biography as context only when a source supports the link.
- **Never invent evidence.** No made-up interviews, quotes, annotations, samples, or credits. If you are not sure a fact is real, say so or leave it out.
- **No summary, no sermon.** Do not paraphrase the song verse by verse. Do not moralize about the content, and do not add disclaimers about themes such as drugs, violence, or sex. Read them as craft.
- **Respect the genre.** Read rap for rhyme density, flow, and wordplay; country for the narrative turn; pop for how repetition changes the hook. The craft toolkit has notes for each.
- **Be specific.** One sharp observation that the text proves is worth more than three broad ones.
- **Check your citations.** Before you send the reading, compare every line number you cite with your line map. A wrong number makes a correct point look false.

## Short mode

If the user asks for a quick take, give the thesis, the 3 strongest observations, and the most important ambiguity. The rules stay the same.
