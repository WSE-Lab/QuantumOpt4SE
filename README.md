# Quantum Optimization for Software Engineering: A Survey

This is the artifact of our article, titled "Quantum Optimization for Software Engineering: A Survey", which is a systematic literature review (SLR) of applying quantum and quantum-inspired optimization techniques to solve software engineering problems relevant to optimization.

During the SLR, we have our raw data available:

+ [`initial_searching.csv`](data/initial_searching.csv): All the raw data for initial keyword searching is included in this file. We presented the details of the 2083 primary papers after removing duplicates across databases.
+ [`final_selection.csv`](data/final_selection.csv): The file saves the results for 76 primary papers in the final list, meaning that they all are used in our survey paper. All the papers included were derived from keyword searching and snowballing. The presented data encompass all the results displayed in our manuscript in response to the proposed research questions.
+ [`updated_selection.csv`](data/updated_selection.csv): The file records the originally 77 primary papers filtered by our criteria, where one paper removed from `final_selection.csv` and excluded by our survey paper is recovered now, since it has already been published at a journal.

# Updates

- 2026/4/12: We update data in [`final_selection.csv`](data/final_selection.csv) owing to the revision of our article. Now, there are 76 primary studies retained in our final list.
- 2026/10/8: We add a new file [`updated_selection.csv`](data/updated_selection.csv) with one paper recovered (i.e., [*Performance-Driven QUBO for Recommender Systems on Quantum Annealers*](https://dl.acm.org/doi/full/10.1145/3814611)), as this paper has been published in 2026. Despite only 76 primary studies discussed in [our TOSEM paper](https://dl.acm.org/doi/abs/10.1145/3816147) at that time, we are still willing to offer the original 77 primary studies whose collection follows our defined methodology to support future research.