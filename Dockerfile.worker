FROM n8nio/n8n:latest

# Switch to root to install custom node
USER root

# Install Telepilot node
RUN npm install --no-save @telepilotco/n8n-nodes-telepilot

# Switch back to n8n user
USER node

# Start worker
CMD ["n8n", "worker"]
