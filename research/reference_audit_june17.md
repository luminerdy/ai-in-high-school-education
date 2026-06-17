# Reference Audit

Date: June 17, 2026

Purpose: Check the references used in the AI education research notes and identify which are strong anchors, which should be used with caution, and which were cleaned up.

## Strong Anchor References

Use these confidently in the presentation.

| Source | Status | Notes |
|---|---|---|
| U.S. Department of Education, "Artificial Intelligence and the Future of Teaching and Learning," May 2023 | Verified | Official PDF. Strong for human-in-the-loop, inspectable/explainable/overridable AI, privacy, bias, and teacher-centered guidance. |
| RAND, "Uneven Adoption of Artificial Intelligence Tools Among U.S. Teachers and Principals," Feb. 11, 2025 | Verified | Primary research page confirms 25% teacher use, nearly 60% principal use, 18% guidance, and high-poverty guidance gap. |
| TeachAI, "AI Guidance for Schools Toolkit," 2025 | Verified | Strong practical guidance source for school/district/teacher AI guidance, policy review, professional learning, and parent/student communication. |
| TeachAI Policy Tracker | Verified | Good for showing that state guidance is expanding. Recheck exact state count before using a precise number in slides. |
| Common Sense Media, "The Dawn of the AI Era," Sept. 18, 2024 | Verified | Primary source page confirms seven in ten youth had used at least one type of GenAI tool and emphasizes schoolwork use plus parent/school communication gaps. |
| PLTW, "Principles of Artificial Intelligence" course information, 2026 | Local source reviewed, not publicly redistributed | Use only as a high-level referenced example. Do not publish PDFs or detailed lesson/activity sequencing in the public repo. |
| Microsoft Work Trend Index 2026 | Verified | Primary source confirms 2026 report, 20,000 AI-using workers surveyed, 49% cognitive-work Copilot conversations, quality control/critical thinking, and "starting point, not final answer" findings. Vendor source, so cite transparently. |
| World Economic Forum, "Future of Jobs Report 2025" | Verified | Official report page. Use for broad employer/workforce trends; remember it is global, not U.S.-only. |
| NIST AI Risk Management Framework | Verified | Official .gov page. Strong for risk management and trustworthy AI framing. |
| NIST Generative AI Profile, NIST AI 600-1 | Verified | Official DOI/PDF. Strong for GenAI-specific risks and risk-management framing. |
| AP coverage of FTC inquiry into AI companion chatbots and children/teens | Verified | Better general-news reference than secondary tech coverage for the FTC inquiry. |

## Academic References For AI Detection

Use these as support for "detectors are not enough."

| Source | Status | Notes |
|---|---|---|
| Liang et al., "GPT detectors are biased against non-native English writers," 2023 | Verified | Strong and widely cited. Supports fairness concerns around AI text detectors. |
| Gehring and Paassen, "Assessing LLM Text Detection in Educational Contexts," 2025 | Verified | Supports difficulty detecting intermediate human/AI contribution levels. |
| Davalos and Zhang, "AI Misuse in Education Is a Measurement Problem," 2026 | Verified via arXiv search result | Useful conceptual framing: learning visibility, not just detection. |
| Garland, "AI Detectors Fail Diverse Student Populations," 2026 | Verified via arXiv search result | Useful theoretical framing; use cautiously if audience prefers peer-reviewed sources. |

## References To Use With Caution

| Source / Claim | Issue | Recommendation |
|---|---|---|
| Pew teen ChatGPT schoolwork statistic: 26% in 2024, up from 13% in 2023 | The original Pew page was not directly retrievable during this audit, though the statistic is widely reported. | Use as a supporting point, not the central adoption statistic, unless you can cite Pew directly. |
| Exact TeachAI state guidance count | Policy tracker changes over time. | Say "many states" unless you recheck the tracker the day before the presentation. |
| Vendor workplace reports | Microsoft has a commercial stake in AI adoption. | Cite transparently and pair with WEF/RAND/government sources. |
| Local policy claims | Local district/state guidance has not been verified. | Do not imply local policy details unless you confirm them before Monday. |

## References Removed Or Replaced

- Replaced The Verge FTC chatbot inquiry reference with AP coverage in `ai_children_regulation_and_concerns.md`.
- Removed Financial Times and AP workplace-candidate links from `workplace_ai_candidate_skills_slide_notes.md` because WEF and Microsoft are enough for the workplace claims and are easier to cite cleanly.
- Removed the direct secondary-link citation for the Pew teen ChatGPT statistic from the main source list and added caution language. A primary Pew source would still be preferable.

## Presentation Citation Strategy

For slides, cite only a small set:

1. RAND for teacher/principal use and guidance gap.
2. Common Sense Media for teen GenAI use.
3. TeachAI for practical school guidance.
4. WEF and Microsoft for workplace skills.
5. U.S. Department of Education / NIST for human oversight and guardrails.
6. Liang et al. or Gehring/Paassen for AI detector limits.

Do not overload slides with citations. Put the broader source list in notes or a handout.
