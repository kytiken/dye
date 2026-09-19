# AGENTS.md

## Git Commit Messages

git commitする際は Conventional Commits に従うこと。

形式: `<type>[optional scope]: <subject>`

- `feat`: 新機能
- `fix`: バグ修正
- `docs`: ドキュメントのみの変更
- `style`: フォーマット等、動作に影響しない変更
- `refactor`: 挙動を変えないコードの再構成
- `perf`: パフォーマンス改善
- `test`: テストの追加・修正
- `build`: ビルドシステムや外部依存関係の変更
- `ci`: CI設定・スクリプトの変更
- `chore`: 上記に当てはまらないその他の変更
- `revert`: 以前のコミットの取り消し

破壊的変更を含む場合は、`<type>`の後に`!`を付けるか、フッターに`BREAKING CHANGE:`を記載する。

