# Copyright 2016 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

jar_library(name = 'scalac',
            jars = [
              jar(org = 'org.scala-lang', name = 'scala-compiler', rev = '2.13.0'),
            ])

jar_library(name = 'scala-library',
            jars = [
              jar(org = 'org.scala-lang', name = 'scala-library', rev = '2.13.0'),
            ])

jar_library(name = 'scala-repl',
            jars = [
              jar(org = 'org.scala-lang', name = 'scala-compiler', rev = '2.13.0'),
              jar(org = 'org.scala-lang', name = 'scala-library', rev = '2.13.0'),
            ])

jar_library(name = 'scalastyle',
            jars = [
              scala_jar(org='org.scalastyle', name='scalastyle', rev='0.9.0')
            ])


scala_library(
  sources=['Hello.scala'],
)
