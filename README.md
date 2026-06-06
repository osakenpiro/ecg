# ECG — 帝国運用カードゲーム

**▶ Play: https://osakenpiro.github.io/ecg/**

74枚のカードで帝国を運用するカードゲーム。単一HTML・オフライン可（file://直開きOK）・localStorage継戦。

- vs CPU / ホットシート2P
- デッキ構築（初期10+サプライ20・同名2枚まで・勢力プリセット3種: Viking/Knight/Samurai）
- ターン: 待機→メイン→精算→獲得。兵站・押し出し・循環・Burst(資源clamp)・英雄Scale(人気H閾値Tier)
- タイトル画面に神話残篇1句（パエトン/ナルキッソス/アラクネ/オルフェウス）

## 開発
開発正本は `workspace/ecg/`（このrepoは配布のみ）。`src/` 4ファイル → `node tools/build_ecg.cjs` で単一HTML再合成、`node tools/sim_test.cjs` = 単体26+opカバレッジ32種+AI対AI270戦ハーネス。カード正本=cards.v220.json（74枚/op語彙29種・v2.20仕様準拠）。

#全人類UX改善計画 — © osakenpiro
