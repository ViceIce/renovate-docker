FROM atlassian/bitbucket-server:6.4.0


ENV MYSQL_VERSION 5.1.47

RUN set -eux \
    && curl -Ls "https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-java-${MYSQL_VERSION}.tar.gz" | tar -xz --directory "${BITBUCKET_INSTALL_DIR}/lib" --strip-components=1 --no-same-owner "mysql-connector-java-${MYSQL_VERSION}/mysql-connector-java-${MYSQL_VERSION}.jar"