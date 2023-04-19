# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY Cprogram_2.c .
# Compile the C program
RUN gcc -o Cprogram_2 Cprogram_2.c
# Set the command to run when the container starts
CMD ["./Cprogram_2"]