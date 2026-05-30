# Design Checklist — General Site-to-System Workflow

_Last updated: 2026-05-29_

A **general engineering workflow** for taking a property from raw site to a
chosen, sized on-site wastewater system. This is study scaffolding, **not** a
permit procedure. Every numeric value, setback, loading rate, and acceptance
criterion is a **jurisdiction-specific legal requirement** — pull each one from
the Authority Having Jurisdiction's governing document (see
`provincial_overview.md`). Where a step depends on such a value, it says
**[per AHJ]**.

---

## Step 0 — Establish jurisdiction and scope
- [ ] Identify the **AHJ** and the **governing instrument** for the property's
      jurisdiction (province/territory, and the specific health authority,
      municipality, or building authority).
- [ ] Confirm the property's **design flow** is within the on-site regime's cap
      **[per AHJ]** (above the cap → different regulation).
- [ ] Confirm who is **legally permitted** to design/install here (certified
      practitioner requirement) **[per AHJ]**.

## Step 1 — Site evaluation
- [ ] Map the property: dwelling/structures, **well(s)**, surface water,
      property lines, slopes, drainage, easements.
- [ ] Record all features that drive **separation distances**.
- [ ] Note slope and landscape position (affects mounding, runoff, system type).

## Step 2 — Soil investigation
- [ ] Dig/bore test pits to expose the **soil profile** to the required depth
      **[per AHJ]**.
- [ ] Log **soil texture** and **structure** by horizon.
- [ ] Identify the **restrictive (limiting) layer** depth.
- [ ] Identify the **seasonal high water table** (look for redoximorphic
      mottling), not just the day-of water level.
- [ ] Determine the soil's **loading rate** using the AHJ-accepted method —
      **soil morphology/texture** and/or **percolation test** **[per AHJ]**.

## Step 3 — Vertical separation check
- [ ] Confirm sufficient depth of suitable unsaturated soil between the planned
      dispersal field and the restrictive layer / seasonal high water table
      meets the minimum **vertical separation [per AHJ]**.
- [ ] If native vertical separation is insufficient → an in-ground field is out;
      consider **at-grade**, **mound**, or **advanced treatment** to compensate.

## Step 4 — Design flow (sizing basis)
- [ ] Determine **design daily flow** from the AHJ method — typically bedroom
      count (sometimes fixtures/occupants) **[per AHJ]**.
- [ ] Apply any **peaking / safety factors** the AHJ requires **[per AHJ]**.

## Step 5 — Treatment level selection
- [ ] Decide the **treatment level** needed before dispersal:
  - **Primary** (septic tank) where soil + separation + setbacks all allow it.
  - **Secondary** (sand filter / ATU) where effluent quality must improve to fit
    the site (tight soils, reduced separation, sensitive receptor).
  - **Tertiary** (nutrient removal / disinfection) where the receiving
    environment is sensitive (near aquifer or surface water) **[per AHJ]**.

## Step 6 — Primary treatment sizing
- [ ] Size the **septic tank** working capacity for the design flow **[per
      AHJ]**.
- [ ] Specify an **effluent filter** and (if needed) a **dosing/pump chamber**.

## Step 7 — Dispersal field design
- [ ] Select dispersal type (trench / bed / at-grade / mound / sand filter /
      drip) based on soil, separation, slope, and treatment level.
- [ ] Size the **infiltrative area** from design flow ÷ **loading rate** **[per
      AHJ]**.
- [ ] Check **linear loading rate** / mounding constraints on sloping or
      layered sites **[per AHJ]**.
- [ ] Choose **distribution method** — gravity (with d-box) vs. **pressure
      distribution** (dosed laterals); pressure is usually required for mounds,
      sand filters, and large/level fields.
- [ ] Lay out laterals/trenches: spacing, length, and reserve/replacement area
      **[per AHJ]**.

## Step 8 — Separation distances & siting
- [ ] Apply all required **setbacks** — from wells, surface water, property
      lines, buildings, cut banks/slopes **[per AHJ]**.
- [ ] Subtract setback **exclusion areas**; confirm the dispersal field fits in
      what remains.
- [ ] Confirm a **reserve area** for future replacement if required **[per
      AHJ]**.

## Step 9 — Documentation & permitting
- [ ] Compile the site evaluation, soil logs, calculations, and a scaled site
      plan.
- [ ] Show **provenance** for every value: which section/table of the governing
      document produced it.
- [ ] Submit the application/registration in the form the AHJ requires **[per
      AHJ]**.

## Step 10 — Install, inspect, record
- [ ] Build to the approved design; capture **inspection hold points** **[per
      AHJ]**.
- [ ] Record **as-built** locations and elevations.
- [ ] Provide the owner with operation & maintenance guidance (pump-out
      intervals, filter cleaning, what not to flush, dosing/alarm checks).

---

### Selection cheat-sheet (engineering logic, confirm specifics per AHJ)

| Site condition | Typical implication |
|---|---|
| Deep, well-drained, permeable soil; ample separation | Conventional septic tank + gravity trench may suffice |
| Tight (clayey) or very slow soil | Larger field / pressure distribution / secondary treatment |
| Shallow restrictive layer or high water table | At-grade or **mound**; in-ground field likely not allowed |
| Small lot / many setback exclusions | Higher treatment level to shrink field or reduce setbacks |
| Near a well, lake, or stream | Setbacks dominate; possibly tertiary treatment / nutrient removal |
| Permafrost / very short season (North) | Holding tank + trucked service often the practical option |

> Reminder: this table encodes **engineering practice**. The thresholds that turn
> each row into a requirement are **legal rules** — always read them from the
> governing document for the jurisdiction.
