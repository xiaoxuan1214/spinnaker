FROM golang:1.22.4

ADD . /go/src/spinnaker.io/demo/k8s-demo

RUN go install spinnaker.io/demo/k8s-demo

ENTRYPOINT /go/bin/k8s-demo
