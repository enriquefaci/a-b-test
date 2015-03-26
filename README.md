<!--_
Copyright 2015 HM Revenue & Customs

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
A-B-Test
===========

[![Build Status](https://travis-ci.org/hmrc/a-b-test.svg?branch=master)](https://travis-ci.org/hmrc/a-b-test)

Micro-library to help with A-B-Testing. Chooses a cohort from a set of cohorts given an identifier

# Adding to your service

Include the following dependency in your SBT build

```scala
resolvers += Resolver.bintrayRepo("hmrc", "releases")

libraryDependencies += "uk.gov.hmrc" %% "a-b-test" % "0.0.1"
```

