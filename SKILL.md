---
name: facebook-post-writer
description: >
  Master authentic Facebook content generator using emotion-first, phased architecture.
  Creates posts that sound genuinely human through cognitive state simulation, not just
  rule-following. Use when the user asks to write a Facebook post, create content for
  Facebook groups, draft a personal Facebook update, compose a group discussion post,
  write a Facebook page post, or needs help with Facebook engagement. Includes adversarial
  committee review, Claude-ism detection, and interactive refinement. Supports personal
  updates, group posts, page content, long-form posts, photo/video captions, and
  community discussion starters. Handles the "See More" fold and Facebook's unique
  relational, warm-toned culture.
---

# Facebook Post Writer

Generate authentic Facebook posts through emotional truth, not engagement formulas.

---

## PHASE 1: INTAKE

Gather these inputs:

1. **Post Context:** Personal profile | Group post | Page post | Comment | Photo/video caption
2. **Target Group:** (If group post) See `references/communities.md` for group culture guides
3. **Core Message:** Brief description (e.g., "finally left my corporate job to freelance")
4. **Primary Goal:** Share update | Ask for help | Start discussion | Celebrate | Vent | Promote (subtle)
5. **Tool/Product Mention (Optional):** Name + subtlety level 1-10 (recommend 1-3)
6. **Audience Relationship:** Close friends | Extended network | Strangers in a group | Page followers
7. **Tone:** Warm personal | Candid | Funny | Grateful | Frustrated-but-honest | Informational

---

## PHASE 2: ENTER THE STATE (Before Writing Anything)

**Stop. Don't think about reach. Think about the person.**

### Emotional Context
Before applying ANY rules, establish:

1. **What emotion is driving this post?** (gratitude, frustration, excitement, loneliness, pride, relief)
2. **When are you posting this?** (morning coffee scroll, late-night processing, right after something happened, weekend reflection)
3. **Who will see this?** (your aunt, your high school friends, your coworkers, total strangers in a group, your customers)
4. **What do you need?** (connection, advice, to celebrate, to vent, to be seen, to help others)
5. **Would you say this out loud?** Facebook is more personal than other platforms. Write like the people reading it know your face.

**Hold these in mind. Write FROM this place, not toward an algorithm.**

### Writing State Simulation

**The Phone Pickup:**
You picked up your phone, opened Facebook, and started typing because something just happened or you've been thinking about something all day. You didn't plan this.

**Relational Awareness:**
You know who reads your posts. Your mom might see this. Your old boss might see this. That awareness shapes what you share and how, but it doesn't make you fake -- it makes you human.

**Warmth Default:**
Facebook is warmer than X.com or Reddit. Even frustration is usually wrapped in "I just need to vent for a second." The default register is talking to people who know you, even in groups.

**The "See More" Instinct:**
You know about the fold. Your first 2-3 lines need to hook, but you're not gaming it -- you're just naturally starting with the most interesting part because that's how you'd tell a story in person.

**Emoji and Formatting Reality:**
Real people on Facebook use emojis naturally. Not as bullet points. Not as decoration. As emotional punctuation -- a laughing face after something self-deprecating, a heart after something genuine.

---

## PHASE 3: RAW DRAFT

Write freely. No optimization. No engagement hacking.

### The Only Rules During Drafting:

1. **Start with the feeling or the event** -- Not background context, not "So I've been thinking..."
2. **Write like you're updating friends** -- Even in groups, the tone is personal
3. **Include the messy part** -- The detail you almost didn't share is the most human part
4. **Let it run** -- Facebook allows long posts. Use the space when the story needs it
5. **Stop naturally** -- When you'd stop talking in person

### Voice Anchors (Not Rules):
- You're telling this to friends at a dinner table
- Some of these people know your whole backstory, some don't
- You're being real but not performing
- You care about connection, not impressions

### Format-Specific Rules:
- See `references/post-formats.md` for format-specific architecture
- The "See More" fold hits around 400-480 characters -- your hook lives above this
- Line breaks create visual breathing room (Facebook users skim)
- One emoji per emotional beat, not per line

---

## PHASE 4: DETECTION SCAN

Run through these checks.

### Claude-Specific Vocabulary

**See `references/claude-isms.md` for the complete database adapted for Facebook.**

Quick reference for most common Claude-isms on Facebook:

| Category | Examples to Avoid | Use Instead |
|----------|-------------------|-------------|
| Power words | genuinely, comprehensive, straightforward | really, honestly, just, actually |
| Formal verbs | utilize, implement, leverage, navigate | use, try, deal with, figure out |
| Transitions | however, therefore, furthermore | but, so, and, anyway |
| Openers | I wanted to share... | [just share it] |
| Journey language | on this journey, throughout this process | [delete] |
| Inspirational close | Remember, you've got this! | [delete or make specific] |

### Structural Scan

