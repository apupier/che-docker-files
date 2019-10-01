FROM eclipse/che-remote-plugin-kubernetes-tooling-1.0.0:next

ENV KAMEL_VERSION 1.0.0-M1

RUN curl -L https://github.com/apache/camel-k/releases/download/${KAMEL_VERSION}/camel-k-client-${KAMEL_VERSION}-linux-64bit.tar.gz | tar -C /usr/local/bin -xz
RUN chmod +x /usr/local/bin/kamel