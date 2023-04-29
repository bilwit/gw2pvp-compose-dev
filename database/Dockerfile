FROM mongo:4.0.10

# ADD ./db.tar.gz /data/db

# Initialize db default values
COPY ./init-db.d/seed.sh /docker-entrypoint-initdb.d

# Expose port
EXPOSE 27017

