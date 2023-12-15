FROM python:3
COPY requirement.txt /requirement.txt
RUN pip install -r requirement.txt
COPY deployment.py /deployment.py
CMD ["python" , "/deployment.py"]
