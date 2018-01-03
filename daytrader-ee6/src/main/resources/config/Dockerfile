FROM websphere-liberty:kernel
COPY wlp/etc /opt/ibm/wlp/etc /opt/ibm/wlp
COPY wlp/usr/servers/Daytrader3Sample /opt/ibm/wlp/usr/servers/defaultServer
RUN installUtility install --acceptLicense defaultServer
