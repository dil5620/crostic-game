CROSTIC - Android APK banane ke tareeqe

TAREEQA A: GitHub se (laptop/Android Studio ke baghair)
1. github.com par naya repository banao.
2. Is zip ke saari files (www, package.json, capacitor.config.json, .github) upload karo.
3. Repository mein Actions tab > "Build APK" > Run workflow.
4. 3-5 minute baad Artifacts mein "crostic-apk" download karo, zip kholo, app-debug.apk phone mein install karo.

TAREEQA B: Computer par
1. Node.js 20 aur Android Studio install karo.
2. Is folder mein: npm install
3. npx cap add android
4. npx cap sync android
5. npx cap open android  -> Android Studio mein Build > Build APK(s)

Game badalna ho to www/index.html edit karo, phir "npx cap sync android" chalao.
Play Store ke liye Build > Generate Signed Bundle use karo.

WHATSAPP MADAD BUTTON
Game mein "Help" button dabane par game screen ka screenshot ban kar phone ka share menu khulta hai.
Wahan WhatsApp chuno, phir apne saare chats/contacts mein se jis ko bhejna ho chun kar send dabao.
(Plugins: @capacitor/share aur @capacitor/filesystem, package.json mein pehle se hain.)
