# TAG: 0.3

FROM python:3.11.5

COPY requirements.txt /tmp/requirements.txt

RUN pip3 install --no-cache-dir --prefer-binary \
    -r /tmp/requirements.txt

CMD [ "/bin/bash" ]

LABEL \
    maintainer="Marc Vorwerk" \
    org.label-schema.description="Ansible in a container for CI" \
    org.label-schema.build-date=${BUILD_DATE} \
    org.label-schema.name="ansible-lint" \
