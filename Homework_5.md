## Task 5

The client wants to develop the Instagram-like application for the cosmetologists. Somehow she had heard that the great programming language is Ruby and is asking if this is a good match for the project.

Please, advice the client the best technical approach for such an application based on the research you have performed in terms of the Instagram performance (technology stack itself with the background, please describe why you are advising exactly these options)

## Homework

Instagram is a free, online photo-sharing application and social network platform that was acquired by Facebook in 2012. Instagram allows users to edit and upload photos and short videos through a mobile app.
Instagram’s founders - Kevin Systrom and Mike Krieger - sold their startup to Facebook in 2012 for $1 billion ($300 million in cash, the rest in Facebook stock). Currently, Instagram is a free app with a net worth of more than $100 billion US.
Many businesses were inspired by the success of Instagram. This success resulted in the appearance of other well-known photo-sharing apps: Swipe, Snapchat, Vine, Camera, Flickr. 
So it is not surprising that we have a client who wishes to develop the Instagram-like application, but for particular user communities - for cosmetologists.

- Below you will find a brief description of critical components of the Instagram technology stack:
- Python/Django on the server side (back-end)
- JavaScript and React.js for the website user interface (front-end)
- React Native for the iOS and Android mobile apps
- PostgreSQL database
- Amazon S3, Amazon, EBS and Amazon EC 2 for cloud computing services
- Webpack for DevOps tasks

Our potential client asked if Ruby is a good match for her project.
Speaking of Ruby it's a dynamic, open-source programming language with a focus on simplicity and productivity. It fits in scenarios where rapid prototyping of traffic-heavy applications is desired. The core area is Web development and Ruby backed with Ruby on Rails (RoR) framework especially shines at it. Ruby provides a great developer experience and mature tooling.
History has a lot of great examples that have been built with Ruby as the main language: Airbnb, Hulu, Kickstarter, Basecamp, Dribbble, SlideShare and Github.

If take a look at the same class/level alternatives - Python is noticeable and often becomes a choice of developers. It also provides great productivity and development speed. Ruby on Rails alternative in the Python world is Django. It's also a full-stack Web development framework.
As Ruby was created as a general-purpose language and extensively used in Web, Pythons' initial focus was academic and scientific programming. It has numerous libraries for data science. The balance between coding speed/efficiency and execution performance is pretty similar for both Ruby and Python.
The main concern regarding Ruby over Python could be the problem of finding experienced, proficient and competent developers. There are fewer such developers for Ruby than for Python. Also, this limitation might lead to Ruby developers be more expensive.
After all, programming language won't be the main focus for a project like Instagram at scale. Eventually, most of the attention will be pointed at the infrastructure. Infrastructure means data-storage level, caching, data processing and tasks execution, services, servers and physical network organization.

After some investigation process on Instagram internals, the basic architecture might consist of:
- Ruby/RoR as a backend part;
- HTML/CSS/JavaScript as a front end part;
- React Native for the mobile apps (cross platform solution that can save time and money; this tool is used by world-class companies and allow developers to simultaneously integrate exceptional features into both iOS and Android apps.);
- PostgreSQL database as a data storage ( very mature, rich on features, free to pay, open-source database, which plays great at big scale, as well);
- RabbitMQ as a messaging system (if necessary);
- Amazon Web Services (to reduce efforts on servers and physical network organization).

Taking into account the narrow target audience, overall architecture could be simplified and efforts along with costs - optimized. Summary: we could recommend the usage of Ruby for such a project.
