FROM hemanhp/djbase:5.0

COPY ./requirements /requirements
COPY ./src /src

WORKDIR src

EXPOSE 8000

RUN /py/bin/pip install -r /requirements/development.txt

ENV PATH="/py/bin:$PATH"