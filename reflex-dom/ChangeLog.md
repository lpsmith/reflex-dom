# Revision history for reflex-dom

## Unreleased
* On Android, enable prompting the user for geolocation
  permissions on demand by default. See
  https://developer.android.com/reference/android/webkit/WebChromeClient.html#onGeolocationPermissionsShowPrompt(java.lang.String,%20android.webkit.GeolocationPermissions.Callback)
  for details.

## 0.5.1

* The default jsaddle backend on macOS when built from nix
  is now jsaddle-wkwebview, matching the behaviour of cabal
  builds.

## 0.5

* Re-export new hydration widget "mainWidget" functions.
* The use-warp flag now properly takes precedence on macOS.
