# nycscertweb
## Joel Bianchi NYCS Cert Web Portfolio
* Started 7/22/2022

* [Link to Portfolio Page](index.md)


* [GitHub Markdown cheatsheet](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


Setup Repo on GitHub (from Tophr):
* Create a new GitHub Repo
* Go to Settings on your repository.
* Towards the bottom, you will find a section called GitHub Pages
* Under source, select main from the dropdown menu and click save.
* Go to to https://<username>.github.io/nycscertweb/
  * (Wait a minute to see a change.)
  * (Refresh browser with ```Shift-Ctrl-R``` or ```Shift-F5```)


Jekyll:
* Download & Install Ruby [for Windows](https://rubyinstaller.org/)
* Install Bundler with:
  * ``` gem install bundler ```
* Install Jekyll with:
  * ```gem install jekyll bundler``` 

In Local Repo on computer:
* Clone github repo onto computer with:
  * ``` git clone -reference <github-repositorypurl> -d <directory-to-put-project-in>```
* Create a new Jekyll site in the project with:
  * ```jekyll new --skip-bundle . --force```

Using Jekyll:
* Add ```#``` to th beginning of the line that starts with ```gem "jekyll"``` to comment out this line.


To install a new Jekyll theme:
(See  modernist theme example)[https://rubygems.org/gems/jekyll-theme-modernist/versions/0.1.1]
* Edit the Gemfile:
```gem 'jekyll-theme-modernist', '~> 0.1.1' ```
* Install the theme on your computer:
```gem install jekyll-theme-modernist -v 0.1.1 ```


* To run the new site locally:
```bundle exec jekyll serve```

* Testing CSS in HTML in MD

<style>
.green {
    color: green;
    font-weight:700;
    font-size: 30px;
    font-family: "Times New Roman", Times, serif    
}
</style>

<div class="green">
    Markdown css styles
</div>
