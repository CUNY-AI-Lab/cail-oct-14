# October 14, 2026 deck: slide manifest

CUNY AI Lab session, October 14, 2026, about 4:15 to 5:20. The audience is Aankit Patel (CUNY Central) and visiting guests. The format is informal, with questions invited throughout. Luke and Matt open with context, without slides. This deck remixes the ACH 2026 deck (`../ach-2026`) and two internal sources: the September 4 retreat "CUNY AI Infrastructure — Working Outline" and the August 15 five-slide Gateway overview, both in Drive.

Times are targets. The four sections run about 25 minutes, which leaves about 35 minutes for discussion.

| # | data-slide | Presenter | Title | Source |
|---|---|---|---|---|
| 1 | `title` | all | CUNY AI Lab | ACH title slide, retitled |
| 2 | `break-stefano` | Stefano | Infrastructure Decisions and Procurement | new divider |
| 3 | `stefano-1` | Stefano | Handling Requests | retreat outline II.A, IV |
| 4 | `stefano-2` | Stefano | Services We Buy and Run | retreat outline V.A |
| 5 | `break-steve` | Steve | The CAIL Gateway and the Studios | new divider |
| 6 | `steve-gateway` | Steve | The CAIL Gateway | five-slide deck 01, redrawn in HTML |
| 7 | `steve-choices` | Steve | Gateway Design Decisions | retreat outline III, five-slide deck 03 |
| 8 | `steve-4` | Steve | Agent Studio and Site Studio | ACH 39, bullets rewritten; Agent Studio is now a real workspace screenshot |
| 9 | `steve-pi` | Steve | CAIL Pi | vault note "CAIL Pi", Fall 2026 workshops |
| 10 | `zach-intro` | Zach | Apps and Outreach | ACH 16, retitled |
| 11 | `zach-2` | Zach | The CAIL Sandbox | ACH 19, retitled |
| 12 | `zach-4` | Zach | Comparing Open-Weight Models | ACH 21, retitled |
| 13 | `zach-5` | Zach | Configurations for Courses | ACH 22, retitled |
| 14 | `zach-8` | Zach | AmigAI in Spanish Courses | ACH 25, retitled |
| 15 | `zach-tools` | Zach | Tools Portal | ACH 38, new screenshot and bullets |
| 16 | `zach-people` | Zach | Access and Outreach | new |
| 17 | `qa` | all | Discussion | ACH 47, retitled |

## Spoken notes

**Stefano, slide 4.** The slide does not name vendors. Say aloud what fits the room. Cloudflare is an Enterprise account. The AWS contract is close but not yet signed.

**Steve, slide 6.** Providers are deliberately unnamed. Production currently serves Workers AI and Bedrock; OpenRouter is no longer behind the Gateway. The Sandbox still has older direct connections outside the Gateway, so the diagram shows the Gateway path, not every Sandbox route.

**Steve, slide 7.** We made each of these choices. A vendor would make them differently. On Workers we pay only for the requests that come in. An always-on container on AWS, which is how the Sandbox runs, costs money every hour whether or not anyone is using it.

**Steve, slide 8.** Site Studio is still the HTML mock-up from the ACH deck. The Agent Studio workspace is a real screenshot of the current app, taken October 13 from a local run. The panels hold real OpenAlex results (search "generative AI" "higher education"), placed there directly rather than produced by the agent, and the prompt in the chat box was typed for the picture, not sent.

**Steve, slide 9.** Stefano maintains CAIL Pi and can take questions on it. The released version (0.3.0) is one `npx` command that installs Pi and asks for the person's Lab API key. A version that signs in with CUNY Login in the browser is in progress and not released. The terminal is the barrier for many people; Agent Studio and Site Studio offer agent help in the browser instead.

**Steve, slide 9, closing.** We can connect the Gateway to any provider that meets these rules, including a public one. Empire AI is the obvious candidate in New York. Keep this to a sentence or two.

**Zach, slides 11–14.** Use the ACH talk track (`../ach-2026/SLIDES.md`, "Zach — talk track"), except for its "Transparency and Privacy by Design" lines. That slide is not in this deck, and its provider list (OpenRouter, Google) and admin-readable chat claim are out of date or disputed.

**Zach, slide 16.** One number fits if wanted: about 200 people had access in late September, roughly a third of them through classes.

## Open items

- Slide 11's sign-in screenshot is from June and shows an email and password form above the CUNY Login button. Check it against the current sign-in page.
- The public Tools page (ailab.gc.cuny.edu/tools, Media Processing) still embeds the old transcription GIF, whose privacy notice says files go to Fireworks AI and AssemblyAI. That is a website fix, separate from this deck. Slide 15's screenshot is cropped above the GIF.
