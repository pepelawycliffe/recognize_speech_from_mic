# recognize_speech_from_mic
Transcribe speech from recorded from `microphone`.     Returns a dictionary with three keys:     "success": a boolean indicating whether or not the API request was                successful     "error":   `None` if no error occured, otherwise a string containing                an error message if the API could not be reached or                speech was unrecognizable     "transcription": `None` if speech could not be transcribed,                otherwise a string containing the transcribed text
