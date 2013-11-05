puppet-gerrit-workflow
======================

A workflow for using gerrit hooks to automatically publish approved puppet manifests

Why?
====

Gerrit doesn't obey git hooks, which means Gerrit wasn't working with Puppet Lab's
suggested git workflow: http://puppetlabs.com/blog/git-workflow-and-puppet-environments

How?
====

The top of the script has some settings that can be tuned.  Drop into $site\_path/hooks
or configure a separate hooks directory in gerrit.config and put it there.

About gerrit hooks: https://gerrit.googlecode.com/svn/documentation/2.1.2/config-hooks.html

The MIT License (MIT)
=====================

Copyright (c) 2013 Stephen Benjamin

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

