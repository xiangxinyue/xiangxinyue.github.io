# Building a static website with GitHub Pages 
I am going to write a readme for anyone, including people who don't have a lot of computer science foundation. 
So that people can use GitHub Pages to build their own static websites in a short time.
This readme will also include the steps to buy a domain name (if you do want to have your own domain name instead of github.io), resolve the domain name, and so on.

# About
In February of 2019, I came up with the idea of making my own personal website/tech blog. At that time, I was a second year computer major student who was looking for an internship so this website might help me more on that time. And also it is the time when I really wanted to learn new knowledge.

# Requirement
1)A github id is enough at the beginning! 

2)If you want to make a better website based on frame you might need to know some basic HTML/CSS/JS.

3)Overall, it is Github pages + Jekyll + Ruby + Git + md.

# First Step: Let's Go! Create a Repository
1)Have your github id and know some Git basics.

2)Create a new repository named like xiangxinyue.github.io (name.github.io).

# Second Step: Choose a theme or fork other people's repo
1)Go to the setting and find the Github Pages.

2)You will see a link like "Your site is published at https://xiangxinyue.github.io/". Click it and you will see your website.

# Third Step: Get your machine enviorment prepared

1)Before you have Jekyll in your machine, you need to have ruby and gem. If you do not have ruby in your machine first install ruby and gem.

2)Use "$ ruby -v" to check your ruby version or if your machine have ruby. Mac OS already have ruby but you better to get a newest one.

3)Use "$ brew install ruby" to download ruby. If you do not have home brew in your machine use the command "$/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

4)Use "$ gem install jekyll bundle" to download jekyll. 

5)You better do the whole things in the Ubuntu, it is better in Mac OS.


# Fourth Step: Revise the website to your style using Jekyll
1)Another way to open the website is "cd xiangxinyue.github.io" in terminal. -> then "bundle exec jekyll serve". Then you can go through Returned IP address and to look at your website through localhost.

2)_config.yml : Global configuration file.

3)posts: The file put your blog article.

4)Other file you can see the details inside.

5)Use the local host to see your revision.



# Fifth Step : Your self define domain name
1)Buy a domain name.

2)Resolve domain name. After registering your domain name, you need to resolve the domain name to your blog.

3)Management Console → Domain Name and Website (Internet) → Domain Name.

4)Add parsing. Add two A record types separately. A host record is www, which represents the domain name that can resolve www.xiangxinyue.top( I bought it from ali cloud)
The other is @, representing xiangxinyue.top.

5)The recorded value is the IP address of our blog, which is the address of the GitHub Pagas server in the United States 151.101.100.133. Because the Github Pages use the CNAME to lead it to your github io.

# Well done!
If you do want to futuer develop your website, see the jekyll document https://jekyllrb.com/

# Conclusion
The hardest part is to set the envirment in Mac OS. So I wrote another document about "How to download Jekyll in Mac OS" and will put it in my github. But using Ubuntu is a great choice.

# Development time-line and versions instructions
This Github Pages is based on Jekyll-Mono.

The first version (Jan 2019 - July 2019) is based on the repo crafted by [Akshay Agarwal](https://github.com/AkshayAgarwal007). Thanks to him!

Will continue update ...

July

Aug
 











  
