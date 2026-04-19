# DDP-DQN for Sepsis Treatment

This repository accompanies the following publication:

> **Evaluating Deep Reinforcement Learning Architectures for Sepsis Treatment: MIMIC-IV Development and ViennaAIdb External Validation**\
> Mohammad Mahdi Azarbeik\*, Lorenz Kapral\*, Richard Weiss, Razvan Bologheanu, Oliver Kimberger†, Clemens Heitzinger†\
> *Submitted to npj Digital Medicine*\
> \* These authors contributed equally as first authors.\
> † These authors contributed equally as last authors.

---

## Overview

This repository will contain the full implementation of the **DDP-DQN** (Dueling Double Prioritized Deep Q-Network) agent and the Weighted K-means tabular Q-learning baseline for optimising sepsis treatment policies in the ICU.

The framework includes:
- Weighted K-means state clustering (tabular MDP)
- Sparse autoencoder for continuous state representation (deep RL MDP)
- DDP-DQN agent based on the Rainbow DQN architecture
- Off-policy evaluation using FQE, DualDICE, and GradientDICE

---

## Code Availability

**The full code will be made publicly available upon acceptance of the manuscript.**

For DICE algorithm implementations, see the companion repository:
[https://github.com/Reinforcement-Learning-TU-Vienna/dice_rl_sepsis](https://github.com/Reinforcement-Learning-TU-Vienna/dice_rl_sepsis)

---

## Data

- **MIMIC-IV v3.1** is publicly available on PhysioNet: [https://physionet.org/content/mimiciv/](https://physionet.org/content/mimiciv/)
- **ViennaAIdb** is available from the corresponding author upon reasonable request.

The data preprocessing pipeline was adapted from the Python implementation of Komorowski et al., available at: [https://github.com/cmudig/AI-Clinician-MIMICIV](https://github.com/cmudig/AI-Clinician-MIMICIV)

---

## Contact

For questions regarding this work, please contact:

**Mohammad Mahdi Azarbeik**
Institute for Information Systems Engineering, TU Vienna
[mohammad.azarbeik@tuwien.ac.at](mailto:mohammad.azarbeik@tuwien.ac.at)

---

## Citation

If you use this work, please cite:

```
Azarbeik, M.M.*, Kapral, L.*, Weiss, R., Bologheanu, R., Kimberger, O., & Heitzinger, C.
Evaluating Deep Reinforcement Learning Architectures for Sepsis Treatment:
MIMIC-IV Development and ViennaAIdb External Validation.
Submitted to npj Digital Medicine.
```

---

## License

To be specified upon acceptance.
