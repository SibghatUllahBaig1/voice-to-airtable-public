<div align="center">

# 🎙️ Voice to Airtable

**Talk to your Airtable base. Add, update, delete and look up records by voice — with schema-aware AI that understands your tables.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat-square&logo=airtable&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

</div>

> 🔒 **Source code is private** (commercial product). This page is a case study of what I designed and built end to end.

---

## 🎯 The problem

Airtable is brilliant on a desktop — but on the move, finding the right base, table and fields just to log one record is slow. Field staff and busy owners end up skipping updates, so the data falls behind reality.

## 💡 The solution

**Voice to Airtable** is a mobile voice assistant for your Airtable bases. Say *"Add a new client, Acme Ltd, follow up on Friday"* or *"Mark the Johnson job as complete"* and the app works out which table and fields you mean, shows a quick confirmation, and writes the change to Airtable.

---

## ✨ Key features

| Feature | What it does |
|---|---|
| 🎤 **Voice-driven CRUD** | Add, query, update and delete records using natural speech. |
| 🧠 **Schema-aware understanding** | Reads your base's tables and field types so spoken input is mapped to the right columns. |
| 🔗 **Linked-record matching** | Spoken names are matched to existing records (including linked fields) for accurate updates, deletes and lookups. |
| ✅ **Confirmation before writing** | A clear summary of what will change, so mistakes are caught before they hit your data. |
| 🔐 **Google sign-in** | Secure accounts with user profiles stored in Firestore. |
| 🖼️ **Image attachments** | Capture photos and attach them to records. |
| 🌍 **Multi-language** | Localized interface and speech handling. |
| 🎨 **Themed, polished UX** | Welcome flow, themed screens and instant return to Home after a successful write. |

---

## 🏗️ Architecture & engineering highlights

- **Feature-first architecture** with clean separation of `models`, `services`, `features`, `design` and `utils`.
- **AI pipeline** — speech-to-text feeds a schema-aware parser (Gemini) that returns structured actions, with deterministic fallbacks for reliability.
- **Fuzzy name resolution** — spoken names are reconciled against existing Airtable records before updating or deleting.
- **Serverless backend** — Firebase Cloud Functions broker all Airtable calls, so API tokens never live in the app.
- **Firebase** Auth, Firestore and Storage with locked-down security rules.
- **Deep links & secure OAuth flow** via App Links and WebView for connecting a user's Airtable account.
- **Fast iteration** — device preview for responsive testing across screen sizes.

## 🧰 Tech stack

**Flutter · Dart · GetX · Airtable API · Google Gemini · Speech-to-Text · Firebase Auth · Cloud Firestore · Cloud Functions · Firebase Storage · Google Sign-In · App Links**

---

## 📸 Screenshots & links

<!-- Add screenshots: <img src="screenshots/home.png" width="220"/> -->
*Screenshots and demo available on request.*

---

## 🤝 Want an app like this?

I build voice-powered and AI-assisted mobile apps and automations that connect to the tools your team already uses.

📫 **sibghat.developlogix@gmail.com** · 🌐 **[developlogix.com](https://www.developlogix.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/sibghat-ullah-baig-4a2812a1)**

<sub>Built by [Develop Logix](https://www.developlogix.com)</sub>
