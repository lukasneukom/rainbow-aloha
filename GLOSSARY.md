# Rainbow Aloha

Ein Obsidian-Plugin, das nach `@` im Editor Datumswörter in der Sprache der Nutzerin oder des Nutzers vorschlägt und das gewählte Datum als Link einfügt.

## Language

**Date Word**:
Ein Wort mit einem Tagesabstand zu heute, zum Beispiel *Heute* (0), *Morgen* (+1), *Gestern* (−1), *Übermorgen* (+2) und *Vorgestern* (−2). Es besteht immer aus genau einem Wort ohne Leerzeichen.
_Avoid_: Keyword, Shortcut

**Suggestion**:
Ein Date Word, wie es im Menü nach `@` angezeigt wird. Gefunden wird es über den Wortanfang, wobei Akzente und Grossschreibung ignoriert werden.
_Avoid_: Treffer, Vorschlag-Eintrag

**Date Link**:
Das eingefügte Ergebnis einer gewählten Suggestion, zum Beispiel `[[2026-07-05]]`.
_Avoid_: Datumslink, Date Reference

**Locale**:
Die Date Words einer Sprache. Heute, Morgen und Gestern sind Pflicht, Übermorgen und Vorgestern sind freiwillig. Fehlt ein Date Word in einer Locale, zeigt das Menü es nicht an und weicht nie auf eine andere Sprache aus.
_Avoid_: Sprachpaket, Übersetzung

**Fallback Language**:
Die Sprache, die gilt, wenn Obsidian auf Englisch oder auf eine nicht unterstützte Sprache eingestellt ist. Aktuell Spanisch.
_Avoid_: Standardsprache
