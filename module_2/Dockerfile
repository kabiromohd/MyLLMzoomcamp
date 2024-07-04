# Use the original ollama image as the base
FROM ollama/ollama

# Create the necessary directories
#RUN mkdir -p /root/.ollama

# Copy the weights from the local directory to the image
COPY ollama_files /root/.ollama

#RUN ollama serve

#RUN sleep 8

#RUN ollama run gemma:2b

# Expose the port (if needed)
EXPOSE 11434