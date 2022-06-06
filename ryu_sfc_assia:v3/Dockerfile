FROM python:3.8.10

WORKDIR /root

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

RUN git clone https://github.com/martimy/flowmanager
COPY sfc_app /root


