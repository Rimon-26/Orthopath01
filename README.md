# অর্থপাঠ (Orthopath)

## এই ZIP ফাইল দিয়ে কী করবেন

### ধাপ ১: GitHub-এ আপলোড
1. github.com এ লগইন করুন
2. "New repository" → নাম দিন `orthopath` → Create
3. "uploading an existing file" লিংকে ক্লিক করুন
4. এই ZIP ফাইলের ভেতরের **সব ফাইল ও ফোল্ডার** (এক্সট্রাক্ট করার পর) সিলেক্ট করে আপলোড করুন —
   পুরো ফোল্ডার স্ট্রাকচার (public/, src/, package.json) ঠিক রেখে আপলোড করতে হবে
5. "Commit changes"

### ধাপ ২: Netlify-এর সাথে সংযুক্ত করুন
1. netlify.com এ লগইন করুন (GitHub দিয়ে সাইন ইন করা সহজ)
2. "Add new site" → "Import an existing project" → GitHub বাছুন
3. আপনার `orthopath` রিপোজিটরি সিলেক্ট করুন
4. Build settings এমনিতেই ঠিক থাকার কথা:
   - Build command: `npm run build`
   - Publish directory: `build`
5. "Deploy site" চাপুন
6. কয়েক মিনিট পর একটা লিংক পাবেন (যেমন `https://random-name-123.netlify.app`)

### ধাপ ৩: APK বানানো
1. pwabuilder.com এ যান
2. আপনার Netlify লিংক পেস্ট করুন
3. স্ক্যান শেষ হলে "Package for Stores" → Android বাছুন
4. APK ডাউনলোড করুন

---

## অ্যাডমিন/শিক্ষক পাসওয়ার্ড
প্রথমবার "আমি শিক্ষক" বাটনে ক্লিক করলে সাইন আপ করে নিজের পাসওয়ার্ড বানাতে হবে — কোনো ডিফল্ট পাসওয়ার্ড নেই।

## আইকন পরিবর্তন
`public/icons/` ফোল্ডারে থাকা ৪টা ছবি এখন সাধারণ প্লেসহোল্ডার (সবুজ ব্যাকগ্রাউন্ডে সোনালি ৳ চিহ্ন)।
নিজের লোগো বসাতে চাইলে একই নামে (icon-192.png, icon-512.png, icon-maskable-192.png, icon-maskable-512.png)
নতুন ছবি দিয়ে প্রতিস্থাপন করুন।
