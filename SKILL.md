---
name: consulting-ppt
description: Builds and reworks consulting-style (McKinsey, Bain, BCG) presentations that tell a clear story - a storyline structured with SCQA and the Pyramid Principle, action titles, numbers shown against a reference point, purposeful color, and the right chart or table for each message. Use when the user wants a consulting-style, MBB-style, or high-end polished deck, a business report, strategy or market analysis, a board or client presentation, or wants an existing deck restructured so its argument lands more clearly, even if they never say "consulting". Pairs with the pptx skill, which handles .pptx file mechanics.
---

# Consulting-Style Presentations

A consulting deck is an argument made visible. A reader who skims only the slide titles should come away knowing the question, the answer, and the reasons behind it. Every number, color, and shape on a slide carries part of that message, and that discipline is what makes these decks feel both clear and polished.

This skill offers directions, techniques, and examples to draw on. Use what serves the material and the audience in front of you, bring your own judgment where the situation calls for it, and follow the user's brand, template, and preferences wherever they differ from the examples here. Where general slide-making guidance (such as the pptx skill's type sizes or palette suggestions) differs from the consulting conventions here, such as 24-28pt sentence titles or a restrained navy-and-grey scheme, these conventions guide the look and the pptx skill guides the file mechanics. Write in the user's language, keeping framework names such as SCQA and MECE in English.

**Files in this skill** (each links directly from here; open the one that matches the stage you are in):

- `references/storyline.md` - building the argument: SCQA and the pyramid in depth, deck shapes, action-title patterns and tightening, flow between slides, a ghost-deck template, and a worked example.
- `references/visual-craft.md` - laying out slides: a starting grid and type scale, hierarchy, an example palette, chart and table craft, shapes, and a library of slide compositions.
- `references/case-studies.md` - eight real BCG, McKinsey, and Bain slides, each with the composition behind it. Useful when building a slide that resembles one of them.

## Approach

A rough flow, with plenty of looping back.

**Understand the reader and the decision.** Work out who will read the deck, which question it answers, what decision or action it should enable, what data and source material exist, and the page count or speaking time. Infer what you can from the request and the materials and state your assumptions in the reply; ask one focused question only when a missing piece would change the direction entirely. A line in the reply inviting the user to flag any facts, figures, or wording that must stay exactly as given is usually enough.

**Find the answer, then shape the story.** Write a governing thought (one sentence: the answer and why it matters), an SCQA opening, and about three supporting reasons that do not overlap. List the slides as action titles, which are full sentences stating each slide's conclusion, and read them in order: they should tell the story from question to answer to reasons to next step. When the user supplies data files, analyze them first so the governing thought rests on computed numbers. For a long deck or an uncertain direction, sharing the storyline for the user's steer before building can save a lot of rework; for a clear brief, building straight away and including the storyline with the deliverable works well. A template and a worked example are in `references/storyline.md`.

**Design slides around judgments.** For each slide, name what the reader should conclude, then choose the evidence form (chart, table, framework, big number, diagram), the reference point that gives the data meaning, and the one element that earns the accent color. For pivotal slides such as an investment trade-off or a recommendation, sketching two clearly different layouts (for example "main chart plus compact table of key values" versus "full-width table with the key row highlighted") shows which one reveals the key gap fastest. For long decks, two sample slides, one data slide and one text-heavy slide, can settle style and density before the rest; when the user is not around to respond, review them yourself and carry on, stating the choices made.

**Build and look.** Build in whichever deck format the session offers: a dedicated slides artifact type when one is listed, or a .pptx file through the pptx skill when the user asks for PowerPoint or no such type exists. Native charts let the user edit the data later. Speaker notes help when the deck will be presented live; a good note bridges from the previous slide, points to the one thing to look at, and states the so-what. After rendering, glance at each slide for about ten seconds and ask what the conclusion is and where the key gap sits; fix whatever a reader would trip over, then deliver.

**Let the work loop.** Storyline, titles, and layouts evolve together. Drafting a slide often reveals that a title should be sharper, a reason is missing, or two slides should merge; comparing two layouts can show which finding deserves the lead. Feed these discoveries back into the storyline and keep refining until the titles read as one argument and each slide makes its point at a glance.

**Delivering.** A reply that opens with the storyline in a few lines (governing thought, supporting reasons, the decision requested), followed by the file and any assumptions worth confirming, lets the user judge the thinking before opening the deck. When the user asks only for an outline or advice, deliver that.

**Reworking an existing deck.** Extract all slide titles and read them in order as a story. Diagnose where the argument breaks (topic-style titles, overlapping reasons, numbers without reference points, competing highlights), propose the new storyline with a mapping from old slides to new, then rebuild. When the user wants to keep their template, edit in place following the pptx skill's editing approach: rewrite titles, recolor, and restructure content inside the template.

## Five core techniques

### 1. Give numbers a point of comparison

A lone number leaves the reader asking "compared to what?" A reference point beside it turns data into a finding.

Useful reference points: **time** (last year, same period last quarter, five years ago), **peers** (country versus country, company versus company), **industry benchmark** (above or below the average, and by how much), and **target or plan**. Choose the one that best supports the message, and keep definitions identical on both sides (same scope, currency, period). Putting the headline number and its reference point in one block works well: a large figure for the result, one short line for the reference.

