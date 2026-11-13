# Hallo, ich bin Enrico 👋

**Senior Software Developer aus Potsdam.** Ich entwickle Webanwendungen von der Anforderung bis zum laufenden Betrieb, seit 2011 mit PHP, später auch mit Java und TypeScript.

Mir ist wichtig, dass Software für Nutzer genauso verständlich ist wie für das Team, das sie weiterentwickelt. Deshalb interessiert mich nicht nur der Code, sondern auch alles drumherum: Deployment, Qualitäts-Gates und Standards, die über viele Projekte hinweg halten.

![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

## Woran ich gerade arbeite

Neben meiner Arbeit betreibe ich rund ein Dutzend Web-Projekte: eigene Ideen, aber auch Seiten, mit denen ich Vereine und Initiativen unterstütze, von statischen Seiten bis zu einer Vereinsverwaltung in Laravel. Damit das mit wenig Aufwand stabil bleibt, habe ich eine kleine Plattform gebaut:

```mermaid
flowchart LR
    subgraph Standards
        K[Seiten-Baukasten<br/>Layout, SEO, CSP, Recht]
        P[PWA-Baukasten<br/>Manifest, Service Worker]
        L[Launch-Checkliste<br/>Security, SEO, Recht]
    end
    K -- Pull Request --> R[(12 Projekt-Repos)]
    P -- Pull Request --> R
    L -- KI-Agent prüft --> R
    R --> CI[GitHub Actions<br/>Build, Links, Indexierung]
    CI --> D[Deploy-Werkzeug<br/>mit Prüf-Gates]
    D -->|Gates grün| S[Server<br/>atomarer Release]
    S -->|Smoke-Test rot| RB[automatischer Rollback]
```

- **Ein Standard, viele Projekte:** Gemeinsame Bausteine kommen per Pull Request in jedes Projekt, ohne npm-Registry und ohne Token in der CI.
- **Deployments, die sich selbst absichern:** Erst CI, Changelog, Qualität (axe, Lighthouse) und Kit-Stand prüfen, dann atomar umschalten, bei Fehlern automatisch zurück.
- **KI-Agenten mit festen Regeln:** Aufgaben laufen als Tasks mit Pull-Request-Pflicht und Freigabe, die Agenten setzen um, ich entscheide.

## Kontakt

🌐 [rufnak.de](https://www.rufnak.de) · 💼 [LinkedIn](https://www.linkedin.com/in/enricorufnak) · [XING](https://www.xing.com/profile/Enrico_Rufnak)

<sub>Die meisten meiner Projekte sind privat. Was hier öffentlich liegt, ist bewusst ausgewählt.</sub>
