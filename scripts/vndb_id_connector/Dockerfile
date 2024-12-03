FROM python:3.10

VOLUME ["/game_id_connector"]

COPY . /work

WORKDIR /work

RUN python -m pip install --upgrade pip && \
    pip install -r requirements.txt && \
    python main.py /game_id_connector/2-vndb_automated.json