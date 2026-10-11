# Lyric Lens

A Claude Code plugin that reads song lyrics the way a good critic reads poetry: line by line, with every claim tied to the text.

| Command | What it does |
| --- | --- |
| `/lyric-lens:close-read` | A full reading of one song: thesis, motifs and metaphors, shifts in voice and tone, sound and form, the ambiguities in the ending, and a check against what the artist has said. |
| `/lyric-lens:challenge` | Tests your own interpretation against the text and gives a verdict: holds, holds as a second layer, partly holds, or does not hold. |
| `/lyric-lens:catalog` | Tracks one image, theme, or character across an artist's songs and shows how its meaning changes over time. |

You do not have to type the commands. Paste some lyrics and ask "what is the last verse really saying?", and Claude uses the correct skill.

## Install

In a Claude Code terminal session, type:

```
/plugin install lyric-lens --marketplace TheAntagonist2020/lyric-lens
```

Answer `y` to add the marketplace, then pick a scope.

From a shell, the same install is:

```bash
claude plugin install lyric-lens --marketplace TheAntagonist2020/lyric-lens
```

## Use

1. Copy the lyrics from an official source: the liner notes, the artist's site, or a verified transcription.
2. Run the command and paste the lyrics in the same message:

   ```
   /lyric-lens:close-read "Song Title" by Artist (2019)
   <paste the lyrics here>
   ```

   Add what you hear in the recording if you can: the tempo, the delivery, where the voice cracks, a beat switch. It makes the reading sharper.
3. Push back on any line:

   ```
   /lyric-lens:challenge I think the river in the bridge is the speaker's father, not the lover
   ```

4. Follow an image across a whole career:

   ```
   /lyric-lens:catalog Artist: the recurring image of rain
   ```

## How it reads

- **Every claim cites a line.** Lines are numbered from the first line you paste.
- **Every point has a label:** *[Text]* when the words support it directly, *[Context]* when it rests on a sourced fact, *[Inference]* when it is interpretation. You always know which is which.
- **Ambiguity stays open.** An ambiguous line gets at least 2 readings, the evidence for each, and an honest call on which one the text supports more.
- **The speaker is not the artist.** The "I" in a song is not assumed to be the songwriter unless a source supports it.
- **Sources have tiers:** the artist's own words first, then documented facts such as credits and samples, then other people's readings. With web search, Claude looks these up. Without it, Claude tells you what to check. Nothing is invented.
- **No summaries and no sermons.** No verse-by-verse paraphrase, and no moralizing about the content.
- **Genre-aware.** Rap is read for rhyme density, flow, and wordplay; country for the narrative turn; pop for how repetition changes the hook.

## Lyrics and copyright

Lyric Lens works from the lyrics you paste. It does not rebuild lyrics from memory, and it does not print the lyrics back to you. It quotes only the few words that a point needs.

## Example

[examples/danny-boy.md](examples/danny-boy.md) is a full reading of "Danny Boy" (Frederic Weatherly, 1913), a song in the public domain.

## Contribute

Issues and pull requests are welcome. Good contributions are genre notes for the craft toolkit (`skills/close-read/references/craft-toolkit.md`) and example readings of public-domain songs.

## License

[MIT](LICENSE)
