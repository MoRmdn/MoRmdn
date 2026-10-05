<div align="center">

# Mohamed Ramadan

**Senior Flutter Developer · Production Mobile Apps**<br>
📍 Suez, Egypt 🇪🇬 · Open to roles in KSA · Kuwait · Remote

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://mormdn.com)
[![Email](https://img.shields.io/badge/Email-000000?style=flat-square&logo=gmail&logoColor=white)](mailto:morm9n@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mormdn)
[![CV](https://img.shields.io/badge/CV-000000?style=flat-square&logo=readthedocs&logoColor=white)](https://github.com/MoRmdn/MoRmdn/blob/main/myResume.pdf)
[![dev.to](https://img.shields.io/badge/dev.to-000000?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/mormdn)
[![Upwork](https://img.shields.io/badge/Upwork-000000?style=flat-square&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/mormdn)

</div>

## `$ whoami`

```
> I build Flutter apps that ship to the stores and stay maintainable
  after launch. Architecture, state, Firebase back end, store release,
  end to end.

> 5+ years of Flutter, delivered remotely to teams in Saudi Arabia,
  Morocco, Libya, Türkiye, Algeria and the UK, across healthcare,
  e-commerce, driver education, field service and AI platforms.
  Currently a Flutter Developer at MisMar.

> The work I'm known for is the awkward part of mobile: apps that stay
  usable with no signal, Arabic-first interfaces that are RTL by design
  rather than by patch, and payment flows that have to clear in seven
  different gateways.

> The hard part is never the first screen. It's the codebase still
  being easy to change a year later.
```

---

## `$ ls ~/shipped`

Five apps live on the App Store and Google Play, several built solo from empty repo to release.

**Published apps**

- **Arcit-AI** — social platform matching architecture and home-improvement providers with clients, with AI-driven matchmaking and task automation. *Bloc, AI model integration.* [App Store](https://apps.apple.com/eg/app/arcit-ai/id6503910700) · [Google Play](https://play.google.com/store/apps/details?id=com.mormdn.arcitAI)
- **Lpermis** — driving-theory testing and appointment booking, used by driving schools across Morocco. Led from initial architecture to release. *GetX.* [App Store](https://apps.apple.com/eg/app/lpermis/id1635317382) · [Google Play](https://play.google.com/store/apps/details?id=com.demetre.code)
- **Lpermis Pro** — companion edition for schools managing lesson bookings across multiple user roles. *Cubit, multi-role logic.* [App Store](https://apps.apple.com/eg/app/lpermis-pro/id6467557160) · [Google Play](https://play.google.com/store/apps/details?id=com.demetre.institution)
- **Mutabbib** — medical social network connecting patients with hospitals, clinics and doctors, with schedule and availability tracking. *Bloc, real-time sync, secure storage.* [App Store](https://apps.apple.com/eg/app/mutabbib-%D9%85%D8%B7%D8%A8%D8%A8/id6563148338) · [Google Play](https://play.google.com/store/apps/details?id=com.mormdn.mutabbib)
- **Saber Yamen** — multi-vendor marketplace for new and used items, built from scratch. *GetX.* [App Store](https://apps.apple.com/gb/app/saber/id6467415590) · [Google Play](https://play.google.com/store/apps/details?id=com.elevenstars.saber)

<sub>Also shipped: <b>MisMar</b> (vehicle service, Egypt) · <b>FreeDoc</b> (trilingual doctor booking, Algeria) · <b>O'Permis</b> (driving licences, Morocco) · <b>Dental Dinar</b> (oral-health companion) · <b>Savior App</b></sub>

**Client work**

- **AYCO Maintenance Reports** — Arabic-first, offline-first field-service app with barcode scanning, on-device signatures, and QR-coded PDF reports. *Case study below.*
- **Delivery platform** — subscription-based access with timed visibility of incoming requests.
- **Sports platform** — Flutter client integrated with an existing GraphQL backend.

**How I build**

- **Clean Architecture, feature-first** — each feature owns its data, domain, and presentation layers. SOLID throughout.
- **State management chosen per feature, not per habit** — Riverpod, Bloc, Cubit, Provider, GetX.
- **Firebase + REST / GraphQL** — offline-first Firestore sync, Cloud Functions, security-rule authorisation.
- **Arabic-first RTL** localisation, on-device PDF generation, barcode and QR scanning, Google ML Kit.
- **Architecture before code** — the plan comes first, generation and implementation second.

---

## `$ cat ~/case-studies/ayco.md`

An Arabic-first field-service reporting app for a medical-equipment maintenance company. Built solo, end to end, on Flutter and Firebase. Private client delivery, so the source is closed — the engineering is below.

**The problem.** Technicians service hospital equipment in basements and shielded rooms where connectivity drops, then have to produce a signed, numbered PDF report per device before they leave site.

<details>
<summary><b>What I built</b></summary>

- **Every write is offline-safe.** Firestore writes race against a timeout; if the timeout wins, the result surfaces to the technician as *queued*, not *failed*. A visit completes with no connectivity and reconciles later.
- **Batching inside Firestore's limits.** Up to 100 devices per visit, written in resumable 25-report transaction chunks to stay under the transaction cap, with report numbers issued transactionally so two technicians can never claim the same one.
- **Authorisation on the server, not the client.** A three-role model — super admin, admin, technician — enforced in Cloud Functions and security rules.
- **Two build flavours** bound to separate development and production Firebase projects.
- Device serial scanning with registry auto-fill, technician and client signature capture, and on-device numbered PDF generation with QR archival.

</details>

---

## `$ cat results.log`

<sub>As reported by the client teams I delivered to.</sub>

```
+25%  appointment bookings on Mutabbib       real-time notifications + scheduling
-20%  data load times at Eleven Stars         state-management optimisation
+15%  retention & engagement on Arcit-AI      data-interaction interface
+15%  user satisfaction at Bracket Media      Null Safety migration + UI redesign
+12%  retention, -10% binary size at Cyparta
```

---

## `$ stack`

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-000000?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-000000?style=flat-square&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-000000?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)

**State management**

![Riverpod](https://img.shields.io/badge/Riverpod-000000?style=flat-square)
![Bloc](https://img.shields.io/badge/Bloc-000000?style=flat-square)
![Cubit](https://img.shields.io/badge/Cubit-000000?style=flat-square)
![Provider](https://img.shields.io/badge/Provider-000000?style=flat-square)
![GetX](https://img.shields.io/badge/GetX-000000?style=flat-square)

**Backend & Data**

![Firebase](https://img.shields.io/badge/Firebase-000000?style=flat-square&logo=firebase&logoColor=white)
![Cloud Functions](https://img.shields.io/badge/Cloud_Functions-000000?style=flat-square&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-000000?style=flat-square&logo=supabase&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-000000?style=flat-square)
![GraphQL](https://img.shields.io/badge/GraphQL-000000?style=flat-square&logo=graphql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-000000?style=flat-square&logo=socketdotio&logoColor=white)
![Pusher](https://img.shields.io/badge/Pusher-000000?style=flat-square&logo=pusher&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-000000?style=flat-square&logo=sqlite&logoColor=white)
![Hive](https://img.shields.io/badge/Hive-000000?style=flat-square)

**Practices & Tooling**

![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-000000?style=flat-square)
![SOLID](https://img.shields.io/badge/SOLID-000000?style=flat-square)
![Testing](https://img.shields.io/badge/Unit_%26_Widget_Testing-000000?style=flat-square)
![GitFlow](https://img.shields.io/badge/GitFlow-000000?style=flat-square&logo=git&logoColor=white)
![Claude](https://img.shields.io/badge/AI--assisted_dev-000000?style=flat-square&logo=anthropic&logoColor=white)

**Also writes**

![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=flat-square&logo=javascript&logoColor=white)
![React](https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=white)
![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white)

<sub>Payments shipped with: FlutterWave · PayU · PayPal · PayStack · Moyasar · Fawry · Stripe</sub>

---

## `$ ls ~/projects`

### 🎙️ Personal finance app — *Arabic voice to transactions* <kbd>in progress</kbd>

Speak a transaction in Arabic, get a structured entry. <!-- TODO: status, stack, repo link -->

▸ <!-- github.com/MoRmdn/REPO -->

### 🧩 JS Quest — *free 100-question JavaScript course* <kbd>live</kbd>

Five chapters that unlock in order, progress saved to Postgres so you can close the tab and come back, and correct answers withheld server-side behind row-level security — the quiz can't be beaten by reading the network tab. React, Vite and Supabase.

▸ [js-basics-quiz.vercel.app](https://js-basics-quiz.vercel.app)

---

## `$ history --career`

| Period | Role | Company | Location |
|:--|:--|:--|:--|
| **YYYY.MM → now** | **Flutter Developer** | **[MisMar](https://mismarapp.com/)** | **Egypt** |
| YYYY.MM → now | Flutter Developer *(Freelance)* | Independent | KSA · MA · LY · TR · DZ · UK |

<details>
<summary><b>Earlier roles</b></summary>

| Period | Role | Company | Location |
|:--|:--|:--|:--|
| YYYY.MM → YYYY.MM | Flutter Developer | Eleven Stars | TODO |
| YYYY.MM → YYYY.MM | Flutter Developer | Bracket Media | TODO |
| YYYY.MM → YYYY.MM | Flutter Developer | Cyparta | TODO |

</details>

---

## `$ ping`

📧 [morm9n@gmail.com](mailto:morm9n@gmail.com) · 🔗 [linkedin.com/in/mormdn](https://www.linkedin.com/in/mormdn) · 🌐 [mormdn.com](https://mormdn.com) · ✍️ [dev.to/mormdn](https://dev.to/mormdn)

<sub><b>B.Sc. Bioinformatics</b>, Mansoura University (2021) — final-year project graded A+ · Google Flutter Developer Certification, Udemy (2022) · Android Basics Nanodegree, Udacity (2020) · Learn JavaScript & Learn React, Scrimba (2026)</sub><br>
<sub>🇪🇬 Arabic native · 🇬🇧 English professional working proficiency</sub>

<div align="center"><sub>~ Mohamed Ramadan</sub></div>
