FROM ubuntu:16.04
 
WORKDIR /mydir
COPY script.sh .
RUN chmod 755 script.sh
RUN apt-get update && apt-get install -y curl
CMD ["/bin/bash", "./script.sh"]
