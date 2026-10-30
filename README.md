# CI/CD First Step Demo

[![Python CI Pipeline](https://github.com/sitkeitamas-debug/cicd-first-step/actions/workflows/ci.yml/badge.svg)](https://github.com/sitkeitamas-debug/cicd-first-step/actions/workflows/ci.yml)

Ez a projekt egy egyszerű demostráció a **GitHub Actions** és a **CI/CD** (Continuous Integration) folyamatok működéséről.

## 🚀 Miről szól a projekt?

- **Automata tesztelés:** A GitHub felhőbeli futtatói (GitHub-hosted runners) minden egyes `push` és `pull request` eseménynél automatikusan elindítanak egy tiszta Linux környezetet.
- **Folyamatos integráció:** A rendszer feltelepíti a Python környezetet, és a `pytest` segítségével ellenőrzi, hogy a kód működőképes-e.
- **Státusz visszajelzés:** A sikeres vagy elbukott tesztekről azonnali visszajelzést ad a felületen és e-mailben.

## 🛠️ Használt technológiák

- **Python 3.10**
- **Pytest** (tesztelési keretrendszer)
- **GitHub Actions** (CI/CD pipeline automatizáció)
