# Amadou Bocoum

### Data Science · Statistics · Machine Learning · Deep Learning

**[Explore my portfolio](https://bocoum1.github.io/portfolio/)**

I am a **second-year Master's student in Data Science and Statistical Modelling** at Université Bretagne Sud, with a background in mathematics and computer science.

My focus is on understanding statistical methods, implementing them and evaluating what the results actually support. I compare tabular models and neural networks through explicit experimental protocols, and explore algorithms through pathfinding experiments.

**Looking for a 4–6 month final-year internship starting in January 2027**, in data science, statistics or machine learning.

## Statistics: code, reports and experiments

| Project | Question and evidence | Tools |
| --- | --- | --- |
| [Recursive kernel estimation](https://github.com/Bocoum1/recursive-kernel-estimation) | Estimate the derivative of a noisy regression function; compare three kernels using Monte-Carlo MSE, bias and simulation uncertainty | R, nonparametric estimation, simulation |
| [Binomial GLMs](https://github.com/Bocoum1/binomia-glm) | Compare logit, probit and cloglog through Fisher scoring; check manual estimates against `stats::glm` | R, likelihood, numerical estimation, diagnostics |

Both are university projects coauthored with **Anya Levêque**. The repositories preserve the original work and add reproducibility checks, generated figures and explicit methodological limitations. Simulation results and in-sample fit are not presented as evidence of predictive generalisation.

## Machine learning and deep learning

| Project | Question and evidence | Tools |
| --- | --- | --- |
| [MNIST: linear model, MLP and CNN](https://github.com/Bocoum1/Mnist) | Compare three architectures with a fixed train/validation/test split and three training seeds; inspect learning curves, confusion and errors | Python, PyTorch, scikit-learn |
| [House Prices](https://github.com/Bocoum1/Kaggle/tree/main/house_prices) | Compare a constant baseline, Ridge, random forest and gradient boosting using five-fold CV; fit preprocessing within each fold and analyse held-out errors | Python, scikit-learn, pandas |

The CNN reaches **98.32% mean accuracy on the internal test split** of Kaggle
Digit Recognizer, not on an external evaluation or leaderboard. On House Prices,
Ridge improves log-RMSE and MAE over the baseline, but a large extrapolation error
worsens dollar RMSE and produces a negative R². The reports explain both the
results and their limitations. Datasets and trained weights are not included.

## Algorithms

[Pathfinding Lab](https://github.com/Bocoum1/Pathfinding-Lab) compares BFS,
Dijkstra, A*, greedy search and weighted A* on weighted grids. The
[interactive demo](https://bocoum1.github.io/Pathfinding-Lab/) replays exploration
traces computed in Julia, making path cost and search effort visible. My
[original Pathfinding project](https://github.com/Bocoum1/Pathfinding) remains
available separately.

## Complementary applications

| Project | Problem addressed | Stack |
| --- | --- | --- |
| [Local Hybrid RAG](https://github.com/Bocoum1/Retrieval-Augmented-Generation) | Ask questions about private documents while keeping generation local and citations inspectable | Python, FAISS, BM25, Ollama, Streamlit |
| [UKRA](https://github.com/Bocoum1/UKRA) | Explore when, where and under which conditions road accidents occur | R, Shiny, Plotly, Leaflet |
| [MoreMovies](https://github.com/Bocoum1/moremovies) | Reconcile three heterogeneous systems into a shared data warehouse for sales and rental analysis | MySQL, Pentaho PDI, Mondrian, MDX |

These projects complement my statistical work with data preparation, visualisation and application development.

## Methods and tools

- **Statistics:** inference, generalised linear models, nonparametric estimation, Monte-Carlo experiments.
- **Machine learning & deep learning:** supervised learning, dense and convolutional neural networks, Python, PyTorch.
- **Algorithms:** graph search, heuristics, path cost and exploration, Julia.
- **Analysis and communication:** R, SQL, visualisation, Shiny, reproducible reports.
- **Supporting engineering:** Git, automated checks, APIs and data pipelines.

My priorities: make assumptions explicit, separate fitting from evaluation, document uncertainty and respect the confidentiality of data.

## Contact

- Email: [bocoumoumar535@gmail.com](mailto:bocoumoumar535@gmail.com)
- Portfolio: [bocoum1.github.io/portfolio](https://bocoum1.github.io/portfolio/)
- GitHub: [@Bocoum1](https://github.com/Bocoum1)
