# gallery-be

## Getting Started

### Setup and start

* Setup postgresql (latest)
* create a user in it (it does not matter if its the root or not, you can go with the root user)
* create a database with name of gallery (but it does not matter)
* set the attributes of application properties. for you only the followings are important:
  * spring.datasource.url=jdbc:postgresql://localhost:5432/gallery
  * spring.datasource.username=dante 
  * spring.datasource.password=root
* run GalleryBeApplication as you did with Winelab
