
# Softwareentwicklung 2022 - Projekt

[![build](https://github.com/Ifi-Softwareentwicklung-SoSe2022/SWE22_Projekt/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/Ifi-Softwareentwicklung-SoSe2022/SWE22_Projekt/actions/workflows/build.yml)&nbsp;
[![GitHub License](https://img.shields.io/badge/license-MIT-green)](LICENSE)&nbsp;
![visitors](https://visitor-badge.laobi.icu/badge?page_id=Ifi-Softwareentwicklung-SoSe2022/SWE22_Projekt/devlop)&nbsp;

## Zielstellung

>*Transformation von Math.NET Inhalten (Matrizen, Vektoren, Terme usw.) nach Latex*

Das Ergbenis soll ein wiederverwendbare Klassenbibliothek sein, die dem Programmierer die Möglichkeit gibt, mathematische C#-Objekte der Math.NET Bibliothek in LaTeX zu transformieren und als Text zu speichern.

## Aktueller Stand

### CodeMap von [MaTeX.cs](/src/MaTeX/MaTeX.cs)

![](img/MaTeX_CodeMap.png)

### [Dokumentation](/docs/Dokumentation.md)

### Dependencies

- [CSharpMath](https://www.nuget.org/packages/CSharpMath)
- [Math.NET Numerics](https://www.nuget.org/packages/MathNet.Numerics)
- [Math.NET Symbolics](https://www.nuget.org/packages/MathNet.Symbolics)
- [Microsoft.CodeAnalysis.CSharp.Scripting](https://www.nuget.org/packages/Microsoft.CodeAnalysis.CSharp.Scripting)

## Zeitplan

|             Datum | Bemerkung                                                                           |
| -----------------:| ----------------------------------------------------------------------------------- |
|     21. Juni 2022 | Rückmeldung der Gruppen zur Teilnahme an der praktischen Prüfungsleistung           |
|                   | Anlegen eines Repositories und Erläuterung Ihrer Zielstellungen im Wiki             |
|  bis 7. Juli 2022 | Spezifikation einer Fragestellung und zugehöriger Softwareentwurf                   |
| bis 14. Juli 2022 | Bestätigung der Idee und des Entwurfes                                              |
|                   | Bearbeitung der Aufgabenstellung in einem GitHub Projekt mit eingeladenen Betreuern |
|     26. Juli 2022 | (Tag der Klausur) Abschluss der Bearbeitung, die Repos werden gespiegelt.           | 

## Kriterienkatalog

In der Bewertung fließen neben der eigentlichen Implementierung insbesondere der Entwurf und der Entwicklungsprozess ein!

| Aspekt             | Maßstäbe                                                                   | Bewertungsgewicht |
| ------------------ | -------------------------------------------------------------------------- | ----------------- |
| Funktionalität     | Komplexität, Originalität, Grundidee                                       | 20 %              |
| Softwareentwurf    | Klassendesign, Dokumentation des methodischen Vorgehens, integrierte Tests | 20 %              |
| Umsetzung          | Lauffähigkeit, Qualität der Implementierung,                               | 30 %              |
| Versionsmanagement | Entwicklungsfluss auf Github, Teamwork                                     | 20 %              |
| Dokumentation      | Tutorial, Beispielcode, Erläuterungen der API                              | 10 %              |
