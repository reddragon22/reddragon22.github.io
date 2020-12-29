# Xu Guanzhou's Website
* A personal website that has allowed me to sharpen my "Full Stack" capabilities
* This website showcases some of my coding/design/engineering capabilities
* Built with an rotation of various technologies I've come across and will wish to try
* More feature surely to come...

# Front End
* I use Jekyll to generate the blog posts
* I "handcraft" my own templates using CSS, HTML5, and Bootstrap
  * Thinking about rewriting the entire application in React
* I credit the artistic inspiration to a fellow computer scientist

# Hosting/Backend
* This website is now hosted on an Amazon EC2 Container - modeled off of LAMP software architecture
* Originally hosted as a github.io page
* Potentially will migrate this onto a Amazon S3
  * Thinking about wrapping the whole application into a deployable DOCKER cluster
* HTTPD
  * /sbin/service httpd start
  * /sbin/service httpd stop

# Git Hook Methodology
* This needs to be re-enabled after the EC2 migration
  * Need to be able to deploy and edit this website from any remote internet location
  * Connection
    * Public: 3.82.170.186
	* Private: 172.31.95.201
  * Needs to be incorporated into a CICD pipeline

# About
This website contains the following:
* My resume
* A portfolio detailing some projects
* A blog containing my thoughts
* A way to contact me
