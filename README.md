# Prompting, Standards, and Quality Rules

## 1. Prompting and Task Requirements

### Scenario
You are a student or employee with a high-stakes deliverable due tomorrow. How well you do will determine whether you get a promotion or passing grade.

### Task setup
- The subject should be one where you have proficiency, either personally or professionally.
- For highly specialized domains like medicine or law, avoid these unless you are a subject-matter expert.
- All deliverables must follow the standards for professional documents in the File Standards tab.
- You only get one conversation with Model, and a maximum of 20 turns to make it as good as possible.
- Tasks should be realistic and cover a diverse range of difficulty levels and subject areas.
- Every prompt must include the file type requested: PDF, PPTX, or DOCX.
- Every prompt must include the quantity requested, up to 3 files.

### Deliverable rules
- The final submission must include at least 1 and no more than 3 total files.
- Final files must be in PPT, PDF, and/or DOCX format.
- Deliverables can be abandoned, changed, or added mid-conversation, as long as the final submission follows the file-count and file-type limits.
- Excel files cannot be requested as deliverables. They can only be used as reference files.

### Web search
- Tasks requesting real-time or current data are allowed.
- Web search is enabled.

### Names and personally identifying information
- Use unique and varied names for people and companies in each task.
- Never include real personally identifying information.
- Model tends to default to names such as Alex Rivera, Elena Vargas, Summit, Apex, Horizon, and Meridian. If these appear, ask Model to change them to something more unique or use a placeholder.

### Synthetic reference data
- Generate synthetic data in a separate Model window if needed.
- Do not generate reference data in the same conversation as the task.

### Optional details to include
- Any details relevant to the final deliverable, such as color scheme, company name, audience, or structure.
- Reference files in accepted formats: .pdf, .docx, .pptx, .xlsx, .csv, .json, and images.

### Prohibited requests
- Requesting Excel (.xlsx) files as deliverables.
- Requesting items like an email, copy-and-paste template, or anything that could have just been put into the chat.
- Incorporating non-English reference files or requesting non-English deliverables.
- Including any personally identifying information in reference files.
- Submitting the same prompt and requesting the same deliverable across multiple tasks, even with different reference files.
- Downloading the deliverable, editing it in native software, and submitting the manually edited version.

### Allowed exception
Using the same reference dataset for multiple different deliverables is allowed. For example, one dataset can be used for a board presentation, executive summary, and detailed report.

### Iteration rules
- The original prompt counts as turn 1.
- Each follow-up exchange counts as another turn.
- The maximum is 20 turns.
- Download and open each deliverable with native software, such as Microsoft Word or Microsoft PowerPoint.
- Do not rely only on the Model preview.
- Assess whether Model followed instructions, whether there are factual inaccuracies, whether formatting is poor, and whether sections are missing.
- Use follow-up turns to improve the deliverable.
- Stay in character. Do not reference the project, review process, or internal terminology. A real user would simply state what they want changed.

### When to stop iterating
Stop when either condition is true:

1. The 20-turn limit has been reached.
   - The original prompt counts as turn 1.
   - To count prompts quickly, use Ctrl + F or Cmd + F and search for “Thought for,” “Thought(s),” or “No response.”

2. The deliverable is flawless.
   - It meets all professional document standards.
   - It has zero content errors, misrepresentations, or factual inaccuracies.
   - It fulfills all prompt constraints that were not intentionally changed or dropped.

---

## 2. Standards

## General File Standards

### Fonts
- Use one or two fonts maximum.
- Additional fonts must have a clear purpose.
- Fonts must be used consistently throughout.
- Font sizes must follow a clear visual hierarchy.
- Font size and weight must be consistent, such as body text using the same size and headers using the same size.

### Alignment
- Pick one alignment approach and use it consistently.
- Bullet points and lists must always be left-aligned.

### Spacing
- Line spacing must be consistent.
- There must be enough spacing between sections, paragraphs, and elements so nothing feels crowded.
- Headings should have more space above than below.
- Tables, charts, and images need visible breathing room.
- Text inside table cells and text boxes needs padding.

