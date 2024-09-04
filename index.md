---
title: Online gehostete Anweisungen
permalink: index.html
layout: home
---

# Inhaltsverzeichnis

Die Demos für diesen Kurs basieren auf den Demos aus dem Beschleuniger-Kit [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Es ist wichtig, dass Sie sich vor der Durchführung dieser Schulung mit den Demos vertraut machen. Für mehrere Labs verwenden Sie Beispieldokumente und vorab erstellte Teams-Meetings und E-Mails.

- Laden Sie alle Beispieldokumente [hier](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles) herunter.
- Richten Sie Team-Meetings und E-Mail-Threads ein, indem Sie den Anweisungen [hier](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG) folgen.
- Machen Sie sich mit den interaktiven Funktionen vertraut, die [hier](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012_interactive_experience.pdf) zu finden sind.

    > **HINWEIS:** Die PDF-Datei „Interaktive Funktionen“ wird direkt auf das Gerät (in den Downloadordner) heruntergeladen.

- Sehen Sie sich [hier](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/MS-4012-ENU-PowerPoint.pptx) die aktuellsten Schulungsunterlagen an.

## Beschreibung des Kurses

Entdecken Sie das transformative Potenzial von Microsoft Copilot und seine Auswirkungen auf die Effizienz von Organisationen. Diese Erfahrung wurde für Führungskräfte und Unternehmensleitende ohne Copilot-Lizenz entwickelt und befasst sich mit der Kunst der Erstellung effektiver Prompts. Sie bietet eine interaktive Erfahrung und zeigt, wie Microsoft Copilot für Microsoft 365 nahtlos in die täglichen geschäftlichen Workflows integriert werden kann, um die Produktivität und Innovation zu steigern.

Die Hauptziele für diese Bereitstellung sind:

- Vermitteln, wie effektive Prompts erstellt werden
- Veranschaulichen von Microsoft Copilot (Webbereich) und Führen der Teilnehmenden durch die interaktiven Funktionen
- Vorführen von Microsoft Copilot für Microsoft 365 – Microsoft Copilot (Arbeitsbereich), Wort, Outlook und Teams
- Einladen von Teilnehmenden zum Herunterladen und Testen von Microsoft Copilot für Mobilgeräte

## Kurszeitplan (noch nicht endgültig festgelegt) 

| # | Thema                                 | Details                                                                                          | Total Time      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Erstellen effektiver Prompts in Copilot für Microsoft 365 | - Die Kunst der Prompt-Folie <br> - Aufforderung zum Erstellen einer Folie <br> - Copilot Lab-Folie | 5–10 Minuten    |
| 2 | Microsoft Copilot im Web          | - Demo Microsoft Copilot (Webmodus) <br> - Interaktive Funktionen  <br> - Folie „Sagen Sie uns Ihre Meinung!“ | 35 Minuten      |
| 3 | Funktionsweise von Copilot für Microsoft 365     | - Microsoft Graph-Folie  <br> - Demo Copilot in Word, Microsoft Copilot (Arbeitsmodus), Copilot in Outlook und Copilot in Teams <br> - Testimonial-Folie <br> - Folie zu Microsoft Copilot auf Mobilgeräten | 25 Minuten      |
|   |                                       |                                                                                                  | **Gesamtzeit könnte 70 Minuten betragen** |


Die Hyperlinks zu den einzelnen Demos sind unten aufgeführt.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
