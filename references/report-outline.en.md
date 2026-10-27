# Report structure and length

This is the user's default reading-report template. Reorder sections, merge overlapping points, or rename them for the paper type while preserving coverage; every point does not need a separate section. Default to Chinese, 4–5 A4 pages, and approximately 2,500–3,500 Chinese characters of prose, with readable figures, tables, and references.

## Content order

**Opening: paper identity and specific research fields**

Give the title, authors, year, venue, and short name. Classify by specific task and object, such as “building point-cloud instance segmentation,” “monocular building reconstruction from oblique remote-sensing imagery,” or “dynamic novel-view synthesis / deformable 3D Gaussian splatting.” Do not automatically classify a visual backbone as a VLM or conflate semantic segmentation, instance segmentation, and 3D reconstruction.

**0. Task background**

For a reader unfamiliar with the field, explain the purpose, input data, required priors, and output form. Clarify the roles of time, viewpoints, point clouds, sensors, or external maps when relevant. Distinguish training supervision from inference inputs, per-scene optimization from general-purpose models, and coarse volumes from detailed geometry.

**1. One-sentence summary**

State which key idea addresses which problem, rather than merely rephrasing the title.

**2. One-paragraph summary and motivation**

In approximately 100–180 Chinese characters for the default language, summarize the bottleneck, core approach, most important result, and limits of the conclusion. Avoid repeating the task background.

**3. Timeline of prior approaches and their limitations**

Choose three to five stages or key works. Explain their approaches and the limitations attributed to them by the paper, then briefly assess whether those criticisms are justified or overstated. Clearly separate the authors' statements from your assessment. A complete field history is unnecessary.

**4. Direct foundations**

Identify the papers, backbones, pretrained models, datasets, and postprocessing on which the work builds. Label direct implementation foundations, conceptual predecessors, and comparison methods separately. Do not count established techniques and standard modules as new inventions.

**5. Core innovations and method modules**

Condense the method into two to four modules, explaining the obstacle each addresses and how they connect. Include an original method diagram or one or two key equations when useful. Explain symbols without listing every layer and loss. State the method's assumptions and scope.

**6. Experimental setup**

Cover datasets, regions or scenes, input resolution, sample counts and splits, supervision proportion, and baselines. Select useful details about epochs or steps, optimizer, learning rate, backbone, and hardware. Report available parameter counts, training time, memory or storage use, and FPS. Mark missing details as “not reported”; do not directly convert model file size into parameter count. Label configurations obtained from code separately from settings reported in the paper.

**7. Main results: quantitative and qualitative evidence together**

Use a compact table or figure for representative main results and necessary ablations, including important strong baselines, units, and whether higher or lower is better. Avoid reproducing every table.

When qualitative results are available, select one or two informative original figures, ideally retaining side-by-side ground truth, relevant baselines, and the proposed method. Explain specific improvements and defects. Do not omit representative failures, negative results, or supplementary counterexamples merely because they weaken the narrative. If visual comparisons are absent, state that rather than fabricating them.

**8. Support for the modules and broader applicability**

Assess whether ablations control relevant factors and whether data, compute, and architectural changes are confounded. Determine whether the results support claimed generalization, efficiency, geometry, or temporal properties. Distinguish “not tested,” “unclearly reported,” and observed failure.

**9. Quality and whether the approach is simple but effective**

Give a brief, balanced assessment grounded in evidence. Distinguish conceptual simplicity, implementation simplicity, and low resource costs. Do not substitute venue prestige for quality assessment or invent numerical scores.

**10. Future directions**

Suggest two or three directions tied to the identified limitations. Distinguish the authors' proposals from your own, and prioritize concrete comparisons or improvements worth testing.

**11. Significance and sources of novelty**

State whether the main contribution lies in methods, data, training mechanisms, engineering integration, or problem framing. Combinations can be novel, but identify what actually improved rather than making generic claims of significance.

**Closing: sources and reading scope**

List the main paper, supplements, and project or code sources actually used. Preserve stable URLs or DOIs, versions, original figure and table numbers, and key page references. Disclose gaps in full text, attachments, implementation verification, or reproduction. If another skill used requires tool attribution, place it in a tool-attribution note rather than treating it as experimental evidence.

## Suggested pagination

1. Research classification, task background, both summaries, and the prior-method timeline with limitations assessed.
2. Direct foundations, innovations, method diagram, and key mechanisms.
3. Experimental setup, compact main results, and necessary ablations.
4. One or two qualitative comparison figures and observations.
5. Evidence boundaries, quality assessment, future directions, sources of novelty, and references.

These page breaks are optional. Use four pages when the paper is short or lacks suitable figures; expand for complex papers or requests for more detail. Save space through selection and deduplication rather than shrinking fonts or cropping legends.
