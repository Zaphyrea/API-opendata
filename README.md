# API-opendata

This work is for an NGO that wants to centralise open data on the environment.
We had to make the data available to as many people as possible. To do this, we have developed and tested a REST API on an initial dataset and proposed a draft opendata portal. 

## Getting Started

To get started, follow these steps to set up the OpenData Environment Portal on your local machine:
Prerequisites

Make sure you have the following installed on your system:

    Docker: Download and install Docker from Docker's official website.


### Installation

Download Files: Download the following files and folders from this repository:

Folder Organization: Keep the downloaded files and folders in the same organization structure as provided in this repository. This is essential for the system to function properly.

      .
      ├── client_rest
      │   ├── __pycache__
      │   ├── static
      │   │   └── [static files and images]
      │   ├── templates
      │   │   └── [HTML templates]
      │   ├── client.py
      │   └── requirements.txt
      ├── mongo_seed
      │   ├── conso_departement.json
      │   └── Dockerfile
      ├── serveur_rest
      │   ├── __pycache__
      │   ├── data.py
      │   ├── serveur.py
      │   └── requirements.txt
      ├── Dockerfile-client
      ├── Dockerfile-serveur
      ├── docker-compose.yml
      └── .env


Terminal Installation:
    Open a terminal window and navigate to the directory where docker-compose.yml is located.
    Run the following command:
      

        docker-compose up

  This command will initiate the installation process.

  Access the Portal:
        Once the installation is complete, you can access the OpenData Environment Portal by opening your web browser and visiting localhost:5000.

Explore Environmental Data

After following these steps, you will have the OpenData Environment Portal up and running on your local machine. You can now explore the rich collection of environmental data presented through interactive and visually appealing histograms.

Feel free to contribute, report issues, or enhance our portal. 


