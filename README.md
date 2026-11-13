# মানবতার পাশে — Free Starter

এটি একটি responsive বাংলা ওয়েবসাইটের প্রাথমিক ডেমো।

## কী আছে
- বাংলা হোমপেজ ও মোবাইল-ফ্রেন্ডলি ডিজাইন
- রোগীর আবেদন অংশের ডেমো ফর্ম
- অনুদান প্রক্রিয়া ও নিরাপত্তা সংক্রান্ত নির্দেশনা
- HTML/CSS/JavaScript — কোনো paid library নেই

## কী এখনো নেই
- বাস্তব রোগী অ্যাকাউন্ট বা লগইন
- অনলাইনে আবেদন সংরক্ষণ
- অ্যাডমিন লগইন/অনুমোদন
- bKash/Nagad/Rocket/card payment
- রোগীর নথির নিরাপদ আপলোড

ডেমো ফর্ম তথ্য সার্ভারে পাঠায় না। বাস্তব রোগীর তথ্য বা অর্থ সংগ্রহে ব্যবহার করবেন না।

## বিনামূল্যে অনলাইনে প্রকাশ
1. GitHub-এ একটি account খুলুন।
2. নতুন public repository তৈরি করুন, যেমন `manobotar-pashe`।
3. ZIP-এর `index.html` ফাইলটি repository-তে upload করুন।
4. Repository Settings → Pages → Deploy from a branch → `main` এবং `/root` নির্বাচন করে Save করুন।
5. GitHub Pages একটি `https://USERNAME.github.io/manobotar-pashe/` ঠিকানা দেবে।

## পরবর্তী নিরাপদ ধাপ
Supabase Free দিয়ে authentication ও database যুক্ত করা যায়। সেটি চালু করার আগে:
- Supabase project তৈরি
- database schema ও row-level security policies
- রোগী/দাতা/অ্যাডমিন role
- admin approval workflow
- private storage bucket এবং signed URL
- audit log ও backup plan

কখনোই Supabase service-role key বা private credentials browser code/GitHub-এ প্রকাশ করবেন না।

## অর্থ সংগ্রহ বিষয়ে সতর্কতা
প্রথমে দায়িত্বশীল পরিচালন কাঠামো, পরিচয় যাচাই, রোগীর সম্মতি, অনুদান ও ব্যয়ের হিসাব এবং প্রযোজ্য আইন/পেমেন্ট-প্রোভাইডারের শর্ত যাচাই করুন। সরাসরি রোগীকে টাকা দেওয়া ও হাসপাতালের বিল পরিশোধ—দুই পদ্ধতির জন্য আলাদা যাচাই ও রসিদ সংরক্ষণ রাখুন।
