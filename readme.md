# サッカー情報管理システム
## プロジェクトの概要
このシステムでは  **<br>以下の内容を管理します。**
- チームリスト
 1. Jリーグ
1. 欧州リーグ
- 選手リスト
- 試合結果

## ページ構成
| url | 内容 | HTMLファイル |
|-----|------|-------------|
| /home |ホーム | HomeServlet | index.jsp|
| /home |チーム紹介 | TeamServlet | list.jsp|
| /login |ログイン | HomeServlet | login.jsp|

### domainクラスの例
'''java
@Date
public class Team {
privae Integer id;
private String id;
}