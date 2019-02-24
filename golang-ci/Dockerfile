FROM golang:1.11-alpine3.9

LABEL "com.github.actions.name"="Run Tests"
LABEL "com.github.actions.description"="Run the test suite and generate test coverage"
LABEL "com.github.actions.icon"="trending-up"
LABEL "com.github.actions.color"="green"

COPY test-runner /usr/bin/test-runner

ENTRYPOINT ["/usr/bin/test-runner"]
