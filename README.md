# tl500-info

## OpenShiftとのネットワーク接続設定

Workstation内でターミナルを開き、以下のコマンドを実行します。

```
[student@workstation ~]$ cd /home/student/
[student@workstation ~]$ sudo ./set_tl500_network.sh --ip=10.82.1.46

```

## リンク集
### 共通
* [TL500 Technical Foundation Workbook(HTML)](http://tl500-docs-ja-tl500-tech-exercise.apps.ocp4.example.com/TL500.html)
* [OpenShift Web Console](https://console-openshift-console.apps.ocp4.example.com)
* [GitLab Server](https://gitlab-ce.apps.ocp4.example.com)

### PetBattle (team1の場合)
* [PetBattle] (https://console-openshift-console.apps.ocp4.example.com/topology/ns/team1-test)
* [CI/CD Pipeline] (https://console-openshift-console.apps.ocp4.example.com/dev-pipelines/ns/team1-ci-cd)

### インフラ (team1の場合)
* [ArgoCD UI] (https://argocd-server-team1-ci-cd.apps.ocp4.example.com)
* [SonarQube UI] (https://sonarqube-team1-ci-cd.apps.ocp4.example.com)
  * ユーザー名: admin, パスワード: admin123
* [Allure UI] (https://allure-team1-ci-cd.apps.ocp4.example.com/allure-docker-service/projects/pet-battle-api/reports/latest/index.html)




