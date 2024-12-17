---
title: "LSTM Network-Assisted Belief Propagation Flip Polar Decoder"
collection: 2020 54th Asilomar Conference on Signals, Systems, and Computers
category: conferences
date: 01-04 November 2020
venue: 'Pacific Grove, CA, USA'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9443504/'
---

The belief propagation (BP) decoding has the advantage of providing soft information iteratively, which allows polar codes to be applicable in scenarios requiring high throughput. However, the unsatisfactory error-correction performance makes the BP polar decoding unable to compete with the successive cancellation list (SCL) decoding that is the baseline algorithm in 3GPP. The BP flip (BPF) decoding offers one option to address this issue through additional decoding attempts with a few bits flipped. However, current BPF decoders yield less efficient flipping accuracy. Considering the complex bit correlation and unanalyzable erroneous bit probability of BPF decoding, we propose a long short-term memory (LSTM) network-assisted BPF (LSTM-BPF) decoding algorithm. Given the soft information output by the original BP decoding, the trained LSTM network achieves more accurate erroneous bit prediction ability. The simulation results show that compared with the state-of-the-art BPF decoders, the LSTM-BPF decoder improves the hit rate of the error bits by 10%, thereby obtaining more than 0.1 dB gains at a frame error rate (FER) of $10^{-4}$ for polar codes with length 128 and code rate 0.5. The efficient hardware architecture of the proposed LSTM-BPF decoder is designed. By introducing a critical set to reduce the size of the network, the LSTM accelerator could significantly reduce the required computation and storage resources, thereby reducing the inference time.
