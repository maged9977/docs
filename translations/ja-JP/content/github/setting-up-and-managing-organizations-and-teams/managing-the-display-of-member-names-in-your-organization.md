---
title: Organization のメンバー名表示を管理する
intro: Organization のプライベートリポジトリ内において、Organization のメンバーが、コメント作者のプロフィール名を表示できるよう許可することができます。
product: '{{ site.data.reusables.gated-features.display-names }}'
redirect_from:
  - /articles/managing-the-display-of-member-names-in-your-organization
versions:
  free-pro-team: '*'
  enterprise-server: '>=2.18'
---

Organization のオーナーは、Organization 内のメンバー名表示を管理できます。

![コメントに表示されたコメント作者の名前](/assets/images/help/issues/commenter-full-name.png)

Organization の各メンバーは、自分のプロフィール名を設定で選択します。 詳細は「[プロフィールをパーソナライズする](/github/setting-up-and-managing-your-github-profile/personalizing-your-profile#changing-your-profile-name)」を参照してください。

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.member-privileges }}
5. [Admin repository permissions] の下で、[**Allow members to see comment author's profile name in private repositories**] を選択または選択解除します。 ![プライベートリポジトリ内で、コメント作者のフルネームを表示することをメンバーに許可するためのチェックボックス](/assets/images/help/organizations/allow-members-to-view-full-names.png)
6. [**Save**] をクリックします。