# Prebuilt Widevine DRM L3, pulled from ChromeOS's Hatch Recovery Image

Android image fingerprint : google/hatch/hatch_cheets:11/R107-15117.112.0/9196637:user/release-keys

## How to integrate into the Android build

#### Clone this Repo To: <br> 
<code> vendor/google/proprietary/widevine-prebuilt </code><br>

#### Add this to your device.mk : <br>
<code>$ (call inherit-product-if-exists, vendor/google/proprietary/widevine-prebuilt/widevine.mk) </code><br>


#### Optional : If you want sepolicy, add this in your BoardConfig.mk <br>
<code> BOARD_SEPOLICY_DIRS += vvendor/google/proprietary/widevine-prebuilt/sepolicy </code><br>
