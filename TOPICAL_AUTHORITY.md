# Topical Authority — kapal.berat.id

## Role and boundary

`kapal.berat.id` should become an Indonesian decision and learning hub for heavy cargo vessels, cargo-carrier systems, towing, heavy marine logistics, and the operational decisions that connect a cargo requirement to a safe vessel and voyage plan.

The repository proves an existing commercial/editorial emphasis on barge carriers, chemical tankers, coal carriers, container ships, vehicle carriers, livestock carriers, LNG/LPG carriers, molten-metal carriers, Ro-Ro vessels, oil tankers, barges, and tugboats. It does **not** prove that the site owns vessels, is a licensed ship operator, classification society, naval-architecture practice, port authority, insurer, or legal adviser. Educational pages may explain how those specialists work, but vessel-specific stability, lifting, towing, dangerous-goods, statutory, insurance, and emergency decisions require current documents and qualified review.

Geography is Indonesia, including archipelagic logistics, tropical humidity, heavy rainfall, coastal corrosion, shallow or constrained ports, and inter-island supply chains. Geographic pages are not an authority strategy: a local page is justified only by real port limits, route conditions, regulations, infrastructure, or documented cases—not a swapped city name.

Commercial service, quote, fleet/capability, availability, and contact intent must remain on clearly identified commercial routes. Neutral knowledge articles must not imply fleet ownership, guaranteed capacity, compliance, price, sailing time, or service availability.

## Evidence audited

