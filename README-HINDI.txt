JARVIS HINDI — ANDROID PROJECT

Yeh native Android app ka source project hai, ready-made APK nahi.

APK banane ka beginner-friendly tareeka (phone se):
1. GitHub account banao/login karo.
2. Naya repository banao, naam JarvisHindi rakho.
3. ZIP ko extract karke andar ki files/folders repository mein upload karo. Root par settings.gradle.kts, build.gradle.kts, app/ aur .github/ hone chahiye.
4. GitHub mein Actions tab kholo. Agar workflow permission maange to enable karo.
5. 'Build JARVIS APK' workflow select karke Run workflow dabao (ya files main branch mein upload karne ke baad workflow automatic run hoga).
6. Build successful hone par workflow run kholo > Artifacts > JARVIS-Hindi-debug-APK download karo.
7. ZIP extract karke app-debug.apk phone mein kholo. Android warning aaye to sirf apne build ki APK install karne ke liye browser/file manager ko temporary permission do. Install ke baad permission band kar sakte ho.

Features:
- Hindi speech recognition Android speech service par nirbhar
- Hindi Text-to-Speech phone mein Hindi voice installed hone par
- Time/date, Google/YouTube, simple Google search
- Mic permission app ke andar maangega

Limitations:
- Wake word 'Jarvis' always listening nahi karta.
- Full phone control, WhatsApp auto-message, calls, lock-screen assistant, AI brain/API abhi shamil nahi.
- Yeh debug APK hogi, Play Store release signing nahi.
- Internet connection, GitHub account aur GitHub Actions availability chahiye.
