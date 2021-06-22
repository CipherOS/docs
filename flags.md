![banner](.github/banner.png)

### CipherOS Specific Build flags ### 

#### cipher.mk:  ####

- If your device supports Face unlock, use `TARGET_FACE_UNLOCK_SUPPORTED := true`
- If you want to build with Gapps, use `CIPHER_GAPPS := true`
- If you want to Enable AOSP Blur, use `TARGET_USES_BLUR := true`
- 

#### system.prop: ####

- To add maintainer name in settings, add `ro.cipher.maintainer=yournamehere` to your system.prop. 

