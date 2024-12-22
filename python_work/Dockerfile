FROM python:3.10-slim

WORKDIR /app

RUN apt-get update && \
    apt-get install -y --no-install-recommends python3 python3-pip && \
    pip install --no-cache-dir pycodestyle && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

# COPY requirements.txt ./

# RUN pip install --no-cache-dir -r requirements.txt

# COPY . ./

CMD [ "tail", "-f", "/dev/null" ]