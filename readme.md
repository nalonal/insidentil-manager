
# Elasticsearch and Kibana Docker Compose

This repository contains a `docker-compose` file to spin up Elasticsearch and Kibana services in a single containerized environment. 

## Prerequisites

-   Docker
-   Docker Compose

## Installation

1.  Clone the repository:
    
    Copy code
    
    `git clone https://github.com/nalonal/insidentil-manager.git` 
    
2.  Navigate to the cloned repository:
    
    Copy code
    
    `cd insidentil-manager` 
    
3.  Start the containers:
    
    Copy code
    
    `docker-compose up` 
    

## Usage

Once the containers are up and running, you can access Elasticsearch and Kibana via the following URLs:

-   Elasticsearch: [http://localhost:9200](http://localhost:9200/)
-   Kibana: [http://localhost:5601](http://localhost:5601/)

You can use these URLs to interact with the services and perform various operations.

## Configuration

By default, the `docker-compose` file sets up Elasticsearch and Kibana with the following configuration:

-   Elasticsearch:
    -   Version: 8.4.0
    -   Port: 9200
-   Kibana:
    -   Version: 8.4.0
    -   Elasticsearch URL: [http://elasticsearch:9200](http://elasticsearch:9200/)

You can modify these settings by editing the `docker-compose.yml` file.

## Maintenance

To stop the containers, use the following command:

bashCopy code

`docker-compose down` 

## Contributing

If you find any issues or have any suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://chat.openai.com/LICENSE) file for details.