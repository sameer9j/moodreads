# 📚 MoodRead - AI That Knows Your Reading Soul

> Stop scrolling through endless "readers also enjoyed" lists and LLM recommendations that aren't personalized. Get three strategic book recommendations from an AI that understands who you are, not just what you've read.

**Setup time**: 2 minutes  
**Cost**: Free (uses your existing Claude/ChatGPT subscription)  
**Privacy**: Your data never leaves the conversation

---

## 🎯 What This Does

**MoodRead doesn't just match genres—it understands you.**

Upload your reading history. MoodRead analyzes the patterns, infers your personality (MBTI-style), and shares what your books reveal about you. Once you validate its insight, you get exactly three books:

- 🌟 **Life-Changing**: The book you'll remember in 5 years
- 📚 **Natural Next Read**: Guaranteed to hit the spot right now
- 📈 **Trending Title**: What everyone's talking about (that you'll actually like)

No overwhelm. No algorithm mystery. Just three strategic picks that feel like they came from someone who really knows you.

---

## 🎯 Why Three Books?

**One to transform you. One to comfort you. One to connect you.**

🌟 **Life-Changing** — Addresses where you're going, not just where you are  
📚 **Natural Next Read** — Safe bet based on recent patterns (high probability you'll love it)  
📈 **Trending Title** — Current buzz filtered through your taste (so you're never left out of conversations)

No choice paralysis from 10+ options. No wondering which to pick. Three strategic recommendations, each with a clear purpose.

If none resonate? You get three NEW books. MoodRead never repeats itself.

---

## 🚀 Quick Start

### Option 1: Claude Projects

**Why this is best**: Your reading history persists across conversations. Just share your mood each time.

1. **Create a Claude Project**
   - Go to [claude.ai](https://claude.ai) → "Projects" → "+ New Project"
   - Name it "MoodRead"

2. **Add the system prompt**
   - Click "Add Content" → "Set custom instructions"
   - Copy [`system-prompt.txt`](./system-prompt.txt) and paste it
   - Click "Save"

3. **Add your reading history**
   - Upload your Goodreads CSV or create a manual book list
   - (See [Getting Your Reading History](#-getting-your-reading-history) below for export instructions)

4. **Start chatting**
   - MoodRead analyzes your books and shares an insight about you
   - Validate or correct it
   - Get your three strategic recommendations

---

### Option 2: ChatGPT Custom GPT

**Why use this**: Prefer ChatGPT or want to share your setup publicly.

1. **Create a Custom GPT**
   - Go to [ChatGPT](https://chat.openai.com) → Your profile → "My GPTs" → "Create a GPT"
   - Name: "MoodRead"

2. **Configure Instructions**
   - Paste [`system-prompt.txt`](./system-prompt.txt) into the "Instructions" field

3. **Add your reading history**
   - Upload your Goodreads CSV or manual book list in "Knowledge"
   - (See [Getting Your Reading History](#-getting-your-reading-history) below for details)

4. **Save and use**
   - Click "Save" (choose "Only me" for privacy)
   - Start chatting with your custom GPT

---

### Option 3: Simple Copy-Paste (Gemini or any other platform)

**Why use this**: Works anywhere (Claude.ai, ChatGPT, API), but you need to re-paste your books each conversation.

1. **Copy the system prompt**
   - Open [`system-prompt.txt`](./system-prompt.txt)
   - Copy the entire text

2. **Start a conversation**
   - Go to Claude.ai or ChatGPT
   - Paste the system prompt
   - Add: "Here's my reading history:" and paste your book list
   - Then ask: "I'm in the mood for [your mood]"

3. **For future conversations**
   - You'll need to re-paste both the prompt and your book list
   - Consider using Option 1 or 2 for persistence

---

## 📖 Getting Your Reading History

### From Goodreads (Recommended)
1. Log into [Goodreads](https://www.goodreads.com)
2. Go to "My Books"
3. Click "Import and Export" at the top
4. Click "Export Library"
5. Check your email for the CSV file
6. Upload to your Claude Project or ChatGPT Custom GPT

**Why use the full export?**  
The CSV includes ratings, dates, shelves (read/to-read/currently-reading), and your reviews—giving MoodRead much richer context.

### Manual Entry (Quick Start)
```
My Favorite Books:

High-rated (5 stars):
- [Book] by [Author] - Why I loved it: [one sentence]
- [Book] by [Author] - Why I loved it: [one sentence]

Enjoyed (4 stars):
- [Book] by [Author]
- [Book] by [Author]

Didn't finish or disliked:
- [Book] by [Author] - Why: [too slow/too dark/etc]
```

**Minimum**: 5-10 books for decent recommendations  
**Ideal**: 20-50 books for great recommendations  
**Maximum**: Unlimited (though AI handles ~100 most recent best)

---

## 💡 How to Use It

### Phase 1: Let It Know You
```
You: [Upload Goodreads CSV or share book list]
MoodRead: Based on your reading history, you seem like an [MBTI type]—
[2-3 line insight about you]. Does this resonate?
```

**Respond honestly:**
- "Yes, that's spot on!"
- "Mostly, but I'm more [X] than [Y]"
- "Not really, here's what I think..."

MoodRead will adjust its understanding before recommending.

### Phase 2: Get Strategic Recommendations

You'll get exactly **three books**:

1. **🌟 Life-Changing**: The book that could shift something for you
2. **📚 Natural Next Read**: Safe bet based on recent favorites  
3. **📈 Trending Title**: What's buzzing that matches your taste

**Then iterate:**
```
You: Book 2 sounds perfect! Tell me more.
MoodRead: [Deeper context, similar titles, etc.]
```

Or:
```
You: None of these feel right
MoodRead: No problem! What's going on in your life right now? 
[Gets more context] → [Shares 3 NEW books]
```

### Advanced Usage

**Include your mood or context:**
```
You: I'm feeling stressed and need escapism
MoodRead: [Factors stress/escapism into the three recommendations]
```

**Ask for specific types:**
```
You: I want the life-changing book but in a thriller
MoodRead: [Adjusts recommendations]
```

**Request more after finishing:**
```
You: I finished Book 2 and loved it! What's next?
MoodRead: [Builds on that choice with 3 new recommendations]
```

---

## 🎨 Mood Vocabulary

Not sure how to describe your mood? Try these:

- **Cozy / Comfort**: Low stakes, warm vibes, happy endings
- **Adventurous / Excited**: Fast-paced, world-building, page-turners
- **Melancholic / Reflective**: Thoughtful, bittersweet, character studies
- **Stressed / Anxious**: Escapism, humor, easy reads
- **Curious / Inspired**: Learning, unique perspectives, mind-expanding
- **Romantic / Yearning**: Emotional, relationship-focused, swoon-worthy
- **Dark / Intense**: Gritty, morally complex, psychological
- **Playful / Fun**: Witty, entertaining, light-hearted

Or just describe it naturally: "I want to feel like I'm on vacation" or "Something that makes me think but doesn't depress me"

---

## 🔒 Privacy & Data

- **No data collection**: Your books and preferences stay in your conversation
- **Not stored externally**: Unless you use Claude Projects (stored in your Anthropic account) or Custom GPT (stored in your OpenAI account)
- **You control sharing**: With copy-paste method, nothing is saved

---

## ❓ FAQ

**Q: How does it infer my personality from books?**  
A: It analyzes patterns in your reading choices—whether you gravitate toward introspection vs. action, analytical vs. emotional narratives, structured self-improvement vs. exploratory fiction. This reveals cognitive preferences similar to MBTI typing.

**Q: What if the personality insight is wrong?**  
A: Tell it! The whole point is to establish trust first. If the insight is off, correct it, and MoodRead will adjust before recommending books.

**Q: Why only 3 books? I want more options!**  
A: Quality over quantity. Three strategic recommendations (life-changing, natural next read, trending) is more useful than 10 random suggestions. If none resonate, it'll give you 3 NEW books—never repeats.

**Q: Does this work with library/Kindle/Libby/StoryGraph data?**  
A: Yes! Export your data as CSV or create a manual list. Any format works as long as it includes: book title, author, and ideally your rating.

**Q: Can I use this without reading history?**  
A: Yes, but it'll ask you for 3-5 favorite books first to understand your taste before inferring your personality.

**Q: How is this different from Goodreads/Amazon recommendations?**  
A: 
- **Goodreads/Amazon**: Algorithm-based, focused on genre matching

**Q: What if I don't want personality analysis?**  
A: You can skip it by saying "Just recommend books based on my recent favorites" or "I'm in the mood for [X], don't analyze me." MoodRead will adapt.

**Q: Can I modify the prompt?**  
A: Yes! It's open source. Fork it, customize it, improve it. See [CONTRIBUTING.md](./CONTRIBUTING.md) for ideas.

---

## 📄 License

MIT License - feel free to use, modify, and share.

---

## 🙏 Credits

Built with: Claude Sonnet 4 (prompt development), cognitive psychology principles, and a belief that the right book at the right time can change your life.