FROM python:3.12-slim-bookworm

WORKDIR /logical

COPY python_libs.txt .

RUN pip install --no-cache-dir -r python_libs.txt

COPY logical_python_functions.py .

CMD ["python", "logical_python_functions.py"]

