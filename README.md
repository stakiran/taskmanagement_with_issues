# taskmanagement_with_issues

## 締切
[Milestone](https://github.com/stakiran/taskmanagement_with_issues/milestones) を使う。YYYY/MM/DD という名前の Milestone を、「締切日が YYYY/MM/DD である」という属性として利用し、Issue に設定する。

## 親子関係
小タスク内から親タスクに `#6` のようにして言及してやると、親タスク側から「小タスクから参照されたよ」と表示されるので依存関係を擬似的に表現できる。これを使えば簡易的な親子関係が実現できなくもない……。

- [親タスク](https://github.com/stakiran/taskmanagement_with_issues/issues/6)
  - [小タスク1](https://github.com/stakiran/taskmanagement_with_issues/issues/7)
  - [小タスク2](https://github.com/stakiran/taskmanagement_with_issues/issues/8)

## 優先度
各優先度のタスク一覧:

- [優先度:低のタスク一覧](https://github.com/stakiran/taskmanagement_with_issues/issues?q=is%3Aopen+is%3Aissue+label%3A%2200%E5%84%AA%E5%85%88%E5%BA%A6%3A+%E4%BD%8E%22)
- [優先度:中のタスク一覧](https://github.com/stakiran/taskmanagement_with_issues/issues?q=is%3Aopen+is%3Aissue+label%3A%2201%E5%84%AA%E5%85%88%E5%BA%A6%3A+%E4%B8%AD%22)
- [優先度:高のタスク一覧](https://github.com/stakiran/taskmanagement_with_issues/issues?q=is%3Aopen+is%3Aissue+label%3A%2202%E5%84%AA%E5%85%88%E5%BA%A6%3A+%E9%AB%98%22)

タスク新規時に優先度ラベル付けるのを忘れないようにする:

- [ISSUE_TEMPLATE.md](https://github.com/stakiran/taskmanagement_with_issues/blob/master/.github/ISSUE_TEMPLATE.md) に「優先度付けて！」と書いとく
