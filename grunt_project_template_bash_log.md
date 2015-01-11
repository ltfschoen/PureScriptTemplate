$ npm install -g grunt-init
/usr/local/bin/grunt-init -> /usr/local/lib/node_modules/grunt-init/bin/grunt-init
grunt-init@0.3.2 /usr/local/lib/node_modules/grunt-init
├── semver@1.0.14
├── async@0.2.10
├── colors@0.6.2
├── hooker@0.2.3
├── lodash@2.4.1
├── grunt@0.4.5 (which@1.0.8, dateformat@1.0.2-1.2.3, eventemitter2@0.4.14, getobject@0.1.0, rimraf@2.2.8, async@0.1.22, grunt-legacy-util@0.2.0, exit@0.1.2, lodash@0.9.2, nopt@1.0.10, coffee-script@1.3.3, underscore.string@2.2.1, iconv-lite@0.2.11, glob@3.1.21, grunt-legacy-log@0.1.1, minimatch@0.2.14, findup-sync@0.1.3, js-yaml@2.0.5)
└── prompt@0.1.12 (async@0.1.22, pkginfo@0.3.0, winston@0.5.11)

$ mkdir ~/.grunt-init

$ git clone https://github.com/purescript-contrib/grunt-init-purescript.git ~/.grunt-init/purescript 
Cloning into '/Users/Luke/.grunt-init/purescript'...
remote: Counting objects: 61, done.
remote: Total 61 (delta 0), reused 0 (delta 0)
Unpacking objects: 100% (61/61), done.
Checking connectivity... done.

$ mkdir purescript-grunt-template-test

cd purescript-grunt-template-test/

$ grunt-init purescript
Running "init:purescript" (init) task
This task will create one or more files in the current directory, based on the
environment and the answers to a few questions. Note that answering "?" to any
question will show question-specific help and answering "none" to most questions
will leave its value blank.

Please answer the following:
[?] Project name (starter-kit) 
[?] Description (An empty PureScript project.) 
[?] Version (0.1.0) 
[?] Licenses (MIT) 
[?] Author name (ltfschoen) 
[?] Do you need to make any changes to the above before continuing? (y/N) N

Writing .bowerrc...OK
Writing .gitignore...OK
Writing Gruntfile.js...OK
Writing README.md...OK
Writing bower.json...OK
Writing js/index.js...OK
Writing package.json...OK
Writing src/Starter/Kit/Example.purs...OK
Writing tests/Tests.purs...OK
Writing LICENSE-MIT...OK

Initialized from template "purescript".
You can now build the project as follows: 

  npm install
  bower update
  grunt

Done, without errors.

$ npm install
grunt-contrib-copy@0.5.0 node_modules/grunt-contrib-copy

grunt-purescript@0.6.0 node_modules/grunt-purescript

grunt-execute@0.1.5 node_modules/grunt-execute

grunt-contrib-clean@0.5.0 node_modules/grunt-contrib-clean
└── rimraf@2.2.8

grunt@0.4.5 node_modules/grunt
├── which@1.0.8
├── dateformat@1.0.2-1.2.3
├── eventemitter2@0.4.14
├── getobject@0.1.0
├── rimraf@2.2.8
├── colors@0.6.2
├── async@0.1.22
├── hooker@0.2.3
├── grunt-legacy-util@0.2.0
├── exit@0.1.2
├── nopt@1.0.10 (abbrev@1.0.5)
├── lodash@0.9.2
├── coffee-script@1.3.3
├── minimatch@0.2.14 (sigmund@1.0.0, lru-cache@2.5.0)
├── underscore.string@2.2.1
├── iconv-lite@0.2.11
├── glob@3.1.21 (graceful-fs@1.2.3, inherits@1.0.0)
├── findup-sync@0.1.3 (lodash@2.4.1, glob@3.2.11)
├── grunt-legacy-log@0.1.1 (underscore.string@2.3.3, lodash@2.4.1)
└── js-yaml@2.0.5 (esprima@1.0.4, argparse@0.1.16)

