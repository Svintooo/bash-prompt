# bash-prompt
My attempt at creating a configurable bash prompt from scratch using only bash and standard CLI tools.

# Install
Copy file `.bash_prompt` to your unix $HOME directory and source it in your `.bashrc` file.

Example:
```bash
cd ~

wget https://raw.githubusercontent.com/Svintooo/bash-prompt/refs/heads/main/.bash_prompt

cat >>~/.bashrc <<EOF
if [ -f ~/.bash_prompt ];then
  . ~/.bash_prompt
fi
EOF
```

# Config

## In short
1. Put your bash code in the correct section in file `.bash_prompt`.
2. Follow the code conventions described in the script comments.
3. PROFIT.

## Longer explanation
The script is designed to let anyone code their own bash prompt. Boilerplate code already exists that takes care of all the tricky details.

The script is heavily commented that explains what you need to take into consideration when writing your code. If done correctly it should just work.

# Final note
This was one of those projects that took over my life for a short while. I have spent way too much time on this. But in the end I am very proud of the result.
