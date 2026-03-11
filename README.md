# 📚 AAU Klagenfurt — Sommersemester 2026

> Alpen-Adria-Universität Klagenfurt · Informatik & Technik

---

## 🗂️ Kurse & Repositories

| # | Kurs | Repo | Sprache |
|---|------|------|---------|
| 1 | **App Development** (623.950) | [`aau_S26_App_Development`](https://github.com/Fafoooo/aau_S26_App_Development) | Kotlin |
| 2 | **Betriebssysteme** (621.750) | [`aau_26S_Betriebssysteme`](https://github.com/Fafoooo/aau_26S_Betriebssysteme) | C |
| 3 | **Software Engineering II** (621.250) | [`se2-einzelprojekt-service`](https://github.com/Fafoooo/se2-einzelprojekt-service) | Kotlin · Spring Boot |
| 4 | **Logik** (621.310) | [`aau_26S_Logik`](https://github.com/Fafoooo/aau_26S_Logik) | — |
| 5 | **Lineare Algebra** (311.910) | [`aau_26S_Linear_Algebra`](https://github.com/Fafoooo/aau_26S_Linear_Algebra) | — |

---

## 🛠️ Setup

```bash
# Alle Repos auf einmal klonen
gh repo list Fafoooo --json name,sshUrl \
  -q '.[] | select(.name | test("aau_|se2")) | .sshUrl' \
  | xargs -I {} git clone {}
```

---

<p align="center">
  <sub>🎓 SS 2026 · Fabio Schmickl</sub>
</p>
