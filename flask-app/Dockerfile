#base image with Python
FROM python:3.9

#Working directory for the app
WORKDIR app/

#Copy the code from the system
COPY app.py .

#install required libraries
RUN pip install Flask

#RUN the application
CMD ["python","app.py"]




