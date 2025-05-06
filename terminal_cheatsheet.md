# Start local server
python3 -m http.server

# Run server in background
nohup python3 -m http.server > server.log 2>&1 &

# Stop all background servers
pkill -f "http.server"

# Make new file
touch index.html

# Make new folder
mkdir NewFolder
