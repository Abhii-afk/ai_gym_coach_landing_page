# AI Gym Coach Landing Page

A responsive landing page for the real-time AI Gym Coach application. It includes:

- Hero section with live-app call to action
- Animated product gallery with app interface screenshots
- Demo video section
- Feature highlights and contact links
- Scroll-triggered reveal animations with reduced-motion support

## Run locally

Open [`LandingPage/index.html`](./LandingPage/index.html) directly in a browser, or serve the project with any static web server:

```bash
cd LandingPage
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Assets

Gallery images are stored in [`LandingPage/images`](./LandingPage/images). The demo video is loaded from:

```text
LandingPage/videos/demo.mp4
```

To replace the gallery images, keep the filenames referenced in `LandingPage/index.html`:

```text
interface_login.png
interface_dashboard.png
workout_history.png
end_workout.png
working_sample1.png
working_sample2.png
```