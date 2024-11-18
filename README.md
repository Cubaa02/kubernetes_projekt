# kubernetes_projekt

# Enter the directory
cd kubernetes_projekt

# Create a virtual enviroment .venv
python -m venv .venv

# Activate the virtual enviroment
. .venv/bin/activate

# Install the requirements
pip install -r requirements.txt

# Build the container
docker build -t test .

# Run the docker container
docker run -p 5000:5000
