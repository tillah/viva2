FROM python
RUN pip install flask
COPY ./static /home/myapp/static/
COPY ./templates /home/myapp/templates/
COPY viva_app.py /home/myapp/
EXPOSE 5000
CMD python /home/myapp/viva_app.py
