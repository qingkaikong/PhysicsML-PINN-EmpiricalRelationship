# PhysicsML-PINN-EmpiricalRelationship
This repo contains the code used for the paper - [Evaluating Physics Informed Neural Network Performance for Seismic Discrimination Between Earthquakes and Explosions](https://arxiv.org/abs/2403.04952)


***
## [Content](#Content)

* Discrimination_with_physics_loss.ipynb - notebook contains the training code for adding P/S ratio into the loss function for discrimination purposes.
* ./demo_data/demo_data.npz - numpy zipped arrays, contains 200/50/50 training/validation/testing sample data from earthquake and explosion waveforms as well as the computed P/S ratios. Keys: X_train, ps_train, X_val, ps_val, X_test, ps_test, y
* requirements.txt - Python packages used to run the code.

***
## [License](#license)

This code is provided under the [MIT License](LICENSE.txt).

```text
 Copyright (c) 2024 Qingkai Kong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

***
## [Disclaimer](#disclaimer)
```text
  This work was performed under the auspices of the U.S. Department of Energy
  by Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344.
```

``LLNL-CODE-866087``
