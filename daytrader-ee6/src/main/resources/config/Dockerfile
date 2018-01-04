FROM websphere-liberty:kernel
USER root
COPY wlp/usr/servers/Daytrader3Sample /opt/ibm/wlp/usr/servers/defaultServer
RUN installUtility install --acceptLicense defaultServer
