#Class Rep

Class Rep is a web tool to record the audio from the online classes or recorded audio and automatically generate questions/quiz from them. First, from the recorded audio file, we generate the text file with the help of the [Google Speech-To-Text Api](https://cloud.google.com/speech-to-text). Next, we use a robust NLP system built on [HuggingFace Transformers](https://github.com/huggingface/transformers). It contains two models: the Question-Generator itself and another QA evaluator which ranks and filters the questions generated. Follow this [link](https://github.com/AMontgomerie/question_generator) for more insight on this model.



##Timeline

✅Integrate the Google Speech-to-Text Api and generate text.
✅Concatenate the text obtained from all the video divisions.
✅Generate and evaluate the questions from the text.
✅Complete the backend of the project using Django(handleing the workflow).
🔳Build a frontend for the web app using React.
