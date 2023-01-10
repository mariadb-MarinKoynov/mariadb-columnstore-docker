FROM mariadb/skysql-enterprise-columnstore:sky-6.3.1-GA

# Copy Config Files & Scripts To Image
COPY scripts/skysql-specific-startup.sh /usr/bin/

# Make Scripts Executable
RUN chmod +x /usr/bin/skysql-specific-startup.sh
