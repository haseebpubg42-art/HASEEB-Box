# HASEEB Box - APK kaise banayein (phone se)

1. github.com par account banayein, naya repository banayein.
2. Is zip ki saari files (`.github` folder samet) repository mein upload karein.
   Tip: bohat files hon to browser mein "Desktop site" on karein, phir "Add file > Upload files".
3. **Actions** tab > **Build HASEEB Box APK** > **Run workflow**.
4. 15-30 minute baad run kholein, neeche **Artifacts** se `HASEEB_Box_APK` download karein.
5. Zip ke andar 2 APK hongi: `HASEEB_app-BlackBox64` (64-bit) aur `HASEEB_app-BlackBox32` (32-bit).
   Zyadatar naye phones par 64-bit wali install karein. Agar game list mein na mile to doosri try karein.

## Zaroori baatein
- Ye virtual Android nahi, app-level clone engine hai: game asli CPU/GPU par chalta hai, is liye lag kam hota hai.
- Pehli build mein error aa sakta hai (ye test nahi hui). Error ka text bhej dein.
- Games virtual/clone environment detect kar ke ban kar sakti hain. Main account se na khelein.
- Har build ka signing key naya banta hai, to naya APK install karne se pehle purana uninstall karna parega.
- License: Apache 2.0.
