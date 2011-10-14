# Scala Improvement Process Website #

This project generates the SIP website containing all pending/finished/rejected SIPs.


## Migrating a SIP to other states ##

To reject a SIP simply:

    git mv pending/_posts/{sip-file}  rejected/_posts/{sip-file}

To mark a SIP completed simply:

    git mv pending/_posts/{sip-file}  completed/_posts/{sip-file}

