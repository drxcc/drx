drx scala utilities
==============

See [http://drx.cc/api](http://drx.cc/api) for api details.

drx scala utilities is a collection of classes and commonly used 
scala functions released under the Apache License 2.0 license for
uninhibited commercial use.

## Current Modules

**core**: many useful core types with no dependencies other than scala (for cross compilation for jvm, js, native)

    libraryDependencies += "cc.drx" %% "core" % "di"

- d3 inspired types
- cross compiled for jvm, js, native
- cross compiled for scala 2.10, 2.11, 2.12, 2.13

**p5**: Interaction with processing.org (p5) which uses d3 inspired utilities

    libraryDependencies += "cc.drx" %% "p5" % "di"

**archive**:  Wrapper around `apache-commons-compress` and `jpounts-lz4`

    libraryDependencies += "cc.drx" %% "archive" % "di"

**math**:  Wrapper around `apache-commons-math`

    libraryDependencies += "cc.drx" %% "math" % "di"

**ng**:  Nailgun utilities

    libraryDependencies += "cc.drx" %% "ng" % "di"

**boot**: boot/build tool using kson configuration lookup

    libraryDependencies += "cc.drx" %% "boot" % "di"

**gen**: code gen utilities around kson config files

    libraryDependencies += "cc.drx" %% "gen" % "di"


## Deprecated Modules

**conf**:

- Wrapper around typesafe's config for drx-core type classes

## History

The source of these utilities have changed over the years.

**aao**: was a large container of many of these common utilities

- started in 2005 in perl 
- ported to ruby in 2006
- ported to scala in 2010

**convey**: is an concatenative language that provided a concise engine inside of `aao` templating

**sp5-scala**: was a collection of utilities that are now rolled into cc.drx.p5

## License

   Copyright 2010 Aaron J. Radke

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

