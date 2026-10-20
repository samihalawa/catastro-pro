# Detailed source-specific workflow


1. Ask for a cadastral reference only when it is not already supplied or available in the user's authorized documents. Do not ask for owner identity, tax number, certificate, account or password. A street address is not a verified cadastral reference; resolve ambiguity through the official map before attaching facts to a property.
2. Use `catastro_property` for the public descriptive record. Show reference, source address, use, built area, parcel area where available, construction year, property/parcel distinction and official map link. Preserve units and distinguish built area from usable area. A 14-character parcel reference can cover multiple properties; do not silently pick one unit.
3. Use `catastro_coordinates` only for a reference point. Inspect the CRS and labelled coordinates before plotting. A reference point is not a surveyed boundary. Do not swap axes, infer exact boundaries or claim centimetre accuracy.
4. Explicitly distinguish Catastro from Registro de la Propiedad, urban planning, occupancy licences and physical measurements. Public descriptions do not establish ownership, title, legal habitable status, planning compliance, protected cadastral values or market value. Navarra and the Basque Country require their separate systems; do not fabricate national coverage.
5. Return the factual sheet plus targeted official checks appropriate to the user's question. Do not reveal owner identities, protected valuations or use credentials to expand this public-data product.

## Output

Reference and property/parcel distinction; public descriptive fields with units; official map; retrieval date; uncertainty and separate title/planning checks.

