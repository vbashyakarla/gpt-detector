# gpt-detector

In July 2023, a team of Stanford researchers published a paper in CellPress Patterns entitled 
["GPT detectors are biased against non-native English writers"](https://doi.org/10.1016/j.patter.2023.100779).
The authors highlight that detectors enlisting detectors to distinguish between content that is AI-generated from content that is human-generated 
is a natural step in an effort to flag or identify AI-generated content that may be used to spread false information. 
However, the reliability, fairness, and robustness of the classifications output by these detectors remain underexplored.

Specifically, the study examines the performance of detectors on native vs. non-native English speakers. 
The authors write that, " Our findings reveal that these detectors consistently misclassify non-native English writing samples as AI-generated, whereas native 
writing samples are accurately identified." The finding that these detectors perform worse on non-native English speakers and tend to 
classify text from non-native speakers as AI-generated raises a number of ethical questions, including how such speakers may be inadvertantly penalized 
(e.g., in academic contexts via automated scans that flag plagiarised or AI-generated text) through the use of these technologies.

**There are two main goals for this exercise.** First, I attempt to indepdently replicate the authors' findings from the underlying data. 
Second, I hope to explore the paper's findings in greater depth than summarized in text and available furnished supplements. The accompanying analysis 
fulfills both of these goals.

## Project Structure
- `git-detector-bias.ipynb`: Analysis 
- `data/`: Source data
- `docs/`: [Rendered analysis](https://vbashyakarla.github.io/gpt-detector/git-detector-bias.html)
