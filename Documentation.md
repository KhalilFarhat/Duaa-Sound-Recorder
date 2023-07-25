Duaa Recognition Desktop Application
-------------------------------------
The Duaa Recognition Desktop Application is a speech recognition tool designed to recognize and match spoken prayers (duaas) with a database of predefined duaas. This application utilizes the Vosk and Google Speech Recognition libraries to recognize speech input in both English and Arabic languages.

--------------------------------------------------------

Features:
-----------

-Offline and Online Mode: The application supports both offline and online speech recognition, allowing users to use it even without an internet connection. However, initial installation requires an internet connection as it automatically downloads and installs the required packages during setup.

-Intelligent Matching: Using the Waterman-Smith algorithm, the application performs a local alignment between the user's spoken pattern and the duaas in the database, ranking the most similar duaas based on their degrees of similarity.

-Database Integration: The application accesses a local SQLite database containing a collection of duaas in English and Arabic to match the user's input with the closest matches.

-User-Friendly Interface: The desktop application comes with a simple and intuitive interface, making it easy for users to interact with the tool and view the results.

-Installer with Instructions: The application is distributed through an installer that simplifies the setup process. The installer includes step-by-step instructions to guide users through the installation process.

---------------------------------------------
Data Models:
-------------
The application includes two pre-trained data models for speech recognition:

vosk-model-ar-mgb2-0.4: A Vosk model trained for Arabic speech recognition.

vosk-model-small-en-us-0.15: A Vosk model trained for English (US) speech recognition.

Please ensure that these data models are located within the "DataModels" folder for the application to function correctly.

The Duaa Recognition Desktop Application provides an efficient and user-friendly solution for individuals seeking to find and match their spoken duaas with a comprehensive database of duaas. Whether in English or Arabic, this application offers accurate recognition results, making it a valuable tool for daily prayers and spiritual practices.

Note: 
-----
The Duaa Recognition Desktop Application uses the Vosk and Google Speech Recognition libraries for speech recognition and alignment purposes. The application is designed for personal use and does not transmit any data to external servers.
