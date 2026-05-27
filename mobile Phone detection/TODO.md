# TODO

- [ ] Review `phone_detection.py/code` logic around `frame_count`, `phone_detected`, and `confidence_score`.
- [x] Update detection logic so `Suspicious Activity Detected` triggers after **consecutive** confident detections.
- [x] Reset `confidence_score` and consecutive counter when phone is not confidently detected.

- [ ] Keep bounding box + overlay text behavior consistent.
- [ ] Run the script to verify webcam display, rectangle drawing, and JSON correctness.