> "Customer satisfaction: 82" becomes "Customer satisfaction 82, up 6 from last year and above the industry average of 75."

BCG's AI-at-work survey shows the effect: 52% optimistic and 30% worried is a snapshot, but the 35% and 40% from five years earlier, placed beside them, reveal optimism rising and worry falling. A comparison also raises the next question, which links slides: after showing that worry fell, ask "What happened over those five years?" and let the next slide answer it. (Cases 1 and 2 in `references/case-studies.md`.)

### 2. Open with SCQA

SCQA gives the deck a reason to exist by turning background into a question the rest of the deck answers.

- **Situation**: the shared starting point the audience already accepts, in a sentence or two.
- **Complication**: the change, gap, or tension that disturbs the situation. Specific beats vague; a number helps.
- **Question**: what the complication makes the reader ask. It can stay implicit on the slide; write it down in the storyline.
- **Answer**: your conclusion, which becomes the top of the pyramid.

SCQA works at three levels: the deck's executive summary, the opening of each section, and the lead-in of an important slide. In a live presentation, highlighting the summary's paragraphs one at a time lets the audience follow the story as it unfolds. BCG's and McKinsey's AI reports both open this way (case 3).

### 3. Lead with the answer (Pyramid Principle)

Executives want the bottom line first. The top of the pyramid is the answer; below it sit about three reasons; below each reason sit the facts and analysis that support it. Each level summarizes the one beneath it, and reasons on one level are mutually exclusive and collectively exhaustive (MECE), ordered by a logic the reader can see. The executive summary is the top two layers on one page.

On a single slide, the action title states the answer and the body presents the findings behind it: "East China growth is slowing, mainly because of channel inventory" does this work where the topic label "East China market analysis" does not. Bain's metaverse page puts the answer ("five to ten more years") at the top and the adoption histories of smartphones, consoles, and laptops beneath it (case 4). Title patterns and rewrites are in `references/storyline.md`.

### 4. Use color with purpose

Decide which relationship the color should express, then assign it. Color has three jobs:

- **Focus attention**: the accent color lands on the element the slide is about, and everything else stays quiet.
- **Group information**: related items share a color, so the reader sees structure before reading a word. BCG's capability chart colors the two existing stages grey and the three generative-AI stages green (case 5).
- **Make text-heavy pages readable**: BCG's decision tree marks each topic with a bold green keyword, branches with a green "yes" and a red "no", and notes in yellow, so a dense page reads along one path (case 7).

Tendencies that work well: when one thing is the focus, one accent with grey for context; when several series are compared, a fixed color per series (as in the two-year bars and the six-color stack in `references/case-studies.md`); one meaning per color across the whole deck; a handful of hues, each tied to a category in the data (a six-color stacked chart works because every color has one fixed meaning); a second encoding beside color (label, icon, position) so the message survives grayscale. For multi-row comparisons such as McKinsey's industry chart, fixing each series' color once and reusing it in every row lets the reader follow one color down the page (case 6). Converting a slide to grayscale is a quick test of whether the grouping still reads.

### 5. Match the chart or table to the task

Ask what the reader needs to do with the data.

| Reader's task | Form |
|---|---|
| Compare categories | Bar chart; compare bar lengths |
| Compare subgroups within each category (such as two years) | Clustered bars; the subgroup color stays constant across categories |
| See total size and internal composition together | Stacked bars; read the whole bar, then its segments |
| See a trend over time | Line chart; the connecting line makes the points read as one whole |
| See what drove a change | Waterfall |
| See the relationship between two measures | Scatter, with notable points labeled |
| See the share of a whole (a few parts) | Pie up to about four slices, or stacked bars |
| Look up exact values across several attributes | Table; read along a row to collect related fields (case 8) |
| Hold two or three numbers | Put them in the title or a large callout |

When a slide must both compare and support lookup, let the main chart show the relationship that drives the decision and add direct labels or a compact small table for the key values. Format numbers for the reading task: a management comparison reads best with 3.9128m shown as 3.91m, with consistent units and decimals within a set; a lookup slide keeps the precision the reader needs. Craft details for charts and tables are in `references/visual-craft.md`.

## Visual craft in brief

The goal is that a reader sees the point of a slide within about three seconds.

- **Three layers per slide**: action title (the conclusion), body (one core visual), annotations (source, footnote, page number). Consistent title position, margins, and chart-label style across similar slides let the eye land on content.
- **One focal point and clear grouping.** Size, weight, and contrast steer the eye to a large number, a highlighted bar, or an emphasized line; whitespace separates groups.
- **Charts that state their conclusion**: the focus series in the accent with the rest grey (or fixed colors per series when several are compared), labels on the marks, and a short callout for the key change. The slide title carries the conclusion; a small chart header gives metric, unit, and period.
- **Titles planned in full, then tightened to the space**, keeping subject, judgment, and key number.
- **Simple, consistent shapes** and **varied compositions** from slide to slide, so the deck has rhythm. A starting grid, palette, and twelve compositions are in `references/visual-craft.md`.
