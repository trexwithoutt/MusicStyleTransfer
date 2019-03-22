
# Music Style Transfer via VAE

*Author: Yubi Chen, Rex Zhou*

## Dependencies

    - Python 3.6
    - Numpy 1.14
    - Keras 2.0.8
    - ReccurentShop
    - sklearn
    - matplotlib

## Files

    .
    ├── data_folder_settings.py
    ├── credentials.json
    ├── instrument_classifier.ipynb
    ├── velocity_classifier.ipynb
    ├── pitch_classifier.ipynb
    ├── LICENSE.md
    ├── settings.py
    ├── token.pickle
    ├── vae_definition.py
    ├── README.md
    ├── vae_evaluation.ipynb
    └── vae_training.ipynb

## Usage

`vae_training.ipynb` will train the vae model, and `vae_evaluation.ipynb` will give different evaluate method for the transfer work.

## Reference

- Gino Brunner MIDI-VAE: Modeling Dynamics And Instrumentation of Music With Application to Style Transfer. ISMIR 2018, Paris, France
- Ramon Lopez de Mantaras and Josep Lluis Arcos Ai and music from composition to expressive performance. AI Mag., 23(3):4357, September 2002. ISSN 0738-4602.
- Midi association, the official midi specifications. https://www.midi.org/specifications. Accessed: 01-06-2018.
- Leon A Gatys, Alexander S Ecker, and Matthias Bethge. Image style transfer using convolutional neural networks. In Computer Vision and Pattern Recognition (CVPR), 2016 IEEE Conference on, pages 2414–2423. IEEE, 2016
- A¨aron van den Oord, Oriol Vinyals, and Koray Kavukcuoglu. Neural discrete representation learning. In Advances in Neural Information Processing Systems 30: Annual Conference on Neural Information Processing Systems 2017, 4-9 December 2017, Long Beach, CA, USA, pages 6309–6318, 2017


