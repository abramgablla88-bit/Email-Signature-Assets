# Email signature assets

This repository hosts the existing `Email-Signature-Assets.gif` used by signature consumers. Keep its filename and bytes stable unless a separately reviewed asset update is intended; no asset bytes changed during the security remediation.

Validated October 20, 2026: GIF, 500 × 500 pixels, 85 frames, 15 seconds, 1,605,235 bytes. SHA-256:

```text
fb86cadb9fbcd9b29099b91910cd0c3cdede230ab2fb65ca66870c103954dc82  Email-Signature-Assets.gif
```

To validate a checkout, use `sha256sum Email-Signature-Assets.gif` and compare the hash above. A full frame decode was performed with Pillow during audit. This does not prove remote hosting or email-client rendering; verify the actual signature URL and representative desktop/mobile clients before changing the asset. Some email clients display only the first frame, so keep that frame meaningful.

There is no application runtime or dependency installation here. Future size optimization should use a separately named draft asset and visual/client review; do not overwrite the working GIF as unrelated cleanup.
