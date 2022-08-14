# virtualMouse
Implementing a virtual mouse using gesture recognition . 

#### Required Modules :
  - Opencv   
    ```bash
      pip install opencv-python
    ```
  - mediapipe 
    ```bash
      pip install mediapipe
    ```
  - pyautogui
    ```bash
      pip install PyAutoGUI
    ```
 
#### How it works ?

Generally moving a mouse has two states :
  - Moving the Cursor 
  - Clicking
Now we consider that we'll be detecting two objects (green color), and if the both appear this is the first state(moving the cursor) and if they are too near so that they form one single detected object this considered as the second state(clicking mode)
