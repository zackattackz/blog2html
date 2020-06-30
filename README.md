# blog2html
`blog2html` is a command line program that takes in a `.blog` file as input and outputs a formatted html file to stdout.

A `.blog` file is a sort of markdown file that has three different types of entries. Each entry begins with a \` (backtick) followed by some letter and ends with a \`.

The different entry types are 
* \`P: paragraph
* \`C: caption
* \`I: image

An example of a `.blog` file and its corresponding html file can be found in `Example_Blog_Post.blog` and `Example_Blog_Post.html`

## Dependencies
* [templatemake](https://github.com/zackattackz/templatemake) and it's dependencies

## Usage

`blog2html /path/to/blogfile.blog`
