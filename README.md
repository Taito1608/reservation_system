# reservation_system

大学内教室予約管理システム

## 使用言語
<img src="https://img.shields.io/badge/-Java-007396.svg?logo=java&style=plastic">

## 概要
本プロジェクトは大学内講義にて作成した、大学内教室予約管理システムである。総合開発環境はEclipseを利用し、データベースは開発者のPC上に構築する形で実装を行なっている。

主な機能
- ログイン・ログアウト機能
- 教室概要表示機能
- 新規予約機能
- 教室予約状況確認機能
- 自己予約状況確認機能
- 予約キャンセル機能

## ディレクトリ構成
```
.
├── reservation/
│   └── src/
│       └── client_system/
│           ├── CancelReservationDialog.java
│           ├── ChoiceFacility.java
│           ├── ChoiceHour.java
│           ├── ChoiceMinute.java
│           ├── ConfirmCancelReservationDialog.java
│           ├── GetReservationDialog.java
│           ├── LoginDialog.java
│           ├── MainFrame.java
│           ├── ReservationControl.java
│           ├── ReservationDialog.java
│           └── ReservationSystem.java
├── .classpath
├── .gitignore
├── .project
└── README.md
```
