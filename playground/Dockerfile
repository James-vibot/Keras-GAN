FROM tensorflow/tensorflow:latest-gpu

RUN mkdir /workspace

WORKDIR /workspace
COPY . /workspace

RUN pip install keras numpy matplotlib

CMD python3 gan.py
