The CCN Roadshow(Dev Track) Module 3 Guide 2019
===
このモジュールでは、開発者は Istio サービスメッシュを既存のクラウドネイティブアプリケーションと統合し、Kiali, Prometheus, Grafana などを介して機能を監視することができます。
また、Red Hat Application Runtimes の Red Hat Single Sign-On サーバーを介してクラウドネイティブアプリを認証する方法も学習します。

アジェンダ
===
* サービスメッシュの使用開始
* 継続的なデリバリーの実装
* 分散サービスの作成
* サービスの可視化と監視
* 高度なサービスメッシュ開発

OpenShift上でのラボインストラクション
===

APB経由でラボインストラをインストールした場合、ラボインストラクションはすでにデプロイされていることに注意してください。

_Migration_: ドキュメントはmarkdownからadocにマイグレーション済みです。 
Using pandoc e.g: 
``` 
for i in *.md; do pandoc --standalone --to=asciidoc --output=$i.adoc $i; done;
```