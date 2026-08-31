![Mohamed Ramadan](https://raw.githubusercontent.com/MoRmdn/MoRmdn/main/wallpaperflare-cropped.jpg)

<h1 align="center">Mohamed Ramadan</h1>
<h3 align="center">Senior Flutter Developer — cross-platform apps for Android and iOS</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-5%2B%20Years-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Shipped-5%20apps%20on%20App%20Store%20%26%20Google%20Play-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Based%20in-Mansoura%2C%20Egypt-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20to-Remote%20%26%20Gulf%20roles-8A2BE2?style=flat-square" />
</p>

---

I build and ship production Flutter apps end to end — architecture, state, Firebase back end, store release. Five years of it, delivered remotely to teams in Saudi Arabia, Morocco, Libya, Türkiye and the UK, across healthcare, e-commerce, driver education, field service and AI platforms.

The work I am known for is the awkward part of mobile: apps that stay usable with no signal, Arabic-first interfaces that are right-to-left by design rather than by patch, and payment flows that have to clear in seven different gateways.

- Currently a Flutter Developer at **[MisMar](https://mismarapp.com/)**
- Five apps live on the App Store and Google Play, several built solo from empty repo to release
- Offline-first Firestore synchronisation, Cloud Functions, and security-rule authorisation
- Arabic-first RTL localisation, on-device PDF generation, barcode and QR scanning, Google ML Kit
- Bloc, Cubit, GetX, Provider and Riverpod — chosen per feature, not per habit
- Writing at [dev.to/mormdn](https://dev.to/mormdn) · [Full CV](https://github.com/MoRmdn/MoRmdn/blob/main/myResume.pdf)

---

### Selected work

| Project | What it is | Built with | Links |
|---|---|---|---|
| **Arcit-AI** | Social platform matching architecture and home-improvement providers with clients, with AI-driven matchmaking and task automation | Bloc, AI model integration | [App Store](PASTE_APP_STORE_URL) · [Google Play](PASTE_PLAY_URL) |
| **Mutabbib** | Medical social network connecting patients with hospitals, clinics and doctors, with schedule and availability tracking | Bloc, real-time sync, secure storage | [App Store](PASTE_APP_STORE_URL) · [Google Play](PASTE_PLAY_URL) |
| **Lpermis** | Driving-theory testing and appointment booking, used by driving schools across Morocco. Led from initial architecture to release | GetX | [App Store](PASTE_APP_STORE_URL) · [Google Play](PASTE_PLAY_URL) |
| **Lpermis Pro** | Companion edition for schools managing lesson bookings across multiple user roles | Cubit, multi-role logic | [App Store](PASTE_APP_STORE_URL) · [Google Play](PASTE_PLAY_URL) |
| **Saber Yamen** | Multi-vendor marketplace for new and used items, built from scratch | GetX | [App Store](PASTE_APP_STORE_URL) · [Google Play](PASTE_PLAY_URL) |

---

### Case study — AYCO Maintenance Reports

An Arabic-first field-service reporting app for a medical-equipment maintenance company. Built solo, end to end, on Flutter and Firebase. Private client delivery, so the source is closed — the engineering is below.

**The problem.** Technicians service hospital equipment in basements and shielded rooms where connectivity drops, then have to produce a signed, numbered PDF report per device before they leave site.

**What I built.**

- **Every write is offline-safe.** Firestore writes race against a timeout; if the timeout wins, the result surfaces to the technician as *queued*, not *failed*. A visit completes with no connectivity and reconciles later.
- **Batching inside Firestore's limits.** Up to 100 devices per visit, written in resumable 25-report transaction chunks to stay under the transaction cap, with report numbers issued transactionally so two technicians can never claim the same one.
- **Authorisation on the server, not the client.** A three-role model — super admin, admin, technician — enforced in Cloud Functions and security rules.
- **Two build flavours** bound to separate development and production Firebase projects.
- Device serial scanning with registry auto-fill, technician and client signature capture, and on-device numbered PDF generation with QR archival.

---

### Tech stack

**Languages** ·
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**State management** ·
![Bloc](https://img.shields.io/badge/Bloc-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Cubit](https://img.shields.io/badge/Cubit-13B9FD?style=for-the-badge&logo=flutter&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-0288D1?style=for-the-badge&logoColor=white)
![Provider](https://img.shields.io/badge/Provider-4CAF50?style=for-the-badge&logoColor=white)
![GetX](https://img.shields.io/badge/GetX-8A2BE2?style=for-the-badge&logoColor=white)

**Back end and data** ·
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Cloud Functions](https://img.shields.io/badge/Cloud_Functions-FFA000?style=for-the-badge&logo=firebase&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Pusher](https://img.shields.io/badge/Pusher-300D4F?style=for-the-badge&logo=pusher&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Hive](https://img.shields.io/badge/Hive-FFC107?style=for-the-badge&logoColor=black)

**Practices** ·
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-4CAF50?style=for-the-badge)
![SOLID](https://img.shields.io/badge/SOLID-FF5722?style=for-the-badge)
![Testing](https://img.shields.io/badge/Unit_%26_Widget_Testing-C21325?style=for-the-badge&logo=jest&logoColor=white)
![GitFlow](https://img.shields.io/badge/GitFlow-F05032?style=for-the-badge&logo=git&logoColor=white)

**Payments** · FlutterWave · PayU · PayPal · PayStack · Moyasar · Fawry · Stripe

---

### Measured results

Figures below are as reported by the client teams I delivered to.

- 25% increase in appointment bookings on Mutabbib after real-time notification and scheduling
- 20% reduction in data load times through state-management optimisation at Eleven Stars
- 15% improvement in user retention and engagement on Arcit-AI's data-interaction interface
- 15% increase in user satisfaction after leading a Null Safety migration and UI redesign at Bracket Media
- 12% improvement in user retention and a 10% smaller binary at Cyparta

---

### Background

B.Sc. Bioinformatics, Mansoura University (2021) — final-year project graded A+, on mobile application data analysis and visualisation.
Google Flutter Developer Certification, Udemy (2022) · Android Basics Nanodegree, Udacity (2020).
Arabic — native. English — professional working proficiency.

---

<p align="center">
  <a href="mailto:mormdn@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/mormdn"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://dev.to/mormdn"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" /></a>
  <a href="https://www.upwork.com/freelancers/mormdn"><img src="https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white" /></a>
</p>

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=MoRmdn&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MoRmdn&layout=compact&theme=tokyonight&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=MoRmdn&theme=tokyonight" />
</p>
