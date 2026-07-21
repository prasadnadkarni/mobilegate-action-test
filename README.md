# mobilegate-action-test

Throwaway repo used to test `prasadnadkarni/mobilegate`'s GitHub Action
(`action.yml`) end to end: pinned-release binary fetch, checksum
verification, exit-code propagation on a BLOCKED result, and the
sticky PR comment.

The Android-build-artifact path (a real Gradle-built APK rather than a
fetched one) is a separate test, not yet run here — see
`.github/workflows/mobilegate.yml`'s header comment.
