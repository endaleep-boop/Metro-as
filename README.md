# Metro A.Ş. – İstanbul (Android)
Oyun `app/src/main/assets/index.html` içinde; uygulama tam ekran bir WebView kabuğudur.
## APK almanın 2 yolu
1. **GitHub (bilgisayarsız):** Bu klasörü bir GitHub deposuna yükle → Actions → "APK derle" → Run workflow → çıkan `MetroAS-apk` içindeki `app-debug.apk`'yı telefona kur (bilinmeyen kaynaklara izin ver).
2. **Android Studio:** Klasörü aç → Build ▸ Build APK(s). Çıktı: `app/build/outputs/apk/debug/app-debug.apk`.
Oyunu güncellemek için yeni HTML'i `assets/index.html` üzerine kopyalayıp yeniden derle.
