FROM softwrdev/tensorflow:latest-gpu-python-py37

ENV PYTHONUNBUFFERED 1

# Upgrade to latest pip
RUN pip install --upgrade pip

COPY ./requirements /requirements

# Install required python packages
RUN pip install --no-cache-dir -r /requirements/requirements.txt && rm -rf /requirements
