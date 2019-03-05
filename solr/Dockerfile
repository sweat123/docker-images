FROM solr:7.7.1

COPY solrconfig.xml /opt

USER root

RUN rm /opt/solr/server/solr/configsets/_default/conf/solrconfig.xml &&\
    mv /opt/solrconfig.xml /opt/solr/server/solr/configsets/_default/conf

USER solr
