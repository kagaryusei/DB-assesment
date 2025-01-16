System_diagram.pdf：Webアプリケーションのシステム構成図
Persona.pdf：ペルソナ定義
Story_board.pdf：ストーリーボード
UI_mock.pdf：UIモック
ER図.pdf：RDBのER図
Demo_video_supplement.txt：デモ動画の補足資料
Demo_video_URL.txt：アプリケーションのデモ動画がアップロードされているギガファイル便のURL
Infra, Application, DBA：アプリケーションを実行するのに必要なファイルが揃ったディレクトリ

＜ディレクトリ構成図＞
DB-assesment
├─ Architect
│   └─ System_diagram.pdf
├─ Business_Analyst
│   ├─ Persona.pdf
│   ├─ Story_board.pdf
│   └─ UI_mock.pdf
├─ DBA
│   └─ ER図.pdf
├─ Sprint_Review
│   ├─ Demo_video_supplement.txt
│   └─ Demo_video_URL.txt
└─ Infra, Application, DBA
    ├─ docker
    │   ├─ mysql
    │   │   ├─ data
    │   │   └─ Dockerfile
    │   └─ php
    │       └─ Dockerfile
    ├─ src
    │   ├─ album
    │   │   └─ OIP.jpg
    │   ├─ includes
    │   │   └─ login.php
    │   ├─ info.txt
    │   ├─ album.php
    │   ├─ bbs.php
    │   ├─ delete.php
    │   ├─ index.php
    │   ├─ info.php
    │   ├─ login.php
    │   ├─ logout.php
    │   ├─ navbar.php
    │   ├─ resize.php
    │   ├─ upload.php
    │   └─ write.php
    └─ docker-compose.yml
