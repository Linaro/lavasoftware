---
layout: flow
title: Linaro Automated Validation Architecture
permalink: /
lang: ja
description: >-
  Linaro Automated Validation Architecture (LAVA) 継続的な統合システムです テストを実行するために物理ハードウェアと仮想ハードウェアにオペレーティング システムを展開する場合。

  LAVAは、チーム間でボードを管理し、共有するためにも使用されます。
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
            Linaro Automated Validation Architecture (LAVA) は連続積分システムです テストを実行するために物理ハードウェアと仮想ハードウェアにオペレーティング システムを展開する場合。

            LAVAは、チーム間でボードを管理し、共有するためにも使用されます。
  - row: container_row
    sections:
      - format: text
        style: blockquote
        text_content:
          text: |
            ### ユースケース

            LAVAは、テストの大規模な多様性に使用することができます。

            テストは、簡単なブートテスト、ブートローダテスト、システムレベルのテストになりますが、一部のハードウェアには追加のハードウェアが必要な場合があります。 システムテスト。結果は時間の経過とともに追跡され、データをエクスポートしてさらなる分析を行うことができます。

            LAVA は[Linux Kernel Functional Testing](https://lkft.linaro.org/)や [KernelCI](https://kernelci.org/)のような大規模なテストシステムで使用されます。

            ### ソースコード

            LAVA ソースコードは [lavasoftware GitLab](https://git.lavasoftware.org/lava) でホストされています
---
