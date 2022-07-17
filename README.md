# language_translator_ml_py
# This is an Language Translator Program made with IBM Watson and Python
The ```.ipynb``` or the ```notebook``` program is working very fine but the ```.py``` program is not working well, seems like some error has crept in.
But you can still run the ```.ipynb``` program in your google collab or jupyter notebook
To run the program follow the steps
- Open the program in Google Collabotary or Jupyter NoteBook
- Add a new codeblock.
- Run the following command.
```
translation = langtranslator.translate(text='Text you Want to Convert', model_id='Language code you want to translate')
```
- The model_id means which language you are translating and which language to translate For Ex - If I want English to Hindi model_id ='en-hi' or English to Japanese model_id ='en-ja'
- The following link will redirect you to the table which you can refer for languages codes.
```
https://cloud.ibm.com/docs/language-translator?topic=language-translator-translation-models
```
- After writing the translation code execute it. 
- If execution of code was successful add another code block, Write the following line of code and execute it.
```
translation.get_result()
```
After executing the above code your given text will be translated to the required/given language.
😊
