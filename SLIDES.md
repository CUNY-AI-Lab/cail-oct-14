# October 14, 2026 deck: slide manifest

CUNY AI Lab session, October 14, 2026, about 4:15 to 5:20. The audience is Aankit Patel (CUNY Central) and visiting guests. The format is informal, with questions invited throughout. This deck remixes the ACH 2026 deck (`../ach-2026`) and two internal sources: the September 4 retreat "CUNY AI Infrastructure — Working Outline" and the August 15 five-slide Gateway overview, both in Drive.

Times are targets. The four sections run about 25 minutes, which leaves about 35 minutes for discussion.

| # | data-slide | Presenter | Title | Source |
|---|---|---|---|---|
| 1 | `title` | all | CUNY AI Lab | ACH title slide, retitled |
| 2 | `break-luke` | Luke, Matt | Context | new divider |
| 3 | `matt-1` | Matt | CUNY and the Graduate Center | ACH 3, retitled (optional) |
| 4 | `luke-precursors` | Luke | Projects Before the CUNY AI Lab | ACH 17 (Zach's flowchart), relabeled (optional) |
| 5 | `break-stefano` | Stefano | Infrastructure Decisions and Procurement | new divider |
| 6 | `stefano-1` | Stefano | Handling Requests | retreat outline II.A, IV |
| 7 | `stefano-2` | Stefano | Services We Buy and Run | retreat outline V.A |
| 8 | `break-steve` | Steve | The CAIL Gateway and the Studios | new divider |
| 9 | `steve-gateway` | Steve | The CAIL Gateway | five-slide deck 01, redrawn in HTML |
| 10 | `steve-access` | Steve | Getting Access | five-slide deck 02 |
| 11 | `steve-choices` | Steve | Gateway Design Decisions | retreat outline III, five-slide deck 03 |
| 12 | `steve-4` | Steve | Agent Studio and Site Studio | ACH 39, bullets rewritten |
| 13 | `zach-intro` | Zach | Apps and Outreach | ACH 16, retitled |
| 14 | `zach-2` | Zach | The CAIL Sandbox | ACH 19, retitled |
| 15 | `zach-4` | Zach | Comparing Open-Weight Models | ACH 21, retitled |
| 16 | `zach-5` | Zach | Configurations for Courses | ACH 22, retitled |
| 17 | `zach-8` | Zach | AmigAI in Spanish Courses | ACH 25, retitled |
| 18 | `zach-tools` | Zach | Tools Portal | ACH 38, new screenshot and bullets |
| 19 | `zach-people` | Zach | Access and Outreach | new |
| 20 | `qa` | all | Discussion | ACH 47, retitled |

## Spoken notes

**Stefano, slide 7.** The slide does not name vendors. Say aloud what fits the room. Cloudflare is an Enterprise account. The AWS contract is close but not yet signed.

**Steve, slide 9.** The diagram keeps the five-slide deck's "Other routes" box: local models and other services. Providers are deliberately unnamed. Production currently serves Workers AI and Bedrock; OpenRouter is no longer behind the Gateway.

**Steve, slide 11.** None of these choices came with the technology. A vendor would decide each one differently.

**Steve, slide 12, closing.** The Gateway doesn't care where a model runs, so a public provider could sit behind it. Empire AI is the obvious candidate in New York. Keep this to a sentence or two.

**Zach, slides 14–17.** Use the ACH talk track (`../ach-2026/SLIDES.md`, "Zach — talk track"), except for its "Transparency and Privacy by Design" lines. That slide is not in this deck, and its provider list (OpenRouter, Google) and admin-readable chat claim are out of date or disputed.

**Zach, slide 19.** One number fits if wanted: about 200 people had access in late September, roughly a third of them through classes.

## Open items

- Slide 14's sign-in screenshot is from June and shows an email and password form above the CUNY Login button. Check it against the current sign-in page.
- The public Tools page (ailab.gc.cuny.edu/tools, Media Processing) still embeds the old transcription GIF, whose privacy notice says files go to Fireworks AI and AssemblyAI. That is a website fix, separate from this deck. Slide 18's screenshot is cropped above the GIF.
- Luke and Matt may not use slides 3 and 4. Delete them if not.
