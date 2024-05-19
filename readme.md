# AI Commit Message Script

This script uses ollama to generate commit messages based on the changes made in your git repository, the package.json (if there is one), and all commits message pushed.

## Installation

### 1. Clone the repository:

   ```git clone <repository-url>```

### 2. Navigate to the directory containing the script:

   ```cd <repository-directory>```

### 4. Add the script to your PATH.

   You can do this by adding the following line to your `.bashrc` or `.bash_profile` file:

   ```export PATH=$PATH:/path/to/your/script/directory```

   Replace `/path/to/your/script/directory` with the actual path to the directory containing the `ai_commit` script, you could use `pwd` if you are in the correct directory.


### 5. Reload your bash shell to apply the changes:

   ```source ~/.bashrc```
   or
   ```source ~/.bash_profile```
   depending on which file you added the PATH export to.

## Usage

To use the script, simply call `ai_commit` in your terminal. You can optionally pass a model name as an argument. If no model name is provided, it defaults to `deepseek-coder:6.7b-instruct`.

Example:
```ai_commit```
or
```ai_commit mistral```
