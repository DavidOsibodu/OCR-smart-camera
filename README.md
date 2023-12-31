# OCR-smart-camera

This script provides a user-friendly interface for performing optical character recognition (OCR) on images. Users can select an image file either from their computer or capture it through a webcam. The selected image is then preprocessed, and the text present in the image is extracted using the Tesseract OCR engine.

Once the text is extracted, users can choose a target language from a dropdown menu. The extracted text is then translated into the selected language using the Google Translate API. The translated text is displayed in the GUI, allowing users to read and review the translation.

Additionally, users have the option to play the translated text as audio. The script converts the translated text into speech using the gTTS library and saves it as an audio file. The audio file is then played using the system's default media player, allowing users to listen to the translated text.

Overall, this script combines OCR, translation, and text-to-speech functionalities in a single application, making it convenient for users to extract, translate, and listen to the text present in images.++
