# Profile cards

The English profile layout is inspired by [Lohit Kolluri](https://github.com/lohitkolluri), with project information specific to VpSanta3. The analytics also draw on [this profile customization guide](https://neusoftware.top/articles/2025/09/16/1758012543979.html).

- Activity and language cards: [GitHub Readme Stats Action](https://github.com/stats-organization/github-readme-stats-action), the maintained successor recommended by the original GitHub Readme Stats project.
- Streak: [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats).
- Icons: [Skill Icons](https://github.com/tandpfun/skill-icons). Vendored SVG files and the MIT license are in `assets/icons/`.

The `Refresh profile cards` workflow generates light and dark SVGs daily at 03:23 UTC. It can also be triggered manually. It uses the repository's built-in token and public statistics; no personal access token is needed. Generation runs with read-only repository permissions; the separate publishing job can write the generated images. A failed generation leaves the last successful images unchanged.

Language statistics measure code distribution across public repositories, not language proficiency. Statistics follow the respective upstream tools' definitions and are snapshots from the last successful workflow run. The profile does not display private repository names or content.

The original tutorial's shared statistics / trophy endpoints returned errors when checked, so they are not embedded as live dependencies. The centered introduction, local typing animation, link badges, and project table remain editable in `README.md` and `assets/`. The typing animation respects reduced-motion preferences. Compact contribution cards and wrapping statistic cards support narrow screens.
