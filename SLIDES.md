# October 14, 2026 deck: slide manifest

Slide URLs use numbers: https://cuny-ai-lab.github.io/cail-oct-14/#/3 opens slide 3.

CUNY AI Lab session, October 14, 2026, about 4:15 to 5:20. The audience is Aankit Patel (CUNY Central) and visiting guests. The format is informal, with questions invited throughout. Luke and Matt open with context, without slides. This reveal.js deck remixes slides from the ACH 2026 deck (`../ach-2026`) and two internal sources: the September 4 retreat "CUNY AI Infrastructure — Working Outline," the July position paper "AI Infrastructure for CUNY, by CUNY," and the August 15 five-slide Gateway overview, all in Drive.

Times are targets. The four sections run about 25 minutes, which leaves about 35 minutes for discussion.

| # | Presenter | Title | Source |
|---|---|---|---|
| 1 | all | CUNY AI Lab | ACH title slide |
| 2 | all | Origins | logos of the four units: TLC, GCDI and ASHP from the CAIL website repo, Mina Rees Library from MRL-GC-logo-blue.svg |
| 3 | Stefano | Infrastructure Decisions | new opener |
| 4 | Stefano | Guiding Principles | the four principles on ailab.gc.cuny.edu, each beside a practice; working outline III in notes |
| 5 | Stefano | Bottom Up Approach to AI Infrastructure | rewritten October 13: bottom-up operations; diagram redrawn from the ACH "CALI to CAIL" chart (13_cali_to_cail.png) with the four centers at equal weight |
| 6 | Stefano | Infrastructure | hosting diagram (Cloudflare Workers, AWS, New Media Lab) with the application/front door and request/Lab staff ways in; hosting from cail-knowledge-base, October 12 |
| 7 | Stefano | The Local Pipeline | split from slide 6; faster-whisper, pyannote 3.1, Qwen3-VL 8B and DeepSeek-OCR on the NML's RTX 5000 Ada workstation and Mac Studios (Mac Studios per Stefano, not in the knowledge base); installed parts from cail-knowledge-base, image description and OCR models are the ones we would run |
| 8 | Stefano | Sustaining and Sharing the Work | working outline V.B; position paper |
| 9 | Steve | The CAIL Gateway, Access and Agent Tools | new opener |
| 10 | Steve | The CAIL Gateway | five-slide Gateway deck 01 and 03, merged |
| 11 | Steve | Applying for Access | live request-access page; admin queue from a local run with sample data |
| 12 | Steve | Class Overview for Instructors | Doorway My classes page with sample data |
| 13 | Steve | Administration | admin People and class views with sample data; CAIL Admin MCP in notes |
| 14 | Steve | Agent Studio and Site Studio | ACH 39; real Agent Studio workspace screenshot |
| 15 | Steve | CAIL Pi | vault note "CAIL Pi", Fall 2026 workshops |
| 16 | Zach | Apps and Outreach | ACH 16 |
| 17 | Zach | The CAIL Sandbox | ACH 19 |
| 18 | Zach | Comparing Open-Weight Models | ACH 21 |
| 19 | Zach | Configurations for Courses | ACH 22 |
| 20 | Zach | AmigAI in Spanish Courses | ACH 25 |
| 21 | Zach | Tools Portal | ACH 38, new screenshot and bullets |
| 22 | Zach | Teaching Tools | screenshot supplied October 14, showing Stem Splitter and Systems Mapping |
| 23 | Zach | Demo | Vimeo video 1231478071, embedded; replaced the Who Has Access slide October 14 |
| 24 | all | Discussion | ACH 47 |

Stefano's section carries the commitments and the long view. Steve's Gateway slide shows where those commitments become working rules, so it does not repeat them. Open weights and zero retention live on slide 4, under the website's Transparency and Privacy by Design; provider switching is spoken on slide 10. Slide 6 names the providers.

## Spoken notes

Spoken notes live in the deck as reveal.js speaker notes (`<aside class="notes">` in `index.html`). Press `S` during the talk to open the speaker view.

## Open items

- Slides 11–13 use sample data. The admission screens come from a local copy of `cail-tools-admission` (Admission's admin page and Doorway's My classes page) filled with invented people at example.edu addresses, captured October 13. Only the application form on slide 11 is the live public page. The Plus allowance in the test fixture ($12.50) was set to the real $20 for the capture.

- Slides 18 and 19 show names in the Sandbox sidebars: course channels named after instructors, model-card authors, and two people's names. These came over from the ACH deck. Check them before a public audience.
- Slide 17's sign-in screenshot is from June and shows an email and password form above the CUNY Login button. Check it against the current sign-in page.
- The public Tools page (ailab.gc.cuny.edu/tools, Media Processing) still embeds the old transcription GIF, whose privacy notice says files go to Fireworks AI and AssemblyAI. That is a website fix, separate from this deck. Slide 21's screenshot is cropped above the GIF.
