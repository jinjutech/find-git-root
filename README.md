# find-git-root
Recursively find the closest .git/ and return repo path

# Installation

    $ npm install find-git-root

# Usage

    'use strict'

    const findGitRoot = require('find-git-root)

    // git clone url /home/you/repo
    const root = findGitRoot('/home/you/repo/somedir/somefile')
    // => /home/you/repo

    const root = findGitRoot('/home/you/repo/somedir')
    // => /home/you/repo