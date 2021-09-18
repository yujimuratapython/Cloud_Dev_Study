# チーム開発感ある環境を整える（暇だったら）
# 最初にやること
# Githubのアカウント作成 
- 参考:https://www.sejuku.net/blog/73468
- gitインストール- https://git-scm.com/
# VSCodeインストール 
- https://azure.microsoft.com/ja-jp/products/visual-studio-code/
- 参考github連携：https://breezegroup.co.jp/202102/vscode-github-windows/
- 参考Docker連携：https://qiita.com/Yuki_Oshima/items/d3b52c553387685460b0
# Dockerインストール
- https://www.docker.com/
- 参考：https://www.pasonatech.co.jp/workstyle/column/detail.html?p=2675
- 使ってるイメージファイル：https://hub.docker.com/r/jupyter/datascience-notebook/tags?page=1&ordering=last_updated
- 　補足：DockerがBIOSうんたらかんたらで起動しない場合。https://mrkmyki.com/docker%E3%82%92%E8%B5%B7%E5%8B%95%E3%81%97%E3%82%88%E3%81%86%E3%81%A8%E3%81%97%E3%81%9F%E3%82%89%E3%80%8Chardware-assisted-virtualization-and-data-execution-protection-must-be-enabled-in-the-bios
- 　ちなみに、AMDのCPUの場合BIOS設定でSVMをEnableにすると動くかもしれないし動かないかもしれない。

# 上記インストールが終わったら、下記参考ページ
- Docker + VSCode + Remote Containerで作る快適Jupyter Lab(Python)分析環境
- https://qiita.com/sho-hata/items/02ad47f67bce6816a69a
- VSCode Remote Containerが良い
- https://qiita.com/d0ne1s/items/d2649801c6f804019db7
- docker-compose.yml の内容を理解しよう（Dockerで作るコンテナの設定ファイル）
- https://futureys.tokyo/lets-understand-contents-of-docker-compose-yml/
- dockerfileの作り方
- https://kitsune.blog/dockerfile-summary
- Python, pipでrequirements.txtを使ってパッケージ一括インストール
- https://note.nkmk.me/python-pip-install-requirements/
