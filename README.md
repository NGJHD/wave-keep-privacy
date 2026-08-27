# wave-keep-privacy

The published privacy policy for **Wave Keep** (`com.wavekeep.game`), served by GitHub Pages at:

<https://ngjhd.github.io/wave-keep-privacy/>

That URL is filed with Google Play. **It must stay live for as long as the app is listed** —
renaming this repository, making it private, or disabling Pages will break the link in the store
listing, which is a policy violation rather than a broken page.

`index.html` is the whole site. No build step, no dependencies.

## If the app changes

The policy claims the app collects nothing. That is true of version 1.0.0 and is worth re-checking
before any release that adds a dependency: no network calls, no analytics, no ads, no accounts, and
three `localStorage` keys that never leave the device.

Wave Keep is declared to Google Play as directed to children, so it falls under the Families
policy. Adding an advertising or analytics SDK would break both that declaration and this document.
Update the policy *before* shipping such a version, not after.
