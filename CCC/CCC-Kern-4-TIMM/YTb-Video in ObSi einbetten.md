
#hl #hlObSi

Ja, es gibt mehrere Möglichkeiten, in **Obsidian** eine **Vorschau von YouTube-Videos** anzuzeigen, statt nur den reinen Linktext. Hier sind die gängigsten Varianten – von eingebaut bis Plugin-basiert:

---

### ✅ **1. Einbettung über Markdown direkt (funktioniert meist ohne Plugin)**

Wenn Du den Link wie folgt **einbettest**, zeigt Obsidian direkt ein eingebettetes YouTube-Video:

```
![](https://www.youtube.com/watch?v=VIDEO_ID)
```

🔁 _Beispiel mit echtem Link:_

```markdown
![](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
```

🔍 **Ergebnis:** Es erscheint ein eingebetteter Player direkt in der Vorschauansicht von Obsidian.

> ⚠️ Wichtig: Das funktioniert **nur**, wenn Obsidian **im Preview-Modus** ist (nicht im Editiermodus) und die Sicherheitseinstellungen externe Inhalte nicht blockieren.

---

### ✅ **2. Einbettung über HTML (auch ohne Plugin möglich)**

Du kannst auch den YouTube-Embed-Code direkt als HTML in Deine Notiz schreiben:

```html
<iframe width="560" height="315"
src="https://www.youtube.com/embed/dQw4w9WgXcQ"
frameborder="0" allowfullscreen></iframe>
```

⚠️ **Aber:** In der **Standardinstallation von Obsidian ist HTML deaktiviert** – es wird also nicht gerendert. Um das zu aktivieren, brauchst Du:

#### 👉 Schritte:

1. Aktiviere **"Reading View"** (Vorschauansicht).
    
2. Installiere ggf. das Community Plugin **"CustomJS"** oder **"Advanced Slides"**, wenn Du regelmäßig HTML nutzen willst.
    
3. In vielen Fällen ist **Lösung 1 (Markdown mit ![]-Syntax)** einfacher.
    

---

### ✅ **3. Plugin: "Media Extended" (falls mehr Kontrolle gewünscht ist)**

Wenn Du mehrere Medienarten einbetten willst (z. B. YouTube, Vimeo, lokale Videos, Podcasts), ist das Plugin **Media Extended** hilfreich.

#### Schritte zur Nutzung:

1. Gehe zu `Settings > Community Plugins > Browse`.
    
2. Suche nach `Media Extended`.
    
3. Installiere und aktiviere das Plugin.
    
4. Nutze dann einfach wieder die `![](YouTube-Link)` Syntax.
    

---

### Fazit

Die einfachste und funktionierende Lösung ohne Plugin ist:

```markdown
![](https://www.youtube.com/watch?v=DEIN_VIDEO_ID)
```

Wechsle dann in den **Preview-Modus** – und das Video wird direkt angezeigt.

---

Möchtest Du stattdessen lieber **nur eine Vorschau-Karte** wie bei Twitter-Links (mit Titel, Beschreibung, Thumbnail), **ohne eingebetteten Player**? Dann müsste man etwas tricksen oder ein spezielles Plugin entwickeln – sag mir Bescheid, falls das Dein Ziel ist.