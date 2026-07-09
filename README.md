# ClosePlane UI gallery

Generated screenshots published from the private `ClosePlane` repository.

Notification bodies are rendered headlessly on the JVM (Robolectric + Roborazzi)
from the real `Notification` object. Live chips are captured on an API 36.1
`google_apis` emulator, because the chip is drawn by SystemUI and cannot be
rendered off-device.

Do not edit by hand. Regenerate with `scripts/update-ui-gallery.sh` and
republish with `scripts/publish-gallery.sh` in the source repo.

Source commit: `c22a231`
