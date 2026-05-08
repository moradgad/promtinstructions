# Prompting, Standards, and Quality Rules

## Table of Contents

1. [Overview](#1-overview)
2. [Rules and Constraints](#2-rules-and-constraints)
   - [Scenario Setup](#scenario-setup)
   - [Deliverable Rules](#deliverable-rules)
   - [Reference Files](#reference-files)
   - [Names and PII](#names-and-pii)
   - [Prohibited Requests](#prohibited-requests)
   - [Violations](#violations)
3. [File Standards](#3-file-standards)
   - [General Standards](#general-standards)
   - [PPTX Standards](#pptx-standards)
   - [DOCX and PDF Standards](#docx-and-pdf-standards)
4. [Quality Assessment](#4-quality-assessment)
   - [Good File Checklist](#good-file-checklist)
   - [Bad Deliverable Indicators](#bad-deliverable-indicators)
5. [Iteration Workflow](#5-iteration-workflow)
   - [How to Iterate](#how-to-iterate)
   - [When to Stop](#when-to-stop)
   - [Submitting Your Deliverable](#submitting-your-deliverable)
   - [Turn Quality](#turn-quality)
   - [Troubleshooting](#troubleshooting)

---

## 1. Overview

You are a student or employee with a high-stakes deliverable due tomorrow. How well you do will determine whether you get a promotion or passing grade.

- The subject should be one where you have proficiency, either personally or professionally.
- For highly specialized domains like medicine or law, avoid these unless you are a subject-matter expert.
- Tasks should be realistic and cover a diverse range of difficulty levels and subject areas.
- You only get one conversation with Model, and a maximum of 20 turns to make it as good as possible.
- Web search is enabled. Tasks requesting real-time or current data are allowed.

---

## 2. Rules and Constraints

### Scenario Setup

- Every prompt must include the file type requested: PDF, PPTX, or DOCX.
- Every prompt must include the quantity requested, up to 3 files.
- All deliverables must follow the standards for professional documents in the [File Standards](#3-file-standards) section.

### Deliverable Rules

- The final submission must include at least 1 and no more than 3 total files.
- Final files must be in PPTX, PDF, and/or DOCX format.
- Deliverables can be abandoned, changed, or added mid-conversation, as long as the final submission follows the file-count and file-type limits.
- Excel files cannot be requested as deliverables. They can only be used as reference files.

### Reference Files

- Accepted formats: .pdf, .docx, .pptx, .xlsx, .csv, .json, and images.
- Optional details to include with reference files: color scheme, company name, target audience, or document structure.
- If you need synthetic data, generate it in a separate Model window — do not generate reference data in the same conversation as the task.
- Using the same reference dataset for multiple different deliverables is allowed. For example, one dataset can be used for a board presentation, executive summary, and detailed report.
- If you forget to include a reference file, add it mid-conversation and include it in the final ZIP.

### Names and PII

#### Names

- Use unique and varied names for people and companies in each task.
- Model tends to default to names such as Alex Rivera, Elena Vargas, Summit, Apex, Horizon, and Meridian. If these appear, ask Model to change them to something more unique or use a placeholder.

#### PII (Personally Identifiable Information)

PII refers to private personal details that are not publicly available — such as personal email addresses, home addresses, phone numbers, or other non-public information about an individual. The user's own name must not appear anywhere in the task, prompt, or reference files.

**Before uploading any reference file, review it and remove all PII.**

| | Examples |
|:--|:--|
| **Allowed** | A CEO's name, a company's official name, headquarters address, or any detail found on the company's website or in a published news article |
| **Not allowed** | Personal email addresses, home addresses, phone numbers, or any other private or non-public information about an individual |

### Prohibited Requests

- Requesting Excel (.xlsx) files as deliverables.
- Requesting items like an email, copy-and-paste template, or anything that could have just been put into the chat.
- Incorporating non-English reference files or requesting non-English deliverables.
- Including any personally identifying information in reference files.
- Submitting the same prompt and requesting the same deliverable across multiple tasks, even with different reference files.
- Downloading the deliverable, editing it in native software, and submitting the manually edited version.

### Violations

- **AI use** — The prompt or iterations mention large language models, translators, grammar checkers, or paraphrasing tools.
- **Duplicate prompts** — The same prompt and deliverable are used across multiple tasks, even if the reference file is changed.
- **Editing outside Model** — The deliverable was downloaded, edited in native software, and reuploaded as the corrected version.
- **PII in the prompt or deliverable** — Personally identifying information that identifies a real individual appears in the prompt or deliverable.
- **Model interference** — Prompts, iterations, or reference files attempt to override or alter Model's existing behavior.
- **Edited or restarted turns** — The user went back to a previous turn and edited the prompt, asked Model to regenerate from a previous turn, or restarted the conversation.
- **Copied instructions** — The prompt includes large copied sections of the File Standards without tailoring them to the task.
- **User's own name** — The user's name appears in the prompt or deliverable, such as "Prepared by [Name]" or "As [Name], I want..."

---

## 3. File Standards

### General Standards

#### Fonts
- Use one or two fonts maximum.
- Additional fonts must have a clear purpose.
- Fonts must be used consistently throughout.
- Font sizes must follow a clear visual hierarchy.
- Font size and weight must be consistent, such as body text using the same size and headers using the same size.

#### Alignment
- Pick one alignment approach and use it consistently.
- Bullet points and lists must always be left-aligned.

#### Spacing
- Line spacing must be consistent.
- There must be enough spacing between sections, paragraphs, and elements so nothing feels crowded.
- Headings should have more space above than below.
- Tables, charts, and images need visible breathing room.
- Text inside table cells and text boxes needs padding.

#### Bullets and Lists
- Bullet points must use hanging indents.
- Bullet style must be consistent.
- Numbered lists must follow the same rule.

#### Tables and Charts
- All content must stay within margins.
- Chart labels must be visible and legible.
- Column alignment should make sense for the content.
- Font sizes within tables must be consistent across the document.

#### Images and Graphics
- Images must be properly sized and not distorted.
- Images should be placed between sections, not awkwardly wrapped.
- There should be no broken image icons.

#### Content Accuracy
- All facts, dates, and statistics must be accurate.
- Numbers in charts must match numbers in text.
- There must be no contradictions between sections.
- There must be no fabricated sources, citations, or statistics.
- There must be no spelling or grammar errors.

---

### PPTX Standards

#### Font Minimums

| Element | Minimum size |
|:--|:--|
| Body text | 16pt, or 14pt for larger letterforms like Arial |
| Captions and citations | 12pt |
| Headers, footers, page numbers in all caps | 10pt |

#### Layout and Visual Balance
- Use one main idea per slide.
- Avoid walls of text.
- Keep on-slide text concise.
- Use a consistent slide layout throughout.
- Keep content balanced and centered.
- Add enough spacing between elements.

#### Alignment
- Slide titles must be centered or left-aligned consistently across all slides.
- Body text must be left-aligned.
- Do not mix centered and left-aligned body text on the same slide.

#### Tables
- Tables must fit within slide boundaries.
- If a table is too large, split it across multiple slides instead of shrinking the font.

#### Charts and Graphics
- Charts should be large enough to read without squinting.
- If labels overlap, use a different chart type, such as a horizontal bar chart.

#### Example Fix Prompts
- "Enlarge the chart on slide 3 to fill the blank area on the bottom half."
- "Redistribute the content on slide 6 so it is centered and balanced."
- "Split slide 4 into two slides."
- "Add padding between the text and the edge of the slide on slide 8."
- "Left-align all body text on every slide."
- "Redo the pie chart on slide 6 as a horizontal bar chart."

---

### DOCX and PDF Standards

#### Font Minimums

| Element | Minimum size |
|:--|:--|
| Body text and figure captions | 12pt, or 10pt for larger letterforms like Arial |
| Headers and footers | 10pt |
| Footnotes | 9pt, with smallest body text at 11pt |

#### Margins
- Standard margins should be 0.5 inch on all sides.
- Use 0.25 inch margins only for design-heavy one-pagers.
- Bottom margin should be at least 0.75 inch if there is a footer or page numbers.

#### Alignment
- Body text should be left-aligned or justified consistently.
- If justified, hyphenation must be enabled.
- All body headings and subheadings must share the same alignment.

#### Spacing and Visual Balance
- Body text line spacing should be 1.0 to 1.15.
- Headings should have more space above than below.
- Headings should never appear alone at the bottom of a page.
- Tables should not split across pages if they can fit on one page.
- Avoid single lines of a paragraph stranded at the top or bottom of a page.

#### Page Elements
- Page numbers must be present and consistent.
- Footers should be noticeably smaller than body text.
- Header and footer elements must span the full text width.

#### Example Fix Prompts
- "Set all page margins to 0.5 inch."
- "Left-align all body text and headings."
- "Enable hyphenation to prevent rivers of white space."
- "Add 12pt of space before each heading and 6pt after."
- "Keep the table on page 3 together on one page."
- "Add page numbers to the bottom right corner of every page."

---

## 4. Quality Assessment

### Good File Checklist

- All font is readable.
- There is no unused white space on any slide or page, except acceptable white space on the last page.
- Formatting is consistent throughout, including fonts, alignment, spacing, bullet style, and margins.
- There is a clear visual hierarchy for headers, subheaders, body text, footers, and other elements.
- Images and graphics are properly sized.
- Tables and content stay within margins.
- Chart labels are visible and legible.
- Content is visually balanced across the page or slide.
- In documents, body text, headings, and bullets share the same left margin.
- Presentations use balanced, centered alignment.
- Bullet points use hanging indents.
- Page margins are reasonable and content is not touching the edge.
- There is enough spacing between sections, paragraphs, and elements so nothing feels crowded.

### Bad Deliverable Indicators

#### Font Issues
- Text is too small to read comfortably.
- Headings, subheadings, and body text use the same size or weight.
- Font sizes are inconsistent across the document.

#### Spacing Issues
- Content is squished together.
- Lines are packed too tightly or too loosely.
- Text is crammed against the edges of boxes, cells, or slide boundaries.
- Large areas of unused white space appear.
- Headings are orphaned.
- Single lines are stranded at the top or bottom of a page.
- Tables split across pages when they could fit on one page.
- White space on the last page is only an error if other formatting issues contribute to it.

#### Alignment Issues
- Content is crowded to one side.
- Left margins are not aligned consistently.
- Alignment is inconsistent across slides or pages.

#### Margin Issues
- Page margins are so small that content nearly touches the edge.
- Margins are too small to be printed.

#### Bullet and List Issues
- Continuation lines wrap back under the bullet character instead of using hanging indents.
- Bullet style is inconsistent throughout.

#### Table and Chart Issues
- Tables extend beyond margins.
- Chart labels overlap, are missing, or are unreadable.
- Table columns use inconsistent alignment.

#### Image Issues
- Images are distorted or stretched.
- Broken image icons appear.
- Text inside images is too small or overlapping.

#### Content Accuracy Issues
- The deliverable includes false statements.
- Sources, citations, or statistics are fabricated.
- Sections contradict each other.
- Numbers in charts do not match the text.
- Data is impossible, such as Q5, February 30, or wrong units.

#### Frequently Used Names
- The deliverable uses names specifically flagged as common defaults: Alex Rivera, Elena Vargas, Summit, Apex, Horizon, or Meridian.

---

## 5. Iteration Workflow

### How to Iterate

- Download and open each deliverable with native software, such as Microsoft Word or Microsoft PowerPoint. Do not rely only on the Model preview.
- Assess whether Model followed instructions, whether there are factual inaccuracies, whether formatting is poor, and whether sections are missing.
- Use follow-up turns to improve the deliverable.
- Stay in character. Do not reference the project, review process, or internal terminology. A real user would simply state what they want changed.

### When to Stop

Stop when either condition is true:

1. **The 20-turn limit has been reached.**
   - The original prompt counts as turn 1; each follow-up exchange counts as another turn.
   - To count turns quickly, use Ctrl+F / Cmd+F and search for "Thought for," "Thought(s)," or "No response."

2. **The deliverable is flawless.**
   - It meets all professional document standards.
   - It has zero content errors, misrepresentations, or factual inaccuracies.
   - It fulfills all prompt constraints that were not intentionally changed or dropped.

### Submitting Your Deliverable

Upload the best version of the deliverable, even if this is not the last version.

If the model makes the deliverable worse during the conversation, please do the following when submitting:

- Upload the share link for the full conversation.
- Upload the best version of the deliverable.
- Note in your notes what turn the best version was from (no need to do this if the best version is the final version).
   - **Exception:** If the model provided a single file that it continuously updated, upload the final version instead of the best version.

### Turn Quality

#### Productive Turns

A productive turn is one where the user clearly looked at what Model produced and tried to improve it. The prompt must describe the issue and/or give specific instructions for how to fix it. It can include one change or multiple changes.

**Format:** `[What is wrong] + [How to fix it]`

> Example: "The font on slide 4 is too small to read, increase the body text to at least 18pt."
> Example: "The chart labels on page 2 are overlapping. Switch to a horizontal bar chart."

**Exceptions:**
- If Model makes a mistake, the turn still counts toward the 20 total but is not penalized as long as the user responds appropriately.
- Re-submitting a prompt after an error message, no response, or stall is not penalized.

#### Unproductive Turns

- Submitting a useless prompt that requests new content or additions when the current deliverable has unaddressed flaws that should be fixed first.
- Repeating the same prompt after a valid output without changing the approach.
- Giving no direction, such as "Fix it," "Please revise," or "Make it better."
- Spending more than 3 consecutive turns troubleshooting an issue where Model does not produce an output.
- Asking for the deliverable when it has already been generated and Model already said where the file was saved.

**Exceptions:**
- A turn with no actionable information (e.g., "Fix it" or "It's still broken") is never acceptable.
- Repeating a failed prompt after valid output is allowed only when Model produced valid output but did not make the change and the request is revised rather than repeated exactly.

### Troubleshooting

| Problem | What to do |
|:--|:--|
| Model incorporates some changes but skips others | Rephrase the skipped edits clearly. |
| Model stalls on grouped edits | Reduce to 2–3 edits per turn, or 1 edit at a time as a last resort. |
| Same edit keeps failing | Switch focus to other changes and come back later. |
| Chart will not update | Ask for a different chart format, such as a horizontal bar chart. |
| Model cannot produce a good image | Upload your own image as a reference file. |
| Forgot to include a reference file | Add it mid-conversation and include it in the final ZIP. |
| Model's first deliverable is very poor | Continue iterating because improvement is useful. |
| Stuck and nothing is working | Use: "Start from scratch and incorporate all of my feedback from this chat into a new version." |
