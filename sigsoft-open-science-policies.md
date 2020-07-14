# Open science policies

## Introduction

The present document constitutes a blueprint for generating open science policies and instructions for reviewers for research venues. We developed the policies over time for academic conferences of the software engineering community under the ACM [SIGSOFT](https://sigsoft.org) open science initiative. The policies should also work for software engineering journals and all computer science disciplines.

The rationale and background for the content of the policies are available here: [https://ineed.coffee/5836/effectiveness-of-open-science-policies-at-esec-fse-2019/](https://ineed.coffee/5836/effectiveness-of-open-science-policies-at-esec-fse-2019/).

#### Instructions

We recommend each venue to have a role for open science (e.g., the open science chair or a program committee chair) to be responsible for the policies. The responsible person should act as a bridge between persons with editorial roles (e.g., program committee chairs, associate editors) and authors of papers. The responsible person should take care of uploading the policies to the venue website and network with the venue organization for the useful application of the policies. Examples include: ensure proper visibility of the policies in Call for Papers; collaborate with research track chairs and artifact evaluation chairs to maximize openness and avoiding reinventing the wheel; ensure that program committee members are informed about the policies; answer questions of authors and reviewers.

The text of the policies starts from [OPEN_SCIENCE_POLICIES] and ends and at [/OPEN_SCIENCE_POLICIES].

The text of the instructions for reviewers starts from [INSTRUCTIONS_REVIEWERS] and ends at [/INSTRUCTIONS_REVIEWERS].

Please replace the following variables in the text:

#### Variables to set

- [VENUE_NAME] - e.g., ESEC/FSE 2020, ICSE 2020
- [VENUE_FIELD] - e.g., software engineering, empirical software engineering
- [CHAIR_NAME] - e.g., Jane Doe
- [CHAIR_EMAIL] - e.g., jane DOT doe AT university DOT edu
- [POLICIES_URL] - e.g., https://conference.name/open-science-policies

[OPEN_SCIENCE_POLICIES]

## Open science policies

Openness in science is key to fostering progress via transparency and availability of all outputs produced at each investigative steps. Transparency and availability of research outputs allow better reproducibility, replicability of quantitative studies and recoverability of qualitative studies. Open science builds the core for excellence in evidence-based research.

As an internationally renowned forum for researchers, practitioners, and educators to present and discuss the most recent innovations, trends, experiences, and challenges in the field of [VENUE_FIELD], [VENUE_NAME] has decided to actively support setting standards for how we conduct this kind of research.

To this end, we have explicitly committed ourselves to foster openness to our research outcomes. In particular, we support the adoption of open data and open source principles. We encourage all contributing authors to disclose the (anonymized and curated) data to increase reproducibility, replicability, and/or recoverability of the studies.

#### Principles

Research output should be publicly and freely accessible by anyone, permanently.

Artifacts related to a study (which include, but are not limited to, raw and transformed data, extended proofs, appendices, analysis scripts, software, virtual machines and containers, and qualitative codebooks) and the paper itself should, in principle, be made available on the Internet:

1. without any barrier (e.g., paywalls, registration forms, request mechanisms),
2. under a proper [open license](https://pantonprinciples.org/) that specifies purposes for re-use and repurposing,
3. properly [archived and preserved](https://en.wikipedia.org/wiki/Research_data_archiving),

provided that there are no ethical, legal, technical, economic, or sensible barriers preventing the disclosure.

#### Open artifacts

Fostering artifacts as open data and open source should be done as:

- Archived on preserved digital repositories such as [zenodo.org](https://zenodo.org), [figshare.com](https://figshare.com), [www.softwareheritage.org](https://www.softwareheritage.org), [osf.io](https://osf.io), or institutional repositories.
- GitHub, GitLab, and similar services for version control systems do not offer properly archived and preserved data.
- Personal or institutional websites, consumer cloud storage such as Dropbox, or services such as Academia.edu and Researchgate.net do not provide properly archived and preserved data.
- Released under a proper open data license such as the [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) dedication or the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license when publishing the data.
- Software can be released under an [open source license](https://opensource.org/licenses).
- Different open licenses, if mandated by institutions or regulations, are also permitted.

We encourage authors to make artifacts available upon submission (either privately or publicly) and upon acceptance (publicly).

###### Supporting statement

We ask authors to provide a supporting statement on the data availability (or lack thereof) in their submitted papers in a section named _Data Availability_ after the _Conclusion_ section.

Authors who cannot disclose data for the reasons stated in the principles of the policies should provide a short statement in their submitted papers in a section named _Data Availability_ after the _Conclusion_ section.

Please note that the success of the open science initiative depends on the willingness (and possibilities) of authors to disclose their data and that all submissions will undergo the same review process independent of whether they disclose their analysis code or data.

###### HOWTOs
A step-by-step approach to disclosing artifacts for (double-blind) peer review and make it open data upon acceptance is available at: [https://ineed.coffee/5205/how-to-disclose-data-for-double-blind-review-and-make-it-archived-open-data-upon-acceptance/](https://ineed.coffee/5205/how-to-disclose-data-for-double-blind-review-and-make-it-archived-open-data-upon-acceptance/).

A step-by-step approach to automatically archive a GitHub repository to Zenodo.org is available at [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/).

A step-by-step approach to automatically archive a GitHub repository to figshare.com is available at [https://knowledge.figshare.com/articles/item/how-to-connect-figshare-with-your-github-account](https://knowledge.figshare.com/articles/item/how-to-connect-figshare-with-your-github-account).

A proposal for artifact evaluation by SIGSOFT is available at [https://github.com/acmsigsoft/artifact-evaluation](https://github.com/acmsigsoft/artifact-evaluation).

A proposal for open science in software engineering, including explanations for structuring an open artifact, is available at [https://arxiv.org/abs/1904.06499](https://arxiv.org/abs/1904.06499).

#### Open Access
We encourage [VENUE_NAME] authors to self-archive their pre- and post-prints in open and preserved repositories. Self-archiving is legal and allowed by most publishers (granted in the copyright transfer agreement), and it will enable anybody in the world to reach papers barrier-free.

Upon acceptance to [VENUE_NAME], we encourage authors to revise their article according to the peers' comments, generate a PDF version of it (post-print), and submit it to [arXiv.org](https://arxiv.org) or their institutional repository.

Note: Authors are not allowed to self-archive the PDF of the published article as typeset by the publisher (a.k.a. "publisher proof," "published paper," "the digital library version").

###### HOWTOs

A comprehensive FAQ for open access and self-archiving is available at [https://avandeursen.com/2016/11/06/green-open-access-faq/](https://avandeursen.com/2016/11/06/green-open-access-faq/).

#### Support

In case of questions, please approach the Open Science Chair [CHAIR_NAME] via e-mail ([CHAIR_EMAIL]) at any time.

Contacting the open science chair does not violate the double-blind of submissions.

[/OPEN_SCIENCE_POLICIES]

[INSTRUCTIONS_REVIEWERS]

## Instructions for reviewers

[VENUE_NAME] has adopted an open science stance and introduced guidelines for authors (available at [POLICIES_URL]). The policies invite authors to provide all research artifacts for peer review, self-archive their pre- and post-prints, and archive artifacts as open data upon acceptance. We kindly ask you to pay attention to the following, while reviewing:

1. All open science steps are optional for authors and reviewers.
You are invited, but not required, to inspect the provided artifacts as part of your review efforts.
2. All reasons for partial disclosure of data (or lack thereof) should be trusted.
3. Submissions have to undergo the same review process independent of whether they disclose their analysis code or data.
You are invited to complain in your review of any absence of data, but please do not let it influence your review of submissions. You are free to welcome further disclosure of data and help authors in doing so, with your review.
4. Open science is challenging for qualitative studies. Please be welcoming of qualitative studies which open their artifacts even in a limited way. Furthermore, when evaluating artifacts from qualitative studies that was made available for peer review, please keep in mind that authors of qualitative studies might have underlying ontological and epistemological stances that differ from those of authors of quantitative studies. Concepts such as replicability and reproducibility might apply partially or not apply at all with qualitative studies.
5. Providing research artifacts might introduce issues with double-blind reviews.
We ask you not to actively hunt the identity of authors, especially in case they self-archived a preprint of their submission.

[/INSTRUCTIONS_REVIEWERS]

## Location

An always updated version of the open science policies is available at:

- [**Live**; HTML] at [https://ineed.coffee/open-science-policies](https://ineed.coffee/open-science-policies).
- [**Contribution, Feedback**; Markdown, PDF] at [https://github.com/acmsigsoft/open-science-policies](https://github.com/acmsigsoft/open-science-policies).
- [**Archived**; Markdown, PDF] TBD.

## License

[Open science policies](https://ineed.coffee/open-science-policies) by [Daniel Graziotin](https://ineed.coffee) is licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).