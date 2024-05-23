# Use the official Tomcat image from the Docker Hub
FROM tomcat:9.0

# Set the working directory to the Tomcat webapps directory
WORKDIR /usr/local/tomcat/webapps/ROOT

# Copy the HTML file
COPY index.html ./index.html

COPY about.html ./about.html

# Copy the stylesheet
COPY soca-card.css .

# Copy the stylesheet
COPY styles.css .

# Copy the js file
COPY app.js ./app.js

# Copy the json file
COPY cards_data.json ./cards_data.json

# Copy the images directory
COPY img ./img

COPY language_icons ./language_icons

COPY repo_icons ./repo_icons

# Expose the default Tomcat port
EXPOSE 8080

# Start the Tomcat server
CMD ["catalina.sh", "run"]