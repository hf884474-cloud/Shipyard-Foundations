# Use a lightweight version of Python
FROM python:3.9-slim

# Create a folder inside the container for our app
WORKDIR /app

# Copy the script from your computer into the container
COPY . .

# Tell Docker to run the python script
# (Check if the file in your folder is named 'script.py' or 'app.py')
CMD ["python", "script.py"]