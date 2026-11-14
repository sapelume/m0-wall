# M0 Wall · Sapelume

Sapelume-এর M0 শেষ করা (বা শেষের পথে থাকা) প্রতিটা student-এর নাম আর live portfolio এক দেয়ালে। 🎉
এটা তোমার প্রথম open source অবদানের অনুশীলন: **fork → clone → branch → commit → push → Pull Request**।

## নিয়ম (PR খোলার আগে পড়ো)
1. **শুধু নিজের file যোগ করো:** `students/<তোমার-নাম>.md` (ছোট হাতের অক্ষর, শব্দের মাঝে `-`, যেমন `students/rina-akter.md`)।
2. **অন্য কারো file বা এই README বদলাবে না।** নিজের আলাদা file হলে কারো সাথে merge conflict হয় না।
3. **Branch-এর নাম:** `add-<তোমার-নাম>` (যেমন `add-rina`)।
4. **Commit message:** `Add <তোমার নাম> to the wall` (যেমন `Add Rina Akter to the wall`)।
5. **এক PR-এ এক কাজ:** শুধু তোমার একটা file।
6. **File-এর ভেতরে** নিচের ছাঁচ মেনে লেখো (`students/_example.md` দেখো):

```markdown
# Rina Akter
Backend শিখছি। M0 শেষ করার পথে।

- Portfolio: https://my-portfolio-rina.vercel.app
- GitHub: https://github.com/rina-akter
```

7. কোনো গোপন তথ্য (password, token, phone নম্বর) লিখবে না। শুধু নাম, এক লাইনের পরিচয় আর দুটো link।

## ধাপগুলো
1. ডান উপরে **Fork** → **Create fork**।
2. নিজের fork clone করো: `git clone git@github.com:<তোমার-username>/m0-wall.git`, তারপর `cd m0-wall`।
3. `git switch -c add-<তোমার-নাম>`, তারপর `students/<তোমার-নাম>.md` বানিয়ে লেখো।
4. `git add`, `git commit -m "Add <তোমার নাম> to the wall"`, `git push -u origin add-<তোমার-নাম>`।
5. নিজের fork-এর পাতায় **Compare & pull request** → **base repository: `sapelume/m0-wall`**, base `main` → **Create pull request**।

Mentor দেখে merge করবেন। Merge হলে নিজের fork-এ **Sync fork** → **Update branch**, তারপর `git switch main` আর `git pull`।

বিস্তারিত: Lesson 5, Topic 9 (Fork আর অন্যের project-এ অবদান)।
