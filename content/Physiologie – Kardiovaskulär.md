---
tags:
  - Anästhesie/Physiologie
  - EDAIC/Part-I
  - Kardiovaskulär
  - Prüfung
aliases:
  - Kardio Physio
  - Herz-Kreislauf Physiologie
date: 2026-03-22
status: fertig
---

# Kardiovaskuläre Physiologie

*Examensorientierte Zusammenfassung | Facharztweiterbildung Anästhesiologie*

> [!abstract] Themenübersicht
> [[#1 Aktionspotenzial]] · [[#2 Herzkreislauf – Grundlagen]] · [[#3 Hämodynamik]] · [[#4 Preload & Afterload]] · [[#5 Frank-Starling-Mechanismus]] · [[#6 Koronarperfusion]] · [[#7 Baroreflexe]] · [[#8 Autoregulation]] · [[#9 Kreislaufregulation]]
>
> → Übungsaufgaben: [[MTF – Kardiovaskuläre Physiologie]]

---

## 1 Aktionspotenzial

### 1.1 Ventrikuläres Arbeitsmyokard

Das kardiale AP unterscheidet sich durch seine lange **Plateauphase (Phase 2)** vom neuronalen AP → verhindert tetanischen Dauerkrampf.

| Phase | Ionenstrom | Charakteristika |
|---|---|---|
| **Phase 0** – Depolarisation | Schneller Na⁺-Einstrom (I~Na~) | Vmax ~200 V/s; Schwelle ca. −70 mV |
| **Phase 1** – Frühe Repolarisation | Transienter K⁺-Ausstrom (I~to~) | Kurzer Knick nach Spitze |
| **Phase 2** – Plateau | L-Typ Ca²⁺ (I~Ca-L~) ↔ K⁺ (I~Kr~, I~Ks~) | Dauer 200–300 ms; spezifisch für Herz |
| **Phase 3** – Repolarisation | K⁺-Ausstrom dominiert (I~Kr~, I~Ks~, I~K1~) | Rückkehr zu −90 mV |
| **Phase 4** – Ruhepotenzial | Stabil bei **−90 mV** (Arbeitsmyokard) | Schrittmacher: langsame Depolarisation (I~f~) |

> [!tip] Klinik Anästhesie
> Volatile Anästhetika (Halothan > Isofluran > Sevofluran) **verlängern QTc** → Phase-3-Hemmung → Torsades de pointes (TdP)-Risiko bei LQTS, Hypokaliämie.
> Kalziumantagonisten (Verapamil, Diltiazem) blockieren **Phase 2** → neg. Dromotropie → SVT-Therapie (cave: neg. Inotropie).

### 1.2 Sinusknoten-Schrittmacherpotenzial

- **RMP:** −60 mV (weniger negativ als Arbeitsmyokard)
- **Spontandepolarisation (Phase 4):** I~f~ (HCN-Kanäle) + I~Ca-T~ → Adrenalin ↑, Ach ↓
- **Phase 0:** Langsamer Ca²⁺-Einstrom (I~Ca-L~) — **kein** Fast-Na⁺-Kanal
- **Fehlen von Phase 1/2:** kein stabiles Plateau

**Schrittmacherhierarchie:**

| Struktur | Eigenfrequenz |
|---|---|
| Sinusknoten | 60–100 /min |
| AV-Knoten / Junktional | 40–60 /min |
| His-Purkinje / Ventrikel | 20–40 /min |

### 1.3 Refraktärzeit

- **ARP** (Absolute Refraktärzeit): Phase 0–3 → kein AP auslösbar → kein Tetanus möglich ✓
- **RRP** (Relative Refraktärzeit): Late Phase 3 → vulnerable window → **R-on-T** → VF-Gefahr
- **ERP** (Effektive Refraktärzeit): Na⁺-Kanäle noch inaktiviert

> [!warning] Klinik Intensiv
> R-on-T durch externen Schrittmacher oder DC-Kardioversion in der RRP → VF-Risiko.
> → **Synchronisierte Kardioversion** obligat (außer pulslosem VT/VF)!

---

## 2 Herzkreislauf – Grundlagen

### 2.1 Anatomisch-funktionelle Prinzipien

- **Rechtes Herz:** Niederdrucksystem (PAP ~25/10 mmHg, mPAP <25 mmHg)
- **Linkes Herz:** Hochdrucksystem (~120 mmHg systolisch)
- **Serienschaltung:** beide Ventrikel → gleiche Schlagvolumina (langfristig obligat)
- **Parallelschaltung** der Organgefäße → unabhängige regionale Regulation

### 2.2 Herzzyklus

| Phase | Beschreibung |
|---|---|
| **Isovolumetrische Kontraktion** | Alle Klappen geschlossen; Druckanstieg ohne Volumenänderung; ~25 % des myokardialen O₂ |
| **Austreibungsphase** | Aortenklappe offen; EF normal 55–70 % |
| **Isovolumetrische Relaxation** | Alle Klappen geschlossen; LVEDP-Abfall |
| **Füllung (Diastole)** | Rapid filling ~70–80 % → slow filling → atriale Kontraktion ~15–30 % |

### 2.3 Normalwerte – Schnellreferenz

| Parameter | Normalwert |
|---|---|
| Herzfrequenz | 60–100 /min |
| Schlagvolumen (SV) | ~70 mL (50–100 mL) |
| **Herzzeitvolumen (HZV)** | **4–8 L/min** |
| **Herzindex (CI)** | **2,5–4,0 L/min/m²** |
| LVEDP | 5–12 mmHg |
| Ejektionsfraktion (EF) | 55–70 % |
| **SVR** | **800–1200 dyn·s·cm⁻⁵** |
| **PVR** | **50–150 dyn·s·cm⁻⁵** |
| **MAP** | **70–105 mmHg** |
| ZVD | 2–8 mmHg |
| PCWP | 6–12 mmHg |
| MVO₂ | ~9–10 mL/min/100 g |

---

## 3 Hämodynamik

### 3.1 Grundgleichungen

| Formel | Gleichung |
|---|---|
| **Hagen-Poiseuille** | Q = (ΔP · π · r⁴) / (8 · η · L) → Fluss **∝ r⁴** |
| **Ohmsches Gesetz** | MAP − ZVD = HZV × SVR |
| **MAP** | DBP + 1/3 × (SBP − DBP) ≈ DBP + PP/3 |
| **SVR** | (MAP − ZVD) / HZV × 80 [dyn·s·cm⁻⁵] |
| **PPV** | (PP~max~ − PP~min~) / PP~mean~ × 100; **>13 % → Volumenresponsivität** |
| **SVV** | >13 % (kontrolliert beatmet) → Volumenresponsivität |

### 3.2 Strömungsprinzipien

- **Laminär:** Re < 2000 → geräuschlos, viskositätsabhängig
- **Turbulent:** Re > 4000 → Geräusche (Herzgeräusche), druckverlustreich
- **Optimaler Hkt:** 35–45 % (Viscositäts-O₂-Transport-Kompromiss)
- **Kapazitätsgefäße (Venen):** 65–70 % des Blutvolumens

### 3.3 O₂-Transport

| Parameter | Formel / Normalwert |
|---|---|
| **CaO₂** | (Hb × 1,34 × SaO₂) + (PaO₂ × 0,0031) [mL/dL] |
| **DO₂** | HZV × CaO₂ × 10 → **Normal ~1000 mL/min** |
| **VO₂** | HZV × (CaO₂ − CvO₂) × 10 → **Normal ~250 mL/min** |
| **O₂ER** | VO₂/DO₂ × 100 → **Normal 20–25 %; kritisch >50 %** |
| ScvO₂ / SvO₂ | >70 % / >65 % → Zielwert Intensivmedizin |

> [!danger] Kritischer DO₂
> Kritische DO₂-Schwelle: **~300 mL/min** → darunter VO₂ ∝ DO₂ (supply-dependency) → anaerober Metabolismus → **Laktat ↑**
> Ziele: Laktat <2 mmol/L, ScvO₂ >70 % (Sepsis-Bundle)

---

## 4 Preload & Afterload

### 4.1 Preload

- **Definition:** Myokarddehnung am Ende der Diastole (LVEDV/LVEDP) → Sarkomerlänge
- **Klinische Surrogate:** ZVD (RV-Preload), PCWP (LV-Preload), LVEDVI (volumetrisch besser)

| Preload ↑ | Preload ↓ |
|---|---|
| Volumenload, Bradykardie | Hypovolämie, Tachykardie |
| Aortenklappeninsuffizienz | PEEP ↑, Vasodilatation |
| Diastolische Dysfunktion | Nitrate, Diuretika |

> [!note] Merke PCWP
> **PCWP ≠ LVEDP** bei:
> - PEEP ↑ (PCWP überschätzt LVEDP)
> - Mitralstenose (PCWP > LVEDP)
> - Reduzierter LV-Compliance (LVEDP ↑ bei normalem PCWP)

### 4.2 Afterload

- **Definition:** Wandspannung während Systole → **Laplace: T = P·r / 2h**
- **Klinisches Surrogat:** SVR = (MAP − ZVD) / HZV × 80

| Afterload ↑ | Afterload ↓ |
|---|---|
| Vasokonstriktion, Hypertonie | Vasodilatation, Sepsis |
| Aortenstenose, Viskosität ↑ | Nitroprussid, Nitroglycerin |
| Kompensation bei Schock | Volatile Anästhetika |

### 4.3 Klinische Implikationen

| Zustand | Preload | Afterload |
|---|---|---|
| Sepsis (distributiv) | ↓ (Pooling) | ↓↓ (SVR ↓) |
| Kardiogener Schock | ↑ (Rückstau) | ↑ (kompensatorisch) |
| Spinalanästhesie | ↓ | ↓ |
| Aortenstenose | normal–↑ | ↑↑ (fixierte Obstruktion) |
| HOCM | kritisch abhängig | ↑ wünschenswert |

> [!tip] Klinik Anästhesie
> Inhalationsanästhetika: SVR ↓ (Afterload ↓) + neg. Inotropie → HZV-Abfall bei eingeschränkter LV-Funktion.
> **Ketamin:** SVR ↑ + HF ↑ (Sympathomimetikum) → erhaltenes HZV, aber O₂-Bedarf ↑.

---

## 5 Frank-Starling-Mechanismus

### 5.1 Grundprinzip

- SV nimmt mit steigendem LVEDV (Preload) zu — bis zum optimalen Sarkomerlängenbereich
- **Molekulare Basis:** Aktin-Myosin-Überlappung + Ca²⁺-Sensitivität der Myofilamente bei Dehnung
- **Optimale Sarkomerlänge:** ~2,2 µm → maximale Kraftentwicklung
- Überdehnung (>2,4 µm): Kraft ↓ → absteigender Schenkel (in vivo selten → Perikard limitiert)
- Normales Herz: arbeitet auf **aufsteigendem Schenkel**

### 5.2 Kurvenverschiebungen

| Intervention | Auswirkung |
|---|---|
| Volumenbelastung | Preload ↑ → SV ↑ → HZV ↑ (bis Plateau) |
| Herzinsuffizienz | Flachere Kurve: gleicher Preload → weniger SV |
| **Positiv inotrop** (Dobutamin) | Kurve **nach oben-links** verschoben |
| **Negativ inotrop** (Metoprolol) | Kurve nach unten-rechts |
| Vorlastsenkung (Nitrate) | Bewegung nach links auf Kurve → SV ↓ |

> [!tip] Klinik Intensiv – Volumenresponsivität
> Nur ~50 % der Intensivpatienten sind volumenresponsiv.
> **Methoden:** Passive Leg Raise (PLR) + Echo (ΔSV ≥10 %) oder PPV/SVV >13 % beim kontrolliert beatmeten Patienten.
> Ziel: Patient auf **aufsteigendem Schenkel** der Frank-Starling-Kurve halten.

---

## 6 Koronarperfusion

### 6.1 Anatomische & zeitliche Besonderheiten

- **LCA:** ~70 % der Herzversorgung; perfundiert LV
- **RCA:** ~30 %; Sinusknoten, AV-Knoten, RV (dominant in ~70 %)
- **LV-Perfusion: fast ausschließlich DIASTOLISCH** (systolische Kompression hebt Koronarfluss auf)
- **RV-Perfusion:** systolisch UND diastolisch (geringer Wanddruck)
- **CPP (links):** `DBP − LVEDP` → Normal: ~80 − ~8 = **~72 mmHg**

### 6.2 Regulation des Koronarflusses

| Mechanismus | Beschreibung |
|---|---|
| **Metabolische Autoregulation** | Hauptmechanismus: Adenosin, CO₂, H⁺, K⁺ → Vasodilatation |
| Myogene Autoregulation | Bayliss-Effekt (druckabhängige Vasokonstriktion) |
| Neuronale Kontrolle | α₁: Vasokonstriktion; β₂: Vasodilatation |
| Endothelial | NO (EDRF) → Dilatation; Endothelin-1 → Konstriktion |
| Autoregulationsbereich | MAP **60–140 mmHg** → konstanter Fluss |

### 6.3 Koronare O₂-Extraktion

- Ruhezustand: **~75 % O₂-Extraktion** (Skelettmuskel: ~30 %)
- Bei Mehrbedarf → **kein Extraktionsreservoir** → muss über Fluss ↑ gedeckt werden
- **Koronare Flussreserve (CFR):** max. Fluss / Ruhefluss = **3–5** normal; bei KHK ↓

### 6.4 Klinische Schlüsselkonzepte

| Situation | CPP-Effekt | Konsequenz |
|---|---|---|
| **Tachykardie** | Diastole ↓ | Ischämiegefahr! Ziel HF <80/min |
| Hypovolämie / Hypotonie | DBP ↓ → CPP ↓ | MAP-Ziel >65 mmHg (>80 bei KHK) |
| LVEDP ↑ (Herzinsuffizienz) | CPP ↓ (Nenner ↑) | Vorlastsenkung sinnvoll |
| Aortenklappeninsuffizienz | DBP ↓ → CPP ↓↓ | Häufig Koronarsymptomatik |
| IABP | Diastolische Augmentation | Einsatz bei kardiogenem Schock |

> [!warning] Klinik Anästhesie
> **Tachykardie = wichtigster Risikofaktor** für perioperative Myokardischämie.
> Ziel intraoperativ: **HF 55–75/min**, MAP ≥65 mmHg (bei KHK ≥80 mmHg).
> Beta-Blocker perioperativ fortführen (Nutzen > Risiko bei Hochrisikopatienten).

---

## 7 Baroreflexe

### 7.1 Anatomie & Afferenzen

| Ort | Nerv | Zentrum |
|---|---|---|
| **Karotissinus** | CN IX (Hering-Nerv) | NTS (Nucleus tractus solitarius) |
| **Aortenbogen** | CN X (Aortendepressornerv) | NTS |
| Kardiopulmonale Rezeptoren | CN X aus Vorhöfen/Lunge | Blutvolumenkontrolle |

### 7.2 Reflexbogen (arterielle Barorezeptoren)

```
Blutdruck ↑
  → Dehnung Karotissinus
  → ↑ Afferenzfeuerung (CN IX → NTS)
  → ↑ Parasympathikus (Vagus) → HF ↓
  → ↓ Sympathikus (RVLM) → Vasodilatation + neg. Chronotropie
  → Blutdruck ↓ (Feedback-Stabilisierung)
```

> [!note] Barorezeptor-Reset
> Bei **chronischer Hypertonie** adaptieren Barorezeptoren auf höheres Druckniveau → postoperativer Blutdruckabfall kann ausbleibende Gegenregulation erzeugen!

### 7.3 Klinische Syndrome

- **Vagale Reaktion (Karotissinusmassage):** HF-Abfall → Diagnose/Therapie SVT
- **Bezold-Jarisch-Reflex:** Dehnungsrezeptoren Hinterwand (Inferior-STEMI, Spinalanästhesie, Hypovolämie) → massiver Vagotonus → **Bradykardie + Hypotonie + Vasodilatation** (ohne Tachykardie!)
- **Valsalva:** Phase II: BP ↓ → Tachykardie; Phase IV: BP ↑ → Bradykardie

> [!danger] Klinik Anästhesie – Hohe Spinalanästhesie
> Sympathikolyse (Th1–Th5) → Kardioakzeleratorfasern gelähmt → **keine HR-Kompensation** bei Hypotonie möglich.
> Therapie: Atropin + Vasopressor (Noradrenalin/Phenylephrin) + Volumengabe + ggf. Adrenalin

---

## 8 Autoregulation

### 8.1 Definition & Prinzip

> **Autoregulation** = Fähigkeit eines Organs, seinen Blutfluss bei Druckschwankungen konstant zu halten

Mechanismen: **myogen** (Bayliss) + **metabolisch** (Adenosin, CO₂, O₂) + **endothelial** (NO)

### 8.2 Organspezifische Autoregulation

| Organ | MAP-Bereich | Besonderheiten |
|---|---|---|
| **Gehirn (CBF)** | **50–150 mmHg** | CBF ~50 mL/100g/min; CO₂-Reaktivität **3%/mmHg** |
| **Niere (RBF)** | 80–180 mmHg | GFR autoreguliert; tubuloglomeruläres Feedback |
| **Koronargefäße** | 60–140 mmHg | Metabolisch dominiert (Adenosin); CFR 3–5 |
| Leber | gering | Dualversorgung (A. hepatica + V. portae) |
| Skelettmuskel | metabolisch | Ruhe: sympathoadrenerg vasokonstriktiv |

### 8.3 Störungen der Autoregulation

- **Chronische Hypertonie:** Kurve rechts verschoben → untere Grenze bei MAP ~70–80 mmHg
- **SHT:** gestörte zerebrale Autoregulation → **CPP-Ziel 60–70 mmHg** (ICP-gesteuert)
- **Sepsis:** globale Störung durch NO-Überproduktion → MAP ≥65 mmHg oft unzureichend
- **Volatile Anästhetika:** dosisabhängige Aufhebung (Isofluran > 1,5 MAC)

> [!tip] Klinik
> MAP <65 mmHg für >10 min intraoperativ → ↑ AKI- und MACE-Risiko.
> Karotisendarteriektomie: MAP +20 % über Ausgangswert perioperativ.
> **NIRS (zerebrale Oxymetrie):** Ziel rSO₂ >50 % bzw. >80 % des Ausgangswertes bei HLM.

---

## 9 Kreislaufregulation

### 9.1 Regulationsebenen

| Ebene | Zeitskala | Mechanismus |
|---|---|---|
| **Kurzfristig** (Sek.) | Baroreflex, Chemoreflexe | Sympathikus ↑/↓, Vagus ↑/↓ |
| **Mittelfristig** (Min.–Std.) | RAAS, ADH | Renin → Ang II → Aldosteron; Wasserretention |
| **Langfristig** (Tage–Wochen) | Renale Druckdiurese/-natriurese | Volumen- & NaCl-Bilanz → Langzeit-MAP |

### 9.2 Adrenerge Rezeptoren

| Rezeptor | Hauptwirkung | Agonist (Beispiel) |
|---|---|---|
| **α₁** | Vasokonstriktion | Noradrenalin, Phenylephrin |
| α₂ (präsynaptisch) | NA-Hemmung | Clonidin, Dexmedetomidin |
| **β₁** | HF ↑, Inotropie ↑, Renin ↑ | Dobutamin, Adrenalin |
| β₂ | Vasodilatation, Bronchodilatation | Adrenalin, Salbutamol |
| β₃ | neg. Inotropie (HI), Lipolyse | — |

### 9.3 RAAS & Neurohormone

| Substanz | Wirkung |
|---|---|
| **Angiotensin II** | Vasokonstriktion (AT1) + Aldosteron ↑ + ADH ↑ → Na⁺-Retention → Volumen ↑ |
| **Aldosteron** | Distales Tubulus: Na⁺ ↑, K⁺ ↓ → Volumen ↑ |
| **ADH (Vasopressin)** | V2: H₂O-Reabsorption (AQP2); V1a: Vasokonstriktion (splanchnisch) |
| **ANP / BNP** | Natriurese, Diurese, Vasodilatation, RAAS-Hemmung |
| **Endothelin-1** | Potenter Vasokonstriktor (ETA); ↑ bei pulm. Hypertonie → Bosentan |
| **NO** | eNOS → cGMP → Vasodilatation; HWZ <1 s |

### 9.4 Vasopressoren & Inotropika

| Substanz | Hauptrezeptor | Indikation |
|---|---|---|
| **Noradrenalin** | α₁ >> β₁ | Septischer Schock – **1. Wahl** |
| **Adrenalin** | β₁ = β₂ > α₁ | Anaphylaxie, Reanimation, refraktäre HI |
| **Vasopressin** | V1a | Katecholamin-refraktärer Schock (0,03 U/min) |
| **Dobutamin** | β₁ > β₂ | Kardiogener Schock, akute HI (add-on) |
| **Milrinon** | PDE-III-Hemmer → cAMP ↑ | HI + erhöhter PVR; nach Herzchirurgie |
| **Levosimendan** | Ca²⁺-Sensitizer + PDE-III | Akute dekompensierte HI; Inotropie ohne MVO₂ ↑↑ |
| **Phenylephrin** | α₁ (selektiv) | Spinalanästhesie-Hypotonie, HOCM |

### 9.5 Schockdifferenzierung

| Schockform | HZV | SVR | PCWP | ZVD |
|---|---|---|---|---|
| **Hypovolämisch** | ↓↓ | ↑ | ↓ | ↓ |
| **Kardiogen** | ↓↓ | ↑ | ↑↑ | ↑ |
| **Distributiv (Sepsis)** | ↑ (hyperdynam) | ↓↓ | ↓–N | ↓–N |
| **Obstruktiv (LE)** | ↓ | ↑ | N–↓ | ↑ |
| **Neurogen** | ↓ | ↓ | ↓ | ↓ (+ Bradykardie!) |

> [!tip] Klinik Intensiv – Septischer Schock
> Noradrenalin 1. Wahl (MAP-Ziel ≥65 mmHg); Vasopressin als 2nd-line (spart Noradrenalin).
> Bei kardialer Dysfunktion: Dobutamin oder Levosimendan.
> **Hydrokortison 200 mg/d** bei Vasopressor-refraktärem Schock (Surviving Sepsis Campaign).

---

## 10 Prüfungsrelevante Kernpunkte

> [!example] Never-forget-Liste
> - HZV = HF × SV; MAP = HZV × SVR; **CPP = DBP − LVEDP**
> - Frank-Starling: SV ∝ LVEDV (aufsteigender Schenkel); HI → flachere Kurve
> - **Koronarperfusion LV = diastolisch; Tachykardie = Feind der Koronarperfusion**
> - Baroreflex: BD ↑ → Vagus ↑ → HF ↓ (Karotissinus → NTS → Sympathikus ↓)
> - Zerebrale Autoregulation: MAP 50–150 mmHg; CO₂-Reaktivität **3 %/mmHg**
> - O₂-Extraktion Myokard **~75 %** in Ruhe → O₂-Mehrbedarf NUR über Fluss deckbar
> - Schockformen: HZV + SVR + PCWP unterscheiden kardiogen vs. distributiv vs. hypovolämisch
> - AP Phase 2 (Ca²⁺-Plateau): verlängert QTc → TdP-Risiko

| Prüfungsfrage | Kernantwort |
|---|---|
| Warum kein Tetanus am Herzen? | ARP ≈ Kontraktionsdauer → kein Re-Triggering |
| PEEP-Wirkung auf HZV? | Intrathorakaler Druck ↑ → venöser Rückstrom ↓ → Preload ↓ → HZV ↓ |
| Hypotonie bei Spinalanästhesie? | Sympathikolyse → Vasodilatation ± Bradykardie (Th1–Th5) |
| Phenylephrin statt Noradrenalin wann? | HOCM, Spinalanästhesie ohne Bradykardie (reine Afterload-Erhöhung) |
| Zerebrale Reaktion auf Hypokapnie? | PaCO₂ ↓ → CBF ↓ (Vasokonstriktion); Ziel PaCO₂ 35–40 mmHg |
| Volumenresponsivität? | PLR + ΔSV ≥10 % oder PPV/SVV >13 % (kontrolliert beatmet) |
| Levosimendan-Mechanismus? | Ca²⁺-Sensitizer am Troponin C → Inotropie ohne MVO₂ ↑↑ |

---

