# Arsitektur

## Diagram
```mermaid
flowchart LR
  A[Sumber data<br/>survei, BIM, sensor, sistem mitra] --> B[Ingest & ETL]
  B --> C[(Penyimpanan<br/>data & model)]
  C --> D[Layanan / API<br/>OGC, I3S, 3D Tiles]
  D --> E[Aplikasi DT<br/>web, dashboard, XR]
  E --> F[Pengguna & keputusan]
```

## Komponen
| Lapisan | Teknologi/platform | Catatan |
|---|---|---|
| Akuisisi | | |
| Ingest & ETL | | |
| Penyimpanan | | |
| Layanan/API | | |
| Aplikasi | | |
| Analitik/AI | | |

## Standar data
- CRS:
- Format 3D:
- Skema ID aset:
- Frekuensi pembaruan:

## Keputusan arsitektur
| # | Keputusan | Alasan | Tanggal |
|---|---|---|---|
| 1 | | | |
