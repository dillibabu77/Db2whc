---

copyright:
  years: 2014, 2018
lastupdated: "2018-03-15"

---

<!-- Attribute definitions --> 
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# 柔軟なスケーリング
{: #scale}

ストレージとコンピュート・コアの独立したスケーリング。

Flex Performance システムをプロビジョンする前に、予測されるストレージとコンピュート・コアを調整して、選択内容を送信します。
{: shortdesc}

システムがプロビジョンされた後、必要性が変わったときはいつでも、コンピュート・コアを上下に調整し、ストレージを増やすことができます。RAM は、コンピュート・コアの数が変更されると、比例して割り当てられます。コンピュート・コアが変更されると、短いシステム・ダウン時間が発生します。都合のよい時間にダウン時間が発生するようにスケジュールを設定したり、コンピュート・コアの変更を直ちに開始したりできます。ストレージの変更ではダウン時間は発生しません。 