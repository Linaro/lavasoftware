---
layout: flow
title: Linaro Automated Validation Architecture
permalink: /
description: >-
  Linaro Automated Validation Architecture (LAVA) is a continuous integration system
  for deploying operating systems onto physical and virtual hardware for running tests.

  LAVA is also used to managed and share boards among teams.
jumbotron:
  inner_class: #
  title: Linaro Automated Validation Architecture
  class: background-image
  title-class: font-weight-bold
  image: /assets/images/content/lava_image.jpg
flow:
  - row: container_row
    style: bg-light-green
    sections:
      - format: text
        style: blockquote
        text_content:
          text: |
            Linaro Automated Validation Architecture (LAVA) is a continuous integration system
            for deploying operating systems onto physical and virtual hardware for running tests.

            LAVA is also used to managed and share boards among teams.
  - row: container_row
    sections:
      - format: text
        style: blockquote
        text_content:
          text: |
            ### Use cases

            LAVA can be used for a large diversity of tests.

            Tests can be simple boot testing, bootloader testing and system level testing, although extra hardware may be required for some
            system tests. Results are tracked over time and data can be exported for further analysis.

            LAVA is used in large testing systems like [Linux Kernel Functional Testing](https://lkft.linaro.org/) or [KernelCI](https://kernelci.org/).

            ### Source code

            The LAVA source code is hosted on [lavasoftware GitLab](https://git.lavasoftware.org/lava)
---
