# Softwarearchitektur

Hier geht es um technische Details der Softwarearchitektur und Entwicklungsinfrastruktur.

## Framework/Technologie-Stack

* Die Software ist in C# geschrieben, das UI basiert auf WPF.
* Die Software wurde ursprünglich auf Basis des Microsoft .NET Framework entwickelt, im Laufe der Zeit jedoch zuerst auf .NET 6, dann .NET 8 und mittlerweile auf .NET 10 migriert.
* Die Lautstärkemessung erfolgt über die [NAudio](https://github.com/naudio/NAudio)-Bibliothek.
* Die Software ist modular aufgebaut und könnte bei Bedarf um eigene Seiten erweitert werden (siehe [Plugin-Schnittstelle](#plugin-schnittstelle)).

## CI/CD

* Aus historischen Gründen befinden sich die CI/CD Pipelines nicht direkt hier bei GitHub, sondern bei Azure DevOps

## Codebasis

* Hier und da sieht man dem leider Quellcode an, dass einige Features unter recht grossem Zeitdruck noch kurz vor dem Kirschenmarkt implementiert wurden. Dennoch hat sich die Software als äußerst robust erwiesen und ist bislang noch nie während der Veranstaltung abgestürzt.

## Komponenten

## Plugin-Schnittstelle
