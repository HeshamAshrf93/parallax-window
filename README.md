# parallax-window

Make a normal screen look like a window into a 3D world. The webcam tracks where your head is, and the 3D view moves with you, so objects seem to pop out of the screen.

> Status: early development.

## Planned features

- [ ] Real-time face / head position tracking from the webcam
- [ ] Off-axis (asymmetric) projection in Three.js based on head position
- [ ] Calibration for screen size and viewing distance
- [ ] Demo scenes: floating objects, a box room, a rotating model
- [ ] Smoothing to remove jitter
- [ ] Works in the browser at 30+ FPS
- [ ] Automated tests for the projection maths

## Planned usage

```bash
npm install
npm run dev
```

## Roadmap

1. Project setup: Vite, Three.js, tests, CI
2. Head tracking
3. Off-axis projection
4. Calibration
5. Demo scenes
6. Smoothing and performance
7. Docs and live demo

## Privacy

Camera frames are processed locally in the browser and are never uploaded.

## License

MIT, see [LICENSE](LICENSE).

---
Built by [Hesham Ashraf](https://www.linkedin.com/in/hesham-ashrf)
