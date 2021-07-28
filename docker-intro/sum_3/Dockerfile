FROM alpine
COPY sum.py /home
# set script permissions
RUN chmod +x /home/sum.py
# add /home folder to the PATH
ENV PATH /home:$PATH
RUN apk add --update python3 py3-pip python3-dev