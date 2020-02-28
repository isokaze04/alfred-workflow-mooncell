# alfred-workflow-MooncellSearch
Alfred workflow to search mooncell (https://fgo.wiki)

## Features:
- Search for Servant
- Search for Craft Essence
- Data Caching

Variables *CE_UPDATE_INTERVAL* and *SV_UPDATE_INTERVAL* are intervals (in seconds) for updating local data. 

Press Enter to open associated URL.
CMD+C to copy. Also, press "OPT" or "CMD" on a CE result to reveal more description. 

Initial rollout, could be buggy.

v1.2: fix URL. Add properties. Execute "MCS workflow:delcache" to re-download data.
v1.4: fix Quick Look (Press SHIFT or CMD+Y on an entry to preview). 

## Further work:
- Optimizing search and caching logic.
- Categorizing craft essence.
