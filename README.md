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

![my-blog-admin-1](https://user-images.githubusercontent.com/22620680/228380468-14b444d1-4dc2-4c51-9517-f0166ed99ccc.png)
![my-blog-admin-add-comment-to-post](https://user-images.githubusercontent.com/22620680/228380472-099d595a-869a-4af7-ba1a-3d83fcaad6ac.png)
![my-blog-admin-add-domain-name-to-sitemap](https://user-images.githubusercontent.com/22620680/228380476-77fada46-786b-4f13-a589-c89c016862e5.png)
![my-blog-admin-add-post](https://user-images.githubusercontent.com/22620680/228380478-b89df467-474e-4cc8-93d3-f0286bd05237.png)
![my-blog-feed-subscribe-to-rss](https://user-images.githubusercontent.com/22620680/228380480-b793c53e-906f-4c37-9c48-dde8abd62346.png)
![my-blog-home-page](https://user-images.githubusercontent.com/22620680/228380481-2d5446d1-42f5-4d4a-a4b9-d7a46fb339b7.png)
![my-blog-post-add-comment](https://user-images.githubusercontent.com/22620680/228380484-c9845369-de1d-45d7-9188-40a9de723f71.png)
![my-blog-post-search-page](https://user-images.githubusercontent.com/22620680/228380487-7d27ad3c-ac5b-475f-9b89-67d0d68518ef.png)
![my-blog-post-search-result](https://user-images.githubusercontent.com/22620680/228380489-93d7b3ef-7d4d-4ccd-bc8a-a7784949be57.png)
![my-blog-post-share-page](https://user-images.githubusercontent.com/22620680/228380490-253e6e29-e7ae-44fc-8a7f-16c528ce8a94.png)
![my-blog-post-with-comment](https://user-images.githubusercontent.com/22620680/228380491-8103ce69-5298-4a99-92f7-f2a906f21dd6.png)
![my-blog-sitemap xml](https://user-images.githubusercontent.com/22620680/228380493-9e1273d8-2b99-4399-9080-2a0d05c48357.png)
