# Dimensional Model

## Module

Museum Collections Observatory

## Version

1.0

---

# Business Process

Annual collection of quantitative information about the collections of museums associated with ABPMIS.

Each survey represents a snapshot of the institution's collection for a specific reference year.

---

# Grain

Each record in the fact table represents the quantity of collection items of a specific collection type and support, belonging to one museum, for one reference year.

---

# Fact Table

## FACT_COLLECTION

### Foreign Keys

- Museum_Key
- Time_Key
- Collection_Type_Key
- Support_Key
- Confidence_Level_Key

### Measures

- Collection_Quantity
- Digitized_Quantity

---

# Dimensions

## DIM_MUSEUM

- Museum_Key
- Museum_ID
- Museum_Name
- Acronym
- City
- State
- Region
- Country
- Administrative_Sphere
- Institution_Type
- Year_Founded
- ABPMIS_Associate
- IBRAM_Registered
- Tainacan_Catalog
- Storage_Conservation_Level
- Website

---

## DIM_COLLECTION_TYPE

- Photography
- Video
- Audio
- Archival Documents
- Bibliographic Collection
- Objects
- Other

---

## DIM_SUPPORT

### Photography

- Paper
- Negative
- Slide
- Digital File
- Other

### Video

- Film Reel
- VHS
- Betacam
- DVD
- Blu-ray
- Digital File
- Other

### Audio

- Vinyl
- Audio Tape
- Cassette
- CD
- Digital File
- Other

### Archival Documents

- Paper
- Digital File
- Other

### Bibliographic Collection

- Paper
- Digital File
- Other

### Objects

- Physical Object
- Other

---

## DIM_TIME

- Time_Key
- Reference_Year
- Submission_Date

---

## DIM_CONFIDENCE_LEVEL

- Complete Inventory
- Partial Inventory
- Estimated
- Unknown
- Not Informed

---

# Business Rules

- Data collection is performed annually.
- Digitization is treated as an accessibility indicator.
- Museums may provide complete, partial or estimated values.
- Every quantitative value shall include a confidence level.
- Every classification dimension shall provide an "Other" category whenever applicable.
