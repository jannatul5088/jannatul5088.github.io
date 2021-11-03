How to host a resume on GitHub
===

Purpose
---
This README file demonstrates the steps required to host and format an online resume in the *GitHub* repository. These steps consist of a light markup language, a text editor, and a static site generator. We will be using *Markdown*, *Atom*, and *Jekyll*. It also shows how to host on a DVCS (Distributed Version Control System), *GitHub*.

Prerequisites
---
First of all, you need to have a markdown-formatted resume. *Markdown* is a lightweight markup language that allows documenting texts. There is a resource about markdown under More Resources. Andrew Etter explained the benefits of using markdown in his book. They are widely used and have clean syntax, and are convenient for people to contribute to. Due to their popularity, there are many text editors available. *Atom* is an excellent editor for this. They have a live preview which makes the process easier. You also need to have a *GitHub* account, which is a distributed version control system to host a static site.

Instructions
---
1. **Create a repository on GitHub.**
	1. Click on the "*+*" sign to the left of the profile logo on the top right corner. ![New Repo](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/newRepo.png)
	2. Click on new repository.
	3. Name the repository as your username.github.io.
		> :warning: Verify that the user name is the same as your GitHub user name to work. In the picture below, put the username of username.github.io with your GitHub user name. I already have a repository with my username. Makesure about that.
	4. Make your repository public by selecting the public option.
	5. Scroll down to uncheck add a README file for now.
	6. Scroll down to choose a licence.
	7. Click on create repository. ![Create Repo](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/createRepo.png)
2. **Add your files to your repository.**
	1. Click on add a file. ![Upload Repo](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/uploadFile.png)
	2. Drop your markdown-formatted resume and a README, if you have one, on the drop box.
	3. Add a title in the commit box.
	4. Click on commit changes button. ![Upload File](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/dropFile.png)
> Andrew Etter mentioned the benefits of using *Markdown* language. It can always sync with your latest version of work. It can have multiple version control for your resume to be updated and formatted. It makes contribution very convenient. It is commonly used by developers.
3. **Create a static website using Jekyll theme.**
	1. Click on settings. ![Settings Option](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/settings.png)
	2. Go to pages.
	3. Click on source to set the branch to main.
	4. Click on save option.
	5. Click on choose a theme which will navigate to a page having a wide range of themes. ![Choose Theme](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/chooseTheme.png)
	6. Choose your desired theme for your resume.
	7. Click on select theme. ![Select Theme](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/selectTheme.png)
	8. Add a title in the commit box.
	9. Click on commit changes button. ![Final Repo](https://github.com/jannatul5088/jannatul5088.github.io/blob/main/images/finalRepo.png)
	10. Go to your repository.
	11. Select the _config.yml file and *add title: Resume* to change the title.
	12. Type https://username.github.io/ (your user name) to see the static website.
> This will make a static website for you. Andrew Etter mentioned in his book that using Jekyll as a static site generator makes the Markdown content attractive. You can see a cleaner static webiste from your markdown contents. He also stated that moving the entire website is simple too as it does not depend on any third party application or database.

**Your final resume should look like this website.**\
![gif](https://media.giphy.com/media/BKidylGsLhMkP7YKdR/giphy.gif)

More resources
---
* [Markdown Tutorial](https://www.markdownguide.org/getting-started/)
* [Modern technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Dinky Jekyll Theme](https://pages-themes.github.io/dinky/)
* [Atom](https://flight-manual.atom.io/using-atom/sections/writing-in-atom/)

Authors and Acknowledgments
---
* Etter, Andrew. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), 2016.
* My group members: Benjamin Zhou, Syed Ali Ahsen Muhammad Jafry, Minh Nam Hai Nguyen, and Akashdeep Singh.

FAQs
---
1. Why is Markdown better than a word processor?
> Markdown is free to use. It has a cleaner syntax and is simply making developers interested in contributing. It can always stay up-to-date by syncing. Moreover, it allows the separation of content and style, of HTML and CSS.
2. Why is my resume not showing up?
> GitHub pages, sometimes, take time to generate. You might verify if the username or the link provided are correct and check again for the published site after some time. Refresh the page to see the updates.
