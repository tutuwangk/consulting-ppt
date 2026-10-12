---
name: consulting-ppt
description: Builds and reworks consulting-style (McKinsey, Bain, BCG) presentations that tell a clear story - a storyline structured with SCQA and the Pyramid Principle, action titles, numbers shown against a reference point, purposeful color, and the right chart or table for each message. Use when the user wants a consulting-style, MBB-style, or high-end polished deck, a business report, strategy or market analysis, a board or client presentation, or wants an existing deck restructured so its argument lands more clearly, even if they never say "consulting". Pairs with the pptx skill, which handles .pptx file mechanics.
---

# Consulting-Style Presentations

A consulting deck is an argument made visible. A reader who skims only the slide titles should come away knowing the question, the answer, and the reasons behind it. Every number, color, and shape on a slide carries part of that message, and that discipline is what makes these decks feel both clear and polished.

This skill offers direction, techniques, and examples. Treat it as a toolbox: adapt it to the material and the audience, and follow the user's brand, template, and stated preferences wherever they differ from the defaults here. Write in the user's language, keeping framework names such as SCQA and MECE in English.

**Files in this skill** (each links directly from here; read the one that matches the stage you are in):

- `references/storyline.md` - building the argument: SCQA and the Pyramid Principle in depth, deck shapes, action-title patterns, flow between slides, a ghost-deck template, and a worked example. Read before drafting a storyline.
- `references/visual-craft.md` - laying out slides: grid and type scale, hierarchy, color system, chart and table craft, shapes, and a library of slide compositions. Read before designing slides.
- `references/case-studies.md` - eight real BCG, McKinsey, and Bain slides, each with the composition behind it. Read when building a slide that resembles one of them.

## Approach

**1. Start from the reader's decision.** Work out who will read the deck, which question it answers, what decision or action it should enable, what data and source material exist, and the page count or speaking time. Infer what you can from the request and the materials, and state your assumptions in the reply. Ask one focused question only when a missing piece would change the direction entirely. Invite the user to flag any facts, figures, or wording that must appear exactly as given.

**2. Find the answer before building slides.** Write a governing thought (one sentence: the answer and why it matters), an SCQA opening, and about three supporting reasons that do not overlap. Then list the slides as action titles, which are full sentences stating each slide's conclusion. Read the titles in order; they should tell the whole story from question to answer to reasons to next step, and reordering or merging at this stage costs almost nothing. When the user supplies data files, analyze them first so the governing thought rests on computed numbers. For a long deck (roughly twelve slides or more) or an uncertain direction, share the storyline and let the user steer before building; otherwise continue straight into the build and include the storyline with the deliverable. A template and a worked example are in `references/storyline.md`.

**3. Design each slide around one judgment.** For each slide, name what the reader should conclude, then choose the evidence form (chart, table, framework, big number, diagram), the reference point that gives the data meaning, and the single element that earns the accent color. For pivotal slides such as an investment trade-off or a recommendation, sketch two clearly different layouts (for example "main chart plus compact table of key values" versus "full-width table with the key row highlighted") and keep the one where the key gap shows fastest. For decks of ten or more slides, build two sample slides first, one data slide and one text-heavy slide, so style and density are settled before the rest.

**4. Build the file.** Read the pptx skill for file mechanics, then apply the visual craft below. Use native charts where PowerPoint supports them so the user can edit the data. Add speaker notes when the deck will be presented live; a good note has a bridging sentence from the previous slide, the one thing to look at, and the so-what.

**5. Look at the result.** Render the slides to images and glance at each for about ten seconds: what is the conclusion, and where is the key gap? Fix whatever a reader would trip over, such as clipped or overlapping text, two competing highlights, an awkwardly wrapped title, or a number with no reference point, then deliver.

**Delivering.** Open the reply with the storyline in three or four lines (governing thought, supporting reasons, the decision requested), then the file, then any assumptions worth confirming. When the user asks only for an outline or advice, deliver that.

**Reworking an existing deck.** Extract all slide titles and read them in order as a story. Diagnose where the argument breaks (topic-style titles, reasons that overlap, numbers without reference points, competing highlights), propose the new storyline with a mapping from old slides to new, then rebuild. When the user wants to keep their template, edit in place following the pptx skill's editing approach: rewrite titles, recolor, and restructure content inside the template.

## Five core techniques

### 1. Give numbers a point of comparison

A lone number leaves the reader asking "compared to what?" Placing a reference point beside it turns data into a finding.

Useful reference points: **time** (last year, same period last quarter, five years ago), **peers** (country versus country, company versus company), **industry benchmark** (above or below the average, and by how much), and **target or plan**. Choose the one that best supports the message, and keep definitions identical on both sides (same scope, currency, period). Put the headline number and its reference point in one block: a large figure for the result, one short line for the reference.

> "Customer satisfaction: 82" becomes "Customer satisfaction 82, up 6 from last year and above the industry average of 75."

BCG's AI-at-work survey shows the effect: 52% optimistic and 30% worried is a snapshot, but placing the 35% and 40% from five years earlier beside them reveals optimism rising and worry falling. Bain's food-systems report pairs Ethiopia's 63% growth in per-capita grain output with a 12% median for comparison countries, so the 63% reads instantly as exceptional.

A comparison also raises the next question, which links slides: after showing worry fell, ask "What happened over those five years?" and let the next slide answer it (consumer AI tools made people familiar with the technology).

