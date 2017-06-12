---

copyright:
  years: 2014, 2017
lastupdated: "2017-02-10"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# {{site.data.keyword.objectstorageshort}} インスタンスのアンバインドおよびプロビジョン解除 {: #deprovisioning-object-storage}

{{site.data.keyword.objectstorageshort}} サービスが Cloud Foundry アプリにバインドされているが、ストレージはもう必要ない場合は、インスタンスをアンバインドし、プロビジョン解除することができます。
{: shortdesc}


## インスタンスのアンバインド

保存されたデータを維持し、Cloud Foundry アプリからサービスをアンバインドできます。{{site.data.keyword.objectstorageshort}} アカウントは、サービスがプロビジョン解除されるまで削除されません。

**注意**: {{site.data.keyword.objectstorageshort}} インスタンスを {{site.data.keyword.Bluemix_notm}} アプリケーションからアンバインドした場合、または、サービス・キーを削除した場合は、そのインスタンスのすべての資格情報が削除され、復元できません。インスタンスを再バインドするか、または新しいサービス・キーを作成することによって、新しいクラウド資格情報を生成できます。

1. アプリにバインドされているサービスを表示するには、Cloud Foundry アプリケーション内の「接続」タブをクリックします。
2. アンバインドするサービスを見つけて、サービス・タイルのメニュー・ボタンをクリックします。
3. **「サービスのアンバインド」**を選択します。
4. **「サービス・インスタンスの削除」**ボックスをクリアし、**「OK」**をクリックします。
5. **「再ステージ」**をクリックして、変更を有効にします。



## インスタンスのプロビジョン解除

不要になった {{site.data.keyword.objectstorageshort}} のインスタンスがある場合は、そのインスタンスを削除することができます。

**注意**: {{site.data.keyword.objectstorageshort}} インスタンスをプロビジョン解除すると、クラウド・プロジェクトおよび Swift アカウントが削除されます。プロビジョン解除されたインスタンス内のすべてのコンテナーおよびオブジェクトが削除され、復元できません。

1. アプリにバインドされているサービスを表示するには、Cloud Foundry アプリケーション内の「接続」タブをクリックします。
2. プロビジョン解除するサービスを見つけて、サービス・タイルのメニュー・ボタンをクリックします。
3. **「サービスの削除」**を選択します。
4. **「削除」**をクリックして、確認します。
5. **「再ステージ」**をクリックして、変更を有効にします。