$ bower update
bower cached        git://github.com/purescript/purescript-foldable-traversable.git#0.2.1
bower validate      0.2.1 against git://github.com/purescript/purescript-foldable-traversable.git#*
bower cached        git://github.com/purescript/purescript-quickcheck.git#0.3.2
bower validate      0.3.2 against git://github.com/purescript/purescript-quickcheck.git#*
bower cached        git://github.com/purescript/purescript-arrays.git#0.3.0
bower validate      0.3.0 against git://github.com/purescript/purescript-arrays.git#*
bower cached        git://github.com/purescript/purescript-maybe.git#0.2.1
bower validate      0.2.1 against git://github.com/purescript/purescript-maybe.git#*
bower cached        git://github.com/purescript/purescript-math.git#0.1.0
bower validate      0.1.0 against git://github.com/purescript/purescript-math.git#*
bower cached        git://github.com/purescript/purescript-maybe.git#0.2.1
bower validate      0.2.1 against git://github.com/purescript/purescript-maybe.git#~0.2.0
bower cached        git://github.com/purescript/purescript-control.git#0.2.1
bower validate      0.2.1 against git://github.com/purescript/purescript-control.git#~0.2.0
bower cached        git://github.com/purescript/purescript-tuples.git#0.2.3
bower validate      0.2.3 against git://github.com/purescript/purescript-tuples.git#~0.2.3
bower cached        git://github.com/purescript/purescript-either.git#0.1.4
bower validate      0.1.4 against git://github.com/purescript/purescript-either.git#~0.1.4
bower cached        git://github.com/purescript/purescript-monoid.git#0.1.5
bower validate      0.1.5 against git://github.com/purescript/purescript-monoid.git#~0.1.4
bower cached        git://github.com/purescript/purescript-foldable-traversable.git#0.1.6
bower validate      0.1.6 against git://github.com/purescript/purescript-foldable-traversable.git#~0.1.4
bower cached        git://github.com/purescript/purescript-random.git#0.1.1
bower validate      0.1.1 against git://github.com/purescript/purescript-random.git#~0.1.1
bower cached        git://github.com/purescript/purescript-exceptions.git#0.2.2
bower validate      0.2.2 against git://github.com/purescript/purescript-exceptions.git#~0.2.2
bower cached        git://github.com/purescript/purescript-strings.git#0.4.2
bower validate      0.4.2 against git://github.com/purescript/purescript-strings.git#~0.4.2
bower install       purescript-arrays#0.3.0
bower install       purescript-control#0.2.1
bower install       purescript-foldable-traversable#0.1.6
bower install       purescript-maybe#0.2.1
bower install       purescript-math#0.1.0
bower install       purescript-quickcheck#0.3.2
bower install       purescript-tuples#0.2.3
bower install       purescript-either#0.1.4
bower install       purescript-strings#0.4.2
bower install       purescript-exceptions#0.2.2
bower install       purescript-random#0.1.1
bower install       purescript-monoid#0.1.5

purescript-arrays#0.3.0 bower_components/purescript-arrays
├── purescript-control#0.2.1
└── purescript-maybe#0.2.1

purescript-control#0.2.1 bower_components/purescript-control

purescript-foldable-traversable#0.1.6 bower_components/purescript-foldable-traversable
├── purescript-arrays#0.3.0
├── purescript-control#0.2.1
├── purescript-either#0.1.4
├── purescript-maybe#0.2.1
├── purescript-monoid#0.1.5
└── purescript-tuples#0.2.3

purescript-maybe#0.2.1 bower_components/purescript-maybe
└── purescript-control#0.2.1

purescript-math#0.1.0 bower_components/purescript-math

purescript-quickcheck#0.3.2 bower_components/purescript-quickcheck
├── purescript-arrays#0.3.0
├── purescript-either#0.1.4
├── purescript-exceptions#0.2.2
├── purescript-foldable-traversable#0.1.6
├── purescript-math#0.1.0
├── purescript-maybe#0.2.1
├── purescript-random#0.1.1
├── purescript-strings#0.4.2
└── purescript-tuples#0.2.3

purescript-tuples#0.2.3 bower_components/purescript-tuples
├── purescript-arrays#0.3.0
├── purescript-control#0.2.1
└── purescript-monoid#0.1.5

purescript-either#0.1.4 bower_components/purescript-either
└── purescript-control#0.2.1

purescript-strings#0.4.2 bower_components/purescript-strings
└── purescript-maybe#0.2.1

purescript-exceptions#0.2.2 bower_components/purescript-exceptions

purescript-random#0.1.1 bower_components/purescript-random

purescript-monoid#0.1.5 bower_components/purescript-monoid
├── purescript-arrays#0.3.0
└── purescript-maybe#0.2.1
ruby-2.1.2 
~/code/git/learning/purescript-grunt-template-test $ grunt
Running "clean:0" (clean) task

Running "clean:1" (clean) task

Running "pscMake:lib" (pscMake) task
>> Make was successful.

Running "dotPsci:0" (dotPsci) task
>> Created .psci file

Running "pscMake:tests" (pscMake) task
>> Make was successful.

Running "copy:0" (copy) task
Created 50 directories, copied 98 files

Running "copy:1" (copy) task
Copied 1 files

Running "execute:tests" (execute) task
-> executing /Users/Luke/code/git/learning/purescript-grunt-template-test/tmp/index.js
The differences of an empty list are empty.
1/1 test(s) passed.
The differences of a single-element list are empty.
100/100 test(s) passed.
The differences of a pair of equal elements are zero.
100/100 test(s) passed.
The diffs function returns Just (...) for a sorted list.
100/100 test(s) passed.
The diffs function returns Nothing for a reverse-sorted list with at least one pair of unequal elements.
100/100 test(s) passed.
-> completed /Users/Luke/code/git/learning/purescript-grunt-template-test/tmp/index.js (137ms)

>> 1 file and 0 calls executed (139ms)

Done, without errors.