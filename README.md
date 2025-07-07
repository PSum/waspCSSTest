## Wasp DaisyUI test project

Since i had a lot of problems installing DaisyUI with wasp, this is a small repo to show how to install DaisyUI with wasp

### TLDR;

The main issue was, that i installed versions of wasp, daisyui and tailwindcss that werent compatible with each other.
Since wasp uses tailwindcss@3.2.7 (Version 3 and not Version 4) you also must use DaisyUI Version 4.

You find a tutorial on how to install tailwindcss for wasp [here](https://wasp.sh/docs/project/css-frameworks). Dont forget to actually install it with `npm i -D tailwindcss@3.2.7`.
After that, install DaisyUI V4 with this command: `npm i -D daisyui@4.12.24`.

__The most important part is, that your tailwind version is compatible with wasp__

and

__that your daisyui version is compatible with your tailwind version__
