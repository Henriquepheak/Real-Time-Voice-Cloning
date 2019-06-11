### Code style
- [ ] Object-oriented inference rather than the current static style
- [ ] Setup a config file to allow for default argparse values (mainly datasets_root).
- [ ] Change the structure of the hparams file for each model. I think a namespace is the better solution.
- [ ] Properly document all inference functions

### Implementation
- [ ] Let the user decide if they want to use speaker embeddings or utterance embeddings for training the synthesizer.
- [ ] Move on to a pytorch implementation of the synthesizer?
- Various post-generation cleaning routines:
    - [ ] Detect and shorten silences generated by the spectrogram that are too long
    - [ ] Function in the vocoder to insert breaks between the waveform of consecutive mel spectrograms

### Toolbox
- [ ] Display vocoder generation
- [ ] Handle multiple users in the toolbox
- [ ] Allow for saving generated wavs in the toolbox
