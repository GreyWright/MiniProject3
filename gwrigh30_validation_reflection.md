# MiniProject3 — Validation Reflection

**Greyson Wright (`gwrigh30`)**  
**Partner:** Hari Naicker (`hnaicker`)

Most of my disagreements with Hari were about activity patterns. Some of his notebook descriptions didn't match the labels in his CSV. For example, he described siibra-explorer as declining and deeptime as U-shaped, while the CSV marked both irregular. We used the plots and the overall trends to settle those. The status disagreements were more straightforward. We had to use September 30, 2025 as the reference date, which meant VineCopula, phuzzy, and AiiDA Tutorials were Inactive even though they had newer commits afterward.

Recovery was harder to judge. Some projects were already slowing down before their longest gaps, with only occasional fixes or maintenance. pyAudioAnalysis had dependency updates merged after its gap, and deeptime returned to development work. Those were better signs of recovery than a single commit. In deforest-watch, one cleanup commit didn't seem like enough to say development had resumed. We ran into the same question with shellphish/driller. A long gap doesn't always mean a project is dead, but one new commit doesn't necessarily mean it's back either.

The other issue was missing data. Hari's original `RecentThemes` values were blank, so I classified the recent commits independently. Once he filled those values in, eight matched mine and we settled the other two. I kept the original blanks in my log instead of changing the pre-discussion record. This project showed me how easy it is to get different results from the same history if the time window, categories, or evidence aren't handled consistently. Commit messages can show what changed, but they don't always explain why someone stopped or started contributing.
