# blog-social-network

## Features

- Create posts and comments to posts
- Searching posts
- Making sitemaps
- Making RSS feeds
- Sharing interesting posts

## Installation

Install the project into your_dir.

```sh
cd your_dir
git clone https://github.com/alexzubkoff/blog-social-network.git  .
```
## Docker

MyBlog is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8000, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
docker-compose up -d --build 
docker-compose exec web python manage.py migrate  
```
When create your superuser:
```sh
docker-compose exec web python manage.py createsuperuser 
```
Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000/
Using the URLconf defined in config.urls, Django tried these URL patterns, in this order:
127.0.0.1:8000/admin/
127.0.0.1:8000/blog/
127.0.0.1:8000/sitemap.xml 
```


## License

MIT

**Free Software, Alex Zubkov!**