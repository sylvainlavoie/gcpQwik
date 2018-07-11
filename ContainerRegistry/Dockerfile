# import from Python runtime and set up working directory

FROM python:2.7-slim
WORKDIR /app
ADD . /app

# install any necessary dependencies
RUN pip install -r requirements.txt

# open port 8080 for serving the webpage
EXPOSE 8080

# Run app.py when the container launches
CMD [ "python" , "app.py"]