FROM us-docker.pkg.dev/vertex-ai/training/pytorch-gpu.1-11:latest

COPY . /trainer-ddp-gpu

WORKDIR /trainer-ddp-gpu

RUN pip install -r requirements.txt

ENTRYPOINT ["python", "-m", "main"]
