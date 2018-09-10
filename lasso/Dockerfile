FROM bfoote/lasso

RUN go-wrapper download   # "go get -d -v ./..."
RUN go-wrapper install    # "go install -v ./..."

COPY config ./config
COPY data ./data
