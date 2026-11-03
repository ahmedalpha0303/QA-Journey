## SDLC মডেল
- Waterfall: ধাপে ধাপে চলে (requirement → design → code → test → release)। পেছনে ফেরা কঠিন। requirement স্থির থাকলে ভালো।
- V-model: প্রতিটা ডেভেলপমেন্ট ধাপের বিপরীতে একটা টেস্ট ধাপ থাকে। কোডিংয়ের আগেই টেস্ট পরিকল্পনা শুরু হয়।
- Agile: ছোট ছোট sprint-এ কাজ, ঘন ঘন feedback। টেস্টিং ডেভেলপমেন্টের সাথে সাথে চলে।

## STLC: ৬ ধাপ ও টেস্টারের output

flowchart LR
  A[Requirement Analysis] --> B[Test Planning] --> C[Test Design] --> D[Environment Setup] --> E[Test Execution] --> F[Test Closure]
| ধাপ | টেস্টার কী করে | Output |
|---|---|---|
| Requirement Analysis | requirement পড়ে অস্পষ্ট জায়গা খোঁজে | প্রশ্নের তালিকা, testable requirement |
| Test Planning | scope, সময়, ঝুঁকি ঠিক করে | Test plan, estimation, entry/exit criteria |
| Test Design | test case লেখে | Test scenario, test case, test data, RTM |
| Environment Setup | টেস্টের পরিবেশ তৈরি করে | চালু environment, smoke test-এর ফল |
| Test Execution | test case চালায় | Pass/fail ফল, bug report |
| Test Closure | কাজের হিসাব মেলায় | Test summary report, metrics |

## আজ যেখানে আটকেছিলাম
-SDLC STLC 