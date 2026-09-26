<div align="center">

<img src="./public/icons/icon-512.png" width="96" alt="Aniplex icon" />

# Aniplex

Open-source anime discovery and viewing for people who want to find something, watch it, and come back without losing their place.

<a href="https://www.aniplex.tech/">Open the web app</a>
  ·   <a href="https://github.com/Aniplex/Aniplex-Backend">Backend</a>
  ·   <a href="https://github.com/Aniplex/Aniplex-App">Android app</a>
  ·   <a href="CONTRIBUTING.md">Contribute</a>

</div>

---

## Support Aniplex

Aniplex is open source. Voluntary support helps fund **hosting, releases, and open-source development** and never changes access to site features.

## Sponsor ☕💘

<a href="https://patreon.com/ShoIslam">
<img src="https://user-images.githubusercontent.com/61944859/180249027-678b01b8-c336-451e-b147-6d84a5b9d0e7.png" width="250" alt="Support Aniplex on Patreon"/>
</a>

## Binance Pay

Send directly via Binance Pay to UID:

```text
1098400042
```

Open Binance > Pay > Enter UID > Send. No network fees.

Read the full [Support Guide](./SUPPORT.md).

---

## What Aniplex is

Aniplex keeps discovery, playback, watch history, ratings, bookmarks, comments, and recommendations close to the title you are watching.

The goal is simple: spend less time moving between pages and more time watching.

The main flow is:

```text
discover → watch → remember
```

The catalog uses AniList metadata, schedules, recommendations, and search.

The player supports:

* Adaptive playback
* Provider fallback
* Subtitles
* Dubs
* Quality selection
* Seeking
* Intro/outro skipping where data is available

Progress and personal context remain attached to the title instead of disappearing after playback.

---

## Open the project

<a href="https://www.aniplex.tech/">
<img src="https://img.shields.io/badge/OPEN%20ANIPLEX-Visit%20the%20live%20site-3B82F6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open Aniplex live site" />
</a>

<a href="https://github.com/Aniplex/Aniplex-App">
<img src="https://img.shields.io/badge/ANDROID-App%20repository-111827?style=for-the-badge&logo=android&logoColor=3DDC84" alt="Open Aniplex Android repository" />
</a>

---

## Main areas

| Area                 | What it covers                                                             |
| :------------------- | :------------------------------------------------------------------------- |
| **Discovery**        | Catalog browsing, schedules, recommendations, filters, and search.         |
| **Playback**         | Adaptive quality, provider fallback, subtitles, dubs, and player controls. |
| **Personal context** | Watch history, ratings, bookmarks, comments, and Continue Watching.        |
| **Title pages**      | Watched state, next episode, ratings, metadata, and a Rewatch path.        |
| **Responsive UI**    | Desktop, tablet, iOS, Android, and touch-friendly layouts.                 |

---

## Built with

`React` · `Vite` · `TanStack Query` · `styled-components` · `Artplayer` · `HLS.js` · `AniList` · `Supabase`

The frontend lives in `src/`.

The playback, provider coordination, and synchronization boundary is maintained separately in [Aniplex-Backend](https://github.com/Aniplex/Aniplex-Backend).

---

## Run locally

### 1. Clone the repository

```bash
git clone https://github.com/Aniplex/Aniplex.git
cd Aniplex
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

The application will start using the local Vite development server.

---

## Available commands

Before opening a pull request, run the checks that match your change:

```bash
npm run lint
npm run build
npm run test:bots
npm run test:e2e
```

| Command             | Purpose                                  |
| :------------------ | :--------------------------------------- |
| `npm run dev`       | Start the local Vite development server. |
| `npm run build`     | Build the production bundle.             |
| `npm run preview`   | Preview the production build.            |
| `npm run lint`      | Run ESLint checks.                       |
| `npm run test:bots` | Run player and route smoke checks.       |
| `npm run test:e2e`  | Run Playwright end-to-end checks.        |

---

## Project structure

```text
Aniplex/
├── public/
│   └── icons/
│       └── icon-512.png
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── utils/
│   └── ...
│
├── CONTRIBUTING.md
├── SUPPORT.md
├── package.json
├── vite.config.*
└── README.md
```

The exact structure may change as the project develops.

---

## Contributing

Contributions are welcome when they make the experience:

* Faster
* Clearer
* More accessible
* More reliable
* Easier to maintain

Read [CONTRIBUTING.md](CONTRIBUTING.md) before changing player, authentication, synchronization, or upstream integrations.

### Reporting issues

For issues, include:

* Route or page where the issue occurs
* Device and browser
* A short reproduction path
* Console errors, if available
* Network errors, if relevant

For visual changes, screenshots of both desktop and mobile states make review much easier.

---

## Development workflow

```text
Developer
    ↓
Git Clone
    ↓
Install Dependencies
    ↓
Local Development
    ↓
npm run lint
    ↓
npm run test
    ↓
npm run build
    ↓
Pull Request
    ↓
Code Review
    ↓
Merge
    ↓
Deploy
```

---

## Technology overview

| Technology            | Purpose                                |
| :-------------------- | :------------------------------------- |
| **React**             | Frontend user interface                |
| **Vite**              | Development server and build tooling   |
| **TanStack Query**    | Server-state and API data management   |
| **styled-components** | Component-based styling                |
| **Artplayer**         | Video player interface                 |
| **HLS.js**            | HLS adaptive video playback            |
| **AniList**           | Anime metadata and catalog information |
| **Supabase**          | Backend services and data management   |
| **Playwright**        | End-to-end testing                     |

---

## Project goals

Aniplex aims to provide a simple anime experience where users can:

1. Discover anime.
2. Search and filter titles.
3. View detailed anime information.
4. Watch available episodes.
5. Track viewing progress.
6. Continue watching from where they stopped.
7. Rate and bookmark titles.
8. Receive recommendations.
9. Use the application across desktop and mobile devices.

---

## Support the project

If Aniplex is useful to you, voluntary support helps maintain:

* Hosting infrastructure
* Releases
* Development
* Open-source maintenance

Support does not change access to site features.

---

<div align="center">

### Find it. Watch it. Keep your place.

**Aniplex — Open-source anime discovery and viewing**

</div>
