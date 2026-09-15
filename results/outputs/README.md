# Final Processed Dataset

Populated automatically when `../../group_pipeline.ipynb` is run: produces `mnist_processed.npz`, containing
the final processed train/test arrays (`X_train`, `y_train`, `y_train_onehot`, `X_test`, `y_test`,
`y_test_onehot`) after the full preprocessing pipeline (outlier removal → normalization → feature selection →
PCA dimension reduction → target encoding). This is the file the modeling stage (Step 3) should load from.
