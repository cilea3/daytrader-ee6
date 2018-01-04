FROM websphere-liberty:kernel
RUN chmod 777 -R /opt/ibm/wlp/ /logs
COPY wlp/usr/servers/Daytrader3Sample /opt/ibm/wlp/usr/servers/defaultServer
RUN installUtility install --acceptLicense defaultServer
