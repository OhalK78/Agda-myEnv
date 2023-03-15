# Agda + Docker + VSCode

DockerでAgdaの実行環境を用意し、VSCodeのDev ContainersでAgda-modeプラグインを使用する。

debianの環境にapt-getでagdaを入れているだけ。

# 使用方法

VSCodeにて、Open a Remote Window→Reopen in Container

初回のみBuildを行う。

起動後、hello.agdaを開いて、C-C,C-L(C-はCtrlを押しながらと言う意味)でloadできる。