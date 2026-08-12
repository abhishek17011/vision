- [x] Update `app.py` to guard the `cv2` import and show a clear Streamlit error when OpenCV isn’t installed.
- [x] Provide the exact commands to install `opencv-python` (local) / add to Streamlit Cloud build deps.
- [ ] (Optional) Re-run the app and verify it no longer crashes with `ModuleNotFoundError`.
- [x] Add lane presence/absence detection (Hough + ROI filtering) and show "Lane not found" when missing.
- [ ] Update Streamlit UI to display:
  - [ ] Input image
  - [ ] Lane detection result (overlay + ROI mask/crop)
  - [ ] Text status including "Lane not found" when applicable.


