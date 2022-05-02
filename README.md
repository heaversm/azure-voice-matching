# Speaker Verification Prototype Using Azure Speech API

These samples demonstrate how to verify a speaker with audio sample files using the Speech SDK for JavaScript on a web browser

**Note:** Microsoft limits access to speaker recognition. You can apply for access through the [Azure Cognitive Services speaker recognition limited access review](https://aka.ms/azure-speaker-recognition). For more information, see [Limited access for speaker recognition](https://docs.microsoft.com/en-us/legal/cognitive-services/speech-service/speaker-recognition/limited-access-speaker-recognition).

## Prerequisites

* A subscription key for the Speech service. See [Try the speech service for free](https://docs.microsoft.com/azure/cognitive-services/speech-service/get-started).


## Run the `dependent-verification.html` sample

* Open the `index.html` file or `dependent-verification.html` file in your web browser. The `index.html` file allows you to record your voice in the browser, while the `dependent-verification.html` file relies on you having a pre-recorded verification file.
* Use the input fields to set your `subscription key` and `service region`.
* Upload your enrollment files (samples), and your verification file (voice to compare to samples for a match). If you are using `index.html` - you will first need to record and download this file, then use that download as the verification file (to avoid a security issue with javascript audio recording) 
* Press the `Create Profile` button to create a voice profile and enroll using the chosen enrollment files.
* Press the `Verify Speaker` button to identify a speaker using the chosen verification file.


## References

* [Quickstart article on the SDK documentation site](https://docs.microsoft.com/azure/cognitive-services/speech-service/quickstarts/speech-to-text-from-file?pivots=programming-language-javascript)
* [Speech SDK API reference for JavaScript](https://aka.ms/csspeech/javascriptref)
