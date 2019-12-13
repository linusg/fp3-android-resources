# Fairphone 3 Android Resources

## Fairphone 3 GPL-licensed source code

- Original release: https://code.fairphone.com/projects/fairphone-3-gpl.html
- Copy on GitHub: [`FairphoneMirrors/android_kernel_fairphone_sdm632`](https://github.com/FairphoneMirrors/android_kernel_fairphone_sdm632)

## OTA update ZIP files

The OTA update ZIP files are hosted on `https://android.googleapis.com/packages/ota-api/fairphone_fp3_fp3`. Unlike on the FP2 there's no Fairphone-specific updater app, instead system updates are performed by the *Google Play services* app (invoked via *Settings -> System -> Advanced -> System update*). The service which provides the updates is ["Android Over The Air"](https://developers.google.com/android/over-the-air).

The updates are all delta-updates (a.k.a not full images, brotli-compressed bsdiff mostly it seems). Thanks to [**@z3ntu**](https://github.com/z3ntu) for this information.

The release dates below aren't official but rather the date on which the update is first received and mentioned by a FP3 user.

- **A.0096**, released 2019-10-22:
  - [`39ce8b1b568149d8ecb8b4b7fc0d37beefc388fb.zip`](https://android.googleapis.com/packages/ota-api/fairphone_fp3_fp3/39ce8b1b568149d8ecb8b4b7fc0d37beefc388fb.zip) ([forum post](https://forum.fairphone.com/t/september-security-update-released-and-more/53982/19))

    Patch level: [2019-09-05](https://source.android.com/security/bulletin/2019-09-01)

    Upgrade from: **A.0081**

    Full contents of `META-INF/com/android/metadata`:
    ```
    ota-property-files=payload_metadata.bin:9232:532017,payload.bin:9232:214342271,payload_properties.txt:214351561:155,care_map.txt:843:246,compatibility.zip:1142:8043,metadata:69:726                
    ota-required-cache=0
    ota-streaming-property-files=payload.bin:9232:214342271,payload_properties.txt:214351561:155,care_map.txt:843:246,compatibility.zip:1142:8043,metadata:69:726                  
    ota-type=AB
    post-build=Fairphone/FP3/FP3:9/8901.2.A.0096.20191001/10011803:user/release-keys
    post-build-incremental=10011803
    post-sdk-level=28
    post-security-patch-level=2019-09-05
    post-timestamp=1569925845
    pre-build=Fairphone/FP3/FP3:9/8901.2.A.0081.20190816/08161740:user/release-keys
    pre-build-incremental=08161740
    pre-device=FP3
    ```
  - [`d1e85d55938fdd545fcdc4b4b11098c5d183636f.zip`](https://android.googleapis.com/packages/ota-api/fairphone_fp3_fp3/d1e85d55938fdd545fcdc4b4b11098c5d183636f.zip) ([forum post](https://forum.fairphone.com/t/september-security-update-released-and-more/53982/20))
  
    Patch level: [2019-09-05](https://source.android.com/security/bulletin/2019-09-01)

    Upgrade from: **A.0095**

    Full contents of `META-INF/com/android/metadata`:
    ```
    ota-property-files=payload_metadata.bin:9224:453249,payload.bin:9224:74107701,payload_properties.txt:74116983:154,care_map.txt:835:246,compatibility.zip:1134:8043,metadata:69:718              
    ota-required-cache=0
    ota-streaming-property-files=payload.bin:9224:74107701,payload_properties.txt:74116983:154,care_map.txt:835:246,compatibility.zip:1134:8043,metadata:69:718                
    ota-type=AB
    post-build=Fairphone/FP3/FP3:9/8901.2.A.0096.20191001/10011803:user/release-keys
    post-build-incremental=10011803
    post-sdk-level=28
    post-security-patch-level=2019-09-05
    post-timestamp=1569925845
    pre-build=Fairphone/FP3/FP3:9/8901.2.A.0095.20190926/09261600:user/release-keys
    pre-build-incremental=09261600
    pre-device=FP3
    ```
- **A.0101**, released 2019-11-28:
  - [`a1b56846df6bb6c656a511eeae9f732f5b35fbf9.zip`](https://android.googleapis.com/packages/ota-api/fairphone_fp3_fp3/a1b56846df6bb6c656a511eeae9f732f5b35fbf9.zip) ([forum post](https://forum.fairphone.com/t/has-anybody-received-the-october-security-update-yet/55045/10))
  
    Patch level: [2019-10-05](https://source.android.com/security/bulletin/2019-10-01)

    Upgrade from: **A.0096**

    Full contents of `META-INF/com/android/metadata`:
    ```
    ota-property-files=payload_metadata.bin:9232:567973,payload.bin:9232:352792529,payload_properties.txt:352801819:155,care_map.txt:843:246,compatibility.zip:1142:8043,metadata:69:726                
    ota-required-cache=0
    ota-streaming-property-files=payload.bin:9232:352792529,payload_properties.txt:352801819:155,care_map.txt:843:246,compatibility.zip:1142:8043,metadata:69:726                  
    ota-type=AB
    post-build=Fairphone/FP3/FP3:9/8901.2.A.0101.20191115/11150009:user/release-keys
    post-build-incremental=11150009
    post-sdk-level=28
    post-security-patch-level=2019-10-05
    post-timestamp=1573748558
    pre-build=Fairphone/FP3/FP3:9/8901.2.A.0096.20191001/10011803:user/release-keys
    pre-build-incremental=10011803
    pre-device=FP3
    ```

## LineageOS

- FP2 port: [`LineageOS/android_device_fairphone_FP2`](https://github.com/LineageOS/android_device_fairphone_FP2)
- FP2 build instructions: https://wiki.lineageos.org/devices/FP2/build

## See also

- [`k65onyx/fp3-notes`](https://github.com/k65onyx/fp3-notes)
- [`Development` section in the community forum](https://forum.fairphone.com/c/participate/dev)
- https://en.wikipedia.org/wiki/Fairphone_3
