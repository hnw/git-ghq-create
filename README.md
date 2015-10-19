# git-ghq-create

`git`のサブコマンドで、`hub create`して`ghq get`までを一発に実行するものです。

`ghq`のサブコマンドが作れるなら、その方がよさそうな気もします。

## Usage

`git-ghq-create`をパスの通っているところに適当に置いて使います。

```
$ git ghq-create REPO_NAME
created repository: USER/REPO_NAME
ghq get https://github.com/USER/REPO_NAME.git
     clone https://github.com/USER/REPO_NAME.git -> /Users/USER/src/github.com/USER/REPO_NAME
       git clone https://github.com/USER/REPO_NAME.git /Users/USER/src/github.com/USER/REPO_NAME
Cloning into '/Users/USER/src/github.com/USER/REPO_NAME'...
warning: You appear to have cloned an empty repository.
Checking connectivity... done.
$
```

## Requirement

* [github/hub](https://github.com/github/hub)
* [motemen/ghq](https://github.com/motemen/ghq)

## License

The MIT License

Copyright (c) 2015 Yoshio HANAWA

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
