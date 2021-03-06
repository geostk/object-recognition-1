# Object-Recognition
Ultimate detection and recognition of predefined objects in real time.

************************************

An object is **identified** and **recognized** whenever it comes to the frame. The detected object is marked within a rectangle with label specifying what object it is.

Objects recognized:
1. Face
2. Eye
3. Smile
4. Numberplate
5. Wallclock

******
Follow the steps below:
1. Clone or download video.py, common.py and ObjectRecognition.py.
2. Keep video.py and common.py files in the **same** folder as ObjectRecognition.py.
3. Make sure to **download haar folder** which contains all the haar-cascade files required for object recognition.
4. Also make sure that you **give the path correctly for the cascade files in args.get function within ObjectRecognition.py** - Change the path (provided) and make it correspond to the path for the haar-cascade files on your computer. 
5. **Run** ObjectRecognition.py - This opens your webcam and the objects (specified above) are recognized.

******

*Feel free to make modifications.*

