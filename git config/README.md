##

## git config কমান্ডটি Git এর কনফিগারেশন সেটিংস পরিচালনার জন্য ব্যবহৃত হয়। এটি বিভিন্ন সেটিংস কনফিগার করতে সাহায্য করে, যেমন ইউজার নাম, ইমেইল অ্যাড্রেস, ডিফল্ট এডিটর, ইত্যাদি। নিচে কিছু সাধারণ git config কমান্ডের উদাহরণ এবং তাদের ব্যাখ্যা দেওয়া হলো:

### 1.ইউজার নাম সেট করা Commamd:

`git config --global user.name "Your Name"`

#### এই কমান্ডটি আপনার গিট কনফিগারেশন ফাইলে আপনার ইউজার নাম সংরক্ষণ করবে। --global ফ্ল্যাগটি নির্দেশ করে যে এই সেটিংটি গ্লোবাল বা সমস্ত রিপোজিটরির জন্য প্রযোজ্য হবে।

### 2.ইমেইল অ্যাড্রেস সেট করা:

`git config --global user.email "your.email@example.com"`

#### এই কমান্ডটি আপনার ইমেইল অ্যাড্রেস সংরক্ষণ করবে, যা প্রতিটি কমিটের সাথে যুক্ত থাকবে।

### 3.ডিফল্ট এডিটর সেট করা:

`git config --global core.editor "nano"
`

#### এই কমান্ডটি ডিফল্ট টেক্সট এডিটর সেট করবে, যা গিট কমিট মেসেজ লিখতে ব্যবহৃত হবে। এখানে nano এডিটর হিসেবে সেট করা হয়েছে, আপনি চাইলে অন্য এডিটর যেমন vim, code (VS Code), ইত্যাদি ব্যবহার করতে পারেন।

### 4.সিস্টেম বা লোকাল লেভেলে কনফিগার করা:

`git config --system color.ui true
git config --local core.ignorecase false`

#### --system: সিস্টেম লেভেলে কনফিগার করে, যা সমস্ত ইউজার এবং রিপোজিটরির জন্য প্রযোজ্য।

#### --local: নির্দিষ্ট একটি রিপোজিটরির জন্য কনফিগার করে, যেখানে কমান্ডটি চালানো হয়।

### 5.কনফিগারেশন দেখতে:

`git config --list
`

#### এই কমান্ডটি বর্তমানে সেট করা সমস্ত কনফিগারেশন দেখাবে।

### 6.নির্দিষ্ট কনফিগারেশন ভ্যালু দেখতে:

`git config user.name
`

#### এই কমান্ডটি নির্দিষ্ট কনফিগারেশন কী (এখানে user.name) এর ভ্যালু দেখাবে।

---

## সংক্ষেপে:

##### git config: গিট কনফিগারেশনের সেটিংস সেট বা ম্যানেজ করার জন্য।

##### --global: গ্লোবাল বা সমস্ত রিপোজিটরির জন্য।

##### --system: সিস্টেম লেভেলে।

##### --local: নির্দিষ্ট রিপোজিটরির জন্য।

##### --list: সমস্ত কনফিগারেশন দেখার জন্য।

---

#### এই কমান্ডগুলি ব্যবহার করে আপনি আপনার গিট কনফিগারেশন সহজেই ম্যানেজ করতে পারবেন।