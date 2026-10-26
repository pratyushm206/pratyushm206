<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:0f766e&height=190&section=header&text=Pratyush%20Mishra&fontColor=e6edf3&fontSize=52&fontAlign=50&fontAlignY=38&desc=Backend%20%2B%20AI%20Engineer&descColor=2dd4bf&descSize=20&descAlignY=60" width="100%" alt="Pratyush Mishra — Backend and AI Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1000&color=2DD4BF&background=0D111700&center=true&vCenter=true&width=640&height=40&lines=%24+building+production-style+REST+APIs;%24+integrating+AI+into+useful+workflows;%24+designing+reliable+backend+systems;%24+open+to+SDE%2C+Backend+%26+AI%2FML+roles" alt="Typing statements: building REST APIs, integrating AI, designing backend systems, and open to engineering roles" />

<br/>

<a href="https://portfolio-tau-weld-1pgtqf121q.vercel.app/"><img src="https://img.shields.io/badge/portfolio-visit-2dd4bf?style=for-the-badge&logo=vercel&logoColor=2dd4bf&labelColor=0d1117" alt="Visit portfolio" /></a>
<a href="https://www.linkedin.com/in/pratyushm206"><img src="https://img.shields.io/badge/linkedin-connect-2dd4bf?style=for-the-badge&logo=linkedin&logoColor=2dd4bf&labelColor=0d1117" alt="Connect on LinkedIn" /></a>
<a href="https://leetcode.com/u/pratyushm206"><img src="https://img.shields.io/badge/leetcode-300%2B%20solved-2dd4bf?style=for-the-badge&logo=leetcode&logoColor=2dd4bf&labelColor=0d1117" alt="LeetCode profile — 300+ problems solved" /></a>
<a href="mailto:pratyushm206@gmail.com"><img src="https://img.shields.io/badge/email-contact-2dd4bf?style=for-the-badge&logo=gmail&logoColor=2dd4bf&labelColor=0d1117" alt="Email Pratyush" /></a>

</div>

## `~/about.md`

```bash
$ cat about.md

name       : Pratyush Mishra
role       : Backend + AI Engineer
education  : Final-year B.Tech CSE (AI & ML), GLBITM · CGPA 8.5
location   : Greater Noida, India
focus      : Node.js/Express · MongoDB · PostgreSQL/Prisma · Gemini API
proof      : 300+ DSA problems · AWS · Cisco CCNA · Palo Alto · Red Hat
status     : open to SDE, Backend, Full Stack & AI/ML roles; internships,
             part-time and contract work
```

I build backend services with clear ownership, authorization, and reliability boundaries so they behave predictably beyond a demo. I integrate AI into product workflows with validation, caching, retries, and cost-aware limits.

## `~/projects`

<table>
<tr>
<td width="50%" valign="top">

### PrepSense
AI-powered mock interviews and placement readiness.

<a href="https://prepsense-mhnn.onrender.com/"><img src="https://prepsense-mhnn.onrender.com/og-image.png" alt="PrepSense interview preparation platform preview" width="100%" /></a>

- Added JWT and bcrypt authentication with session ownership checks to block cross-user access.
- Added live database role checks so admin privilege revocation takes effect immediately.
- Cached Gemini generation and evaluation results with TTL, and retried transient failures in two independent layers.
- Built difficulty-weighted scoring and trend detection to track interview readiness across sessions.
- Applied per-route rate limits to control automated traffic and AI API cost exposure.

`Node.js` `Express` `MongoDB` `Mongoose` `JWT` `Gemini API`

