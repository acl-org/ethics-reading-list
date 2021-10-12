# Ethics Reading List

A list of ethics related resources for researchers and practitioners of Natural Language Processing and Computational Linguistics.  This is a public list moderated by the current ACL Ethics Committee.  Please issue a pull request against the repository to have your suggestions discussed before they are approved for integration with the list.  Thanks!

This list is intentionally kept with simple formatting in Markdown to allow machine-readable processing of the resource.

_Last Updated: 2021 Oct 12_

Contributed by (please add/update your name as part of your pull request).

* Use APA style where possible.
* Add minimally a `paper` link to direct readers directly to the `.pdf` or metadata page (arXiv or ACL Anthology) of the paper.

# Contents
* [General Resources](#general-resources)
* [Evaluation](#evaluation)
* [Model Issues](#model-issues)
* [Biases](#biases)
* [Dual-Use](#dual-use)
* [Environmental Impact](#environmental-impact)

### General Resources 

* Monteiro, M. (2019). Ruined by design: How designers destroyed the world, and what we can do to fix it. Mule Design.

* Hovy, D., & Spruit, S. L. (2016, August). The social impact of natural language processing. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers) (pp. 591-598) doi:10.18653/v1/P16-2096. [[paper](https://www.aclweb.org/anthology/P16-2096)] 

* Schwartz, R., Dodge, J., Smith, N. A., & Etzioni, O. (2020). Green AI. Communications of the ACM, 63(12), 54-63. [[paper](http://arxiv.org/abs/1907.10597)]

* Aka, O., Burke, K., Bäuerle, A., Greer, C., & Mitchell, M. (2021). Measuring Model Biases in the Absence of Ground Truth. arXiv preprint arXiv:2103.03417. [[paper](https://arxiv.org/abs/2103.03417)]

* Ferraro, F., Mostafazadeh, N., Vanderwende, L., Devlin, J., Galley, M., & Mitchell, M. (2015). A survey of current datasets for vision and language research. arXiv preprint arXiv:1506.06833. doi:10.18653/v1/D15-1021
[[paper](https://www.aclweb.org/anthology/D15-1021)]

* Gebru, T., Morgenstern, J., Vecchione, B., Vaughan, J. W., Wallach, H., Daumé III, H., & Crawford, K. (2018). Datasheets for datasets. arXiv preprint arXiv:1803.09010. [[paper](http://arxiv.org/abs/1803.09010)]

* Fort, K., & Couillault, A. (2016, May). Yes, we care! results of the ethics and natural language processing surveys. In international Language Resources and Evaluation Conference (LREC) 2016. [[paper](https://hal.inria.fr/hal-01287467/file/EthicsAndNLPSurveys.pdf)]

* Amblard, M. (2016). Pour un TAL responsable. Traitement Automatique des Langues, 57(2), 21-45. [[paper](https://hal.inria.fr/hal-01414145)]

* Lefeuvre-Halftermeyer, A., Govaere, V., Antoine, J. Y., Allegre, W., Pouplin, S., Departe, J. P., ... & Spagnulo, A. (2016). Typologie des risques pour une analyse éthique de l'impact des technologies du TAL. Traitement Automatique des Langues, 57(2), 47-71.
[[paper](https://hal.archives-ouvertes.fr/hal-01501192)]

### Evaluation

* Nangia, N., Vania, C., Bhalerao, R., & Bowman, S. R. (2020). CrowS-pairs: A challenge dataset for measuring social biases in masked language models. arXiv preprint arXiv:2010.00133. doi:10.18653/v1/2020.emnlp-main.154 [[paper](https://www.aclweb.org/anthology/2020.emnlp-main.154)]

* Caliskan, A., Bryson, J. J., & Narayanan, A. (2017). Semantics derived automatically from language corpora contain human-like biases. Science, 356(6334), 183-186.

* Goldfarb-Tarrant, S., Marchant, R., Sanchez, R. M., Pandya, M., & Lopez, A. (2020). Intrinsic bias metrics do not correlate with application bias. arXiv preprint arXiv:2012.15859.

* Ethayarajh, K., & Jurafsky, D. (2020). Utility is in the eye of the user: A critique of NLP leaderboards. arXiv preprint arXiv:2009.13888. doi:10.18653/v1/2020.emnlp-main.393
[[paper](https://www.aclweb.org/anthology/2020.emnlp-main.393)]

* Caglayan, O., Madhyastha, P., & Specia, L. (2020). Curious case of language generation evaluation metrics: A cautionary tale. arXiv preprint arXiv:2010.13588. doi:10.18653/v1/2020.coling-main.210
[[paper](https://www.aclweb.org/anthology/2020.coling-main.210)]

* Mathur, N., Baldwin, T., & Cohn, T. (2020). Tangled up in BLEU: Reevaluating the evaluation of automatic machine translation evaluation metrics. arXiv preprint arXiv:2006.06264. doi:10.18653/v1/2020.acl-main.448
[[paper](https://www.aclweb.org/anthology/2020.acl-main.448)]

* Linzen, T. (2020). How can we accelerate progress towards human-like linguistic generalization?. arXiv preprint arXiv:2005.00955. doi:10.18653/v1/2020.acl-main.465 [[paper](https://www.aclweb.org/anthology/2020.acl-main.465)]

* Mathet, Y., & Widlöcher, A. (2016). Évaluation des annotations: ses principes et ses pièges. Traitement Automatique des Langues, 57(2), 73-98. [[paper](https://hal.archives-ouvertes.fr/hal-01712282)]

* Bregeon, D., Antoine, J. Y., Villaneau, J., & Lefeuvre-Halftermeyer, A. (2019). Redonner du sens à l’accord interannotateurs: vers une interprétation des mesures d’accord en termes de reproductibilité de l’annotation. Traitement Automatique des Langues, 60(2), 23.  [[paper](https://hal.archives-ouvertes.fr/hal-02375240)]

* Garnerin, M., Rossato, S., & Besacier, L. (2020). Pratiques d’évaluation en ASR et biais de performance (Evaluation methodology in ASR and performance bias). In Actes de la 6e conférence conjointe Journées d'Études sur la Parole (JEP, 33e édition), Traitement Automatique des Langues Naturelles (TALN, 27e édition), Rencontre des Étudiants Chercheurs en Informatique pour le Traitement Automatique des Langues (RÉCITAL, 22e édition). 2e atelier Éthique et TRaitemeNt Automatique des Langues (ETeRNAL) (pp. 1-9). [[paper](https://www.aclweb.org/anthology/2020.jeptalnrecital-eternal.1)]

### Model Issues

* Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021, March). On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?🦜. In Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (pp. 610-623). doi:10.1145/3442188.3445922 [[paper](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922)]

### Biases

* Blodgett, S. L., Barocas, S., Daumé III, H., & Wallach, H. (2020). Language (technology) is power: A critical survey of" bias" in NLP. arXiv preprint arXiv:2005.14050. doi:10.18653/v1/2020.acl-main.485
[[paper](https://www.aclweb.org/anthology/2020.acl-main.485)]

* Mohammad, S. M. (2020). Gender gap in natural language processing research: Disparities in authorship and citations. arXiv preprint arXiv:2005.00962. doi:10.18653/v1/2020.acl-main.702 [[paper](https://www.aclweb.org/anthology/2020.acl-main.702)]

* Schluter, N. (2018). The glass ceiling in NLP. In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing (pp. 2793-2798). doi:10.18653/v1/D18-1301
[[paper](https://www.aclweb.org/anthology/D18-1301)]

* Fort, K., & Névéol, A. (2018, January). Présence et représentation des femmes dans le traitement automatique des langues en France. In Penser la Recherche en Informatique comme pouvant être Située, Multidisciplinaire Et Genrée (PRISME-G).
[[paper](https://hal.archives-ouvertes.fr/hal-01683774)]

* Nissim, M., van Noord, R., & van der Goot, R. (2020). Fair is better than sensational: Man is to doctor as woman is to doctor. Computational Linguistics, 46(2), 487-497. doi:10.1162/coli\_a\_00379 [[paper](https://www.aclweb.org/anthology/2020.cl-2.7)]

### Dual Use
* Bonastre, J. F. (2020). 1990-2020: retours sur 30 ans d’échanges autour de l’identification de voix en milieu judiciaire. In 6e conférence conjointe Journées d'Études sur la Parole (JEP, 33e édition), Traitement Automatique des Langues Naturelles (TALN, 27e édition), Rencontre des Étudiants Chercheurs en Informatique pour le Traitement Automatique des Langues (RÉCITAL, 22e édition). 2e atelier Éthique et TRaitemeNt Automatique des Langues (ETeRNAL) (pp. 38-47). ATALA; AFCP.

### Environmental Impact

* Henderson, P., Hu, J., Romoff, J., Brunskill, E., Jurafsky, D., & Pineau, J. (2020). Towards the systematic reporting of the energy and carbon footprints of machine learning. Journal of Machine Learning Research, 21(248), 1-43. [[paper](https://www.jmlr.org/papers/volume21/20-312/20-312.pdf)]

* Lannelongue, L., Grealey, J., & Inouye, M. (2021). Green algorithms: Quantifying the carbon footprint of computation. Advanced Science, 2100707. doi:10.1002/advs.202100707
[[paper](https://onlinelibrary.wiley.com/doi/pdf/10.1002/advs.202100707)]

* Anthony, L. F. W., Kanding, B., & Selvan, R. (2020). Carbontracker: Tracking and predicting the carbon footprint of training deep learning models. arXiv preprint arXiv:2007.03051. [[paper](https://arxiv.org/pdf/2007.03051)]

* Strubell, E., Ganesh, A., & McCallum, A. (2019). Energy and policy considerations for deep learning in NLP. arXiv preprint arXiv:1906.02243. doi:10.18653/v1/P19-1355
[[paper](https://www.aclweb.org/anthology/P19-1355)]

[[paper]()]