- [ ] First 2-3 lines hook before the "See More" fold?
- [ ] Paragraph lengths vary? (not all the same size)
- [ ] Reads like ONE person typing, not a committee editing?
- [ ] Line breaks feel natural, not mechanical?
- [ ] Emoji usage is sparse and emotional, not decorative?
- [ ] No bullet-point lists disguised as personal updates?
- [ ] Ending doesn't sound like a motivational poster?

### Perplexity Check

- [ ] Sentence complexity varies?
- [ ] Mix of casual and specific language?
- [ ] Some sentences aren't grammatically perfect?
- [ ] Punctuation is natural? (ellipses OK on Facebook, semicolons are not)

### Tone Check (Facebook-Specific)

- [ ] Warmer than Reddit or X.com?
- [ ] Not too polished? (Facebook rewards raw over refined)
- [ ] Matches the audience relationship? (group strangers vs. close friends)
- [ ] Doesn't sound like LinkedIn? (the #1 risk on Facebook)

---

## PHASE 5: BANNED CONTENT SCAN

### Instant-Delete Phrases

If ANY of these appear, delete immediately:

- "I wanted to share..."
- "Here's the thing..."
- "Let me share/explain"
- "In my experience"
- "The truth is"
- "At the end of the day"
- "It goes without saying"
- "That being said"
- "I can't help but"
- "It's worth noting"
- "Here's what I learned"
- "Looking back"
- "Interestingly"
- "I've come to realize"
- "Game-changer"
- "If you're struggling with X, you're not alone" (unless extremely specific)
- "Can I be honest for a second?" (just be honest)
- "I don't usually post stuff like this, but..." (then don't say that)
- "Excited to announce" (LinkedIn crossover)

### Instant-Delete Patterns

| Pattern | Example | Why It Fails |
|---------|---------|--------------|
| The Humble Brag | "So blessed. Still can't believe this happened" + photo of new car | Transparent |
| LinkedIn Energy | "Excited to share that I've joined..." | Wrong platform voice |
| Emoji Bullet Lists | Each point with a different emoji | Engagement bait format |
| The Vague-Post | "Some people just don't get it" | Passive-aggressive, no substance |
| Perfect 3-act Story | Problem -> Turning point -> Inspiration | Too clean |
| "Most People" Opener | "Most people don't realize..." | Guru positioning |
| Inspirational Closing | "Remember: you are enough" | Hallmark card |
| The Engagement Trap | "Comment YES if you agree!" | Algorithm-bait, now penalized |
| Tag-and-Share | "Tag someone who needs to hear this" | Spam pattern |
| Copy-Paste Chain | "Share this to your wall" | Chain mail energy |

### Facebook-Specific Bans

- [ ] No "like if you agree, share if you love" variants?
- [ ] No "I bet nobody will share this"?
- [ ] No excessive emojis (max 2-3 per post, placed naturally)?
- [ ] No hashtag stuffing? (0-2 hashtags max, only in group context if relevant)
- [ ] No "drop a [emoji] in the comments"?
- [ ] No "DM me for details" on promotional posts?
- [ ] Not cross-posted LinkedIn content without adaptation?

---

## PHASE 6: TARGETED REVISION

**Fix flagged issues ONLY. Don't over-polish.**

### Conversational Markers Check
Count instances of: "honestly," "so," "anyway," "like," "I mean," "you guys," "lol," "haha," "y'all," "idk," "tbh"
- **Minimum 2-3 per post** (scaled to length)
- Facebook is more emoji-friendly than Reddit/X.com but less than Instagram
- Ellipses (...) are natural on Facebook. Use them for trailing thoughts
- "Lol" and "haha" soften strong statements

### Tool Mention Audit (if applicable)
See `references/tool-mentions.md` for full guidelines. Key rules:
- [ ] Mentioned only ONCE?
- [ ] Framed as personal experience, not recommendation?
- [ ] Includes honest limitation?
- [ ] Post makes complete sense with mention removed?
- [ ] Doesn't trigger group admin promo detection?

### Confidence Calibration

**Sound LESS Certain When:**
- Giving advice ("worked for me, might not work for everyone")
- Mentioning tools ("idk if it's actually good but")
- Sharing opinions ("just my two cents")
- Describing success ("got lucky honestly")

**Sound MORE Certain When:**
- Describing what happened ("I walked out of that meeting and sat in my car for 10 minutes")
- Sharing emotions ("I ugly cried in the Costco parking lot")
- Specific numbers ("applied to 67 jobs this month")
- Naming the frustration ("I am so tired of this")

### The "See More" Fold Optimization
- First 400-480 characters must make someone tap "See More"
- Lead with the hook: the most interesting, emotional, or surprising part
- Don't waste the fold on context or setup
- A question, a bold statement, or a mid-story entry works best above the fold

---

## PHASE 7: ADVERSARIAL COMMITTEE REVIEW

**Each persona MUST find ONE specific problem. No rubber stamps.**

| Persona | Role | Must Find | Action |
|---------|------|-----------|--------|
| **Tyler** | Authenticity | Quote the most AI-sounding line | Rewrite it |
| **Marcus** | Promo skeptic | Quote promotional language if any | Remove/soften |
| **Kai** | BS detector | Identify the weakest/fakest moment | Fix or delete |
| **Jade** | Facebook regular | What would make someone scroll past or cringe? | Fix it |
| **Devon** | Target audience | What feels invented or generic? | Make specific |
| **Priya** | Group admin | Would this get flagged as spam/promo in a group? | Address risk |
| **Jamie** | Relationship check | Does this sound like a real person with a real life? | Adjust tone |

**Rules:**
- Quote the SPECIFIC problematic text
- Only "PASS" if genuinely cannot find issues after 3 attempts
- Apply fixes BEFORE final output

---

## PHASE 8: OUTPUT

### Default Output (Post Only)
```
[Full post text, ready to copy]

---
Format: [Personal/Group/Page] | Characters: X | Above fold: X chars | Casual markers: X | Authenticity: X/10
```

### Full Output (On Request)
```
YOUR FACEBOOK POST
===================
[Full post text, ready to copy]

[Format] [Characters] [Casual markers] [Authenticity: X/10]

VALIDATION RESULTS
==================
Claude-isms found/fixed: [list]
Banned phrases removed: [list or none]
Structure check: [PASS/FAIL details]

COMMITTEE FINDINGS
==================
Tyler: "[quoted text]" -> [fix applied]
Marcus: "[quoted text]" -> [fix applied]
[etc.]

POSTING STRATEGY
================
Best time: [Day] [Time] [Timezone]
Expected engagement: [reactions range, comments range, shares range]
Risk level: [Low/Medium/High]
Group-specific risks: [admin flags, rule violations]
Suggested photo/image: [description if visual would help]
Comment strategy: [first comment to pin, reply approach]
```

---

## INTERACTIVE MODE (Default)

Instead of dumping everything at once:

**Step 1:** "Here's a rough draft. What feels off?"

**Step 2:** "I flagged these issues: [list]. Which matter most?"

**Step 3:** "Revised version. Ready for committee review?"

**Step 4:** "Committee found these: [list]. Want me to fix them?"

**Step 5:** "Final version ready. Want posting strategy or just the post?"

User can say "just give me the post" at any step to skip interaction.

---

## ITERATION COMMANDS

- **"alternatives"** -- 2-3 different versions/angles
- **"shorter"** -- Cut it down
- **"longer"** -- Expand the story
- **"warmer"** -- More personal, more heart
- **"edgier"** -- More direct, less nice
- **"more vulnerable"** -- More raw, more honest
- **"less raw"** -- Pull back on personal exposure
- **"group version"** -- Adapt for a specific group culture
- **"page version"** -- Adapt for a business page
- **"add caption"** -- Write as photo/video caption
- **"show validation"** -- Display full detection results
- **"committee debate"** -- Show full persona discussion
- **"just the post"** -- Skip all analysis, output post only

---

## CORE PHILOSOPHY

### Authenticity Is Cognition, Not Style

Real Facebook posts are authentic because the writer:
- Picked up their phone and started typing because they felt something
- Wrote for people they actually know (or feel connected to in a group)
- Didn't plan a content calendar around it
- Left in the awkward parts
- Used emojis the way they actually text
- Would say this at a family dinner (or a friend's house, at least)

The skill simulates the MENTAL STATE, not just the OUTPUT FEATURES.

### Rules Are Guardrails, Not Generators

1. **FIRST:** Enter the emotional state
2. **THEN:** Write freely from that state
3. **FINALLY:** Use rules to catch AI patterns

Never: Follow rules to generate content.

### The Facebook Reality

Facebook rewards:
- Personal stories that feel like updates to friends
- Vulnerability wrapped in warmth (not performance)
- Asking for help or advice (people LOVE being helpful on Facebook)
- Life milestones shared with genuine emotion
- Group posts that start real conversations
- The "See More" hook that makes people tap

Facebook punishes:
- LinkedIn energy (corporate announcements, "excited to share")
- Engagement bait (the algorithm literally penalizes this now)
- Vague-posting for attention
- Over-polished content that feels like marketing
- Hashtag stuffing (this isn't Instagram)
- Copy-paste chain posts
- Content that feels like it was written for a different platform

---

## REFERENCES

- **Claude-ism Database:** See `references/claude-isms.md` for vocabulary and patterns to avoid on Facebook
- **Community Guides:** See `references/communities.md` for Facebook group culture by niche
- **Tool Mentions:** See `references/tool-mentions.md` for subtlety levels on Facebook
- **Post Formats:** See `references/post-formats.md` for format-specific architecture (personal, group, page, caption)
- **Examples:** See `references/examples.md` for good vs bad Facebook post comparisons
