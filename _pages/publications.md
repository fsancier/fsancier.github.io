---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

\cvitem{Submitted}{J. Clelland, H. Colgate, D. DeFord, B. Malmskog, \textbf{F. Sancier-Barbosa}. Colorado in Context: Congressional Redistricting and Competing Fairness Criteria in Colorado. ArXiv: \href{https://arxiv.org/abs/2011.06049}{arxiv.org/abs/2011.06049}}

\cvitem{Accepted}{S. Flicker, \textbf{F. Sancier-Barbosa}, A. Moors, and L. Browne. A Closer Look at Relationship Structures: Relationship Satisfaction and Attachment among People who Practice Hierarchical and Non-Hierarchical Polyamory. \emph{Arquives of Sexual Behavior}.}

\cvitem{2020}{S. Flicker, \textbf{F. Sancier-Barbosa}, F. Afroz, F. Mohsin, and S. Saif. Marital Quality in Arranged and Couple-Initiated Marriages: The Role of Perceived Influence over Partner Selection. \emph{International Journal of Psychology}, vol. 55, no.4,  pp 629–637. DOI: \href{https://doi.org/10.1002/ijop.12622}{doi.org/10.1002/ijop.12622}.}

\cvitem{2020}{S. Flicker, \textbf{F. Sancier-Barbosa}, F. Afroz, F. Mohsin, and S. Saif. Attachment Hierarchies in Bangladeshi Women in Couple-Initiated and Arranged Marriages. \emph{International Journal of Psychology}, vol. 55, no.4,  pp 638–646. DOI: \href{https://doi.org/10.1002/ijop.12619}{doi.org/10.1002/ijop.12619}.}

\cvitem{2019}{\textbf{F. Sancier-Barbosa},  M. McDevitt, L. Siriwardena, D. Ellsworth. Empirical Testing of an Option Pricing Model with Memory. \emph{Proceedings of the Joint Statistical Meetings}, pp 1575-1579, American Statistical Association, 2019.}

\cvitem{2019}{\textbf{F. Sancier-Barbosa}. Defending with Two or Three Dice: What are the RISKs? \emph{Proceedings of the Recreational Mathematics colloquium VI}, Ludus Association, 2019.}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
