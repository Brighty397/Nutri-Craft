FROM python:3.10.8

RUN mkdir -p app/frontend

COPY Frontend app/frontend

WORKDIR /app/frontend

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

EXPOSE 8501

ENTRYPOINT ["streamlit","run"]

CMD ["NUTRI_CRAFT.py"]
