# SQL

**Summary**: Notes on SQL query techniques, spatial/geospatial SQL, and database engines.
**Last updated**: 2026-08-25

---

- [Optimizing DuckDB Spatial Queries](https://www.geomermaids.com/cookbook/duckdb-spatial/): Compares PostGIS and DuckDB spatial join implementations (point-in-polygon containment, `ST_DWithin` distance queries, nearest-neighbor search) using DuckDB's `spatial` extension, R-tree indexing, and GeoParquet files. PostGIS uses indexed nested loops for small probe sets while DuckDB streams large tables through runtime R-trees, so each engine needs a different optimization strategy. Related: [[Data]]. Keywords: DuckDB, spatial SQL, PostGIS, R-tree indexing, GeoParquet, spatial joins.
