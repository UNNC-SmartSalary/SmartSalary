# SmartSalary

## Basic Infomation

### Repository Structure

```markdown
.  
├── README.md
├── stop_words.txt
├── NLP_data_test.ipynb         // Initial model test @Kai Liang
├── test.ipynb                  // Initial model test @Mingyuan Zhu
└── data_preprocessing.ipynb    // Code for data preprocessing
```

### Notice

Perhaps we should divide our file to different parts, like clean, model..

&emsp;

### Objective

At current stage, we foucuse on matching **Tier 1** job tiles.

&emsp;

### Progress

- [ ] Data Cleaning [Notebook](data_preprocessing.ipynb)
  - [x] Keep pure words (with only english letter)
  - [ ] Remove non-engllish words (spell check)
  - [ ] Correct misspelled words
  - [x] Remove stop words
  - [x] Stemming
  - [ ] Lemmatization
- [ ] Model Building
  - [ ] TensorFlow
  - [ ] PyTorch