### 2. Open with SCQA

SCQA gives the deck a reason to exist by turning background into a question the rest of the deck answers.

- **Situation**: the shared starting point the audience already accepts, in one or two sentences.
- **Complication**: the change, gap, or tension that disturbs the situation. Make it specific, with a number where possible.
- **Question**: the question the complication creates in the reader's mind. It can stay implicit on the slide; write it down in the storyline.
- **Answer**: your conclusion. It becomes the top of the pyramid.

BCG's AI-at-work executive summary runs exactly this way. Situation: people are more positive about AI than five years ago. Complication: optimism varies widely across groups and deep concerns persist. Question: what should be done to close the gap? Answer: the body of the report, closing with three recommendations.

Use SCQA at three levels: the executive summary of the deck, the opening of each section, and the lead-in of an important slide (current state, then the change or tension, then the question and response). In a live presentation, highlight the summary's paragraphs one at a time so the audience follows the story as it unfolds.

### 3. Lead with the answer (Pyramid Principle)

Executives want the bottom line first. The top of the pyramid is the answer; below it sit about three reasons; below each reason sit the facts and analysis that support it. Each level summarizes the one beneath it, and reasons on the same level are mutually exclusive and collectively exhaustive (MECE), ordered by a logic the reader can see (time, structure, or importance). The executive summary is the top two layers of the pyramid.

SCQA explains why the question exists; the pyramid orders the answer and its support. Applied to a single slide, the action title states the answer and the body presents the findings behind it.

Action titles are how the pyramid shows up on each slide: a complete sentence that states the conclusion, such as "East China growth is slowing, mainly because of channel inventory" in place of the topic label "East China market analysis". Titles read in sequence form the argument; pattern tables and more rewrites are in `references/storyline.md`.

Bain's metaverse report is a clean model. The page opens with the answer to "how long until the metaverse goes mainstream?" ("five to ten more years"), then shows how long smartphones, game consoles, the internet, and laptops took to reach mass adoption. The reader holds the conclusion first and then follows the evidence down.

### 4. Use color with purpose

Decide which relationship the color should express, then assign it. Color has three jobs:

- **Focus attention**: the accent color lands on the element the slide is about, and everything else stays quiet.
- **Group information**: related items share a color, so the reader sees the structure before reading a word. BCG's five-stage capability chart colors the two existing stages grey and the three generative-AI stages green.
- **Make text-heavy pages readable**: BCG's model-selection decision tree uses bold green keywords to mark each decision topic, green "yes" and red "no" to identify branches, and yellow text for notes, so a dense page can be read along one path.

Practical rules: a single accent color with grey for context; one meaning per color across the whole deck; a handful of hues at most (a six-color stacked chart works because each color has one fixed meaning); a second encoding beside color (label, icon, position) so the message survives grayscale. For multi-row comparisons such as McKinsey's industry chart, fix each series' color once and reuse it in every row, so the reader can follow one color down the page. A quick test: convert the slide to grayscale and confirm the grouping still reads.

### 5. Match the chart or table to the task

Ask what the reader needs to do with the data.

| Reader's task | Form |
|---|---|
| Compare categories | Bar chart; compare bar lengths |
| Compare subgroups within each category (such as two years) | Clustered bar chart; the subgroup color stays constant across categories |
| See total size and internal composition together | Stacked bar chart; read the whole bar, then its segments |
| See a trend over time | Line chart; the connecting line makes the points read as one whole |
| Look up exact values across several attributes | Table; read along a row to collect related fields |
| Hold two or three numbers | Put them in the title or a large callout |

When a slide must both compare and let the reader look up values, let the main chart show the relationship that drives the decision and add direct labels or a compact small table for the key values. Format numbers for the reading task: a management comparison shows 3.9128m as 3.91m with consistent units and decimals within a set, while a lookup slide keeps the precision the reader needs.

## Visual craft essentials

The goal is that a reader sees the point of a slide within about three seconds. `references/visual-craft.md` has the details and a library of compositions; the essentials:

- **Three layers per slide**: action title (the conclusion), body (one core visual), annotations (source, footnote, page number). Keep title position, margins, and chart-label style identical across similar slides so the eye lands on content, not on layout changes.
- **Hierarchy through size, weight, and contrast.** One focal point per slide, such as a large number, a highlighted bar, or an emphasized line. Group related items closely and separate groups with whitespace.
- **Grey base, one accent.** White background, dark grey text, a primary color for titles and main shapes, and the accent only where the reader should look.
- **Let the chart state its conclusion.** Highlight the series being discussed in the accent color and grey the rest, label data directly on the chart, hide gridlines and the value axis, and add a short callout for the key change (growth rate, gap, turning point). The slide title carries the conclusion; a small chart header gives the metric, unit, and period.
- **Titles sized to the space.** Plan each title as a complete sentence, then tighten it for the layout, keeping the subject, the judgment, and the key number, and moving period and scope into the chart header. For example, "The investment needs 3.47% more transactions for a one-year payback" tightens to "One-year payback requires 3.5% more visits".
- **Simple, consistent shapes.** Numbered circles for sequence, chevrons for process, arrows for change, Harvey balls for qualitative scoring, light-grey cards for grouping, one icon family at one size.
- **Vary compositions** from slide to slide (chart with takeaway panel, big numbers, three-column framework, highlighted table, roadmap, scoring matrix) so the deck has rhythm.
