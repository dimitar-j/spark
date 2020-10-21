# spark
This branch is designated for the [reference documentation site](https://schulichignite.com/spark). The library code itself can be [found here](https://github.com/Schulich-Ignite/spark).



## Contribution guide

### Prerequisites

- python 3.6+
- mkdocs
- mkdocs-material

To install all prerequisites run ```pip install -r requirements.txt``` in the root directory.

### Files

All the files are built in markdown and can be found in ```/src```, the site configuration can be found in ```mkdocs.yml```.

### Building

To build a local copy run ```mkdocs --serve``` and you will have a local copy available at [https://localhost/8000](http://localhost:8000/)

To build a release simply run the ```release``` workflow as part of github actions. 