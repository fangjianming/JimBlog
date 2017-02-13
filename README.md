#Jimblog

> Ported Theme of [Jimmy Blog](https://github.com/fangjianming/fangjianming.github.io), Thank [Huxpro](https://github.com/Huxpro) for designing such a flawless theme.

###[Demo &rarr;](https://fangjianming.github.io/)


![](https://github.com/fangjianming/knowledges/blob/master/images/jimmy-blog.png)

## Usage

I didn't publish it as a single theme folder because a few of the pages are added and modified manually, so you should manually create some extra folders in `source` for the new pages and modify the `_config.yml` if you only have the single theme folder.

So i just pushed the whole hexo project for your convenience, all pre settings and boilerplates are included, have a look and go ahead customizing your own blog!

##### 1.Init

    git clone git@github.com:fangjianming/JimBlog.git  
    cd JimBlog  
    npm install  

##### 2.Modify
Modify `_config.yml` file with your own info.
Especially the section:

    deploy:  
      type: git  
      repo: https://github.com/fangjianming/JimBlog 
      branch: master  

Replace with your own repo!

##### 3.Writting/Serve/Deploy


    hexo new post IMAPOST  
    hexo serve // run hexo in local environment   
    hexo clean && hexo deploy // hexo will push the static files automatically into the specific branch(gh-pages) of your repo!


##### 4.Enjoy! 
Please [**Star**](https://github.com/fangjianming/JimBlog/stargazers) this Project if you like it! [**Following**](https://github.com/fangjianming) would also be appreciated!
