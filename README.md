## Same Information In, Different Model Out: Understanding Representation's Effect on what classical models learn

### Scientific questions

We will answer the following:

1. Sensitivity to features: Do the predictions change when there is feature duplication, feature rescaling, feature removal or rotation? If yes, can we restore performance with hyperparameter tuning?
2. Representation and model selection: Can rotations result in a larger prediction error even with a close-to-optimal model chosen via cross validation?
3. Cross-validation leakage: Do the predictions change when there is observation duplication, or splitting the same subject recording over folds? Effect on model selection and generalization?

### Methodology

We explore 15 classical learning models including linear regression, Ridge, Lasso, Elastic Net, SVMs, k-NN, Decision Trees, random forests, PCA, k-means

Synthetic data (Gaussian) and 3 UCI datasets:
- Concrete Compressive Strength
- Parkinson's voice
- Parkinson's Telemonitoring


For comparing predictions, test error, model selection, and robustness, we conduct repeated experiments (with different seeds) and use paired confidence intervals

### Team

- [Akarapu Shyam Satya Siva Prasad](https://github.com/SHYAMAKARAPU)
- [Ben George](https://github.com/beeegee)
- [Nandavaram Shashi Pritham](https://github.com/prithamnandavaram)
- Paltasingi Abhishek Sonu

---

Indian Institute of Technology (IIT), Palakkad
