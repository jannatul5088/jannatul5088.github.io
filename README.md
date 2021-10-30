How to host and upload a resume on GitHub
===

Purpose
---
This README file demonstrates the steps required to host and format an online resume in the *GitHub* repository. These steps consist of a light markup language-*Markdown*, a text editor-*Atom*, and a static site generator-*Jekyll*. It also shows how to host on a DVS (Distributed Control System), *GitHub*.

Prerequisites
---
First of all, you need to have a markdown-formatted resume. *Markdown* is a lightweight markup language that allows documenting texts. There is a resource about markdown under More Resources. Andrew Etter explained the benefits of using markdown in his book. They are widely used and have clean syntax. They are convenient for people to contribute. Due to their popularity, there are many text editors available. *Atom* is an excellent editor for this. They have a live preview which makes the process easier. You also need to have a *GitHub* account. It is a distributed version control system to host a static site.

Instructions
---
* **Create a repository on GitHub.**
	1. Click on the "*+*" sign to the left of the profile logo on the top right corner.
	2. Click on new repository.
	3. Name the repository as your username.github.io.
		> :warning: Verify that the username is same as your GitHub user name to work.
	4. Make your repository public by selecting the public option.
	5. Scroll down and you can select off add a README file for now.
	6. Scroll down and choose a licence.
	7. Click on create repository.
* **Add your files to your repository.**
	1. Click on add a file.
	2. Drop your markdown-formatted resume and a README, if you have one, on the drop box.
	3. Add a title in the commit box.
	4. Click on commit changes button.
> Andrew Etter mentioned the benefits of using *Markdown* language. It can always sync with your latest version of work. It can have multiple version control for your resume to be updated and formatted. It enables contribution to a very convenient process.
* **Create a static website using Jekyll theme.**
	1. Click on settings.
	2. Go to pages.
	3. Click on source and set the branch to main.
	4. Click on save option.
	5. Click on theme which will navigate to a page having a wide range of themes.
	6. Choose your desired theme for your resume.
	7. Add a title in the commit box.
	8. Click on commit changes button.
	9. Go to your repository.
	10. Select the _config.yml file and add tile: Resume to change the title.
	11. Type https://username.github.io/ to see the static website.
> This will make a static website for you. Andrew Etter mentioned in his book that using Jekyll as a static site generator makes the Markdown content attractive. You can see an elegant site from your markdown contents.

**Your final resume should look like this website.**
![gif](https://media.giphy.com/media/BKidylGsLhMkP7YKdR/giphy.gif)

More resources
---
* [Markdown Tutorial](https://www.markdownguide.org/getting-started/)
* [Modern technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Dinky Jekyll Theme](https://pages-themes.github.io/dinky/)
* [Atom](https://flight-manual.atom.io/using-atom/sections/writing-in-atom/)

Authors and Acknowledgments
---
This article is written by [Md Jannatul Nayem](https://github.com/jannatul5088/jannatul5088.github.io).
Credits:
* Etter, Andrew. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), 2019.
* [Dinky](https://pages-themes.github.io/dinky/) Jekyll Theme
* My group members: Benjamin Zhou, Syed Ali Ahsen Muhammad Jafry, Minh Nam Hai Nguyen, and Akashdeep Singh.

FAQ
---
1. Why is Markdown better than a word processor?
> Markdown is free to use. It has a cleaner syntax and is simply making developers interested to contribute. It can always stay up-to-date by syncing. Moreover, it allows the separation of content and style, of HTML and CSS.
2. Why is my resume not showing up?
> GitHub pages, sometimes, take time to generate. You might verify if the username and the link provided are correct and check again for the published site after some interval. 
