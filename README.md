# STATA Final Master Study Guide (3014831)

คัมภีร์สรุปเข้มสถิติและการวิเคราะห์ข้อมูลด้วย **STATA** ฉบับพิชิตข้อสอบ Final (ครอบคลุมเนื้อหาตั้งแต่หลัง Midterm จนถึงปัจจุบัน)

🌐 **เปิดอ่านฉบับ Interactive Web Page ได้ที่:**
👉 [https://nutt2539.github.io/stata-final-study-guide/](https://nutt2539.github.io/stata-final-study-guide/)

---

## 📋 โครงสร้างเนื้อหาในเอกสาร

* **Master Exam Cheat Sheet:**
  * Master Decision Flowchart (Parametric vs. Non-parametric)
  * ตารางเช็ค Assumption ครบทุกสถิติ (ตรวจตัวแปรไหน, คำสั่ง STATA, เกณฑ์ผ่าน `p >= 0.05` vs Main test `p < 0.05`)
  * ตารางพิกัดดูค่า `p-value` และ `95% CI` ใน Stata Result ทุกคำสั่ง
  * กฎเครื่องหมาย `+` / `-` และกฎการเลือกรายงาน **RR vs. OR** ตาม Study Design
* **บทที่ 1:** คำสั่งพื้นฐาน การจัดการข้อมูล และสถิติพรรณนา (`sum`, `sum, detail`, `tabstat`, `gen`, `replace`, Missing Value & `if` Traps, `tab`, `tabi`)
* **บทที่ 2:** การเปรียบเทียบค่าเฉลี่ย 1–2 กลุ่ม (`ttest`, `ttesti`, `ztesti`, `prtesti`, `cii`, `sdtest`, Mann-Whitney U `ranksum`, Wilcoxon Signed-Rank `signrank`)
* **บทที่ 3:** การเปรียบเทียบค่าเฉลี่ย ≥ 3 กลุ่ม (`oneway` ANOVA, FWER, Bartlett's test, Bonferroni vs. Scheffe, `pwmean`, สูตรเติมตาราง ANOVA, Kruskal-Wallis `kwallis` & `kwallis2`)
* **บทที่ 4:** ข้อมูลกลุ่มและการวัดทางระบาดวิทยา (Cochran's Rule, Fisher's Exact Test, Cohort/RCT `cs`/`csi`, Case-Control `cc`/`cci`, Rare Disease Assumption)
* **บทที่ 5:** ความสัมพันธ์และการวิเคราะห์การถดถอย (Pearson vs. Spearman, `corr` vs. `pwcorr`, Pre-Post 3 วิธี & ANCOVA, Simple/Multiple Linear Regression, OLS & Extrapolation, LINE Assumptions & Parallel Slopes, Logistic Regression `logistic` vs. `logit`)

---
*ผลลัพธ์ตัวอย่างทั้งหมดผ่านการรันตรวจสอบด้วย StataNow 19.5 SE บนชุดข้อมูลการเรียนจริง*
