# DetectFrida
This project has 3 ways to detect frida hooking
a. Detect through named pipes used by Frida
b. Detect through frida specific named thread
c. Compare text section tampering with text section in disk

More details can be found @ https://darvincitech.wordpress.com/2019/12/23/detect-frida-for-android/

Also this project has 3 mechanisms to harden the native code
a. Replace certain libc calls with syscalls
b. Replace string,memory related operation with custom implementation
c. Apply O-LLVM native obfuscation

More details can be found @ https://darvincitech.wordpress.com/2020/01/07/security-hardening-of-android-native-code/

Only arm64, armv7a architectures are supported in this project. The hardened APK is provided for interested reverse engineers to analyze.
