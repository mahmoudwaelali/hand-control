# Hand Control

Control your laptop with hand gestures, using only the webcam.

> [!IMPORTANT]
> **Setup takes 2 minutes. Follow the numbered steps for your computer, in order, and don't skip any.**
> The first time, Windows or macOS shows a security warning. That's normal: the app is free and not registered with Microsoft or Apple. The steps below show exactly what to click.

| Gesture | What it does |
|---|---|
| 👍 Thumbs up | Volume up (keeps going while you hold it) |
| 👎 Thumbs down | Volume down (keeps going while you hold it) |
| 👉 Point right with your index finger | Right arrow |
| 👈 Point left with your index finger | Left arrow |
| 🤏 Pinch thumb and index together | Space bar (one press per pinch) |

The window shows your camera with the hand skeleton drawn on your hand, so you can see what it sees.

## Windows 10 / 11

1. **[Download HandControl-windows.zip](../../releases/latest/download/HandControl-windows.zip)**
2. Right-click the zip and choose **Extract All**.
3. Open the `HandControl` folder and double-click **HandControl.exe**.
4. ⚠️ If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**.

## Mac

> [!WARNING]
> Needs a Mac with Apple Silicon (M1 or newer) and macOS 13 or newer. Intel Macs are not supported.

1. **[Download HandControl-mac.zip](../../releases/latest/download/HandControl-mac.zip)** and open it.
2. Drag **HandControl** into your **Applications** folder, then double-click it there.
3. ⚠️ macOS says it could not verify the app. Click **Done**, open **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to HandControl, then **Open**.
4. Click **Allow** when macOS asks for the camera.
5. ⚠️ When macOS asks to let HandControl control the computer, click **Open System Settings** and switch on **HandControl** under **Accessibility**. This lets it press the arrow keys and space bar.
6. ⚠️ Quit HandControl (press **Q**) and open it again. The arrow keys and space bar only work after this restart.

You can drag the window's edge or press **-** / **+** to resize it. You can minimise it and it keeps working; click its Dock icon to bring it back. To quit, press **Q** in the window, or right-click the Dock icon and choose **Quit**.

### Updating to a new version on a Mac

> [!WARNING]
> Do these steps every time you update, or the arrow keys and space bar will stop working.

1. Quit HandControl (press **Q**).
2. Delete the old HandControl from **Applications**. Keep only one copy on the Mac.
3. Open **System Settings → Privacy & Security → Accessibility**, select **HandControl**, and click **–**.
4. Drag the new HandControl into **Applications** and open it from there. If macOS blocks it, use **Open Anyway** like the first time.
5. When macOS asks, switch **HandControl** on under **Accessibility**.
6. Quit HandControl and open it again.

If the orange message *"macOS is blocking the arrow and space keys"* still appears, restart the Mac and repeat steps 3–6.

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
