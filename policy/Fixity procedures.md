## Fixity procedures

#### Policy Statement

$institution are committed to maintaining the integrity of objects in its care. This includes creating checksums for all archival format objects -- plus associated datastreams -- ingested into the repository, and regular fixity checking of those objects.

#### Implementation

At the time of ingest an MD5 checksum value is calculated for the archival format object, and is stored along the object in the repository.

Daily, a set number of  files in the repository will have their current checksum calculated (using a single checksum) and compared to this stored value, which is expected to match. In cases where the calculated and stored values do not match, this is reported to the repository manager.

