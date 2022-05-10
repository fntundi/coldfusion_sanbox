FROM adobecoldfusion/coldfusion2021:latest
ENV acceptEULA "YES"
ENV JAVA_HOME "/opt/coldfusion/jre/bin/java"
ENV CF_SCRIPTS "/app/cf_scripts/"
ENV installModules "ajax,caching,axis,mail,postgresql,redissessionstorage,scheduler,spreadsheet,debugger"
ENV password "ColdFusion123"
EXPOSE 8500/tcp
RUN mkdir -p /app/cf_scripts/scripts/ajax

