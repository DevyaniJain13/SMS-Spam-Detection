# SMS-Spam-Detection

To run application:

    1. Start the application by running these commands (on terminal):
        > python app.py
            or
        > [absolute path of python.exe] "[absolute path to app.py]"
          e.g. C:/Users/John/AppData/Local/Programs/Python/Python38-32/python.exe "C:/Projects/Spam Classifier/app.py"

    2. Then visit http://127.0.0.1:5000/'

Sample Test Cases:

    > happy birthday buddy (ham)

    > how are you? it has been a while since we met.
      wanna catchup? (ham)

    > best of luck for your exams (ham)

    > Congratulations! You've won a $1000 Walmart gift card. 
      Go to http://bit.ly/123456 to claim now (spam)

    > Your credit card details required in order to unblock your bank account.
      Message your details @ 8327892412 (spam)

    > Want to earn money?
      visit this url : http://bit.ly/easy_money to earn $100 daily (spam)
      

Jupyter Notebook:

    > Spam Classifier.ipynb is included in the folder.

    > if in 2nd cell i.e.
      df = pd.read_csv('archive/spam.csv', encoding="latin-1")
      complaints about something not being right then 
      try to give absolute path to the 'spam.csv' file.
