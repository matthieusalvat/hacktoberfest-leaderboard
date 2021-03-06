# hacktoberfest-leaderboard
This is the leaderboard application for the hacktoberfest summit.
The application is kept simple so you can improve it with your own pull requests to help you
contribute for the hacktoberfest.

The application is hosted on Heroku. Visit it [here](https://hacktoberfest-leaderboard.herokuapp.com/)

Happy coding

## How to test localy
The application is written in `Ruby`, using the [Sinatra](http://www.sinatrarb.com/) framework.
> Need to learn Ruby ? Visit [Rubymonk](https://rubymonk.com/)
### Setup dev environment
First, you need to install an `ruby` interpretter, alongside with the `gem` ruby package management tool.
Visit [Ruby language website](https://www.ruby-lang.org) for more details.

You'll probably need an editor too. [Notepad++](https://notepad-plus-plus.org/) is a simple alternative, [Visual Studio Code](https://code.visualstudio.com/) is a more advanced one.

Download `bundler` by running
```bash
    gem install bundler
```
> If you're running behind a proxy, you'll need to set both environment variables `HTTP_PROXY` and `HTTPS_PROXY`

### Running the app localy
Run
```bash
    bundle exec ruby leaderboard.rb
```
then browse to http://localhost

### Usefull documents
* [Sinatra usage](http://www.sinatrarb.com/intro.html)
* [Github_api usage](https://github.com/piotrmurach/github)