FROM solr:6.6.5

COPY solrconfig.xml /opt

USER root

RUN rm /opt/solr/server/solr/configsets/basic_configs/conf/solrconfig.xml &&\
    mv /opt/solrconfig.xml /opt/solr/server/solr/configsets/basic_configs/conf

USER solr
