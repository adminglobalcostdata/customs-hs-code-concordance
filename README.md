# HS Code Concordance - US, EU, Canada, Australia

[![Apify Actor](https://img.shields.io/badge/Apify-Actor-1f6feb)](https://apify.com/phonic_lily/customs-hs-code-concordance) ![Licence](https://img.shields.io/badge/licence-Mixed_per_jurisdiction_US_public_domain-blue) ![Records](https://img.shields.io/badge/records-5%2C612-green)

HS code concordance: one record per 6-digit HS code, with US, EU, Canada and Australia national tariff codes, descriptions and duty rates. Pay per record.

## What you get
- **5,612 records**, each carrying its own `license` and `attribution` fields, ready to republish with the required credit.
- A **100-record free sample** in this repository: [`sample.jsonl`](sample.jsonl) and [`sample.csv`](sample.csv) (opens as a table on GitHub).
- The **full dataset** as a filterable API (JSON, CSV, Excel), no scraping, no login: [HS Code Concordance - US, EU, Canada, Australia on Apify](https://apify.com/phonic_lily/customs-hs-code-concordance).

## One record
```json
{
  "hs6": "010229",
  "hs2": "01",
  "hs4": "0102",
  "jurisdictions": [
    "us",
    "eu",
    "ca",
    "au"
  ],
  "jurisdictions_count": 4,
  "us_codes": [
    {
      "code": "0102.29.20",
      "description": "Cows imported specially for dairy purposes",
      "general_rate": "Free"
    },
    {
      "code": "0102.29.40",
      "description": "Other",
      "general_rate": "1¢/kg"
    }
  ],
  "eu_codes": [
    {
      "code": "0102290000",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102290500",
      "description": null,
      "general_rate": "0.000 %"
    },
    {
      "code": "0102291000",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102291010",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102291020",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102291030",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102291040",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102291050",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102292100",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102292900",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102292910",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102292920",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102292930",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102292940",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102292950",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102294100",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102294900",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102294910",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102294920",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102294930",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102294940",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102294950",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295100",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102295110",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295190",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295900",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102295911",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295919",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295921",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295929",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295931",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295939",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295991",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102295999",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102296100",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102296900",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102296910",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102296920",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102296930",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102299100",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102299110",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102299190",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102299900",
      "description": null,
      "general_rate": "10.200 % + 93.100 EUR DTN"
    },
    {
      "code": "0102299921",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102299929",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102299991",
      "description": null,
      "general_rate": null
    },
    {
      "code": "0102299999",
      "description": null,
      "general_rate": null
    }
  ],
  "ca_codes": [
    {
      "code": "0102.29.00",
      "statistical_suffix": null,
      "description": "Live bovine animals. - Cattle: - Other",
      "general_rate": "Free"
    },
    {
      "code": "0102.29.00",
      "statistical_suffix": "10",
      "description": "Live bovine animals. - Cattle: - Other - Dairy",
      "general_rate": "Free"
    },
    {
      "code": "0102.29.00",
      "statistical_suffix": "90",
      "description": "Live bovine animals. - Cattle: - Other - Other",
      "general_rate": "Free"
    }
  ],
  "au_codes": [
    {
      "code": "0102.29.00",
      "statistical_code": "03",
      "description": "-- Other",
      "general_rate": "Free"
    }
  ],
  "uk_quota_codes": [
    {
      "code": "0102294100",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102294900",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102295100",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102295110",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102295900",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102295911",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102295921",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102295931",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102295991",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102296100",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102296900",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102299100",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102299110",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102299900",
      "quota_order_numbers": [
        "050146"
      ]
    },
    {
      "code": "0102299921",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    },
    {
      "code": "0102299991",
      "quota_order_numbers": [
        "050341",
        "050345",
        "050347"
      ]
    }
  ]
}
```

## Quick start
Python:
```python
from apify_client import ApifyClient
client = ApifyClient('<YOUR_APIFY_TOKEN>')
run = client.actor('phonic_lily/customs-hs-code-concordance').call(run_input={'maxResults': 10})
for item in client.dataset(run['defaultDatasetId']).iterate_items():
    print(item)
```
Or from the command line:
```bash
curl -X POST 'https://api.apify.com/v2/acts/phonic_lily~customs-hs-code-concordance/run-sync-get-dataset-items?token=<YOUR_APIFY_TOKEN>' \
  -H 'Content-Type: application/json' -d '{"maxResults": 10}'
```
Pricing is pay-per-record on Apify (see the Actor page); the sample here is free.

## Fields
| Field | Description |
|---|---|
| `hs6` | 6-digit Harmonized System code. |
| `hs2` | HS chapter (first 2 digits). |
| `hs4` | HS heading (first 4 digits). |
| `jurisdictions` | Jurisdictions with at least one national tariff line under this HS6: us, eu, ca, au. |
| `jurisdictions_count` | Number of jurisdictions present (1 to 4); the UK is not counted. |
| `us_codes` | US HTS lines: code, description, general_rate. Null when absent. |
| `eu_codes` | EU TARIC 10-digit codes: code, description (always null, not in the source), general_rate (third-country duty as published, with dates when several periods). Nu |
| `ca_codes` | Canada Customs Tariff items: code, statistical_suffix, description, general_rate (MFN). Null when absent. |
| `au_codes` | Australia Working Tariff codes: code, statistical_code, description, general_rate. Null when absent. |
| `uk_quota_codes` | Informational, not counted: UK commodity codes covered by a tariff quota under this HS6 (code, quota_order_numbers). Null when none. |

## Data, licence and attribution
One record per 6-digit Harmonized System (HS6) code, built by grouping the national tariff lines of four jurisdictions on their first six digits. A jurisdiction is present when at least one of its tariff lines starts with that HS6. National codes can differ by HS revision year, so a missing jurisdiction means no line in the embedded data, not proof that the code does not exist there.

Measured on this snapshot: 5,612 HS6 codes. By number of jurisdictions present (US, EU, Canada, Australia): 4 jurisdictions = 4,685 codes; 3 = 919; 2 = 8; 1 = 0. HS6 codes present per jurisdiction: US 5,612; Canada 5,612; EU 5,398; Australia 4,891.

Sources and licences:
- United States: HTS lines (code, description, general duty rate). USITC, public domain.
- European Union: TARIC 10-digit codes that carry at least one measure in the extract. DG TAXUD, CC BY 4.0 (Decision 2011/833/EU), changes made. The source gives NO description for a TARIC code, so the EU description is null. general_rate is the erga omnes third-country import duty as published (several dated periods are all listed); null when the extract holds no such duty for the code.
- Canada: Customs Tariff items with the statistical suffix and the MFN rate. CBSA, Reproduction of Federal Law Order SI/97-5; not an official version.
- Australia: Working Tariff (Schedule 3) codes with statistical code and rate. Australian Border Force, CC BY 3.0 Australia, changes made.
- United Kingdom: not a concordance jurisdiction here. The only UK code field available is the list of commodity codes covered by a tariff quota (HMRC, OGL v3.0), which is not the full nomenclature, so the UK is not counted in jurisdictions_count. Those codes are returned for information in uk_quota_codes (code and quota order numbers) when the HS6 has some.

There is no HS6-level description field: the sources only describe national lines, so each description stays with its own national code. Informational only; the official national tariffs prevail. Null means the source gives no value; it is never 0.

**Licence:** Mixed, per jurisdiction: US public domain (USITC); EU CC BY 4.0 (DG TAXUD); Canada Reproduction of Federal Law Order SI/97-5 (CBSA, unofficial copy); Australia CC BY 3.0 AU (ABF); UK quota codes OGL v3.0 (HMRC)

**Attribution:** Sources: United States International Trade Commission, HTS (public domain); European Commission DG TAXUD, TARIC (CC BY 4.0, Decision 2011/833/EU; changes made: restructured by HS6, third-country duty summarised); Canada Border Services Agency, Customs Tariff (Reproduction of Federal Law Order SI/97-5, not an official version); Australian Border Force, Working Tariff Schedule 3 (CC BY 3.0 Australia; changes made: restructured by HS6); UK quota codes: contains public sector information licensed under the Open Government Licence v3.0 (HM Revenue & Customs).

Snapshot date: 2026-07 (UK quotas fetched 2026-07-30). Empty values are `null`, never 0.

## Cite this dataset
GitHub's *Cite this repository* button reads [`CITATION.cff`](CITATION.cff).

## Feedback
Found an error or want a field added? Open an issue in this repository.
