# mux-cli

CLI for library management coming with the following plugins (some might not be available yet):

Plugin name | Description
------------|----------------
Import | Crawls directory to find new files which then get imported into the database
Chromaprint | Calculates an acoustic fingerprint using the [AcoustID Chromaprint Project](https://github.com/acoustid/chromaprint)
AcoustID | Fetches MBIDs from the [AcoustID](https://acoustid.org/) web API with the generated Chromaprint fingerprint
MusicBrainz | Fetches meta data from the [MusicBrainz](https://musicbrainz.org/) web API for the fetched MBIDs of the AcoustID web API call
ExistanceChecker | Checkes if the indexed files in the database still exist physically on drive
... | ... (more will follow, ideas are welcome)
