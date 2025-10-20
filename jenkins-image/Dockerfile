FROM jenkins/jenkins:lts

USER root

# Install Node.js + npm from NodeSource (recommended for newer versions)
RUN curl -fsSL https://deb.nodesource.com/setup_20.x | bash - && \
    apt-get update && apt-get install -y nodejs && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

# (Optional) Verify installation
RUN node -v && npm -v

# Switch back to Jenkins user
USER jenkins
