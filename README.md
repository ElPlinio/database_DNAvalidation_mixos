# Sample Database — CBF2023-2024-1480

Field collection and moist chamber culture data for the project:
**Amoebozoa–bacteria relationship through metagenomic analysis of the myxomycete plasmodium microbiome**
SECIHTI Ciencia Básica y de Frontera 2023-2024 (CBF2023-2024-1480)
Laboratorio de Interacciones Bióticas, Universidad Autónoma de Tlaxcala, Mexico.

---

## Files

| File | Description |
|------|-------------|
| `juan_2022_LaMalinche_moist_chambers.csv` | Moist chamber review data (J.P. Molina-Viramontes, 2022). La Malinche National Park. |
| `stephanie_2025_sampling_points.csv` | GPS coordinates and substrate for the 12 collection points (Sept 3, 2025). |
| `stephanie_2025_moist_chambers.csv` | Moist chambers with pH measurements (seeded Sept 9, 2025; pH measured Sept 10, 2025). |
| `Sample_Database_CBF2023-2024-1480` | Data summarized in excel format |
---

## Collection Sites

### Juan 2022 — La Malinche National Park
- **Location:** La Malinche National Park, Tlaxcala/Puebla, Mexico
- **Reference:** Molina-Viramontes JP, Gómez-Acata ES, Hereira-Pacheco S, Estrada-Torres A, Navarro-Noya YE. (2025). Comparison of Methods to Characterize the Microbiota of Myxomycete Plasmodia. *Journal of Eukaryotic Microbiology*, 73, e70058. https://doi.org/10.1111/jeu.70058
- **Substrates:** Litter

### Stephanie 2025 — 12 sampling points
- **Collection date:** September 3, 2025
- **Location:** Tlaxcala, Mexico
- **Seeding date:** September 9, 2025
- **Substrates:** Nopal, Maguey, Agave, Biznaga, Naturopatia
- **3 replicates per point (R1, R2, R3)**

---

## Column Descriptions

### juan_2022_LaMalinche_moist_chambers.csv
| Column | Description |
|--------|-------------|
| `#` | Sample number |
| `prefix` | Sample prefix code |
| `degradation_level` | Substrate degradation level (High / Medium / Low) |
| `tree_number` | Tree/substrate identifier |
| `pH` | Initial pH of substrate water |
| `latitude_N` | GPS latitude (decimal degrees N) |
| `longitude_W` | GPS longitude (decimal degrees W, negative) |
| `substrate` | Substrate type |
| `collection_site` | Collection site name |
| `collection_date` | Date of collection |
| `coordinates_source` | Source of coordinates |

### stephanie_2025_sampling_points.csv
| Column | Description |
|--------|-------------|
| `point_id` | Point identifier (P1–P12) |
| `substrate` | Substrate type |
| `latitude_N` | GPS latitude (decimal degrees N) |
| `longitude_W` | GPS longitude (decimal degrees W, negative) |
| `collection_date` | Date of substrate collection |
| `moist_chamber_samples` | Associated moist chamber sample IDs |

### stephanie_2025_moist_chambers.csv
| Column | Description |
|--------|-------------|
| `#` | Sequential number |
| `sample_id` | Sample identifier (e.g. P1R1) |
| `point_id` | Collection point (P1–P12) |
| `replicate` | Replicate (R1, R2, R3) |
| `substrate` | Substrate type |
| `latitude_N` | GPS latitude (decimal degrees N) |
| `longitude_W` | GPS longitude (decimal degrees W, negative) |
| `pH_Sept10_2025` | pH measured on September 10, 2025 |
| `seeding_date` | Date moist chambers were set up |
| `pH_measurement_date` | Date pH was measured |

---

## License
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
