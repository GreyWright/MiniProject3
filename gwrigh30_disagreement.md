# MiniProject3 — Disagreement Examples

**Greyson Wright (`gwrigh30`) and Hari Naicker (`hnaicker`)**  
**Discussion:** October 14, 2026, with a Discord follow-up

Hari and I compared our classifications against the project data, commit histories, and his original notebook. These are four examples of what we discussed and how we settled them.

## 1. VineCopula — Currentstatus

- **Hari (author):** Active
- **Me (validator):** Inactive
- **Final answer:** **Inactive — ValidatorKept**

The instructions say to check activity as of September 30, 2025. The last commit before that date was [March 24, 2025](https://github.com/tnagler/VineCopula/commit/7829d3b17cf1c214f6d074f248225b4005c087a7), which is before the April 1 cutoff for the six-month window. We agreed that later commits don't change whether the project was active at that earlier date. We used the same reasoning for AiiDA Tutorials and phuzzy.

## 2. deeptime — ActivityPattern

- **Hari (author CSV):** irregular
- **Me (validator):** U-shaped
- **Final answer:** **U-shaped — ValidatorKept**

His [notebook](https://github.com/hvnaick/MiniProject2/blob/master/hnaicker_vis.ipynb) actually describes deeptime's activity as U-shaped, although it also says the commits are irregular. The [activity plot](https://github.com/hvnaick/MiniProject2/blob/master/hnaicker_deeptime-ml_deeptime.png) shows the same broad drop and later increase. During the call, we talked about how the generated CSV labels didn't always match his written interpretation. We went with U-shaped for the overall trend.

There were similar notebook-versus-CSV differences for siibra-explorer, jwql, VineCopula, and phuzzy. We kept declining for those based on the long-term patterns discussed.

## 3. phuzzy — RecentThemes

- **Hari's original entry:** blank when I did the independent review
- **Hari's updated entry:** Bug fixes:Documentation updates
- **Me (validator):** Bug fixes:Other
- **Final answer:** **Bug fixes:Other — ValidatorKept**

Among the [ten most recent commits](https://github.com/lepy/phuzzy/commits), there are several fixes, but also tests, build and performance work, and a release. I didn't find documentation updates in that group, so I used Other as the second theme. Hari added his classification to the CSV after our call. I messaged him about the difference, and he agreed we could keep mine.

## 4. statistics-coded — RecentThemes

- **Hari's original entry:** blank when I did the independent review
- **Hari's updated entry:** Bug fixes:Documentation updates
- **Me (validator):** Other:Documentation updates
- **Final answer:** **Other:Documentation updates — ValidatorKept**

Several of the [recent commits](https://github.com/eurostat/statistics-coded/commits) just say `Add files via upload`, while others are README updates. I didn't think the generic uploads were enough evidence to call them bug fixes. We kept Other alongside Documentation updates after Hari confirmed my choice in Discord.

## How the missing entries were handled

Hari's `RecentThemes` column was blank for all ten projects when I reviewed his October 8 version. He filled it in on [October 14](https://github.com/hvnaick/MiniProject2/commit/ce22f8fef0cf3ba17212ed49705e8df333d433ae). Eight new entries matched my original classifications, while the two above needed a follow-up. I left the original blanks and the original No flags in my validation log instead of changing the before-discussion record.

That is why the resolution CSV has **18 flagged rows: eight differences in our original classifications and ten missing author entries**, rather than 18 disagreements about what the projects actually did. Hari's separate validation log covers his review of my ten projects.
