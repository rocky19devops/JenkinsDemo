FROM python
WORKDIR /app
COPY app.py requirements.txt .
RUN python -m pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD ["app.py" ]
