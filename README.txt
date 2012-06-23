This repository packages a ready to run solr server with standard example schema distributed with Solr.
It uses jetty 8 server forthe application container.

To start the Solr server , just run

    java -jar start.jar


To load some data into the index:

    cd exampledocs
    ./post.sh *.xml

Pckaged Versions:
Solr : 3.6
Jetty: 8.1.4.v20120524

