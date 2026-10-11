# Hand Control - IMPORTANT TO READ INSTRUCTIONS 

Control your laptop with hand gestures, using only the webcam.

| Gesture | What it does |
|---|---|
| 👍 Thumbs up | Volume up (keeps going while you hold it) |
| 👎 Thumbs down | Volume down (keeps going while you hold it) |
| 👉 Point right with your index finger | Right arrow |
| 👈 Point left with your index finger | Left arrow |
| 🤏 Pinch thumb and index together | Space bar (one press per pinch) |

The window shows your camera with the hand skeleton drawn on your hand, so you can see what it sees.

## Download for Windows 10 / 11 (READ IMPORTANT NOTE AFTER STEP 3)

1. **[Download HandControl-windows.zip](../../releases/latest/download/HandControl-windows.zip)**
2. Right-click the zip and choose **Extract All**.
3. Open the `HandControl` folder and double-click **HandControl.exe**.

The first time, Windows may show **"Windows protected your PC"**. Click **More info**, then **Run anyway**. This appears because the app is not signed by a company, so Windows does not recognise it yet.

## Download for Mac (READ IMPORTANT STEPS TO RUN IT WITHOUT PROBLEMS)

Needs a Mac with Apple Silicon (M1 or newer) and macOS 13 or newer. Intel Macs are not supported.

1. **[Download HandControl-mac.zip](../../releases/latest/download/HandControl-mac.zip)** and open it.
2. Drag **HandControl** into your Applications folder and double-click it.
3. macOS says it could not verify the app. Click **Done**, open **System Settings > Privacy & Security**, scroll down, click **Open Anyway** next to HandControl, then **Open**. This appears because the app is not registered with Apple.
4. Click **Allow** when macOS asks for the camera.
5. When macOS asks to let HandControl control the computer, click **Open System Settings** and switch on HandControl under **Accessibility**. This is what lets it press the arrow keys and space bar. Then quit HandControl and open it again.

On a Mac you can drag the window's edge or press **-** / **+** to resize it, and you can minimise it while it keeps working; click the Dock icon to bring it back. To quit, press **Q** in the window or right-click its Dock icon and choose **Quit**.

## Using it

- Arrow keys and space go to the window you clicked last. Click your slides, video or photo viewer once after starting Hand Control. Volume works everywhere.
- Hold a gesture for a moment before it fires. Keep your hand upright or level; diagonal gestures are ignored on purpose.
- In the Hand Control window: **P** pauses, **Q** or **Esc** quits.
- If the camera cannot be opened, close other apps that use it (Zoom, Teams, the Camera app).

## Privacy

The camera picture is processed on your computer only. Nothing is recorded, saved or sent anywhere, and the app does not use the internet.

## About

Free to use. © 2026 Mahmoud Wael. Provided as is, without warranty.

Built with [MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) hand tracking and [OpenCV](https://opencv.org/); their licences are included in the download.
