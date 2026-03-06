FROM python:3.8


# set a directory for the app
WORKDIR /usr/src/app

#copy all files to the container
COPY . .

# install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# define the port number that the container should expose
EXPOSE 5000

# run the command
CMD ["python", "./app.py"]

