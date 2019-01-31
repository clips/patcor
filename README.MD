# PATCOR
## A command and control corpus for the card game Patience in Dutch

This is the download page for the PATCOR corpus, as referenced in the paper [Van de Loo et al. (2019)
Effective weakly supervised semantic frame induction using expression sharing in hierarchical hidden Markov models](https://arxiv.org/abs/1901.10680).

Due to the size of the corpus (8.7G unpacked), we offer it as a direct download from:
[https://www.clips.uantwerpen.be/patcor.zip](https://www.clips.uantwerpen.be/patcor.zip)

The unzipped file contains 10 directories, one for each participant in the experiment, labeled pp1 to pp10. Each pp-folder has the same structure, as illustrated for pp1:
* `pp1_transcriptions.txt` all orthographic transcriptions for pp1
* `110802144557_transcription.txt` orthographic transcriptions for session 110802144557
* `110802144557_phon_transcr.txt` all phonetic transcriptions for session 110802144557
* `110802144557.pjt` a subdirectory for session `110802144557`
    * `1.wav` complete audio recording channel 1
    * `2.wav` complete audio recording channel 2
    * `move_1_110802143844_audio.wav` audio recording for move_1
    * `move_1_110802143844_framedescription.xml` frame description for move_1
    * `move_1_110802143844_transcription.txt ` orthographic transcription for move_1
    * `move_39_110802145753_phon_transcr.txt` phonetic transcription for move_1
