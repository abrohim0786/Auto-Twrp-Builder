# Auto TWRP Builder

<p align="center">
  🚀 Build a TWRP recovery for your device in just one click by uploading your recovery image!  
</p>

---

## ✨ Features
- Fully automated TWRP building on GitHub Actions  
- Simple process — no need for a local build environment  
- Get your compiled recovery directly from **Releases**  

---

## 📖 Usage

### 1️⃣ Fork this repository
Click the **Fork** button at the top-right to create your own copy.

---

### 2️⃣ Prepare your recovery image
- Use tools like **bootimg** (or any unpacking tool) to extract your current recovery.  
- Inside `default.prop` or `prop.default`, add the following line:  

  ```ini
  ro.product.first_api_level=(your Android SDK version)