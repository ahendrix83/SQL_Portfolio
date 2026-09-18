Relational Database Architecture (Star Schema) <br>
To eliminate data redundancy and optimize query performance, this project transforms flat datasets into a normalized Star Schema. <br>
The architecture centers around a single master dimension table that acts as the source of truth for geographic data: <br>
**Parent Table (Dimension):** COUNTY_DIM holds the master records for all geographic regions, using the SPRS Texas State County Code Table, a standardized 3-digit county code as its **Primary Key (PK)**.  <br>
**Child Tables (Facts):** All three core datasets—REMOVALS_FACT, VICTIMS_FACT, and POP_FACT—serve as the fact tables.
