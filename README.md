# TopoNigeria

**An open gazetteer of Nigerian place names in correct, tone-marked spelling with audio pronunciation. Pilot: South-West Yoruba.**

TopoNigeria (formally *Toponyms of Nigeria*, "ToN") records Nigerian place names the way they are actually written and spoken.

> **Status: early stage.** The project is being set up. There is no dataset yet, and all partners listed below are proposed and still to be confirmed.

## Why this exists

Nigeria's main place-name lists (OSGOF/NGSA, INEC ward data, GRID3, OCHA P-codes) record names in anglicised, tone-stripped spelling. Yorùbá is a tonal language. Once the tone marks and under-dots are lost, a name's pronunciation, and often its meaning, go with them, and different places can end up looking identical on the page.

That gap affects cultural preservation, education, geocoding and map labelling, and speech and language technology, where good training data for Nigerian languages is scarce. As far as we know, no open, tone-correct, audio-backed gazetteer of Nigerian place names exists today.

## What we are building

For each official place name, TopoNigeria will record:

| Field | Description |
|---|---|
| Official name | As given by the authoritative source |
| Administrative code | e.g. OCHA P-code |
| Standard spelling | Correct standard-language form |
| Tone-marked form | Tone marks and under-dots, for tonal languages (Yorùbá, Igbo) |
| Source | Where the name came from, so every entry is traceable |
| Audio | Link to a recorded pronunciation |

The method is meant to be replicable: **tone-marking** for tonal languages, and **correct spelling plus audio** for the rest.

## Scope

We are keeping the scope deliberately narrow and proving the method on one region first.

- **Phase 1 (pilot):** South-West Yorùbá States and Local Government Areas (about 140 LGAs): Lagos, Ogun, Oyo, Osun, Ondo and Ekiti, plus the Yorùbá-speaking parts of Kwara and Kogi. Text and tone-marking.
- **Phase 2:** Audio pronunciation for the Phase 1 names.
- **Phase 3:** Wards within the pilot states.
- **Phase 4:** Other states and languages.

Covering every state, language and ward at once is out of scope for the pilot.

## Approach

1. **Authoritative base data:** OSGOF/NGSA, INEC, GRID3 and OCHA/HDX P-codes, so names and codes are not invented.
2. **One orthography standard:** standard Yorùbá orthography with tone marks and under-dots, with written rules for dialect variants and contested names.
3. **Tiered review:** native speakers enter names, a linguist reviews them, and a reconciliation step settles disputes. Every name is traceable to its source.
4. **Audio through open platforms:** Mozilla Common Voice and Wikimedia Lingua Libre, with consent and licensing captured at recording.
5. **Reuse:** the content feeds Yorubadico, the Yorùbá dictionary platform, and is archived on Zenodo with a citable DOI.

## Planned outputs

- An open dataset of place names, archived on Zenodo with a DOI
- Pronunciation recordings
- A short dataset paper
- New content for Yorubadico and a public contributors page

## People

- **Project Lead:** Sodiq Lawal (MSc Computational Linguistics, University of Ibadan)
- **Founder and steward:** leads from the background and holds the dataset in trust for the project

Further advisors and partners are being approached. Nothing is confirmed until it appears here.

## Contributing

Contributions are welcome, especially from native Yorùbá speakers, linguists, and people with GIS or data skills.

- Open an [issue](https://github.com/Otomisin/toponigeria/issues) to report a wrong name, suggest a source, or offer to help.
- Contributors will sign a short Contributor Licence Agreement (CLA) so that names, text and recordings can be released openly. Full contribution guidelines and the CLA will be added before the first data is accepted.
- Contributors are credited by default, on a public contributors page and on each audio clip they record.

## Licensing

TopoNigeria is **fully open and non-commercial**. There is no paid or gated tier.

- **Data:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), including names, codes, tone marks and audio. Please attribute TopoNigeria when you reuse it.
- **Code:** MIT or Apache-2.0 (to be fixed when the first code is added).

Place names are facts and cannot be owned. The compiled dataset is held by the project, with the founder as steward.

## Funding

The project is volunteer-led and seeks grant funding (Lacuna Fund is the lead target) alongside in-kind support from open platforms. Donations are welcome as a top-up; an Open Collective page is planned.

## Contact

For now, please use [GitHub issues](https://github.com/Otomisin/toponigeria/issues).
