# CallingClaw Website Visual TODO

Reference: Wispr Flow uses text transformations, UI mockups, device frames, persona photography, logo carousels, SVG motion animations, and scroll-triggered GSAP effects. Every section SHOWS, not just tells.

---

## Page 1: callingclaw-landing.html

### Section 1 — Hero
**Current**: Meeting frame mockup with tab switching + cursor animation (good baseline)
**TODO**:
- [ ] Add a short looping video/GIF above or replacing the static mockup: show the full flow in 10s — AI checking calendar → joining Meet → presenting → capturing feedback
- [ ] Or: animated SVG showing a calendar event → a Meet window opening → screen share activating (like Wispr's text transformation marquee, but for the meeting lifecycle)
- [ ] Add a row of supported platform logos below CTA: Google Meet icon, Zoom icon, macOS icon (like Wispr's Apple/Windows/Android row)

### Section 2 — Chat is too low-bandwidth
**Current**: 3 text-only cards
**TODO**:
- [ ] Left side: restore a chat mockup (similar to the old Telegram mockup) showing a painful IM conversation — user trying to explain a UI bug over text, multiple back-and-forth messages, AI asking "can you send a screenshot?", user sending a cropped image, AI still confused
- [ ] Right side: contrast with a meeting window mockup showing the same problem solved in one screen share — user pointing at the bug, AI seeing it immediately, caption says "Got it, fixing now"
- [ ] This before/after visual is the single most important conversion element on Page 1 (like Wispr's rambled speech → polished text transformation)

### Section 3 — Work with AI in meetings
**Current**: Text only (emphasis section)
**TODO**:
- [ ] Full-width product screenshot or embedded demo video: show a real CallingClaw meeting in progress — split screen with the Meet window on one side and CallingClaw desktop UI on the other
- [ ] Or: an animated data visualization showing bandwidth comparison — a thin line labeled "Chat: ~50 words/min" vs a thick flowing ribbon labeled "Meeting: voice + screen + context"
- [ ] Below the text, add a "See it in action" link to a demo video

### Section 4 — Capabilities (calendar, join, speak, capture)
**Current**: 4 icon+text cards
**TODO**:
- [ ] Each card needs a small product UI screenshot or mockup:
  - "Has its own calendar" → screenshot of Google Calendar with an AI-created event "CallingClaw: Sprint Review Prep" with green accent
  - "Joins meetings automatically" → screenshot of Google Meet lobby showing "CallingClaw is joining..." with the participant avatar
  - "Speaks and presents" → screenshot of screen share active, cursor moving, caption overlay visible
  - "Captures feedback and revises" → screenshot of the meeting summary output — action items, screenshots, revision notes
- [ ] Reference: Wispr Flow shows actual UI mockups (Dictionary panel, Snippet library) for each feature, not just icons
- [ ] Consider making these interactive tabs (like Wispr's persona tabs) — click each capability to see a different screenshot

### Section 5 — Timeline (10:07 → 11:00)
**Current**: Text-only vertical timeline
**TODO**:
- [ ] Each timestamp needs a thumbnail/screenshot on the right side of the timeline:
  - 10:07 → small screenshot of screen share showing a prototype
  - 10:21 → screenshot of the AI capturing a comment with a red annotation box around it
  - 10:34 → screenshot of a Slack/IM message sent by the AI: "New version ready for review" with a file attachment
  - 11:00 → screenshot of a new PR or updated doc showing the iteration
- [ ] Consider making the timeline scroll-animated (like Wispr's DrawSVG effects): as user scrolls, each timestamp fades in with its screenshot, the timeline line draws progressively
- [ ] Add a subtle connecting animation: screenshots slide in from the right as each timestamp becomes active

### Section 6 — Use Cases (review, report, demo, iterate)
**Current**: 4 text cards
**TODO**:
- [ ] Each card needs a scenario illustration or product screenshot:
  - "Review work live" → mockup of CallingClaw presenting a Figma design or code diff on screen share, with the user's face in the corner participant thumbnail
  - "Get work reported back" → mockup of AI presenting a task completion summary, slides-style, with bullet points visible on the shared screen
  - "Save time on demos" → mockup showing the AI in a vendor demo call, participant list shows 3 people + CallingClaw, caption shows AI asking a relevant question
  - "Iterate faster" → before/after showing old version → meeting → new version, compressed into a mini workflow diagram
- [ ] Reference: Wispr uses persona photography (real people in context) for each use case tab. CallingClaw could use stylized meeting room UI screenshots instead.

### Section 7 — Why meetings beat chat
**Current**: 3 text cards
**TODO**:
- [ ] Add a visual metric/stat to each card:
  - "More bandwidth" → data viz: "Chat: ~200 tokens/min context transfer" vs "Meeting: ~2000 tokens/min (voice + screen + visual)" shown as a horizontal bar comparison
  - "Less friction" → mini illustration: crossed-out chain of (screenshot → upload → paste link → explain → wait) vs a single meeting icon
  - "Safer reviews" → mini illustration: a document with a red "PUBLIC LINK" warning crossed out, replaced by a screen share icon with a green lock
- [ ] Consider making this a single animated infographic that builds as user scrolls

### Section 8 — Before / After
**Current**: Text-only comparison grid
**TODO**:
- [ ] Turn each "Before" item into a small visual vignette:
  - "Explain everything in chat" → mini chat bubble stack (5-6 messages, progressively frustrated)
  - "Share half-finished work through public links" → a URL bar showing a public link with a warning icon
  - "Lose context between tools" → 4 app icons (Slack, GitHub, Figma, Docs) with broken connections between them
  - "Spend hours on follow-up" → a clock icon showing 3 hours
  - "Keep humans in every loop" → a stick figure in the center of 6 arrows, looking overwhelmed
- [ ] Turn each "After" item into a matching visual:
  - "Explain once with voice + screen" → a single meeting window icon, clean
  - "Review local work without publishing" → a laptop with a screen share icon, no URL bar
  - "AI prepares and joins with context" → a calendar + auto-join icon
  - "Meetings into action automatically" → action items flowing out of a meeting icon
  - "Humans focused on judgment" → a stick figure with a thought bubble, relaxed
- [ ] Reference: Wispr's speed comparison section uses animated side-by-side text. CallingClaw should use side-by-side illustrated vignettes.

### Section 9 — Supported Agents
**Current**: 2 logo boxes
**TODO**:
- [ ] Add a scrolling compatibility logo carousel (like Wispr's 50+ app logo ticker): show OpenClaw, Claude Code, and "coming soon" agent logos — even if there are only 2 today, the carousel format signals an open ecosystem
- [ ] Below the logos, show a short code snippet or terminal mockup: `/callingclaw` command in OpenClaw → CallingClaw response "Meeting created and joined"
- [ ] Or: two side-by-side product screenshots showing CallingClaw launched from OpenClaw vs launched from Claude Code

### Section 10 — Download
**Current**: Download button + metadata
**TODO**:
- [ ] Add a device frame mockup: MacBook showing the CallingClaw desktop app with the tray icon, status window, and a meeting in progress
- [ ] Below the download button, add a 3-step quick start with small icons (like the old setup steps but more visual): Install → Connect API Key → Join Meeting
- [ ] Add a "macOS only" badge with the Apple logo

### Section 11 — Privacy
**Current**: 4 text cards
**TODO**:
- [ ] Add a simple architecture diagram: laptop icon → direct arrows to "Gemini / OpenAI / Grok" cloud icons, with a big X over any "CallingClaw Server" icon
- [ ] This one diagram communicates "100% local" better than 4 paragraphs
- [ ] Reference: security-focused products often use a single visual trust diagram rather than text cards

### Section 13 — Closing CTA
**Current**: Text only
**TODO**:
- [ ] Add the same demo video embed or an animated product preview (loop of 5s showing the AI in a meeting)
- [ ] Add social proof: 2-3 user quotes with avatars (like Wispr's testimonial carousel)
- [ ] Even placeholder quotes like "This is the first time an AI felt like a real employee" with avatar silhouettes

---

## Page 2: teams.html

### Section 1 — Hero
**Current**: Text only, no visual
**TODO**:
- [ ] Add a team collaboration visual: show 3-4 participant thumbnails in a meeting grid (like a Zoom/Meet call), one of which is CallingClaw with its logo avatar, with connection lines to Tanka showing "shared memory" flowing between participants
- [ ] Or: a workflow diagram showing CallingClaw in the center connected to Calendar, Meet, Tanka, Slack, with arrows showing data flow
- [ ] Add Tanka logo next to CallingClaw logo in the hero

### Section 2 — Org bottleneck
**Current**: 3 text cards
**TODO**:
- [ ] Each card needs a mini illustration:
  - "Fragmented context" → scattered app icons (Slack, Notion, Meet, Email, GitHub) with broken connection lines
  - "Slow iteration" → a timeline showing feedback → 2 days → revision → 3 days → approval → 1 week
  - "Human bandwidth" → a bottleneck/funnel diagram: many tasks flowing in, single human in the middle, slow output
- [ ] Consider one unified "org chaos" illustration that shows all three problems in a single visual

### Section 3 — Tanka (organizational memory)
**Current**: 4 capability cards
**TODO**:
- [ ] Central visual: a Tanka product UI screenshot or mockup showing the shared knowledge graph / project memory interface
- [ ] Each capability card gets a mini UI preview:
  - "Shared memory" → screenshot of Tanka's project context panel
  - "Role-aware preparation" → screenshot showing different prep docs for "PM" vs "Engineer" for the same meeting
  - "Faster routing" → screenshot of auto-sent messages to different team members with appropriate context
  - "Execution continuity" → screenshot of auto-created action items, approvals, or Jira tickets after a meeting

### Section 4 — AI employee capabilities
**Current**: 4 text cards
**TODO**:
- [ ] Full-width timeline or workflow animation showing the complete AI employee journey:
  Meeting prep (pulls docs) → Joins call → Presents work → Captures feedback → Sends new version → Messages teammates → Starts approval → Next experiment begins
- [ ] Each step in the workflow has a small icon and brief label, connected by animated arrows
- [ ] This is the "money shot" for the Teams page — like Wispr's multi-device section showing the same interface everywhere, CallingClaw shows the AI employee working across the entire workflow

### Section 5 — Demo / research calls (90% time savings)
**Current**: Before/after text + 3 cards
**TODO**:
- [ ] Before side: mockup of a team's calendar showing 5 blocked-out "Vendor Demo" meetings, each 45-60 min, with tired emoji or red time indicators
- [ ] After side: same calendar but 4 of the 5 meetings now show "CallingClaw attending" with green checkmarks, only 1 meeting has the human present
- [ ] Below: add a metric callout box: "45 min demo x 5/week = 3.75 hrs saved per person per week"
- [ ] The 3 cards below could each have a small illustration:
  - "AI runs presentation" → screen share icon with play button
  - "Humans step in when needed" → small avatar icon with a speech bubble appearing briefly
  - "Reusable intelligence" → a database/memory icon with an arrow feeding into the next meeting

### Section 6 — New collaboration state
**Current**: 3 text cards
**TODO**:
- [ ] A before/after org chart or workflow diagram:
  - Before: humans in the center of every connection, lots of arrows, entropy visualization
  - After: AI agents handle routing/syncing, humans clustered around "ideation" and "judgment" nodes, cleaner arrows
- [ ] Or: a pie chart showing time allocation shift — Before: 70% coordination, 30% creative work → After: 20% coordination, 80% creative work
- [ ] Reference: this is the "philosophical" section. One strong data visualization beats three text cards.

### Section 7 — Iteration speed (the moat)
**Current**: Text emphasis section
**TODO**:
- [ ] A single powerful visual: an iteration flywheel diagram
  - Center: "Iteration Speed"
  - Around it: Meeting → Feedback → Revision → Distribution → Learning → Next Meeting
  - Each step connected by arrows, with CallingClaw + Tanka logos at the connection points
- [ ] Below: a quote or stat in large type: "Teams using CallingClaw close feedback loops in minutes, not days."
- [ ] This flywheel visual should be the most memorable image on the Teams page

### Section 8 — Closing CTA
**Current**: Text only
**TODO**:
- [ ] Add a visual summary: two product logos side by side:
  - CallingClaw logo + "Meeting Room" label
  - Tanka logo + "Organization" label
  - Connected by an arrow: "Personal Agent → AI Employee"
- [ ] Add 2-3 social proof quotes from team leads or engineering managers (placeholder OK for now)
- [ ] Add a "Book a demo" calendar embed or link

---

## Cross-Page Visual Infrastructure

### Priority 1 — Must have for launch
- [ ] Hero video/GIF for Page 1 (10s product demo loop)
- [ ] Chat vs Meeting comparison visual for Section 2
- [ ] Capability screenshots for Section 4 (4 product UI captures)
- [ ] Timeline screenshots for Section 5 (4 thumbnails)
- [ ] Device frame mockup for Download section

### Priority 2 — High impact
- [ ] Scrolling logo carousel component (for agents section, reusable for partners)
- [ ] Before/After illustrated vignettes for Section 8
- [ ] Tanka UI mockup for Teams page Section 3
- [ ] Calendar before/after for Teams page Section 5
- [ ] Iteration flywheel diagram for Teams page Section 7

### Priority 3 — Polish
- [ ] GSAP/ScrollTrigger animations for timeline section (progressive reveal)
- [ ] SVG motion path animations for the waveform canvas (upgrade from static)
- [ ] Testimonial carousel component (for when real user quotes come in)
- [ ] Persona photography or illustrations for use case cards
- [ ] Architecture trust diagram for Privacy section

### Wispr Flow techniques to adopt
- [ ] **DrawSVG** — animated SVG paths that draw in during scroll (for timeline, workflow diagrams)
- [ ] **SplitText** — character-level animations on headlines for premium feel
- [ ] **Logo ticker** — auto-scrolling Splide carousel for compatibility logos
- [ ] **Scroll-triggered animations** — GSAP ScrollTrigger for section entrances (upgrade from current IntersectionObserver)
- [ ] **Device frames** — MacBook/iPhone frames around product screenshots
- [ ] **Motion path** — icons/elements following bezier curves (currently doing this with waveform canvas, could extend)
- [ ] **Rive animation** — consider for the meeting lifecycle animation (calendar → join → present → follow up)
