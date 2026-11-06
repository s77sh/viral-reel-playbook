# reel-playbook

A [Claude Code](https://claude.com/claude-code) skill for writing short educational videos (Instagram Reels, TikTok, YouTube Shorts) that people watch to the end and that bring in clients, not just views.

It is built from the transcripts of seven creators' reels. Each rule links back to the reel it came from:

| Part | What it answers | Learned from |
|---|---|---|
| Step 0: be known for one thing | What should my channel be about, and how does it make money? | Sam Stoffel ([reel](https://www.instagram.com/reel/DeERlGvM9LK/)) |
| The three questions | Nobody's watching. Should I post more? (No: who's watching, why should they care, what will they remember?) | Elliott Vitzthum ([reel](https://www.instagram.com/reel/DfZnojzItNF/)) |
| Step 1: the funnel job | Is this video for reach, for follows or for clients? | Dan Martell ([reel](https://www.instagram.com/reel/DcL47JZiiu0/)) |
| Step 2: five watch-longer patterns | How do I open, and how do I stop people leaving at 15 seconds? | Chris Chung ([reel](https://www.instagram.com/reel/Dd6jg8FvvAS/)) |
| Step 3: make the frame work | Shock word, countdown timer, a setting that proves it, a follow ask that names a result; a cutaway every few seconds that shows the line being said | Sam Stoffel, Elliott Vitzthum |
| The truth format | I'm scared to post, or I froze on camera. Now what? | Benji Wilkins ([reel](https://www.instagram.com/reel/Ddkc7wwofQ1/)) |
| The look | Which fonts, colors and caption placement? | Kalyl ([reel](https://www.instagram.com/reel/DcBwAjvoEqI/)) |

One rule runs through all of it: **never invent a result to fit a pattern.** Every number, story and backdrop has to be real.

![fonts sample](fonts-sample.png)

## Install

Clone it into your personal skills folder, and it works in every project:

```bash
git clone https://github.com/s77sh/reel-playbook ~/.claude/skills/reel-playbook
```

Or put it in one project only, at `.claude/skills/reel-playbook/`.

## Use

Open Claude Code and ask in plain words. For example:

- "reel-playbook: write a 40-second script about [topic]"
- "Rehook this script, people drop off at 15 seconds"
- "Is this a top, middle or bottom of funnel video?"
- "Nobody watches my videos. Should I post more?"
- "What should I be known for?"
- "I froze on camera today, can I still post it?"
- "Which fonts should my captions use?"

Claude names the funnel stage, picks an opening pattern, adds a rehook around 15-20 seconds, and checks every claim before handing it back.

## Make it yours

Add a `personal.md` next to `SKILL.md` with your own rules: topics you won't touch on camera, your real results and examples, your voice notes, and font paths. The skill reads it first, and it overrides the general rules. It's in `.gitignore`, so it never gets pushed.

## Credits

The ideas belong to the creators linked above; this repo only summarizes and organizes them. Go follow them. The spotlight-effect research is Gilovich, Medvec and Savitsky (2000), *Journal of Personality and Social Psychology*.

**Fonts:**
- Impact and Snell Roundhand ship with the OS.
- Playfair Display is free (SIL Open Font License).
- Rocktown is free for personal use only; buy a commercial license before using it in posted videos.

No font files are included.

## License

MIT
