# Helper(For Pain-Emotion Assesment of Patients who can't verbalize themselves)
To solve any real-life problem, we need to understand the depth of the problem first. One such problem is the assessment of patients suffering from mental disorders and dementia so that we can diagnose them. Often, these patients are inaccurate or reluctant in expressing themselves due to several mental and social boundaries they surround themselves in. This tends to worsen up the patients in the phycological aspect. These patients are not verbal about their situation, so we need to apply sophisticated techniques for a non-verbal assessment of patient’s pain.

In the healthcare setting, performing an accurate assessment of a patient’s pain level is an imperfect science. Certain traditional pain assessment methods rely significantly on a patient’s description of his or her pain level which may be confusing or inaccurate. While non-verbal pain assessment tools are available inherent bias, reliability and sensitivity are some of the challenges encountered regardless of the tool.

Thus, there is a need to access the pain severity score of a person using non-verbal techniques and train the techniques to self-improvise upon themselves. We also need to study the dependency on environmental factors responsible for the prediction using machine learning, to push their sadness to happiness(improve their well-being).
Related files: https://drive.google.com/drive/folders/1bY4ir-3K_xj5YO9mmGYK7z7FGGO9vLit

## Implementation details
The product being developed is a mobile application for an android operating system. It is an emotion and pain assessment tool and can be incorporated on other platforms also, which satisfy the minimum requirements of the system. The application will allow the doctors to select or capture an image of the patient to be assessed. Then the image will be uploaded to the server and given to the Convolutional Neural Network model to process. The model is trained to generate a score of each possible emotion. Then the severity algorithm will work here are 3 java files Forecasts, DisplayGraphs, DisplayGraphs2 (in android code)..... Please change the localhost "server_name" at the time of testing as the server name changes each time a new server is made.k on generated scores. The result will be sent to the app. Then the doctor/user needs to select symptoms varying from different domains. The total aggregated score calculates a category of pain severeness.

## Assessment domains -
Face domain

Voice domain

Movement domain

Behavior domain

Activity domain

Body domain

## Future Improvements:
Video capturing feature for continuous facial analysis.

Voice capturing for automatic voice assessment.

## To integrate the android app and deep learning analysis outputs
Used Flask to host my laptop as the server. I have a separate file for the Flask as server.py. Where all the necessary stuff of client request and server response have been dealt with. I have used npm package rock for tunneling purposes and hosting.

There is a java files Config (in android code)..... Please change the localhost "server_name" at the time of testing as the server name changes each time a new server is made.
