#
#                                 - [ BROAD'16 ] -
#
# A docker instance for accessing AWS resources
# This wraps the cellprofiler docker registry
#


FROM cellprofiler/distributed-cellprofiler:2.0.0_4.2.4


# Install Cellpose 

RUN python3.8 -m pip install cellpose==2.2.2

WORKDIR /home/ubuntu
ENTRYPOINT ["./run-worker.sh"]
CMD [""]
