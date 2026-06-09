# Anti-Patterns: Common Design Mistakes & Error Prevention

> Source: "100 Things Every Designer Needs to Know About People" by Susan M. Weinschenk, Ph.D. (Second Edition, 2020) — Chapters 85-89 (People Make Mistakes), 30-39 (How People Think)

## The Fundamental Error: Designing for a Rational User

The overarching mistake: assuming users process information rationally, sequentially, and consciously. In reality:
- 30% of the time, minds wander (Ch. 29)
- People are driven to create categories whether they exist or not (Ch. 35)
- People screen out information that doesn't fit their beliefs (Ch. 37)
- Uncertainty leads people to defend their ideas more strongly (Ch. 30)

## Anti-Pattern Catalog

### Anti-Pattern 1: Overloading Working Memory
**The mistake**: Asking users to hold information across pages, between fields, or through multi-step processes without visual aids.

**Why it fails**: Working memory holds only 3-4 items and is highly sensitive to interference (Ch. 19-20). Any interruption (phone notification, background noise, another task) causes forgetting.

**Signs of the problem**:
- Users write down information from one screen to enter on another
- Users complain about "too many steps"
- Users refer to sticky notes or printed instructions while using the product

> **Case: Phone Number Paradox** (Ch. 20): U.S. phone numbers are chunked as 3-4-4 because 10 digits exceed working memory. Area codes were originally unnecessary for local calls — reducing memory load further. **Key takeaway**: Chunk information, or better yet, don't make users remember it at all.

### Anti-Pattern 2: Ignoring Affordance Cues
**The mistake**: Designing buttons, links, and interactive elements without clear visual cues for how they work (flat design, hover-only links, indistinguishable clickable/non-clickable elements).

**Why it fails**: People perceive affordances in milliseconds (Ch. 7). Without clear cues, users guess — and guessing leads to errors, frustration, and abandonment.

> **Case: The PUSH Door That Looks Like a PULL** (Ch. 7): A door handle shaped to invite pulling but requiring a push is the classic affordance failure. The same happens on screens when a button looks like decorative text or vice versa. **Key takeaway**: If you need to add instructions ("Click here"), your affordance has failed.

### Anti-Pattern 3: Choice Overload
**The mistake**: Providing too many options, features, or paths, assuming more choice = better experience.

**Why it fails**: While people think more choices = more control (Ch. 93), they can only process 3-4 items in working memory. Excessive choice leads to paralysis, regret, and dissatisfaction.

> **Case: Breadth vs. Depth** (Ch. 20, 27): Broadbent's research shows people organize recall into clusters of 2-4 items. Information that can't be chunked into 4±1 groups is poorly remembered and poorly processed. **Key takeaway**: Curate. If you can't reduce choices, group them into 3-4 categories.

### Anti-Pattern 4: Assuming Users Notice Changes
**The mistake**: Updating a screen (form validation, dynamic content, error messages) and assuming users will notice the change.

**Why it fails**: Change blindness (Ch. 8) means people often miss obvious visual changes — even a gorilla walking through a basketball game. Eye tracking shows people "see" changes with their central vision but don't consciously register them.

> **Case: The Gorilla Video** (Ch. 8): 50% of viewers didn't notice the gorilla, even though eye tracking confirmed their central gaze landed on it. **Key takeaway**: Looking ≠ seeing. Use sound, animation, or multiple redundant cues for important changes.

### Anti-Pattern 5: Relying on User Memory in Research
**The mistake**: Asking users what they did, why they did it, or how they felt about an experience after the fact — and treating answers as accurate.

**Why it fails**: Memories are reconstructed each time (Ch. 24), changed by subsequent events (Ch. 24), and influenced by word choice in questions (Ch. 24). Flashbulb memories are vivid but often wrong (Ch. 26).

> **Case: Loftus "Smashed" vs "Hit"** (Ch. 24): Asking "How fast was the car going when it smashed the other vehicle?" produced higher speed estimates than using "hit" — and twice as many people "remembered" broken glass that didn't exist. **Key takeaway**: Watch your words — they literally rewrite user memory.

### Anti-Pattern 6: Designing Without Error Tolerance
**The mistake**: Assuming users will follow the intended path and not accounting for errors.

**Why it fails**: People will always make mistakes (Ch. 85). There is no fail-safe product. Different error types require different strategies (Ch. 89):
- **Slips** — attention failures (typos, misclicks) → undo, confirmation dialogs
- **Mistakes** — understanding failures → better instruction, clearer labels

> **Case: Stress Impairs Performance** (Ch. 86): Under stress, prefrontal cortex activity decreases, reducing working memory effectiveness. Errors increase dramatically when users are stressed, rushed, or multitasking. **Key takeaway**: Design for the stressed, distracted user, not the calm, focused one.

### Anti-Pattern 7: Information Without Story
**The mistake**: Presenting data, features, or instructions as lists of facts rather than narratives.

**Why it fails**: People process information best in story form (Ch. 33). Stories and anecdotes persuade more than data alone (Ch. 74). Without narrative structure, information is harder to understand, remember, and act on.

**Signs of the problem**:
- Users can repeat facts but can't apply them
- Users ask "So what?" or "What does this mean for me?"
- Data-heavy presentations fail to drive action
