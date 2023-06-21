# Automatic Reader Based on Raspberry Pi


The Raspberry Pi processor board served as the foundation for this project. It acts as an interface
between the system and the user, controlling peripherals like the camera and speaker. This project
uses optical character recognition (OCR) to identify characters. The system then uses a speaker to
read the characters to the user. The camera is mounted on a substitute such a place that on the off
chance that a piece of paper is in the middle of between the areas set apart by precise supports,
it catches a full perspective on the paper into the framework. Additionally, the paper’s lighting is
checked before the picture is taken by the camera. The system takes the photo, processes it, and, if
it finds the document’s content, reads it out loud through the speaker if all these conditions are met.
The primary application of the TTS (Text to Speech) technology is the conversion of text files into
audio or voice. After the TTS unit is installed on the Raspberry Pi, its output is sent to the speaker,
where it is amplified with an audio amplifier.
