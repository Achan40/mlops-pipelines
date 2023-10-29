# mlops-pipelines
ADSP 32021 ON01 Machine Learning Operations - Assignment 2 Pipelines

### Switching Data Versions with Git LFS

Assuming your dataset is being tracking using git lfs already.

1. Locate the commit ID of the data version that you want
2. Find the file path
3. Revert the file using: `git checkout [commit ID] -- path/to/file`

Note: Verify the lfs pointer using: `git lfs ls-files`. You may need to run `git lfs pull` to retrieve the data from the lfs server if you have not done so previously.