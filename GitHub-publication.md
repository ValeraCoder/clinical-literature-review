# Research on GitHub

## Repository details

| Field | Value |
| --- | --- |
| Repository | [ValeraCoder/clinical-literature-review](https://github.com/ValeraCoder/clinical-literature-review) |
| Description | My literature search and review workflow for clinical psychology, psychiatry, and occupational therapy, with source-linked reviews, templates, and a Codex skill |
| Website | https://psihoprosnik.online/ |
| Topics | `clinical-psychology`, `occupational-therapy`, `psychiatry`, `mental-health`, `literature-review`, `literature-search`, `research-methodology`, `psychometrics`, `evidence-based-practice`, `evidence-synthesis`, `adhd`, `codex`, `agent-skills` |
| Release | [Research v0.2.0](https://github.com/ValeraCoder/clinical-literature-review/releases/tag/v0.2.0) |

I built Research to keep track of how I reach a conclusion from the literature. When I read that a treatment “helps,” I want to know what changed, who measured it, and how long the change lasted. Those details matter when I use a paper in my work as a clinical psychologist and occupational therapist

For example, my review of Work-MAP, Cog-Fun A, and CBT for adults with ADHD looks separately at symptom severity and how people manage everyday tasks. One study asked participants to rate their performance on work tasks they had chosen. Another measured symptoms. The review keeps those outcomes separate and links to the original sources so you can check my reading [Adult ADHD and occupational therapy](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/reviews/adult-adhd-occupational-therapy/README.md)

## What’s included

- Four source-linked reviews covering adult ADHD and occupational therapy, autism and ADHD, bright-light therapy and depression, and borderline personality disorder [Review index](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/README.md)
- A search guide, a search log template, and a source card for recording what a paper measured and where to check it [Search guide](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/docs/search-guide.md) · [Search log](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/templates/search-log.md) · [Source card](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/templates/source-card.md)
- A Codex skill for running the workflow with the materials and tools available in your session [Research Literature skill](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/.agents/skills/research-literature/SKILL.md)

The reviews and guides in this repository are in Russian

## Quick start

| I want to… | Mode | What I get |
| --- | --- | --- |
| Get oriented on a new topic | **Search** | Relevant papers, a brief answer, and questions the available evidence leaves open |
| Compare studies or approaches | **Review** | A comparison of study populations, methods, outcomes, and limitations |
| Verify a figure, method, or quotation | **Single-source analysis** | An answer tied to a passage or table, with a note on which parts of the source were accessible |

In Codex, I open the repository folder and invoke `$research-literature` with a request like one of these

```text
$research-literature Search + web: Find studies of occupational therapy for adults with ADHD that report outcomes for daily tasks at home or at work
$research-literature Review + web: Compare Work-MAP, Cog-Fun A, and CBT for adults with ADHD. Report daily functioning and symptom outcomes separately
$research-literature Analyze this paper: https://doi.org/10.1177/15394492231159902 — who was included in the analysis, and what did the researchers measure at three months?
```

You can also follow the workflow by hand. Search the databases you can access and record your queries, sources, and decisions in the log. I use the source card to save the study population, the outcome, and the table or passage behind a claim

## Search coverage

In my own setup, I search a local library by keyword and by meaning. I use historical materials to trace how a term or method developed. For new studies, trial registrations, and current guidelines, I use scholarly databases and the open web. When I need an earlier version of a page, I check a web archive and record what I could access

I log searches in different languages separately. The adult ADHD review includes queries in seven languages. This release contains the workflow and the materials needed to follow it with sources you can access. I maintain the private library and its indexes in my own setup [How the search works](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/docs/how-it-works.md) · [Adult ADHD search log](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/reviews/adult-adhd-occupational-therapy/search-log.md)

## Credits

I drew on Deep Research and ECC when setting up the workflow, used Nature Paper X-Ray for close reading, and consulted psychometrics resources to assess measurement scales. I tried Google Scholar during setup, where a CAPTCHA stopped the test. For the adult ADHD review, I used other databases. The credits document distinguishes the tools I used in reviews from those I configured or tested [Tools and source repositories](https://github.com/ValeraCoder/clinical-literature-review/blob/v0.2.0/docs/tools-and-credits.md)

## Support

If you’d like to support my work on Research, you can find me on [Boosty](https://boosty.to/lususnaturaes)

## Author

I’m **Dmitry Timoshenko**, a clinical psychologist, occupational therapist, and licensed healthcare professional. I run Research as an independent educational project and share these reviews to help readers understand the evidence. Diagnosis and treatment decisions require an individual assessment

[My website](https://psihoprosnik.online/) · [Tools lab](https://psihoprosnik.online/laboratory.html) · [MimirLab](https://psihoprosnik.online/mimirlab.html) · [Modus](https://psihoprosnik.online/modus/) · [EMDR_free](https://psihoprosnik.online/emdr-free/)

[Contact me on Telegram](https://t.me/yahochushaslik) · [Psihoprosnik bot](https://t.me/psihoprosnikbot) · [GitHub](https://github.com/ValeraCoder)
