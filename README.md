# Mustervorlage für ein Online-Lernangebot

## Was ist das hier?

Diese Website ist eine Mustervorlage für ein Online-Lernangebot. 
Sie entstand in der Corona-geprägten Zeit im März 2020, um Workshops, die zuvor als Präsenzangebote gestaltet waren - in ein Online-Format zu überführen.
Das Konzept dahinter ist [in diesem Blogbeitrag im eBildungslabor](https://ebildungslabor.de/blog/onlineformat/) erklärt.

## Wie gestalte ich meine eigene Website?

Die Website ist ein Projekt auf Glitch. Du kannst es Dir kopieren und dann anpassen.

Klicke dazu auf den folgenden Button und folge dann der weiteren Anleitung:
<a class="glitch-remix" href="https://glitch.com/edit/#!/remix/onlinelernangebot-muster">
  <img alt="Remix on Glitch" src="https://cdn.gomix.com/f3620a78-0ad3-4f81-a271-c8a4faa20f86%2Fremix-button.svg">
</a>

### Welche grundlegenden Einstellungen muss ich vornehmen?

Um aus der Mustervorlage Dein eigenes Lernangebot zu machen, sind insbesondere die folgenden Schritte wichtig:

1. Wähle eine passende URL für Deine Website. Beim Remix ist ein Zufallslink generiert worden, den Du links oben siehst und anpassen kannst.
2. Ersetze 'Muster Online-Lernangebot' durch den Namen deines Online-Lernangebots. Dazu öffnest Du unter src und data die Dateiei siteData.json und trägst es dort ein.
3. Passe die wichtigen Links auf der Startseite an. Dazu öffnest Du unter Layouts die Datei home.njk und ersetzt die Beispielslinks durch Deine richtigen. 

### Wie passe ich Inhalte und Texte der Beiträge an?

Alle Beiträge findest Du unter `src/`. In der Mustervorlage sind die folgenden Dateien enthalten
  - `index.md`, die 🏡
  - `orientierung.md`, which you are reading right now
  - `einstieg.md`, which is an example post that you can duplicate over and over again for new content.

Wenn Du andere/ weitere Beiträge brauchst, kannst Du einfach einen der bisherigen Beiträge (nicht die index.md) kopieren und dann umgestalten. Die neuen Beiträge werden dann automatisch auf der Startseite hinzugefügt.

### Wie kann ich die Website zusätzlich gestalten?

Die Website verwendet das Open Source Framework  [eleventy](https://www.11ty.io/). Es gibt dazu ausführliche Anleitungen.
Kurz gefasst:
- In`src/_includes/layouts`. Findest Du die HTML-Layoutvorlagen für
  - `home.njk`, was für `index.md` verwendet wird und in dem Du bereits die Links angepasst hast.
  - `post.njk`, was von allen anderen Beiträgen verwendet wird.

Das Deign der Website findest Du in `css/style.css`

### Von wem stammt diese Vorlage?

Die Vorlage ist entwickelt im <a href="https://ebildungslabor.de">eBildungslabor</a> - basierend auf einem Webring-Template von <a href="https://twitter.com/notwaldorf">Monica</a> und <a href="https://twitter.com/jllord">Jessica</a>. 
