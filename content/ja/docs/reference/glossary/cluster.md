---
title: クラスター
id: cluster
date: 2019-06-15
full_link: 
short_description: >

   コンテナ化されたアプリケーションを実行する、ノードと呼ばれるワーカーマシンの集合です。すべてのクラスターには少なくとも1つのワーカーノードがあります。

aka: 
tags:
- fundamental
- operation
---
コンテナ化されたアプリケーションを実行する、{{< glossary_tooltip text="ノード" term_id="node" >}}と呼ばれるワーカーマシンの集合です。すべてのクラスターには少なくとも1つのワーカーノードがあります。

<!--more-->
ワーカーノードは、アプリケーションのコンポーネントであるPodをホストします。マスターノードは、クラスター内のワーカーノードとPodを管理します。複数のマスターノードを使用して、クラスターにフェイルオーバーと高可用性を提供します。
ワーカーノードは、アプリケーションワークロードのコンポーネントである{{< glossary_tooltip text="Pod" term_id="pod" >}}をホストします。{{< glossary_tooltip text="コントロールプレーン" term_id="control-plane" >}}は、クラスター内のワーカーノードとPodを管理します。本番環境では、コントロールプレーンは複数のコンピューターを使用し、クラスターは複数のノードを使用し、耐障害性や高可用性を提供します。