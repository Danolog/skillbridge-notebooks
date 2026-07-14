# SkillBridge — notebooki Colab ścieżki Data Science

Notebooki ćwiczeniowe ścieżki nauki **SkillBridge** (Grupa Merito). Otwiera się
je linkiem z pozycji ścieżki w SkillBridge — bezpośrednio w Google Colab.

## Jak z nich korzystać (student)

1. Wejdź na pozycję ścieżki w SkillBridge i kliknij **„Otwórz notebook w Google
   Colab"**.
2. Colab pokaże ostrzeżenie, że notatnik nie pochodzi od Google — to standard
   przy każdym notebooku z GitHuba; nasze zawierają wyłącznie widoczny kod.
3. Od L0.2 wzwyż: zrób własną kopię (**Plik → Zapisz kopię na Dysku**) i pracuj
   w niej.
4. Ostatnia komórka każdego notebooka to **pieczątka**: wpisz w niej kod atomu
   z SkillBridge, a wypisany token wklej z powrotem w SkillBridge.

## Dla utrzymujących

⚠ **To repo jest tylko celem publikacji — niczego tu nie edytować.** Źródła
notebooków żyją w prywatnym repo aplikacji
(`tools/content/notebooks/`, builder: `pnpm content:build-notebooks`), gdzie
pilnują ich testy kontraktowe (m.in. parytet pieczątki Python↔TS i identyczność
wspólnego bloku tokenu we wszystkich notebookach). Zmiany robi się tam,
a tu wypycha zbudowane `.ipynb`.

© SkillBridge / Grupa Merito. Materiały edukacyjne ścieżki SkillBridge —
do użytku w ramach platformy.