- Canonical source audited: `cfpages-evelinaquinta/Kapal.Berat.id`, branch `main`, at `0895c93` before this documentation commit.
- Repository form: static WordPress/Elementor export; no application package or content-source framework is tracked.
- Git tree: 7,524 tracked files, including 6,477 HTML files and 52 XML files.
- Top level: 6,357 HTML route files. Filename analysis identifies one homepage, 13 generic vessel/cargo pages, and 6,343 location-swapped variants.
- Twelve template families contain 489 files each (one generic plus 488 locations): barge carrier, chemical tanker, cargo ship, vehicle carrier, livestock carrier, LNG carrier, molten-metal carrier, LPG carrier, Ro-Ro, oil tanker, barge, and tugboat.
- The coal-carrier family contains 488 files (one generic plus 487 locations).
- Thirteen category hubs are tracked: chemical tanker, barge carrier, coal carrier, container ship, vehicle carrier, livestock carrier, LNG, molten-metal carrier, LPG carrier, Ro-Ro vessel, oil tanker, barge, and tugboat.
- Category archives add 26 pagination pages and 13 feed files. `/berita/` has 31 index/pagination pages; the author archive has 31 index/pagination pages.
- Fifteen direct semantic hub directories have an `index.html`: barge carrier, chemical tanker, coal carrier, cargo, vehicle, container, livestock, LNG, molten metal, LPG, material, oil, Ro-Ro, barge, and tugboat.
- Three named sitemap files exist. `sitemap.xml` and `sitemap_index.xml` point to the same Git blob (3,652 bytes); `sitemap-complete.xml` is 930,561 bytes.
- Recent content-export commits are dated October-November 2024. Recency-sensitive claims must be researched again before publication.
- No repository-local `AGENTS.md` is tracked. The only root Markdown evidence is `README.md`.
- The partial clone had complete tree metadata but not HTML/XML blob bodies. A platform external-action limit prevented blob retrieval. Therefore sitemap URL counts, headings, body quality, canonical tags, structured data, and exact service claims remain explicit pre-publication verification gates; they are not guessed here.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/index.html` | Homepage; exact body unavailable | keep | Commercial/editorial gateway | Inspect title, H1, claims, navigation, canonical, and live response |
| `/<vessel-family>.html` (13 generic files) | Generic template landing pages | manual review | One canonical semantic hub per vessel/cargo intent | Compare each with directory and category versions; retain the URL with useful history |
| `/<vessel-family>-<location>.html` (6,343 files) | Mass location-swapped footprint; not independent editorial coverage | manual review | Canonical vessel hub or a genuinely evidence-rich port/route page | Export sitemap/GSC/backlinks/conversions; sample bodies; test uniqueness and local usefulness before noindex/merge/redirect |
| `/barge-carrier/`, `/chemical-tanker/`, `/coal-carrier/`, `/kargo/`, `/kendaraan/`, `/kontainer/`, `/livestock/`, `/lng/`, `/logam-cair/`, `/lpg/`, `/material/`, `/minyak/`, `/ro-ro/`, `/tongkang/`, `/tugboat/` | Fifteen semantic directory hubs, with likely overlap against root files and categories | manual review | One owner route for each main neutral or commercial intent | Compare content, search history, internal links, and commercial role |
| `/category/<type>/` | Thirteen category archives competing with semantic hubs | manual review | Archive for discovery, or merge/canonicalize to the chosen hub | Inspect unique copy, indexability, canonical tags, pagination, and traffic |
| `/category/<type>/page/<n>/` | 26 paginated category pages | canonicalize | Parent category archive | Confirm crawl/index behavior and pagination links |
| `/berita/page/<n>/` | 31 news/archive pages; may expose thin pagination | keep | News archive | Inspect article count, chronology, orphaning, canonical/pagination signals |
| `/author/syamsul-alam/page/<n>/` | 31 author archive pages likely duplicating news/category listings | noindex | Author profile plus canonical article URLs | Verify whether the author archive has standalone user value |
| `sitemap.xml` and `sitemap_index.xml` | Exact same Git object despite different names | merge | One valid sitemap index plus child maps | Parse both, validate XML type, live status, URL count, lastmod accuracy, and robots declaration |
| `sitemap-complete.xml` | Very large sitemap file; contents unavailable | manual review | Valid child sitemap set split by content type if limits or maintenance require | Parse, deduplicate, classify URLs, validate canonical/indexable 200 responses |
| `/feed/`, `/comments/feed/`, category/author feeds | Machine feeds, not editorial authority pages | noindex | Feed endpoints | Verify headers, canonicals, and whether feeds are used |
| Static WordPress plugin/theme assets | Large exported runtime footprint | keep | Current static rendering | Run dependency/reference audit before removing any asset |

The dominant risk is not missing keyword permutations; it is confusing 6,343 location-template URLs and several parallel hub/archive routes with real expertise. Consolidation must use live/GSC/backlink/conversion evidence before any irreversible URL action.

## Coverage matrix

| Completeness lens | Topic owner(s) and status |
|---|---|
| Definition, vocabulary, history, measurement | KPL-01, KPL-02, KPL-09 |
| Taxonomy and variants | KPL-02, KPL-04, KPL-05, KPL-06, KPL-07, KPL-08 |
| Anatomy, components, materials, mechanisms | KPL-03, KPL-10, KPL-11 |
| Need recognition, survey, requirements, selection | KPL-02, KPL-09, KPL-18 |
| Budget, procurement, chartering, contracts | KPL-09, KPL-17, KPL-18 |
| Preparation, loading, installation-like marine work | KPL-10, KPL-11, KPL-12 |
| Commissioning, handover, operation | KPL-09, KPL-12, KPL-13 |
| Inspection, maintenance, troubleshooting, repair | KPL-14, KPL-15 |
| Upgrade, replacement, decommissioning | KPL-15, KPL-16, KPL-18 |
| Stakeholders and user paths | KPL-09, KPL-12, KPL-13, KPL-17, KPL-18 |
| Site/port type, geography, climate | KPL-03, KPL-12, KPL-13, KPL-16 |
| Scale, performance, newbuild/retrofit | KPL-02, KPL-09, KPL-10, KPL-15 |
| DIY versus professional | KPL-09 through KPL-18; all vessel-specific engineering and statutory decisions have stop conditions |
| Safety, health, emergency, failure modes | KPL-10, KPL-11, KPL-13, KPL-14, KPL-15 |
| Standards, regulation, class, insurance | KPL-09, KPL-14, KPL-16, KPL-17 |
| Environmental impact | KPL-03, KPL-13, KPL-16, KPL-18 |
| Evidence quality, myths, unsafe advice | KPL-01, KPL-09, KPL-10, KPL-14, KPL-17 |
| Informational, comparative, diagnostic, calculation, visual, commercial support | All topics; formats and boundaries are assigned per brief in `ARTICLE_CATALOG.md` |
| News/trends | KPL-16 and KPL-17 only when a material regulatory, technology, or environmental change can be maintained |
| Local pages | N/A as a generic template. KPL-12/KPL-13 can support a port or route case only with real constraints and primary evidence |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KPL-01 | Heavy-vessel fundamentals and vocabulary | Understand what “kapal berat” means and speak accurately with marine specialists | vessel versus ship; DWT/GT/NT/displacement; draft/freeboard/beam/LOA; cargo versus carrier terms; deadweight versus payload; Indonesian/English vocabulary; history of cargo specialization; common myths | Glossary, annotated diagram, sourced explanation, terminology table | Defines concepts only; vessel-family selection belongs to KPL-02 and vessel-specific calculations to KPL-09/KPL-10 | 6 |
| KPL-02 | Vessel classes and cargo-to-vessel selection | Narrow a cargo requirement to plausible vessel classes without pretending to complete naval architecture | cargo form and hazard; self-propelled versus towed; liner/tramp/project movement; class notation; capacity and access; sea/river/coastal use; newbuild/retrofit; decision red flags | Decision tree, comparison matrix, expert review, current class references | Chooses a class conceptually; individual vessel families belong to KPL-04–KPL-08 and final suitability to KPL-09 | 6 |
| KPL-03 | Vessel anatomy, construction, materials, and corrosion | Recognize major ship systems and how marine exposure affects them | hull structure; decks/holds/tanks; propulsion/steering; electrical/auxiliary systems; steel/coatings/cathodic protection; fatigue; watertight integrity; tropical/coastal corrosion | Annotated diagrams, material table, original/permissioned photos, naval-architect review | Explains physical systems; maintenance plans belong to KPL-15 and stability effects to KPL-10 | 6 |
| KPL-04 | Barges and barge carriers | Decide when a barge, deck barge, hopper barge, or barge-carrier system fits a movement | barge types; payload/deck strength; river/coastal limits; ballast; push/tow interfaces; barge carrier/LASH concept; loading/unloading; grounding and weather risks | Vessel-family comparison, diagrams, loading examples, expert review | Barge selection only; towing operation belongs to KPL-05 and heavy lifts to KPL-11 | 6 |
| KPL-05 | Tugboats, towing, pushing, and mooring | Understand how towage systems are selected, prepared, and monitored | harbour versus ocean tug; bollard pull concept; towline/bridle; towing resistance; escort/push operations; weather limits; tow plan; mooring interfaces; emergency tow | Diagrams, decision checklist, sourced calculations, master/marine-engineer review | Towage and mooring only; cargo stability belongs to KPL-10 and port workflow to KPL-12 | 6 |
| KPL-06 | Dry cargo carriers | Match coal, bulk, general, containerized, and multipurpose cargo to dry-cargo systems | bulk versus general cargo; coal hazards; holds/hatches; container cells/lashing; reefer interfaces; moisture/contamination; loading rates; segregation; cargo residues | Comparison tables, cargo-flow diagrams, cargo-specialist review | Dry cargo only; liquid/gas cargo belongs to KPL-08 and heavy project cargo to KPL-11 | 6 |
| KPL-07 | Ro-Ro, vehicle, livestock, and special carriers | Understand carriers whose cargo has mobility, ventilation, welfare, or unusual handling needs | PCC/PCTC/MPCC; Ro-Ro ramps; vehicle securing; deck fire risks; livestock ventilation/welfare; reefer cargo; hazardous/special materials; cargo compatibility | Deck diagrams, checklists, current code/source review, veterinary review where relevant | Specialized non-tank carriers; container/general cargo belongs to KPL-06 and tank cargo to KPL-08 | 6 |
| KPL-08 | Oil, chemical, LNG, LPG, and hazardous-material carriers | Distinguish tank-carrier systems and know when specialist engineering is mandatory | oil/chemical/gas carrier differences; tank materials/coatings; containment; cargo compatibility; temperature/pressure; inerting/ventilation concepts; transfer systems; spill/fire/toxic exposure | System diagrams, compatibility decision tree, primary codes, chemical/gas specialist review | High-level tank-carrier education only; no cargo-specific transfer procedure, compatibility approval, or emergency command | 6 |
| KPL-09 | Requirements, survey, specification, and vessel acceptance | Build a complete information pack before chartering, buying, or accepting a vessel | cargo data; route/port limits; vessel particulars; certificates/class/status; condition survey; hold/tank/deck suitability; documentation gaps; acceptance tests; red flags | Requirements template, inspection checklist, document matrix, surveyor review | Requirement and acceptance ownership; pricing/contracts belong to KPL-18 and statutory interpretation to KPL-17 | 6 |
| KPL-10 | Capacity, loading, draft, trim, stability, ballast, and securing | Understand the linked calculations and recognize when a qualified loading/stability plan is required | DWT versus usable payload; draft/under-keel clearance; weight distribution; center of gravity; intact/damage stability concepts; free-surface effect; ballast; trim/list; lashing/sea fastening | Worked conceptual examples, diagrams, checklists, naval-architect/master review | No vessel-specific approval or executable loading plan; heavy-lift rigging belongs to KPL-11 | 6 |
| KPL-11 | Heavy lift, project cargo, and marine lifting | Plan the information and interfaces needed for outsized or high-consequence cargo | lift-on/lift-off versus Ro-Ro/float-on; crane capacity/radius; lifting points; rigging; spreader beams; deck strength; grillage; sea fastening; tandem lifts; weather window; method statement | Lift-plan anatomy, load-path diagram, checklist, lifting engineer/naval-architect review | Educational planning only; no certified lift plan or rigging instruction; general stability belongs to KPL-10 | 6 |
| KPL-12 | Ports, terminals, loading, unloading, and marine interfaces | Map a cargo movement across shore, berth, vessel, and handover constraints | berth depth/length; tides; cranes/ramps/conveyors/pumps; staging; access roads; permits; stevedoring; interface meetings; cargo tally; contamination/damage control; handover | Process map, port-readiness checklist, RACI, real case evidence | Port interface only; voyage operation belongs to KPL-13 and commercial contract allocation to KPL-18 | 6 |
| KPL-13 | Voyage operations, route, weather, and navigation context | Understand operational constraints from departure through arrival | route survey; forecast/sea state; currents/tides; shallow water; archipelagic/coastal/river operations; fuel/endurance; watchkeeping context; communications; delays; arrival planning | Route-risk matrix, weather decision framework, master review, primary hydrographic/weather sources | General operational education; no voyage instruction or navigational advice for a live vessel | 6 |
| KPL-14 | Marine safety, human factors, and emergencies | Recognize critical hazards, preparedness needs, and stop-work/escalation conditions | collision/grounding; fire/explosion/toxic release; flooding; enclosed space; man overboard; towing/lifting failures; fatigue/communication; drills; emergency roles; incident preservation/reporting | Bow-tie diagrams, emergency checklist, primary safety sources, HSE/master review | Preparedness and recognition only; never replaces vessel SMS, emergency command, or authority instructions | 6 |
| KPL-15 | Inspection, maintenance, defects, repair, and lifecycle | Diagnose categories of deterioration and choose inspect/repair/replace/escalate paths | corrosion/cracking; coating failure; machinery symptoms; leaks; hatch/tank integrity; dry-docking; class/statutory survey interfaces; spares; repair verification; retrofit; lay-up/reactivation | Defect atlas, maintenance matrix, diagnostic tree, marine engineer/class review | Does not authorize repair or return to service; regulatory status belongs to KPL-17 | 6 |
| KPL-16 | Environment, emissions, energy, spills, and end-of-life | Evaluate environmental trade-offs across operation and retirement | fuel/efficiency; emissions/accounting concepts; ballast-water and biofouling; spills/waste; underwater noise; cargo loss; route efficiency; alternative propulsion claims; ship recycling; evidence boundaries | Lifecycle matrix, sourced comparison, primary environmental rules, specialist review | Environmental education only; current compliance interpretation belongs to KPL-17 | 6 |
| KPL-17 | Regulation, classification, certification, insurance, and claims | Know which institutions/documents govern a decision and when specialist advice is required | flag/coastal/port state roles; IMO instruments; Indonesian transport authority; BKI/class societies; SOLAS/MARPOL/load line/ISM/COLREG/CSS context; certificates; dangerous goods; insurance/survey/claims; incident records | Institution map, document checklist, current primary-source citations, maritime lawyer/class/insurer review | Explains pathways, not legal advice, class approval, certification, coverage opinion, or claims decision | 6 |
| KPL-18 | Chartering, buying, cost, vendor evaluation, and decommissioning | Compare commercial routes and protect decisions with technical and contractual evidence | charter types; voyage/time/bareboat concepts; freight/cost components; quote normalization; capability evidence; broker/vendor checks; availability/lead time; contract interfaces; handover; resale/recycling | Cost model, bid-comparison sheet, due-diligence checklist, legal/accounting/expert review | Commercial decision support only; no live price guarantee, valuation, tax, legal, or investment advice | 6 |

## Related-domain opportunities

- `alat.berat.id` may independently explain shore cranes, transporters, loaders, and heavy equipment. `kapal.berat.id` should own the shipboard and marine-interface viewpoint; cross-domain overlap is an opportunity, not cannibalization.
- Root `berat.id` and other meaningful subdomains may explain broader heavy-industry logistics. Link only where the user benefits and avoid implying common fleet ownership or one legal operator.
- Construction, port, safety, fire-safety, and material domains may contribute expert interviews or source evidence. Each domain remains free to cover the same entity from its own perspective.
- A future port/route case should link to the relevant owned local or industry property only when the case has real measurements, constraints, and attribution.

## Consolidation plan

1. Export and parse all three sitemaps; classify every URL as homepage, semantic hub, commercial page, editorial article, category/archive, feed, location template, media, or error.
2. Join the URL list to GSC clicks/impressions, external links, conversions, live status, canonical, robots, and content hash before deciding URL fate.
3. For each of the 13 vessel families, compare the root `.html`, semantic directory, and category archive. Select one neutral intent owner and one commercial owner only when the intents genuinely differ.
4. Sample location pages across multiple templates. Keep a local route only where port/route/service facts materially differ and are maintainable; otherwise test noindex/merge/redirect in bounded batches.
5. Preserve useful historical URLs. Do not mass-delete 6,343 pages from filename evidence alone.
6. Replace the duplicate sitemap/index arrangement with a validated sitemap index and content-type child maps; exclude noncanonical/noindex/error URLs.
7. Rebuild internal navigation around the 18 topic hubs and a small first publication wave before adding more articles.

## Internal-link architecture

- Central hub: `panduan-kapal-berat-dan-logistik-marin` links to all 18 topic hubs and the verified commercial capability route.
- Vessel-selection path: KPL-01 → KPL-02 → the relevant KPL-04–KPL-08 family → KPL-09 acceptance → KPL-18 quote/contract.
- Project-cargo path: KPL-09 requirements → KPL-10 stability/securing → KPL-11 lift plan → KPL-12 port interface → KPL-13 voyage risk.
- Risk path: KPL-14 hazard recognition → KPL-15 defect/maintenance → KPL-17 statutory/class/insurance escalation.
- Environmental path: KPL-03 materials/corrosion → KPL-13 operating choices → KPL-16 lifecycle impacts → KPL-17 current obligations.
- Every child links to its topic hub; every hub links to all six children. Diagnostic pages link to prevention, inspection, repair, and replace/escalate decisions.
- Commercial routes receive contextual links only from KPL-09 and KPL-18 pages that help a reader prepare a legitimate enquiry.

## Evidence and editorial standards

- Cite current primary material from the Indonesian transport/maritime authority, IMO, BKI or the applicable classification society, port/harbour authority, hydrographic/weather authority, manufacturer manuals, and vessel-specific approved documents.
- Verify applicability and current edition at publication. Never invent clauses, thresholds, safe working loads, capacity, stability margins, weather limits, prices, sailing times, or certificate status.
- Stability/loading briefs require a naval architect or qualified master. Towing briefs require a qualified tug/towage specialist. Heavy-lift briefs require a lifting engineer plus naval-architecture review where vessel stability/deck strength is involved.
- Tanker/gas/chemical briefs require cargo-system and HSE review. Livestock briefs require current animal-welfare/veterinary evidence. Environmental and regulatory briefs require current specialist review.
- Diagrams must be original or properly licensed and labelled conceptual when not vessel-specific. Calculators must state inputs, assumptions, units, limits, and a professional stop condition.
- No invented fleet, case study, test, incident experience, customer, partner, project, quote, or result. A case study needs source documents, permission, dates, constraints, and measured outcomes.
- Indonesian terms should be paired with the accepted maritime English term where useful; synonyms belong in one owner page, not separate thin pages.
- High-consequence content must lead with limitations and escalation conditions, not place them in fine print.

## First bounded publication cluster

Wave 1 contains 12 assets:

1. KPL-01-01 glossary and measurement hub.
2. KPL-02-01 cargo-to-vessel decision tree.
3. KPL-03-01 annotated vessel anatomy.
4. KPL-04-01 barge-type selection guide.
5. KPL-05-01 tugboat-role comparison.
6. KPL-09-01 cargo requirements data sheet.
7. KPL-10-01 payload-versus-deadweight explanation.
8. KPL-11-01 heavy-project-cargo method map.
9. KPL-12-01 port-readiness checklist.
10. KPL-14-01 marine-operation hazard map.
11. KPL-16-01 environmental-impact lifecycle map.
12. KPL-17-01 regulator/class/flag/port institution map.

This cluster is coherent because it answers: what the terms mean, which vessel family may fit, what information must be supplied, how cargo/ship/port interfaces create risk, and which specialists or institutions must approve the high-consequence decisions. It also creates link destinations before any new commercial page is promoted.

Success signals: canonical/indexable publication; sitemap inclusion; impressions grouped by distinct intent; engagement with diagrams/checklists; movement from selection pages to the requirements sheet; qualified enquiries that include usable cargo/route data; and GSC checks for two planned pages competing on the same query. Ranking alone is not success.

## Definition of done

- All 18 topic hubs and 108 child briefs retain unique intent, boundary, evidence format, and valid internal relationships.
- The first wave passes subject-matter review and is published before later waves are released.
- All three existing sitemap files are parsed; canonical/indexable URL counts replace the current Git-tree proxy counts.
- Existing root, directory, and category routes have one documented intent owner per vessel family.
- The 6,343 location templates have evidence-based keep/noindex/merge/redirect decisions, tested in bounded batches with rollback records.
- Every published page has correct canonical, robots, sitemap, navigation, schema where appropriate, and no broken asset or internal-link path.
- Safety, stability, towing, lifting, dangerous-goods, environmental, legal, class, insurance, and cost claims pass their stated expert/current-source gates.
- Performance measurement connects search visibility to useful task completion and qualified commercial enquiries without inventing fleet capability.
