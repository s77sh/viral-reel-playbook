# Claude Code skill for Instagram Reels hooks, TikTok and YouTube Shorts scripts

I built **viral-reel-playbook** from the transcripts of six reels by six creators. It's a free [Claude Code](https://claude.com/claude-code) skill for Reels, TikTok and Shorts scripts.

**The aim is videos people watch to the end** and that bring in clients. Each rule links back to the reel it came from:

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

Clone it into your personal skills folder and it works in every project:

```bash
git clone https://github.com/s77sh/viral-reel-playbook ~/.claude/skills/viral-reel-playbook
```

Or put it in one project only, at `.claude/skills/viral-reel-playbook/`.

## Use

Open Claude Code and ask in plain words. Here are a few:

- "viral-reel-playbook: write a 40-second script about [topic]"
- "Rehook this script, people drop off at 15 seconds"
- "Is this a top, middle or bottom of funnel video?"
- "Nobody watches my videos. Should I post more?"
- "What should I be known for?"
- "I froze on camera today, can I still post it?"
- "Which fonts should my captions use?"

Claude names the funnel stage and picks an opening pattern. Then it adds **a rehook around 15 to 20 seconds** and checks every claim before handing it back.

## Make it yours

Add a `personal.md` next to `SKILL.md` with the topics you won't touch on camera, your real results and your font paths. **The skill reads it first**, and it's gitignored.

## Credits

**The ideas belong to the creators linked above.** This repo only sorts them into steps, so go follow them.

The spotlight-effect research is Gilovich, Medvec and Savitsky (2000), *Journal of Personality and Social Psychology*.

| Font | License |
|---|---|
| Impact, Snell Roundhand | Ship with the OS |
| Playfair Display | Free (SIL Open Font License) |
| Rocktown | Free for personal use only: buy a commercial license before posting videos with it |

No font files are included.

## FAQ

### What is a Claude Code skill?

A folder Claude Code loads by itself when your request matches it. Ask for a reel script and **Claude uses this one without being told**.

### Does it work for TikTok and YouTube Shorts, or only Instagram Reels?

All three. The hooks, rehooks and funnel stages work the same on any short vertical video.

### Can it write reel hooks on their own?

Yes. Give it a topic and it writes openings from **the five watch-longer patterns**, with a rehook for the 15 to 20 second mark.

### Will it make up results to make a hook work?

It shouldn't. Its core rule is never to invent a result to fit a pattern, so if you don't have the result, **pick a pattern that doesn't need one**.

### Does it work with other AI agents?

It's written for Claude Code, but **`SKILL.md` is plain Markdown**. Paste it into any agent that takes instructions.

## Related repos

| Repo | What it is |
|---|---|
| [claude-seo-skills-benchmark](https://github.com/s77sh/claude-seo-skills-benchmark) | 5 Claude Code SEO skill packs tested on 20 planted problems |
| [claude-random-numbers](https://github.com/s77sh/claude-random-numbers) | Which number Claude picks when you ask for a random one |
| [interview-prep-pack](https://github.com/s77sh/interview-prep-pack) | A Claude Code skill that builds interview prep from your own resume |
| [bali-product-demand](https://github.com/s77sh/bali-product-demand) | Keyword Planner demand for 36 product niches in Bali |

What each one is for: [saeedseo.com/repos/](https://saeedseo.com/repos/).

## Author

Saeed Shahriar, senior SEO and growth marketer. [saeedseo.com](https://saeedseo.com)

## License

MIT
