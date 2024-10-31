FROM python:3.14-rc-slim

COPY ./ /tmp/build
WORKDIR /tmp/build
RUN python -m pip install --no-cache-dir . && rm -rf /tmp/build

ENTRYPOINT ["pylint"]
