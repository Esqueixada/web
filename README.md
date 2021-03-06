## Requirements
- Docker [https://www.docker.com/]

## Setup
1. Clone this repository
  ```bash
  git clone https://github.com/Esqueixada/web.git
  cd web
  ```
2. Run with Docker
  ```bash
  docker-compose up
  ```
3. Visit http://localhost:4000/

## Creating Post Files
To create a new post, all you need to do is create a file in the _posts directory. How you name files in this folder is important. Jekyll requires blog post files to be named according to the following format:

>YEAR-MONTH-DAY-title.MARKUP

Where YEAR is a four-digit number, MONTH and DAY are both two-digit numbers, and MARKUP is the file extension representing the format used in the file. For example, the following are examples of valid post filenames:

> 2011-12-31-new-years-eve-is-awesome.md
> 2012-09-12-how-to-write-a-blog.md
