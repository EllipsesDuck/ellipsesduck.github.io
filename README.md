# lixiaokang — Personal Homepage

**Website:** https://ellipsesduck.github.io/

Personal homepage for lixiaokang, an Advertising Algorithm Engineer at Alibaba who previously studied at the National University of Singapore.

## Research interests

- Generative recommendation
- Scaling up for search, advertising, and recommendation
- LLM agents and reinforcement learning

## Design and interaction

- Dark green palette with lime, blue, and warm orange accents
- Original animated particle field with three selectable research modes
- English and Chinese content, with a persistent language preference
- Persistent light/dark theme selection
- Responsive research cards and a career/education timeline
- Accessible tab navigation, reduced-motion support, and email copying

The particle field and card diagrams are conceptual illustrations, not measured research results. The site contains no analytics or tracking scripts.

## References collected for the redesign

- [User-provided guide](https://zhuanlan.zhihu.com/p/711554540): AcademicPages setup and academic profile structure.
- [AcademicPages](https://github.com/academicpages/academicpages.github.io) · [Demo](https://academicpages.github.io/): academic identity, section hierarchy, and navigation.
- [al-folio](https://github.com/alshedivat/al-folio) · [Demo](https://alshedivat.github.io/al-folio/): research content organization and theme switching.
- [Brittany Chiang](https://brittanychiang.com/) · [v4 source](https://github.com/bchiang7/v4): strong typography, dark palette, spacing, and restrained interaction.

The implementation is original HTML/CSS/JavaScript. No template code, example publications, or other people's profile content is copied.

## Edit and publish

All website markup, styles, and scripts are in `index.html`. Edit the English and Chinese strings together using the `data-en` and `data-zh` attributes. The interactive research captions are in the `modes` array.

Commit to `main` to deploy. No dependencies or build step are required. In **Settings → Pages**, the publishing source is **Deploy from a branch**, **main**, **/(root)**. `.nojekyll` keeps the site as plain static HTML.
