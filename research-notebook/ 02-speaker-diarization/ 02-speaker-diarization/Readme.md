# Chapter 2 – Speaker Diarization

## What is Speaker Diarization?

Speaker diarization is the process of dividing an audio recording into segments and assigning each segment to a speaker.

It answers the question:

**Who spoke when?**

It does not identify names. Instead, it assigns anonymous labels such as Speaker_0, Speaker_1, etc.

## Why is it important?

Speech-to-text systems tell us what was spoken.

Speaker diarization tells us who spoke each sentence.

For my Hindi AI Dubbing Engine, this information is essential because subtitle files contain timing and text but usually do not indicate which character is speaking.
## History of Speaker Diarization

Speech recognition systems were able to convert speech into text, but they could not identify which speaker produced each sentence.

This limitation became important in applications such as business meetings, court recordings, customer support calls, and movie dubbing.

Researchers introduced speaker diarization to answer the question:

**Who spoke when?**

Modern speaker diarization systems generate a timeline of anonymous speaker labels, making it possible to associate speech segments with individual speakers.
