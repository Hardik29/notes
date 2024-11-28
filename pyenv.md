# Installing Pyenv

```
# Install dependencies
sudo apt install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python3-dev

# Install pyenv
curl https://pyenv.run | bash
```

# After installation, you'll need to add some lines to your shell configuration file (usually ~/.bashrc or ~/.zshrc):

```
# Pyenv configuration
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

# Then reload your shell configuration:

```
source ~/.bashrc  # or source ~/.zshrc
```
# Python Version Install:

```
pyenv install [PYTHON_VERSION]
```

# Check Python Version:

```
pyenv versions
```

# Set Globally Python Version:

```
pyenv global [PYTHON_VERSION]
```
