# Release checklist

- [ ] Confirm both DLLs were built from the intended revision.
- [ ] Test Standard and Lite separately after a clean game launch.
- [ ] Confirm the folder contains only the intended Lite and Standard release artifacts.
- [ ] Recalculate `SHA256SUMS.txt` after replacing either DLL.
- [ ] Add current screenshots to `images/` and the GitHub release page when available.
- [ ] Attach `Standard/scuffed_kte.dll` and `Lite/scuffed_kte_lite.dll` to the release.
- [ ] Use `RELEASE_BODY.md` as the short GitHub release description.
