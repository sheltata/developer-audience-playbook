# Developer Messaging: Good vs. Bad — Side by Side

Real examples and rewrites. Each pair shows the same message in two versions: one that fails with developers, one that works.

---

## Example 1: Product launch headline

**❌ Doesn't work:**
> "We're thrilled to announce a revolutionary update that will supercharge your development workflow!"

**Why it fails:**
- "Thrilled" — marketing emotion that developers don't share
- "Revolutionary" — overloaded word that signals overpromising
- "Supercharge your workflow" — generic, unprovable, forgettable
- Tells you nothing specific about what changed

**✅ Works:**
> "WebStorm 2025.3: Faster TypeScript navigation and local AI model support"

**Why it works:**
- Specific — you know what changed before clicking
- Respects the reader's scan behavior
- "Local AI model support" implies privacy benefits without a separate explanation
- Tone: informative, not emotional

---

## Example 2: Feature description (AI feature)

**❌ Doesn't work:**
> "Our cutting-edge AI assistant uses advanced machine learning to intelligently understand your code context and provide smart suggestions that help you write better code faster."

**Why it fails:**
- 30 words to say nothing specific
- "Cutting-edge," "advanced," "intelligent," "smart" — four adjectives that mean nothing
- No proof of the claim
- A developer reading this assumes the feature is mediocre

**✅ Works:**
> "AI Assistant reads your open files, project structure, and imports — not just the line you're on. Suggestions are context-aware from day one, no training needed."

**Why it works:**
- "Open files, project structure, and imports" — specific and technical
- "Not just the line you're on" — directly addresses a known frustration with other AI tools
- "No training needed" — removes a real friction concern
- No adjectives that require the reader to trust marketing claims

---

## Example 3: Comparison (competitive)

**❌ Doesn't work:**
> "Unlike other IDEs, WebStorm offers superior code intelligence and a seamless developer experience."

**Why it fails:**
- "Superior" — claim without evidence
- "Seamless developer experience" — empty phrase
- Reads as marketing talking to itself
- Developers find competitive claims that can't be verified condescending

**✅ Works:**
> "VS Code with TypeScript support is good. WebStorm with TypeScript support is opinionated — it knows your project, not just your file. Here's a 90-second comparison."

**Why it works:**
- Acknowledges VS Code is "good" — developers respect honesty
- "Opinionated" — developer language; implies thoughtful design, not just features
- "Knows your project, not just your file" — specific claim that invites verification
- Leads to a demonstration, which is where the real selling happens

---

## Example 4: Pricing / upgrade CTA

**❌ Doesn't work:**
> "Upgrade to Pro today and unlock unlimited access to all premium features for a truly professional experience!"

**Why it fails:**
- "Unlock unlimited" — sounds like a mobile game
- "Premium features" — vague
- "Truly professional experience" — empty modifier
- No reason given to upgrade

**✅ Works:**
> "All features, one subscription. $7.90/month — less than most developers spend on coffee in a day. Free for open-source contributors."

**Why it works:**
- Price is visible and specific (developers respect transparency)
- The coffee comparison is a cliché but it's proportional and honest
- "Free for open-source contributors" signals community values, not just commerce

---

## Example 5: Email subject line for a release newsletter

**❌ Doesn't work:**
> "Exciting news — big updates coming your way! 🚀"

**Why it fails:**
- Rocket emoji in a developer email — this is for consumer products
- "Exciting news" — personal emotion, not factual signal
- "Big updates" — quantifies nothing
- Many developers filter these out automatically

**✅ Works:**
> "What changed in WebStorm 2025.3 (and what you might want to turn on)"

**Why it works:**
- Informational, not emotional
- "What you might want to turn on" — implies the content has practical, actionable information
- "Might want to" — respects autonomy; not prescriptive
- Reads like something a knowledgeable colleague would send, not a marketing department

---

## Pattern summary

| Bad pattern | What it signals to developers | Better approach |
|---|---|---|
| Adjectives without proof | Overconfidence / inaccuracy | Specific, verifiable claims |
| Emotional opener ("thrilled", "excited") | Marketing voice, not peer voice | Informational opener |
| "Revolutionary" / "cutting-edge" | Almost certainly not | Describe what's new specifically |
| Competitive claims without demo | Something to hide | Lead with demonstration |
| Feature lists without context | Doesn't understand my actual workflow | Lead with "what changes for you" |
| Emoji in technical communication | Wrong audience read | Use text; developers can handle words |

---

*Part of [developer-audience-playbook](../README.md) by Tatiana Shelekhova*
