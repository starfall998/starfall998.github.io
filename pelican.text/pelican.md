Date: 2014-06-01
Title: pelican 

### pelican hierarchy  ###
       yourproject/
    ├── content
    │   └── (pages)
    ├── output
    ├── develop_server.sh
    ├── fabfile.py
    ├── Makefile
    ├── pelicanconf.py   # Main settings file
    └── publishconf.py   # Settings to use when ready to publish
    
### theme structrue ###
    ├── static
    │   ├── css
    │   └── images
    └── templates
    	├── archives.html // to display archives
   		├── period_archives.html  // to display time-period archives
    	├── article.html  // processed for each article
    	├── author.html   // processed for each author
    	├── authors.html  // must list all the authors
    	├── categories.html   // must list all the categories
    	├── category.html // processed for each category
    	├── index.html// the index. List all the articles
    	├── page.html // processed for each page
    	├── tag.html  // processed for each tag
    	└── tags.html // must list all the tags. Can be a tag cloud.






