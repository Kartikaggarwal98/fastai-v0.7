# fast.ai 

## Maintable version of fastai-v0.7
The fast.ai deep learning library, lessons, and tutorials. 

Copyright 2017 onwards, Jeremy Howard. Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. A copy of the License is provided in the LICENSE file in this repository.

## Current Status
Minior issues fixed, please install this instead of pip version.

Most of the library is quite well tested since many students have used it to complete the [Practical Deep Learning for Coders](http://course.fast.ai) course. However it hasn't been widely used yet outside of the course, so you may find some missing features or rough edges. 


## To install
You can install this library in the local environment using `pip install git+https://github.com/kartikaggarwal98/fastai-v0.7`


## To test
Before submitting a pull request, run the unit tests:

1. Activate Python environment: `conda activate fastai`
    - If this fails, use instead: `source activate fastai`
1. Run tests: `pytest tests`

### To run specific test file
1. Activate Python environment: `conda activate fastai`
    - If this fails, use instead: `source activate fastai`
1. `pytest tests/[file_name.py]`

### If tests fail
The `master` build should always be clean and pass. If `master` isn't passing, try the following:

* make sure the virtual environment is activated with `conda activate fastai` or `source activate fastai`
* update the project (see above section)
* consider using the cpu environment if testing on a computer without a GPU (see above section)

If the tests are still failing on `master`, please [file an issue on GitHub](https://github.com/fastai/fastai/issues) explaining the issue and steps to reproduce the problem.

If the tests are failing on your new branch, but they pass on `master`, this means your code changes broke one of the tests. Investigate what might be causing this and play around until you get the test passing. Feel free to ask for help!
