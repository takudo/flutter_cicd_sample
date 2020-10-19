# flutter_cicd_sample

## これはなに？

flutter プロジェクトにおける、実用的なCI/CD環境のサンプルです。

このプロジェクトでは以下の実行が可能です。

- ユニットテスト実行（ローカル環境）
- インテグレーションテスト（エミュレータ or 実機テスト）（ローカル環境）
- codemagic での ユニットテスト実行
- codemagic での インテグレーションテスト実行
    - エミュレーター
    - 実機（AWS Device farm）
- codemagic での ビルド

今後のTODOとしては下記です。

- deploygate での配布（ローカル環境）
- codemagic x deploygate を通じた配布