### Bullets and lists
- Bullet points must use hanging indents.
- Bullet style must be consistent.
- Numbered lists must follow the same rule.

### Tables and charts
- All content must stay within margins.
- Chart labels must be visible and legible.
- Column alignment should make sense for the content.
- Font sizes within tables must be consistent across the document.

### Images and graphics
- Images must be properly sized and not distorted.
- Images should be placed between sections, not awkwardly wrapped.
- There should be no broken image icons.

### Content accuracy
- All facts, dates, and statistics must be accurate.
- Numbers in charts must match numbers in text.
- There must be no contradictions between sections.
- There must be no fabricated sources, citations, or statistics.
- There must be no spelling or grammar errors.

## PPTX Standards

### Font minimums

| Element | Minimum size |
|:--|:--|
| Body text | 16pt, or 14pt for larger letterforms like Arial |
| Captions and citations | 12pt |
| Headers, footers, page numbers in all caps | 10pt |

### Layout and visual balance
- Use one main idea per slide.
- Avoid walls of text.
- Keep on-slide text concise.
- Use a consistent slide layout throughout.
- Keep content balanced and centered.
- Add enough spacing between elements.

### Alignment
- Slide titles must be centered or left-aligned consistently across all slides.
- Body text must be left-aligned.
- Do not mix centered and left-aligned body text on the same slide.

### Tables
- Tables must fit within slide boundaries.
- If a table is too large, split it across multiple slides instead of shrinking the font.

### Charts and graphics
- Charts should be large enough to read without squinting.
- If labels overlap, use a different chart type, such as a horizontal bar chart.

### Example prompts for PPTX fixes
- “Enlarge the chart on slide 3 to fill the blank area on the bottom half.”
- “Redistribute the content on slide 6 so it is centered and balanced.”
- “Split slide 4 into two slides.”
- “Add padding between the text and the edge of the slide on slide 8.”
- “Left-align all body text on every slide.”
- “Redo the pie chart on slide 6 as a horizontal bar chart.”

## DOCX and PDF Standards

### Font minimums

| Element | Minimum size |
|:--|:--|
| Body text and figure captions | 12pt, or 10pt for larger letterforms like Arial |
| Headers and footers | 10pt |
| Footnotes | 9pt, with smallest body text at 11pt |

### Margins
- Standard margins should be 0.5 inch on all sides.
- Use 0.25 inch margins only for design-heavy one-pagers.
- Bottom margin should be at least 0.75 inch if there is a footer or page numbers.

### Alignment
- Body text should be left-aligned or justified consistently.
- If justified, hyphenation must be enabled.
- All body headings and subheadings must share the same alignment.

### Spacing and visual balance
- Body text line spacing should be 1.0 to 1.15.
- Headings should have more space above than below.
- Headings should never appear alone at the bottom of a page.
- Tables should not split across pages if they can fit on one page.
- Avoid single lines of a paragraph stranded at the top or bottom of a page.

### Page elements
- Page numbers must be present and consistent.
- Footers should be noticeably smaller than body text.
- Header and footer elements must span the full text width.

### Example prompts for DOCX and PDF fixes
- “Set all page margins to 0.5 inch.”
- “Left-align all body text and headings.”
- “Enable hyphenation to prevent rivers of white space.”
- “Add 12pt of space before each heading and 6pt after.”
- “Keep the table on page 3 together on one page.”
- “Add page numbers to the bottom right corner of every page.”

## Good File Checklist
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

---

## 3. Violations and Issues

## Troubleshooting Common Issues

| Problem | What to do |
|:--|:--|
| Model incorporates some changes but skips others | Rephrase the skipped edits clearly. |
| Model stalls on grouped edits | Reduce to 2–3 edits per turn, or 1 edit at a time as a last resort. |
| Same edit keeps failing | Switch focus to other changes and come back later. |
| Chart will not update | Ask for a different chart format, such as a horizontal bar chart. |
| Model cannot produce a good image | Upload your own image as a reference file. |
| Forgot to include a reference file | Add it mid-conversation and include it in the final ZIP. |
| Model’s first deliverable is very poor | Continue iterating because improvement is useful. |
| Stuck and nothing is working | Use: “Start from scratch and incorporate all of my feedback from this chat into a new version.” |

