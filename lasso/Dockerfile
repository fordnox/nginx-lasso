FROM bfoote/lasso

RUN go-wrapper download   # "go get -d -v ./..."
RUN go-wrapper install    # "go install -v ./..."

COPY config ./config
COPY data ./data

# ADD config/config.yml /config/config.yml
# RUN mkdir /data

CMD ["/go/bin/lasso"]
