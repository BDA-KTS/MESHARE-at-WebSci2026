# [MEthods SHAring REtreat (MESHARE)](https://methodshub.gesis.org/community/websci26-meshare/) at [WebSci2026](https://websci26.org/?page_id=705)

Computational methods are central to modern research across disciplines, spanning all stages of the research pipeline from data collection and preprocessing to enrichment, analysis, and visualization. When these methods are reproducible, they not only enable verification of research findings but also provide a foundation for extension and refinement, allowing researchers to improve results and make more effective use of available resources. In MESHARE, the participants will use Methods Hub and its integrated services to develop and review computationally reproducible methods for processing web data.

## Learning Objectives

- Foster a collaborative, retreat-style environment in which participants can develop and refine computational methods with consistent, transparent documentation.
- Reduce technical barriers to achieving consistent and reliable results with computational methods.
- Support researchers in enhancing computational reproducibility across current projects, as well as legacy and newly developed methods.

## Target audience

- Basic programming skills in Python or R with basic GitHub understanding. 
- Researchers with legacy, in-progress, or new ideas for computational methods.
- New or experienced researchers to learn or refresh on developing computationally reproducible methods. 

## Setting up the computational environment

## Duration

MESHARE is a full-day event.

*Morning session*

| Duration | Activity                    | Description                                                                 |
|----------|-----------------------------|-----------------------------------------------------------------------------|
| 45 min   | Introduction                | Introduction to 1. Methods Hub, 2. Developer resources, and 3. Execution environments |
| 30 min   | Example method showcase     | Demo of a selected published method on Methods Hub                          |
| 15 min   | Method brainstorming        | Participants pitch ideas for methods to work on (organizers too for participants without their own) |
| 30 min   | Coffee break                | —                                                                           |
| 10 min   | Method selection            | Choose your own method, start a new one, or choose from the organizer's list of methods as a GitHub repository.   |
| 50 min   | Method development I        | Method development using the Methods Hub guidelines and resources.          |

*Afternoon session*

| Duration | Activity                    | Description                                                                 |
|----------|-----------------------------|-----------------------------------------------------------------------------|
| 15 min   | Experience exchange         | Participants discuss the insights gained and challenges faced.              |
| 75 min   | Method development II       | Method development using the Methods Hub guidelines and resources.          |
| 30 min   | Coffee break                | —                                                                           |
| 15 min   | Method review               | Generating automated method review, cross-reviewing each other's methods    |
| 45 min   | Method presentation         | Collective reflection and concluding discussion                             |

## Social Science Use Cases

A social scientist interested in developing reproducible computational methods to help reproduce the research findings and reuse the method for future enhancements.

## Activity / Information

- Participants can work individually or in pairs.
- Participants should share their method GitHub repository in reply to the [issue](https://github.com/BDA-KTS/MESHARE-at-WebSci2026/issues/1).
- *Info: On exiting the interactive environment execution container, the code and data are also deleted.*

## Task 1

1. Install cookiecutter and deploy the method structure on your local machine by following the "How to Use" step in [https://github.com/BDA-KTS/MethodsHub-method-template/blob/main/README.md](https://github.com/BDA-KTS/MethodsHub-method-template/blob/main/README.md).
2. Bring existing code to the method directory, if any 
3. Push your method directory to GitHub
4. Add input data file(s) to the *Data* subdirectory
5. Open your method on mybinder by providing the GitHub repository link to [https://mybinder.org/](https://mybinder.org/).

## Task 2
- Install the required packages
- Modify and extend your method code in the interactive environment (using scripts or notebooks)
- Modify README

## Task 3
- Check CITATION.CFF if any changes are required (*it has already preloaded values from the project*)
- Check if the output data is correctly written to the *Data* subdirectory
- Preserve the virtual enviornment

## Task 4
- Download the working updated method
- Upload to your GitHub method repository
- Execute the method workflow using (...)
- Review your method auto-generated compliance report
  
## Outcome

- Theoretical and practical knowledge of computational reproducibility standards.
- Preserving the virtual working environment of computational methods.
- Hands-on experience of transforming untidy scripts into reproducible, reusable, and shareable contributions.
- Developing accurate, complete, and structured method documentation.
- In the longer run, the skills acquired contribute to open science, transparency, collaborative research, and building
on existing reusable modules.

## Useful Links

- [Methods Hub](https://methodshub.gesis.org/)
- [Methods Hub Developer resources](https://github.com/GESIS-Methods-Hub/guidelines)
- [Methods Hub published methods and tutorials list](https://methodshub.gesis.org/search/?source=%7B%22query%22%3A%7B%22bool%22%3A%7B%22must%22%3A%7B%22match_all%22%3A%7B%7D%7D%2C%22filter%22%3A%5B%7B%22term%22%3A%7B%22type%22%3A%22all_methodshub%22%7D%7D%5D%7D%7D%7D&lang=en)
- [Methods Hub automated method review](https://github.com/BDA-KTS/check_workflow_central_repo)
- [Methods Hub community outreach](https://methodshub.gesis.org/community/)
- [Methods Hub taxonomy](https://methodshub.gesis.org/submit/taxonomy/)
- [MyBinder execution](https://mybinder.org/)

## Conclusion

## Contact Us
Methods Hub Team <methodshub@gesis.org>

## References

[1] Althea A Archmiller, Andrew D Johnson, Jane Nolan, Margaret Edwards, Lisa H Elliott, Jake M Ferguson, Fabiola Iannarilli, Juliana Vélez, Kelsey Vitense, Douglas H Johnson, et al. 2020. Computational reproducibility in The Wildlife Society’s flagship journals. The Journal of Wildlife Management 84, 5 (2020), 1012–1017.

[2] Philipp Knöpfle, Mario Haim, and Johannes Breuer. 2024. Key topic or bare necessity? How research ethics are addressed and discussed in computational communication science. Publizistik 69, 3 (2024), 333–356.

[3] Fakhri Momeni, Muhammad Taimoor Khan, Johannes Kiesel, and Tony Ross-Hellauer. 2025. Checklists for Computational Reproducibility in Social Sciences: Insights from Literature and Survey Evaluation. In 3rd ACM Conference for Reproducibility and Replicability (REP 2025), Thomas Pasquier, Ashish Gehani, and Khalid Belhajjame (Eds.). ACM, 179–191. doi:10.1145/3736731.3746161

[4] Sheeba Samuel and Daniel Mietchen. 2024. Computational reproducibility of Jupyter notebooks from biomedical publications. GigaScience 13 (2024), giad113.

[5] David Schoch, Chung-hong Chan, Claudia Wagner, and Arnim Bleier. 2024. Computational reproducibility in computational social science. EPJ Data Science 13, 1 (2024), 75.

[6] Harald Semmelrock, Tony Ross-Hellauer, Simone Kopeinik, Dieter Theiler, Armin Haberl, Stefan Thalmann, and Dominik Kowald. 2025. Reproducibility in machine learning-based research: Overview, barriers, and drivers. AI Magazine 46, 2 (2025), e70002.