[Live demo →](https://prepsense-mhnn.onrender.com/) · [Source →](https://github.com/pratyushm206/PrepSense)

</td>
<td width="50%" valign="top">

### NutriTrack
AI-assisted calorie and nutrition tracking.

<a href="https://nutri-track-sage.vercel.app/"><img src="https://image.thum.io/get/width/1200/crop/760/https://nutri-track-sage.vercel.app/" alt="NutriTrack nutrition tracking application preview" width="100%" /></a>

- Recognizes foods from text or photos through the Gemini API to speed up meal logging.
- Models users, meals, and nutrition logs in PostgreSQL with Prisma.
- Calculates TDEE, calorie, and protein targets during onboarding.
- Adds calendar history and an AI health chatbot to support ongoing tracking.
- Uses stateless JWT authentication with a Node.js and Express REST API.

`React` `Node.js` `Express` `PostgreSQL` `Prisma` `Gemini API` `Tailwind`

[Live demo →](https://nutri-track-sage.vercel.app/) · [Source →](https://github.com/pratyushm206/NutriTrack)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### AI Resume Analyzer
Resume and job description matching with Gemini.

<a href="https://ai-resume-analyzer-pratyushm206.streamlit.app/"><img src="./assets/ai-resume-analyzer.png" alt="AI Resume Analyzer matching and scoring screen" width="100%" /></a>

- Matches resumes to job descriptions semantically with Sentence Transformers.
- Scores resume sections and highlights skill gaps to focus revisions.
- Generates cover letters and tailored resume content with AI assistance.
- Exports a PDF report with ReportLab for sharing and review.

`Python` `Streamlit` `Sentence Transformers` `Gemini API` `ReportLab`

[Live demo →](https://ai-resume-analyzer-pratyushm206.streamlit.app/) · [Source →](https://github.com/pratyushm206/AI-Resume-Analyzer)

</td>
<td width="50%" valign="top">

### Portfolio
Terminal-themed portfolio for projects and contact details.

<a href="https://portfolio-tau-weld-1pgtqf121q.vercel.app/"><img src="https://image.thum.io/get/width/1200/crop/760/https://portfolio-tau-weld-1pgtqf121q.vercel.app/" alt="Pratyush Mishra terminal-themed portfolio preview" width="100%" /></a>

- Presents work in a terminal-inspired interface with JetBrains Mono typography.
- Includes a lightbox gallery and animated project tiles for browsing work.
- Provides a resume download and direct contact paths.
- Deployed on Vercel for public access.

`React` `Tailwind CSS` `Vercel`

[Live site →](https://portfolio-tau-weld-1pgtqf121q.vercel.app/) · [Source →](https://github.com/pratyushm206/portfolio)

</td>
</tr>
</table>

## `~/stack`

| Category | Tools |
|---|---|
| **Backend** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nodejs,express&theme=dark"><img src="https://skillicons.dev/icons?i=nodejs,express&theme=light" alt="Node.js and Express" /></picture> |
| **Databases** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=mongodb,postgres,prisma,mysql&theme=dark"><img src="https://skillicons.dev/icons?i=mongodb,postgres,prisma,mysql&theme=light" alt="MongoDB, PostgreSQL, Prisma, and MySQL" /></picture> |
| **Frontend** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,tailwind,html,css&theme=dark"><img src="https://skillicons.dev/icons?i=react,tailwind,html,css&theme=light" alt="React, Tailwind CSS, HTML, and CSS" /></picture> |
| **Languages** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java,js,py,c&theme=dark"><img src="https://skillicons.dev/icons?i=java,js,py,c&theme=light" alt="Java, JavaScript, Python, and C" /></picture> |
| **Cloud & systems** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=aws,linux,vercel&theme=dark"><img src="https://skillicons.dev/icons?i=aws,linux,vercel&theme=light" alt="AWS, Linux, and Vercel" /></picture> |
| **Tools** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=git,github,vscode&theme=dark"><img src="https://skillicons.dev/icons?i=git,github,vscode&theme=light" alt="Git, GitHub, and Visual Studio Code" /></picture> |

**AI / LLM:** Gemini API · Prompt engineering · Sentence Transformers · Caching and retry design  
**Core CS:** DSA · OOP · DBMS · Computer Networks

## `~/certifications`

<p>
<img src="https://img.shields.io/badge/AWS%20Academy-Cloud%20Foundations-2dd4bf?style=flat-square&logo=amazonwebservices&logoColor=2dd4bf&labelColor=0d1117" alt="AWS Academy Cloud Foundations" />
<img src="https://img.shields.io/badge/Cisco-CCNA%20Networking-2dd4bf?style=flat-square&logo=cisco&logoColor=2dd4bf&labelColor=0d1117" alt="Cisco CCNA Networking" />
<img src="https://img.shields.io/badge/Palo%20Alto-Cybersecurity%20%26%20Network%20Security-2dd4bf?style=flat-square&logo=paloaltonetworks&logoColor=2dd4bf&labelColor=0d1117" alt="Palo Alto cybersecurity and network security" />
<img src="https://img.shields.io/badge/Red%20Hat-Linux%20SysAdmin%20I%20%26%20II-2dd4bf?style=flat-square&logo=redhat&logoColor=2dd4bf&labelColor=0d1117" alt="Red Hat Linux System Administration I and II" />
</p>

## `~/stats`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=pratyushm206&show_icons=true&hide_border=true&bg_color=0d1117&title_color=2dd4bf&icon_color=2dd4bf&text_color=c9d1d9" alt="GitHub contribution and repository statistics" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pratyushm206&layout=compact&hide_border=true&bg_color=0d1117&title_color=2dd4bf&text_color=c9d1d9" alt="Most-used programming languages on GitHub" />
<br/>
<img src="https://streak-stats.demolab.com/?user=pratyushm206&theme=dark&hide_border=true&background=0d1117&ring=2dd4bf&fire=2dd4bf&currStreakLabel=2dd4bf" alt="GitHub contribution streak" />

</div>

## `~/contact`

```bash
$ ./open_to.sh

full-time   : SDE · Backend · Full Stack · AI/ML
internships : software and AI engineering
flexible    : part-time · contract
```

<div align="center">

<a href="mailto:pratyushm206@gmail.com"><img src="https://img.shields.io/badge/email-pratyushm206%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=2dd4bf&labelColor=0d1117" alt="Email Pratyush Mishra" /></a>
<a href="https://www.linkedin.com/in/pratyushm206"><img src="https://img.shields.io/badge/linkedin-connect-0f766e?style=for-the-badge&logo=linkedin&logoColor=2dd4bf&labelColor=0d1117" alt="Connect with Pratyush on LinkedIn" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,100:0d1117&height=110&section=footer" width="100%" alt="Teal and charcoal waving footer" />

</div>
