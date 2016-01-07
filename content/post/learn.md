+++
Categories = ["Development", "GoLang"]
Description = "A few minutes to a Hugo blog"
Tags = ["Development", "golang"]
date = "2015-12-28T18:52:35+05:30"
menu = "main"
title = "Lets Learn To Setup a Blog Using Hugo"

+++
IMP - This post is based on WINDOWS version of Hugo.


Hugo is a static website generator. Okay, our first step is to have Hugo and Git installed on your PC. Once installed, make sure it is kept in your system path.

Run cmd on you PC and set the location where you want to work on the blog.After doing that that type the following command :-


                                 hugo new site [Folder name you want to create]    {for example :- hugo new site learn}
								
A new folder will be created where you set the location. Now type another command to add a new post to your blog.


                                 hugo new post/[post name].md                      {for example :- hugo new post/first.md}

Now we need to add a theme for our blog..  create a folder named themes and change the location of your cmd to themes folder and type the next command


                                 git clone [the theme repository link]             {for example :- git clone https://github.com/SenjinDarashiva/hugo-uno.git}								 
								 
								 
Once it has been cloned, go to the folder where we made our blog. You may see a file called config.toml. Edit it using notepad or any text editor. You may see a code "title=".... you may edit the title to any title you want.
Then add a new line of code :-


                                 theme = "[theme name]"                            {for example :- theme = "hugo-uno"}


After doing this, return back to the folder and you will find a folder called content and then post. Your post will be there. Edit it now. You may write whatever you want to below the "+" sign as it is the content of your post.Save your file after doing this.

The final step is to type the following command :-

                      
                                 hugo server -w


Open your browser and type the following and press enter.


								 http://localhost:1313
								 
								 
								 
That's all , Our Blog is ready to view. You may later upload it to github and use it as a page..								 