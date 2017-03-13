from debian

ENV APP_DIR /opt/app
ENV INIT $APP_DIR/bin/init
ENV CSHARP $APP_DIR/program

WORKDIR $APP_DIR
COPY app/ $APP_DIR

RUN apt-get update && \ 
  apt-get install -y \
  curl \
  libunwind8 \
  libicu52 \
  gettext && \
  curl -sSL -o dotnet.tar.gz https://go.microsoft.com/fwlink/?linkid=843453 && \
  mkdir -p /opt/dotnet && \
  tar zxf dotnet.tar.gz -C /opt/dotnet && \
  ln -s /opt/dotnet/dotnet /usr/local/bin && \
  rm dotnet.tar.gz

CMD $INIT
