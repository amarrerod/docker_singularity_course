FROM alpine
COPY sum.py /home
RUN apk add --update python3 py3-pip python3-dev
ENTRYPOINT ["python3", "/home/sum.py"]
CMD [ "10", "11" ]