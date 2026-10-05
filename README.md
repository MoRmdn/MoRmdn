<div align="center">

# Mohamed Ramadan

**Senior Flutter Developer · Production Mobile Apps**<br>
📍 Mansoura, Egypt 🇪🇬 · Open to roles in KSA · Kuwait · Remote

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://mormdn.com)
[![Email](https://img.shields.io/badge/Email-000000?style=flat-square&logo=gmail&logoColor=white)](mailto:morm9n@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mormdn)
[![dev.to](https://img.shields.io/badge/dev.to-000000?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/mormdn)
[![Upwork](https://img.shields.io/badge/Upwork-000000?style=flat-square&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/mormdn)

</div>

## `$ whoami`

```
> I build Flutter apps that ship to the stores and stay maintainable
  after launch. Clean Architecture, feature-first structure, state
  chosen per feature, Firebase and REST/GraphQL on the backend side.

> 5+ years of Flutter across product teams in Saudi Arabia, Morocco,
  Libya, Türkiye, the UK and Egypt. Five apps live on Google Play
  and the App Store, several built solo from empty repo to release.

> I'm known for the awkward part of mobile: apps that work with no
  signal, Arabic-first RTL by design, and payments across seven
  gateways.

> The hard part is never the first screen. It's the codebase still
  being easy to change a year later.
```

---

## `$ ls ~/shipped`

Apps in production, built and published end to end.

**Published apps**

- **MisMar** — Arabic-first vehicle maintenance and repair platform for Egyptian drivers, with a seven-stage service flow from request to delivery. *Current role.*
- **Arcit-AI** — social platform matching architecture and home-improvement providers with clients, with AI-driven matchmaking. [App Store](https://apps.apple.com/eg/app/arcit-ai/id6503910700) · [Google Play](https://play.google.com/store/apps/details?id=com.mormdn.arcitAI)
- **Lpermis** / **Lpermis Pro** — driving-theory testing and lesson booking for driving schools across Morocco, plus a multi-role edition for schools. Led from architecture to release. [Lpermis](https://apps.apple.com/eg/app/lpermis/id1635317382) ([Play](https://play.google.com/store/apps/details?id=com.demetre.code)) · [Lpermis Pro](https://apps.apple.com/eg/app/lpermis-pro/id6467557160) ([Play](https://play.google.com/store/apps/details?id=com.demetre.institution))
- **Mutabbib** — medical social network connecting patients with hospitals, clinics and doctors; real-time scheduling lifted bookings 25%. [App Store](https://apps.apple.com/eg/app/mutabbib-%D9%85%D8%B7%D8%A8%D8%A8/id6563148338) · [Google Play](https://play.google.com/store/apps/details?id=com.mormdn.mutabbib)
- **Saber Yamen** — multi-vendor marketplace for new and used items, built from scratch. [App Store](https://apps.apple.com/gb/app/saber/id6467415590) · [Google Play](https://play.google.com/store/apps/details?id=com.elevenstars.saber)

<sub>Also shipped: Dental Dinar · FreeDoc · O'Permis · Savior App</sub>

**Client work**

- **AYCO Maintenance Reports** — Arabic-first field-service app for medical-equipment maintenance: barcode scanning, on-device signatures, and QR-coded PDF reports. Built solo on Flutter and Firebase.

  <details>
  <summary>How it works offline</summary>

  - Firestore writes race a timeout; if the timeout wins, the technician sees *queued*, not *failed*, and the visit syncs later.
  - Up to 100 devices per visit, written in resumable 25-report transaction chunks, with report numbers issued transactionally.
  - Three-role permissions (super admin, admin, technician) enforced server-side in Cloud Functions and security rules.
  - Two build flavours bound to separate dev and prod Firebase projects.

  </details>

- **Delivery platform** — subscription-based access with timed visibility of incoming requests.
- **Sports platform** — Flutter client integrated with an existing GraphQL backend.

**How I build**

- **Clean Architecture, feature-first** — each feature owns its data, domain, and presentation layers.
- **State chosen per feature** — Riverpod, Bloc / Cubit, Provider or GetX, matched to the complexity and data flow.
- **Firebase + REST / GraphQL** for auth, data, and push — with offline-first sync and server-side authorisation.
- **Architecture before code** — the plan comes first, generation and implementation second.

---

## `$ stack`

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-000000?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-000000?style=flat-square&logo=dart&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-000000?style=flat-square)
![Bloc](https://img.shields.io/badge/Bloc_/_Cubit-000000?style=flat-square)
![GetX](https://img.shields.io/badge/GetX-000000?style=flat-square)
![Android](https://img.shields.io/badge/Android-000000?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)

**Backend & Data**

![Firebase](https://img.shields.io/badge/Firebase-000000?style=flat-square&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-000000?style=flat-square&logo=supabase&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-000000?style=flat-square)
![GraphQL](https://img.shields.io/badge/GraphQL-000000?style=flat-square&logo=graphql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-000000?style=flat-square&logo=socketdotio&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-000000?style=flat-square&logo=sqlite&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=white)
![Claude](https://img.shields.io/badge/AI--assisted_dev-000000?style=flat-square&logo=anthropic&logoColor=white)

<sub>Also shipped with: Cloud Functions · Firestore Security Rules · Hive · Pusher · Google ML Kit · Google Maps · Provider · GitFlow · unit & widget testing · payments via FlutterWave, PayU, PayPal, PayStack, Moyasar, Fawry, Stripe</sub>

---

## `$ ls ~/projects`

### 🎙️ Personal finance app — *Arabic voice to transactions* <kbd>in progress</kbd>

Speak a transaction in Arabic, get a structured entry. <!-- TODO: status, stack, repo link -->

▸ <!-- github.com/MoRmdn/REPO -->

### 🧩 JS Quest — *free 100-question JavaScript course* <kbd>live</kbd>

Five chapters that unlock in order, progress saved to Postgres, and answers kept server-side behind row-level security so the quiz can't be beaten from the network tab. React, Vite, Supabase.

▸ [js-basics-quiz.vercel.app](https://js-basics-quiz.vercel.app)

---

## `$ history --career`

| Period | Role | Company | Location |
|:--|:--|:--|:--|
| **2025.01 → now** | **Flutter Developer** | **[MisMar](https://mismarapp.com/)** | **KSA · remote** |
| 2024.01 → 2026.01 | Mid-Level Flutter Developer | Ebdda LTD | Libya · remote |
| 2023.12 → 2024.12 | Mid-Level Flutter Developer | Arcit-AI | KSA · remote |
| 2023.03 → 2025.01 | Mid-Level Flutter Developer | Demeter | Morocco · remote |
| 2023.03 → 2024.02 | Medior Flutter Developer | Eleven Stars | Türkiye · remote |

<details>
<summary><b>Earlier roles</b></summary>

| Period | Role | Company | Location |
|:--|:--|:--|:--|
| 2022.05 → 2023.01 | Junior Flutter Developer | Bracket Media Ltd | England · remote |
| 2021.04 → 2022.05 | Junior Flutter Developer | Cyparta | Egypt |

</details>

---

## `$ ping`

📧 [morm9n@gmail.com](mailto:morm9n@gmail.com) · 🔗 [linkedin.com/in/mormdn](https://www.linkedin.com/in/mormdn) · 🌐 [mormdn.com](https://mormdn.com)

<sub><b>B.Sc. Computer Science — Bioinformatics</b>, Mansoura University (2021) · 🇪🇬 Arabic native · 🇬🇧 English professional working proficiency</sub>

<div align="center"><sub>~ Mohamed Ramadan</sub></div>
