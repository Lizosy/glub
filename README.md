A fun playground of Python Jupyter notebooks and little helper scripts for messing around with audio analysis, transcription, diarization, QA, and summarization.

## Overview

This is **glub**, my personal sandbox where I try out different audio-processing tricks. Think of it as a grab-bag of notebooks and utilities that let me:

- **Chunk audio files** into bite-sized pieces for faster experiments  
- **Transcribe** speech using OpenAI’s Whisper  
- **Separate speakers** (diarize) with Pyannote  
- Play with **rhyming & semantic analysis** via models like Qwen  
- Run quick **QA pipelines** over transcript text  
- Test out **summarization** tricks with token batching  

Everything’s set up so you can swap in your favorite models or strategies, then hit “Run” and see what happens in a reproducible, notebook-driven workflow.

## Features

- **Audio Chunking**: Slice up long recordings into neat, uniform chunks for whatever comes next  
- **Transcription & Diarization**: Whisper + Pyannote = automatic speech-to-text plus speaker labels  
- **Rhyme & Semantic Play**: Feed lyrics or talks into your LLM of choice and see what rhymes or themes pop out  
- **QA on Transcripts**: Ask questions of your audio’s text so you don’t have to read the whole thing  
- **Summarization**: Experiment with batching tokens to squeeze long transcripts down into bite-size summaries

  
## Credits

- **Models**  
  - **OpenAI Whisper** by OpenAI. GitHub: https://github.com/openai/whisper 
  - **pyannote.audio** by pyannote. GitHub: https://github.com/pyannote/pyannote-audio
  - **Qwen (通义千问)** by Alibaba Cloud. GitHub: https://github.com/QwenLM/Qwen 
  - **longformer-base-4096-finetuned-squadv1** by Suraj Patil (`valhalla`) on Hugging Face: https://huggingface.co/valhalla/longformer-base-4096-finetuned-squadv1 

