# নামাজের সময়সূচী

ফজর, যোহর, আসর, মাগরিব, এশা ও জুমার একটি সম্পাদনযোগ্য (editable) সময়সূচী। সময় পরিবর্তন হলে যেকোনো সময় নিজের মত বসিয়ে নেওয়া যায়, ব্রাউজারে সেভ হয়ে থাকে।

## GitHub Pages দিয়ে চালু করার নিয়ম

1. GitHub-এ একটা নতুন repository বানান (যেমন: `namaz-somoy`)।
2. এই ফোল্ডারের সবগুলো ফাইল (`index.html`, `manifest.json`, `icons/` ফোল্ডার) সেই repository-তে আপলোড করুন।
3. repository-র **Settings → Pages** এ যান।
4. **Branch** থেকে `main` সিলেক্ট করে **Save** চাপুন।
5. কিছুক্ষণ পর একটা লিংক পাবেন, যেমন:
   `https://<আপনার-ইউজারনেম>.github.io/namaz-somoy/`
6. মোবাইলে ওই লিংক খুলে ব্রাউজারের মেনু থেকে **"Add to Home Screen"** করলে অ্যাপের মত আইকন সহ হোম স্ক্রিনে বসে যাবে।

## ফোল্ডার গঠন

```
namaz-somoy/
├── index.html
├── manifest.json
└── icons/
    ├── logo.svg
    ├── icon-512.png
    ├── icon-192.png
    ├── icon-180.png
    └── favicon-32.png
```
