# Shofi's Dairy - Android APK Build Guide

## 🚀 সহজ উপায়: GitHub Actions দিয়ে স্বয়ংক্রিয় APK বিল্ড

### ধাপ ১: GitHub Repository তৈরি করুন

1. **GitHub এ লগইন করুন:** https://github.com/login
2. **নতুন Repository তৈরি করুন:**
   - https://github.com/new এ যান
   - Repository name: `shofis-dairy-app`
   - Description: "Shofi's Dairy - Credit & Ledger Management"
   - "Create repository" ক্লিক করুন

### ধাপ ২: কোড আপলোড করুন

আপনার কম্পিউটারে Terminal খুলুন এবং এই কমান্ড চালান:

```bash
# এই প্রজেক্ট ডাউনলোড করুন
cd ~/shofis_dairy_app

# Git সেটআপ করুন
git init
git add .
git commit -m "Initial commit: Shofi's Dairy Flutter App"

# আপনার GitHub রিপো সংযোগ করুন
git remote add origin https://github.com/YOUR_USERNAME/shofis-dairy-app.git
git branch -M main
git push -u origin main
```

**YOUR_USERNAME** এর জায়গায় আপনার GitHub ইউজারনেম লিখুন।

### ধাপ ৩: GitHub Actions চালু হবে স্বয়ংক্রিয়ভাবে

1. আপনার Repository এ যান
2. **"Actions"** ট্যাবে ক্লিক করুন
3. **"Build Android APK"** workflow দেখবেন
4. সবুজ ✓ চেকমার্ক মানে বিল্ড সফল!

### ধাপ ৪: APK ডাউনলোড করুন

1. **"Build Android APK"** workflow এ ক্লিক করুন
2. সবচেয়ে নতুন run খুলুন
3. **"Artifacts"** সেকশন খুঁজুন
4. **"shofis-dairy-apk"** ডাউনলোড করুন
5. ফাইল খুলুন: `app-release.apk`

---

## 📱 Android ফোনে ইনস্টল করুন

### উপায় ১: সরাসরি ডাউনলোড (সহজ)

1. APK ফাইল ফোনে কপি করুন (USB বা ক্লাউড)
2. ফাইল ম্যানেজার খুলুন
3. APK ফাইলে ট্যাপ করুন
4. "Install" ক্লিক করুন
5. সম্পন্ন! অ্যাপ ইনস্টল হবে

### উপায় ২: GitHub থেকে সরাসরি

1. আপনার Repository এ যান
2. "Releases" সেকশনে যান
3. সর্বশেষ রিলিজ খুলুন
4. APK ফাইল ডাউনলোড করুন
5. ফোনে ইনস্টল করুন

---

## 🔧 সমস্যা সমাধান

### "Build failed" ত্রুটি

**সমাধান:**
1. Repository এ যান
2. "Actions" → সর্বশেষ run খুলুন
3. লাল ✗ এর উপর ক্লিক করুন
4. Error message পড়ুন
5. আমাকে এরর মেসেজ পাঠান

### APK খুব বড় (50-100 MB)

এটি স্বাভাবিক। Flutter APK সাধারণত এই সাইজ।

### GitHub এ কোড কীভাবে আপলোড করব?

**সহজ উপায়:**
1. GitHub Desktop ডাউনলোড করুন: https://desktop.github.com/
2. Repository ক্লোন করুন
3. ফাইল কপি করুন
4. "Commit" করুন
5. "Push" করুন

---

## 📋 প্রয়োজনীয় তথ্য

**অ্যাপ নাম:** Shofi's Dairy  
**ডেভেলপার:** কামরান আহমেদ  
**ফোন:** ০१७४६१४९९१२  
**অ্যাপ আইডি:** com.shofidairy  
**ভার্সন:** 1.0.0

---

## ✨ অ্যাপ ফিচার

- 🔐 PIN-ভিত্তিক নিরাপদ লগইন
- 👥 গ্রাহক ম্যানেজমেন্ট
- 💰 বিক্রয় এবং পেমেন্ট এন্ট্রি
- 📊 ড্যাশবোর্ড এবং রিপোর্ট
- ⚙️ সেটিংস এবং কনফিগারেশন
- 💾 ডেটা ব্যাকআপ

---

## 🎯 পরবর্তী ধাপ

APK তৈরি হওয়ার পর:

1. **ফোনে টেস্ট করুন**
2. **PIN সেটআপ করুন** (যেমন: 1234)
3. **গ্রাহক যোগ করুন**
4. **বিক্রয় রেকর্ড করুন**
5. **রিপোর্ট দেখুন**

---

## 📞 সাহায্য প্রয়োজন?

- GitHub Issues খুলুন
- আমাকে যোগাযোগ করুন
- ত্রুটি স্ক্রিনশট পাঠান

---

**Happy Building! 🚀**

Developer: Kamran Ahmed  
Phone: 01746149912
