# Projektplan: Landingpage für Necip Saygili (Creative Developer & Designer)

## 1. Konzept & Vision
Die Landingpage soll Necip Saygili nicht nur als erfahrenen Backend-Entwickler (Shopware 6/PHP), sondern vor allem als **Creative Developer/Graphik-Designer im technischen Bereich** präsentieren. 
Das Hauptmerkmal wird eine immersive 3D-Umgebung sein, die direkt im Browser läuft (basierend auf Babylon.js), um die techniscche und gestalterische Kompetenz sofort erlebbar zu machen.

## 2. Design-Strategie
*   **Ästhetik:** "Dark Mode Modern" – Dunkle Hintergründe, Neon-Akzente oder weiche Verläufe (Fog/Atmosphäre), Fokus auf Typografie und 3D-Interaktion.
*   **Technik:** Nutzung von Babylon.js für flüssige 3D-Effekte.
*   **Parallax-Struktur:** Wie in `parallaxWebSite.html` vorgeschlagen, dient das Scrollen als Navigation durch verschiedene "Szenen" oder "Stationen".

## 3. Struktur der Landingpage (index.html)

### A. Hero-Sektion (Intro)
*   **Visuell:** Ein atmosphärischer Hintergrund (basierend auf `cloudsBeyond.html` oder `worldSphereFog.html`).
*   **Inhalt:** Name "Necip Saygili" und Titel "Senior Backend Developer & Creative Tech Artist".
*   **Interaktion:** Ein dezenter Hinweis "Scrollen zum Entdecken".

### B. Über mich (Profil)
*   **Inhalt:** Basierend auf `profil.md`.
    *   Expertise: Shopware 6, Symfony, AI-assisted Development (10x Efficiency).
    *   Slogan: "Wo Code auf Design trifft – Effizienz durch KI".
*   **Visuell:** Overlay-Text über einer ruhigen 3D-Szene (z.B. `lowPolyWorld.html`).

### C. Portfolio (Die "Exponate")
*   **Konzept:** Eine interaktive Galerie der `examples`.
*   **Integration:**
    *   `oceanBraunianMotion`: Symbol für Dynamik und mathematische Ästhetik.
    *   `marchingCubesSphere`: Demonstration von algorithmischer Formgebung.
    *   `defender`: Einblick in interaktive Logik/Gaming.
*   **Darstellung:** Karten oder "Portale" in der 3D-Welt, die zu den einzelnen HTML-Dateien verlinken.

### D. Technischer Stack & Skills
*   **Inhalt:** PHP 8, Shopware 6, Babylon.js, AI-Integration.
*   **Visuell:** Ein "Partikel-Netzwerk" (basierend auf `noiceParticle3.html`), das die Vernetzung der Technologien symbolisiert.

### E. Kontakt & Footer
*   Links zum GitHub-Profil, Impressum und Kontaktmöglichkeit.

## 4. Technische Umsetzung
1.  **Haupt-Framework:** Babylon.js (wie in den Beispielen vorhanden).
2.  **HTML/CSS:** Ein schlankes Overlay für Texte, das die 3D-Szene nicht überlagert, sondern ergänzt.
3.  **Modularität:** Die `index.html` wird die Kernlogik von `parallaxWebSite.html` übernehmen und für die neuen Inhalte erweitern.

---

**Nächster Schritt:** Nach Ihrer Freigabe beginne ich mit der Erstellung der `index.html` und der notwendigen CSS/JS-Struktur.