## Bad Deliverable Indicators

### Font issues
- Text is too small to read comfortably.
- Headings, subheadings, and body text use the same size or weight.
- Font sizes are inconsistent across the document.

### Spacing issues
- Content is squished together.
- Lines are packed too tightly or too loosely.
- Text is crammed against the edges of boxes, cells, or slide boundaries.
- Large areas of unused white space appear.
- Headings are orphaned.
- Single lines are stranded at the top or bottom of a page.
- Tables split across pages when they could fit on one page.
- White space on the last page is only an error if other formatting issues contribute to it.

### Alignment issues
- Content is crowded to one side.
- Left margins are not aligned consistently.
- Alignment is inconsistent across slides or pages.

### Margin issues
- Page margins are so small that content nearly touches the edge.
- Margins are too small to be printed.

### Bullet and list issues
- Continuation lines wrap back under the bullet character instead of using hanging indents.
- Bullet style is inconsistent throughout.

### Table and chart issues
- Tables extend beyond margins.
- Chart labels overlap, are missing, or are unreadable.
- Table columns use inconsistent alignment.

### Image issues
- Images are distorted or stretched.
- Broken image icons appear.
- Text inside images is too small or overlapping.

### Content accuracy issues
- The deliverable includes false statements.
- Sources, citations, or statistics are fabricated.
- Sections contradict each other.
- Numbers in charts do not match the text.
- Data is impossible, such as Q5, February 30, or wrong units.

### Frequently used names
- The deliverable uses names specifically flagged as common defaults: Alex Rivera, Elena Vargas, Summit, Apex, Horizon, or Meridian.

## Violations
- AI use in the prompt or iterations, including mentions of large language models, translators, grammar checkers, or paraphrasing tools.
- Duplicate prompts, meaning the same prompt and deliverable are used across multiple tasks, even if the reference file is changed.
- Editing outside Model, meaning the deliverable was downloaded, edited in native software, and reuploaded as the corrected deliverable.
- Personally identifying information that identifies a real person in the deliverable or prompt.
- Model interference, meaning prompts, iterations, or reference files attempt to override existing model behavior or change it to improve or affect Model’s performance in any way.
- Edited, regenerated, or restarted from a previous turn, meaning the user went back to a previous turn and edited the prompt, asked Model to regenerate from a previous turn, or restarted the conversation from a previous turn.
- Copied or pasted instructions without customization, including any prompt that includes large copied sections of the File Standards without tailoring them to the task.
- Including the user’s own name in the deliverable or prompt, such as “Prepared by [User Name]” or “As [User Name], I want...”

## Productive Turns
A productive turn is one where the user clearly looked at what Model produced and tried to improve it. The prompt must describe the issue and/or give specific instructions for how to fix it. It can include one change or multiple changes, as long as it clearly tries to improve the deliverable based on what Model produced.

### Productive turn exceptions
- If Model makes a mistake, such as wrong output or ignoring an instruction, the turn still counts toward the 20 total but is not penalized as long as the user responds appropriately.
- Re-submitting a prompt after an error message, no response, or stall is not penalized because this is expected troubleshooting.

## Unproductive Turns
- Repeating the same prompt after a valid output without changing the approach.
- Giving no direction, such as “Fix it,” “Please revise,” or “Make it better.”
- Spending more than 3 consecutive turns troubleshooting an issue where Model does not produce an output.
- Asking for the deliverable when it has already been generated and Model already said where the file was saved.
- Ignoring an obvious file failure, such as continuing to ask for fixes when a PDF is corrupted.

## Exceptions for Unproductive Turns
- No-effort prompts are not acceptable when a turn has no actionable information, such as “Fix it” or “It’s still broken.” A turn must include at least some detail.
- Repeating a failed prompt after valid output is allowed only when Model produced a valid output but did not make the change and the request is revised instead of repeated exactly.
