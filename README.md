# Models for FUTO Voice Input

Want to finetune your language for voice input?

## Requirements

The model must be whisper-tiny, whisper-base or whisper-small finetuned on your language. We do not support large, large-v2 or large-v3 as it is too big to run on most phones.

For the model to work correctly in the apps, it should be finetuned with the [ACFT method](https://github.com/futo-org/whisper-acft). This allows the model to run with greater efficiency. If you use a model in the app not finetuned with this, it will work with long dictations (30s) but shorter dictations (under 15s) will exhibit infinite repetition or a long delay at the end. If you already finetuned a model on your language but need help with this process, please make a new issue and we can help.

## Method

This document is still a WIP, more details will follow eventually. If you're interested in this or have done this before feel free to make an issue