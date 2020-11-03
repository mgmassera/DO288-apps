FROM registry.access.redhat.com/ubi8/ubi:8.0
COPY . /home/
RUN chgrp -R 0 /home/ && \
    chmod -R g=u /home/ 
USER 1001
CMD bash -c "while true; do echo test; sleep 5; done"
