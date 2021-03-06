# This repo is a fork of https://github.com/Hironsan/anago

**Updated with support for tf 2.0 and newer keras versions.**

This repo is a fork of https://github.com/Hironsan/anago and is modified to suit my needs. The module's name is changed so that it doesn't conflict with the installation of the original repo and so that I can push my changes to PyPi.

**Unless you know why are you using this, don't use this module. Use the excellent https://github.com/Hironsan/anago**

The purpose of creating a fork (and a separate module) instead of using the excellent anago is as follows.

1.  **Maintain compatibility with newer tf and keras versions.**
2. Anago's installation comes with ELMo, allennlp and some other stuff, which are not needed for the intended use cases of this repo (mainly DeepSegment).
3. It's not easy to include a git repo link as a requirement in setup.py while publishing to PyPi. So, this module is renamed to seqtag-keras.

**Full credit and thanks for the original implementation of this repo goes to https://github.com/Hironsan/ and https://github.com/chakki-works/ . **
