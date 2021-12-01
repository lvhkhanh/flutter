“dart” can’t be opened because Apple cannot check it for malicious software.
  System Preferences / Security Private/ General/ Allow 

# set path to run flutter in any terminal session
echo $SHELL
vi $HOME/.zshrc
export PATH="$PATH:[PATH_OF_FLUTTER_GIT_DIRECTORY]/bin"
esc :wq
source $HOME/.zshrc
