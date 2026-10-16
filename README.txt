PITCHPERFECT AI — FREE STARTER PROJECT

WHAT IT DOES
- Mobile-friendly single-page website.
- Lets you select a local video file.
- Uses MediaPipe Pose (free library loaded from jsDelivr CDN) to draw a basic body skeleton.
- Shows approximate 2D left/right elbow and knee angles and cautious practice notes.
- Does not intentionally upload your selected video.

REQUIREMENTS
- Android phone with a modern browser (Chrome recommended).
- Internet connection to download the MediaPipe library/model.
- Short video clip recommended; keep the phone cool and stop if it becomes hot.

HOW TO TRY IT ON ANDROID
1. Extract this ZIP in your phone's Downloads folder using your phone's built-in file manager.
2. Open index.html in a browser if your browser allows local HTML and scripts. Some Android browsers block scripts in file:// pages.
3. If it does not work from a local file, use a free static hosting option such as GitHub Pages. Creating a GitHub account/repository may have age/guardian requirements. Do not enter payment details or publish personal videos.
4. Upload a short batting video, tap "Load video", then "Start pose analysis".
5. Keep internet on while the pose library loads.

IMPORTANT
- This is a starter prototype, not professional cricket coaching.
- It does NOT yet track the bat or ball, identify shot types reliably, measure bat-ball contact, or provide validated accuracy scores.
- Angles are rough 2D image measurements and can be wrong due to camera perspective, occlusion, or missed landmarks.
- Free code does not guarantee unlimited cloud hosting; this prototype runs pose estimation in the browser after loading the library.
- If the library fails to load, try Chrome and internet, or serve the folder over HTTPS using a free static host.
