<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Mradul+Sharma+%F0%9F%91%8B;Backend+Developer+%7C+Java+%7C+Node.js;Building+Distributed+Systems; GSoC+2027+Aspirant+%7C+Jenkins+Contributor" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]([https://linkedin.com/in/mradul-sharma](https://www.linkedin.com/in/mradul-sharma-a0ab33372/))
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/Mradul_Sharma_)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mradulfpu@gmail.com)
[![Jenkins Community](https://img.shields.io/badge/Jenkins_Community-D33833?style=for-the-badge&logo=jenkins&logoColor=white)](https://community.jenkins.io)

</div>

---

## 🧠 About Me

- 🎓 **VIT** — B.Tech CSE '29 &nbsp;&nbsp; 
- 🔧 Building production-grade backend systems in **Java** and **Node.js**
- ⚙️ Currently building a **Distributed Idempotency Engine** (Spring Boot + Redis)
- 🌱 Contributing to **Jenkins** — targeting **GSoC 2027**
- 🎯 Goal: Backend Engineer at a product company that ships real things

---

## ⚡ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

**Databases & Cache**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## 🔨 What I'm Building

### 🔐 [Student Management API](https://github.com/sharma-mradul/student-management-api)
`Node.js` `Express.js` `MongoDB` `JWT`

Production-grade REST API with a security layer most tutorials skip:
- **Refresh token rotation** — every token use invalidates the old one
- **Token family tracking** — all tokens in a session share a `familyId`
- **Reuse detection** — a consumed token being replayed triggers family-wide revocation
- **RBAC** — separate admin and student permission scopes
- **HTTP-only cookies** — refresh tokens never exposed to JavaScript (XSS protection)

> Same auth pattern used by Stripe in production.

---

### ⚙️ Distributed Idempotency Engine *(in progress)*
`Spring Boot` `Redis` `Java`

Guarantees exactly-once execution for distributed API calls.
- **SHA-256 request fingerprinting** — method + path + body + idempotency key
- **Redis distributed lock** — concurrent duplicate requests coalesced into one response
- **TTL-managed cache** — 24-hour response storage, no cron jobs needed
- **Prevents duplicate payments, form submissions, and race conditions**

> The same pattern that prevents duplicate charges at Stripe, Razorpay, and every serious payment system.

---

## 📊 DSA Progress

| | |
|---|---|
| **Platform** | LeetCode — [`Mradul_Sharma_`](https://leetcode.com/Mradul_Sharma_) |
| **Solved** | 46 problems — 32 Medium · 6 Hard |
| **Language** | Java — always Java |
| **Patterns** | Arrays · Two Pointers · Sliding Window · Binary Search · Binary Search on Answer · Stack · Greedy · Merge Intervals |

---

## 📈 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=sharma-mradul&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sharma-mradul&layout=compact&theme=tokyonight&hide_border=true" />

<br/>

[![GitHub Streak](https://streak-stats.demolab.com/?user=sharma-mradul&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🌱 Open Source

**Target:** Jenkins (GSoC 2027)
**Status:** Active contributor — starting with plugin contributions, building toward a GSoC proposal

[![Jenkins](https://img.shields.io/badge/Jenkins_Contributor-D33833?style=flat-square&logo=jenkins&logoColor=white)](https://community.jenkins.io)

---

## 📬 Reach Me

I'm open to **startup internship opportunities** where the work is real and the learning curve is steep.

[![Gmail](https://img.shields.io/badge/mradulfpu@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mradulfpu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mradul-sharma)

---

<div align="center">
<img src="https://komarev.com/ghpvc/?username=sharma-mradul&style=flat-square&color=6366F1" alt="Profile views" />
</div>
