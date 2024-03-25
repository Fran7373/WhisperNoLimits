# WhisperNoLimits

This code uses Whisper to transcribe audio to text (https://github.com/openai/whisper). Whisper has a 25 MB limit. However, this doesn't mean that you can't transcribe a file larger than 25 MB. You simply need to divide the file into smaller segments until each segment is less than 25 MB. With this workaround, you can transcribe audio to text regardless of the audio file size, while maintaining the quality of the Whisper model. And precisely, this is what this code accomplishes.

## Dependencies

ffmpeg and whipser most be installed

