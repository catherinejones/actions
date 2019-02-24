FROM alpine:3.9

LABEL "com.github.actions.name"="Push Test Coverage"
LABEL "com.github.actions.description"="Push the test coverage to Code Climate"
LABEL "com.github.actions.icon"="code"
LABEL "com.github.actions.color"="red"

RUN curl -L https://codeclimate.com/downloads/test-reporter/test-reporter-latest-linux-amd64 > /usr/bin/cc-test-reporter

ENTRYPOINT ["cc-test-reporter"]
