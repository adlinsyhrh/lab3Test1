FROM		 python:3
LABEL		maintainer="compeng-utp"

RUN		 pip install Wikipedia

WORKDIR		 /app
COPY		 wikicrawler.py /app/
RUN		 chmod a+x wikicrawler.py

ENTRYPOINT 	["./wikicrawler.py"]
