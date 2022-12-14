<p align="center">
    <img src="https://user-images.githubusercontent.com/73451363/187207442-bae7ea26-7eac-4cab-8806-42779629c653.png" alt="Tailslide logo" width="400">
</p>

# Tailslide

Welcome to Tailslide, a light-weight feature flag management tool with built-in circuit breaking.

Tailslide is a self-hosted application that can be installed on your own server and run with just a single command.

Click [here](https://tailslide-io.github.io/documentation/) for full documentation.

Tailslide's case study can be found [here](https://tailslide-io.github.io//).

## Quick Start
### Clone GitHub repository
```
git clone https://github.com/tailslide-io/tailslide
cd tailslide
```

### Run Docker
Running the command `SDK_KEY=your_SDK_KEY docker-compose up` will create a single Docker network that runs all of the Tailslide application components. Pass in your SDK_KEY argument

To start the Tailslide application:
```
SDK_KEY=your_SDK_KEY docker-compose up
```

### Access the User Interface
Visit `http://localhost:3001` and start creating your own feature flags!
