[![Build Status](https://travis-ci.com/kaldi-asr/kaldi.svg?branch=master)](https://travis-ci.com/kaldi-asr/kaldi)
Kaldi Speech Recognition Toolkit (modified)
===========================================

This fork of Kaldi Toolkit aims at testing the performance of using synthetic impulse responses (IRs) vs real IRs for far-field speech augmentation, on the LibriSpeech dataset. We modified/simplified the recipe of LibriSpeech for this purpose. The modified recipe is [here](https://github.com/RoyJames/kaldi/blob/master/egs/librispeech/s5/run_rvb.sh).

The test relies on a 3rd-party recorded IR dataset called [BUT ReverbDB](https://speech.fit.vutbr.cz/software/but-speech-fit-reverb-database). We provide the selected and pre-split version of them, along with our synthetic IRs used during test; please download [here (1.5GB)](https://obj.umiacs.umd.edu/gammadata/dataset/eq/IRs_release.zip). More details are described in our manuscript ["Low-frequency Compensated Synthetic Impulse Responses for Improved Far-field Speech Recognition"](https://arxiv.org/abs/1910.10815).

If you have any questions regarding Kaldi itself, please refer to the [original repository](http://kaldi-asr.org/).

## Citation
If you use our codes or data, please consider citing:
```
@article{tang2019lowfrequency,
  title={Low-frequency Compensated Synthetic Impulse Responses for Improved Far-field Speech Recognition},
  author={Tang, Zhenyu and Meng, Hsien-Yu and Manocha, Dinesh},
  journal={arXiv preprint arXiv:1910.10815},
  year={2019}
}
```
We also recommend citing the BUT ReverbDB if you use them as well:
```
@article{szoke2019building,
  title={Building and Evaluation of a Real Room Impulse Response Dataset},
  author={Szoke, Igor and Skacel, Miroslav and Mosner, Ladislav and Paliesek, Jakub and Cernocky, Jan},
  journal={IEEE Journal of Selected Topics in Signal Processing},
  year={2019},
  publisher={IEEE}
}
```
