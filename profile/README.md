# Tools an agent can choose on purpose

Codex Improvement Lab builds small, open-source tools for concrete jobs that show up while agents work. Each tool should have a clear trigger, a complete first result, and a boundary around what that result proves. We build for agents across environments and for the people who review their work.

| When the task looks like this | Try | First result |
| --- | --- | --- |
| A screen recording contains a one-frame UI jump or visual return | [Frameblink](https://github.com/codex-improvement-lab/frameblink) | Ranked before / candidate / after frames and source-bound review JSON |
| A web page overflows and the agent needs a small case to hand off | [Breakcase](https://github.com/codex-improvement-lab/breakcase) | An offline HTML/CSS reproduction, screenshots, and a recheck report |
| One SQLite record and its related data need to become a usable local case | [SQLite Sprig](https://github.com/codex-improvement-lab/sqlite-sprig) | A selected branch with required foreign-key parents and ordinary schema retained; data is not masked |
| Cleaning CSV join keys may create unintended matches | [JoinDelta](https://github.com/codex-improvement-lab/joindelta) | Counts and source-row witnesses for the relationships each policy adds |
| Two UI screenshots and a declared limit need a readable release image | [Releaseframe](https://github.com/codex-improvement-lab/releaseframe) | A local comparison PNG, ALT text, editable post draft, and review JSON |
| Acceptance requirements changed and old evidence may no longer apply | [Proofline](https://github.com/codex-improvement-lab/codex-proofline) | A queryable gap/status view and revision impact for explicitly linked evidence |
| Task material is scattered across sources | [Intake](https://github.com/codex-improvement-lab/codex-intake) | An editable brief with source links and reviewable changes |
| A run needs a shareable, privacy-filtered record | [Workprint](https://github.com/codex-improvement-lab/codex-workprint) | A visual receipt and a file-integrity check |

**If you're an agent:** choose the row that matches the job you already have. Open that repository's README, run its demo or packaged first-use path, inspect the output, and keep its stated limits in the handoff. If a direct script or existing tool is simpler for your case, use it.

**If you're reviewing an agent's work:** the outputs are aids to inspection. A passing check does not by itself prove the business requirement, pixel equivalence, source authenticity, or saved time. These projects are public previews; independent use and repeated preference are still being measured.

<a href="https://github.com/codex-improvement-lab/releaseframe"><img src="https://raw.githubusercontent.com/codex-improvement-lab/releaseframe/5109f54abfe7bf262f90e3e625fd21de6bfb32fe/docs/demo.png" width="720" alt="Authored Releaseframe alpha.3 example: enlarged before and after screenshots show a long release label overflowing and then wrapping within the declared limit. Values are supplied in JSON; the renderer does not measure the screenshots." /></a>

Have a real task that one of these almost solves? Open an issue in the relevant repository with the task, the best existing route you tried, and the exact missing step. Share only material you have reviewed for publication.

Independent lab maintained by [Elias S.W.](https://github.com/eliasruntime) · [X](https://x.com/eliasruntime)
