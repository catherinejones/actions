FROM golang:1.11-alpine3.9

LABEL "com.github.actions.name"="Run Golang Tests"
LABEL "com.github.actions.description"="Run the test suite and generate test coverage"
LABEL "com.github.actions.icon"="activity"
LABEL "com.github.actions.color"="green"

RUN apk add --no-cache \
        git

COPY test-runner /usr/bin/test-runner

ENTRYPOINT ["/usr/bin/test-runner"]
