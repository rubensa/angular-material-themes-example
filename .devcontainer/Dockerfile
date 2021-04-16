FROM rubensa/ubuntu-tini-dev-chrome

# Create vscode extensions cache directory so it is owned by the user
RUN mkdir -p /home/${USER_NAME}/.vscode-server/extensionsCache

# Create node cache directory so it is owned by the user
RUN mkdir -p /home/${USER_NAME}/.npm/_cacache

