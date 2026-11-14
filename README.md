# 🚀 AirShare PC - Desktop File Transfer App (PC ⇄ Android)

**AirShare PC** ek powerful, fast aur modern Desktop Application hai jo aapke Windows PC aur Android phone ke beech high-speed local Wi-Fi ke through direct file transfer karta hai.

---

## ✨ Key Features (Khaas Baatein)

1. **Phone par No App Required (Zero Install):**
   - Android phone par koi bhi app download ya install karne ki jarurat nahi hai.
   - PC screen par aane wala **QR Code** phone ke camera/browser se scan karein aur transfer shuru!
2. **Bidirectional Transfer (Dono Taraf Transfer):**
   - 📱 **Android ➔ PC:** Photos, 4K videos, heavy files, APKs, documents direct PC ke download folder me save hote hain.
   - 💻 **PC ➔ Android:** Files ko PC app me drag & drop karein, phone me turant 1-tap download option aa jata hai.
3. **Full Wi-Fi LAN Speed:**
   - Transfer direct local Wi-Fi router par hota hai (No Internet / Mobile Data required). Speed 20MB/s se 60+ MB/s tak jati hai (depending on your Wi-Fi).
4. **Live Progress & Stats:**
   - Real-time progress bar, transfer speed (MB/s), aur byte counter dono screens par dikhta hai.
5. **Instant Clipboard Sync (Copy-Paste):**
   - PC par text, links, OTP ya notes type karein, woh turant Android phone par dikhega aur 1-click me copy ho jayega.
   - Phone par copy kiya gaya text turant PC par aa jayega.
6. **Custom Save Folder:**
   - PC par "Change Location" button se aap kisi bhi folder ya drive (D:, E:) me files save kar sakte hain. Default: `Downloads/AirShare`.

---

## 🛠️ App Kaise Start Karein?

### Option 1: Double-Click Launcher (Sabse Aasan)
Folder me maujood **`Launch-AirShare.bat`** file par double-click karein.

### Option 2: Terminal / PowerShell
```bash
npm start
```

---

## 📱 Android Phone Se Connect Kaise Karein?

1. **Step 1:** Ensure karein ki aapka **PC aur Android Phone ek hi Wi-Fi network** (ya mobile hotspot) se connected hain.
2. **Step 2:** Desktop App open karein. Screen ke left side me **QR Code** aur ek URL (jaise `http://10.118.121.130:5050`) dikhega.
3. **Step 3:** 
   - Apne Android Phone ka **Camera** ya **Google Lens** open karke QR code scan karein.
   - *Ya* phone ke Chrome/browser me upar diya gaya URL type karein.
4. **Step 4:** Phone me **AirShare Web App** khul jayega:
   - **Send:** "Select Files / Media" par tap karein aur "Send to PC" dabayein.
   - **Receive:** PC se drag kiye gaye files ko 1-tap me download karein.
   - **Text:** Links ya notes instant share karein.

---

## 📁 Files Kahan Save Hoti Hain?
Default location:
```
C:\Users\<YourUsername>\Downloads\AirShare
```
App me **"Open Folder"** button par click karke aap direct received files tak pahunch sakte hain.

---

## 🏗️ Project Architecture
- **Desktop Frontend:** Modern Dark Fluent UI with HTML5/CSS3/JavaScript.
- **Desktop Runtime:** Electron v45.
- **Backend Server:** Node.js + Express + Multer + Socket.io.
- **Mobile Client:** Responsive, Touch-optimized Web App with drag/pick & real-time socket events.
"# FileShareDesktopApp" 
