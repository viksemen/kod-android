# Third-party dependencies / Сторонние компоненты

**Preliminary inventory / Предварительный перечень. Not release clearance.**

Direct declarations in Android 1.4.2 app/build.gradle.kts (BOM-managed versions are not resolved):

- `androidx.compose:compose-bom:2026.09.00`
- `androidx.compose.ui:ui`
- `androidx.compose.foundation:foundation`
- `androidx.compose.material3:material3`
- `androidx.compose.material:material-icons-core`
- `androidx.activity:activity-compose:1.13.0`
- `androidx.lifecycle:lifecycle-viewmodel-compose:2.11.0`
- `androidx.lifecycle:lifecycle-runtime-compose:2.11.0`
- `androidx.core:core-ktx:1.19.1`
- `org.jetbrains.kotlinx:kotlinx-coroutines-android:1.11.0`
- `com.squareup.okhttp3:okhttp-bom:5.5.1`
- `com.squareup.okhttp3:okhttp`
- `org.matrix.android:olm-sdk:3.2.12`
- `io.github.webrtc-sdk:android:137.7151.05`
- `com.google.zxing:core:3.5.3`
- `com.airbnb.android:lottie-compose:6.6.2`
- `androidx.camera:camera-core:1.6.2`
- `androidx.camera:camera-camera2:1.6.2`
- `androidx.camera:camera-lifecycle:1.6.2`
- `androidx.camera:camera-video:1.6.2`
- `androidx.camera:camera-view:1.6.2`
- `androidx.credentials:credentials:1.6.0`
- `androidx.credentials:credentials-play-services-auth:1.6.0`
- `androidx.fragment:fragment-ktx:1.8.6`
- `org.bouncycastle:bcprov-jdk18on:1.84`
- `org.bouncycastle:bcutil-jdk18on:1.84`
- `org.bouncycastle:bcpg-jdk18on:1.84`

Expected license families: AndroidX, Kotlin coroutines, OkHttp, ZXing, Lottie and Olm — Apache-2.0 (verify exact artifacts); Bouncy Castle — permissive license (verify exact texts); WebRTC — BSD and bundled third-party notices; Google dependencies — verify individual terms and notices.

До выпуска необходимо получить полный releaseRuntimeClasspath, тексты LICENSE/NOTICE всех распространяемых компонентов, включая нативные библиотеки, и проверить права на ресурсы. Этот перечень не заменяет обязательные уведомления.

Before release, resolve all transitive dependencies, collect complete license and notice texts including native libraries, and verify asset rights.

- https://developers.google.com/android/guides/opensource
- https://developer.android.com/studio/terms
