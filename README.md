My dotfiles
============

This repo builds on the awesome work from [Donne Martin](https://github.com/donnemartin), thanks man!

### Single Setup Script

#### Running with Git

##### Clone the Repo

    $ git clone https://github.com/scussel/dotfiles.git && cd dotfiles

##### Run the .dots Script with Command Line Arguments

**Since you probably don't want to install every section**, the `.dots` script supports command line arguments to run only specified sections.  Simply pass in the scripts that you want to install.  Below are some examples.

Run all:

    $ ./.dots all

Run `bootstrap.sh`, `osxprep.sh`, `brew.sh`, and `osx.sh`:

    $ ./.dots bootstrap osxprep brew osx

#### Running without Git

    $ curl -O https://raw.githubusercontent.com/scussel/dotfiles/master/.dots && ./.dots [Add ARGS Here]

## Contact Info

Feel free to contact me to discuss any issues, questions, or comments.

* Email: [william@scussel.biz](mailto:william@scussel.biz)
* Twitter: [@wscussel](https://twitter.com/wscussel)
* GitHub: [Scussel](https://github.com/scussel)
* Website: [scussel.biz](http://scussel.biz)
