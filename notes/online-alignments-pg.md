## [Learning Online Alignments with Continuous Rewards Policy Gradient](https://arxiv.org/abs/1608.01281)

TLDR; The authors a sequence to sequence model with hard attention using binary stochastic decision to indicate whether to output at this timestep. Compared to usual attetion models, this model need no whole sequence input, thus is suitable for instantaneous cases. The  model was validated on TIMIT and WSJ dataset, showing comparable result with baseline models.

#### Notes

- baselines and entropy regularization is need to train the model
- grid lstm preforms better than stacked
- PER: TIMIT 20.5, WSJ 27.0
