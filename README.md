Developed by Prerak Naik, 2025.

This camera app, called MatrixCam developed by me, Prerak Naik, as a personal project. It is still under development.

The application uses the python language.

If you would like to download and run the application, download the .ZIP, and extract all to a folder of your choice. After that, you can run the python file, but before running the file, please read the paragraph below.

Please note that the application does not come with the libraries, since the exe was too large to put on github. If they are not already installed, you will get an error trying to run the file. If they are not installed, they need to be installed in your python folder (ex. Python312, Python311) using pip. If you want to do this, go to the command prompt on your system, use "cd" to navigate to your python folder. Your path in the command prompt should look like this (Replace 'Python31x' with your version of Python installed: C://...Python31x/Scripts>. Once the path looks like that, enter the following line: "pip install pyautogui customtkinter tkinter pillow". The modules should begin installing in your system. Once that is, you should be able to use the application correctly. You can uninstall those modules by using the same command, but replace 'install' with 'uninstall.' I have the project this way to avoid using a single EXE as the final project, which will only work on Windows, preventing other users. This project was finished in 2024, and since then, my knowledge of programming has changed. If I had the knowledge at the time, I would have made this into a website. But it is good for now, with no further changes necessary, since customtkinter cannot be made into a flask based website.

This application allows you to see yourself in the Matrix. Instead of pixels, you become characters (letters, not virtual characters). It is surreal. When you blur your eyes, you can see the actual images. What is crazy is that somehow, the program can also emulate brightness, with the different characters. The overall logic is that there is a set list of characters to construct the image from, then the frames of the video or camera feed are resized to 80px by 45px to reduce lag, and then each pixel's intensity (the image is first converted to grayscale) is matched with those characters' intensity, giving us the images.

This application uses opencv, pyqt5, and other modules. You can use other video feed instead of the camera feed. 

You are allowed to use this project for the sole purpose of what it is intended for. You may not reverse engineer, copy, plagiarize, or relabel the project as your own.

If you think this is great, please look at my other projects on my Github page.
