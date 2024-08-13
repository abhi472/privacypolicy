## Unswipe: Privacy policy

Welcome to the Unswipe app for Android!

This is an open source Android app developed by Dreamers and Doers. The source code is available on GitHub under the GNU AGPL license (3.0 or later).

As a FOSS, We take privacy very seriously.
We know how frustrating it is when apps collect your data without your knowledge.

### Data collected by the app

We hereby state, to the best of my knowledge and belief, that We have not programmed this app to collect any personally identifiable information. 

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:

https://github.com/WrichikBasu/ShakeAlarmClock/blob/d7f323c7769ad600d4f97eb499f3d7fa34a2a1fc/app/src/main/AndroidManifest.xml#L21-L38
<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.READ_CONTACTS` |We Use this permission to read list of contacts from device to preemptly block any known user that may be on the app, we do not store these contacts in any way whatsoever. |
