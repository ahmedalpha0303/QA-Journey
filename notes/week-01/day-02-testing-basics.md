TC-W01-D2 — Testing-এর মূল ধারণা

১. Error, Defect ও Failure

- Error: মানুষের ভুল কাজ, সিদ্ধান্ত বা বোঝাপড়া।
- Defect: Requirement, Design, Code বা অন্য Work Product-এর ত্রুটি।
- Failure: Software চালানোর সময় প্রত্যাশিত ফল না পাওয়া।

উদাহরণ: Developer ভুল হিসাব করলেন (Error), ভুল Calculation-এর Code লিখলেন (Defect), Website ভুল দাম দেখাল (Failure)।

২. Verification বনাম Validation

- Verification: Software নির্দিষ্ট Requirement ও Specification অনুসারে তৈরি হয়েছে কি না যাচাই করা।
- Validation: Software ব্যবহারকারীর প্রয়োজন ও প্রত্যাশা পূরণ করছে কি না যাচাই করা।

উদাহরণ: Requirement অনুযায়ী Wallet-এ ৬টি Card Slot আছে কি না যাচাই করা Verification-এর উদাহরণ। Wallet ব্যবহারকারীর প্রয়োজন পূরণ করছে কি না যাচাই করা Validation-এর উদাহরণ।

৩. Testing-এর সাতটি Principle

1. Testing shows the presence of defects — Testing Defect খুঁজে পেতে সাহায্য করে, কিন্তু Defect নেই তা প্রমাণ করে না।
2. Exhaustive testing is impossible — সব সম্ভাব্য Test করা বাস্তবে সম্ভব নয়।
3. Early testing saves time and money — শুরুতেই Testing করলে সংশোধনের খরচ কমতে পারে।
4. Defects cluster together — কিছু Module-এ বেশি Defect পাওয়া যেতে পারে।
5. Pesticide paradox — একই Test বারবার করলে নতুন Defect খুঁজে পাওয়ার ক্ষমতা কমতে পারে।
6. Testing is context dependent — Software-এর ধরন ও Risk অনুযায়ী Testing পদ্ধতি বদলায়।
7. Absence-of-errors fallacy — Defect না থাকলেও Software ব্যবহারকারীর প্রয়োজন পূরণ নাও করতে পারে।

৪. Testing বনাম Debugging

- Testing: Software পরীক্ষা করে সমস্যা শনাক্ত করা এবং রিপোর্ট করা।
- Debugging: সমস্যার কারণ অনুসন্ধান করে সংশ্লিষ্ট ত্রুটি সংশোধন করা।

উদাহরণ: QA Checkout-এ ভুল Total শনাক্ত ও রিপোর্ট করল। Developer Code-এর ভুল খুঁজে সংশোধন করলেন।

৫. Retesting বনাম Regression Testing

- Retesting: নির্দিষ্ট Bug-এর Fix কাজ করছে কি না পরীক্ষা করা।
- Regression Testing: পরিবর্তনের কারণে অন্য Function-এ সমস্যা হয়েছে কি না পরীক্ষা করা।