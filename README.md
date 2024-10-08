# Live Speech-to-Text and Summarization Application

This project is a **Live Speech-to-Text** application built with Python that allows users to transcribe speech into text, generate summaries of the transcribed text using the **BART model**, and save the transcription to a file. Additionally, the project includes a feature to calculate the accuracy of the transcription compared to a reference text file.

## Features

1. **Live Speech-to-Text Transcription**: The application captures live speech using a microphone and transcribes it in real-time using the **Google Speech Recognition** API.
   
2. **Summarization**: The transcribed text can be summarized using **BART** (Bidirectional and Auto-Regressive Transformers) from the HuggingFace library.
   
3. **Saving Transcriptions**: You can save the live transcriptions to a specified file for later use.
   
4. **Accuracy Calculation**: The accuracy of the transcribed text can be compared to a reference file, and the similarity percentage is displayed using the **SequenceMatcher** from the `difflib` library.

5. **User-friendly Interface**: A GUI built with **PySimpleGUI** provides a simple interface with buttons for starting/stopping transcription, generating summaries, saving the transcription, and calculating accuracy.

## How It Works

- The app uses **PySimpleGUI** to display the transcriptions in real time.
- **SpeechRecognition** is used to capture and transcribe speech using a microphone.
- The BART model from **transformers** is employed to summarize the transcribed text into a shorter version.
- Transcriptions are saved to a `.txt` file, and you can compare the accuracy of the transcriptions against a reference file.
  
## Demonstration Video

To better understand how the application works, you can watch the demonstration video below:

[![Live Speech-to-Text App Demo](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)

Click the image above to watch the video on YouTube, where we show the application’s main features, including live transcription, summarization, saving transcripts, and accuracy calculation.

## Future Enhancements

Here are some ideas for future improvements:

1. **Multiple Language Support**: Implement transcription for languages other than English by adding language options for both speech recognition and summarization models.
   
2. **Cloud Storage**: Enable saving transcripts to cloud platforms like Google Drive or Dropbox for easier access and sharing.

3. **Voice Command Actions**: Allow the app to respond to voice commands (e.g., “save transcript,” “generate summary”) to make it fully hands-free.

4. **Speaker Identification**: Help distinguish between multiple speakers during a conversation, making the transcription clearer by attributing text to the correct speaker.


## References

- **Google Speech Recognition API**: [SpeechRecognition Documentation](https://pypi.org/project/SpeechRecognition/)
- **HuggingFace BART Model**: [BART Model Documentation](https://huggingface.co/facebook/bart-large-cnn)
- **PySimpleGUI**: [PySimpleGUI Documentation](https://pypi.org/project/PySimpleGUI/)
- **SequenceMatcher**: [Python difflib Library](https://docs.python.org/3/library/difflib.html)
- **Transformers Library**: [HuggingFace Transformers Documentation](https://huggingface.co/transformers/)





