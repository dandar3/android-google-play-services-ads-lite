## google-play-services-ads-lite

Eclipse library project based on:<br/>
https://maven.google.com/com/google/android/gms/play-services-ads-lite/18.3.0/play-services-ads-lite-18.3.0.aar

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-play-services-ads-lite/18.3.0/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/>
  https://github.com/dandar3/android-google-play-services-ads-lite/tags/18.3.0

**Notes:** <img src="https://raw.githubusercontent.com/google/material-design-icons/master/alert/1x_web/ic_error_outline_black_24dp.png" align="top" />
- _Tag **&lt;provider&gt;** attribute **authorities** has invalid character '$'._<br/>
  Replace `${applicationId}` with your own application package in this `AndroidManifest.xml`<br/>
  See [&lt;provider android:authorities&gt;](https://developer.android.com/guide/topics/manifest/provider-element.html#auth) tag documentation for more details.

**References:**
- https://firebase.google.com/docs/admob/android/lite-sdk
- https://developers.google.com/admob/android/rel-notes
- https://developers.google.com/android/guides/releases

**Requires:**
- `Android 9 (API 28) SDK Platform`
- [dandar3/android-google-play-services-ads-base](https://github.com/dandar3/android-google-play-services-ads-base/tree/18.3.0)
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement/tree/17.0.0)
- [dandar3/android-google-play-services-measurement-sdk-api](https://github.com/dandar3/android-google-play-services-measurement-sdk-api/tree/17.1.0)
