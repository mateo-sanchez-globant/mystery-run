# Mystery Run

🕹️ This simple platform game boasts online capabilities, letting you test your agility against players worldwide. Guide your brave protagonist through levels teeming with obstacles and enemies, aiming to conquer each one without stumbling. Register, log in, and share your highest scores with the global community. Stay tuned for more challenges and surprises in the future!


# Backend

# Python virtualenv

- in mystery-run folder
- '''pyenv install 3.11.4'''
- '''pyenv virtualenv 3.11.4 mystery-run'''
- '''pyenv activate mystery-run'''
- '''pip install fastapi'''
- '''pip install "uvicorn[standard]"'''
- cd be/ && uvicorn main:app --reload
