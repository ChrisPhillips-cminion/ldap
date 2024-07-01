#Pull the latest base image from Dockerhub

FROM osixia/openldap

# Set the environment variables

ENV LDAP_ORGANISATION="SWAT CP4I" \

LDAP_DOMAIN="swat.cp4i.com" \

LDAP_BASE_DN="dc=swat,dc=cp4i,dc=com"

COPY bootstrap.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-bootstrap.ldif
