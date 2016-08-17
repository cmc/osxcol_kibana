# osxcol_kibana
bunch of kibana searches w/ osxcollector data

/usr/bin/python2.7 osxcollector.py on target

ship back osxcollector JSON

install ES + Kibana (brew install elasticsearch, kibana && `elasticsearch` && `kibana`)

edit config && ./logstash -f logstash_ingest.conf

import searches.json into the kibana dashboard

Searches -

Browser History - Chrome

Browser History - Firefox

Chrome - Download History

Chrome - Search Inputs

Launch Agents 

Mozilla - Input History

OSX - QuarantineEvents

Safari Data - WIP

Installed Applications

Startup - General
