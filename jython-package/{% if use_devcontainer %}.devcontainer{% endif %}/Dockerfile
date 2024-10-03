FROM quay.io/ignition-devs/devcontainer-base:jython

COPY requirements.txt /tmp/requirements.txt

RUN set -eux; \
    \
    python2 -m pip install --requirement \
        /tmp/requirements.txt

CMD ["/bin/bash"]