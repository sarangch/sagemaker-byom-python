# Sagemaker Bring Your Own Model Python

The code here will be used to showcase the Bring Your Own Model capabilities of Amazon Sagemaker.

## Instance Setup

In this Step, we will configure the Sagemaker Instance that we are going to use throughout this session.

### Add Repository

1. URL `https://github.com/purnesh/sagemaker-byom-python`
2. Branch Name `master`
3. Create **New Secret**
4. Add Repository

### Lifecycle Management

In this section we will configure the Lifecycle Policy for our Sagemaker instance

1. Go to create a new Lify 

```
#!/bin/bash

set -e
pip install --upgrade pip
git config --global user.name "<YOUR NAME>"
git config --global user.email "<YOUR@EMAIL>"
```

### Verification and Debugging

1. Go to Cloudwatch
2. Click on **Log Groups** in the left hand menu
3. Go to `/aws/sagemaker/NotebookInstances`
4. Click on the appropriate option to view logs

